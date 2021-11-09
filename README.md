-- made by Hello
local MM2EmoteGUI = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local MainLabel = Instance.new("TextLabel")
local ninja = Instance.new("TextButton")
local zen = Instance.new("TextButton")
local zombie = Instance.new("TextButton")
local headless = Instance.new("TextButton")
local dab = Instance.new("TextButton")
local floss = Instance.new("TextButton")
local sit = Instance.new("TextButton")
local del = Instance.new("TextButton")
local UIS = game:GetService("UserInputService")
local function InputBegan(Input)
 if rawequal(Input.KeyCode, Enum.KeyCode.RightControl) then
        if not MM2EmoteGUI.Enabled then
            MM2EmoteGUI.Enabled = true
        else 
            MM2EmoteGUI.Enabled = false
        end
    end
end

UIS.InputBegan:Connect(InputBegan)


MM2EmoteGUI.Name = "MM2EmoteGUI by Hello"
MM2EmoteGUI.Parent = game.CoreGui

Frame.Parent = MM2EmoteGUI
Frame.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Frame.BorderColor3 = Color3.fromRGB(255, 255, 255)
Frame.Position = UDim2.new(0.740126371, 0, 0.573983729, 0)
Frame.Size = UDim2.new(0, 321, 0, 256)
Frame.Active  = true
Frame.Draggable = true


MainLabel.Name = "MainLabel"
MainLabel.Parent = Frame
MainLabel.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
MainLabel.BorderColor3 = Color3.fromRGB(255, 255, 255)
MainLabel.Position = UDim2.new(0.027692087, 0, 0.0688641071, 0)
MainLabel.Size = UDim2.new(0, 177, 0, 50)
MainLabel.Font = Enum.Font.GothamBold
MainLabel.Text = "MM2 Emote GUI BY HELLO#0182"
MainLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
MainLabel.TextSize = 14.000

ninja.Name = "ninja"
ninja.Parent = Frame
ninja.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
ninja.BorderColor3 = Color3.fromRGB(255, 255, 255)
ninja.Position = UDim2.new(0.523038626, 0, 0.297006667, 0)
ninja.Size = UDim2.new(0, 148, 0, 50)
ninja.Font = Enum.Font.GothamBold
ninja.Text = "Ninja"
ninja.TextColor3 = Color3.fromRGB(255, 255, 255)
ninja.TextSize = 14.000

zen.Name = "zen"
zen.Parent = Frame
zen.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
zen.BorderColor3 = Color3.fromRGB(255, 255, 255)
zen.Position = UDim2.new(0.027692318, 0, 0.297006667, 0)
zen.Size = UDim2.new(0, 148, 0, 50)
zen.Font = Enum.Font.GothamBold
zen.Text = "Zen"
zen.TextColor3 = Color3.fromRGB(255, 255, 255)
zen.TextSize = 14.000

zombie.Name = "zombie"
zombie.Parent = Frame
zombie.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
zombie.BorderColor3 = Color3.fromRGB(255, 255, 255)
zombie.Position = UDim2.new(0.0245770533, 0, 0.533122659, 0)
zombie.Size = UDim2.new(0, 148, 0, 50)
zombie.Font = Enum.Font.GothamBold
zombie.Text = "Zombie"
zombie.TextColor3 = Color3.fromRGB(255, 255, 255)
zombie.TextSize = 14.000

headless.Name = "headless"
headless.Parent = Frame
headless.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
headless.BorderColor3 = Color3.fromRGB(255, 255, 255)
headless.Position = UDim2.new(0.523038626, 0, 0.533122659, 0)
headless.Size = UDim2.new(0, 148, 0, 50)
headless.Font = Enum.Font.GothamBold
headless.Text = "Headless"
headless.TextColor3 = Color3.fromRGB(255, 255, 255)
headless.TextSize = 14.000

