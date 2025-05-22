# Loadstring
*Paste the lines at the bottom to your executor.*

```lua
local synsaveinstance = loadstring(game:HttpGet("https://raw.githubusercontent.com/verysigmapro/UniversalSynSaveInstance-With-Save-Terrain/refs/heads/main/saveinstance_rewrite.luau", true), "saveinstance")();
local SaveinstanceOptions = {}
synsaveinstance(SaveinstanceOptions);
```

# Options (W.I.P)
Heres the options that you can use it to set how decompiler works.<br>
You need to put these options inside the curly braces of **SaveinstanceOptions** by the way.

- noscripts= bool (true, false)
  - This will only save the map and not the scripts.
- usekonstantdecompiler= bool (true, false)
  - This will use the Konstant Decompiler for Scripts (Recommended)
- **Coming soon...**
