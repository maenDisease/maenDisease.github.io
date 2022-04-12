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

[Video of Manual Install](https://user-images.githubusercontent.com/90428263/162848023-9816afe8-8e77-44b5-afe2-054fd9131700.mp4)

____

## (MacOS)

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
