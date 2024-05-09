# ElvUI-Update-Script
## Steps to use:
1. Edit the config.ini file:
  - Download_Path = Where should ElvUI gets downloaded
  - WoW_Path = Your \Interface\AddOns folder
2. Create an Virtual Environment with the needed packages:
  - ```
    python -m venv env
    pip install -r requirements.txt
    ```
3. Access the Virtual Environment:
   Run the Activate batch or powershell file in /env/Scripts/
5. Run the Script:
   ```
   python pyelvui.py
   ```

I've written a small batch file which activates the Virtual Environment and starts the script. 
You could add this batch file in the Windows Task Scheduler
