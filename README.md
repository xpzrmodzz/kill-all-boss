-- Fonction pour tuer tous les boss en boucle
local function killAllBosses()
    while true do
        wait()

        -- Tuer le boss DragonGiraffe
        pcall(function()
            game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(workspace.NPC.DragonGiraffe.Humanoid)
        end)

        -- Tuer le boss Griffin
        pcall(function()
            game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(workspace.NPC.Griffin.Humanoid)
        end)

        -- Tuer le boss LavaGorilla
        pcall(function()
            game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(workspace.NPC.LavaGorilla.Humanoid)
        end)

        -- Tuer le boss CENTAUR
        pcall(function()
            game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(workspace.NPC.CENTAUR.Humanoid)
        end)
    end
end

-- Démarrer la fonction pour tuer les boss
killAllBosses()
