command /about [<player>]
  trigger: 
    if player is "Irzax"
      send "Hey I'm irzax!" to player
      wait 1 tick
      send "I do skripting as a hobby." to player
      wait 1 tick
      send "I started skripting since November 16th 2024." to player
      wait 1 tick
      send "So do not expect everything to work right away, there are some bugs in my skripts." to player
    else:
      send "I do not know anyone else except for Irzax" to player

on tab complete of "/about":
    set tab completions for position 1 to "Irzax"
    
