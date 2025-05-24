# Supported Executors
- [x] Delta
- [x] Fluxus
- [x] Swift
- [x] Velocity 
- [ ] KRNL
   - It initializes but leads to crash when script tries to decompile or save the place since it doesn't has Workspace support afaik.
- [x] Other Executors

# Loadstring
*Paste the lines at the bottom to your executor.*

```lua
local synsaveinstance = loadstring(game:HttpGet("https://raw.githubusercontent.com/P0L3NARUBA/UniversalSynSaveInstance-Mod/refs/heads/main/saveinstance.luau", true), "saveinstance")();
local SaveinstanceOptions = {}
synsaveinstance(SaveinstanceOptions);
```

# Options (W.I.P)
Heres the options that you can use it to set how decompiler works.<br>
You need to put these options inside the curly braces of **SaveinstanceOptions** by the way.

- noscripts=*bool* (true, false)
  - This will only save the map and not the scripts.
- usekonstantdecompiler=*bool* (true, false)
  - This will use the Konstant Decompiler for Scripts (Recommended)
- **Coming soon...**
