for _, v in pairs(getconnections(game.Players.LocalPlayer.Idled)) do
    v:Disable()
end


loadstring(game:HttpGet("https://pastefy.app/j7uTuprn/raw"))()
loadstring(game:HttpGet("https://pastefy.app/imJbbsHT/raw"))()
------------------garante o respawn com aura ativada-------
local player = game.Players.LocalPlayer 
player.CharacterAdded:Connect(function()
local args = {
    [1] = {
        ["Character"] = workspace:WaitForChild(player.Name),
        ["Action"] = "Cursed_Energy",
        ["MiscData"] = game:GetService("Players").LocalPlayer:WaitForChild("UIStats")
    }
}
game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("CombatEvent"):FireServer(unpack(args))
end)
----------------------------
loop1 = false
looop = false 
ativo1 = false
ativo = false
------screengui principal------
s = i("ScreenGui", game.CoreGui)
farm1 = {}
auto1 = {}
skill1 = {}
tp1 = {}
boss1 = {}
-----------
aberto = i("ScrollingFrame", workspace)
    b(aberto, 0.47, 0, 0.849, 0)
    p(aberto, 0.25, 0, 0.05, 0)

aberto.BackgroundTransparency = 0.7

cor(aberto, 0, 0, 0)

farmar = i("ScreenGui", aberto)

------farm gui-------
farm = i("TextButton", aberto)
    b(farm, 0.1, 0, 0.1, 0)
    p(farm, 0.25, 0, 0.05, 0)
farm.Text = "FARMS"
farmar.Parent = workspace
-----------------------
auto = i("TextButton", farmar)
    b(auto, 0.1, 0, 0.1, 0)
    p(auto, 0.25, 0, 0.17, 0)
auto.Text = "Auto"
----------------------
skill = i("TextButton", farmar)
    b(skill, 0.1, 0, 0.1, 0)
    p(skill, 0.25, 0, 0.29, 0)
skill.Text = "skills"

tp = i("TextButton", farmar)
    b(tp, 0.1, 0, 0.1, 0)
    p(tp, 0.25, 0, 0.41, 0)
tp.Text = "TP"
boss = i("TextButton", farmar)
    b(boss, 0.1, 0, 0.1, 0)
    p(boss, 0.25, 0, 0.53, 0)
boss.Text = "bosses"
--------opçoès da barra farmar
sorcer = i("TextButton", aberto)
    b(sorcer, 0.2, 0, 0.06, 0)
    p(sorcer, 0.75, 0, 0.1, 0)
sorcer.Text = "auto sorceres"
auto_sorcerer = i("TextLabel", aberto)
    b(auto_sorcerer, 0.4, 0, 0.04, 0)
    p(auto_sorcerer, 0.6, 0, 0.02, 0)
auto_sorcerer.Text = "auto sorcer"
table.insert(farm1, auto_sorcerer)
table.insert(farm1, sorcer)

cor(auto_sorcerer, 255, 0, 0)
-------
auto_dummy = i("TextLabel", aberto)
    b(auto_dummy, 0.4, 0, 0.04, 0)
    p(auto_dummy, 0.6, 0, 0.2, 0)
auto_dummy.Text = "auto punch dummy"
table.insert(farm1, auto_dummy)
cor(auto_dummy, 255, 0, 0)
------
table.insert(farm1, auto_dummy)
foto_sorcerer = i("ImageLabel", aberto)
    b(foto_sorcerer, 0.2, 0, 0.1, 0)
    p(foto_sorcerer, 0.4, 0, 0.001, 0)
foto_sorcerer.Image = "rbxassetid://81031392374218"
table.insert(farm1, foto_sorcerer)
------------------
foto_dummy = i("ImageLabel", aberto)

    b(foto_dummy, 0.2, 0, 0.1, 0)
    p(foto_dummy, 0.4, 0, 0.2, 0)
foto_dummy.Image = "rbxassetid://106523851285306"
------------------
table.insert(farm1, foto_dummy)
---------
dummy = i("TextButton", aberto)
    b(dummy, 0.2, 0, 0.06, 0)
    p(dummy, 0.75, 0, 0.25, 0)
dummy.Text = "auto dummy"
table.insert(farm1, dummy)
        open = i("TextButton", s)
    b(open, 0.1, 0, 0.1, 0)
    p(open, 0.43, 0, -0.05, 0)
open.Text = "open menu"
for _, farmss in ipairs(farm1) do
    
    farmss.Parent = workspace
