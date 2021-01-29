local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TopFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Close = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Open = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")
local BottomFrame = Instance.new("Frame")
local UICorner_5 = Instance.new("UICorner")
local HubName = Instance.new("TextLabel")
local SharpenFrame = Instance.new("Frame")
local EspScript = Instance.new("TextButton")
local HitBoxScript = Instance.new("TextButton")
local Dookies = Instance.new("TextLabel")
local HitBoxLight = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local EspLight = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local NoobFrame = Instance.new("Frame")
local TriggerBotScript = Instance.new("TextButton")
local AimBotScript = Instance.new("TextButton")
local SilentAimScript = Instance.new("TextButton")
local SilentAimLight = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local AimBotLight = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local TriggerBotLight = Instance.new("TextLabel")
local UICorner_10 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")
local SideFrame = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local OpenNoobs = Instance.new("TextButton")
local OpenSharpen = Instance.new("TextButton")
local Frame = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local Close2 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local PlayerName = Instance.new("TextLabel")
local Insult1 = Instance.new("TextLabel")
local Insult2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(21, 22, 24)
Main.Position = UDim2.new(0.27564767, 0, 0.222408026, 0)
Main.Size = UDim2.new(0, 233,0, 116)
Main.Draggable = true
Main.Active = true

TopFrame.Name = "TopFrame"
TopFrame.Parent = Main
TopFrame.BackgroundColor3 = Color3.fromRGB(47, 0, 104)
TopFrame.BorderSizePixel = 0
TopFrame.Size = UDim2.new(0, 306, 0, 28)
TopFrame.Visible = false

UICorner.CornerRadius = UDim.new(0.100000001, 0)
UICorner.Parent = TopFrame

Close.Name = "Close"
Close.Parent = TopFrame
Close.BackgroundColor3 = Color3.fromRGB(95, 31, 31)
Close.Position = UDim2.new(0.885620892, 0, 0.107142858, 0)
Close.Size = UDim2.new(0, 35, 0, 22)
Close.Font = Enum.Font.SourceSans
Close.Text = ""
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 14.000
Close.MouseButton1Down:connect(function()
	Main.Visible = false
end)

UICorner_2.CornerRadius = UDim.new(0.5, 0)
UICorner_2.Parent = Close

Open.Name = "Open"
Open.Parent = TopFrame
Open.BackgroundColor3 = Color3.fromRGB(55, 105, 143)
Open.Position = UDim2.new(0, 0, 0.107142858, 0)
Open.Size = UDim2.new(0, 35, 0, 22)
Open.Font = Enum.Font.SourceSans
Open.Text = ""
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 14.000
Open.MouseButton1Down:connect(function()
	SideFrame.Visible = true
	BottomFrame.Visible = false
	NoobFrame.Visible = false
	SharpenFrame.Visible = false
	TopFrame.Visible = false
	Main.Size = UDim2.new(0, 233,0, 116)
end)

UICorner_3.CornerRadius = UDim.new(0.5, 0)
UICorner_3.Parent = Open

UICorner_4.CornerRadius = UDim.new(0.100000001, 0)
UICorner_4.Parent = Main

BottomFrame.Name = "BottomFrame"
BottomFrame.Parent = Main
BottomFrame.BackgroundColor3 = Color3.fromRGB(47, 0, 104)
BottomFrame.BorderSizePixel = 0
BottomFrame.Position = UDim2.new(0, 0, 0.919075131, 0)
BottomFrame.Size = UDim2.new(0, 306, 0, 28)
BottomFrame.Visible = false

UICorner_5.CornerRadius = UDim.new(0.100000001, 0)
UICorner_5.Parent = BottomFrame

HubName.Name = "HubName"
HubName.Parent = BottomFrame
HubName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HubName.BackgroundTransparency = 1.000
HubName.BorderSizePixel = 0
HubName.Position = UDim2.new(-0.00182517059, 0, 0.108131401, 0)
HubName.Size = UDim2.new(0, 93, 0, 21)
HubName.Font = Enum.Font.SourceSans
HubName.Text = "TellyTubby"
HubName.TextColor3 = Color3.fromRGB(0, 0, 0)
HubName.TextSize = 18.000
HubName.TextWrapped = true

