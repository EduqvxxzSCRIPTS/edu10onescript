local Tab = Window:MakeTab({
	Name = "Scripts",
	Icon = "rbxassetid://6403436082",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "BloxFruits: XeroHub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/verudous/Xero-Hub/main/main.lua"))()
  	end    
})

Tab:AddButton({
	Name = "BloxFruits: CokkaHub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/UserDevEthical/Loadstring/main/CokkaHub.lua"))()
  	end    
})

Tab:AddButton({
	Name = "BloxFruits: W-Azure",
	Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/3b2169cf53bc6104dabe8e19562e5cc2.lua"))()
  	end    
})
