local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "DeltaScripts - Blox Fruits GUI", HidePremium = false, SaveConfig = true, ConfigFolder = "dxl_bf"})

local Tab = Window:MakeTab({
	Name = "Scripts",
	Icon = "rbxassetid://6403436082",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Domadic Hub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
  	end    
})

Tab:AddButton({
	Name = "BloxFruits: CokkaHub",
	Callback = function()
        loadstring(game:HttpGet"https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/CokkaHub.lua")()
  	end    
})

Tab:AddButton({
	Name = "BloxFruits: W-Azure",
	Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})
