📄 DRIVE MAPPING POLICY SETUP (GPO)

Open Group Policy Management (gpmc.msc)

Right-click the domain or OU where you want to apply the mapping

Click "Create a GPO in this domain, and Link it here..."

Name the GPO: Drive Mapping Policy

Right-click the new GPO and select Edit

In the Group Policy Management Editor, go to:

User Configuration  
└── Preferences  
    └── Windows Settings  
        └── Drive Maps
Right-click Drive Maps > New > Mapped Drive

In the New Drive Properties window:

Action: Create

Location:


\\YourServerName\SharedFolder
Drive Letter: Choose one (E)

Click OK to save

Close the editor