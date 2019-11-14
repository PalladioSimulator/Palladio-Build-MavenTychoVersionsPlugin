# Palladio-Build-MavenTychoVersionsPlugin

This plugin provides the same capabilities as the set-version goal of the tycho-versions-plugin. For documentation, please refer to the [official documentation](https://www.eclipse.org/tycho/sitedocs/tycho-release/tycho-versions-plugin/set-version-mojo.html).

We introduced a new parameter `ignoreVersionMismatch` that can be set to true or false (default). If set to true, the plugin will update versions no matter if the existing version matches the version of the project on which the goal is triggered.