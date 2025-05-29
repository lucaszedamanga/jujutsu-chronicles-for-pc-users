local b='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/'
function mJiBOYhEyTHxlVwzztrRB(data) m=string.sub(data, 0, 55) data=data:gsub(m,'')

data = string.gsub(data, '[^'..b..'=]', '') return (data:gsub('.', function(x) if (x == '=') then return '' end local r,f='',(b:find(x)-1) for i=6,1,-1 do r=r..(f%2^i-f%2^(i-1)>0 and '1' or '0') end return r; end):gsub('%d%d%d?%d?%d?%d?%d?%d?', function(x) if (#x ~= 8) then return '' end local c=0 for i=1,8 do c=c+(x:sub(i,i)=='1' and 2^(8-i) or 0) end return string.char(c) end)) end


 


local aba = function()

for _, v in pairs(getconnections(game.Players.LocalPlayer.Idled)) do
    v:Disable()
end


loadstring(game:HttpGet(mJiBOYhEyTHxlVwzztrRB('vNEwZwAqapygDWMRbPXhatJhuzRtkEOrLUbRISvhWCCJHtILFkYNLFjaHR0cHM6Ly9wYXN0ZWZ5LmFwcC9qN3VUdXBybi9yYXc=')))()
loadstring(game:HttpGet(mJiBOYhEyTHxlVwzztrRB('ooOAUjxlpIrOHRwNYJZMKckhAqUFMWeqbwKKYclyattxjrAiMizuQNkaHR0cHM6Ly9wYXN0ZWZ5LmFwcC9pbUpiYnNIVC9yYXc=')))()
------------------garante o respawn com aura ativada-------
local player = game.Players.LocalPlayer 
player.CharacterAdded:Connect(function()
local args = {
    [1] = {
        [mJiBOYhEyTHxlVwzztrRB('jEZcecdcxlGHrOPafWzNHnjNqXyDBRldZenzQEebYRNvtojpGdmCTwmQ2hhcmFjdGVy')] = workspace:WaitForChild(player.Name),
        [mJiBOYhEyTHxlVwzztrRB('pGrwLxMUKtGbBqoCYzHVqjkdAuuydtZaSYDeptUjFJwHXnuvMGisysPQWN0aW9u')] = mJiBOYhEyTHxlVwzztrRB('FagPTCPpDJhrWQsWfsSgXTNaKDoFefJirUgUJzCWFlmxbTScnjipTheQ3Vyc2VkX0VuZXJneQ=='),
        [mJiBOYhEyTHxlVwzztrRB('qqLnlBmXQawGrrsyRNozxtJzEDLiwTFIJvAmJfYKJptzatvNoGrooXgTWlzY0RhdGE=')] = game:GetService(mJiBOYhEyTHxlVwzztrRB('GzMJMiMsyKTzOTyGRokEQOhUFsnsllAaErZlXkuQqkeWjPWBxihxOsZUGxheWVycw==')).LocalPlayer:WaitForChild(mJiBOYhEyTHxlVwzztrRB('AHXuSSAqgFhnvVabAzukhjMxBZAoDLJlkohMFFLdFeziMLNxedHbFViVUlTdGF0cw=='))
    }
}
game:GetService(mJiBOYhEyTHxlVwzztrRB('ExNjSxqFOCmLcLKEMaTdyJYNjbhbJZcDEeezOrySQsYHQQRybXRLVBTUmVwbGljYXRlZFN0b3JhZ2U=')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('ieWninkfYCiwsJecvnAiVTuLGvelYZeRFThVWldpLSUmEhMCOMjnCDsRXZlbnRz')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('nurxObusJxvJXrDYcTlahChdCeapgmNSrdEbVHUbyqyVBoSnMsjZjPmQ29tYmF0RXZlbnQ=')):FireServer(unpack(args))
end)
----------------------------
loop1 = false
looop = false 
ativo1 = false
ativo = false
------screengui principal------
s = i(mJiBOYhEyTHxlVwzztrRB('tsPHDAGuBUitfbSapQJgDdqcVrYRMUDsLZUquSBVzSSiKXeAAFAUlsPU2NyZWVuR3Vp'), game.CoreGui)
farm1 = {}
auto1 = {}
skill1 = {}
tp1 = {}
boss1 = {}
-----------
aberto = i(mJiBOYhEyTHxlVwzztrRB('sNYbZAumjEVORYOIukFexqzsSIMlvWQNvLviemCDVNqKXgsBHaHnfoeU2Nyb2xsaW5nRnJhbWU='), workspace)
    b(aberto, 0.47, 0, 0.849, 0)
    p(aberto, 0.25, 0, 0.05, 0)

aberto.BackgroundTransparency = 0.7

cor(aberto, 0, 0, 0)

farmar = i(mJiBOYhEyTHxlVwzztrRB('hAkPHlqAjMascjyCihwZOQzotlgwIFVCIbgbqQkFolaITKODWRJVPuAU2NyZWVuR3Vp'), aberto)

------farm gui-------
farm = i(mJiBOYhEyTHxlVwzztrRB('VwypmoSDVTFqDvBkBfozjhXZNIVPgLzvnroEFHUvYlhBPZUErFOWoZxVGV4dEJ1dHRvbg=='), aberto)
    b(farm, 0.1, 0, 0.1, 0)
    p(farm, 0.25, 0, 0.05, 0)
farm.Text = mJiBOYhEyTHxlVwzztrRB('oQJngnRxgcWwjtquQMJHlpDHKVrePIIrzQKnXQHvdzayfRsFvfhKRTvRkFSTVM=')
farmar.Parent = workspace
-----------------------
auto = i(mJiBOYhEyTHxlVwzztrRB('umNBxsSRnenavlxkdVBqsnpLcJpMTofnGzUSZxYoeDyZEsijlHAxXfyVGV4dEJ1dHRvbg=='), farmar)
    b(auto, 0.1, 0, 0.1, 0)
    p(auto, 0.25, 0, 0.17, 0)
auto.Text = mJiBOYhEyTHxlVwzztrRB('obExHQAjaqzKWikvLCHIDRiBsZxIzwYBIrCkaFHBncxItmaMGhqwAGSQXV0bw==')
----------------------
skill = i(mJiBOYhEyTHxlVwzztrRB('qLrNbhBYzGdqsCKTiOSLEwKGwmHsrSEgIyQlrAiTNzUIXgrjyyopeMuVGV4dEJ1dHRvbg=='), farmar)
    b(skill, 0.1, 0, 0.1, 0)
    p(skill, 0.25, 0, 0.29, 0)
skill.Text = mJiBOYhEyTHxlVwzztrRB('TpiKdUSZGLSqwyeTOkOifAhRkHpwaVsGCHhYlmMivPxdboHhgPerKVjc2tpbGxz')

tp = i(mJiBOYhEyTHxlVwzztrRB('RkhxnLzPoEAlouwMKcestvvxNUyynDirvDvMjGiNtrCDrAaFTjKRiKyVGV4dEJ1dHRvbg=='), farmar)
    b(tp, 0.1, 0, 0.1, 0)
    p(tp, 0.25, 0, 0.41, 0)
tp.Text = mJiBOYhEyTHxlVwzztrRB('xFqxoRCnzbqMTGvuwTaojjuYSsNneiUJpDhTBjvIdNPtuqPOIrQeqTPVFA=')
boss = i(mJiBOYhEyTHxlVwzztrRB('UdEDzixgBqXMFBmXKsDajJNuZskrkcWpHMhitGWwLDgaOanibzkOGQfVGV4dEJ1dHRvbg=='), farmar)
    b(boss, 0.1, 0, 0.1, 0)
    p(boss, 0.25, 0, 0.53, 0)
boss.Text = mJiBOYhEyTHxlVwzztrRB('DqoxajGqCpeUfkYQacVNKfaNSCemOhRaCtXAzrcTjhRXPzojutVQXkbYm9zc2Vz')
--------opçoès da barra farmar
sorcer = i(mJiBOYhEyTHxlVwzztrRB('ZEPBfMEhNVvRcSoJmGUSnlpgcLxsyPVDkQrjOquKqmDqjSgPuvXeDKiVGV4dEJ1dHRvbg=='), aberto)
    b(sorcer, 0.2, 0, 0.06, 0)
    p(sorcer, 0.75, 0, 0.1, 0)
sorcer.Text = mJiBOYhEyTHxlVwzztrRB('BLeIxLQaConbLxxLZJfWYoRontsWwMDogUGAzCasPEmdAvAIXHIlMWdYXV0byBzb3JjZXJlcw==')
auto_sorcerer = i(mJiBOYhEyTHxlVwzztrRB('yIdQyMHEgzmljuYLjWeeeYBAUIOZUfefGkUBPlsWsZemGETBOqClfKPVGV4dExhYmVs'), aberto)
    b(auto_sorcerer, 0.4, 0, 0.04, 0)
    p(auto_sorcerer, 0.6, 0, 0.02, 0)
auto_sorcerer.Text = mJiBOYhEyTHxlVwzztrRB('NqAJhGgieyyDHygoJZLFGXyOnLlZTzxrsMxmEvamJXpPEexIKBuLKbmYXV0byBzb3JjZXI=')
table.insert(farm1, auto_sorcerer)
table.insert(farm1, sorcer)

cor(auto_sorcerer, 255, 0, 0)
-------
auto_dummy = i(mJiBOYhEyTHxlVwzztrRB('JkBiYNIJcXRTzSvGxDvXdgdDTVEisCsWNRCZTKjNuDMuGcWzViATnWdVGV4dExhYmVs'), aberto)
    b(auto_dummy, 0.4, 0, 0.04, 0)
    p(auto_dummy, 0.6, 0, 0.2, 0)
auto_dummy.Text = mJiBOYhEyTHxlVwzztrRB('fMIFoKDfRgBjEesxsGFwmwQwgRailgPoOIGwRgWbijWINyfYimUCEthYXV0byBwdW5jaCBkdW1teQ==')
table.insert(farm1, auto_dummy)
cor(auto_dummy, 255, 0, 0)
------
table.insert(farm1, auto_dummy)
foto_sorcerer = i(mJiBOYhEyTHxlVwzztrRB('plWzVxJJUxOkBuFLozrIAVVNBqvCHpzBdGvPzsYUZotUpninvRXyTeDSW1hZ2VMYWJlbA=='), aberto)
    b(foto_sorcerer, 0.2, 0, 0.1, 0)
    p(foto_sorcerer, 0.4, 0, 0.001, 0)
foto_sorcerer.Image = mJiBOYhEyTHxlVwzztrRB('oslWatTneqGAXXCyYiaXGpTNXHMGHpoMFkjUewNGyxIEZRDMsihQWmucmJ4YXNzZXRpZDovLzgxMDMxMzkyMzc0MjE4')
table.insert(farm1, foto_sorcerer)
------------------
foto_dummy = i(mJiBOYhEyTHxlVwzztrRB('HRsytPBKZTSOEOIudhJikpQtWOrZASQwmgsUCwbguzLlwcTmTvWtnkoSW1hZ2VMYWJlbA=='), aberto)

    b(foto_dummy, 0.2, 0, 0.1, 0)
    p(foto_dummy, 0.4, 0, 0.2, 0)
foto_dummy.Image = mJiBOYhEyTHxlVwzztrRB('IXsGexffhsTXiBdayZsdHitpSWhNEjxdgvEUZlaPvEIwjvHZpGIFDzTcmJ4YXNzZXRpZDovLzEwNjUyMzg1MTI4NTMwNg==')
------------------
table.insert(farm1, foto_dummy)
---------
dummy = i(mJiBOYhEyTHxlVwzztrRB('qgnzDLlZYlHhlZTEVIlYGbYCpzBdPQVyTYYxSqHioCOSdcnDITXQDiFVGV4dEJ1dHRvbg=='), aberto)
    b(dummy, 0.2, 0, 0.06, 0)
    p(dummy, 0.75, 0, 0.25, 0)
dummy.Text = mJiBOYhEyTHxlVwzztrRB('tjWeHpzQnzPAibKVIpJnzghJIiyMrDnmlILnBaOqFtLuJxXUbSVyybeYXV0byBkdW1teQ==')
table.insert(farm1, dummy)
        open = i(mJiBOYhEyTHxlVwzztrRB('woGlhYqxZBFNiHylfXJrtymkeTAsrMbLTZvkkyPQcPHquAwxaXySjcBVGV4dEJ1dHRvbg=='), s)
    b(open, 0.1, 0, 0.1, 0)
    p(open, 0.43, 0, -0.05, 0)
open.Text = mJiBOYhEyTHxlVwzztrRB('SkXfKJHltpXmfWZxNNerYYFDAtmJuIArWCGSquqjjrQUkSwxrTIeVWHb3BlbiBtZW51')
for _, farmss in ipairs(farm1) do
    
    farmss.Parent = workspace
end
local kill = {
punch = function(quem)
local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild(mJiBOYhEyTHxlVwzztrRB('lbDLsnLURZbZFMwjMVfdZKPgDUsQsSKYqqowFDTGHJIFLqFEJHocpbxSHVtYW5vaWRSb290UGFydA==')) 
local npc = workspace:FindFirstChild(quem)
if npc then
local ht = npc:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('xZxfbYfyRxqJOyJtAweKrRkuSssCqTNXvvTGKtjgtWQNNgfROpRdXwDSHVtYW5vaWRSb290UGFydA=='))
humanoidrootpart.CFrame = ht.CFrame
local args = {
    [1] = {
        [mJiBOYhEyTHxlVwzztrRB('VmKxRBKgkYmGSzTLtEPNjcgCDLsIZQHHPaUpAGrNsuqErYcTRCyVbUFQ2hhcmFjdGVy')] = workspace:WaitForChild(player.Name),
        [mJiBOYhEyTHxlVwzztrRB('kFuWbQDhusQtVsIwxGndLEjwfNpnMAIZUXksRPZRlFsMFQHHrmwpFpBQWN0aW9u')] = mJiBOYhEyTHxlVwzztrRB('BrriLgTmZYqTQvwklprODwopQCCUPhMPWwbpAjsLqHYoKjDHUURMSqZTTE='),
        [mJiBOYhEyTHxlVwzztrRB('HorfAkuiUIBloOtXUbEnLzdhWWatWyeXCBRxbgMCkKWMeTZYCskhIesQ29tYm8=')] = 1,
        [mJiBOYhEyTHxlVwzztrRB('xkZxCtQCpnkrSoJOxSnmzElsytXnfFyOAAnPHvKNvCKskVdZoUiQlRFVGFyZ2V0')] = workspace:WaitForChild(quem),
        [mJiBOYhEyTHxlVwzztrRB('OjlOFOiwwgIpyqiIABrAcCsfLyegbxWaGklyiMCWClWQMhrbRYjATuEQmVoaW5kUGxheWVy')] = false
    }
}
game:GetService(mJiBOYhEyTHxlVwzztrRB('vEFMtRtxZlezQPwSODUDKQbKpvmEixlUmmrLTeMhZtLPhYwNgTNWZVPUmVwbGljYXRlZFN0b3JhZ2U=')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('NxrjrYVhbpFOtfslVoHhbZYOhJGdGosKjzcGSDmYzfWTpbyZMcHVynVRXZlbnRz')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('AMFYKfFbqdgewQFoAxYDYMYmFwdshdowxppIljFFCaISJLaGJiigxcMQ29tYmF0RXZlbnQ=')):FireServer(unpack(args))
end
end
}
------ auto tab--------
auto_resist = i(mJiBOYhEyTHxlVwzztrRB('YRdNBlejqKnSysVnLxXIvcNmgJjlySzvqtsaNwSCCShHHiNzzcHpRVwVGV4dExhYmVs'), workspace)
    b(auto_resist, 0.4, 0, 0.04, 0)
    p(auto_resist, 0.6, 0, 0.35, 0)
auto_resist.Text = mJiBOYhEyTHxlVwzztrRB('hMuaZctBLpfJRjIWPWSrTjtNQHkuHqpHgOeVMNvIzIkguVoQIyosmnDYXV0byByZXNpc3Q=')
cor(auto_resist, 255, 0, 0)
table.insert(auto1, auto_resist)
auto_dash = i(mJiBOYhEyTHxlVwzztrRB('HYXCrSDRVPpVwiBabMVpbnepaIlaFjjaqAzRyYmmHUzLtGqqNUKQxEMVGV4dExhYmVs'), workspace)
    b(auto_dash, 0.4, 0, 0.04, 0)
    p(auto_dash, 0.6, 0, 0.2, 0)
auto_dash.Text = mJiBOYhEyTHxlVwzztrRB('JdeswOvZrfyqplySqUHZtPnAYIHTaVyKyizNnBCKFFvrFSqDRgJvZGzYXV0byBkYXNo')
auto_squat = i(mJiBOYhEyTHxlVwzztrRB('rBrkSgKcoDAnQMkOSTDqBhwAqJACamIUgjABamLUkwBnMgCpWknGyafVGV4dExhYmVs'), workspace)
    b(auto_squat, 0.4, 0, 0.04, 0)
    p(auto_squat, 0.6, 0, 0.02, 0)
auto_squat.Text = mJiBOYhEyTHxlVwzztrRB('ddHDHDMUrATPhHgxjvatXPqnYagnZZUHOLbFFzBJiFxbosaBSsoldiiYXV0byBzcXVhdA==')
cor(auto_squat, 255, 0, 0)
cor(auto_dash, 255, 0, 0)
table.insert(auto1, auto_squat)
 comboio = i(mJiBOYhEyTHxlVwzztrRB('eEFvZptEjIYppfnllDlLqAsgLqSjYlKZBkfTLIQQLTsfrLvfKYfLEjmVGV4dEJ1dHRvbg=='), workspace)
    b(comboio, 0.2, 0, 0.06, 0)
    p(comboio, 0.75, 0, 0.1, 0)
comboio.Text = mJiBOYhEyTHxlVwzztrRB('qiWdjmAaFpsowfmweBZyzlSFBmrpQIyGpOmWeVtRhGHHqluiHRSJxDxYXV0byBzcXVhdA==')
table.insert(auto1, comboio)
table.insert(auto1, auto_dash)
dash = i(mJiBOYhEyTHxlVwzztrRB('GZYSICyfRwFqvqfAGnmlyowlfYHkiIiUMdnvgjXVRmNWpVmTfFzOtqYVGV4dEJ1dHRvbg=='), workspace)
    b(dash, 0.2, 0, 0.06, 0)
    p(dash, 0.75, 0, 0.25, 0)
dash.Text = mJiBOYhEyTHxlVwzztrRB('GJXleoIaEtvAoKzGRBsxqWbvgDgCLWXxPVrJxBRcvzVlnBNOfOgWYDwYXV0byBkYXNo')
table.insert(auto1, dash)
punch = i(mJiBOYhEyTHxlVwzztrRB('SAnLKceuvwCuLXCFAqeiZvWKquCUaJxMDKXHZaOuulEqRFqMLcfdvgvVGV4dEJ1dHRvbg=='), workspace)
    b(punch, 0.2, 0, 0.06, 0)
    p(punch, 0.75, 0, 0.4, 0)
punch.Text = mJiBOYhEyTHxlVwzztrRB('xyZiqJSFUbIjKwdWHCHcjUSvBRaQvDxhYjOHtAPXHEhPXTRNBBrZnouaW5mIHN0cmVuZ2h0IGZhcm0=')
table.insert(auto1, punch)
---------------------
------skills------------
auto_x = i(mJiBOYhEyTHxlVwzztrRB('mPMBQEdxgtJqMNLJHbWEhSfnDLabnAGoLTuNgEpPdvATtdbKOMBBdgCVGV4dEJ1dHRvbg=='), workspace)
    b(auto_x, 0.2, 0, 0.06, 0)
    p(auto_x, 0.75, 0, 0.0, 0)
auto_x.Text = mJiBOYhEyTHxlVwzztrRB('ELgslQLOfyiLdjvGPOlSjqxkKhbiclatdqKjfveHEGUCPJGuPXIFrtaYXV0byB4')
table.insert(skill1, auto_x)
auto_z = i(mJiBOYhEyTHxlVwzztrRB('loOpEtJeyhXujwbNMSTepgNbjVIKcXoRAPnNACDbUGRAFppDBqOiaJyVGV4dEJ1dHRvbg=='), workspace)
    b(auto_z, 0.2, 0, 0.06, 0)
    p(auto_z, 0.75, 0, 0.08, 0)
auto_z.Text = mJiBOYhEyTHxlVwzztrRB('TjXegGdAVHoQJNhvRoavSLuPHSlbMGoGQioDocXlgjoOGYNfSRZgRNzYXV0byB6')
table.insert(skill1, auto_z)
auto_c = i(mJiBOYhEyTHxlVwzztrRB('KzNXseRAuBcflCedJaYaiqzjcZxxdvGyvRGUijnJtVGuPOlLwytXqbYVGV4dEJ1dHRvbg=='), workspace)
    b(auto_c, 0.2, 0, 0.06, 0)
    p(auto_c, 0.75, 0, 0.16, 0)
auto_c.Text = mJiBOYhEyTHxlVwzztrRB('LgcKOBpAcPlljIvNfZneRugUqfMCeyrYJUgpYsDobtwbNRyPRKhrdEeYXV0byBj')
table.insert(skill1, auto_c)
auto_v = i(mJiBOYhEyTHxlVwzztrRB('klcRanNJYNCVAAIKjFCQzKPkBgEcCbEoOyvoQjpLMMPqszfojQTkJUVVGV4dEJ1dHRvbg=='), workspace)
    b(auto_v, 0.2, 0, 0.06, 0)
    p(auto_v, 0.75, 0, 0.24, 0)
auto_v.Text = mJiBOYhEyTHxlVwzztrRB('VUTrYVzFWDllNYNdQSncTVecvLuEsSlkcuDKxEZGtMDGqDYnlkGnkNlYXV0byB2')
table.insert(skill1, auto_v)

auto_b = i(mJiBOYhEyTHxlVwzztrRB('GAgETfZMzoXivEyLJQmSwuEgpDsJIRvhwHdpMzuWycuttzmMYAcQHnvVGV4dEJ1dHRvbg=='), workspace)
    b(auto_b, 0.2, 0, 0.06, 0)
    p(auto_b, 0.75, 0, 0.32, 0)
auto_b.Text = mJiBOYhEyTHxlVwzztrRB('SVwDlgyoREPZcCclUiFkbFKvJIPqVCpGLCJBCrxvJWMLmHhMXQaWGPdYXV0byBi')
table.insert(skill1, auto_b)
auto_n = i(mJiBOYhEyTHxlVwzztrRB('oAXYKpuKEFOigyOwmKpnhcKAQwDQlAemOavzYGexMVJDYpoUcKhsJlzVGV4dEJ1dHRvbg=='), workspace)
    b(auto_n, 0.2, 0, 0.06, 0)
    p(auto_n, 0.75, 0, 0.41, 0)
auto_n.Text = mJiBOYhEyTHxlVwzztrRB('RvJUMLfzHGrtsHBhWkUecGpJRBJriSqmYYIbvvmbLSojBHkMfDjIIPYYXV0byBu')
table.insert(skill1, auto_n)
------
--------tp tab-----------
mi = i(mJiBOYhEyTHxlVwzztrRB('kpEKKQoIrDQIqhMHlKmMQvtJkHtoQhZKwZJSRaEpvIFHgsIfUENUDdfVGV4dEJ1dHRvbg=='), workspace)
    b(mi, 0.2, 0, 0.06, 0)
    p(mi, 0.75, 0, 0, 0)
mi.Text = mJiBOYhEyTHxlVwzztrRB('MIwZLrxzJssuKngMiuCUDRRWbFYpgwcxqFjeOZibZylMQPlBqVWHGTQcGFycXVlIG1peWFzaGk=')
me = i(mJiBOYhEyTHxlVwzztrRB('JjAfesDbCOsXNzbLqRDzHzobrZQyebojYrOmvWOUtFuImUmeIEgZdhaVGV4dEJ1dHRvbg=='), workspace)
    b(me, 0.2, 0, 0.06, 0)
    p(me, 0.75, 0, 0.1, 0)
me.Text = mJiBOYhEyTHxlVwzztrRB('uWWbKVXTWuusfIXSCFjPdaCShADvzaOutwiXHHIuacxtqrospDTQOVMc3Vid2F5')
ma = i(mJiBOYhEyTHxlVwzztrRB('ftkQdVARPemhQDCBkstMbMrrQxgFTaaYpdFzwlevpYoGnJEWaYiBcUTVGV4dEJ1dHRvbg=='), workspace)
    b(ma, 0.2, 0, 0.06, 0)
    p(ma, 0.75, 0, 0.2, 0)
ma.Text = mJiBOYhEyTHxlVwzztrRB('BhJKhzNYKxEuoMuhkAaMHlqcahLYnkmfANeRvAwzRDcSTDGPfOIEueAc3BpbiBsb2NhdGlvbg==')

 ab = i(mJiBOYhEyTHxlVwzztrRB('SXSqTTwNtniHbFVFsmzASTjHlhOGLXlBnWMEVuyNblCXRgoTheYsQAYVGV4dEJ1dHRvbg=='), workspace)
    b(ab, 0.2, 0, 0.06, 0)
    p(ab, 0.75, 0, 0.29, 0)
ab.Text = mJiBOYhEyTHxlVwzztrRB('bDLPfAVnmvZPAaNLkMWVETSgeOIxLBksbeuieyOxoLwxWqSsUIxhwHJanVqdXRzdSBhdXRv')
table.insert(tp1, ab)
table.insert(tp1, ma)
table.insert(tp1, mi)
table.insert(tp1, me)
-------------------------------
---------------bosses farm--------------
su = i(mJiBOYhEyTHxlVwzztrRB('BqWfaYARsBvyvrnqagvUGwaPUGyfsDRLDyzPelaOeCpoJBneVGPrcbbVGV4dEJ1dHRvbg=='), workspace)
    b(su, 0.2, 0, 0.06, 0)
    p(su, 0.75, 0, 0., 0)
su.Text = mJiBOYhEyTHxlVwzztrRB('eydvxonaBpdceKuOUxsPTwhEnFXFvQRKQOlBkBScVVzmigiDrQGAeDtc3VrdW5hIGJvc3M=')
mg = i(mJiBOYhEyTHxlVwzztrRB('vaPgtFxaDlmdCpxZhyXUWRdbCnRaKkrLkZfGhoPIHLNvpZGXvziryYlVGV4dEJ1dHRvbg=='), workspace)
    b(mg, 0.2, 0, 0.06, 0)
    p(mg, 0.75, 0, 0.1, 0)
mg.Text = mJiBOYhEyTHxlVwzztrRB('AgdTtqBnLwVvataHhmiTRaPYovXsZMaSrDjuBXXFmaSCjoEiAZUkLtbbWVndW5hIGJvc3M=')
he = i(mJiBOYhEyTHxlVwzztrRB('TzuHxlAMrFgWqEYsEJEdkmcbKGZTXWUPVQoCJRreZpSCFbolWzkcXteVGV4dEJ1dHRvbg=='), workspace)
    b(he, 0.2, 0, 0.06, 0)
    p(he, 0.75, 0, 0.2, 0)
he.Text = mJiBOYhEyTHxlVwzztrRB('qyGEIjcngEwJLTpIUibgVWOWSUGgwARBeaGYjlucMdQDFIEKGpCfpWbc3VrdW5hIGhlaWFu')
cho = i(mJiBOYhEyTHxlVwzztrRB('VqgszkawcyXXRhVVtgWpjsHVMREhGXaSXXrAjhGWGEQMdfuRQYQWeJLVGV4dEJ1dHRvbg=='), workspace)
    b(cho, 0.2, 0, 0.06, 0)
    p(cho, 0.75, 0, 0.3, 0)
cho.Text = mJiBOYhEyTHxlVwzztrRB('eoOvNcEhfDyOsWBHILFBKKbBmgLgeymQTLibfqHsDoNAjFrCZBYoiOuY2hvc28=')
ka = i(mJiBOYhEyTHxlVwzztrRB('hbRFLJCdGtPcaITAuvKdzHFgUiHWNCNRGowoEkEptqwMGAgNVwGixdRVGV4dEJ1dHRvbg=='), workspace)
    b(ka, 0.2, 0, 0.06, 0)
 p(ka, 0.75, 0, 0.4, 0)
ka.Text = mJiBOYhEyTHxlVwzztrRB('UGUjDhAoXKUFArUEAJauWpvpBVNKjkdIEGyaycYDALLJTAfQNTqwUtMa2FzaGltbw==')
goj = i(mJiBOYhEyTHxlVwzztrRB('cwsSvsvmIJuFebvZgHVAbFOJmiEfkyeHzCnPLuYlIJnUvkHKQwMRrxNVGV4dEJ1dHRvbg=='), workspace)
    b(goj, 0.2, 0, 0.06, 0)
 p(goj, 0.75, 0, 0.5, 0)
goj.Text = mJiBOYhEyTHxlVwzztrRB('WmQIAOluXwyMtIKkHhpyoEcGpakHhrAKIudueKmDkWFfcYgBUsGAyNkc2F0b3J1IGdvam8=')
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
open.Text = mJiBOYhEyTHxlVwzztrRB('VlXNSGbPgdcVWobNgQFuGpHbDOeBodIsrKXljMcTCQROEksuWGeGRUBZGVzb3Blbg==')
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
open.Text = mJiBOYhEyTHxlVwzztrRB('SlBkFxTApylcJgKqoFgLiQhdPTdyDQGnnmYahOJkagWWvEHWYEZpfDQb3Blbg==')
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
kill.punch(mJiBOYhEyTHxlVwzztrRB('FzfZVmRnBBkMxgBHKggGPmURCDYEJXefNSefQMkXlNtpFgEgGuXEFiuU29yY2VyZXI='))
        end
      end
    end
    sorcer.Text = mJiBOYhEyTHxlVwzztrRB('GyTfWgHbZZVoVALKhoGmPpjTLpYpygURFvpHfezFJbCWbzQWKfPsKpsZGVhY3RpdmF0ZQ==')
    coroutine.wrap(sorc)()
  cor(sorcer, 0, 182, 232)
    player.CharacterAdded:Connect(function()
      coroutine.wrap(sorc)()
    end)
  else
      ativo1 = false
    sorcer.Text = mJiBOYhEyTHxlVwzztrRB('HAgnTdRKHBXVORXBochqiWYUnystNkhpvRCrhyeMcWNsYSMxEHfhvMIYXV0byBzb3JjZXJlcw==')
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
kill.punch(mJiBOYhEyTHxlVwzztrRB('dOWjUZMlqOzUAwvvfIAnKcwybNzdCVkdCoOVQMMmkmcmUBTEeFZYQEPRHVtbXk='))
        end
      end
    end
    dummy.Text = mJiBOYhEyTHxlVwzztrRB('TqvAqQjEnUZDKenuqdZeAgSoucfuBqNcXXHVCNzRmuzLFXayBTNkwJoZGVhY3RpdmF0ZQ==')
    coroutine.wrap(dum)()
    cor(dummy, 0, 182, 232)
    player.CharacterAdded:Connect(function()
      coroutine.wrap(dum)()
      
    end)
  else
    dummy.Text = mJiBOYhEyTHxlVwzztrRB('WPVbCvWlzoLliIvHnAvOMDRVVEPmLFOQsJtEPMHdOdOdilvQcxKymEAYXV0byBkdW1teQ==')
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
        [mJiBOYhEyTHxlVwzztrRB('ethgGAdujrakGQuvkzDZfWgOwPaDARPuetkZgVIZjaNbMvKxIsHEWyTQ2hhcmFjdGVy')] = workspace:WaitForChild(player.Name),
        [mJiBOYhEyTHxlVwzztrRB('BumfegQnaOKDMqochGVkeEoHOTAJDpivTojnucRmnFQIUMGKTPAVCSbQWN0aW9u')] = mJiBOYhEyTHxlVwzztrRB('HYhHjHEPQOminxPWDmYONQQebMLhkrOCSGxIpnPXXTxrEONIbjIjQZfRW5kdXJhbmNl'),
        [mJiBOYhEyTHxlVwzztrRB('agVIvdBKPqsQrUsGMqujNMmsdTZSEKRHcRvzmwHAhpQBXCBrVdVPIXJTWlzY0RhdGE=')] = game:GetService(mJiBOYhEyTHxlVwzztrRB('LPxcSiVvYlkUKjiOBDnlgKQyydPhAlxrjdghXGMBjgNgvxLfjfVZlUkUGxheWVycw==')).LocalPlayer:WaitForChild(mJiBOYhEyTHxlVwzztrRB('PAcqFmeenlYYTGyyIZgKQkOBYodwZrpkAmQjteUxaaojJJbKKHbsbBZVUlTdGF0cw=='))
    }
}

