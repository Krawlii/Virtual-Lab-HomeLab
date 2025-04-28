📄 DISABLE USB DEVICES (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain or OU where you want to apply it

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Disable USB Devices

Right-click the new GPO and select Edit

In the Group Policy Management Editor, go to:


Computer Configuration  
└── Policies  
    └── Administrative Templates  
        └── System  
            └── Removable Storage Access
On the right side, double-click "All Removable Storage classes: Deny all access"

Set it to Enabled

Click Apply, then OK

Close the editor