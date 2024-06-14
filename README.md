v0.3 update 14/06/24 added some bypasses + fixed some


# Use this loadstring to execute:
`loadstring(game:HttpGet("https://raw.githubusercontent.com/sauce-boss01/TND-Bypasser/main/Main"))()`

# Use this loadstring to execute without anti chat logger (use in games that detect the other version or with shitty executors):
`loadstring(game:HttpGet("https://raw.githubusercontent.com/sauce-boss01/TND-Bypasser/main/No-ACL"))()`

# If the game got adonis admin, you can bypass the ACL kick with this:

`for k,v in pairs(getgc(true)) do if pcall(function() return rawget(v,"indexInstance") end) and type(rawget(v,"indexInstance")) == "table" and (rawget(v,"indexInstance"))[1] == "kick" then v.tvk = {"kick",function() return game.Workspace:WaitForChild("") end} end end` 
