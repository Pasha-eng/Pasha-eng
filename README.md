local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("Ghub UI v4*by Ghackscript", "BloodTheme")
 
-- Objects
 
local Tab1 = Window:NewTab("Main_script")
local Tab1Section = Tab1:NewSection("Main_script subscribe to ghacks script")
 
-- Buttons/Windows/FE
 
Tab1Section:NewButton("god mode toggle", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/ignore-touchinterests/main/main",true))()
end)
 
Tab1Section:NewButton("Anti fling", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/PuAwMhXK'),true))()
end)
 
Tab1Section:NewButton("Anti Ban", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/kt8x7uK0'),true))()
end)
 
Tab1Section:NewButton("chat hax troll", "ButtonInfo", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/MBpnp3yS'))()
end)
 
Tab1Section:NewButton("FE lag switch", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/Protected%20-%202023-05-28T225112.055.lua.txt'),true))()
end)
 
Tab1Section:NewButton("FPS booster", "ButtonInfo", function()
    -- Made by RIP#6666
_G.Settings = {
    Players = {
        ["Ignore Me"] = true, -- Ignore your Character
        ["Ignore Others"] = true -- Ignore other Characters
    },
    Meshes = {
        Destroy = false, -- Destroy Meshes
        LowDetail = true -- Low detail meshes (NOT SURE IT DOES ANYTHING)
    },
    Images = {
        Invisible = true, -- Invisible Images
        LowDetail = false, -- Low detail images (NOT SURE IT DOES ANYTHING)
        Destroy = false, -- Destroy Images
    },
    Other = {
        ["No Particles"] = true, -- Disables all ParticleEmitter, Trail, Smoke, Fire and Sparkles
        ["No Camera Effects"] = true, -- Disables all PostEffect's (Camera/Lighting Effects)
        ["No Explosions"] = true, -- Makes Explosion's invisible
        ["No Clothes"] = true, -- Removes Clothing from the game
        ["Low Water Graphics"] = true, -- Removes Water Quality
        ["No Shadows"] = true, -- Remove Shadows
        ["Low Rendering"] = true, -- Lower Rendering
        ["Low Quality Parts"] = true -- Lower quality parts
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/FPSBooster.lua"))()
end)
 
Tab1Section:NewButton("FE sound panel", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/SWsFdk2U'),true))()
end)
 
Tab1Section:NewButton("Anti Kick", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/VLe9pcs2'),true))()
end)
 
Tab1Section:NewButton("Inf Jump", "Enables Inf Jumps", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)
 
Tab1Section:NewToggle("Fov", "Changes Fov", function(state)
    if state then
        game.Workspace.CurrentCamera.FieldOfView = 120
    else
        game.Workspace.CurrentCamera.FieldOfView = 80
    end
end)
 
Tab1Section:NewButton("FE Teleport player gui", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/Infinity2346/Tect-Menu/main/Teleport%20Gui.lua'))()
end)
 
Tab1Section:NewSlider("Speed", "G Speed", 500, 10, function(v)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
end)
 
Tab1Section:NewButton("FE invisible gui", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Invisible%20Gui'))()
end)
 
Tab1Section:NewButton("Fly gui v3", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
end)
 
Tab1Section:NewButton("Fling gui", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_5wpM7bBcOPspmX7lQ3m75SrYNWqxZ858ai3tJdEAId6jSI05IOUB224FQ0VSAswH.lua.txt'),true))()
end)
 
Tab1Section:NewButton("Tool giver", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastefy.app/VYIAk3o1/raw'),true))()
end)
 
Tab1Section:NewButton("Dino fling", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_K2n31uc6t2wY5A8786eR4K15sgbUF0vdQ80a0LzgvLRkSNYd89H1AS3124gMR6SM.lua.txt'),true))()
end)
 
Tab1Section:NewButton("UFO kidnap gui", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/7scRrYKM'),true))()
end)
 
Tab1Section:NewButton("Control player gui", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/fJbWYetZ'),true))()
end)
 
--
 
local Tab2 = Window:NewTab("Scripts hub")
local Tab2Section = Tab2:NewSection("Scripts hub")
 
--
 
Tab2Section:NewButton("Ghost hub script", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)
 
Tab2Section:NewButton("Moon UI v10", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)
 
Tab2Section:NewButton("rosehub v3.0.1", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/9q2nraUs", true))()
end)
 
Tab2Section:NewButton("Moon UI v13", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IlikeyocutgHAH/MoonUI-v13-102-SCRIPTS/main/MoonUI%20v13!"))()
end)
 
Tab2Section:NewButton("C00lgui script", "ButtonInfo", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/theawesomari0/c00lgui/main/c00lgui"), true))()
end)
 
Tab2Section:NewButton("Vhub script", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt'),true))()
end)
 
Tab2Section:NewButton("Giga chad hub script", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Gigachad%20Hub%20V4'))()
end)
 
-- 
 
local Tab3 = Window:NewTab("FE animation script")
local Tab3Section = Tab3:NewSection("FE animation script")
 
--
 
Tab3Section:NewButton("FE animation changer gui script", "ButtonInfo", function()
    local AnimationChanger = Instance.new("ScreenGui")
    loadstring(game:HttpGet(('https://pastebin.com/raw/h4CbmhTt'),true))()
end)
 
--
 
local Tab4 = Window:NewTab("FE Keyboard script")
local Tab4Section = Tab4:NewSection("FE Keyboard script")
 
--
 
Tab4Section:NewButton("keyboard script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
end)
 
--
 
local Tab5 = Window:NewTab("Admin_script")
local Tab5Section = Tab5:NewSection("Admin_script")
 
--
 
Tab5Section:NewButton("infinite yield", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
 
Tab5Section:NewButton("Nameless Admin", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source"))();
end)
 
--
 
local Tab6 = Window:NewTab("Prison life script gui")
local Tab6Section = Tab6:NewSection("Prison life script gui")
 
--
 
Tab6Section:NewButton("Prison life script gui", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))();
end)
 
--
 
local Tab7 = Window:NewTab("Natural disaster Survival script")
local Tab7Section = Tab7:NewSection("Natural disaster Survival script")
 
--
 
Tab7Section:NewButton("Natural disaster script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CasperFlyModz/discord.gg-rips/main/NaturalDisasterSurvival.lua"))()
end)
 
--
 
local Tab8 = Window:NewTab("blox fruit script")
local Tab8Section = Tab8:NewSection("blox fruit  script")
 
--
 
Tab8Section:NewButton("blox fruit script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Domadicoof/Domadicoof/main/Domadichub/NottoGay/Start.ranscript"))()
end)
 
--
 
local Tab9 = Window:NewTab("Survive the killer script")
local Tab9Section = Tab9:NewSection("Survive the killer script")
 
--
 
Tab9Section:NewButton("Survive the killer script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Milan08Studio/ChairWare/main/main.lua"))()
end)
 
--
 
local Tab10 = Window:NewTab("Murder mystery script")
local Tab10Section = Tab10:NewSection("Murder mystery script")
 
--
 
Tab10Section:NewButton("murder mystery script", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Doggo-cryto/EclipseMM2/master/Script", true))()
end)
