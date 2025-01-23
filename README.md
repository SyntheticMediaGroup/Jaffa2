# Jaffa2
> [!note]
> This modpack REQUIRES the Prism Launcher. MultiMC will no longer be supported. If you wish to retain your old instances, [a migration guide is available](https://prismlauncher.org/wiki/getting-started/migrating-multimc/) and is quick and easy to follow.

This is mostly a mirror of https://www.curseforge.com/minecraft/modpacks/jaffa-factory-2-replica with a handful of changes to allow for running a server. In addition, this has a handful of server management mods added in, removes bloated malware like Essential
and adds feature mods like CC: Tweaked, and Mine Colonies. 

# Installation

## Installing Java
> [!tip]
> The latest versions of Prism Launcher support automatic installation of Java. Only follow these steps if you get an error, or are using an old version of Prism Launcher. 
1. Download the [latest version of Java 17](https://adoptium.net/temurin/releases/?package=jdk&version=17).
2. This will vary depending on which operating system you use.
   1. If you're running **Windows**, select the **.msi** file and install it.
   2. If you're running **MacOS**:
      1. Select the **.pkg** file for **aarch64** if you're running **Apple Silicon** (aka M1/M2/M3).
      2. Select the **.pkg** file for the **x64** version if you're running an **Intel** Mac.
   3. If you're running **Linux**: figure it out.

## Installing the Prism Launcher
1. Head to the Prism Launcher [download page](https://prismlauncher.org/download?from=button).
2. Download the version the corresponds to the device you're using.
3. Install the downloaded file.
## Logging Into Prism Launcher
1. Click `Settings` from the top bar
2. Select `Accounts` along the side
3. Click `Add Microsoft` or `Add Mojang` depending on which account type you have.
4. Follow the on-screen instructions
5. Click `Close`
## Installing the Pack
1. Click `Add Instance`, then `Import from ZIP`
2. Paste the following link into the text box: https://github.com/SyntheticMediaGroup/Jaffa2/releases/download/1.0.0/Jaffa2.zip
3. Select `Ok`
4. Wait for the pack to be installed then press `Launch`.

If you receive an error along the lines of:
`The java binary "" couldn't be found. Please fix the java path override in the instance's settings or disable it.`

1. Select `Edit` from the sidebar (right side of screen).
2. Select `Settings` from the sidebar (left side of screen).
3. Under `Java Installation`, select `Auto-detect...` and pick version 17.x.x.

# Server Installation
1. Download the [`packwiz_installer_bootstrap.jar`](https://github.com/packwiz/packwiz-installer-bootstrap/releases)
2. Copy it to the folder where you wish to install the server.
3. Run the following command
   ```bash
   java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/SyntheticMediaGroup/Jaffa2/refs/heads/main/pack.toml
   ```
4. Install [Minecraft Forge 1.20.1 version 47.3.0](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.20.1.html).
4. Launch the server using the script(s) provided by Forge.
   
