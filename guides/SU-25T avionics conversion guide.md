How to convert to SU-25T avionics guide
### THIS CONVERSION DOESNT ALLOW FOR RADAR/RADAR GUIDED MISSILES, ONLY HEAT SEEKING MISSILES IN LONGITUDINAL MODE CAN BE USED!!!
1. locate and open the mod's folder (usually in `C:\Users\%USERNAME%\Saved Games\DCS\Mods\Aircraft` or in `C:\Users\%USERNAME%\Saved Games\DCS.openbeta\Mods\Aircraft`)
2. open the `entry.lua` file
3. in line 87 (first line with `make_flyable('Su-57',`), add a `--` to the start of the line
4. on the line below (line 88), remove the `--` at the start of the line
5. save and close the file
6. enjoy!