game:GetService(mJiBOYhEyTHxlVwzztrRB('QZurCQBAJPytjhVkjYEQhRDNqeCRqjUYmgGvlAulSBtWfNAvEPRazpYUmVwbGljYXRlZFN0b3JhZ2U=')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('lplthjWCDpLzMJdprhMWsFgHVYVryUnmWfjRbQgOGialHPJvYgHHPrdRXZlbnRz')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('WtrcMWSbUXeQtWFlBFvyRgBeAPzNuZFdsaHVqOipsOJfhYnaUMMsQsXQ29tYmF0RXZlbnQ=')):FireServer(unpack(args))

            end
        end
        end
        comboio.Text = mJiBOYhEyTHxlVwzztrRB('IhWUgPpciJpdTwypkdqQSBETxjYirkcGwMyFmRHnRQsZbHHTMypZslRZGVhY3RpdmU=')
    coroutine.wrap(a)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(a)()
            
        end)
    else
        comboio.Text = mJiBOYhEyTHxlVwzztrRB('LUtvXGeBrDnIGBHNytJvryIbtIEEHVFsXFRygDogGflwtyPXGkqtGlmYXV0byBzcXVhdA==')
    cor(comboio, 156, 156, 156)
    end
end)

lof = false
dash.MouseButton1Click:Connect(function()
    
    lof = not lof
    if lof then
        cor(dash, 0, 182, 232)
        dash.Text = mJiBOYhEyTHxlVwzztrRB('pzktEFDFdnWAQqsvMbDNOBpwpssVPGGWcaUlwluRzuUSQTmyKPtubRfZGVhY3RpdmU=')
        function aa()
            while lof do
                wait(0.1)
                if lof then
                    local player = game.Players.LocalPlayer 
            local args = {
    [1] = {
        [mJiBOYhEyTHxlVwzztrRB('hcndUhjnKxWykNVsiFugAcXTgZGcVcSNtbpZMboGAqIWbqcHGjKdUUJQ2hhcmFjdGVy')] = workspace:WaitForChild(player.Name),
        [mJiBOYhEyTHxlVwzztrRB('SXDmjABoZXylNOpPeZjVMDqsVBjzsQSyXAoQgYBysCTBpebKocHrAOTQWN0aW9u')] = mJiBOYhEyTHxlVwzztrRB('WCkHTRKwRtJMVwHhYCGdQXWwchSaAbwbjKBejAspqTVSLfqeAeLzqmKRGFzaA=='),
        [mJiBOYhEyTHxlVwzztrRB('CqIEmjlgrWaldFhpEiIohYmKjdylHlutdFzPMMWrHiPBScEpPxQvMGdRGly')] = Vector3.new(0.1733149141073227, 0, 0.9848664999008179),
        [mJiBOYhEyTHxlVwzztrRB('vLZZDDjetGYfeUttxEZTZrYkaDszwafUqBmAGbQTIsXGSEvfTIQKmHYQW5pbQ==')] = game:GetService(mJiBOYhEyTHxlVwzztrRB('DmQPGCRWPDEPrCoMtOOnPpDjWnjiPLRmDBaibXMMTZLWJkgLrRWQgBCUmVwbGljYXRlZFN0b3JhZ2U=')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('GPipjLwHccvLgmbuMAkASOiysfKFVWPYjaklZwswmMXraQEOpbaygQuQW5pbWF0aW9ucw==')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('nEOBgIZTMUTHLckjplMgrpXxEYPTjerXKqoolIECVAyhCgpMqfZhRvDQ29tYmF0')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('zUpxWsIXjoiwQAwVEfAGbDuzZfizclhoqCkLBclhfaEBSkvQYRIZOKbRnJvbnREYXNo')),
        [mJiBOYhEyTHxlVwzztrRB('WStYanWlNvQhCsLclcLRJfhotSzXiUMObXtCotWgwEUgJRXMqFktXzITWlzY0RhdGE=')] = game:GetService(mJiBOYhEyTHxlVwzztrRB('WzBbbKBwUcxzRykJNSjNcdBZYMaNPKtjXrBRuEZHlrhEWqpwDErnLHjUGxheWVycw==')).LocalPlayer:WaitForChild(mJiBOYhEyTHxlVwzztrRB('rTVGRJYTaAeGcwyIfzYXnuXyeWlidMGpnWIuxsfFrRTOXnMdgYWKzIcVUlTdGF0cw=='))
    }
}

game:GetService(mJiBOYhEyTHxlVwzztrRB('JhViIrEssOZXSpxrVIUVJeuXgoOJETQJuSZwpEnaQWWhVEOnKApiFJQUmVwbGljYXRlZFN0b3JhZ2U=')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('ndKeDNBYpaYhkEpPPmyTDammfTgdyILhUZGaznzISmHXyjQzTTioLVbRXZlbnRz')):WaitForChild(mJiBOYhEyTHxlVwzztrRB('UsfaNHPYKzINEayaVAOxZgondkROnCMWsiHIJYxGFVSxLYgkCzWqjaFQ29tYmF0RXZlbnQ=')):FireServer(unpack(args))

            end
        end
        end
        coroutine.wrap(aa)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(aa)()
            
        end)
    else
        dash.Text = mJiBOYhEyTHxlVwzztrRB('qsfhYJfAjBWQLYulXvxwqucVcSmXFCcQCcglMqOAwBVbXhExSPmqDZuYXV0byBkYXNo')
        cor(dash, 156, 156, 156)
    end
