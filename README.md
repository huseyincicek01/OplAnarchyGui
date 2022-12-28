local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub V 1.0.0 | This Gui Made By Cat#2728", "DarkTheme")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("Npc Stuff")
--script
MainSection:NewButton("Santa", "Gives Santa Present", function()
    workspace.Merchants.SantaMerchant.Clickable.Retum:FireServer()
end)

local Main = Window:NewTab("Teleport")
local MainSection = Main:NewSection("Teleport Npc")
--script
MainSection:NewButton("Sam", "Teleports you to sam", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1302, 218, -1353)
end)

MainSection:NewButton("Drink", "Teleports you to Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1282, 218, -1367)
end)

MainSection:NewButton("Better Drink", "Teleports you to Better Drink Merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1493, 260, 2171)
end)

MainSection:NewButton("Flail", "Teleports you to flail sword seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1110, 217, 3366)
end)

MainSection:NewButton("Rod Quest", "Teleports you to fish quest", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1699, 216, -326)
end)

MainSection:NewButton("Krizma Seller", "Teleports you to krizma seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1074, 361, 1670)
end)

MainSection:NewButton("Sword Seller", "Teleports you to sword seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1007, 224, -3338)
end)

MainSection:NewButton("Gun Seller", "Teleports you to gun seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1843, 222, 3408)
end)

MainSection:NewButton("Emote", "Teleports you to emote seller", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1517, 260, 2166)
end)

MainSection:NewButton("Affinity", "Teleports you to affinity merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(117, 278, 4948)
end)

MainSection:NewButton("Mixer", "Teleports you to mixer and fish merchant", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1991, 218, 566)
end)

MainSection:NewButton("Mission Assignment", "Teleports you to Mission Assignment", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(901, 270, 1219)
end)

MainSection:NewButton("Santa", "Teleports you to Santa", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(711, 241, 1249)
end)

local Main = Window:NewTab("Island")
local MainSection = Main:NewSection("Island")
MainSection:NewButton("Orange House Island", "Teleports you to Orange House Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(729, 241, 1192)
end)

MainSection:NewButton("Windmill Island", "Teleports you to Wkndmill Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8, 224, -91)
end)

MainSection:NewButton("Money Farm Island", "Teleports you to Money farm Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1110, 218, 1673)
end)

MainSection:NewButton("Cave Island", "Teleports you to Cave Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-68, 216, -893)
end)

MainSection:NewButton("Pursuer Island", "Teleports you to Pursuer Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4847, 570, -7143)
end)

MainSection:NewButton("Bar Island", "Teleports you to Bar Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1494, 264, 2133)
end)

MainSection:NewButton("Snow Mountain", "Teleports you to Snow Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6654, 418, -1468)
end)

MainSection:NewButton("Vokun Island", "Teleports you to Vokun Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4574, 217, 4962)
end)

MainSection:NewButton("Green Island", "Teleports you to Green Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2727, 253, 1041)
end)

MainSection:NewButton("Flail Island", "Teleports you to Flail Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1068, 217, 3351)
end)

MainSection:NewButton("Sam Island", "Teleports you to Sam Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1283, 218, -1348)
end)

MainSection:NewButton("Pyramid Island", "Teleports you to Pyramid Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(118, 216, 4773)
end)

MainSection:NewButton("Fish Quest Island", "Teleports you to Boar Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1668, 217, -300)
end)

MainSection:NewButton("Mountain", "Teleports you to Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1896, 222, 3385)
end)

MainSection:NewButton("Snowy Island", "Teleports you to Snowy Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2053, 488, -700)
end)

MainSection:NewButton("Marine Ford", "Teleports you to Marine Ford", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3164, 296, -3780)
end)

MainSection:NewButton("Desert Island", "Teleports you to Desert Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(896, 224, -3275)
end)

MainSection:NewButton("Trees Island", "Teleports you to Trees Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5781, 216, 114)
end)

MainSection:NewButton("Purple Island", "Teleports you to Purple Island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5168, 523, -7800)
end)

MainSection:NewButton("Mini Mountain", "Teleports you to Mini Mountain", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3193, 357, 1670)
end)

MainSection:NewButton("Islands", "Teleports you to Islands", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4329, 245, 5252)
end)

MainSection:NewButton("Town", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1818, 218, 755)
end)

MainSection:NewButton("Rocky", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-37, 229, 2149)
end)

MainSection:NewButton("Palm", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(766, 216, -1374)
end)

MainSection:NewButton("Sand", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2747, 216, -942)
end)

MainSection:NewButton("Sand2", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1237, 240, -244)
end)

MainSection:NewButton("Small", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1235, 223, 623)
end)

MainSection:NewButton("Tiny", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4007, 216, -2190)
end)

MainSection:NewButton("Super Tiny", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2096, 217, -1884)
end)

MainSection:NewButton("Grass", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
end)
--script
