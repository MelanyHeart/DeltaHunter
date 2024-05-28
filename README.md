# HeartStrike
HeartStrike is an RPG server which can be self-hosted or modified to your hearts content. The server is primarily programmed using a plugin called Skript which features a very easy to understand programming language, as well as a couple other plugins for ease of development. 

Keep in mind, HeartStrike is not in a playable state yet. When there is stable version which includes some neat foundational features, then I'll  begin publishing releases here on GitHub.

As for now, there is a set of tools in place for easier development of items and other basic things. The server is intended to be played in offline mode so there is a login/passkey system in place to keep admin accounts secure... (At least, in future because right now the /totalreset command can be used from an operator's account without needing to be logged in.)

## Contact Me/The Community
Feel free to join the discord server  here : [__💙 Parliament of Owls 💙__](https://discord.gg/fQUzhGpf3a) if you'd like to ask for any help outside of GitHub.

# How to Play / Create Your Own Instance
Here are the steps to create and join your own instance of HeartStrike. Remember to keep calm during each process:

<details>

<summary>Downloading all the required files.</summary>

1. A version of [PaperMC for 1.20.4](https://papermc.io/downloads/paper). Set the file name to __`Paper.jar`__!
2. The world file can be downloaded from [Mega](__https://mega.nz/file/wjcWUBZQ#HOGV5RQ72fgFK7v4rxCvpaYn8HkmYBr1n93piov-Pco__).
3. The config and Skripts from here on GitHub by selecting `Code` then `Download ZIP`
4. The following plugins used during development:
    - OPTIONAL - [Freedom Chat](https://modrinth.com/plugin/freedomchat) (`Version 1.5.2`)
    - OPTIONAL  - [Via Version](https://github.com/ViaVersion/ViaVersion/releases) (`Version 4.10.2`)
    - OPTIONAL (Dev Tool) - [Fast Async World Edit](https://ci.athion.net/job/FastAsyncWorldEdit/) (`Version 2.9.2-SNAPSHOT-708`)
    - OPTIONAL (Dev Tool) - [WorldEditSelectionVisualizer](https://www.spigotmc.org/resources/worldeditselectionvisualizer-1-7-10-1-20-6.17311/) (`2.1.6`)
    - OPTIONAL (Dev Tool) - [Fancy Holograms](https://modrinth.com/plugin/fancyholograms/version/2.0.6)
    - [World Guard](https://dev.bukkit.org/projects/worldguard) (`Version 7.0.9`)
    - [Skript](https://github.com/SkriptLang/Skript/releases) (`Version 2.8.5`)
    - [SkBee](https://github.com/ShaneBeee/SkBee/releases) (`Version 3.5.0`)
    - OPTIONAL (Discort Integration) [DiSky](https://modrinth.com/plugin/disky/version/3utXU8e8) (`Version 4.12.2-beta1`)
    - [Skript Particle](https://github.com/sovdeeth/skript-particle/releases) (`Version 1.2.0`)
    - [Diskuise](https://github.com/UnderscoreTud/diskuise/releases) (`Version 0.3.4`)
    - [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) (`Version 5.2.0-SNAPSHOT-679`)
    - [Libs Disguises](https://github.com/libraryaddict/LibsDisguises/releases) (`Version 10.0.42-Free`)
    - [Citizens](https://ci.citizensnpcs.co/job/Citizens2/) (`Version 2.0.33-SNAPSHOT (build 3374)`)
    - [Mythic Mobs](https://mythiccraft.io/index.php?resources/mythicmobs.1/) (`Version 5.6.1`)
    - [Mythic Skript Addon](https://github.com/BerndiVader/MythicSkriptAddon/releases) (`Version 0.99.6`)
    - OPTIONAL (Dev Tool) - [Image on map](https://dev.bukkit.org/projects/imageonmap) (`Version 4.2.2`)
    - OPTIONAL - [Skins Restorer](https://www.spigotmc.org/resources/skinsrestorer.2124/) (`Version 15.0.7`)

</details>



<details>

<summary>Setting up HeartStrike.</summary>

1. Create a new folder to contain the all the server files.
2. Extract the `.ZIP` within the new folder.
3. Paste the `Paper.jar` file in the folder.
4. To start the server, you may double click or in a Terminal use a command such as `java -jar ~/path/to/Paper.Jar`.

</details>



<details>

<summary>How to update.</summary>

- The world:
    - Download the latest world file.
    - Unzip the world file and replace the old world folder with the new world folder.

- The scripts and config
    - Download the config and Skripts from here on GitHub by selecting `Code` then `Download ZIP`.
    - Unzip the file then drag and drop all the files into the server folder.
    - Your file manager will ask you what you'd like to do with the files. Just click on any option which says Replace.

- The plugins
    - Check the version of the plugin(s) to update. Do `/plugins` in the server, click on the plugin(s) to view their version.
    - In "Downloading all the required files", check if the plugin version is greater than the one you are using.
    - Follow the hyperlink (click on the plugin name) to conveniently go to the releases page of that plugin.

</details>
