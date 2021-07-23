-- making function

game.Players.PlayerAdded:Connect(function(player)

-- making leaderstats

  local leaderstats = Instance.New('Folder', player)
  leaderstats.Name = 'leaderstats'
 
  -- making cum
  
  local cum = Instance.New('IntValue', leaderstats)
  cum.Name = 'Cum'
  cum.Value = 69,420
  
  -- cum has been made in game
  
end)