SharpenFrame.Name = "SharpenFrame"
SharpenFrame.Parent = Main
SharpenFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SharpenFrame.BackgroundTransparency = 1.000
SharpenFrame.BorderSizePixel = 0
SharpenFrame.Position = UDim2.new(0, 0, 0.0809248537, 0)
SharpenFrame.Size = UDim2.new(0, 306, 0, 290)
SharpenFrame.Visible = false

EspScript.Name = "EspScript"
EspScript.Parent = SharpenFrame
EspScript.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
EspScript.BorderSizePixel = 0
EspScript.Position = UDim2.new(0, 0, 0.220689654, 0)
EspScript.Size = UDim2.new(0, 306, 0, 30)
EspScript.Font = Enum.Font.SourceSans
EspScript.Text = "Esp"
EspScript.TextColor3 = Color3.fromRGB(0, 0, 0)
EspScript.TextScaled = true
EspScript.TextSize = 14.000
EspScript.TextWrapped = true
EspScript.MouseButton1Down:connect(function()
	EspLight.BackgroundColor3 = Color3.fromRGB(0, 149, 17)
	local gplrs = game.Players:GetPlayers()
	local plr = game.Players.LocalPlayer
	local TorsoEsp = Instance.new("Part")
	TorsoEsp.Anchored = true
	TorsoEsp.BottomSurface = Enum.SurfaceType.Smooth
	TorsoEsp.CFrame = CFrame.new(-153.01, 3, -34.152)
	TorsoEsp.Name = "TorsoEsp"
	TorsoEsp.Reflectance = 1
	TorsoEsp.Size = Vector3.new(0.05, 1.66, 0.05)
	TorsoEsp.TopSurface = Enum.SurfaceType.Smooth
	TorsoEsp.Transparency = 1
	TorsoEsp.Parent = game:GetService("Workspace")
	TorsoEsp.CanCollide = false

	local BoxHandleAdornment = Instance.new("BoxHandleAdornment")
	BoxHandleAdornment.Adornee = nil
	BoxHandleAdornment.AlwaysOnTop = true
	BoxHandleAdornment.Color3 = Color3.fromRGB(180, 155, 255)
	BoxHandleAdornment.Size = Vector3.new(2, 5.1, 1)
	BoxHandleAdornment.Transparency = 0.6
	BoxHandleAdornment.ZIndex = 2
	BoxHandleAdornment.Parent = TorsoEsp



	game.Players.PlayerAdded:Connect(function(plr)
		TorsoEsp:Clone()
		TorsoEsp.Parent = game.Workspace:WaitForChild(plr.Name)
		TorsoEsp.BoxHandleAdornment.Adornee = game.Workspace:WaitForChild(plr.Name).HumanoidRootPart
	end)


	for i, v in pairs(gplrs) do
		local BoxHandleAdornment = Instance.new("BoxHandleAdornment")
		BoxHandleAdornment.Adornee = v.Character.HumanoidRootPart
		BoxHandleAdornment.AlwaysOnTop = true
		BoxHandleAdornment.Color3 = Color3.fromRGB(180, 155, 255)
		BoxHandleAdornment.Size = Vector3.new(2, 5.1, 1)
		BoxHandleAdornment.Transparency = 0.6
		BoxHandleAdornment.ZIndex = 2
		BoxHandleAdornment.Parent = v.Character
	end
end)

