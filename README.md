MainSection:NewButton("Gold Bar", "Buy Gold From Market", function()
    local args = {
        [1] = "Gold Bar",
     }
     
     game:GetService("ReplicatedStorage").Events.PurchaseFromShop:FireServer(unpack(args))

end)

MainSection:NewButton("Crystal Chunk", "Buy Crystal Chunk From Market", function()
    local args = {
        [1] = "Crystal Chunk",
     }
     
     game:GetService("ReplicatedStorage").Events.PurchaseFromShop:FireServer(unpack(args))

end)
