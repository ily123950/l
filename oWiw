loadstring(game:HttpGet('https://raw.githubusercontent.com/ily123950/scv3/main/var'))()
game.Players:Chat("h \n \n \n \n \n \n Vernam has been executed.")
game.Players:Chat("!gearannounce disable")
local playerJoinEnabled = true
local isPlayerLeaveEnabled = true
local isAntigearEnabled = false
game.Players.PlayerAdded:Connect(function(player)
    if playerJoinEnabled then
        game.Players:Chat("h \n \n \n \n \n \n " .. player.Name .. " joined the server!")
        if player.Name == game.Players.LocalPlayer.Name then
            game.Players:Chat("!gearannounce disable")
        end
    end
end)

game.Players.PlayerRemoving:Connect(function(player)
    if isPlayerLeaveEnabled then
        game.Players:Chat("h \n \n \n \n \n \n " .. player.Name .. " left the server!")
    end
end)

game.Players.LocalPlayer.Chatted:Connect(function(msg)
    local lowerMsg = msg:lower()
    
    if lowerMsg == ".disableplrleave" then
        isPlayerLeaveEnabled = false
    elseif lowerMsg == ".enableplrleave" then
        isPlayerLeaveEnabled = true
    elseif lowerMsg == ".disableplrjoin" then
        playerJoinEnabled = false
    elseif lowerMsg == ".enableplrjoin" then
        playerJoinEnabled = true
    elseif lowerMsg == ".credits" then
        game.Players:Chat("h \n \n \n \n \n \n  Vernam was coded by user.")
    elseif lowerMsg == ".all" then
        game.Players:Chat(".antiblind")
        wait(0.1)
        game.Players:Chat(".antimsg")
        wait(0.1)
        game.Players:Chat(".permap")
        wait(0.1)
        game.Players:Chat(".nok")
        wait(0.1)
        game.Players:Chat(".antikill")
    elseif lowerMsg == ".antigear" then
        game.Players:Chat(".spam ungear/others")
        wait(0.1)
        game.Players:Chat("h \n \n \n \n \n \n Anti gear is now on.")
        isAntigearEnabled = true
    elseif lowerMsg == ".unantigear" then
        game.Players:Chat(".stop")
        wait(0.1)
        game.Players:Chat("h \n \n \n \n \n \n Anti gear is now off.")
        isAntigearEnabled = false
    elseif lowerMsg == ".rcrash" then
        game.Players:Chat("h \n \n \n \n \n \n please join another server.")
        game.Players:Chat("respawn others")
        game.Players:Chat("time 1")
        game.Players:Chat("brightness nan")
        wait(0.1)
        game.Players:Chat("!rcrash")
        wait(2)
        game.Players:Chat("!rcrash")
    elseif lowerMsg:sub(1, 5) == ".nuke" then
        game.Players:Chat(".spam gear me 16979083")
        wait(0.2)
        game.Players:Chat(".stop")
        game.Players:Chat(".usetools")
        
        local plr = game:GetService("Players").LocalPlayer
        plr.Character.Humanoid:UnequipTools()
        
        local Tools = plr.Backpack:GetChildren()
        
        for _, tool in ipairs(Tools) do
            tool.Parent = plr.Character
            tool:Activate()
        end
    elseif lowerMsg:sub(1, 3) == ".eg" and #lowerMsg > 3 then
        local letter = lowerMsg:sub(5, 5)
        game.Players:Chat("blind " .. letter)
        game.Players:Chat("respawn " .. letter)
        game.Players:Chat(".punish2 " .. letter)
        game.Players:Chat(".setspamdelay 0.4")
        wait(6)
        game.Players:Chat(".setspamdelay 0.0000001")
        game.Players:Chat(".stop")
        game.Players:Chat(".spam pm " .. letter .. " sorry, just a test.")
    elseif lowerMsg:sub(1, 2) == ".d" and #lowerMsg > 2 then
        local letter = lowerMsg:sub(4, 4)
        game.Players:Chat("respawn " .. letter)
        wait(1)
        game.Players:Chat("skydive me")
        wait(0.3)
        game.Players:Chat("skydive me")
        wait(0.3)
        game.Players:Chat("skydive me")
        wait(0.3)
        game.Players:Chat("skydive me")
        wait(0.3)
        game.Players:Chat("skydive me")
        wait(0.3)
        game.Players:Chat("jail me")
        wait(0.3)
        game.Players:Chat(".viewpart baseplate")
        wait(1)
        game.Players:Chat("removejails")
        wait(1)
        game.Players:Chat("respawn me")
        wait(1)
        game.Players:Chat(".rkick " .. letter)
        wait(4)
        game.Players:Chat(".rkick " .. letter)
    elseif lowerMsg == ".rg" then
        local gearIDs = {212296936, 10468797, 253519495, 11999247, 111876831, 44115926, 68603151, 20064349, 88885539, 110789105}
        local randomGearID = gearIDs[math.random(1, #gearIDs)]
        game.Players:Chat("gear me " .. tostring(randomGearID))
    elseif lowerMsg == ".cloud" then
        game.Players:Chat(".spam gear me 111876831")
        wait(4)
        game.Players:Chat(".stop")
        local plr = game:GetService("Players").LocalPlayer
        plr.Character.Humanoid:UnequipTools()
        
        local Tools = plr.Backpack:GetChildren()
        local numTools = #Tools
        local radiusOuter = 4 -- Adjust the outer radius of the star
        local radiusInner = 4 -- Adjust the inner radius of the star

        for i, tool in ipairs(Tools) do
            local angle = (2 * math.pi / numTools) * i
            local xOuter = math.cos(angle) * radiusOuter
            local zOuter = math.sin(angle) * radiusOuter
            local xInner = math.cos(angle + math.pi/numTools) * radiusInner
            local zInner = math.sin(angle + math.pi/numTools) * radiusInner

            tool.Grip = CFrame.new(xOuter, 0, zOuter) + Vector3.new(xInner, 0, zInner)
            tool.Parent = plr.Character
        end
        
        wait(0.1) -- Delay for 0.1 second
        
        plr.Character.Humanoid:UnequipTools()
        game.Players:Chat(".usetools")
    elseif lowerMsg == ".toolorb" then
        game.Players:Chat(".spam gear me 111876831")
        wait(6)
        
        local plr = game:GetService("Players").LocalPlayer
        plr.Character.Humanoid:UnequipTools()

        local Tools = plr.Backpack:GetChildren()
        local numTools = #Tools
        local radiusOuter = 4 -- Adjust the outer radius of the star
        local radiusInner = 5 -- Adjust the inner radius of the star

        for i, tool in ipairs(Tools) do
            local angle = (2 * math.pi / numTools) * i
            local xOuter = math.cos(angle) * radiusOuter
            local zOuter = math.sin(angle) * radiusOuter
            local xInner = math.cos(angle + math.pi/numTools) * radiusInner
            local zInner = math.sin(angle + math.pi/numTools) * radiusInner

            tool.Grip = CFrame.new(xOuter, 0, zOuter) + Vector3.new(xInner, 0, zInner)
            tool.Parent = plr.Character
        end
        
        wait(0.1) -- Delay for 0.1 second
        
        plr.Character.Humanoid:UnequipTools()
        game.Players:Chat(".stop")
        
        loadstring(game:HttpGet('https://raw.githubusercontent.com/ily123950/Yool/main/l'))()
    elseif lowerMsg == ".vgcrash" then
        local message = "h \n \n \n \n \n \n server crashed."
        game.Players:Chat(message)
    end
    
    if isAntigearEnabled and msg:lower():find("gear me") then
        local playerName = game.Players.LocalPlayer.Name
        local message = "h \n \n \n \n \n \n " .. playerName .. " was trying to crash the server."
        game.Players:Chat(message)
        game.Players:Chat(".spam pm " .. playerName .. " You have been punished.")
        wait(0.3)
        game.Players:Chat(".spam blind " .. playerName)
    end
end)

local player = game.Players.LocalPlayer -- Change this to the player you want to equip tools for
equipAndUnequipTools(player)
