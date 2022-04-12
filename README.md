# Installing BetterDiscord

1. Download the installer from [https://betterdiscord.app](https://betterdiscord.app/)
2. Run the installer.

> **:warning: Installing on macOS**  
> You may see a warning popout running the installer. Simply press the `?` icon in the top right corner of the popout, then follow the instructions to allow the file.

[Video: Installing BetterDiscord](https://user-images.githubusercontent.com/90428263/163029485-d7421b5a-9e89-40ee-b853-566181062d59.mp4)

# Manual Install 

## (Windows)

1. Install **Git** and **Node.js**. Other versions may not work.
   - [https://github.com/git-for-windows/git/releases/download/v2.34.1.windows.1/Git-2.34.1-64-bit.exe](https://github.com/git-for-windows/git/releases/download/v2.34.1.windows.1/Git-2.34.1-64-bit.exe)
   - [https://nodejs.org/dist/v16.13.1/node-v16.13.1-x64.msi](https://nodejs.org/dist/v16.13.1/node-v16.13.1-x64.msi)
2. Open **Command Prompt** (Not in Admin)
3. Copy/paste the simplified command:

   - `git clone https://github.com/BetterDiscord/BetterDiscord.git && cd ./BetterDiscord/ && npm install && npm run build && npm run inject`

Individual commands if the simplified command fails:
1. `git clone https://github.com/BetterDiscord/BetterDiscord.git`
2. `cd ./BetterDiscord/`
3. `npm install`
4. `npm run build`
5. `npm run inject`

Add `PTB` or `Canary` to `npm run inject` for non-stable clients = `npm run inject canary`

[Video: Installing Manually](https://user-images.githubusercontent.com/90428263/162848023-9816afe8-8e77-44b5-afe2-054fd9131700.mp4)

____

## (macOS)

1. Install **Git** and **Node.js**. Other versions may not work.
   - [https://git-scm.com/download/mac](https://git-scm.com/download/mac)
   - [https://nodejs.org/dist/v16.13.1/node-v16.13.1.pkg](https://nodejs.org/dist/v16.13.1/node-v16.13.1.pkg)
2. Open **Terminal** (using ⌘Command + spacebar and type in "Terminal")
3. Copy/paste the simplified command:

   - `git clone https://github.com/BetterDiscord/BetterDiscord.git && cd ./BetterDiscord/ && npm install && npm run build && npm run inject`

Individual commands if the simplified command fails:
1. `git clone https://github.com/BetterDiscord/BetterDiscord.git`
2. `cd ./BetterDiscord/`
3. `npm install`
4. `npm run build`
5. `npm run inject`

Add `PTB` or `Canary` to `npm run inject` for non-stable clients = `npm run inject canary`
