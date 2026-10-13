> [!IMPORTANT]
> You'll have to [build from source](https://docs.vencord.dev/installing/) to add custom plugins<br/>
> Check out https://docs.vencord.dev/installing/custom-plugins for more info<br/>
> 

## Install
1. Create `userplugins` folder inside your `src` folder (read the guide above if you're confused, or ignore this step if you already have one)
2. Open the terminal and run these commands inside the `src` folder:
```bash
cd userplugins
git clone https://github.com/lastfpvp/iDontLikeU
pnpm build
```
3. Launch your Discord and head up to Settings > Plugins > Filters > Show UserPlugins, search for the plugin and enable it.

> [!NOTE]
> You can read the [Official Install Guide](https://discord.com/channels/1015060230222131221/1257038407503446176) on [Vencord's Discord Server](https://discord.gg/vencord)

## Update
To update the plugin, use the following commands:
```bash
cd src/userplugins/iDontLikeU
git pull
```
