---
description: >-
  This guide explains how to set up a modded Minecraft server and how to install
  the required mods on your computer.
---

# 🖥️ Playing with Mods (NeoForge / Forge)

## Choosing a Modded Server Version

1. Go to the **Fire Hosting control panel**
2. Select your **Minecraft server**
3. Open the tab used to **change the server version / software**
4. Choose a modded server type:
   * **Forge**
   * **NeoForge**

For this example, we will use **NeoForge**.

5. Select the **NeoForge version** that matches your Minecraft version (e.g. **Minecraft 1.21.1 – NeoForge**)
6. Confirm the installation

The panel will now **install NeoForge automatically**.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>



## First Server Start (Initialization)

1. Start the server **once** by clicking **Start**
2. Let the server fully start
   * This step is required to initialize files and folders
3. Once started, **stop the serve**



## Accessing the Mods Folder

1. Go to the **Files** tab in the panel
2. You will see several folders created automatically
3. Open the folder named:

`mods`

This is where all server mods must be placed.



## Downloading Mods

You now need to choose mods that are **compatible** with:

* The **Minecraft version** (example: 1.21.1)
* The **mod loader** (**NeoForge** in this example)

Recommended websites:

* [**Modrinth**](https://modrinth.com/discover/mods)
* [**CurseForge**](https://www.curseforge.com/minecraft/search?class=mc-mods)

⚠️ Always check that the mod supports **NeoForge** and the correct Minecraft version.



## Installing Mods on the Server

1. Download the mods you want
2. Make sure the files are in **.jar** format
3. Upload or drag-and-drop the **.jar files** into the server's `mods` folder
4. Once all mods are uploaded, **start the server** again

The server will now load the installed mods.



## Installing NeoForge on Your Computer (Client)

To join a modded server, you **must have the same mod loader and mods installed on your PC**.

***

### Step 1: Download NeoForge

1. Go to the official **NeoForge** website
2. Download the **installer** for your Minecraft version (example: 1.21.1)

***

### Step 2: Install NeoForge

1. Open the downloaded NeoForge installer
2. Select **Install Client**
3. Choose your Minecraft directory (default is recommended)
4. Click **Install**

Once installed, a new NeoForge profile will be available in your Minecraft launcher.

***

### Step 3: Install Mods on Your PC

1. Open your Minecraft directory:
   * Windows: `%appdata%/.minecraft`
   * Linux: `~/.minecraft`
   * macOS: `~/Library/Application Support/minecraft`
2. Open (or create if it does not exist) the folder:

mods

3. Copy the **exact same mods (.jar files)** that are on the server into this folder

⚠️ The **mods must match** the server:

* Same mod loader (NeoForge)
* Same Minecraft version
* Same mods and versions

***

#### Step 4: Launch Minecraft and Join the Server

1. Open **Minecraft Launcher**
2. Select the **NeoForge profile**
3. Click **Play**
4. Go to **Multiplayer**
5. Join your Fire Hosting server

***

✅ You are now playing on a **modded Minecraft server** with NeoForge on **Fire Hosting**.
