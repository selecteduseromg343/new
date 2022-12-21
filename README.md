

local ScreenGui = Instance.new("ScreenGui")
local MainBox = Instance.new("Frame")
local labellol = Instance.new("TextLabel")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local grandmaster = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local neptunian = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local baller = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")


ScreenGui.Parent = game.CoreGui

MainBox.Name = "MainBox"
MainBox.Parent = ScreenGui
MainBox.BackgroundColor3 = Color3.fromRGB(54, 54, 54)
MainBox.BorderColor3 = Color3.fromRGB(255, 0, 4)
MainBox.Position = UDim2.new(0.0156107079, 0, 0.219047621, 0)
MainBox.Size = UDim2.new(0, 171, 0, 249)
MainBox.Active = true

labellol.Name = "label lol"
labellol.Parent = MainBox
labellol.BackgroundColor3 = Color3.fromRGB(96, 125, 255)
labellol.Size = UDim2.new(0, 78, 0, 21)
labellol.Font = Enum.Font.Unknown
labellol.Text = "DarkWare FE"
labellol.TextColor3 = Color3.fromRGB(0, 0, 0)
labellol.TextSize = 14.000

UICorner.Parent = labellol

TextLabel.Parent = MainBox
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
TextLabel.Position = UDim2.new(0.0490797535, 0, 0.155894756, 0)
TextLabel.Size = UDim2.new(0, 82, 0, 22)
TextLabel.Font = Enum.Font.SourceSansBold
TextLabel.Text = "GrandMasterFE"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

UICorner_2.Parent = TextLabel

grandmaster.Name = "grandmaster"
grandmaster.Parent = MainBox
grandmaster.BackgroundColor3 = Color3.fromRGB(123, 255, 0)
grandmaster.Position = UDim2.new(0.601226985, 0, 0.167055339, 0)
grandmaster.Size = UDim2.new(0, 53, 0, 15)
grandmaster.Font = Enum.Font.SourceSansBold
grandmaster.Text = "EXECUTE"
grandmaster.TextColor3 = Color3.fromRGB(0, 0, 0)
grandmaster.TextSize = 14.000
grandmaster.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/selecteduseromg343/GrandMasterAnim/main/README.md"))()
end)

UICorner_3.Parent = grandmaster

UICorner_4.Parent = MainBox

TextLabel_2.Parent = MainBox
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
TextLabel_2.Position = UDim2.new(0.0490797535, 0, 0.465218186, 0)
TextLabel_2.Size = UDim2.new(0, 82, 0, 22)
TextLabel_2.Font = Enum.Font.SourceSansBold
TextLabel_2.Text = "FE NeptunianV"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

UICorner_5.Parent = TextLabel_2

neptunian.Name = "neptunian"
neptunian.Parent = MainBox
neptunian.BackgroundColor3 = Color3.fromRGB(123, 255, 0)
neptunian.Position = UDim2.new(0.601226985, 0, 0.492468536, 0)
neptunian.Size = UDim2.new(0, 53, 0, 15)
neptunian.Font = Enum.Font.SourceSansBold
neptunian.Text = "EXECUTE"
neptunian.TextColor3 = Color3.fromRGB(0, 0, 0)
neptunian.TextSize = 14.000
neptunian.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/mememasterboi/a-lot-of-scripts/master/Obfuscate Template.txt'),true))()
end)

UICorner_6.Parent = neptunian

baller.Name = "baller"
baller.Parent = MainBox
baller.BackgroundColor3 = Color3.fromRGB(123, 255, 0)
baller.Position = UDim2.new(0.601226985, 0, 0.299697459, 0)
baller.Size = UDim2.new(0, 53, 0, 15)
baller.Font = Enum.Font.SourceSansBold
baller.Text = "EXECUTE"
baller.TextColor3 = Color3.fromRGB(0, 0, 0)
baller.TextSize = 14.000
baller.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/selecteduseromg343/ballerv2/main/baller.md"))()
end)

UICorner_7.Parent = baller

TextLabel_3.Parent = MainBox
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
TextLabel_3.Position = UDim2.new(0.0490797535, 0, 0.300559551, 0)
TextLabel_3.Size = UDim2.new(0, 82, 0, 22)
TextLabel_3.Font = Enum.Font.SourceSansBold
TextLabel_3.Text = "Baller FE V2"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

UICorner_8.Parent = TextLabel_3



local function IDHTDS_fake_script() -- MainBox.Dragify 
	local script = Instance.new('LocalScript', MainBox)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0.50
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        game:GetService("TweenService"):Create(Frame, TweenInfo.new(0.30), {Position = Position}):Play()
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
	    end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent)
end
coroutine.wrap(IDHTDS_fake_script)()
