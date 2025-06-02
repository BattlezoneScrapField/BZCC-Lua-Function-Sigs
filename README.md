### Requirements
- [Visual Studio Code](https://code.visualstudio.com/)
- [Sumneko's Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua)
  
### How to use the ScriptUtils API Definitions in your code
1. Download [battlezone2_defs.lua](https://github.com/BattlezoneScrapField/BZCC-Lua-Function-Sigs/blob/main/battlezone2_defs.lua "battlezone2_defs.lua") to any location on your PC (I recommend putting it somewhere you can easily remember E.G. Documents)
2. Open Visual Studio Code and Navigate to the Extensions Page
3. If necessary, install Sumneko's Lua Language Server
4. When installed, navigate to the `settings.json` file that comes with the extension which can be located in: `%appdata%\Code\User`.
5. Copy the following code: ```
```json
"Lua.workspace.library": ["<ADD LOCATION OF WHERE YOU SAVED BATTLEZONE2_DEFS.LUA>"],
```
6. Restart Visual Studio Code.

## Contact me 👋
Any issues? Feel free to hop in to Discord: 
<a href="https://www.discord.gg/a5g9tmdF">
  <img alt="Discord" title="Discord" src="https://custom-icon-badges.demolab.com/badge/-Discord-7289da?style=for-the-badge&logoColor=white&logo=discord&labelColor=40464a"/>
</a>
