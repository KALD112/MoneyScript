local player = game.Players.LocalPlayer or game.Players:GetChildren()[1]

if not player:FindFirstChild("leaderstats") then
    local stats = Instance.new("Folder")
    stats.Name = "leaderstats"
    stats.Parent = player
end

if not player.leaderstats:FindFirstChild("Money") then
    local money = Instance.new("IntValue")
    money.Name = "Money"
    money.Value = 0
    money.Parent = player.leaderstats
end

player.leaderstats.Money.Value = player.leaderstats.Money.Value + 1000

print("تمت إضافة 1000 فلوس 🎉")
