local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("no name V69", "Synapse")

--Tabs

local Tab1 = Window:NewTab("Scripts")

local Tab1Section = Tab1:NewSection("Script")

--Buttons/Windows/idk

Tab1Section:NewButton("Pro hub ", "ButtonInfo", function()

    loadstring(game:HttpGet(("https://cdn.discordapp.com/attachments/922823751127683082/994188489358835752/Protected.lua"), true))()

end)

Tab1Section:NewButton("Britishhub V5", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/Bri%20hub"))()

end)

Tab1Section:NewButton("Bang r15", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()

end)

Tab1Section:NewButton("Vhub", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/SourceScript5315/sauce/main/VH-Launcher.lua"))()

end)

Tab1Section:NewButton("bed war jn hub", "ButtonInfo", function()

loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/1002510858917773352/1002895558790361158/untitled.txt"))()

end)

Tab1Section:NewButton("KeyBored", "script key bored", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/kC3dAMvt"))()

end)

Tab1Section:NewButton("Old Roblox Ui", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/kosuke14/REBOYHub/main/games/2016_Roblox.lua'))()

end)

Tab1Section:NewButton("Mario [R15]", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/mario-r15/main/Protected.lua'))()

end)

Tab1Section:NewButton("Fly V3", "", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/RPv4GELs"))()

end)

Tab1Section:NewButton("Fly v2", "", function()

    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

end)

Tab1Section:NewButton("Fly old", "ButtonInfo", function()

     loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

end)

Tab1Section:NewSlider("Jump Power", "", 500, 5, function(s) -- 500 (MaxValue) | 0 (MinValue)

game.Players.LocalPlayer.Character.Humanoid.JumpPower = s

end)

Tab1Section:NewSlider("Speed", "", 1000, 15, function(s) -- 500 (MaxValue) | 0 (MinValue)

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s

end)

Tab1Section:NewToggle("Auto Jump", "", function(state)

    if state then

        while true do wait(0.000001)

game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") 

wait(1)

end

    else

        game.Players.LocalPlayer.Character:Destroy()

    end

end)

Tab1Section:NewTextBox("Set Walkspeed","", function(txt) 

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt

end)

Tab1Section:NewTextBox("Set Jumppower","Increases JP", function(txt)

game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt

end)

Tab1Section:NewTextBox("Set FOV [Normal Fov: 70]","", function(txt) 

game.Workspace.CurrentCamera.FieldOfView = txt

end)

Tab1Section:NewButton("Bang r15", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()

end)

Tab1Section:NewButton("Viet hub", "Support Game vietnam piece", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/viet452009/VietHub/main/Loading.Lua"))()

end)

Tab1Section:NewButton("RTX HUB", "ButtonInfo", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/Bkf0BJb3'))()

end)

local Tab2 = Window:NewTab("Tower of hell")

local Tab2Section = Tab2:NewSection("Tower of hell")

local Tab3 = Window:NewTab("Bed war")

local Tab3Section = Tab3:NewSection("Bed war")

local Tab4 = Window:NewTab("Other Gui")

local Tab4Section = Tab4:NewSection("Other gui or something hub")

Tab2Section:NewButton("TOH gui", "", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/BbVHjH56'))()

end)

Tab2Section:NewButton("toh Script", "", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/iiProductionz/Floater-Scripts/main/WaifuEdition/Tower%20Of%20Hell"))()

end)

Tab2Section:NewButton("toh gui 3", "", function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/dqvh/dqvh/main/SprinHub",true))()

end)

Tab2Section:NewButton("Toh Admin", "say .cmds", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/TwomadJR/nto/main/admiin"))()

end)

local Tab2Section = Tab2:NewSection("Coming soon")

Tab3Section:NewButton("jn hub 2.0V", "", function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/JNHHGaming/JN-HH-Gaming-2.0/main/JN%20HH%20Gaming%202.0"))();

end)

Tab3Section:NewButton("Inf Jump", "", function()

    local InfiniteJumpEnabled = true

game:GetService("UserInputService").JumpRequest:connect(function()

	if InfiniteJumpEnabled then

		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")

	end

end)

end)

Tab3Section:NewButton("Key bored", "", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()

end)

Tab3Section:NewButton("Vape v4", "need flie to works", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))() 

end)

Tab4Section:NewButton("Moon Ui", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()

end)

Tab4Section:NewButton("Bobo Hub", "", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/ItsRhylee/Rhylee/main/It's%20Rhylee%20Hub%20(Beta)"))()

end)

Tab4Section:NewButton("Gui", "", function()

    loadstring(game:HttpGet(('https://pastebin.com/raw/JLPe0B3H'),true))();

end)

Tab4Section:NewButton("HarshTech full version", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Full-Version/main/HarshTech7.4.txt"))()

end)

Tab4Section:NewButton("Harsh Tech Beta", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Beta/main/HarshTech7.4.txt"))()

end)

Tab3Section:NewButton("Bonsai v1", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/wv4KvxZa"))();

end)

