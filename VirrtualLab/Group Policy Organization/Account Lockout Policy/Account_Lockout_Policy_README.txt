 ACCOUNT LOCKOUT POLICY SETUP (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain or specific OU you want to apply the policy to

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Account Lockout Policy

Right-click the new GPO and select Edit

In the Group Policy Management Editor, navigate to:


Computer Configuration  
└── Policies  
    └── Windows Settings  
        └── Security Settings  
            └── Account Policies  
                └── Account Lockout Policy

Configure the following settings:

Account lockout threshold → Set to 5

Account lockout duration → Set to 30 minutes

Reset account lockout counter after → Set to 15 minutes

Close the editor.