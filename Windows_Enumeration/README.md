BE AWARE THAT THIS EXECUTABLE MAY TAKE A LONG TIME TO RUN
=================================================================================

This Executable will gather information about the following:

     Alternate Data Streams
     Address Resolution Protocol Cache
     Audit Policy
     Current Processes
     Current Services
     Domain Name Service Cache
     ETC Hosts
     Event Logs
     Files
     HK(CU/LM/U) Run Key
     Local Groups
     Local Users
     Network Connected Processes
     Network Statistics
     Prefetch Files
     Scheduled Tasks
     Server Message Block Shares
     Trusted Windows Remote Management Clients

The information that it gathers will be placed in "C:\Investigation". 

Be aware that this will remove a folder called "Investigation" if there is one located at "C:\Investigation".

This was tested with systems that have PowerShell 5.1 installed on Windows 10. Other versions may result in items not being collected.

![Screen_Capture](https://user-images.githubusercontent.com/69497564/169200967-e63d4ef4-58a1-4d2b-822a-50a0182c2a8a.png)