HitBoxScript.Name = "HitBoxScript"
HitBoxScript.Parent = SharpenFrame
HitBoxScript.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
HitBoxScript.BorderSizePixel = 0
HitBoxScript.Position = UDim2.new(0, 0, 0.0965517163, 0)
HitBoxScript.Size = UDim2.new(0, 306, 0, 30)
HitBoxScript.Font = Enum.Font.SourceSans
HitBoxScript.Text = "HitBox"
HitBoxScript.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBoxScript.TextScaled = true
HitBoxScript.TextSize = 14.000
HitBoxScript.TextWrapped = true
HitBoxScript.MouseButton1Down:connect(function()
	HitBoxLight.BackgroundColor3 = Color3.fromRGB(0, 149, 17)
	function getplrsname()
		for i,v in pairs(game:GetChildren()) do
			if v.ClassName == "Players" then
				return v.Name
			end
		end
	end
	local players = getplrsname()
	local plr = game[players].LocalPlayer
	coroutine.resume(coroutine.create(function()
		while  wait(1) do
			coroutine.resume(coroutine.create(function()
				for _,v in pairs(game[players]:GetPlayers()) do
					if v.Name ~= plr.Name and v.Character then
						v.Character.RightUpperLeg.CanCollide = false
						v.Character.RightUpperLeg.Transparency = 1
						v.Character.RightUpperLeg.Size = Vector3.new(13,13,13)

						v.Character.HeadHB.CanCollide = false
						v.Character.HeadHB.Transparency = 1
						v.Character.HeadHB.Size = Vector3.new(13,13,13)

						v.Character.HumanoidRootPart.CanCollide = false
						v.Character.HumanoidRootPart.Transparency = 1
						v.Character.HumanoidRootPart.Size = Vector3.new(13,13,13)

						v.Character.LeftUpperLeg.CanCollide = false
						v.Character.LeftUpperLeg.Transparency = 1
						v.Character.LeftUpperLeg.Size = Vector3.new(13,13,13)

					end
				end
			end))
		end
	end))
end)

Dookies.Name = "Dookies"
Dookies.Parent = SharpenFrame
Dookies.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Dookies.BackgroundTransparency = 1.000
Dookies.Position = UDim2.new(0.312603414, 0, 0.518965483, 0)
Dookies.Size = UDim2.new(0, 113, 0, 29)
Dookies.Font = Enum.Font.SourceSans
Dookies.Text = "--Status--"
Dookies.TextColor3 = Color3.fromRGB(170, 0, 255)
Dookies.TextScaled = true
Dookies.TextSize = 14.000
Dookies.TextWrapped = true

HitBoxLight.Name = "HitBoxLight"
HitBoxLight.Parent = SharpenFrame
HitBoxLight.BackgroundColor3 = Color3.fromRGB(167, 0, 0)
HitBoxLight.Position = UDim2.new(0.0294117648, 0, 0.660344839, 0)
HitBoxLight.Size = UDim2.new(0, 43, 0, 29)
HitBoxLight.Font = Enum.Font.SourceSans
HitBoxLight.Text = ""
HitBoxLight.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBoxLight.TextSize = 14.000

UICorner_6.CornerRadius = UDim.new(0.100000001, 0)
UICorner_6.Parent = HitBoxLight

EspLight.Name = "EspLight"
EspLight.Parent = SharpenFrame
EspLight.BackgroundColor3 = Color3.fromRGB(167, 0, 0)
EspLight.Position = UDim2.new(0.0294117648, 0, 0.812068999, 0)
EspLight.Size = UDim2.new(0, 43, 0, 29)
EspLight.Font = Enum.Font.SourceSans
EspLight.Text = ""
EspLight.TextColor3 = Color3.fromRGB(0, 0, 0)
EspLight.TextSize = 14.000

UICorner_7.CornerRadius = UDim.new(0.100000001, 0)
UICorner_7.Parent = EspLight

TextLabel.Parent = SharpenFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.062091507, 0, 0.658620715, 0)
TextLabel.Size = UDim2.new(0, 174, 0, 29)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "---  HitBox"
TextLabel.TextColor3 = Color3.fromRGB(0, 102, 255)
TextLabel.TextSize = 18.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = SharpenFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0, 0, 0.810344815, 0)
TextLabel_2.Size = UDim2.new(0, 193, 0, 29)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "---  Esp"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 102, 255)
TextLabel_2.TextSize = 18.000
TextLabel_2.TextWrapped = true

