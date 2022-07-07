local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "UNLIMITEDOMAIN", HidePremium = false, IntroText = "UNLIMITEDOMAIN", SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "OPL",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = true
})

local Section = Tab:AddSection({
	Name = "OnePieceLegendary"
})
 
OrionLib:MakeNotification({
	Name = "Welcome Back Unlimited!",
	Content = "What Script Will You Use Today?",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddButton({
	Name = "TurtleHub",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/toaie0112/Turtle-Hub/main/OPL'))()


      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "TurtleScript",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/AltsegoD/script/master/OnePieceLegendary.lua'))()


      		print("button pressed")
  	end    
})

local Tab = Window:MakeTab({
	Name = "AHD",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = true
})

local Section = Tab:AddSection({
	Name = "AHerosDestiny"
})

Tab:AddButton({
	Name = "KillEveryBoss",
	Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Suricato006/Scripts-Made-by-me/master/Scripts/RandomScripts/A%20Hero%20Desiny/KillEveryBossOnce.lua'))()


      		print("button pressed")
  	end    
})

local Tab = Window:MakeTab({
	Name = "EGG",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = true
})

local Section = Tab:AddSection({
	Name = "ElementalGrindGame"
})

Tab:AddButton({
	Name = "AutoFarm&AutoSpin",
	Callback = function()Tab:AddButton({
        Name = "KillEveryBoss",
        Callback = function()loadstring(game:HttpGet('https://raw.githubusercontent.com/Suricato006/Scripts-Made-by-me/master/Scripts/RandomScripts/A%20Hero%20Desiny/KillEveryBossOnce.lua'))()
    
    
                  print("button pressed")
          end    
    })

      		print("button pressed")
  	end    
})

OrionLib:Init()
