# Discord Library
## This is a Roblox Gui that look like discord i make it documentation the owner who make it is dawid here hes v3rm: https://v3rmillion.net/member.php?action=profile&uid=1052423

## Library
```lua
local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()
```




## Window
```lua
local win = DiscordLib:Window("DiscordLib")
```





## Tab
```lua
local serv = win:Server("Roblox Scripting", "")
```




## Button
```lua
btns:Button("Kill all", function()
print()
```




## Notification
```lua
DiscordLib:Notification("Tittle", "Message", "Option")
end)
```




## Seperator
```lua
btns:Seperator()
```



## Toogle
```lua
tgls:Toggle("Toogle",false, function(bool)
print(bool)
end)
```





## Slider
```lua
local sldr = sldrs:Slider("Slide me!", 0, 1000, 400, function(t)
print(t)
end)
```




## Dropdown
```lua
local drop = drops:Dropdown("Pick me!",{"Option 1","Option 2","Option 3","Option 4","Option 5"}, function(bool)
print(bool)
end)
```




## Colorpicker
```lua
clrs:Colorpicker("ESP Color", Color3.fromRGB(255,1,1), function(t)
print(t)
end)
```




## Textbox
```lua
textbs:Textbox("Tittle", "Type here!", true, function(t)
print(t)
end)
```





## Label
```lua
lbls:Label("Label")
```





## Bind
```lua
bnds:Bind("bind", Enum.KeyCode.RightShift, function()
print("BIND")
end)
```






## Server(idk this)
```lua
win:Server("Main", "http://www.roblox.com/asset/?id=6031075938")
```