end
local kill = {
punch = function(quem)
local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild("HumanoidRootPart") 
local npc = workspace:FindFirstChild(quem)
if npc then
local ht = npc:FindFirstChild("HumanoidRootPart")
humanoidrootpart.CFrame = ht.CFrame
local args = {
    [1] = {
        ["Character"] = workspace:WaitForChild(player.Name),
        ["Action"] = "M1",
        ["Combo"] = 1,
        ["Target"] = workspace:WaitForChild(quem),
        ["BehindPlayer"] = false
    }
}
game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("CombatEvent"):FireServer(unpack(args))
end
end
}
------ auto tab--------
auto_resist = i("TextLabel", workspace)
    b(auto_resist, 0.4, 0, 0.04, 0)
    p(auto_resist, 0.6, 0, 0.35, 0)
auto_resist.Text = "auto resist"
cor(auto_resist, 255, 0, 0)
table.insert(auto1, auto_resist)
auto_dash = i("TextLabel", workspace)
    b(auto_dash, 0.4, 0, 0.04, 0)
    p(auto_dash, 0.6, 0, 0.2, 0)
auto_dash.Text = "auto dash"
auto_squat = i("TextLabel", workspace)
    b(auto_squat, 0.4, 0, 0.04, 0)
    p(auto_squat, 0.6, 0, 0.02, 0)
auto_squat.Text = "auto squat"
cor(auto_squat, 255, 0, 0)
cor(auto_dash, 255, 0, 0)
table.insert(auto1, auto_squat)
 comboio = i("TextButton", workspace)
    b(comboio, 0.2, 0, 0.06, 0)
    p(comboio, 0.75, 0, 0.1, 0)
comboio.Text = "auto squat"
table.insert(auto1, comboio)
table.insert(auto1, auto_dash)
dash = i("TextButton", workspace)
    b(dash, 0.2, 0, 0.06, 0)
    p(dash, 0.75, 0, 0.25, 0)
dash.Text = "auto dash"
table.insert(auto1, dash)
punch = i("TextButton", workspace)
    b(punch, 0.2, 0, 0.06, 0)
    p(punch, 0.75, 0, 0.4, 0)
punch.Text = "inf strenght farm"
table.insert(auto1, punch)
---------------------
------skills------------
auto_x = i("TextButton", workspace)
    b(auto_x, 0.2, 0, 0.06, 0)
    p(auto_x, 0.75, 0, 0.0, 0)
auto_x.Text = "auto x"
table.insert(skill1, auto_x)
auto_z = i("TextButton", workspace)
    b(auto_z, 0.2, 0, 0.06, 0)
    p(auto_z, 0.75, 0, 0.08, 0)
auto_z.Text = "auto z"
table.insert(skill1, auto_z)
auto_c = i("TextButton", workspace)
    b(auto_c, 0.2, 0, 0.06, 0)
    p(auto_c, 0.75, 0, 0.16, 0)
auto_c.Text = "auto c"
table.insert(skill1, auto_c)
auto_v = i("TextButton", workspace)
    b(auto_v, 0.2, 0, 0.06, 0)
    p(auto_v, 0.75, 0, 0.24, 0)
auto_v.Text = "auto v"
table.insert(skill1, auto_v)

auto_b = i("TextButton", workspace)
    b(auto_b, 0.2, 0, 0.06, 0)
    p(auto_b, 0.75, 0, 0.32, 0)
auto_b.Text = "auto b"
table.insert(skill1, auto_b)
auto_n = i("TextButton", workspace)
    b(auto_n, 0.2, 0, 0.06, 0)
    p(auto_n, 0.75, 0, 0.41, 0)
auto_n.Text = "auto n"
table.insert(skill1, auto_n)
------
--------tp tab-----------
mi = i("TextButton", workspace)
    b(mi, 0.2, 0, 0.06, 0)
    p(mi, 0.75, 0, 0, 0)
mi.Text = "parque miyashi"
me = i("TextButton", workspace)
    b(me, 0.2, 0, 0.06, 0)
    p(me, 0.75, 0, 0.1, 0)
me.Text = "subway"
ma = i("TextButton", workspace)
    b(ma, 0.2, 0, 0.06, 0)
    p(ma, 0.75, 0, 0.2, 0)
ma.Text = "spin location"

 ab = i("TextButton", workspace)
    b(ab, 0.2, 0, 0.06, 0)
    p(ab, 0.75, 0, 0.29, 0)
