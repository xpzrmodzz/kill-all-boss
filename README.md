while true do
    wait()

    -- Script pour le NPC DragonGiraffe
    local args1 = {
        [1] = workspace.NPC.DragonGiraffe.Humanoid,
        [2] = 2
    }
    game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(unpack(args1))

    -- Script pour le NPC Griffin
    local args2 = {
        [1] = workspace.NPC.Griffin.Humanoid,
        [2] = 4
    }
    game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(unpack(args2))

    -- Script pour le NPC LavaGorilla
    local args3 = {
        [1] = workspace.NPC.LavaGorilla.Humanoid,
        [2] = 6
    }
    game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(unpack(args3))

    -- Script pour le NPC CENTAUR
    local args4 = {
        [1] = workspace.NPC.CENTAUR.Humanoid,
        [2] = 1
    }
    game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli:FireServer(unpack(args4))
end
