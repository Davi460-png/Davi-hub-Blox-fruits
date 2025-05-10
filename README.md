Davi hub
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

Windows
local Window = Library.CreateLib("Davi hub", "DarkTheme")

Tabs
local Tab = Window:NewTab("Ola")

labs
Section:NewLabel("davi hub")

Buttons
Section:NewButton("Ola", "Privado", function()

end)

script
Section:NewSlider("SliderText", "SliderInfo", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