ab.Text = "jujutsu auto"
table.insert(tp1, ab)
table.insert(tp1, ma)
table.insert(tp1, mi)
table.insert(tp1, me)
-------------------------------
---------------bosses farm--------------
su = i("TextButton", workspace)
    b(su, 0.2, 0, 0.06, 0)
    p(su, 0.75, 0, 0., 0)
su.Text = "sukuna boss"
mg = i("TextButton", workspace)
    b(mg, 0.2, 0, 0.06, 0)
    p(mg, 0.75, 0, 0.1, 0)
mg.Text = "meguna boss"
he = i("TextButton", workspace)
    b(he, 0.2, 0, 0.06, 0)
    p(he, 0.75, 0, 0.2, 0)
he.Text = "sukuna heian"
cho = i("TextButton", workspace)
    b(cho, 0.2, 0, 0.06, 0)
    p(cho, 0.75, 0, 0.3, 0)
cho.Text = "choso"
ka = i("TextButton", workspace)
    b(ka, 0.2, 0, 0.06, 0)
 p(ka, 0.75, 0, 0.4, 0)
ka.Text = "kashimo"
goj = i("TextButton", workspace)
    b(goj, 0.2, 0, 0.06, 0)
 p(goj, 0.75, 0, 0.5, 0)
goj.Text = "satoru gojo"
table.insert(boss1, goj)
table.insert(boss1, ka)
table.insert(boss1, cho)
table.insert(boss1, he)
table.insert(boss1, mg)
table.insert(boss1, su)
---------------
loop = false
open.MouseButton1Click:Connect(function()
loop = not loop
if loop then
  farm.Parent = farmar
farmar.Parent = s
open.Text = "desopen"
aberto.Parent = s
farm.MouseButton1Click:Connect(function()
cor(farm, 9, 235, 28)
     cor(skill, 156, 156, 156)
    cor(tp, 156, 156, 156)
    cor(boss, 156, 156, 156)
    for _, boss in ipairs(boss1) do
    boss.Parent = workspace
        
    end
    
    for _, tps in ipairs(tp1) do
        tps.Parent = workspace
        
        
    end
    
    
    
    for _, skills in ipairs(skill1) do
        
        skills.Parent = workspace
        
    end
    
for _, autos in ipairs(auto1) do
        autos.Parent = workspace
        
    end
   
  cor(auto, 156, 156, 156)
  for _, farmss in ipairs(farm1) do
    
    farmss.Parent = aberto
    
end
  
end)
else
open.Text = "open"
farmar.Parent = workspace
aberto.Parent = workspace
end


end)








loop1 = false

sorcer.MouseButton1Click:Connect(function()
  loop1 = not loop1
  if loop1 then
    function sorc()
      while loop1 do
      wait(0.01)
        if loop1 then
kill.punch("Sorcerer")
        end
      end
    end
    sorcer.Text = "deactivate"
    coroutine.wrap(sorc)()
  cor(sorcer, 0, 182, 232)
    player.CharacterAdded:Connect(function()
      coroutine.wrap(sorc)()
    end)
  else
      ativo1 = false
    sorcer.Text = "auto sorceres"
    cor(sorcer, 156, 156, 156)
  end
end)
------------------------------------
looop = false
dummy.MouseButton1Click:Connect(function()
  
  looop = not looop
  if looop then
    function dum()
      while looop do
        wait(0.1)
        if looop then
kill.punch("Dummy")
        end
      end
    end
    dummy.Text = "deactivate"
    coroutine.wrap(dum)()
    cor(dummy, 0, 182, 232)
    player.CharacterAdded:Connect(function()
      coroutine.wrap(dum)()
      
    end)
  else
    dummy.Text = "auto dummy"
    cor(dummy, 156, 156, 156)
  end
end)