NoobFrame.Name = "NoobFrame"
NoobFrame.Parent = Main
NoobFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NoobFrame.BackgroundTransparency = 1.000
NoobFrame.BorderSizePixel = 0
NoobFrame.Position = UDim2.new(0, 0, 0.0809248537, 0)
NoobFrame.Size = UDim2.new(0, 306, 0, 290)
NoobFrame.Visible = false

TriggerBotScript.Name = "TriggerBotScript"
TriggerBotScript.Parent = NoobFrame
TriggerBotScript.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
TriggerBotScript.BorderSizePixel = 0
TriggerBotScript.Position = UDim2.new(0, 0, 0.0965517163, 0)
TriggerBotScript.Size = UDim2.new(0, 306, 0, 30)
TriggerBotScript.Font = Enum.Font.SourceSans
TriggerBotScript.Text = "TriggerBot"
TriggerBotScript.TextColor3 = Color3.fromRGB(0, 0, 0)
TriggerBotScript.TextScaled = true
TriggerBotScript.TextSize = 14.000
TriggerBotScript.TextWrapped = true
TriggerBotScript.MouseButton1Down:connect(function()
	TriggerBotLight.BackgroundColor3 = Color3.fromRGB(0, 149, 17)
	local player = game:GetService("Players").LocalPlayer
	local mouse = player:GetMouse()
	game:GetService("RunService").RenderStepped:Connect(function()
		if mouse.Target.Parent:FindFirstChild("Humanoid") and mouse.Target.Parent.Name ~= player.Name then
			mouse1press() wait() mouse1release()
		end
	end)
end)

