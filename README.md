local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub V 0.0.0 | This Gui Made By Cat#2728", "Synapse")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("Npc")


-- Script

MainSection:NewButton("Santa", "Gives Santa Present", function()
    workspace.Merchants.SantaMerchant.Clickable.Retum:FireServer()
end)
