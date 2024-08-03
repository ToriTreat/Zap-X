-- // Loadstring \\ -- 
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/LeadMarker/Kronos/main/KronosUI.lua"))()

-- // CreateWindow \\ --
local window = library:Window({
    <string> Title,
    <color3> Accent,
    <number> Logo,
    <keycode> ToggleKey
})

-- // NewTab \\ -- 
local tab = window:NewTab({
    <number> Logo
})

-- // TabSection \\ --
local tabsection = tab:TabSection({
    <string> Title
})

-- // NewColumn \\ --
local column = tabsection:AddColumn({
    <string> Title
})

-- // Section \\ -- 
local section = column:Section({
    <string> Title
})

-- // Button \\ -- 
local button = section:Button({
    <string> Text,
    <function> Callback
})
  
button:UpdateText(<string>)
  
-- // Toggle \\ -- 
local toggle = section:Toggle({
    <string> Text,
    <function> Callback,
    <bool> State 
})
    
toggle:SetState(<bool>)

-- // Textlabel \\ -- 
local textlabel = section:TextLabel({
    <string> Text
})
    
textlabel:Update(<string>)
    
-- // Divider \\ -- 
section:Divide({})
    
-- // Keybind \\ -- 
local keybind = section:Keybind({
    <string> Text,
    <keycode> Key
    <function> Callback
})
      
keybind:UpdateKey(<keycode>)
      
-- // Textbox \\ -- 
local textbox = section:Textbox({
    <string> Text,
    <function> Callback
})

textbox:Update(<string>)
        
-- // Dropdown \\ -- 
local dropdown = section:Dropdown(
    <string> Text,
    <table> List,
    <function> Callback
})
        
dropdown:UpdateList(<table>)
          
-- // Slider \\ -- 
local slider = section:Slider({
    <string> Text,
    <number> Min,
    <number> Max,
    <number> Def,
    <function> Callback
})
          
slider:UpdateSlider(<number>)
