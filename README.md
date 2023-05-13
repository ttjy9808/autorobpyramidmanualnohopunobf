localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -261
     y = -29
     z = -1345
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()

for i, v in pairs(game.Workspace:GetDescendants()) do
    if v.Name == "MovingLasers" or v.Name == "Laser" or v.Name == "GreenLaser" or v.Name == "GreenLasers" or v.Name == "Lasers" or v.Name == "VaultLasers" or v.Name == "NightLaser" or v.Name == "LaserDoor" or v.Name == "Lava" or v.Name == "Spotlight" or v.Name == "Flamethrowers" or v.Name == "Saws" or v.Name == "SpikeTraps" or v.Name == "Balls" or v.Name == "PressurePlates" or v.Name == "RoofTrap" or v.Name == "LaserWalls" or v.Name == "WallBeam" or v.Name == "Detectors" or v.Name == "Turrets" then
        v:Destroy()
    end
end
task.wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-320.64,-15,-1346.12)
task.wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-363.38,-29.06,-1352.29)
task.wait(0.8)
localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -434.07
     y = -28.81
     z = -1359.96
        hrd.CFrame = CFrame.new(p.x, -29.06, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -29.06, p.z)
         targetPos = Vector3.new(x, -29.06, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -29.06, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -523.72
     y = -29.06
     z = -1238.17
        hrd.CFrame = CFrame.new(p.x, -28.81, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -28.81, p.z)
         targetPos = Vector3.new(x, -28.81, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -28.81, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -513.49
     y = -29.06
     z = -1098.19
        hrd.CFrame = CFrame.new(p.x, -27, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -27, p.z)
         targetPos = Vector3.new(x, -27, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -27, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -472.56
     y = -4
     z = -1014.64
        hrd.CFrame = CFrame.new(p.x, -4, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -4, p.z)
         targetPos = Vector3.new(x, -4, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -4, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-398.57,-4,-1047.78)
        task.wait(1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-398.57,-55.47,-1047.78)
        task.wait(1)
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = -206.55
     y = -114.44
     z = -870.41
        hrd.CFrame = CFrame.new(p.x, -114.44, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -114.44, p.z)
         targetPos = Vector3.new(x, -114.44, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -114.44, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait()
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 77.48
     y = -114.44
     z = -1038.4
        hrd.CFrame = CFrame.new(p.x, -114.44, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, -114.44, p.z)
         targetPos = Vector3.new(x, -114.44, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, -114.44, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(73.79,-100.23,-1073.45)
        task.wait(0.1)
        local GamePassId = 5275408

		local player = game.Players.LocalPlayer
		local MarketplaceService = game:GetService("MarketplaceService")

		local function checkGamePass()
    	local hasGamePass = MarketplaceService:UserOwnsGamePassAsync(player.UserId, GamePassId)

    	if hasGamePass then
    		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
    		wait(1)
    		local VirtualInputManager = game:GetService('VirtualInputManager')

			function keyPress(Key, Press)
    		VirtualInputManager:SendKeyEvent(Press, Key, false, game)
			end
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
    		wait(1)
    		local VirtualInputManager = game:GetService('VirtualInputManager')

			function keyPress(Key, Press)
    		VirtualInputManager:SendKeyEvent(Press, Key, false, game)
			end
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(134.16,-100,-1168.51)
            task.wait(0.5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(134.16,-51.28,-1168.51)
            task.wait(0.1)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(151.13,-51.28,-1185.08)
            task.wait(1)
            localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 43.02
     y = 25.34
     z = -144.48
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.8)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(122.05,26.57,-177.99)
    	else
    		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(104.76,-100.28,-1106.36)
    		wait(0.1)
    		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(131.88,-100.28,-1151.56)
    		wait(0.8)
    		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
    		wait(1)
    		local VirtualInputManager = game:GetService('VirtualInputManager')

			function keyPress(Key, Press)
    		VirtualInputManager:SendKeyEvent(Press, Key, false, game)
			end
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(119.38,-96.53,-1163.81)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(109.66,-94.75,-1178.99)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(116.14,-95.98,-1171.97)
            keyPress(Enum.KeyCode.E, true)
            task.wait(5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(134.16,-100,-1168.51)
            task.wait(0.5)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(134.16,-51.28,-1168.51)
            task.wait(0.1)
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(151.13,-51.28,-1185.08)
            task.wait(1)
            localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 43.02
     y = 25.34
     z = -144.48
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 10) 
        for i = 1, steps do
            currentPos = currentPos + direction * 10 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.8)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(122.05,26.57,-177.99)
    	end
    	end
    	checkGamePass()
        
        
        







