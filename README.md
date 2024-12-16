local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "DeltaScripts - Blox Fruits GUI", HidePremium = false, SaveConfig = true, ConfigFolder = "dxl_bf"})

local Tab = Window:MakeTab({
	Name = "Scripts",
	Icon = "rbxassetid://11759193017",
	PremiumOnly = false
})

local Tab2 = Window:MakeTab({
	Name = "Fruit Finder",
	Icon = "rbxassetid://11759193017",
	PremiumOnly = false
})

Tab2:AddButton({
	Name = "BloxFruits/SpeedHub",
	Callback = function()
        repeat wait(5) until game:IsLoaded()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
  	end    
})

Tab:AddButton({
	Name = "BloxFruits/W-Azure",
	Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})

Tab:AddButton({
	Name = "Fisch/SpeedHub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
  	end    
})
