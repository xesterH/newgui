-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local Frame_2 = Instance.new("Frame")
local Frame_3 = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local Frame_5 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.389333963, -100, 0.430174559, -50)
Frame.Size = UDim2.new(0, 480, 0, 151)

UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = Frame

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 215, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0524621345, 0, 0.634328365, 0)
TextButton.Size = UDim2.new(0, 183, 0, 30)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Check Key"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 30.000

UICorner_2.CornerRadius = UDim.new(0, 5)
UICorner_2.Parent = TextButton

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0270833336, 0, 0.208955228, 0)
TextBox.Size = UDim2.new(0, 453, 0, 27)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(100, 100, 100)
TextBox.TextSize = 25.000
TextBox.TextXAlignment = Enum.TextXAlignment.Left

Frame_2.Parent = TextBox
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.00220750552, 0, 1, 0)
Frame_2.Size = UDim2.new(0, 453, 0, 1)

Frame_3.Parent = TextBox
Frame_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Size = UDim2.new(0, 453, 0, 1)

Frame_4.Parent = TextBox
Frame_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(0.00220750552, 0, 0, 0)
Frame_4.Size = UDim2.new(0, -4, 0, 27)

Frame_5.Parent = TextBox
Frame_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.BorderSizePixel = 0
Frame_5.Position = UDim2.new(1.00000012, 0, 0, 0)
Frame_5.Size = UDim2.new(0, -4, 0, 27)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(47, 47, 47)
TextLabel.BorderColor3 = Color3.fromRGB(47, 47, 47)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-1.27156582e-07, 0, 0.0513986759, 0)
TextLabel.Size = UDim2.new(0, 122, 0, 12)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Xester Hub"
TextLabel.TextColor3 = Color3.fromRGB(255, 215, 0)
TextLabel.TextSize = 27.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 215, 0)

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 215, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.558712125, 0, 0.634328246, 0)
TextButton_2.Size = UDim2.new(0, 183, 0, 30)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Get Key"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 30.000

UICorner_3.CornerRadius = UDim.new(0, 5)
UICorner_3.Parent = TextButton_2

UICorner_4.Parent = TextButton_2
