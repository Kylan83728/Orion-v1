local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "ASTRAL HUB-animal simulator🐻",
   LoadingTitle = "animal simulator🐻",
   LoadingSubtitle = "HUB",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})


local farmTab = Window:CreateTab("Farm", 4483362458) -- Title, Image


local Button = farmTab:CreateButton({
   Name = "anti afk😴",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/2n6FV7Sc"))()
   -- The function that takes place when the button is pressed
   end,
})


local Toggle = farmTab:CreateToggle({
   Name = "🔥farm 5k",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
while true do
local args = {
    [1] = workspace:WaitForChild("MAP"):WaitForChild("5k_dummies"):WaitForChild("Dummy2"):WaitForChild("Humanoid"),
    [2] = 1
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
wait()
end
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local Toggle = farmTab:CreateToggle({
   Name = "farm Spawn👊🔥",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
while true do
local args = {
    [1] = workspace:WaitForChild("MAP"):WaitForChild("dummies"):WaitForChild("Dummy"):WaitForChild("Humanoid"),
    [2] = 3
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
wait()
end
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local Toggle = farmTab:CreateToggle({
   Name = "fire ball spawn🔥",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/VnwNzUvN"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})



local Toggle = farmTab:CreateToggle({
   Name = "fire ball 5k🔥",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/A6GH96ed"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})



local Toggle = farmTab:CreateToggle({
   Name = "auto coin💲",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
while true do
game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("CoinEvent"):FireServer()
wait()
end
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local Toggle = farmTab:CreateToggle({
   Name = "kill all boss🐎🦒🐈🔥🐸🦀🐻",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
while true do
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("Griffin"):WaitForChild("Humanoid"),
    [2] = 3
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("CRABBOSS"):WaitForChild("Humanoid"),
    [2] = 1
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("LavaGorilla"):WaitForChild("Humanoid"),
    [2] = 5
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("CENTAUR"):WaitForChild("Humanoid"),
    [2] = 4
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
local args = {
    [1] = workspace:WaitForChild("NPC"):WaitForChild("DragonGiraffe"):WaitForChild("Humanoid"),
    [2] = 1
}
 
game:GetService("ReplicatedStorage"):WaitForChild("jdskhfsIIIllliiIIIdchgdIiIIIlIlIli"):FireServer(unpack(args))
wait()
end
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local pvpTab = Window:CreateTab("PvP", 4483362458) -- Title, Image


local Button = pvpTab:CreateButton({
   Name = "Hitbox👻",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Vcsk/RobloxScripts/main/HitboxExpander.lua"))()
   -- The function that takes place when the button is pressed
   end,
})


local Toggle = pvpTab:CreateToggle({
   Name = "kill aura👊",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/SZRpkcYv"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})



local titreTab = Window:CreateTab("farm titre", 4483362458) -- Title, Image



local Input = titreTab:CreateInput({
   Name = "texte",
   CurrentValue = "",
   PlaceholderText = "activer tou",
   RemoveTextAfterFocusLost = false,
   Flag = "Input1",
   Callback = function(Text)
   -- The function that takes place when the input is changed
   -- The variable (Text) is a string for the value in the text box
   end,
})


local Toggle = titreTab:CreateToggle({
   Name = "tp maison",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/f109eC2i"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})



local Toggle = titreTab:CreateToggle({
   Name = "farm titre",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/hPpNpTpt"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})



local Toggle = titreTab:CreateToggle({
   Name = "titre 10kill",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
local args = {
    [1] = "NoviceHunter"
}

local repetitions = 10  -- Nombre de fois que l'événement sera envoyé

for i = 1, repetitions do
    game:GetService("ReplicatedStorage").Events.TitleEvent:FireServer(unpack(args))
    wait(1)  -- Attendre 1 seconde entre chaque envoi
end
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local trollTab = trollWindow:CreateTab("troll", 4483362458) -- Title, Image



local Toggle = trollTab:CreateToggle({
   Name = "troll kill",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/Ln8Gqhvt"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})


local clanTab = Window:CreateTab("clan", 4483362458) -- Title, Image


local Toggle = clanTab:CreateToggle({
   Name = "ASTRAL HUB",
   CurrentValue = false,
   Flag = "Toggle1", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
loadstring(game:HttpGet("https://pastebin.com/raw/XyKEJgX5"))()
   -- The function that takes place when the toggle is pressed
   -- The variable (Value) is a boolean on whether the toggle is true or false
   end,
})