AimBotScript.Name = "AimBotScript"
AimBotScript.Parent = NoobFrame
AimBotScript.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
AimBotScript.BorderSizePixel = 0
AimBotScript.Position = UDim2.new(0, 0, 0.220689654, 0)
AimBotScript.Size = UDim2.new(0, 306, 0, 30)
AimBotScript.Font = Enum.Font.SourceSans
AimBotScript.Text = "AimBot"
AimBotScript.TextColor3 = Color3.fromRGB(0, 0, 0)
AimBotScript.TextScaled = true
AimBotScript.TextSize = 14.000
AimBotScript.TextWrapped = true
AimBotScript.MouseButton1Down:connect(function()
	AimBotLight.BackgroundColor3 = Color3.fromRGB(0, 149, 17)
	_G.FRIEND_LIST = {"ROBLOX","builderman"} --Add players you want to ignore

	_G.IGNORE_TEAM = true
	_G.START_AIMBOT = Enum.KeyCode.Z
	_G.MAX_DIST = 5000
	_G.TARGET_PART = "Head"


	local startTime = tick()
	local AIMBOT = false

	local plr = game.Players.LocalPlayer
	local camera = workspace.CurrentCamera
	local mouse = plr:GetMouse()
	local StarterGui = game:GetService("StarterGui")

	local function GetClosestPlayer(returnPlr,ignoreList)
		ignoreList = _G.FRIEND_LIST
		returnPlr = returnPlr or false

		local ignoreTeam = _G.IGNORE_TEAM
		if ignoreTeam == true then
			if #game:GetService("Teams"):GetChildren() <= 1 then
				ignoreTeam = false
			end
			if plr.Neutral == true then
				ignoreTeam = false
			end
		end

		local temp1 = (_G.MAX_DIST)
		local FoundPlr
		local FoundPart

		local Table = game.Players:GetPlayers()
		for _,v in pairs(Table) do
			local skip = false
			for _,i in pairs(ignoreList) do
				if i:lower() == v.Name:lower() then
					skip = true
				end
			end
			if ignoreTeam == true then
				if v.Team == plr.Team then
					skip = true
				end
			end
			if skip == false then
				if (temp1 ~= nil and v.Character ~= nil and plr.Character ~= nil and plr.Character:FindFirstChild(_G.TARGET_PART)) then
					if temp1 > (plr.Character.Head.Position - v.Character:FindFirstChild(_G.TARGET_PART).Position).magnitude then
						local vChar = v.Character
						if vChar:FindFirstChild("Humanoid") then
							local vHuman = vChar:FindFirstChild("Humanoid")
							if vHuman.Health > 0 then
								local dist = (game.Players.LocalPlayer.Character.Head.Position - v.Character:FindFirstChild(_G.TARGET_PART).Position).magnitude
								if dist <= _G.MAX_DIST then
									local ray = Ray.new(plr.Character.Head.CFrame.p, (v.Character:FindFirstChild(_G.TARGET_PART).CFrame.p - plr.Character.Head.CFrame.p).unit * _G.MAX_DIST)
									local hitPart,position = workspace:FindPartOnRay(ray,game.Players.LocalPlayer.Character)

									if hitPart then
										if hitPart:IsDescendantOf(vChar) then
											temp1 = dist
											FoundPlr = v
											FoundPart = vChar:FindFirstChild(_G.TARGET_PART)
										end
									end
								end
							end
						end
					end
				end
			end
		end
		if returnPlr == false then
			return FoundPart
		elseif returnPlr == true then
			return FoundPlr
		end
	end

	local UIS = game:GetService("UserInputService")
	UIS.InputBegan:Connect(function(KEY, gpe)
		if gpe then return end;
		if KEY.KeyCode == _G.START_AIMBOT then
			if AIMBOT == false then
				AIMBOT = true
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = "Enabled AimHot",
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size24
				})
			elseif AIMBOT == true then
				AIMBOT = false
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = "Disabled AimHot",
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size24
				})
			end
		end
	end)


	game:GetService("RunService").RenderStepped:Connect(function()
		if (AIMBOT == true and plr.Character ~= nil and plr.Character.Humanoid.Health > 0) then
			local closestPart = GetClosestPlayer(false,{})
			if closestPart ~= nil then
				camera.CoordinateFrame = CFrame.new(camera.CoordinateFrame.p, closestPart.CFrame.p)
			end
		end
	end)

	plr.Chatted:Connect(function(msg)
		if string.sub(msg,1,12) == "/e -maxdist " then
			local maxdist = tonumber(string.sub(msg,13,msg:len()))
			if type(maxdist) == "number" then
				_G.MAX_DIST = maxdist
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = ("Changed maxdist to; "..(tostring(maxdist))),
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size28
				})
				print(("Changed maxdist to; "..(tostring(maxdist))))
			end
		end
		if string.sub(msg,1,15) == "/e -ignoreteam " then
			local setting = string.sub(msg,15,msg:len()):lower()
			print(setting)
			if setting == "true" or "false" then
				_G.IGNORE_TEAM = setting
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = ("Changed ignoreteam to; "..(tostring(setting))),
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size28
				})
				print("Changed ignoreteam to; "..(tostring(setting)))
			end
		end
		if string.sub(msg,1,15) == "/e -targetpart " then
			local setting = string.sub(msg,16,msg:len())
			if type(setting) == "string" then
				_G.TARGET_PART = setting
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = ("Changed targetpart to; "..(tostring(setting))),
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size28
				})
				print("Changed targetpart to; "..(tostring(setting)))
			end
		end
		if string.sub(msg,1,17) == "/e -removefriend " then
			local setting = string.sub(msg,18,msg:len())
			if type(setting) == "string" then
				for i,v in pairs(_G.FRIEND_LIST) do
					if v:lower() == setting:lower() then
						table.remove(_G.FRIEND_LIST,i)
					end
				end
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = ("Removed player from friend list; "..(tostring(setting))),
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size28
				})
				print("Removed player from friend list; "..(tostring(setting)))
			end
		end
		if string.sub(msg,1,14) == "/e -addfriend " then
			local setting = string.sub(msg,15,msg:len())
			if type(setting) == "string" then
				for i,v in pairs(_G.FRIEND_LIST) do
					if v == setting:lower() then
						return
					end
				end
				table.insert(_G.FRIEND_LIST,setting:lower())
				StarterGui:SetCore("ChatMakeSystemMessage",{
					Text = ("Added player to friend list; "..(tostring(setting))),
					Color = Color3.fromRGB(200,10,10),
					FontSize = Enum.FontSize.Size28
				})
				print("Added player to friend list; "..(tostring(setting)))
			end
		end
		if string.sub(msg,1,11) == "/e -friends" then
			local friends = ""
			for i,v in pairs(_G.FRIEND_LIST) do
				if i == 1 then
					friends = v
				else
					friends = friends..", "..v
				end
			end

			StarterGui:SetCore("ChatMakeSystemMessage",{
				Text = (
					"Your friends are; " .."\n"..
						friends
				),
				Color = Color3.fromRGB(200,10,10),
				FontSize = Enum.FontSize.Size24
			})
			print("Your friends are; \n"..friends)
		end
		if string.sub(msg,1,8) == "/e -help" then
			StarterGui:SetCore("ChatMakeSystemMessage",{
				Text = (
					"Aimbot loaded. Time taken: ".. tick()-startTime .."\n"..
						"Press Z to turn on and off."
				),
				Color = Color3.fromRGB(200,10,10),
				FontSize = Enum.FontSize.Size24
			})
			print(
				"Aimbot loaded. Time taken: ".. tick()-startTime .."\n"..
					"Press Z to turn on and off."
			)
		end
	end)

	print(
		"Aimbot loaded. Time taken: ".. tick()-startTime .."\n"..
			"Press Z to turn on and off."
	)

	StarterGui:SetCore("ChatMakeSystemMessage",{
		Text = (
			"Aimbot loaded. Time taken: ".. tick()-startTime .."\n"..
				"Press Z to turn on and off."
		),
		Color = Color3.fromRGB(200,10,10),
		FontSize = Enum.FontSize.Size24
	})
	_G.AIMHOT_SECRETKEY = "dF10qLMn"
	_G.AIMHOT_VERSION = "2.0"
