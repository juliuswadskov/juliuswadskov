```lua
oskar_raagart = {}

oskar_raagart.description = {
  title = "Hey i am Oskar Raagart",
  everythingElse = {
    "I develop in: PHP, JavaScript, lua, CSS and html",
    "I am making a framework for fivem called R25",
    "My favorate frameworks are Node.js, Jquery and FiveM",
    "I make a lot of scripts for the CitizenFX Collective A.K.A FiveM"
  }
}

oskar_raagart.print = function(table)
  print(table.title)
  for k, v in pairs(table.everythingElse) do
     print(v)
  end
end

oskar_raagart.whoAmI = function(table)
  oskar_raagart.print(table)
end

oskar_raagart.whoAmI(oskar_raagart.description)
```

H
E
Y

