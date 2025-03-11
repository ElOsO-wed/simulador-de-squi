-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ImageButton = Instance.new("ImageButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local UICorner_6 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

ImageButton.Parent = ScreenGui
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0, 0, 0.533227861, 0)
ImageButton.Size = UDim2.new(0, 76, 0, 37)
ImageButton.Image = "http://www.roblox.com/asset/?id=115828081273710"

UICorner.Parent = ImageButton

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Size = UDim2.new(0, 162, 0, 169)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(9, 9, 9)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 162, 0, 34)
TextLabel.Font = Enum.Font.LuckiestGuy
TextLabel.Text = "Simulador de carrera de squi"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.TextWrapped = true

UICorner_3.Parent = TextLabel

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.846808791, 0)
TextLabel_2.Size = UDim2.new(0, 162, 0, 25)
TextLabel_2.Font = Enum.Font.LuckiestGuy
TextLabel_2.Text = "YT: YANSER_EXPLOIT"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.TextWrapped = true

UICorner_4.Parent = TextLabel_2

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(1, 0, 0.012765957, 0)
TextButton.Size = UDim2.new(0, 33, 0, 18)
TextButton.Font = Enum.Font.LuckiestGuy
TextButton.Text = "-"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(1.20603013, 0, 0.012765957, 0)
TextButton_2.Size = UDim2.new(0, 33, 0, 18)
TextButton_2.Font = Enum.Font.LuckiestGuy
TextButton_2.Text = "X"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.396449715, 0)
TextLabel_3.Size = UDim2.new(0, 129, 0, 34)
TextLabel_3.Font = Enum.Font.LuckiestGuy
TextLabel_3.Text = "Infinito Giros"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

UICorner_5.Parent = TextLabel_3

UICorner_6.Parent = TextLabel_3

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(140, 140, 140)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.790123641, 0, 0.426035583, 0)
TextButton_3.Size = UDim2.new(0, 35, 0, 25)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = ""
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

UICorner_7.Parent = TextButton_3

-- Scripts:

local function PCSJK_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	local player = game.Players.LocalPlayer 
	
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui.ScreenGui.Frame.Visible = true
	end)
end
coroutine.wrap(PCSJK_fake_script)()
local function JINQXV_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local button = script.Parent -- El botón
	local frame = button.Parent -- El Frame que se va a minimizar
	local labels = frame:GetChildren() -- Todos los elementos dentro del Frame
	local minimized = false -- Estado del frame
	
	-- Busca el primer TextLabel para mantener visible cuando minimiza
	local mainLabel = nil
	for _, child in pairs(labels) do
		if child:IsA("TextLabel") then
			mainLabel = child
			break -- Solo tomamos el primero
		end
	end
	
	-- Función para minimizar o expandir
	local function toggleFrame()
		minimized = not minimized
	
		if minimized then
			frame.Size = UDim2.new(0, 200, 0, 30) -- Cambia el tamaño del frame
			button.Text = "+" -- Cambia el texto del botón
	
			-- Ocultar todos los labels excepto el principal
			for _, child in pairs(labels) do
				if child:IsA("TextLabel") and child ~= mainLabel then
					child.Visible = false
				end
			end
		else
			frame.Size = UDim2.new(0, 200, 0, 200) -- Tamaño original
			button.Text = "-" -- Cambia el texto del botón
	
			-- Mostrar todos los labels nuevamente
			for _, child in pairs(labels) do
				if child:IsA("TextLabel") then
					child.Visible = true
				end
			end
		end
	end
	
	-- Conectar la función al evento del botón
	button.MouseButton1Click:Connect(toggleFrame)
	
end
coroutine.wrap(JINQXV_fake_script)()
local function WVBFIRB_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local player = game.Players.LocalPlayer 
	
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui.ScreenGui.Frame.Visible = false
	end)
end
coroutine.wrap(WVBFIRB_fake_script)()
local function IKHEH_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	local button = script.Parent -- Referencia al TextButton
	local scriptRunning = false -- Controla si el script está activo
	local loopTask -- Variable para la tarea del bucle
	
	local function startLoop()
		while scriptRunning do
			wait(0.1) -- Espera 0.1 segundos
			game:GetService("ReplicatedStorage").Remotes.Gifts.RequestSpinReward:InvokeServer()
		end
	end
	
	local function onButtonClick()
		if not scriptRunning then
			-- Activar script
			scriptRunning = true
			button.Text = "" -- Cambia el texto
			button.BackgroundColor3 = Color3.fromRGB(255, 0, 0) -- Cambia a rojo
	
			-- Iniciar el bucle en una nueva tarea
			loopTask = task.spawn(startLoop)
		else
			-- Desactivar script
			scriptRunning = false
			button.Text = "" -- Cambia el texto
			button.BackgroundColor3 = Color3.fromRGB(170, 170, 170) -- Cambia a gris
		end
	end
	
	button.MouseButton1Click:Connect(onButtonClick) -- Detecta clics en el botón
	
	
end
coroutine.wrap(IKHEH_fake_script)()
