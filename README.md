[![EssentialsX](https://i.imgur.com/CP4SZpB.png)](https://essentialsx.github.io)

This is a fork of EssentialsX called EssentialsXOptimized.

If you are using this, do **NOT** ask Essentials for support.

The official upstream repository is at https://github.com/EssentialsX/Essentials.


Why use EssentialsXOptimized?
--------

EssentialsXOptimized is an unofficial continuation of EssentialsX to improve the performance and overall make the plugin better to use for server admins and players alike. (https://essentialsx.github.io/#/Improvements)

EssentialsXOptimization is almost a completely drop-in replacement for EssentialsX. However, it has different requirements:

* **EssentialsXOptimized requires [Vault](http://dev.bukkit.org/bukkit-plugins/vault/) to enable chat prefix/suffixes and group support if you have a supported permissions plugin.** We recommend using [LuckPerms](https://luckperms.github.io).

* **If you have an unsupported permissions plugin but still wish to use wildcards, enable `use-bukkit-permissions` in the configuration.** Otherwise, the plugin will fall back to config-based permissions.

* **EssentialsXOptimized requires Java 8 or higher.** On older versions, the plugin may not work properly.

* **EssentialsXOptimized supports Minecraft versions 1.8.8, 1.9.4, 1.10.2, 1.11.2, 1.12.2, 1.13.2 and 1.14.4.**

Building
--------

EssentialsXOptimized builds against the Spigot/CraftBukkit server software for legacy support.

To compile EssentialsXOptimized, you first need to run [BuildTools](https://www.spigotmc.org/wiki/buildtools).
This only needs to be done once. There are two ways to do this:

* Use the provided script at `scripts/buildtools.sh` to automatically download and run BuildTools if needed.
* Download and run BuildTools yourself for versions `1.8` and `1.8.3`.

Next, to build EssentialsX with Maven, run the following command:
```
mvn clean install
```

Each module's jar can be found in `target/` inside each module's directory.


Contributing
------------

Want to help improve EssentialsX? There are numerous ways you can contribute to the project.

If you'd like to make a financial contribution to the project, you can join our [Patreon](https://www.patreon.com/essentialsx/).
If you can't make a donation, don't worry! There's lots of other ways to contribute:

* Do you run a server? Take a look at our ["help wanted" issues](https://github.com/EssentialsX/Essentials/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22help+wanted%22),
  where you can find issues that need extra testing and investigation. You can also join the [MOSS Discord community](https://discord.gg/casfFyh)
  and provide support to others.
* Do you speak multiple languages? If so, we always welcome contributions to our [Crowdin project](https://crowdin.com/project/essentialsx-official).
* If you're a developer, you could look through our ["open to PR" issues](https://github.com/EssentialsX/Essentials/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22status%3A+open+to+PR%22).
  We're always happy to receive bug fixes and feature additions as pull requests.
