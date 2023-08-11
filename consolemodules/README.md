# Console Modules

------

**DISCLAIMER: This is a prototype of a Graphical User Interface (GUI for short), this script only lets you use a smaller selection of functions**

------
## Documentation

------

**Booting up the Library**
```lua
local dhig = loadstring(game:HttpGet("https://raw.githubusercontent.com/Cilacs/Roblox/main/consolemodules/source.lua"))()
```
**Importing Modules**
```lua
dhig:import(moduleName <string>, returnModule <boolean>, instantImport <boolean>)
```
- moduleName
  - *found in Source Code*
  - *string*
- returnModule
  - *return Module as table (local t = dhig:import(...))*
  - *place Module inside of library (dhig.NAME.FUNCTION)*
  - *boolean*
- instantImport
  - *true: dhig.NAME.FUNCTION(...)*
  - *false: dhig.NAME(functionPosition <number>, ...)*
  - *boolean*
