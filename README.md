# bonsec
A Powerful Lua Obfuscator.

**Usage**\
Add BonSec:
```lua
local bonsec = loadstring(game:HttpGet("https://raw.githubusercontent.com/realbxnnie/bonsec/refs/heads/main/main.lua"), true)()
```
Obfuscate code: 
```lua
local obfc = bonsec.obf("print('Hello, BonSec!')")
```

Run obfuscated code:
```lua
local obfc = bonsec.obf("print('Hello, BonSec!')")
loadstring(obfc)()
```

Copy obfuscated code to clipboard:
```lua
local obfc = bonsec.obf("print('Hello, BonSec!')")
setclipboard(tostring(obfc))
```
