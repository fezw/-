local CoreGui = game:GetService("StarterGui")

CoreGui:SetCore("SendNotification", {
    Title = "你的脚本",
    Text = "正在加载风族脚本V1",
    Duration = 5, 
})
print("风族帮你开启了反挂机")
		local vu = game:GetService("VirtualUser")
		game:GetService("Players").LocalPlayer.Idled:connect(function()
		   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		   wait(1)
		   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		end)
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/asehbzi/gay/refs/heads/main/gay')))()
local Window = OrionLib:MakeWindow({Name = "风族脚本V1", HidePremium = false, SaveConfig = true,IntroText = "欢迎使用风族脚本V1", ConfigFolder = "欢迎使用风族脚本V1"})
local about = Window:MakeTab({
    Name = "信息",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

about:AddParagraph("您的用户名:"," "..game.Players.LocalPlayer.Name.."")
about:AddParagraph("您的注入器:"," "..identifyexecutor().."")
about:AddParagraph("您当前服务器的ID"," "..game.GameId.."")
about:AddParagraph("作者qq暂时不暴露")
about:AddParagraph("qq官方群暂时不做不暴露")
about:AddParagraph("作者：风族牛逼")
about:AddParagraph("作者快手暂时不暴露")
about:AddParagraph("免费脚本请不要倒卖")
about:AddParagraph("也不要外传")

local Tab = Window:MakeTab({
  Name = "通用脚本",
  Icon = "rbxassetid://4483345998",
  PremiumOnly = false
  })
Tab:AddButton({
	Name = "飞行",
	Callback = function()

loadstring(game:HttpGet("https://pastebin.com/raw/u8rthPGW"))()

end
})
Tab:AddButton({
	Name = "透视",
	Callback = function()

loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/UNIVERSALESPLTX/main/README.md'),true))()

end
})
Tab:AddButton({
	Name = "聊天绕过",
	Callback = function()
	
loadstring(game:HttpGet("https://raw.githubusercontent.com/BingusWR/Fechatbypassroblox/refs/heads/main/Fe%20Roblox%20ChatBypass"))()
	
end
})
Tab:AddButton({
	Name = "帽子旋转",
	Callback = function()
	
loadstring(game:HttpGet("https://raw.githubusercontent.com/BingusWR/Fe-Spinning-Hat-Script/refs/heads/main/Fe%20Spinning%20Hats%20Script"))()

end
})
Tab:AddButton({
	Name = "r15变r6",
	Callback = function()
	
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-R6-Animations-on-R15-16865"))()

end
})
Tab:AddButton({
	Name = "选人甩飞（需要输入别人的名字）",
	Callback = function()
	
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Auto%20Fling%20Player'))()

end
})
Tab:AddButton({
	Name = "阿尔宙斯自瞄",
	Callback = function()
	
loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/chillz-workshop/main/Arceus%20Aimbot.lua"))()

end
})
Tab:AddButton({
	Name = "换皮肤（需要别人id还需要加入群组Hell_$treet）",
	Callback = function()
	
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\73\110\118\111\111\107\101\114\49\49\47\79\117\116\102\105\116\47\109\97\105\110\47\79\117\116\102\105\116\67\111\112\105\101\114\46\108\117\97\34\44\32\116\114\117\101\41\41\40\41\10")()

end

})
Tab:AddButton({
	Name = "键盘脚本",
	Callback = function()
	
loadstring(game:HttpGet("https://raw.githubusercontent.com/Xxtan31/Ata/main/deltakeyboardcrack.txt", true))()

end
})
Tab:AddButton({
	Name = "无限收益（copyid 输入别人名字获得id可搭配换皮肤使用）",
	Callback = function()
	
loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()

end
})
Tab:AddButton({
	Name = "光影",
	Callback = function()
	
loadstring(game:HttpGet(('https://pastefy.app/xXkUxA0P/raw'),true))()

end
})
Tab:AddButton({
	Name = "无头加kor",
	Callback = function()
	
loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Permanent-Headless-And-korblox-Script-4140"))()

end
})
Tab:AddButton({
	Name = "Shift Lock",
	Callback = function()
	
-- made by fedoratum.

-- Gui to Lua
-- Version: 3.2

-- Instances:

local ShiftlockStarterGui = Instance.new("ScreenGui")
local ImageButton = Instance.new("ImageButton")

--Properties:

ShiftlockStarterGui.Name = "Shiftlock (StarterGui)"
ShiftlockStarterGui.Parent = game.CoreGui
ShiftlockStarterGui.ZIndexBehavior =  Enum.ZIndexBehavior.Sibling
ShiftlockStarterGui.ResetOnSpawn = false

ImageButton.Parent = ShiftlockStarterGui
ImageButton.Active = true
ImageButton.Draggable = true
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.921914339, 0, 0.552375436, 0)
ImageButton.Size = UDim2.new(0.0636147112, 0, 0.0661305636, 0)
ImageButton.SizeConstraint = Enum.SizeConstraint.RelativeXX
ImageButton.Image = "http://www.roblox.com/asset/?id=182223762"

-- Scripts:

local function TLQOYN_fake_script() -- ImageButton.ShiftGUI 
	local script = Instance.new('LocalScript', ImageButton)

	local MobileCameraFramework = {}
	local players = game:GetService("Players")
	local runservice = game:GetService("RunService")
	local CAS = game:GetService("ContextActionService")
	local player = players.LocalPlay# -