auto.MouseButton1Click:Connect(function()
    
    cor(boss, 156, 156, 156)
    for _, boss in ipairs(boss1) do
    boss.Parent = workspace
        
    end
    
    cor(auto, 9, 235, 28)
    cor(skill, 156, 156, 156)
    cor(tp, 156, 156, 156)
    for _, tps in ipairs(tp1) do
        tps.Parent = workspace
        
        
    end
    
    for _, skills in ipairs(skill1) do
        
        skills.Parent = workspace
        
    end
    
     cor(farm, 156, 156, 156)
    for _, farmss in ipairs(farm1) do
    
    farmss.Parent = workspace
    
end
    for _, autos in ipairs(auto1) do
        autos.Parent = aberto
        
    end
end)
loc = false
comboio.MouseButton1Click:Connect(function()
    loc = not loc
    if loc then
    cor(comboio,  0, 182, 232)
        
        function a()
        while loc do
            wait(0.01)
            if loc then
        
                local player = game.Players.LocalPlayer
                local args = {
    [1] = {
        ["Character"] = workspace:WaitForChild(player.Name),
        ["Action"] = "Endurance",
        ["MiscData"] = game:GetService("Players").LocalPlayer:WaitForChild("UIStats")
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("CombatEvent"):FireServer(unpack(args))

            end
        end
        end
        comboio.Text = "deactive"
    coroutine.wrap(a)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(a)()
            
        end)
    else
        comboio.Text = "auto squat"
    cor(comboio, 156, 156, 156)
    end
end)

lof = false
dash.MouseButton1Click:Connect(function()
    
    lof = not lof
    if lof then
        cor(dash, 0, 182, 232)
        dash.Text = "deactive"
        function aa()
            while lof do
                wait(0.1)
                if lof then
                    local player = game.Players.LocalPlayer 
            local args = {
    [1] = {
        ["Character"] = workspace:WaitForChild(player.Name),
        ["Action"] = "Dash",
        ["Dir"] = Vector3.new(0.1733149141073227, 0, 0.9848664999008179),
        ["Anim"] = game:GetService("ReplicatedStorage"):WaitForChild("Animations"):WaitForChild("Combat"):WaitForChild("FrontDash"),
        ["MiscData"] = game:GetService("Players").LocalPlayer:WaitForChild("UIStats")
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("CombatEvent"):FireServer(unpack(args))

            end
        end
        end
        coroutine.wrap(aa)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(aa)()
            
        end)
    else
        dash.Text = "auto dash"
        cor(dash, 156, 156, 156)
    end
end)

l = false
punch.MouseButton1Click:Connect(function()
  l = not l
if l then  
    
    cor(punch, 0, 182, 232)
    punch.Text = "deactive"
else
    punch.Text = "inf strength farm"
    cor(punch, 156, 156, 156)
end
end)



skill.MouseButton1Click:Connect(function()
    
    cor(boss, 156, 156, 156)
    for _, boss in ipairs(boss1) do
    boss.Parent = workspace
        
    end
    
    for _, tps in ipairs(tp1) do
        tps.Parent = workspace
        
        
    end
    cor(tp, 156, 156, 156)
    
    cor(skill, 9, 235, 28)
        
        cor(farm, 156, 156, 156)
        cor(auto, 156, 156, 156)
        
    for _, autoss in ipairs(auto1) do
        
        autoss.Parent = workspace
        
    end
    for _, farmss in ipairs(farm1) do
        
        farmss.Parent = workspace
        
    end
    for _, skills in ipairs(skill1) do
        
        skills.Parent = aberto
        
    end
end)



loop1 = false
auto_x.MouseButton1Click:Connect(function()
    loop1 = not loop1 
    if loop1 then
    cor(auto_x, 0, 182, 232)
        auto_x.Text = "deactive"
        function ao()
            while loop1 do
                wait(0.1)
            if loop1 then
            game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.X,false,game)
                
            end
            end
        end
        coroutine.wrap(ao)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(ao)()
            
            
        end)
    else
        cor(auto_x, 156, 156,156)
        auto_x.Text = "auto x skill"
    end
end)

lopy = false
auto_z.MouseButton1Click:Connect(function()
    lopy = not lopy
    
    if lopy then
        function il()
            while lopy do
                wait(0.01)
                if lopy then
            
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.Z,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il)()
        
    end)
        auto_z.Text = "deactive"
        cor(auto_z, 0, 182, 232)
    else
        auto_z.Text = "auto z"
        cor(auto_z, 156, 156, 156)
    end
end)




loopy = false
auto_c.MouseButton1Click:Connect(function()
    loopy = not loopy
    
    if loopy then
        function il()
            while loopy do
                wait(0.01)
                if loopy then
            
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.C,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il)()
        
    end)
        auto_c.Text = "deactive"
        cor(auto_c, 0, 182, 232)
    else
        auto_c.Text = "auto c"
        cor(auto_c, 156, 156, 156)
    end
end)



loopy2 = false
auto_v.MouseButton1Click:Connect(function()
    loopy2 = not loopy2
    
    if loopy2 then
        function il2()
            while loopy2 do
                wait(0.01)
                if loopy2 then
            
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.V,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il2)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il2)()
        
    end)
        auto_v.Text = "deactive"
        cor(auto_v, 0, 182, 232)
    else
        auto_v.Text = "auto v"
        cor(auto_v, 156, 156, 156)
    end