dab.Name = "dab"
dab.Parent = Frame
dab.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
dab.BorderColor3 = Color3.fromRGB(255, 255, 255)
dab.Position = UDim2.new(0.523038626, 0, 0.765332401, 0)
dab.Size = UDim2.new(0, 148, 0, 50)
dab.Font = Enum.Font.GothamBold
dab.Text = "Dab"
dab.TextColor3 = Color3.fromRGB(255, 255, 255)
dab.TextSize = 14.000

floss.Name = "floss"
floss.Parent = Frame
floss.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
floss.BorderColor3 = Color3.fromRGB(255, 255, 255)
floss.Position = UDim2.new(0.027692318, 0, 0.765332401, 0)
floss.Size = UDim2.new(0, 148, 0, 50)
floss.Font = Enum.Font.GothamBold
floss.Text = "Floss"
floss.TextColor3 = Color3.fromRGB(255, 255, 255)
floss.TextSize = 14.000

sit.Name = "sit"
sit.Parent = Frame
sit.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
sit.BorderColor3 = Color3.fromRGB(255, 255, 255)
sit.Position = UDim2.new(0.617272973, 0, 0.0688641146, 0)
sit.Size = UDim2.new(0, 87, 0, 50)
sit.Font = Enum.Font.GothamBold
sit.Text = "Sit"
sit.TextColor3 = Color3.fromRGB(255, 255, 255)
sit.TextSize = 14.000

del.Name = "del"
del.Parent = Frame
del.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
del.BackgroundTransparency = 1.000
del.BorderColor3 = Color3.fromRGB(27, 42, 53)
del.Position = UDim2.new(0.915887833, 0, 0, 0)
del.Size = UDim2.new(0, 27, 0, 25)
del.Font = Enum.Font.GothamBold
del.Text = "X"
del.TextColor3 = Color3.fromRGB(255, 255, 255)
del.TextSize = 14.000



local function TMSZC_fake_script() 
	local script = Instance.new('LocalScript', ninja)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("ninja")
		end)
end
coroutine.wrap(TMSZC_fake_script)()
local function CIJHNWH_fake_script()  
	local script = Instance.new('LocalScript', zen)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("zen")
	end)
end
coroutine.wrap(CIJHNWH_fake_script)()
local function IBEOM_fake_script() 
	local script = Instance.new('LocalScript', zombie)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("zombie")
		end)
end
coroutine.wrap(IBEOM_fake_script)()
local function NWEV_fake_script() 
	local script = Instance.new('LocalScript', headless)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("headless")
		end)
end
coroutine.wrap(NWEV_fake_script)()
local function QGSHQVE_fake_script() 
	local script = Instance.new('LocalScript', dab)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("dab")
	end)
end
coroutine.wrap(QGSHQVE_fake_script)()
local function KUBYUEU_fake_script()  
	local script = Instance.new('LocalScript', floss)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("floss")
		end)
end
coroutine.wrap(KUBYUEU_fake_script)()
local function RORY_fake_script() 
	local script = Instance.new('LocalScript', sit)

	script.Parent.MouseButton1Down:Connect(function()
		game.ReplicatedStorage.PlayEmote:Fire("sit")
	end)
end
coroutine.wrap(RORY_fake_script)()
local function BEDYBN_fake_script()
	local script = Instance.new('LocalScript', del)

	script.Parent.MouseButton1Down:Connect(function()
		game.CoreGui.MM2EmoteGUI:Remove()
	end)