Tab1Section:NewButton("Fe sussy", "", function()

   -- FE SussyHub Made by Nil <3

-- Mizt Source by Melon <3

loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();

end)

Tab4Section:NewButton("dino hub v5", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/GithubUset/Dion-Hub-VI/main/Dion%20Hub%20Be%20like.lua'))()

end)

local Tab5 = Window:NewTab("Credit")

local Tab5Section = Tab5:NewSection("By no name#7128")

local Tab5Section = Tab5:NewSection("script were not made by me")

local Tab5Section = Tab5:NewSection("credit to all owner script")

Tab4Section:NewButton("aimbot for any games", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/1Gp9c57U"))()

end)

local Tab4Section = Tab4:NewSection("Coming Soon")

local Tab6 = Window:NewTab("theme")

local Tab6Section = Tab6:NewSection("Chose theme if you want.")

Tab6Section:NewButton("Black theme", "", function()

    local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("no name ware", "BlackTheme")

--Tabs

local Tab1 = Window:NewTab("Scripts")

local Tab1Section = Tab1:NewSection("Script")

--Buttons/Windows/idk

Tab1Section:NewButton("Inf jump", "Ez", function()

    local InfiniteJumpEnabled = true

game:GetService("UserInputService").JumpRequest:connect(function()

	if InfiniteJumpEnabled then

		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")

	end

end)

end)

Tab1Section:NewButton("Pro hub ", "ButtonInfo", function()

    loadstring(game:HttpGet(("https://cdn.discordapp.com/attachments/922823751127683082/994188489358835752/Protected.lua"), true))()

end)

Tab1Section:NewButton("Britishhub V5", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/Bri%20hub"))()

end)

Tab1Section:NewButton("Bang r15", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()

end)

Tab1Section:NewButton("Vhub", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/SourceScript5315/sauce/main/VH-Launcher.lua"))()

end)

Tab1Section:NewButton("bed war jn hub", "ButtonInfo", function()

loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/1002510858917773352/1002895558790361158/untitled.txt"))()

end)

Tab1Section:NewButton("KeyBored", "script key bored", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/kC3dAMvt"))()

end)

Tab1Section:NewButton("Old Roblox Ui", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/kosuke14/REBOYHub/main/games/2016_Roblox.lua'))()

end)

Tab1Section:NewButton("Mario [R15]", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/mario-r15/main/Protected.lua'))()

end)

Tab1Section:NewButton("Fly V3", "", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/RPv4GELs"))()

end)

Tab1Section:NewButton("Fly v2", "", function()

    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

end)

Tab1Section:NewButton("Fly old", "ButtonInfo", function()

     loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()

end)

Tab1Section:NewSlider("Jump Power", "", 500, 5, function(s) -- 500 (MaxValue) | 0 (MinValue)

game.Players.LocalPlayer.Character.Humanoid.JumpPower = s

end)

Tab1Section:NewSlider("Speed", "", 1000, 15, function(s) -- 500 (MaxValue) | 0 (MinValue)

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s

end)

Tab1Section:NewToggle("Auto Jump", "", function(state)

    if state then

        while true do wait(0.000001)

game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") 

wait(1)

end

    else

        game.Players.LocalPlayer.Character:Destroy()

    end

end)

Tab1Section:NewTextBox("Set Walkspeed","", function(txt) 

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt

end)

Tab1Section:NewTextBox("Set Jumppower","Increases JP", function(txt)

game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt

end)

Tab1Section:NewTextBox("Set FOV [Normal Fov: 70]","", function(txt) 

game.Workspace.CurrentCamera.FieldOfView = txt

end)

Tab1Section:NewButton("Bang r15", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/manimcool21/bang/main/Protected%20(27).lua'))()

end)

Tab1Section:NewButton("RTX HUB", "ButtonInfo", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/Bkf0BJb3'))()

end)

local Tab2 = Window:NewTab("Tower of hell")

local Tab2Section = Tab2:NewSection("Tower of hell")

local Tab3 = Window:NewTab("Bed war")

local Tab3Section = Tab3:NewSection("Bed war")

local Tab4 = Window:NewTab("Other Gui")

local Tab4Section = Tab4:NewSection("Other gui or something hub")

Tab2Section:NewButton("TOH gui", "", function()

    loadstring(game:HttpGet('https://pastebin.com/raw/BbVHjH56'))()

end)

Tab2Section:NewButton("toh Script", "", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/iiProductionz/Floater-Scripts/main/WaifuEdition/Tower%20Of%20Hell"))()

end)

Tab2Section:NewButton("toh gui 3", "", function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/dqvh/dqvh/main/SprinHub",true))()

end)

Tab2Section:NewButton("Toh Admin", "say .cmds", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/TwomadJR/nto/main/admiin"))()

end)

local Tab2Section = Tab2:NewSection("Coming soon")

Tab3Section:NewButton("jn hub 2.0V", "", function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/JNHHGaming/JN-HH-Gaming-2.0/main/JN%20HH%20Gaming%202.0"))();

end)

Tab3Section:NewButton("Inf Jump", "", function()

    local InfiniteJumpEnabled = true

game:GetService("UserInputService").JumpRequest:connect(function()

	if InfiniteJumpEnabled then

		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")

	end

end)

end)

Tab3Section:NewButton("Key bored", "", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()

end)

Tab3Section:NewButton("Vape v4", "need flie to works", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua", true))() 

end)

Tab4Section:NewButton("Moon Ui", "", function()

loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()

end)

Tab4Section:NewButton("Bobo Hub", "", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/ItsRhylee/Rhylee/main/It's%20Rhylee%20Hub%20(Beta)"))()

end)

Tab4Section:NewButton("Gui", "", function()

    loadstring(game:HttpGet(('https://pastebin.com/raw/JLPe0B3H'),true))();

end)

Tab4Section:NewButton("HarshTech full version", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Full-Version/main/HarshTech7.4.txt"))()

end)

Tab4Section:NewButton("Harsh Tech Beta", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTech7.4-Beta/main/HarshTech7.4.txt"))()

end)

Tab3Section:NewButton("Bonsai v1", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/wv4KvxZa"))();

end)

Tab1Section:NewButton("Fe sussy", "Fuck me daddy", function()

   -- FE SussyHub Made by Nil <3

-- Mizt Source by Melon <3

loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();

end)

Tab4Section:NewButton("dino hub v5", "ButtonInfo", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/GithubUset/Dion-Hub-VI/main/Dion%20Hub%20Be%20like.lua'))()

end)

local Tab5 = Window:NewTab("Credit")

local Tab5Section = Tab5:NewSection("By no name#7128")

local Tab5Section = Tab5:NewSection("script were not made by me")

local Tab5Section = Tab5:NewSection("credit to all owner script")

Tab4Section:NewButton("aimbot for any games", "ButtonInfo", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/1Gp9c57U"))()

end)

end)