end)


loopy3 = false
auto_b.MouseButton1Click:Connect(function()
    loopy3 = not loopy3
    
    if loopy3 then
        function il3()
            while loopy3 do
                wait(0.01)
                if loopy3 then
            
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.B,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il3)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il3)()
        
    end)
        auto_b.Text = "deactive"
        cor(auto_b, 0, 182, 232)
    else
        auto_b.Text = "auto b"
        cor(auto_b, 156, 156, 156)
    end
end)


loopy4 = false
auto_n.MouseButton1Click:Connect(function()
    loopy4 = not loopy4
    
    if loopy4 then
        function il4()
            while loopy4 do
                wait(0.01)
                if loopy4 then
            
                    game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.N,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il4)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il4)()
        
    end)
        auto_n.Text = "deactive"
        cor(auto_n, 0, 182, 232)
    else
        auto_n.Text = "auto n"
        cor(auto_n, 156, 156, 156)
    end
end)



tp.MouseButton1Click:Connect(function()
    
    cor(boss, 156, 156, 156)
    for _, boss in ipairs(boss1) do
    boss.Parent = workspace
        
    end
    
    
    cor(tp, 9, 235, 28)
       cor(skill, 156, 156, 156) 
        cor(farm, 156, 156, 156)
        cor(auto, 156, 156, 156)
        
    for _, autoss in ipairs(auto1) do
        
        autoss.Parent = workspace
        
    end
    for _, farmss in ipairs(farm1) do
        
        farmss.Parent = workspace
        
    end
    for _,  skills in ipairs(skill1) do
        
        skills.Parent = workspace
        
    end
    
    
    for _,  tp in ipairs(tp1) do
        
        tp.Parent = aberto
        
    end
end)


mi.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild("HumanoidRootPart") 
humanoidrootpart.CFrame = CFrame.new(-537, -391, -2205)
    
    
end)


me.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild("HumanoidRootPart") 
humanoidrootpart.CFrame = CFrame.new(-377, -452, -2256)
    
    
end)


ma.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild("HumanoidRootPart") 
humanoidrootpart.CFrame = CFrame.new(-500, -397, -1993)
    
    
end)

ab.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild("HumanoidRootPart") 
humanoidrootpart.CFrame = CFrame.new(-382, -265, 171)
    
    
end)

boss.MouseButton1Click:Connect(function()
    
    
    cor(boss, 9, 235, 28)
    cor(tp, 156, 156, 156)
       cor(skill, 156, 156, 156) 
        cor(farm, 156, 156, 156)
        cor(auto, 156, 156, 156)
        
    for _, autoss in ipairs(auto1) do
        
        autoss.Parent = workspace
        
    end
    for _, farmss in ipairs(farm1) do
        
        farmss.Parent = workspace
        
    end
    for _,  skills in ipairs(skill1) do
        
        skills.Parent = workspace
        
    end
    
    
    for _,  boss in ipairs(boss1) do
        
        boss.Parent = aberto
        
    end
    
    for _,  tp in ipairs(tp1) do
        
        tp.Parent = workdpace
        
    end
end)



loopy5 = false
su.MouseButton1Click:Connect(function()
    loopy5 = not loopy5
    
    if loopy5 then
        function il5()
            while loopy5 do
                wait(0.01)
                if loopy5 then
                    if looop and workspace:FindFirstChild("Sukuna") then
    looop = false
    ativo = true
    
end

if loop1 and workspace:FindFirstChild("Sukuna") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
            
                    kill.punch("Sukuna")
                    
                end
            end
end
    coroutine.wrap(il5)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il5)()
        
    end)
        su.Text = "deactive"
        cor(su, 0, 182, 232)
    else
      
      
      if ativo then
    looop = true
          cor(dummy, 0, 182, 232)
    coroutine.wrap(dum)()
end
if ativo1 then
    ativo1 = false
    loop1 = true
    cor(sorcer, 0, 182, 232)
    coroutine.wrap(sorc)()
end
      
      
        su.Text = "sukuna boss"
        cor(su, 156, 156, 156)
    end
end)

