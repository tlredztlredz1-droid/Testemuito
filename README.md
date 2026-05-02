_G.AutoFarm = true 
Default = true,
    _G.AutoFarm = Value
end

task.spawn(function()
    pcall(function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/tlredztlredz1-droid/Autofarm-/main/Auto%20Ataque%20Farm%20Quest"))()
    end)
end)

--