end)

SilentAimScript.Name = "SilentAimScript"
SilentAimScript.Parent = NoobFrame
SilentAimScript.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
SilentAimScript.BorderSizePixel = 0
SilentAimScript.Position = UDim2.new(0, 0, 0.344827563, 0)
SilentAimScript.Size = UDim2.new(0, 306, 0, 30)
SilentAimScript.Font = Enum.Font.SourceSans
SilentAimScript.Text = "SilentAim"
SilentAimScript.TextColor3 = Color3.fromRGB(0, 0, 0)
SilentAimScript.TextScaled = true
SilentAimScript.TextSize = 14.000
SilentAimScript.TextWrapped = true
SilentAimScript.MouseButton1Down:connect(function()
	SilentAimLight.BackgroundColor3 = Color3.fromRGB(0, 149, 17)
	local CurrentCamera = workspace.CurrentCamera
	local Players = game.GetService(game, "Players")
	local LocalPlayer = Players.LocalPlayer
	local Mouse = LocalPlayer:GetMouse()
	function ClosestPlayer()
		local MaxDist, Closest = math.huge
		for I,V in pairs(Players.GetPlayers(Players)) do
			if V == LocalPlayer then continue end
			if V.Team == LocalPlayer then continue end
			if not V.Character then continue end
			local Head = V.Character.FindFirstChild(V.Character, "Head")
			if not Head then continue end
			local Pos, Vis = CurrentCamera.WorldToScreenPoint(CurrentCamera, Head.Position)
			if not Vis then continue end
			local MousePos, TheirPos = Vector2.new(Mouse.X, Mouse.Y), Vector2.new(Pos.X, Pos.Y)
			local Dist = (TheirPos - MousePos).Magnitude
			if Dist < MaxDist then
				MaxDist = Dist
				Closest = V
			end
		end
		return Closest
	end
	local MT = getrawmetatable(game)
	local OldNC = MT.__namecall
	local OldIDX = MT.__index
	setreadonly(MT, false)
	MT.__namecall = newcclosure(function(self, ...)
		local Args, Method = {...}, getnamecallmethod()
		if Method == "FindPartOnRayWithIgnoreList" and not checkcaller() then
			local CP = ClosestPlayer()
			if CP and CP.Character and CP.Character.FindFirstChild(CP.Character, "Head") then
				Args[1] = Ray.new(CurrentCamera.CFrame.Position, (CP.Character.Head.Position - CurrentCamera.CFrame.Position).Unit * 1000)
				return OldNC(self, unpack(Args))
			end
		end
		return OldNC(self, ...)
	end)
	MT.__index = newcclosure(function(self, K)
		if K == "Clips" then
			return workspace.Map
		end
		return OldIDX(self, K)
	end)
	setreadonly(MT, true)
end)


