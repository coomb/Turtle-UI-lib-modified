# Basically how this thing works

--[[
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/coomb/Turtle-UI-lib-modified/refs/heads/main/MainLib"))()

local UI = library:Window("Window")

Button("Button name", BackgroundColor, BorderColor, function()

Toggle("Example toggle", true, ToggleDotColor, BackgroundColor, BorderColor, function(bool)

ColorPicker("Color Picker", Color3.fromRGB(255, 255, 255), function(color)

Slider("Example Slider",0,100,20, SliderFillColor, BackgroundColor, BorderColor, function(value)

Label("Credits to Intrer#0421", BackgroundColor, BorderColor, Color3.fromRGB(127, 143, 166))

Box("Walkspeed", BackgroundColor, BorderColor, function(text, focuslost)

local dropdown = Lib:Dropdown("Example dropdown", BackgroundColor, BorderColor, {"Button 1", "Button 2", "Third button"}, function(name)
   print(name)
end)

dropdown:Button("New button")

dropdown:Remove("Button")
]]
