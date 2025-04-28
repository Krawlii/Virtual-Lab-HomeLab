📄 PASSWORD POLICY SETUP (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain (not an OU)

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Password Policy

Right-click the new GPO and select Edit

In the Group Policy Management Editor, navigate to:


Computer Configuration  
└── Policies  
    └── Windows Settings  
        └── Security Settings  
            └── Account Policies  
                └── Password Policy
Configure the following settings:

Maximum password age → 90 days

Minimum password age → 31 day

Minimum password length → 12 characters

Password must meet complexity requirements → Enabled



Close the editor.