local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Anonymus", "Ocean")

-- MAIN
local Main = Window:NewTab("Anonymus")
local MainSection = Main:NewSection("Anonymus")


MainSection:NewButton("Anonymus Admin CMD", "Admin  commands credit Git hub", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)


MainSection:NewButton("Anonymus Arsenal", "Arsenal Esp Auto aim", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)


MainSection:NewButton("Anonymus Door", "Anonymus", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/plamen6789/DoorsEntitySpawner/main/EntitySpawner"))()
end)