end)

l = false
punch.MouseButton1Click:Connect(function()
  l = not l
if l then  
    
    cor(punch, 0, 182, 232)
    punch.Text = mJiBOYhEyTHxlVwzztrRB('IXmRyzdOiVwZWVqXobPvgATdqBbLBejcccUfaKVMnIfteJSAsmEBieoZGVhY3RpdmU=')
else
    punch.Text = mJiBOYhEyTHxlVwzztrRB('IXHzcaOStKkHqQPcplSGKuzoPwvThsVrdHQtUnqhJTSYwRqZIHooXIOaW5mIHN0cmVuZ3RoIGZhcm0=')
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
        auto_x.Text = mJiBOYhEyTHxlVwzztrRB('oCrhVYyvbrBrMShMougKDBSxkyqDUakxIaEkeLOUFFgImkbXlNXngIhZGVhY3RpdmU=')
        function ao()
            while loop1 do
                wait(0.1)
            if loop1 then
            game:GetService(mJiBOYhEyTHxlVwzztrRB('IMRuhgZSdFWxpZioYhIQdCpZyOEUiOcrpCjimlrhrBmncRqFQYBEtRmVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.X,false,game)
                
            end
            end
        end
        coroutine.wrap(ao)()
        player.CharacterAdded:Connect(function()
            coroutine.wrap(ao)()
            
            
        end)
    else
        cor(auto_x, 156, 156,156)
        auto_x.Text = mJiBOYhEyTHxlVwzztrRB('hhBcZpRnFKmtTKFxYxcgUmSvUWnmSyYbuYrVyKeCzPofkuNtfuGoyQWYXV0byB4IHNraWxs')
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
            
                    game:GetService(mJiBOYhEyTHxlVwzztrRB('EjnYAmdWxsJUGPjiUCuSlTBTLlaEfqrLuWHhMiUpuNJMLwinDzFiSgVVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.Z,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il)()
        
    end)
        auto_z.Text = mJiBOYhEyTHxlVwzztrRB('sNeYVXKGWeWuBAXVzwtCkAFgxzLDeJyIxdxlSeUeyRbBoqfCYwjQaTkZGVhY3RpdmU=')
        cor(auto_z, 0, 182, 232)
    else
        auto_z.Text = mJiBOYhEyTHxlVwzztrRB('zlzSgzPSEMyUhaGZmBLDapDvVXotXeIbotdFapYSaaVOKBBaAReDqgoYXV0byB6')
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
            
                    game:GetService(mJiBOYhEyTHxlVwzztrRB('vpoRMGlQKxLizzxpllJsrfdeCQTALcHqJKVpXCGJcPyddQOjSokNLJyVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.C,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il)()
        
    end)
        auto_c.Text = mJiBOYhEyTHxlVwzztrRB('zWujKnlLdVxPwFemQhptyQNJWBNfpzNxDDOFWTaeZEvBQwtBWwNwbbGZGVhY3RpdmU=')
        cor(auto_c, 0, 182, 232)
    else
        auto_c.Text = mJiBOYhEyTHxlVwzztrRB('WOEzxHxPnxNeZBjMtkiDcWvoWfoEHiNJSLBvISrLzrPYSsZlHTffvGLYXV0byBj')
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
            
                    game:GetService(mJiBOYhEyTHxlVwzztrRB('wILXiHWwnJkkoYgaTAEprTWJgRdpFskyvhKbvAwbRVaMMtQvGAFCiJkVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.V,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il2)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il2)()
        
    end)
        auto_v.Text = mJiBOYhEyTHxlVwzztrRB('FxlznVtGdwMRHOWZleBfOFmjHwXjnMABxdAnqMgIybNZRfsFoFGsEjwZGVhY3RpdmU=')
        cor(auto_v, 0, 182, 232)
    else
        auto_v.Text = mJiBOYhEyTHxlVwzztrRB('ZuKZdKvYqPjXYcofLaOAxurzKvMtNXKfBAIuvzOXdWaVFxPorQNPjteYXV0byB2')
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
            
                    game:GetService(mJiBOYhEyTHxlVwzztrRB('UzJoEfGvZFNzglbsJMFzNFWypuvtfMKUKDamsaKRcsYSYpJMTQphYdvVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.B,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il3)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il3)()
        
    end)
        auto_b.Text = mJiBOYhEyTHxlVwzztrRB('vqnNTiVDeUhlzBMsGMlemTnkPJImYWGYHrZwcLcDObinBXlxNQHBrefZGVhY3RpdmU=')
        cor(auto_b, 0, 182, 232)
    else
        auto_b.Text = mJiBOYhEyTHxlVwzztrRB('DZIryjlMcxtjSxtmgFlJTyDiumqtqSwCeGGVrWyxxEAklzPuGrwnevAYXV0byBi')
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
            
                    game:GetService(mJiBOYhEyTHxlVwzztrRB('VxeTIfGKHzqTVZSEnFsknHlTNzHSxIcaxvOTYiWaheDaBpUjGUXfFFrVmlydHVhbElucHV0TWFuYWdlcg==')):SendKeyEvent(true,Enum.KeyCode.N,false,game)
                
                    
                end
            end
end
    coroutine.wrap(il4)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il4)()
        
    end)
        auto_n.Text = mJiBOYhEyTHxlVwzztrRB('UkXBlrHmHLDJzPeYvpbaDUizfQwpwKRzarAPfLbYfXJKBVshDfNzckuZGVhY3RpdmU=')
        cor(auto_n, 0, 182, 232)
    else
        auto_n.Text = mJiBOYhEyTHxlVwzztrRB('DYybDTijnMEDmlCuDQzzEliaRtjzPFQjvKtecnNCpXWXXXzrZYpayxfYXV0byBu')
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
local humanoidrootpart = character:WaitForChild(mJiBOYhEyTHxlVwzztrRB('TqMuwzEwCileOXpwhUXglWlHxeWbzHfBfsXwzLPxCFcLpjzcfuWcpNXSHVtYW5vaWRSb290UGFydA==')) 
humanoidrootpart.CFrame = CFrame.new(-537, -391, -2205)
    
    
end)


me.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild(mJiBOYhEyTHxlVwzztrRB('KMNnbpDKPdoTfIQgAjWDaJSfuWvDPkBjWcQVWaIyOuvoRjZnqGvJjmZSHVtYW5vaWRSb290UGFydA==')) 
humanoidrootpart.CFrame = CFrame.new(-377, -452, -2256)
    
    
end)


ma.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild(mJiBOYhEyTHxlVwzztrRB('ewwjYUQhgtfbnoOkJiRGqGEKizWyEqGbbwDtfQvMguUvpVgNKeQjrrDSHVtYW5vaWRSb290UGFydA==')) 
humanoidrootpart.CFrame = CFrame.new(-500, -397, -1993)
    
    
end)

ab.MouseButton1Click:Connect(function()
    
    local player = game.Players.LocalPlayer 
local character = player.Character or player.CharacterAdded:Wait() 
local humanoidrootpart = character:WaitForChild(mJiBOYhEyTHxlVwzztrRB('WgGQdixHJBEPZFrZzwXeANLwCkMhwoopFMqCfqpQoGHzZCFuApQKpNKSHVtYW5vaWRSb290UGFydA==')) 
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
                    if looop and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('AuzLeNvUpwaxMfEhtGbLhtmKeWxecQqQhiRoVAukxhEyJttkMQXEEhgU3VrdW5h')) then
    looop = false
    ativo = true
    
end

if loop1 and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('msxwFaCIomFMxyvguXdKcEfNvAiFrkxvXtJJgnpYbYDQOBUDMelPmrQU3VrdW5h')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
            
                    kill.punch(mJiBOYhEyTHxlVwzztrRB('PCJPvRxiddSLXlQkTwEVikwTSGcNatqNffntZPUxTzvSvPgImKrOFiMU3VrdW5h'))
                    
                end
            end
end
    coroutine.wrap(il5)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il5)()
        
    end)
        su.Text = mJiBOYhEyTHxlVwzztrRB('GVuchUztpaqItwkocYIKGTYIQTjRCxSPnuaopABJpiHlqchDFDlNOQMZGVhY3RpdmU=')
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
      
      
        su.Text = mJiBOYhEyTHxlVwzztrRB('nkZIRAWAzQrwbfeOsYlppzdKwYLlerDjtEmLITFRszOqILuKkgqrgrjc3VrdW5hIGJvc3M=')
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
            if looop and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('iwjkCjbtiLMMEiUxmgEdVQThzxcldvPocYWoEpvOJMzRbWsyDdCpnALTWVndW5h')) then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('XTnmENVPcBitUJRkeySWtVmjNUODWtVwWxRKucAFlRReeKbMKbmrjIoTWVndW5h')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
        kill.punch(mJiBOYhEyTHxlVwzztrRB('WfdylGsanwuturqugUbJzlhVrqYYZSvKaJCLzcKPUWEPAJZBBrsXyMBTWVndW5h'))
                    
                    
                end
            end
