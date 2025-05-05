# Basically how this thing works

local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/coomb/Turtle-UI-lib-modified/refs/heads/main/MainLib"))()

local UI = library:Window("Window", BarColour, LineColour, BackgroundColour)

UI:Button("Button name", BackgroundColor, BorderColor, function()

UI:Toggle("Example toggle", true, ToggleDotColor, BackgroundColor, BorderColor, function(bool)

UI:ColorPicker("Color Picker", Color3.fromRGB(255, 255, 255), function(color)

UI:Slider("Example Slider",0,100,20, SliderFillColor, BackgroundColor, BorderColor, function(value)

UI:Label("Credits to Intrer#0421", BackgroundColor, BorderColor, Color3.fromRGB(127, 143, 166))

UI:Box("Walkspeed", BackgroundColor, BorderColor, function(text, focuslost)

local dropdown = UI:Dropdown("Example dropdown", BackgroundColor, BorderColor, {"Button 1", "Button 2", "Third button"}, function(name)
   print(name)
end)

dropdown:Button("New button")

dropdown:Remove("Button")
