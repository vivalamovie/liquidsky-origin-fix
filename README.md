# liquidsky-origin-fix
Working on a fix for blocked access after automatic Origin updates on LiquidSky Cloud Gaming PCs

__Test #1 - failed__

Sources:  
https://www.reddit.com/r/LiquidSky/comments/54xepj/how_to_fix_origin_installation_in_liquidsky/  http://community.liquidsky.tv/t/installed-origin-cant-connect/267/10

Adding the recommended commands (which do work when used in the windows command line / shell after the Origin installation)

    net stop "Origin Web Helper Service
    sc config "Origin Web Helper Service" start= demand

as an origin-fix.bat in the autostart folder didn't work.
