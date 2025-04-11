This is a json file intended to be used for Karabiner-Elements on mac

Setup:
1. Install and setup Karabiner-Elements
2. Open your terminal and run:
   - cd ~/.config/karabiner/assets/complex_modifications
   - nano mouse-control.json
3. Paste the contents in the repo into the nano text editor
4. Save and exit nano editor ('CTRL+ x', 'y', 'ENTER')
5. Enter Karabiner-Elements, navigate to "Complex Modifications" > "Add pre-defined-rule"
6. Under "Toggle mouse mode with Right Shift + WASD/RF/QE for control, click "Enable All"
7. The json should work as intended

Should you want to:
1. Modify the mouse speed: modify x and y values in json file. The mouse speed is temporarily set to 2000/-2000
2. Modify the scroll speed: modify vertical wheel in json file. The scroll speed is currently set to 32
3. Modify the toggle button: Under manipulators, modify "key_code" to your desired button
   - Do take note that you currently have to hold the right shift when using the mouse (it is not toggle)
