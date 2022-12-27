local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub V 0.0.0 | This Gui Made By Cat#2728", "Midnight")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("NpcStuff")
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
MainSection:NewButton("Orange House Island", "Teleports you to orange house island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(729, 241, 1192)
end)

MainSection:NewButton("Windmill Island", "Teleports you to windmill island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8, 224, -91)
end)

MainSection:NewButton("Money Farm Island", "Teleports you to money farm island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1110, 218, 1673)
end)

Section:NewButton("Cave Island", "Teleports you to cave island", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-68, 216, -893)
end)

--script
