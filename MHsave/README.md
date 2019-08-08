# Memory Hacking
This is a save file for memory addresses obtained through Memory Hacking Software by L. Spiro.

### Known addresses
##### Machine select tiles
These addresses control whether you can select particular machines on the selection screen.

| Address | Description | Values |
| ---: | --- | --- |
| 0x5303EEA4 | Show Avenger tile | 0=off, 1=on |
| 0x5303EEA5 | Show Hornet tile | 0=off, 1=on |
| 0x5303EEA6 | Show Interceptor tile | 0=off, 1=on |
| 0x5303EEA7 | Show Control Pad tile | 0=off, 1=on |
| 0x5303EEA8 | Show Prowler tile | 0=off, 1=on |
| 0x5303EEA9 | Show Vengeance tile | 0=off, 1=on |
| 0x5303EEAA | Show Black Lightning tile | 0=off, 1=on |
| 0x5303EEAB | Show Shredder tile | 0=off, 1=on |
| 0x5303EEAE | Show Dominator tile | 0=off, 1=on |
| 0x5303EEAF | Show Reaper tile | 0=off, 1=on |

##### Gameplay scenario addresses
These addresses control things like which machine you're using, which course you're on, and what difficulty you're playing.

| Address | Description | Values |
| ---: | --- | --- |
| 0x530EFF94 | Machine skin | 0-1, or 0-5 for Control Pad.\* |
| 0x530EFF96 | Machine | 0-9\*\* |
| 0x530EFF97 | Difficulty | 0=Novice, 1=Intermediate, 2=Expert |
| 0x530EFF98 | Course | 0-5\*\*\* |

\* You can actually set this to just about any value to get some interesting glitchy textures. Some later values (60 or so) might halt the game.  
\*\* 0=Control Pad, 1=Interceptor, 2=Hornet, 3=Avenger, 4=Shredder, 5=Black Lightning, 6=Vengeance, 7=Prowler, 8=Reaper, 9=Dominator, 10=Ghost (not playable), 11=...One of Interceptor's wings?  
\*\*\* 0=Canyon Rush, 1=Bikini Island, 2=Chinatown, 3=Neo Arena, 4=Chinatown Jam, 5=Neo Speedway

##### Input addresses
These addresses read controller input. Work in progress.

| Address | Description | Values |
| ---: | --- | --- |
| 0x530EFFF2 | Fractional/analogue movement, vertical movement | todo |
| 0x530EFFF3 | Digital movement, horizontal movement | todo |

