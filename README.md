local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextBox = Instance.new("TextBox")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.427720428, -100, 0.322942644, -50)
Frame.Size = UDim2.new(0, 338, 0, 242)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 338, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Xester Hub-Key System"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 40.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0710059181, 0, 0.512396693, 0)
TextButton.Size = UDim2.new(0, 139, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Get Key"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.526627243, 0, 0.512396693, 0)
TextButton_2.Size = UDim2.new(0, 139, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Check Key"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.115384616, 0, 0.760330558, 0)
TextButton_3.Size = UDim2.new(0, 262, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Discord"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 40.000

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0, 0, 0.239669427, 0)
TextBox.Size = UDim2.new(0, 338, 0, 50)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = "Your Key"
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 30.000