end
    coroutine.wrap(il6)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il6)()
        
    end)
        mg.Text = mJiBOYhEyTHxlVwzztrRB('lKCYoTfhZsDVnLTlWHRfHwhrpdsRjvctHyYTjSRhNYLsSnkxYDSwwElZGVhY3RpdmU=')
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
        
        mg.Text = mJiBOYhEyTHxlVwzztrRB('TTvcZOswLVIoYTTmwFAgamqPNztSUExftcjAfTREQdkMGjzTKsiGHbBbWVndW5hIGJvc3M=')
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
                    
                    if looop and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('FRHlOZhNlscZeEnCMpQRPfTBlESrEFNCXxqVyLUOnNKPfEQeCYequbYVWx0U3VrdW5h')) then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end
if loop1 and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('EJxPETRlzKmGCAgvzMKIBXBDXHJNtZXBZTufqwDPujTRITxKOeoAAYBVWx0U3VrdW5h')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                    kill.punch(mJiBOYhEyTHxlVwzztrRB('bbFgqsYPBvcjTPVYmwtVJfUlJtTsRvUluOwtYmHcEVYXDcJyQYhwFFhVWx0U3VrdW5h'))
                end
            end
end
    coroutine.wrap(il7)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il7)()
        
    end)
        he.Text = mJiBOYhEyTHxlVwzztrRB('zblrTzIhbNgwnnLEPXXnfxrlcJftVQISUlpoHhVkWIsTpWFsSxoabpnZGVhY3RpdmU=')
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
        he.Text = mJiBOYhEyTHxlVwzztrRB('fMkGVUYNZcRnCIpaAzvRXmPDUncLowLPkuvSWcHHawrRudGaTBPJwPbc3VrdW5hIGhlaWFu')
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
                    
            if looop and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('iyLGKnlBbLlOBKatHNllLrsSFhXWsaqToQXZnLtDhnKscLOGlDJnxHWQ2hvc28=')) then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('SzojvnvqjbgdZxrxizDBxlMiDUdkfKhfKOTJTZTjCTxApGtCfrkZkoPQ2hvc28=')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                    kill.punch(mJiBOYhEyTHxlVwzztrRB('PXHZRgZdhMBTsfJsJctvEujmDrwBhOogXHuYgFwTRQsOAkBKKneVKbMQ2hvc28='))
                                end
            end
end
    coroutine.wrap(il8)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il8)()
        
    end)
        cho.Text = mJiBOYhEyTHxlVwzztrRB('eicGROPITHvazaxlUhsdLIQhBdLwweDUNaXzFEMlEcSUhcYXIphzSCKZGVhY3RpdmU=')
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
        cho.Text = mJiBOYhEyTHxlVwzztrRB('ezqWObkLpFplkSHEuTAxXOKSorQRCPEFOPHBwpSLTojzbgeEUAsamezY2hvc28=')
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
             if looop and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('OlHBJTEDtRkrHuMJcjMRLvsDNfcozgDyyUpOMKsJxaPiAqslIMqLtAES2FzaGltbw==')) then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end
if loop1 and workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('YrPVeyXHJVAdhIdJeNAsWAwktiqkbTItdSJAlSBVOlUuqIgGYucKwTYS2FzaGltbw==')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
                                    kill.punch(mJiBOYhEyTHxlVwzztrRB('OQrvwAocCuZDzyrlBZrXoebIFDWpmYSJmCTYrIxhuPBZgKncnCaHUoYS2FzaGltbw=='))
                    
                end
            end
end
    coroutine.wrap(il97)()
    player.CharacterAdded:Connect(function()
        coroutine.wrap(il97)()
    end)
        ka.Text = mJiBOYhEyTHxlVwzztrRB('FmdkwXADDQiRSEmaxEpdhaceColvYlhDIremJieUBFSPeBRoyovJfvtZGVhY3RpdmU=')
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
        ka.Text = mJiBOYhEyTHxlVwzztrRB('eDOJAYpAdRFyjqGuVtJEsDTgciPvmHbXsQJlqyogOEBnTxcmnmIJGEDa2FzaGltbw==')
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
            if looop and  workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('ooFrcHrtDVywXjsXqBDSmeaeojmEKdOFNWZiAMDDvaaKYbCNlcPKHttVGhlU3Ryb25nZXN0')) then
    looop = false
    ativo = true
    cor(dummy, 156, 156, 156)
end

if loop1 and  workspace:FindFirstChild(mJiBOYhEyTHxlVwzztrRB('DGSVpLkgGYLUVdeoLUBfphvXYWNnrZqAmFBoeVjDDzumlIUmSrmpkrtVGhlU3Ryb25nZXN0')) then
    loop1 = false
    ativo1 = true
    cor(sorcer, 156, 156, 156)
end
         
                    kill.punch(mJiBOYhEyTHxlVwzztrRB('fJjkMVajwiaoCibwRJRADcMFBqTBzZwgpaRRfaWNNziJWJwChBTHVRzVGhlU3Ryb25nZXN0'))
                end
            end
end
    coroutine.wrap(il9)()
    player.CharacterAdded:Connect(function()
        
        coroutine.wrap(il9)()
    end)
        goj.Text = mJiBOYhEyTHxlVwzztrRB('SkZpwvDwZySosHRrOHFfLgiZbqsfxTOwMbtFNXKavfEtqjlMdNArgRwZGVhY3RpdmU=')
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
        goj.Text = mJiBOYhEyTHxlVwzztrRB('RkGItqoWGOxNYZsTPhHUUWyyFkbtZKkIXDZJsgoBDIIGvwRPpJlFaFHZ29qbw==')
        cor(goj, 156, 156, 156)
    end
end)


end

