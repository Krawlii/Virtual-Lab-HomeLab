📄 DESKTOP WALLPAPER POLICY SETUP (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain or OU where you want to apply it

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Desktop Wallpaper Policy

Right-click the new GPO and select Edit

In the Group Policy Management Editor, go to:


User Configuration  
└── Policies  
    └── Administrative Templates  
        └── Desktop  
            └── Desktop
Double-click "Desktop Wallpaper" on the right pane

Set to Enabled

In the Wallpaper Name field, enter the full UNC path to the wallpaper file
Example:


\\YourServerName\SharedFolder\wallpaper.jpg
Set Wallpaper Style to one of the following:

Fill

Fit

Stretch

Tile

Center

Click Apply, then OK

Close the editor