SilentAimLight.Name = "SilentAimLight"
SilentAimLight.Parent = NoobFrame
SilentAimLight.BackgroundColor3 = Color3.fromRGB(167, 0, 0)
SilentAimLight.Position = UDim2.new(0.0490196086, 0, 0.870689631, 0)
SilentAimLight.Size = UDim2.new(0, 43, 0, 29)
SilentAimLight.Font = Enum.Font.SourceSans
SilentAimLight.Text = ""
SilentAimLight.TextColor3 = Color3.fromRGB(0, 0, 0)
SilentAimLight.TextSize = 14.000

UICorner_8.CornerRadius = UDim.new(0.100000001, 0)
UICorner_8.Parent = SilentAimLight

TextLabel_3.Parent = NoobFrame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.150326803, 0, 0.617241383, 0)
TextLabel_3.Size = UDim2.new(0, 153, 0, 29)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "---  TriggerBot"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 102, 255)
TextLabel_3.TextSize = 18.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = NoobFrame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.09150327, 0, 0.744827569, 0)
TextLabel_4.Size = UDim2.new(0, 171, 0, 29)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "---  AimBot"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 102, 255)
TextLabel_4.TextSize = 18.000
TextLabel_4.TextWrapped = true

AimBotLight.Name = "AimBotLight"
AimBotLight.Parent = NoobFrame
AimBotLight.BackgroundColor3 = Color3.fromRGB(167, 0, 0)
AimBotLight.Position = UDim2.new(0.0490196086, 0, 0.746551752, 0)
AimBotLight.Size = UDim2.new(0, 43, 0, 29)
AimBotLight.Font = Enum.Font.SourceSans
AimBotLight.Text = ""
AimBotLight.TextColor3 = Color3.fromRGB(0, 0, 0)
AimBotLight.TextSize = 14.000

UICorner_9.CornerRadius = UDim.new(0.100000001, 0)
UICorner_9.Parent = AimBotLight

TriggerBotLight.Name = "TriggerBotLight"
TriggerBotLight.Parent = NoobFrame
TriggerBotLight.BackgroundColor3 = Color3.fromRGB(167, 0, 0)
TriggerBotLight.Position = UDim2.new(0.0490196086, 0, 0.618965507, 0)
TriggerBotLight.Size = UDim2.new(0, 43, 0, 29)
TriggerBotLight.Font = Enum.Font.SourceSans
TriggerBotLight.Text = ""
TriggerBotLight.TextColor3 = Color3.fromRGB(0, 0, 0)
TriggerBotLight.TextSize = 14.000



UICorner_10.CornerRadius = UDim.new(0.100000001, 0)
UICorner_10.Parent = TriggerBotLight

TextLabel_5.Parent = NoobFrame
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.114379086, 0, 0.868965507, 0)
TextLabel_5.Size = UDim2.new(0, 170, 0, 29)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "---  SilentAim"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 102, 255)
TextLabel_5.TextSize = 18.000
TextLabel_5.TextWrapped = true

SideFrame.Name = "SideFrame"
SideFrame.Parent = Main
SideFrame.BackgroundColor3 = Color3.fromRGB(21, 22, 24)
SideFrame.BorderSizePixel = 0
SideFrame.Size = UDim2.new(0, 233, 0, 116)

UICorner_11.CornerRadius = UDim.new(0.100000001, 0)
UICorner_11.Parent = SideFrame