local Tab6 = Window:NewTab("Da Hood")

local Tab6Section = Tab6:NewSection("Aimlock or something scripts")

local Tab7 = Window:NewTab("Script need hat to use.")

local Tab7Section = Tab7:NewSection("sure u need hat to use")

Tab6Section:NewButton("Nuker Mode", "NukerMode", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/Allvideo/test/main/Whitelist.txt"))()

end)

Tab6Section:NewButton("Swag Mode beta", "Swag mode", function()

   loadstring(game:HttpGet('https://raw.githubusercontent.com/lerkermer/lua-projects/master/SwagModeV002'))()

end)

Tab6Section:NewButton("Fadded", "", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded/main/YesEpic", true))()

end)

Tab6Section:NewButton("RayCodeX", "Type Aimlock for lock.", function()

    loadstring(game:GetObjects("rbxassetid://5812737894")[1].Source)()

end)

Tab6Section:NewButton("Auto Farm", "auto farm Cash da hood", function()

    loadstring(game:HttpGet("https://pastebin.com/raw/Le3eNZua", true))()

end)

Tab7Section:NewButton("NightWare V1", "ButtonInfo", function()

    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Nighmaretwastaken/Hide/main/Protected (4).lua'),true))()

end)

local Tab7Section = Tab7:NewSection("Coming Soon")

local Tab6Section = Tab6:NewSection("Coming Soon")

local Tab8 = Window:NewTab("BloxFruit")

local Tab8Section = Tab8:NewSection("Blox Fruit")

local Tab9 = Window:NewTab("arsenal")

local Tab9Section = Tab:NewSection("Arsenal")

Tab8Section:NewButton("Hoho Hub", "Hoho hub", function()

    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()

end)

Tab8Section:NewButton("Zen Hub V3", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/ZenHub/main/bloxfrui%20v0.3", true))()

end)

Tab8Section:NewButton("PlayBackX", "ButtonInfo", function()

   loadstring(game:HttpGet("https://raw.githubusercontent.com/NeaPchX2/Playback-X-HUB/main/Protected.lua.txt"))()

end)

Tab8Section:NewButton("Blox fruit script", "ButtonInfo", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/BlodyXHub/Xeniel_All/main/ForAll"))()

end)

Tab9Section:NewButton("aimbot arsenal", "ButtonInfo", function()

    loadstring(game:HttpGet(("https://raw.githubusercontent.com/Maikderninja/Maikderninja/main/PWNERHUB.lua"), true))()

end)

Tab9Section:NewButton("arsenal Gui", "ButtonInfo", function()

    https://raw.githubusercontent.com/GamingScripter/arsenal-hub/main/Arsenal%20GamingScripter

end)

local Tab9Section = Tab9:NewSection("comingsoon")

local Tab8Section = Tab:NewSection("Coming Soon")

local Tab10 = Window:NewTab("Notes")

local Tab10Section = Tab10:NewSection("Credit all to owner script")

local Tab10Section = Tab10:NewSection("Script not make by me tho")

local Tab10Section = Tab10:NewSection("add me No name#7128 if u need help.")

local Tab10Section = Tab10:NewSection("dm for help")

