# liquidsky-origin-fix
Working on a fix for blocked access after automatic Origin updates on LiquidSky Cloud Gaming PCs

Test #1 - failed

Adding the recommended commands (which do work when used in the windows command line / shell after the Origin installation)

net stop "Origin Web Helper Service"

sc config "Origin Web Helper Service" start= demand

as an origin-fix.bat in the autostart folder didn't work.
