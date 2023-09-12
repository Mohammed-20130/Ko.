local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()local Window = OrionLib:MakeWindow({Name = "سكربت احلام العصر درجة اولى 🤤", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]local Tab = Window:MakeTab({
	Name = "👑 قائمة السكربتات 👑",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]local Section = Tab:AddSection({
	Name = "قائمة السكربتات"
})

--[[
Name = <string> - The name of the section.
]]Tab:AddButton({
	Name = "سكربت الطيران✈️",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://github.com/HUBSXOBOX/HUBSXOBOX/raw/main/Hussin%20Danis'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت الاختفاء👻",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://pastebin.com/raw/AYtzGEPb'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت مراقبة الناس",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://pastebin.com/raw/wyvdb7gr'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت الشقلبة",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://pastebin.com/raw/yjxXnxbS'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت التيليسكوب",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://pastebin.com/raw/8T0STS4f'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت التنقل بندون كتابة اسم🏎️",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://gist.githubusercontent.com/DagerFild/b4776075a0d26ef04394133ee6bd2081/raw/0ed51ac94057d2d9a9f00e1b037b9011c76ca54a/tpGUI", true))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "🛩️سكربت كاميرا درون",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Break%20Camera'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت جرافيكس",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/moh3mah/KATAKORI.ZR/main/Geeetho"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت كل الرقصات💃",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/anyahubs/FE/main/Dances.lua'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "🧐سكربت البحث عن السكربتات الاخرى",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/anyahubs/Hub/main/anyahubV1.lua'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]local Section = Tab:AddSection({
	Name = "👆طريقة استخدام هذا السكربت👆"
})

--[[
Name = <string> - The name of the section.
]]local Section = Tab:AddSection({
	Name = "بعدها تكتب اسم الماب كاملة ولا خطاء script هي انك تكتب"
})

--[[
Name = <string> - The name of the section.
]]Tab:AddButton({
	Name = "سكربت ايس هوب",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/anyahubs/FE/main/ICEHUB_ARABIC"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت حرب السيوف أسرق الوقت من الاخرين⚔️",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/anyahubs/swordgame/main/anya.lua'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت الهاتف📱",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://sirius.menu/script'))();
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]local Section = Tab:AddSection({
	Name = "هذا السكربت 👆 يعمل على هاك دلتا فقط 👆"
})

--[[
Name = <string> - The name of the section.
]]local Section = Tab:AddSection({
	Name = "سكربتات الاق"
})

--[[
Name = <string> - The name of the section.
]]Tab:AddButton({
	Name = "سكربت لاق 1 معروف",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/BidoSkinsYT/BidoSkinsYT/main/Fe%20lag%20chat%20Gui"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت لاق 2 غير معروف",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://pastebin.com/raw/JAAfsp1N"))() 
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]local Section = Tab:AddSection({
	Name = "سكربتات ايم بوت"
})

--[[
Name = <string> - The name of the section.
]]Tab:AddButton({
	Name = "سكربت ايم بوت 1",
	Callback = function()
      		print("button pressed")loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\65\99\117\114\97\88\48\52\57\47\111\98\102\117\115\99\97\116\101\100\83\99\114\105\112\116\115\47\109\97\105\110\47\75\105\108\108\71\117\105\34\41\41\40\41\10")()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت ايم بوت 2",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/hasan08122020108181818/HASA/main/scripthusenidanacronaldo.lua"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "اصدار قديم من سكربت احلام العصر",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/ARAB-SCR/Sc-hlame/main/Sc"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت المشي على الهواء🚶",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Float'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "🤴👸سكربت ادمن",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت عندما تملس شخص تقتله☠️",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet('https://pastebin.com/raw/TXMNj1yy'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت بلوكس فروت يجمع فواكه و اكثر💥🔥",
	Callback = function()
      		print("button pressed")_G.HohoVersion = "v3"
loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت طيران السيارة🚗",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://raw.githubusercontent.com/hasan08122020108181818/HASA/759cc1030d8a4f4c23b32e8cb8550b47f567d1b9/carflyronald"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]Tab:AddButton({
	Name = "سكربت مشيات",
	Callback = function()
      		print("button pressed")loadstring(game:HttpGet("https://pastebin.com/raw/Uq8vajaM"))()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]local Tab = Window:MakeTab({
	Name = "كلام",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]local Section = Tab:AddSection({
	Name = "🔪ادخل سيرفر الديسكورد لك !!!🔪"
})

--[[
Name = <string> - The name of the section.
]]local Section = Tab:AddSection({
	Name = "https://discord.gg/uwzzqycK"
})

--[[
Name = <string> - The name of the section.
]]local Section = Tab:AddSection({
	Name = "اذا شفت واحد اسمه بالديسكود محمد ثامر و كلك انا مصمم السكربت و ما صدقته اكتلك 🔪"
})

--[[
Name = <string> - The name of the section.
]]
