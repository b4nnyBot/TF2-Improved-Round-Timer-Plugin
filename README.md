# Setup
roundtimer_override.sp goes to /tf/addons/sourcemod/scripting folder   
roundtimer_override.smx goes to /tf/addons/sourcemod/plugins folder   

# Operation
The plugin creates the "round_time_override" cvar   
Value is in seconds   
Ex: rcon round_time_override 180 would set round timer to 3 minutes   
Value of -1 disables round timer override, reverts back to default 10 minutes   
Changes take effect on round restart   

# Recommended Settings
round_time_override 180
mp_timelimit 0
mp_winlimit 5
