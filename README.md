# Windows11
This is how you can activate Windows 11 in a new PC.
  
1) Identify your Windows 11 Edition.
   After identifying your current Windows 11 edition , pick the corresponding key from this list.
   > Home: TX9XD-98N7V-6WMQ6-BX7FG-H8Q99  
   > Pro: W269N-WFGWX-YVC9B-4J6C9-T83GX  
   > Education: NW6C2-QMPVW-D7KKK-3GKT6-VCFB2  
   > Enterprise: NPPR9-FWDCX-D2C8J-H872K-2YT43  
    
2) Run Command Prompt app as administrator.

   
3) Install KMS client key by typing this commmand: ***slmgr /ipk LicenseKey***
   ```
   slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
   ```
     
4) Change your KMS server to this one :
   ```
   slmgr /skms kms8.msguides.com
   ```
     
5) You are done , this is the last command:
   ```
   slmgr /ato
   ```
  
This should be enough to activate your Windows version Lifetime till the Key Management Server is down or dead (wont happen).