loopy6 = false
mg.MouseButton1Click:Connect(function()
    loopy6 = not loopy6
    
    if loopy6 then
        
        
        function il6()
            while loopy6 do
                wait(0.01)
                if loopy6 then
            if looop and workspace:FindFirstChild("Meguna") then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and workspace:FindFirstChild("Meguna") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
        kill.punch("Meguna")
                    
                    
                end
            end
end
    coroutine.wrap(il6)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il6)()
        
    end)
        mg.Text = "deactive"
        cor(mg, 0, 182, 232)
    else
      if ativo then
          ativo = false
    looop = true
          cor(dummy, 0, 182, 232)
    coroutine.wrap(dum)()
end
if ativo1 then
    ativo1 = false
    loop1 = true
    cor(sorcer, 0, 182, 232)
    coroutine.wrap(sorc)()
end
        
        mg.Text = "meguna boss"
        cor(mg, 156, 156, 156)
    end
end)
loopy7 = false
he.MouseButton1Click:Connect(function()
    loopy7 = not loopy7
    if loopy7 then
        function il7()
            while loopy7 do
                wait(0.01)
                if loopy7 then
                    
                    if looop and workspace:FindFirstChild("UltSukuna") then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end
if loop1 and workspace:FindFirstChild("UltSukuna") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                    kill.punch("UltSukuna")
                end
            end
end
    coroutine.wrap(il7)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il7)()
        
    end)
        he.Text = "deactive"
        cor(he, 0, 182, 232)
    else
      
      
      if ativo then
          cor(dummy, 0, 182, 232)
    looop = true
          ativo = false
    coroutine.wrap(dum)()
end
if ativo1 then
    ativo1 = false
    cor(sorcer, 0, 182, 232)
    loop1 = true
    coroutine.wrap(sorc)()
end
        he.Text = "sukuna heian"
        cor(he, 156, 156, 156)
    end
end)
loopy8 = false
cho.MouseButton1Click:Connect(function()
    loopy8 = not loopy8
    if loopy8 then
        function il8()
            while loopy8 do
                wait(0.01)
                if loopy8 then
                    
            if looop and workspace:FindFirstChild("Choso") then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and workspace:FindFirstChild("Choso") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                    kill.punch("Choso")
                                end
            end
end
    coroutine.wrap(il8)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il8)()
        
    end)
        cho.Text = "deactive"
        cor(cho, 0, 182, 232)
    else
      
      
      if ativo then
          cor(dummy, 0, 182, 232)
    looop = true
          ativo = false
    coroutine.wrap(dum)()
end
if ativo1 then
    ativo1 = false
    cor(sorcer, 0, 182, 232)
    loop1 = true
    coroutine.wrap(sorc)()
end
        cho.Text = "choso"
        cor(cho, 156, 156, 156)
    end
end)
loopy97 = false
ka.MouseButton1Click:Connect(function()
    loopy97 = not loopy97
    if loopy97 then
        function il97()
            while loopy97 do
                wait(0.01)
                if loopy97 then
             if looop and workspace:FindFirstChild("Kashimo") then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end
if loop1 and workspace:FindFirstChild("Kashimo") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                                    kill.punch("Kashimo")
                    
                end
            end
end
    coroutine.wrap(il97)()
    player.CharacterAdded:Connect(function()
        coroutine.wrap(il97)()
    end)
        ka.Text = "deactive"
        cor(ka, 0, 182, 232)
    else
      if ativo then
    looop = true
          cor(dummy, 0, 182, 232)
          ativo = false
    coroutine.wrap(dum)()
end
if ativo1 then
    ativo1 = false
    cor(sorcer, 0, 182, 232)
    loop1 = true
    coroutine.wrap(sorc)()
end
        ka.Text = "kashimo"
        cor(ka, 156, 156, 156)
    end
end)
loopy9 = false
goj.MouseButton1Click:Connect(function()
    loopy9 = not loopy9
    if loopy9 then
        function il9()
            while loopy9 do
                wait(0.01)
                if loopy9 then
            if looop and  workspace:FindFirstChild("TheStrongest") then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and  workspace:FindFirstChild("TheStrongest") then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
         
                    kill.punch("TheStrongest")
                end
            end
end
    coroutine.wrap(il9)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il9)()
    end)
        goj.Text = "deactive"
        cor(goj, 0, 182, 232)
    else
      
      if ativo then
    looop = true
          cor(dummy, 0, 182, 232)
          ativo = false
    coroutine.wrap(dum)()
end
if ativo1 then
    cor(sorcer, 0, 182, 232)
    ativo1 = false
    loop1 = true
    coroutine.wrap(sorc)()
end
        goj.Text = "gojo"
        cor(goj, 156, 156, 156)
    end
end)
