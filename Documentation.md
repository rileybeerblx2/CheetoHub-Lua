# CheetoHub UI
This documentation is for CheetoHub UI Credit To The Owner

## Booting the CheetoHub UI Library
```lua
local Fun = loadstring(game:HttpGet("https://raw.githubusercontent.com/insanedude59/CheetoHub/main/newlib"))()
```




## Creating a CheetoHub UI Window
```lua
local a = Fun.Create('hi')
```

## Creating a Tab
```lua
local tab1 = a:Tab("hii")
```

## Creating a Section
```lua
local section1 = tab1:Section('section')
```

## Creating a Toggle
```lua
section1:Toggle("toggle",function(value)
    print(value)
end)
```

## Creating a Button
```lua
section1:Button("yoo",function()
    print("yoo")
end)
```

## Creating a Slider
```lua
section1:Slider("slider",16,50,function(value)
    num = value
    print(num)
end)
```

## Creating a Dropdown
```lua
section1:Dropdown("dropdown",{"hi","hi2","hi3"},function(val)
    print(val)
end)
```

## Creating a Text Label
```lua
section1:Label("textlabel")
```

## Creating a Textbox
```lua
section1:TextBox("textbox",function(text)
print(text)
end)
```

## Creating a Label
```lua
section1:Label('hello')
```
