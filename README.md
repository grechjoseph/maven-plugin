Plugin module: The custom plugin.
Plugin-Use module: Module making use of the plugin.

1. Create Plugin dependencies (refer to POM file).
2. Create Plugin Mojo/s.
3. <b>mvn clean install</b> plugin.

4. Import plugin in plugin-use POM file. (define phase to run in, and goal to run)
5. <b>mvn clean <phase to run plugin></b> to see the plugin working.
