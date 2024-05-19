How to remove the "blue boxes" in the cockpit
1. Navigate to the mods files (mod folder usually in `C:\Users\%USERNAME%\Saved Games\DCS\Mods\Aircraft` or `C:\Users\%USERNAME%\Saved Games\DCS.openbeta\Mods\Aircraft`)
2. in `cockpit\scripts`, locate and open `clickabledata.lua`
3. in line 9 (`show_element_boxes = true`), add `--` to the start of the line
4. save and close the file
5. enjoy!