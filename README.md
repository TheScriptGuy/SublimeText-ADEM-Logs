# Autonomous Digital Experience Management
Enables log formatting to apply to both the endpoint DEM and ION DEM log files.

## Syntax Highlighting
* Version: 0.03
* Last Modified: 2024/05/24


# Requirements
## MacOS
1. Access to `~/Library/Application Support/Sublime Text/Packages/`
(This folder is hidden, use the Finder Menu --> Go Menu --> Go To Folder to access)

2. You need to copy the `*.sublime-syntax` files into the respective folder above.

3. Next time you open a `palo_alto_networks_dem_agent.log` or `palo_alto_networks_dem_agent.1.log` file, it should do the syntax highlighting for you.

4. If it doesn't set the syntax correctly, `⌘ + ⇧ + P` will open the Command Palette.

5. Type: 
* `Set Syntax: Palo Alto Networks ADEM Logs` for ADEM endpoint log file format. 
* `Set Syntax: Palo Alto Networks ION ADEM Logs` for ION ADEM endpoint log file format

## Windows

1. Access to `%APPDATA%\Sublime Text 3\Packages\`
2. Create a directory `Palo Alto Networks`
3. You need to copy the `PaloAltoNetworksADEM.sublime-syntax` file into the newly created folder above.
4. Next time you open a `palo_alto_networks_dem_agent.log` or `palo_alto_networks_dem_agent.1.log` file, it should do the syntax highlighting for you.

5. If it doesn't set the syntax correctly, `Ctrl + Shift + P` will open the Command Palette.

6. Type: 
* `Set Syntax: Palo Alto Networks ADEM Logs` for ADEM endpoint log file format. 
* `Set Syntax: Palo Alto Networks ION ADEM Logs` for ION ADEM endpoint log file format
