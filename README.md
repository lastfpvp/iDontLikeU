> [!IMPORTANT]
> You'll need to build [Vencord](https://github.com/Vendicated/Vencord) first<br/>
> Check out https://docs.vencord.dev/installing/custom-plugins for more info<br/>
> 
> Also you'll need [Node.js](https://nodejs.org/en/download) and [Git](https://git-scm.com/install/windows) (if this is your first time)

## Tech Stack
- VS Code (Editor)
- Typescript/TSX
- Vencord's plugin API

## Install
1. Create `userplugins` folder inside your `src` folder (read the guide above if you're confused, or ignore this step if you already have one)
2. Open the terminal and run these commands inside the `src` folder:
```bash
cd userplugins
git clone https://github.com/lastfpvp/iDontLikeU
pnpm build
```
3. Launch your Discord and head up to Settings > Plugins > Filters > Show UserPlugins, search for the plugin and enable it.

## Update
To update the plugin, use the following commands:
```bash
cd src/userplugins/iDontLikeU
git pull
```
