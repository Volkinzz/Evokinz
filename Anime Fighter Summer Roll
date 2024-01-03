--Variaveis]
    local player = game.Players.LocalPlayer -- Obter o jogador local

    --Load
    local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

    --Hub
    local Window = OrionLib:MakeWindow({Name = "Evok lindo", HidePremium = true, SaveConfig = true, ConfigFolder = "OrionTest"})

    --valor
    _G.AutoRoll = false


    --Abas
    local Tab = Window:MakeTab({
        Name = "dark lindeza",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })



    function Autoroll()
        while _G.AutoRoll == true do
                local args = {
                [1] = "Summer2Egg"
            }

            game:GetService("ReplicatedStorage"):WaitForChild("Remote"):WaitForChild("AttemptMultiOpen"):FireServer(unpack(args))
            wait(0.00001)
        end
    end


 --tab
    Tab:AddToggle({
        Name = "Summer(2023)",
        Default = false,
        Callback = function(Value)
            _G.AutoRoll = Value
            Autoroll()
          
        end   
    })