end
coroutine.wrap(BEDYBN_fake_script)()
local function YCKQ_fake_script() 
	local script = Instance.new('LocalScript', MM2EmoteGUI)

	local frame = script.Parent.Frame
	local labeltext = script.Parent.Frame.MainLabel
	
	local ninja = script.Parent.Frame.ninja
	local zen = script.Parent.Frame.zen
	local zombie = script.Parent.Frame.zombie
	local headless = script.Parent.Frame.headless
	local dab = script.Parent.Frame.dab
	local floss = script.Parent.Frame.floss
	local sit = script.Parent.Frame.sit
	
	local x = script.Parent.Frame.del
	
	
	
	
	
	
	
	
	
	while wait() do
		frame.BorderColor3 = Color3.new(255/255,0/255,0/255)
		labeltext.TextColor3 =  Color3.new(255/255,0/255,0/255)
		labeltext.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		ninja.TextColor3 =  Color3.new(255/255,0/255,0/255)
		ninja.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		zen.TextColor3 =  Color3.new(255/255,0/255,0/255)
		zen.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		zombie.TextColor3 =  Color3.new(255/255,0/255,0/255)
		zombie.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		headless.TextColor3 =  Color3.new(255/255,0/255,0/255)
		headless.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		dab.TextColor3 =  Color3.new(255/255,0/255,0/255)
		dab.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		floss.TextColor3 =  Color3.new(255/255,0/255,0/255)
		floss.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
	
		sit.TextColor3 =  Color3.new(255/255,0/255,0/255)
		sit.BorderColor3 =  Color3.new(255/255,0/255,0/255)
		
		
		
		x.TextColor3 =  Color3.new(255/255,0/255,0/255)
		
		
		
		
		for i = 0,255,10 do
			wait()
			frame.BorderColor3 = Color3.new(255/255,i/255,0/255)
			labeltext.TextColor3 = Color3.new(255/255,i/255,0/255)
			labeltext.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			
			ninja.TextColor3 = Color3.new(255/255,i/255,0/255)
			ninja.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			zen.TextColor3 = Color3.new(255/255,i/255,0/255)
			zen.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			zombie.TextColor3 = Color3.new(255/255,i/255,0/255)
			zombie.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			headless.TextColor3 = Color3.new(255/255,i/255,0/255)
			headless.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			dab.TextColor3 = Color3.new(255/255,i/255,0/255)
			dab.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			floss.TextColor3 = Color3.new(255/255,i/255,0/255)
			floss.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			sit.TextColor3 = Color3.new(255/255,i/255,0/255)
			sit.BorderColor3 = Color3.new(255/255,i/255,0/255)
			
			
			x.TextColor3 = Color3.new(255/255,i/255,0/255)
			
			
			
		end
		for i = 255,0,-10 do
			wait()
			frame.BorderColor3 = Color3.new(i/255,255/255,0/255)
			labeltext.TextColor3 = Color3.new(i/255,255/255,0/255)
			labeltext.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			
			ninja.TextColor3 = Color3.new(i/255,255/255,0/255)
			ninja.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			zen.TextColor3 = Color3.new(i/255,255/255,0/255)
			zen.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			zombie.TextColor3 = Color3.new(i/255,255/255,0/255)
			zombie.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			headless.TextColor3 = Color3.new(i/255,255/255,0/255)
			headless.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			dab.TextColor3 = Color3.new(i/255,255/255,0/255)
			dab.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			floss.TextColor3 = Color3.new(i/255,255/255,0/255)
			floss.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			sit.TextColor3 = Color3.new(i/255,255/255,0/255)
			sit.BorderColor3 = Color3.new(i/255,255/255,0/255)
			
			
			x.TextColor3 = Color3.new(i/255,255/255,0/255)
			
			
		end
		for i = 0,255,10 do
			wait()
			frame.BorderColor3 = Color3.new(0/255,255/255,i/255)
			labeltext.TextColor3 =  Color3.new(0/255,255/255,i/255)
			labeltext.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			ninja.TextColor3 =  Color3.new(0/255,255/255,i/255)
			ninja.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
	
			zen.TextColor3 =  Color3.new(0/255,255/255,i/255)
			zen.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			zombie.TextColor3 =  Color3.new(0/255,255/255,i/255)
			zombie.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			headless.TextColor3 =  Color3.new(0/255,255/255,i/255)
			headless.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			dab.TextColor3 =  Color3.new(0/255,255/255,i/255)
			dab.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			floss.TextColor3 =  Color3.new(0/255,255/255,i/255)
			floss.BorderColor3 = Color3.new(0/255,255/255,i/255)
			
			sit.TextColor3 =  Color3.new(0/255,255/255,i/255)
			sit.BorderColor3 = Color3.new(0/255,255/255,i/255)
	
	
			x.TextColor3 =  Color3.new(0/255,255/255,i/255)
			
			
		end
		for i = 255,0,-10 do
			wait()
			frame.BorderColor3 = Color3.new(0/255,i/255,255/255)
			labeltext.TextColor3 = Color3.new(0/255,i/255,255/255)
			labeltext.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			ninja.TextColor3 = Color3.new(0/255,i/255,255/255)
			ninja.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			zen.TextColor3 = Color3.new(0/255,i/255,255/255)
			zen.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			zombie.TextColor3 = Color3.new(0/255,i/255,255/255)
			zombie.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			headless.TextColor3 = Color3.new(0/255,i/255,255/255)
			headless.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			dab.TextColor3 = Color3.new(0/255,i/255,255/255)
			dab.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			floss.TextColor3 = Color3.new(0/255,i/255,255/255)
			floss.BorderColor3 = Color3.new(0/255,i/255,255/255)
			
			sit.TextColor3 = Color3.new(0/255,i/255,255/255)
			sit.BorderColor3 = Color3.new(0/255,i/255,255/255)
	
			x.TextColor3 = Color3.new(0/255,i/255,255/255)
			
			
			
		end
		for i = 0,255,10 do
			wait()
			frame.BorderColor3 = Color3.new(i/255,0/255,255/255)
			labeltext.TextColor3 = Color3.new(i/255,0/255,255/255)		
			labeltext.BorderColor3 = Color3.new(i/255,0/255,255/255)	
			
			ninja.TextColor3 = Color3.new(i/255,0/255,255/255)		
			ninja.BorderColor3 = Color3.new(i/255,0/255,255/255)	
			
	
			zen.TextColor3 = Color3.new(i/255,0/255,255/255)		
			zen.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
			zombie.TextColor3 = Color3.new(i/255,0/255,255/255)		
			zombie.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
			headless.TextColor3 = Color3.new(i/255,0/255,255/255)		
			headless.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
	
			dab.TextColor3 = Color3.new(i/255,0/255,255/255)		
			dab.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
			floss.TextColor3 = Color3.new(i/255,0/255,255/255)		
			floss.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
			sit.TextColor3 = Color3.new(i/255,0/255,255/255)		
			sit.BorderColor3 = Color3.new(i/255,0/255,255/255)
			
			x.TextColor3 = Color3.new(i/255,0/255,255/255)		
			
			
			
			
		end
		for i = 255,0,-10 do
			wait()
			frame.BorderColor3 = Color3.new(255/255,0/255,i/255)
			labeltext.TextColor3 = Color3.new(255/255,0/255,i/255)
			labeltext.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
			ninja.TextColor3 = Color3.new(255/255,0/255,i/255)
			ninja.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
			zen.TextColor3 = Color3.new(255/255,0/255,i/255)
			zen.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
			
			zombie.TextColor3 = Color3.new(255/255,0/255,i/255)
			zombie.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
			headless.TextColor3 = Color3.new(255/255,0/255,i/255)
			headless.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
	
			dab.TextColor3 = Color3.new(255/255,0/255,i/255)
			dab.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
	
			floss.TextColor3 = Color3.new(255/255,0/255,i/255)
			floss.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
	
			sit.TextColor3 = Color3.new(255/255,0/255,i/255)
			sit.BorderColor3 = Color3.new(255/255,0/255,i/255)
			
			
			x.TextColor3 = Color3.new(255/255,0/255,i/255)
			
		end
	end
	
	
end
coroutine.wrap(YCKQ_fake_script)()