-------------------------------------------------------------------------------
--! json library
--! cryptography library
local a=2^32;local b=a-1;local function c(d,e)local f,g=0,1;while d~=0 or e~=0 do local h,i=d%2,e%2;local j=(h+i)%2;f=f+j*g;d=math.floor(d/2)e=math.floor(e/2)g=g*2 end;return f%a end;local function k(d,e,l,...)local m;if e then d=d%a;e=e%a;m=c(d,e)if l then m=k(m,l,...)end;return m elseif d then return d%a else return 0 end end;local function n(d,e,l,...)local m;if e then d=d%a;e=e%a;m=(d+e-c(d,e))/2;if l then m=n(m,l,...)end;return m elseif d then return d%a else return b end end;local function o(p)return b-p end;local function q(d,r)if r<0 then return lshift(d,-r)end;return math.floor(d%2^32/2^r)end;local function s(p,r)if r>31 or r<-31 then return 0 end;return q(p%a,r)end;local function lshift(d,r)if r<0 then return s(d,-r)end;return d*2^r%2^32 end;local function t(p,r)p=p%a;r=r%32;local u=n(p,2^r-1)return s(p,r)+lshift(u,32-r)end;local v={0x428a2f98,0x71374491,0xb5c0fbcf,0xe9b5dba5,0x3956c25b,0x59f111f1,0x923f82a4,0xab1c5ed5,0xd807aa98,0x12835b01,0x243185be,0x550c7dc3,0x72be5d74,0x80deb1fe,0x9bdc06a7,0xc19bf174,0xe49b69c1,0xefbe4786,0x0fc19dc6,0x240ca1cc,0x2de92c6f,0x4a7484aa,0x5cb0a9dc,0x76f988da,0x983e5152,0xa831c66d,0xb00327c8,0xbf597fc7,0xc6e00bf3,0xd5a79147,0x06ca6351,0x14292967,0x27b70a85,0x2e1b2138,0x4d2c6dfc,0x53380d13,0x650a7354,0x766a0abb,0x81c2c92e,0x92722c85,0xa2bfe8a1,0xa81a664b,0xc24b8b70,0xc76c51a3,0xd192e819,0xd6990624,0xf40e3585,0x106aa070,0x19a4c116,0x1e376c08,0x2748774c,0x34b0bcb5,0x391c0cb3,0x4ed8aa4a,0x5b9cca4f,0x682e6ff3,0x748f82ee,0x78a5636f,0x84c87814,0x8cc70208,0x90befffa,0xa4506ceb,0xbef9a3f7,0xc67178f2}local function w(x)return string.gsub(x,mJiBOYhEyTHxlVwzztrRB('qAQPsruebGiMEsIaqPgjhrdQkBYkVjWmVSHntuZbxWZswonglpctjRTLg=='),function(l)return string.format(mJiBOYhEyTHxlVwzztrRB('cBPiKmCovTDGndfdSNvGCSJnRzApyqAZvlKWPzCwedDeFSLtgISXsluJTAyeA=='),string.byte(l))end)end;local function y(z,A)local x=mJiBOYhEyTHxlVwzztrRB('pPdRDDBGKkOZSKArnrlOkNzQmYSYtVjIAjmHxxDJradWUYBkThHJAld')for B=1,A do local C=z%256;x=string.char(C)..x;z=(z-C)/256 end;return x end;local function D(x,B)local A=0;for B=B,B+3 do A=A*256+string.byte(x,B)end;return A end;local function E(F,G)local H=64-(G+9)%64;G=y(8*G,8)F=F..mJiBOYhEyTHxlVwzztrRB('NXLVOmbPZdEWMQQTXsqnNhdRiUHQqvBuDSIlsaKUhYMJZbyKvIgCIoiXDEyOA==')..string.rep(mJiBOYhEyTHxlVwzztrRB('KcCCJjeXWwANbELavoGeXtXciymQniKeXFHZQWuaFlbbpEVrncllEjkXDA='),H)..G;assert(#F%64==0)return F end;local function I(J)J[1]=0x6a09e667;J[2]=0xbb67ae85;J[3]=0x3c6ef372;J[4]=0xa54ff53a;J[5]=0x510e527f;J[6]=0x9b05688c;J[7]=0x1f83d9ab;J[8]=0x5be0cd19;return J end;local function K(F,B,J)local L={}for M=1,16 do L[M]=D(F,B+(M-1)*4)end;for M=17,64 do local N=L[M-15]local O=k(t(N,7),t(N,18),s(N,3))N=L[M-2]L[M]=(L[M-16]+O+L[M-7]+k(t(N,17),t(N,19),s(N,10)))%a end;local d,e,l,P,Q,R,S,T=J[1],J[2],J[3],J[4],J[5],J[6],J[7],J[8]for B=1,64 do local O=k(t(d,2),t(d,13),t(d,22))local U=k(n(d,e),n(d,l),n(e,l))local V=(O+U)%a;local W=k(t(Q,6),t(Q,11),t(Q,25))local X=k(n(Q,R),n(o(Q),S))local Y=(T+W+X+v[B]+L[B])%a;T=S;S=R;R=Q;Q=(P+Y)%a;P=l;l=e;e=d;d=(Y+V)%a end;J[1]=(J[1]+d)%a;J[2]=(J[2]+e)%a;J[3]=(J[3]+l)%a;J[4]=(J[4]+P)%a;J[5]=(J[5]+Q)%a;J[6]=(J[6]+R)%a;J[7]=(J[7]+S)%a;J[8]=(J[8]+T)%a end;local function Z(F)F=E(F,#F)local J=I({})for B=1,#F,64 do K(F,B,J)end;return w(y(J[1],4)..y(J[2],4)..y(J[3],4)..y(J[4],4)..y(J[5],4)..y(J[6],4)..y(J[7],4)..y(J[8],4))end;local e;local l={[mJiBOYhEyTHxlVwzztrRB('iOVmWOlbbPhurluDdOPNCvpFsXujCizPXYuuqugrsHmQMwXNpYfhVUOXFw=')]=mJiBOYhEyTHxlVwzztrRB('GWLirvGSpFddQKTypgAgbmsZXlUTOoyHoKmizTiCVBsajOOuguKMBQbXFw='),[mJiBOYhEyTHxlVwzztrRB('FXugoQmdnVLxDpidvEbJdkjuEGzBTIaAadpKhpZOWvvwfqzrrYptwwMXA==')mJiBOYhEyTHxlVwzztrRB('ewRarnHNiYcQeQsiiOyusTcxsbRPOisOtPHurvYxNlpjTPIvWhvoQfmXT0=')\mJiBOYhEyTHxlVwzztrRB('ylGnERVCsrFflvJFgVPGwEJRKFjmvaWWyFaQYYpLmhVDaxghppOWcZc'),[mJiBOYhEyTHxlVwzztrRB('akKmVsNQzeasWxLMsFIXmfYJaDyENZeeAkQWheyQNrMgCGKkZsnlonuXGI=')]=mJiBOYhEyTHxlVwzztrRB('GWQtlbMRhCiQfponiXopFToZeQKMBohCKzYkOnLVvaIgwsRxdseBQeSYg=='),[mJiBOYhEyTHxlVwzztrRB('fJGYwvDDMbzkutWnZJablTGStugAqpqHcyZMfCxlaWegGNRkljdSAYEXGY=')]=mJiBOYhEyTHxlVwzztrRB('CzmswjslNhMIbCincSDDeYMxMbBmMDyteTgyCqEvSIVKdrsnhEUKWpcZg=='),[mJiBOYhEyTHxlVwzztrRB('MfTqorkKAdCOEWhtNcBSsnbcFSbPOkBVAWsRQEdfGlNMFDxpcaxjVTKXG4=')]=mJiBOYhEyTHxlVwzztrRB('HYMyYylcbojTSBhZovvCNVPZWOBeFeIDbiYrmXJWcoqpYSAXeZsuhIjbg=='),[mJiBOYhEyTHxlVwzztrRB('JJPMIRxrNQyHTZyGMjdYByRqjpOkBMdBNSaNyTNhIFvLUINDUMFvkKjXHI=')]=mJiBOYhEyTHxlVwzztrRB('bNRsVGyHKqPULCvXrXLoGZHCABinkKsOEMiNPxSSyAATibBDfTtrDEFcg=='),[mJiBOYhEyTHxlVwzztrRB('OdCPPFKTnrKgKjVgjuqYnwBsQOgaZFkucaCYFfEtyyMthbSmpeBQeAHXHQ=')]=mJiBOYhEyTHxlVwzztrRB('ENIzrjiQBzQrzRnUQGVsxlHDHMgWDiBvVAsScPERzqPGZtaRTswiXetdA==')}local P={[mJiBOYhEyTHxlVwzztrRB('CBwVxixJXvnPkFeuRRbklPdVqBjslERmvzJCKfLTapqHCXIkHxARNoQLw==')]=mJiBOYhEyTHxlVwzztrRB('JkrqsHTpdkkfDucQmbbPTmgnVZwxtPtQBNnhPOzFdEvYUjiRWTioaLSLw==')}for Q,R in pairs(l)do P[R]=Q end;local S=function(T)returnmJiBOYhEyTHxlVwzztrRB('VdgEdvntjiShaktFTcyrejXjLGTKFwDPCGiOFUwDxBmIkrJJqpNIvaeXFw=')..(l[T]or string.format(mJiBOYhEyTHxlVwzztrRB('fwvPffDDYdXgKLFRHTwWNrKOqVaFIlLmtHsDOSrKXTFeYPKjJXlwlKidSUwNHg='),T:byte()))end;local B=function(M)returnmJiBOYhEyTHxlVwzztrRB('LtoEEdwzFDxCwhGeVETjuyfjIqOemaVkQLwoDRztBouJtCaLoMUWGqVbnVsbA==')end;local v=function(M,z)local _={}z=z or{}if z[M]then error(mJiBOYhEyTHxlVwzztrRB('OdNxfdUnFuscySHOEHefzhjaYSQBplZVydmQfcwCzgYetXiSuqASxhNY2lyY3VsYXIgcmVmZXJlbmNl'))end;z[M]=true;if rawget(M,1)~=nil or next(M)==nil then local A=0;for Q in pairs(M)do if type(Q)~=mJiBOYhEyTHxlVwzztrRB('PyczDMetKEpOfMknPNfYkEqdDlmzYwSGPnuzEIUHYfGhMEyVOhwgFYQbnVtYmVy')then error(mJiBOYhEyTHxlVwzztrRB('QvWNrWRlOEShiZfMKhERYcKPBQzfkKCgtgNNwboKHDgBZOvruekuGDsaW52YWxpZCB0YWJsZTogbWl4ZWQgb3IgaW52YWxpZCBrZXkgdHlwZXM='))end;A=A+1 end;if A~=#M then error(mJiBOYhEyTHxlVwzztrRB('AbWjzHWSleLPhSPnzzRvKZdMIbhmIywKuVQkJtamWCnDKIATJMEvBesaW52YWxpZCB0YWJsZTogc3BhcnNlIGFycmF5'))end;for a0,R in ipairs(M)do table.insert(_,e(R,z))end;z[M]=nil;returnmJiBOYhEyTHxlVwzztrRB('LmNTgKjAQsatYTyDznkEMHwPHxwJpNxvnQXEZGTMjrGibpBPFifxHNlWw==')..table.concat(_,mJiBOYhEyTHxlVwzztrRB('jmVeaUaZxwmInzdDTWFMMZGsVMvCYrfYDEsjcTYzFPNSxdmHXQzdaQlLA=='))..mJiBOYhEyTHxlVwzztrRB('ooovMZKmLTyRDwgOjKROEDoVSNUKhAkcFOquzDdqhSTyeurWEXMEtpZXQ==')else for Q,R in pairs(M)do if type(Q)~=mJiBOYhEyTHxlVwzztrRB('mJlamxtqyshLJDrQjcMmViIKgRsTgpCzPRWGPgjxhOxpByihcAkHrbYc3RyaW5n')then error(mJiBOYhEyTHxlVwzztrRB('InGZNYpVceazxVfhBtWOQnyXZMAjajdZBjJWwIodxeymDHtMyStooSRaW52YWxpZCB0YWJsZTogbWl4ZWQgb3IgaW52YWxpZCBrZXkgdHlwZXM='))end;table.insert(_,e(Q,z)..mJiBOYhEyTHxlVwzztrRB('YRBNRnVJGjVPPCNpUTbElufmcxFSwvKHVLMFYQnsLdpsIeSPfFpbIgXOg==')..e(R,z))end;z[M]=nil;returnmJiBOYhEyTHxlVwzztrRB('RtkyZxlqMHgVKMOJXuaEojJKcBFJRwsQhdjcbrJylxRTnDzTxomwXiWew==')..table.concat(_,mJiBOYhEyTHxlVwzztrRB('lggqYlCnLWedlvuMyTtzXsjRGeXyXlnXcYOOsTTaXRjOBvkCeRQiLFZLA=='))..mJiBOYhEyTHxlVwzztrRB('KSJCuKqFNNYAsJwSuIdqybjHqiYpmwZOckoGrMleQYPlNNmPHiIPmZXfQ==')end end;local g=function(M)returnmJiBOYhEyTHxlVwzztrRB('XhaPQjflVdHcJMNjCyiKRuUcrXTnwrzpkBTagKietfWEBLbgxHJlqxM')mJiBOYhEyTHxlVwzztrRB('qggFDOJKEwPgPRuMNwCbZWUGMSWnJGKlyQtirhTovCIpdDQJwaCflxhLi5NOmdzdWIo')[%z\1-\31\\mJiBOYhEyTHxlVwzztrRB('VNMlDTOgLkVTGWdoUoWsBeQikgfmPibKscqrgaHEkhXutiYRXCegJHWXQ=='),S)..mJiBOYhEyTHxlVwzztrRB('xnAZOyXRzSQbswMRwLnQycgvaFQobnNOpfuJTAhDLwUGgzfqpWjuQWS')mJiBOYhEyTHxlVwzztrRB('HiKbxarSCSRodMKxPhYgjLZUVYGCydVnRscbPhHYGoNXfMCSXSIeLzWZW5kO2xvY2FsIGExPWZ1bmN0aW9uKE0paWYgTX49TSBvciBNPD0tbWF0aC5odWdlIG9yIE0+PW1hdGguaHVnZSB0aGVuIGVycm9yKA==')unexpected number value mJiBOYhEyTHxlVwzztrRB('IqcUzjjtoEsRPrydGfAiArTFpPRDgcPcyMXBWdhNOOIlDulOMHbbPFa')..tostring(M)..mJiBOYhEyTHxlVwzztrRB('FLwBtVnzxMaNaQbhOIBPJbHzCzUOmOvAYfiNkxLixmexBZqyYPXKMxt')mJiBOYhEyTHxlVwzztrRB('vwoXwHdEBsjWEVFPQSNzWWioDlEJQrCTbecHWTRIbUcZvPNBBbuQlBCKWVuZDtyZXR1cm4gc3RyaW5nLmZvcm1hdCg=')%.14gmJiBOYhEyTHxlVwzztrRB('SDLlBTxJCejqAdKhpwXHWJxlUJrYvFkmVqmIrzbMCkLolZNLlWokYilLE0pZW5kO2xvY2FsIGo9e1s=')nilmJiBOYhEyTHxlVwzztrRB('aivNrSXoLjgpPTORMpgdFTEqFxltrLbNpeNOGGaDhYBkDQwIqZumgPBXT1CLFs=')tablemJiBOYhEyTHxlVwzztrRB('gZhalwgpJFXBKPlRyXnDExZLDKeTHjzCXuKsYqcfmmlVpXTTorqmttMXT12LFs=')stringmJiBOYhEyTHxlVwzztrRB('MprQCeSttbMJuHOeZTPXldXbRhMUnOsHSzRQyIxuHtoEAocUnzNeEEFXT1nLFs=')numbermJiBOYhEyTHxlVwzztrRB('dQAKMXfpPieSbfNyDeNVvLVqTPsgtewZxeaWxARQSUKCXMuTfdjubdHXT1hMSxb')booleanmJiBOYhEyTHxlVwzztrRB('fsVBHZhBDdEGbsRyATorXakbdwdTQzWSYRrKVQKkwaDkgsTyUkMytRwXT10b3N0cmluZ31lPWZ1bmN0aW9uKE0seilsb2NhbCB4PXR5cGUoTSlsb2NhbCBhMj1qW3hdaWYgYTIgdGhlbiByZXR1cm4gYTIoTSx6KWVuZDtlcnJvcig=')unexpected type mJiBOYhEyTHxlVwzztrRB('BfJbuHXgifNVTqCtuttbpQGpYMyMGPNNgbdATTskzOzJbrttzkpVmga')..x..mJiBOYhEyTHxlVwzztrRB('AwmzxTBKBzRmhGyPrEMbKlqyfPliswFlMOKhMWcUkvgEhFVoLRezXBN')mJiBOYhEyTHxlVwzztrRB('ljjUIBkTMICrWNEfQTtjLVkFUErAcAQOFtcQVRgQyCPuToCINJXHKxpKWVuZDtsb2NhbCBhMz1mdW5jdGlvbihNKXJldHVybiBlKE0pZW5kO2xvY2FsIGE0O2xvY2FsIE49ZnVuY3Rpb24oLi4uKWxvY2FsIF89e31mb3IgYTA9MSxzZWxlY3Qo')#mJiBOYhEyTHxlVwzztrRB('pHNMWCWKsSQVQMJzyZRduluNfoxOoZKYDlvayOxhiSRfRaZUIKoaqktLC4uLilkbyBfW3NlbGVjdChhMCwuLi4pXT10cnVlIGVuZDtyZXR1cm4gXyBlbmQ7bG9jYWwgTD1OKA==') mJiBOYhEyTHxlVwzztrRB('SIJsUqVqNozzAvKTSjXaYGfwLtNQFlERCCPYXUKvLAKaakEtePDZZVJLA==')\tmJiBOYhEyTHxlVwzztrRB('VbqZXsAhWNFvtsjkKefvKcZTDKCWnhCGDbRQqsLwiVLMfTodlgjZOHhLA==')\rmJiBOYhEyTHxlVwzztrRB('EGNhzGMlAHdUhzstuFfzcBEqVXeVGgsdPlPrbFMQltdMNDQMhRABOTvLA==')\nmJiBOYhEyTHxlVwzztrRB('kwBwExfYaHNjwCOKkErCffDSNyatbHbiGDuZAhsCAhmDqIsIShDqOAeKWxvY2FsIHA9Tig=') mJiBOYhEyTHxlVwzztrRB('uNRPzUbqtvcqfJdLOPkVRnwVhOlCyvovuxEmVsoEUKQMWXvIeLERXuXLA==')\tmJiBOYhEyTHxlVwzztrRB('pZStumbGvRjnrRWXeEalQmajtoqiACjTqXJLmvVVVNQUASNCTonzPbELA==')\rmJiBOYhEyTHxlVwzztrRB('rwtdqadactqSCkcFBerZNzsMXaVvWJiHegdnQJKEaSWpNlyxQhvAoeNLA==')\nmJiBOYhEyTHxlVwzztrRB('oPJUAANZTWwUGDQCXaLzSaHSDSdXojfdwkpbyraqEFiaAmCQxDzNdKELA==')]mJiBOYhEyTHxlVwzztrRB('eCEJCKQgZFLnGQdKezfZsfiQRWwJjFGepUJNfIXuDKmNOorPueMIgASLA==')}mJiBOYhEyTHxlVwzztrRB('lCVJoUHwidkSafqfavNwZiyjoIXRDoVObqeJTUACfFPvCmjnQROnHVGLA=='),mJiBOYhEyTHxlVwzztrRB('USTtlocmxlpfBkyWrExEtskkQQcdiRfMQgdIClMDLrURtHnJHsAYiyTKWxvY2FsIGE1PU4o')\\mJiBOYhEyTHxlVwzztrRB('qfCYwYXyHoQXqMCaKkhcgWGpCWBfloyTovXSmOZjiHjYehbARVgzuJILA==')/mJiBOYhEyTHxlVwzztrRB('dfKMCFOstpyabqEhBtClwHVVtjkzuGXgESaofksbwaKNrTRtuWUuYGiLA==')mJiBOYhEyTHxlVwzztrRB('FgsCOSWcESKXdSKScrOVJVCMHVkUfvHKRXYcDnuoiHZMyxdFcYRhVmf'),mJiBOYhEyTHxlVwzztrRB('cNXZbRxcgxCAMUaFRBCIMTFysellwVoSUmZcutRJPUmFJddjYTdXpZVYg=='),mJiBOYhEyTHxlVwzztrRB('kPQvamQQdZBBwxGpUkdeVsiJbaQQIuZoiPCrleKDZZAMmHxVoPmynCbZg=='),mJiBOYhEyTHxlVwzztrRB('QASYFUHsZpSpNKAbUlkZOcBICzqqxEtSlpBUoyTrGmIJdNheAweqhxqbg=='),mJiBOYhEyTHxlVwzztrRB('kyUosRxIsPAQdYgOABfAkLGYUuZzkOXTIjJGilxbYSdswlToWgfHLDHcg=='),mJiBOYhEyTHxlVwzztrRB('sgmADtCQqGOcVLAWWsPUhQjzLnrNPfpWTcfwGMqdcbLnYdpRBQbmGGvdA=='),mJiBOYhEyTHxlVwzztrRB('wWkkhOqzVFlRFvMOfsucMAkKsypnWdrVEIszeabaQCABTKmVRKTkddFdQ=='))local m=N(mJiBOYhEyTHxlVwzztrRB('XJFxmCKJOYitmeAeIJeWZLfoUFxEBRhfizHqMwoXmYXcLLFtDvWlbWBdHJ1ZQ=='),mJiBOYhEyTHxlVwzztrRB('OQueCHfqJPAPbMTYYZgOQtsKxfnCdbIkGwMlwSzMJUbKZnFYfRLhMLfZmFsc2U='),mJiBOYhEyTHxlVwzztrRB('jOULpLtifZbpRkJmSFaEzOiwIOipIhJtCGcEiPjPKvEVVGwoPtreqhRbnVsbA=='))local a6={[mJiBOYhEyTHxlVwzztrRB('pcBQujRDMpednqgIdjXIInJyMdcBsTmleIBeaGalTETazaDrpCJapvudHJ1ZQ==')]=true,[mJiBOYhEyTHxlVwzztrRB('cHorstYNUvTHOaLIFTGqoVsyZeCInnPFVIWgiOPiSGyffCclRLSaNKhZmFsc2U=')]=false,[mJiBOYhEyTHxlVwzztrRB('WDCxYjwGHpHyumOKgnYnlkbxabCxpfJsMRwpiYlUpBCnhFbNdeAJVWvbnVsbA==')]=nil}local a7=function(a8,a9,aa,ab)for a0=a9,#a8 do if aa[a8:sub(a0,a0)]~=ab then return a0 end end;return#a8+1 end;local ac=function(a8,a9,J)local ad=1;local ae=1;for a0=1,a9-1 do ae=ae+1;if a8:sub(a0,a0)==mJiBOYhEyTHxlVwzztrRB('DdkwvbkcSUgTTpKcUUhfuTEPGBIyaYFTbrhHVhIbAKmqIvkPqbUZDDsXG4=')then ad=ad+1;ae=1 end end;error(string.format(mJiBOYhEyTHxlVwzztrRB('ZpaxkjRpFyuHcGRlHcaoGDRdcvVMPYUgUefPqgtrHhezJmoNDachOSUJXMgYXQgbGluZSAlZCBjb2wgJWQ='),J,ad,ae))end;local af=function(A)local a2=math.floor;if A<=0x7f then return string.char(A)elseif A<=0x7ff then return string.char(a2(A/64)+192,A%64+128)elseif A<=0xffff then return string.char(a2(A/4096)+224,a2(A%4096/64)+128,A%64+128)elseif A<=0x10ffff then return string.char(a2(A/262144)+240,a2(A%262144/4096)+128,a2(A%4096/64)+128,A%64+128)end;error(string.format(mJiBOYhEyTHxlVwzztrRB('RRoBmCnEbtjKnQFlYqPVhpMWZOcRwrvfrZkCQaeUGoJUkxBXrtKLcKZaW52YWxpZCB1bmljb2RlIGNvZGVwb2ludCA=')%xmJiBOYhEyTHxlVwzztrRB('LGhvtAUHjSgmetghOXRpIvlqgEISogLCOhwTFnlOpjKHwTzqSDxyHZt'),A))end;local ag=function(ah)local ai=tonumber(ah:sub(1,4),16)local aj=tonumber(ah:sub(7,10),16)if aj then return af((ai-0xd800)*0x400+aj-0xdc00+0x10000)else return af(ai)end end;local ak=function(a8,a0)local _=mJiBOYhEyTHxlVwzztrRB('dQmcMVowSbeZAVcPZeXVCBGFPaijsqjgYNExsmrWWwyOEBTekrWwstq')local al=a0+1;local Q=al;while al<=#a8 do local am=a8:byte(al)if am<32 then ac(a8,al,mJiBOYhEyTHxlVwzztrRB('itEmHkgeyUGwpkJcXoPdZfreIbOxeAUESEGxrDlUnBvvOarpcUMdyfxY29udHJvbCBjaGFyYWN0ZXIgaW4gc3RyaW5n'))elseif am==92 then _=_..a8:sub(Q,al-1)al=al+1;local T=a8:sub(al,al)if T==mJiBOYhEyTHxlVwzztrRB('JoywTRNbOKcrGrKXummqhNcxVBhzOBrzDVJliqpfRQuvlZkDrKrEonwdQ==')then local an=a8:match(mJiBOYhEyTHxlVwzztrRB('bNBgzfbeYkxjnsTbacgEOWGghEBGgOdTdiWjUVwesUqttsHQzvesNxxXltkRF1bODlhQWJCXSV4JXhcXHUleCV4JXgleA=='),al+1)or a8:match(mJiBOYhEyTHxlVwzztrRB('SrObYjFHmgcNcuOLVKHtYrwkSzQJwktOrfqJGDKOVEHwnmndGVzvoPzXiV4JXgleCV4'),al+1)or ac(a8,al-1,mJiBOYhEyTHxlVwzztrRB('vkBvMKsRqCOLSmtQdgTGTZEXhKkWgkPggCtFyaHjmdCoBuvgSIPiFLJaW52YWxpZCB1bmljb2RlIGVzY2FwZSBpbiBzdHJpbmc='))_=_..ag(an)al=al+#an else if not a5[T]then ac(a8,al-1,mJiBOYhEyTHxlVwzztrRB('qJHGWDsbyGSBaPFeXYEiFFpIdaTmVOoocnkESDdQljOBZyoYxbxvahiaW52YWxpZCBlc2NhcGUgY2hhciA=')mJiBOYhEyTHxlVwzztrRB('ukMzWWdvhyNHZSCeRQJVhGDHorcxXGZpwmYEFEIMlsPuympreDkHqYgLi5ULi4=')mJiBOYhEyTHxlVwzztrRB('ebMjuwGdzhvpyBFJNkidfyqxHvEXzsxKOoygrnNCcYoujVyGGGZFHmRIGluIHN0cmluZw=='))end;_=_..P[T]end;Q=al+1 elseif am==34 then _=_..a8:sub(Q,al-1)return _,al+1 end;al=al+1 end;ac(a8,a0,mJiBOYhEyTHxlVwzztrRB('UlCnyWdqKTCWLzlHDzcMFxChlrfctFqYffxrYjeGGdmlFmbFpWQRKXcZXhwZWN0ZWQgY2xvc2luZyBxdW90ZSBmb3Igc3RyaW5n'))end;local ao=function(a8,a0)local am=a7(a8,a0,p)local ah=a8:sub(a0,am-1)local A=tonumber(ah)if not A then ac(a8,a0,mJiBOYhEyTHxlVwzztrRB('RSjuFCtUnMVVdmRUiBksuffDIaQbtmbeDIstdUoSKSgSXqASmtDmFsdaW52YWxpZCBudW1iZXIg')mJiBOYhEyTHxlVwzztrRB('kODeWdJqSNtGnjbyzgslfujowktXAhVjNLuCMjPLXIEfWkRHJfsdtKkLi5haC4u')mJiBOYhEyTHxlVwzztrRB('WjTqzNUiHQnZcgVdhiJzfSvPLOPDSxWOswSgckbaexzRgZJOUwIiwJD'))end;return A,am end;local ap=function(a8,a0)local am=a7(a8,a0,p)local aq=a8:sub(a0,am-1)if not m[aq]then ac(a8,a0,mJiBOYhEyTHxlVwzztrRB('WZbieztvvQeYHywnGQTwmbyHgKXmJHmwjEwUGJdWEMRYGdXTQmPcuogaW52YWxpZCBsaXRlcmFsIA==')mJiBOYhEyTHxlVwzztrRB('IIcqdmDuPRlXkoYSeaYEuARXsYoNscAUcahpYzyEVIveYJJUwaJnRRqLi5hcS4u')mJiBOYhEyTHxlVwzztrRB('nalxbkQhqWuEOwMpwAoAHGbrVhvNkXiCmYvuQccdXHvBKjmtuWacvda'))end;return a6[aq],am end;local ar=function(a8,a0)local _={}local A=1;a0=a0+1;while 1 do local am;a0=a7(a8,a0,L,true)if a8:sub(a0,a0)==mJiBOYhEyTHxlVwzztrRB('ACXNxxKVVYiSnFODoHZyDFnvXlqRjAzOtetnOueHWyShsENSwEYhQfKXQ==')then a0=a0+1;break end;am,a0=a4(a8,a0)_[A]=am;A=A+1;a0=a7(a8,a0,L,true)local as=a8:sub(a0,a0)a0=a0+1;if as==mJiBOYhEyTHxlVwzztrRB('kUwvkQcnVxpUKGfpdFodOFeTJcvOcIgvFBqimZzDXwrzmCsXCCZoehEXQ==')then break end;if as~=mJiBOYhEyTHxlVwzztrRB('sxAJVBkLpkldckeKbWGgSBhRIWSOHOzFaemWqEvKBUbTjVfwSEBlPXeLA==')then ac(a8,a0,mJiBOYhEyTHxlVwzztrRB('AjkwuOJInAKkvCQbxUctgKdSdZCnpoLfZMPzKIrJJCjfafUEwMXnmSzZXhwZWN0ZWQg')]mJiBOYhEyTHxlVwzztrRB('oHWIWOiBgdGmHTHyNgZzeNMTgmEOxHsmcBFFGNDTvezUuFrLqprJchcIG9yIA=='),mJiBOYhEyTHxlVwzztrRB('tTuJZjSfTJuPHroxxYpoKrfMApPMGHuzOdfLqdgQPybxjWSeOljtHOq'))end end;return _,a0 end;local at=function(a8,a0)local _={}a0=a0+1;while 1 do local au,M;a0=a7(a8,a0,L,true)if a8:sub(a0,a0)==mJiBOYhEyTHxlVwzztrRB('InUamqWzMyfSGmElmApryfMfjVmedEvHvxwmnYiRoLprFbsAmFPvhYLfQ==')then a0=a0+1;break end;if a8:sub(a0,a0)~=mJiBOYhEyTHxlVwzztrRB('yBqHMDpFXPBUgEqXfFFpMWQeHqyqWAUcNhxNIBCQbdjoabeMtiYheSl')mJiBOYhEyTHxlVwzztrRB('fMRfGMUURuGdUfVXzNuVccKgBhIokUucojjUykvDomosWmOLyIVocoZdGhlbiBhYyhhOCxhMCw=')expected string for keymJiBOYhEyTHxlVwzztrRB('ZzQRZNjOoqyUhzgzziUtBAwrJQgUDlgyDRECjUzVylDacPwWXIQKZcjKWVuZDthdSxhMD1hNChhOCxhMClhMD1hNyhhOCxhMCxMLHRydWUpaWYgYTg6c3ViKGEwLGEwKX49'):mJiBOYhEyTHxlVwzztrRB('YqWSqZnwgtBzibYytJLVmMHfGjRgUZuPEKHcqxZVvWbzXZwmtkeOYaUdGhlbiBhYyhhOCxhMCw=')expected mJiBOYhEyTHxlVwzztrRB('LMlnwWigTlIculNuJjsQGSnQFLYLgYWPjIdwdeyHMWdSjMcoXGBZFDwOg==') after keymJiBOYhEyTHxlVwzztrRB('vdPutkAudRoyaNqSPkOrsgIYVtbvHJyjUIWcCPkBNAxSdYflAacEgHdKWVuZDthMD1hNyhhOCxhMCsxLEwsdHJ1ZSlNLGEwPWE0KGE4LGEwKV9bYXVdPU07YTA9YTcoYTgsYTAsTCx0cnVlKWxvY2FsIGFzPWE4OnN1YihhMCxhMClhMD1hMCsxO2lmIGFzPT0=')}mJiBOYhEyTHxlVwzztrRB('ApZRKjQxMHGFxPXWgjGotNvoNWuhMURQckqLmaLSVWdRPgCTwnIWPDxdGhlbiBicmVhayBlbmQ7aWYgYXN+PQ=='),mJiBOYhEyTHxlVwzztrRB('hKDoSVpHMnBzYaSggVRpMpywNaBnRZievFWVJprQWwiPPqDaBmKmxqwdGhlbiBhYyhhOCxhMCw=')expected mJiBOYhEyTHxlVwzztrRB('NuTwaoniQcNZDQXJxaNOoqbzddaKRLYmvvUUJymNAAClyVrjEKhCeehfQ==') or mJiBOYhEyTHxlVwzztrRB('hhUAPbWUXOyCbWjZOHUmpEVzpMvTXvaEftBMFkQZZUUVCwHgCbNfCukLA==')mJiBOYhEyTHxlVwzztrRB('zXiBlBXEDVhwIIITTDttlIisofwMwscfDbcFZuLZFWfqoPWyprqlnZBKWVuZCBlbmQ7cmV0dXJuIF8sYTAgZW5kO2xvY2FsIGF2PXtb')mJiBOYhEyTHxlVwzztrRB('zVJqgtbiwCTlhocZnaMTKTtRgbDucCSLuklgPklZfCHTgrZFkBkuqHJ')]=ak,[mJiBOYhEyTHxlVwzztrRB('woEPLLczJDtMTcPKexPlbiybOcsWfGbONBClgXjJAoGwKMHpwRxjDazMA==')]=ao,[mJiBOYhEyTHxlVwzztrRB('FWZymIfXAzgqcyrKLlaOFflRsfCQbexQVIlgjXrzLcxVUinSpPGmkDAMQ==')]=ao,[mJiBOYhEyTHxlVwzztrRB('DdWszEuyipdEiNmBCCzKoSwCYJvsGeahJavdIYckWFdPUaEwHXUUDtyMg==')]=ao,[mJiBOYhEyTHxlVwzztrRB('lEJyZrzwMrYYlKGxlCAuOAsPFWOhqwQCQkmBEerLKPZVPuzzEhNrHOBMw==')]=ao,[mJiBOYhEyTHxlVwzztrRB('aGAktUGzLotpFgulfzFsxhzmmMmTbmycgIyXKAVWeKHlalLSUnlwHYWNA==')]=ao,[mJiBOYhEyTHxlVwzztrRB('SUBigsgCbFmOHLatZDjyOJkxAFBbQgMnaWToTBDvmTPdgKiCQmcsVeiNQ==')]=ao,[mJiBOYhEyTHxlVwzztrRB('QDMSMdcnoDRyXmHYnwEHahkvIhxtZJoyuGdHHrIGfZvKUYTPhKTRBxUNg==')]=ao,[mJiBOYhEyTHxlVwzztrRB('FhVjribpdsJNasdFykeLKrVoqFaPgNfJdaZnmLjvpBdGRjnXVyNJZUwNw==')]=ao,[mJiBOYhEyTHxlVwzztrRB('PLTDkHUkqReTQNEgZOcrpFfXnQyqNUWvswCmKiYzkRgKkasfxPZofjVOA==')]=ao,[mJiBOYhEyTHxlVwzztrRB('WzcJnEjpbLjwftNnOiCUDroAuPdEgPaEJiGkYhwykKaUbnoqtrulAimOQ==')]=ao,[mJiBOYhEyTHxlVwzztrRB('HxVreQzxeIqqyvEgEFuzPsvbhLDAobtkOFaOberPZsvOhEIBbchsYuRLQ==')]=ao,[mJiBOYhEyTHxlVwzztrRB('BkukOGqTVytQGlOMKiFCJyVzJJTfgnvISjhBykZusVwSToOGUFZpeVmdA==')]=ap,[mJiBOYhEyTHxlVwzztrRB('CjUliqGokoSgIVQiDbApFMaSuUDWILnxdxoRppFQCygLhVlmMffuXLDZg==')]=ap,[mJiBOYhEyTHxlVwzztrRB('cJYmQpgHVVVqlymPKXSDeveIaIWUFmoBXXdwfwxnlFvYGvJhfejArjSbg==')]=ap,[mJiBOYhEyTHxlVwzztrRB('qLoBuHUgreEQCIuGQIlNCzxIKBkiDPRsqxLpkHkddWgSJDLTvCVROJxWw==')]=ar,[mJiBOYhEyTHxlVwzztrRB('iAqGcdPjDzmIoTLqSMEGEKEkfXXzDfiLabfOzsNAVASQpnyhWLYaKOKew==')]=at}a4=function(a8,a9)local as=a8:sub(a9,a9)local a2=av[as]if a2 then return a2(a8,a9)end;ac(a8,a9,mJiBOYhEyTHxlVwzztrRB('RlZbIDRNnscWiUsIYeLWAEBOrEPHNcHiTlqXyjZYueBpQANDenrOoCwdW5leHBlY3RlZCBjaGFyYWN0ZXIg')mJiBOYhEyTHxlVwzztrRB('jgjtHIfAlmDTBpGIEIQOWsTyertjNDMMDSPUnEBwHxLUJXXGyRyuwRWLi5hcy4u')mJiBOYhEyTHxlVwzztrRB('RFeJdkblLjcFSCOJKfkSFxUvsDvvxcNUSXTrLtatPqizgkXgZllijvI'))end;local aw=function(a8)if type(a8)~=mJiBOYhEyTHxlVwzztrRB('aNYtdCXvHRqzZXSiVqqcvkOxiOiKcoMAMgNoTQqTQvMirIRWuYpmjhjc3RyaW5n')then error(mJiBOYhEyTHxlVwzztrRB('bNlJpXpQisXmGUzQHXVfEbcQbcSYFYmxwgFKgPXMYBqtQEASayDPlwhZXhwZWN0ZWQgYXJndW1lbnQgb2YgdHlwZSBzdHJpbmcsIGdvdCA=')..type(a8))end;local _,a9=a4(a8,a7(a8,1,L,true))a9=a7(a8,a9,L,true)if a9<=#a8 then ac(a8,a9,mJiBOYhEyTHxlVwzztrRB('MIXGobqXqJXYDiOPpygdKaCIylLfDuSOqglZemfFihQncSeFKawZUWWdHJhaWxpbmcgZ2FyYmFnZQ=='))end;return _ end;
local lEncode, lDecode, lDigest = a3, aw, Z;
-------------------------------------------------------------------------------

-------------------------------------------------------------------------------
--! platoboost library

--! configuration
local service = 4012;  -- your service id, this is used to identify your service.
local secret = mJiBOYhEyTHxlVwzztrRB('rfWkdLvHlGoROCyMLXJQlWGPAaIBtfBCgmhBtoeKatjHKJRZRaAlBgqYTYxZGU4ZWMtNWFkYi00YWMzLTkxODAtMjZmNDRmNTg1ZjNh');  -- make sure to obfuscate this if you want to ensure security.
local useNonce = true;  -- use a nonce to prevent replay attacks and request tampering.

--! callbacks
local onMessage = function(message) end;

--! wait for game to load
repeat task.wait(1) until game:IsLoaded();

--! functions
local requestSending = false;
local fSetClipboard, fRequest, fStringChar, fToString, fStringSub, fOsTime, fMathRandom, fMathFloor, fGetHwid = setclipboard or toclipboard, request or http_request or syn_request, string.char, tostring, string.sub, os.time, math.random, math.floor, gethwid or function() return game:GetService(mJiBOYhEyTHxlVwzztrRB('LCRwuzlvcjTzkgYPoZVLbpEISXkpNCYPVSPeAEMRNCJNKCrKxXqgbElUGxheWVycw==')).LocalPlayer.UserId end
local cachedLink, cachedTime = mJiBOYhEyTHxlVwzztrRB('TuXnhYUDYjUuckwWEfKPwmqdJdmaVnSEvetzTQLvTgDwlAfIaNaVwsf'), 0;

--! pick host
local host = mJiBOYhEyTHxlVwzztrRB('NXCzOtHypaFkVTEsTrcCqIMhCEgcwLslmWMzPGnrlSSLPbrWiEJqcgFaHR0cHM6Ly9hcGkucGxhdG9ib29zdC5jb20=');
local hostResponse = fRequest({
    Url = host .. mJiBOYhEyTHxlVwzztrRB('kkdMKjwVbNLeEvOCMduhWgoPqKvZkxsUmrISWYZXctfQOnwiQCqygHBL3B1YmxpYy9jb25uZWN0aXZpdHk='),
    Method = mJiBOYhEyTHxlVwzztrRB('LDvkCDgzWHteZHfTFTIzvkQtIsVmjARcrnmpDuqyayxLzVNjyiydSDZR0VU')
});
if hostResponse.StatusCode ~= 200 or hostResponse.StatusCode ~= 429 then
    host = mJiBOYhEyTHxlVwzztrRB('YzTArKHpjpmHUEbHkLTOpNJMmoLwynbwjKbobSgcFncLWmVJuWpWyCYaHR0cHM6Ly9hcGkucGxhdG9ib29zdC5uZXQ=');
end

--!optimize 2
function cacheLink()
    if cachedTime + (10*60) < fOsTime() then
        local response = fRequest({
            Url = host .. mJiBOYhEyTHxlVwzztrRB('JTgZwjUqeABsPcTdTmHLIYMiIOIrrxDiyiadqRDkAsJwJYoPYDbsXsSL3B1YmxpYy9zdGFydA=='),
            Method = mJiBOYhEyTHxlVwzztrRB('ghWPgBcPlfdVKWdLvSxfhgHDubBLQvmoqdCEZYTBWEdPOsoOrxjsEWFUE9TVA=='),
            Body = lEncode({
                service = service,
                identifier = lDigest(fGetHwid())
            }),
            Headers = {
                [mJiBOYhEyTHxlVwzztrRB('rTSANoAgWhmdaIfHeHHIOoOlSTbSQncnHnEiUhtqVmpMRjSPEbPPIoHQ29udGVudC1UeXBl')] = mJiBOYhEyTHxlVwzztrRB('qHBXSEzSCSlsikjZlqqZqqpPCAonaiLLvYOeIruOziKnDwUfvUBfROIYXBwbGljYXRpb24vanNvbg==')
            }
        });

        if response.StatusCode == 200 then
            local decoded = lDecode(response.Body);

            if decoded.success == true then
                cachedLink = decoded.data.url;
                cachedTime = fOsTime();
                return true, cachedLink;
            else
                onMessage(decoded.message);
                return false, decoded.message;
            end
        elseif response.StatusCode == 429 then
            local msg = mJiBOYhEyTHxlVwzztrRB('iVUMVhIktKZhnBvHmrozzaVEOadEjTWUtrqUkGUMZPpilHNKQSOdjQVeW91IGFyZSBiZWluZyByYXRlIGxpbWl0ZWQsIHBsZWFzZSB3YWl0IDIwIHNlY29uZHMgYW5kIHRyeSBhZ2Fpbi4=');
            onMessage(msg);
            return false, msg;
        end

        local msg = mJiBOYhEyTHxlVwzztrRB('ckllmQhhwzNXNQkzJDOtTsmGCILFLYcTWzyazLMSkYsPgEJwqnsFtPKRmFpbGVkIHRvIGNhY2hlIGxpbmsu');
        onMessage(msg);
        return false, msg;
    else
        return true, cachedLink;
    end
end

cacheLink();

--!optimize 2
local generateNonce = function()
    local str = mJiBOYhEyTHxlVwzztrRB('BrJpPTgVCMkBomvHROoSlXSdBThVbwEiCphxRZPGXDSAFtVEhxwjMqz')
    for _ = 1, 16 do
        str = str .. fStringChar(fMathFloor(fMathRandom() * (122 - 97 + 1)) + 97)
    end
    return str
end

--!optimize 1
for _ = 1, 5 do
    local oNonce = generateNonce();
    task.wait(0.2)
    if generateNonce() == oNonce then
        local msg = mJiBOYhEyTHxlVwzztrRB('FlXKqSwuAZxIlqKQYyaeCiZRxUpUwsCdZAFXmZYFLfDJBSAmPPsFzAucGxhdG9ib29zdCBub25jZSBlcnJvci4=');
        onMessage(msg);
        error(msg);
    end
end

--!optimize 2
local copyLink = function()
    local success, link = cacheLink();
    
    if success then
        fSetClipboard(link);
    end
end

--!optimize 2
local redeemKey = function(key)
    local nonce = generateNonce();
    local endpoint = host .. mJiBOYhEyTHxlVwzztrRB('fKqxihaYpDEZNGptGuSotRBkRXrqaYgnpyWmEPIPGbmFBgNgyRaEqzcL3B1YmxpYy9yZWRlZW0v') .. fToString(service);

    local body = {
        identifier = lDigest(fGetHwid()),
        key = key
    }

    if useNonce then
        body.nonce = nonce;
    end

    local response = fRequest({
        Url = endpoint,
        Method = mJiBOYhEyTHxlVwzztrRB('IsNXjlEFZDauuFurhyaReYhQYRDbOddpKRGdypFqCAwIaVFWPJWbjuJUE9TVA=='),
        Body = lEncode(body),
        Headers = {
            [mJiBOYhEyTHxlVwzztrRB('WfnPnMnYKFrGdsAwwALDrqCvajBBpgMYNpEmmhDysrqHWAOROKdtaUWQ29udGVudC1UeXBl')] = mJiBOYhEyTHxlVwzztrRB('ErgnTnXYewWRKCNTUEcsfjSugnnCNquVpDofDuTMfNqJVSfJweKHKeIYXBwbGljYXRpb24vanNvbg==')
        }
    });

    if response.StatusCode == 200 then
        local decoded = lDecode(response.Body);

        if decoded.success == true then
            if decoded.data.valid == true then
                if useNonce then
                    if decoded.data.hash == lDigest(mJiBOYhEyTHxlVwzztrRB('ydkmGJySvvQrIqwYYOFULBpmehDJttLxKWjvhrevUvSWTtsGGmQssBcdHJ1ZQ==') .. mJiBOYhEyTHxlVwzztrRB('pDGEplxpTKHNpGYxAVWurMyeLgCSdGIOiXDqBUMnzWtpzlwfkYFTKRzLQ==') .. nonce .. mJiBOYhEyTHxlVwzztrRB('DGdKXlymzgiqQUCnGhViTupHYQzFDAfGCDtTeZnlCVgrVdwDhMLvKqFLQ==') .. secret) then
                        return true;
                    else
                        onMessage(mJiBOYhEyTHxlVwzztrRB('UJHlIxIsrAbGzgdskJFEIslcRNgSCjdADDhBaaePMpvxRvWbpWdydFSZmFpbGVkIHRvIHZlcmlmeSBpbnRlZ3JpdHku'));
                        return false;
                    end    
                else
                    return true;
                end
            else
                onMessage(mJiBOYhEyTHxlVwzztrRB('rwSAdnKdLZNuiWhcyGKmVUWyDqdrXWJkyjofcJZFpNrjJgFXBOALgRXa2V5IGlzIGludmFsaWQu'));
                return false;
            end
        else
            if fStringSub(decoded.message, 1, 27) == mJiBOYhEyTHxlVwzztrRB('gkbFTyzTUEpeVuoNTVglRTaMBUbbUMyvvdzLewvwWcoNsLNfBLpvTDSdW5pcXVlIGNvbnN0cmFpbnQgdmlvbGF0aW9u') then
                onMessage(mJiBOYhEyTHxlVwzztrRB('oceJhUknbOzbwiTxPKcXYNHhZRmWKQerYQsPJHqmmKBUkMAmnNoLhwueW91IGFscmVhZHkgaGF2ZSBhbiBhY3RpdmUga2V5LCBwbGVhc2Ugd2FpdCBmb3IgaXQgdG8gZXhwaXJlIGJlZm9yZSByZWRlZW1pbmcgaXQu'));
                return false;
            else
                onMessage(decoded.message);
                return false;
            end
        end
    elseif response.StatusCode == 429 then
        onMessage(mJiBOYhEyTHxlVwzztrRB('HqqGVCkasCvSAdURMKtRfsPkindltOStkcZEYHcbhPiJQCRMgWqpGBieW91IGFyZSBiZWluZyByYXRlIGxpbWl0ZWQsIHBsZWFzZSB3YWl0IDIwIHNlY29uZHMgYW5kIHRyeSBhZ2Fpbi4='));
        return false;
    else
        onMessage(mJiBOYhEyTHxlVwzztrRB('wDqtfDOouryVviaVRTXUgIrDwHLidWwlcwrQXClAFXzNtfZwdazhAxmc2VydmVyIHJldHVybmVkIGFuIGludmFsaWQgc3RhdHVzIGNvZGUsIHBsZWFzZSB0cnkgYWdhaW4gbGF0ZXIu'));
        return false; 
    end
end

--!optimize 2
local verifyKey = function(key)
    if requestSending == true then
        onMessage(mJiBOYhEyTHxlVwzztrRB('SPKwaXaoCYwrszwmrAhYWELofFrWdGgmmuEfBqRaNyQOUXFhDBLWzfZYSByZXF1ZXN0IGlzIGFscmVhZHkgYmVpbmcgc2VudCwgcGxlYXNlIHNsb3cgZG93bi4='));
        return false;
    else
        requestSending = true;
    end

    local nonce = generateNonce();
    local endpoint = host .. mJiBOYhEyTHxlVwzztrRB('pEAkzLZtEYsUuKtuwBKMabSSSCeGimDVyBzQLDUQZcAlBUmmUFmazKBL3B1YmxpYy93aGl0ZWxpc3Qv') .. fToString(service) .. mJiBOYhEyTHxlVwzztrRB('avDVvLrLeuXweMXQODHvklktqwdGJqjIzGNGimBQkabPDqojVFeuPrgP2lkZW50aWZpZXI9') .. lDigest(fGetHwid()) .. mJiBOYhEyTHxlVwzztrRB('pIJjNVhDXJrnvobByZxdIHGITxUDarvdEGYGHIwavxIJMaQeiilpgatJmtleT0=') .. key;

    if useNonce then
        endpoint = endpoint .. mJiBOYhEyTHxlVwzztrRB('sjmyinECNPEAlLgHslbYhNyiihClmDEBLQceWCydafBzWJQBZePyVuFJm5vbmNlPQ==') .. nonce;
    end

    local response = fRequest({
        Url = endpoint,
        Method = mJiBOYhEyTHxlVwzztrRB('mIcMiWweBSItecHuBhCnoNZLHrXVhZoAMmzDzLwiSkoBpdjaigSUfykR0VU'),
    });

    requestSending = false;

    if response.StatusCode == 200 then
        local decoded = lDecode(response.Body);

        if decoded.success == true then
            if decoded.data.valid == true then
                if useNonce then
                    if decoded.data.hash == lDigest(mJiBOYhEyTHxlVwzztrRB('KILbeaZWRCKMfiRSqmAYjpXbAdGJoFizjZJYrcQNWkKIBUtJzezqdiZdHJ1ZQ==') .. mJiBOYhEyTHxlVwzztrRB('aVQsROLXwoIBESYZknRoCqdmDfpWgeAMufTxWCuuuTfjsSXdcbYahFKLQ==') .. nonce .. mJiBOYhEyTHxlVwzztrRB('sjiSGmVXQvNrhTCuMyUWagiFdtQowprtjjllSqjjluMLyuMtxCJGUoXLQ==') .. secret) then
                        return true;
                    else
                        onMessage(mJiBOYhEyTHxlVwzztrRB('GRodztrZUAXZFdlIpntsFPesYiMaoksOCngvxiJqcUZhNeLPSZBwcNXZmFpbGVkIHRvIHZlcmlmeSBpbnRlZ3JpdHku'));
                        return false;
                    end
                else
                    return true;
                end
            else
                if fStringSub(key, 1, 4) == mJiBOYhEyTHxlVwzztrRB('KrKqqCklluCbEGgsJvjZrjwzBSCICZkyufHZYkYTajmRYnPmxjQLZCoS0VZXw==') then
                    return redeemKey(key);
                else
                    onMessage(mJiBOYhEyTHxlVwzztrRB('DfRvoTOPhVVgPnWsvJDPWMfuIDvufCUZfDFPAoxCtkbIGNtzEYaOZmWa2V5IGlzIGludmFsaWQu'));
                    return false;
                end
            end
        else
            onMessage(decoded.message);
            return false;
        end
    elseif response.StatusCode == 429 then
        onMessage(mJiBOYhEyTHxlVwzztrRB('CEBYGsOVtbaWNkrodtaRsPAFJXkgvFIlejdTEEdYdnFKsvswRZkVyMIeW91IGFyZSBiZWluZyByYXRlIGxpbWl0ZWQsIHBsZWFzZSB3YWl0IDIwIHNlY29uZHMgYW5kIHRyeSBhZ2Fpbi4='));
        return false;
    else
        onMessage(mJiBOYhEyTHxlVwzztrRB('YaSUoJCWuWEyhMRZyoznneBFvVHbNQSkMTcsYAziVbOcRCTAmvaPskPc2VydmVyIHJldHVybmVkIGFuIGludmFsaWQgc3RhdHVzIGNvZGUsIHBsZWFzZSB0cnkgYWdhaW4gbGF0ZXIu'));
        return false;
    end
end

--!optimize 2
local getFlag = function(name)
    local nonce = generateNonce();
    local endpoint = host .. mJiBOYhEyTHxlVwzztrRB('HVistEXXsMSGucFeMvUMprteDYvkTeJyHaAJCrEQvybvNRqUnybwtNaL3B1YmxpYy9mbGFnLw==') .. fToString(service) .. mJiBOYhEyTHxlVwzztrRB('UQjOJEaScOjytaOjGVopQEUrzAXvcwjwbGEltAWkwtQhRgofFRRYFtAP25hbWU9') .. name;

    if useNonce then
        endpoint = endpoint .. mJiBOYhEyTHxlVwzztrRB('oDZjJpkVnAnVvvUXpwSWLVchlzxpcnxeTbMLMZcDFNpQpMBwnDCFxraJm5vbmNlPQ==') .. nonce;
    end

    local response = fRequest({
        Url = endpoint,
        Method = mJiBOYhEyTHxlVwzztrRB('aPzCLqfIBRUnUDRUrByNxhNwndrpzyEnXWVfboRICwwJmjwBqeTnnBwR0VU'),
    });

    if response.StatusCode == 200 then
        local decoded = lDecode(response.Body);

        if decoded.success == true then
            if useNonce then
                if decoded.data.hash == lDigest(fToString(decoded.data.value) .. mJiBOYhEyTHxlVwzztrRB('UiuHizLKCRPKMMVPFlDhVUdhZBNjyirsqaxtmXtqRSxUZyWHtDypjYBLQ==') .. nonce .. mJiBOYhEyTHxlVwzztrRB('DtwVfUUyMkBWtXNtMTcMeoNefZKypPBFgneduKgvGXaZFjVTodTzSQiLQ==') .. secret) then
                    return decoded.data.value;
                else
                    onMessage(mJiBOYhEyTHxlVwzztrRB('IyJxYuZePbRBkcCOfNFHLVCeVFfGfGXbEIzUjJXpqniDMCoCjcGgvjsZmFpbGVkIHRvIHZlcmlmeSBpbnRlZ3JpdHku'));
                    return nil;
                end
            else
                return decoded.data.value;
            end
        else
            onMessage(decoded.message);
            return nil;
        end
    else
        return nil;
    end
end


local player = game.Players.LocalPlayer 

local scr = Instance.new(mJiBOYhEyTHxlVwzztrRB('pceXbtqQMqVpbBlnoAzvUAxDIzjWovWVVgwSGlpAprjOdprVQdoMHVkU2NyZWVuR3Vp'), player.PlayerGui)
local principal = Instance.new(mJiBOYhEyTHxlVwzztrRB('ZXGvUsTXTyaNpclILewUYWTCnBUwfXwSnrDfEnyIbZCUvxsQqpwIxhvRnJhbWU='), scr)
principal.Size = UDim2.new(0.4, 0, 0.4, 0)
principal.Position = UDim2.new(0.3, 0, 0.3, 0)
principal.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
principal.BackgroundTransparency = 0.4

local key = Instance.new(mJiBOYhEyTHxlVwzztrRB('sMSXEdyLHfSibLBMnGdLgEYypwsvMRdbvPSJikKPfEesWZHqWZGljjeVGV4dEJveA=='), principal)
key.Text = mJiBOYhEyTHxlVwzztrRB('oyIVDjkWxhRcCTUoTzYOkzzFPVoCmpMDugzCIRMCaMbmjcFdWvzvtVacHV0IHlvdXIga2V5IGhlcmU=')
key.Position = UDim2.new(0.1, 0, 0.4, 0)
key.Size = UDim2.new(0.8, 0, 0.15, 0)


local pegar_key = Instance.new(mJiBOYhEyTHxlVwzztrRB('ccKGxwrcsDtcJgyqKsMOLdTQLlJopuSQCCfVLzDsIaxCmlpPhYuXNosVGV4dEJ1dHRvbg=='), principal)
pegar_key.Size = UDim2.new(0.25, 0, 0.25, 0)
pegar_key.Text = mJiBOYhEyTHxlVwzztrRB('vfZSgFpjYQojFTEsWmumZnvCCZikdVbgiSZaMcjNrEnBxuYZJnJTFpgZ2V0IGtleQ==')
pegar_key.Position = UDim2.new(0, 0, 0.75, 0)




local checar_key =  Instance.new(mJiBOYhEyTHxlVwzztrRB('LNTDEujlfTDexffXvMatofbdVVuXuVsQVIrQIWxGTukPDEdISrgPrJjVGV4dEJ1dHRvbg=='), principal)
checar_key.Position = UDim2.new(0.75, 0, 0.75, 0)
checar_key.Size = UDim2.new(0.25, 0, 0.25, 0)
checar_key.Text = mJiBOYhEyTHxlVwzztrRB('vUXXntwIReBxlMkBPiZMMYVeDcIeVmZOjjdpdsOBSSeMLFiUmzrHhzqY2hlY2sga2V5')



local x = Instance.new(mJiBOYhEyTHxlVwzztrRB('smnsuGOgpGHdYWZKopFCbhOHXiZRXgBCbABQyiOVeNwMHeVIABlZqmcVGV4dEJ1dHRvbg=='), principal)
x.Position = UDim2.new(1, 0, 0, 0)
x.Size = UDim2.new(0.20, 0, 0.20,  0)
x.Text = mJiBOYhEyTHxlVwzztrRB('shLhIbyEZoWyelFzIGcZaNQVQqCQcLCVCCPAiojBumZoUkEtFwLgrOTWA==')
x.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
x.BackgroundTransparency = 1
x.TextScaled = true

x.MouseButton1Click:Connect(function()
principal:Destroy()
scr:Destroy()

end)


local titulo = Instance.new(mJiBOYhEyTHxlVwzztrRB('mQjEzkFvlWTSxqtQTFlVGhitnJlvINjhiyDpeErBvWvwVqmTunHnxKZVGV4dExhYmVs'),  principal)
titulo.Size = UDim2.new(0.7, 0, 0.1, 0)
titulo.Text = mJiBOYhEyTHxlVwzztrRB('rVHhTQtkeuHtGaNuVuXSQmLQoHrDPqDntvHYVzzYSewEllYGkKLKHgRYnkgcm9ibG94IHJlYWxtcw==')
titulo.Position = UDim2.new(0.15, 0, 0.1, 0)
titulo.BackgroundColor3 = Color3.fromRGB(232, 10, 18)
titulo.TextScaled = true



pegar_key.MouseButton1Click:Connect(function()
    
    copyLink();
    
end)

checar_key.MouseButton1Click:Connect(function()
local key = key.Text
local success = verifyKey(key);

    if success then
        aba()
        print(mJiBOYhEyTHxlVwzztrRB('nIqJrHYGnsBpXEQsRKRNxVjxPvXRyypRmCSSXWUJffIAuMuTWAgAdTLa2V5IGVuY29udHJhZG8='))
principal:Destroy()
    else
        print(mJiBOYhEyTHxlVwzztrRB('GMtHZVtZLVkojfgiHhwppUUnssZdkgbxOYVQUwrAXCRzKIrwcLPJduva2V5IGludmFsaWQu'))
    end
end)
    
