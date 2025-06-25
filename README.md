# KiCAD Tools

# Templates

To check where user templates are stored:
- Open KiCAD
- Navigate to Preferences - Configure Paths

![image](https://github.com/user-attachments/assets/3f2e05c1-8fe5-4eaf-a2c1-ee2d19f9c952)
- You can change the highlighted directory to a directory of your choice, or use the default directory.

Template requirements:
- To create your own template, start a new project and save it to KICAD_USER_TEMPLATE_DIR
- In the project file create a new folder called "meta"
    - In the meta folder, you must include a file called "info.html".
    - You may also include an icon, which must be saved and stored in the meta folder as "icon.png" (64x64 resolution recommended).
 

# Logo Footprint Library

The Logos.pretty folder has the UCT, ARU, and MaRiS logos in various sizess. To add a footprint library:
- Open KiCAD
- Navigate to Preferences - Manage Footprint Libraries
- Click the plus in the bottom left to add a new row to the table and fill in the information accordingly.
