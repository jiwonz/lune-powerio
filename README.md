# lune-powerio
PowerShell powered I/O library for Lune

## Installation
Use git submodule.
```sh
git submodule add
```

## Usage
```lua
local filePaths = powerio.promptFile({
	{ name = "Roblox Model Files", extensions = { "rbxm" } }
})

local answer = powerio.promptMessageBox("Title", "Message", "YesNo", "Information")

```

## TODO
- [ ] Support environments without powershell
