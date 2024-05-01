local ui = game:GetService("CoreGui"):FindFirstChild("RobloxGui") 

if not ui then
    ui = Instance.new("ScreenGui")
    ui.Name = "RobloxGui"
    ui.Parent = game:GetService("CoreGui")

    -- combat tab
    local combatTab = Instance.new("TextButton")
    combatTab.Name = "CombatTab"
    combatTab.Size = UDim2.new(0, 100, 0, 50)
    combatTab.Position = UDim2.new(0, 0, 0, 100)
    combatTab.Text = "Combat"
    combatTab.Parent = ui

    -- Auto Parry function
    local function AutoParry()
        -- Your auto parry Script here
    end

    -- Support Blade Ball function
    local function SupportBladeBall()
        -- Your support blade ball blade ball script game here
    end

    combatTab.MouseButton1Click:Connect(function()
        if combatTab.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
            combatTab.BackgroundColor3 = Color3.fromRGB(255,255,255)
        else
            combatTab.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
        end

        -- Toggle The auto parry 
        AutoParry()

        -- Support blade ball game
        SupportBladeBall()
    end)
end
