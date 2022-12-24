local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cat Hub This Gui Made By Cat#2728", "Synapse")

local Main = Window:NewTab("Npc")
local MainSection = Main:NewSection("Npc")

Section:NewButton("Santa", "Gives Santa Present", function()
    workspace.Merchants.SantaMerchant.Clickable.Retum:FireServer()
end)