OpenNoobs.Name = "OpenNoobs"
OpenNoobs.Parent = SideFrame
OpenNoobs.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
OpenNoobs.BorderSizePixel = 0
OpenNoobs.Position = UDim2.new(0.0508711003, 0, 0.703309655, 0)
OpenNoobs.Size = UDim2.new(0, 98, 0, 25)
OpenNoobs.Font = Enum.Font.SourceSans
OpenNoobs.Text = "Noob"
OpenNoobs.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenNoobs.TextSize = 14.000
OpenNoobs.MouseButton1Down:connect(function()
	SideFrame.Visible = false
	BottomFrame.Visible = true
	SharpenFrame.Visible = false
	NoobFrame.Visible = true
	TopFrame.Visible = true
	Main.Size = UDim2.new(0, 306,0, 346)
end)

OpenSharpen.Name = "OpenSharpen"
OpenSharpen.Parent = SideFrame
OpenSharpen.BackgroundColor3 = Color3.fromRGB(57, 7, 89)
OpenSharpen.BorderSizePixel = 0
OpenSharpen.Position = UDim2.new(0.0508711003, 0, 0.358850002, 0)
OpenSharpen.Size = UDim2.new(0, 98, 0, 25)
OpenSharpen.Font = Enum.Font.SourceSans
OpenSharpen.Text = "Sharpen "
OpenSharpen.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenSharpen.TextSize = 14.000
OpenSharpen.MouseButton1Down:connect(function()
	SideFrame.Visible = false
	BottomFrame.Visible = true
	SharpenFrame.Visible = true
	NoobFrame.Visible = false
	TopFrame.Visible = true
	Main.Size = UDim2.new(0, 306,0, 346)
end)


Frame.Parent = SideFrame
Frame.BackgroundColor3 = Color3.fromRGB(47, 0, 104)
Frame.BorderSizePixel = 0
Frame.Size = UDim2.new(0, 233, 0, 28)

UICorner_12.CornerRadius = UDim.new(0.100000001, 0)
UICorner_12.Parent = Frame

Close2.Name = "Close-2"
Close2.Parent = SideFrame
Close2.BackgroundColor3 = Color3.fromRGB(95, 31, 31)
Close2.Position = UDim2.new(0.846994281, 0, 0.020935962, 0)
Close2.Size = UDim2.new(0, 35, 0, 22)
Close2.Font = Enum.Font.SourceSans
Close2.Text = ""
Close2.TextColor3 = Color3.fromRGB(0, 0, 0)
Close2.TextSize = 14.000
Close2.MouseButton1Down:connect(function()
	Main.Visible = false
end)

UICorner_13.CornerRadius = UDim.new(0.5, 0)
UICorner_13.Parent = Close2

PlayerName.Name = "PlayerName"
PlayerName.Parent = SideFrame
PlayerName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.BackgroundTransparency = 1.000
PlayerName.BorderSizePixel = 0
PlayerName.Position = UDim2.new(0.00246667489, 0, 0.0219245031, 0)
PlayerName.Size = UDim2.new(0, 93, 0, 21)
PlayerName.Font = Enum.Font.SourceSans
PlayerName.Text = (game.Players.LocalPlayer.Name)
PlayerName.TextColor3 = Color3.fromRGB(0, 0, 0)
PlayerName.TextSize = 18.000
PlayerName.TextWrapped = true

Insult1.Name = "Insult-1"
Insult1.Parent = SideFrame
Insult1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Insult1.BackgroundTransparency = 1.000
Insult1.Position = UDim2.new(0.502145946, 0, 0.353448272, 0)
Insult1.Size = UDim2.new(0, 108, 0, 25)
Insult1.Font = Enum.Font.SourceSans
Insult1.Text = "To Sharpen \"Skills\""
Insult1.TextColor3 = Color3.fromRGB(0, 102, 255)
Insult1.TextSize = 14.000

Insult2.Name = "Insult-2"
Insult2.Parent = SideFrame
Insult2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Insult2.BackgroundTransparency = 1.000
Insult2.Position = UDim2.new(0.502145946, 0, 0.698275864, 0)
Insult2.Size = UDim2.new(0, 108, 0, 25)
Insult2.Font = Enum.Font.SourceSans
Insult2.Text = "You need this? 🤡"
Insult2.TextColor3 = Color3.fromRGB(0, 102, 255)
Insult2.TextSize = 14.000
