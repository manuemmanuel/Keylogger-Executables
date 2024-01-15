# Run at Startup
1. Registry Editor:
2. Press Win + R to open the Run dialog.
3. Type regedit and press Enter to open the Registry Editor.
4. Navigate to Startup Key:
5. Go to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run.
6. Create a New String Value:
7. Right-click on the right pane, select New, and choose String Value.
8. Set the name of the new string value to something descriptive, e.g., "MyApp".
9. Double-click on the new entry, and in the "Value data" field, provide the full path to your executable (including the executable name).
10. Confirm:

11. Close the Registry Editor.
The next time you log in, your executable should run automatically.
