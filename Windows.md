# Windows Privilege Escalation
## Initial Enumeration
# 1. System Enumeration
i) systeminfo --> Shows all the information

ii) systeminfo | findstr /B /C:"OS Name" /C:"OS Version" /C:"System Type" --> More specific

iii) wmic qfe --> Patches installed

iv) wmic logicaldisk  --> Disk Attached
    
|-wmic logicaldisk get caption,description,providername --> More specific
