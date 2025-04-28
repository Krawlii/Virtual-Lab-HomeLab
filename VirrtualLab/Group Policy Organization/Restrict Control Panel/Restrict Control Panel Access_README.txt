📄 RESTRICT CONTROL PANEL ACCESS (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain or OU where you want to restrict Control Panel

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Restrict Control Panel Access

Right-click the new GPO and select Edit

In the Group Policy Management Editor, navigate to:


User Configuration  
└── Policies  
    └── Administrative Templates  
        └── Control Panel
Double-click "Prohibit access to Control Panel and PC settings"

Set it to Enabled

Click Apply then OK

Close the editor