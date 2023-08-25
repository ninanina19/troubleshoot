# Uinstall MySql Workbench Completely
1. Goto **Program and Features**
   - Press `windows + R`
   - Type `appwiz.cpl`
   - Press `Enter` or click `OK` button
2. In **Program and Features** dialog box, scroll down and found MySQL. Unistall all of MySQL program. Select and right click to unistall.
4. Goto **C:\Program Files** and delete folder **MySQl**
5. Goto **C:\Users\<your user>\AppData\Roaming** then delete **MySQL** folder.

   **Note:** If you didn't found **AppData** folder, just click **view** tab on the diaolog box and check the **Hidden items**
6. Goto **C:\ProgramData** and delete folder **MySQL**
7. Goto **Environment Variables** dialog box to delete MySQL on path
   - press `windows + R`
   - type `rundll32.exe sysdm.cpl,EditEnvironmentVariables`
     - in **User variables for user**, select **Path** and clik button `Edit`
       - select `C:\ProgramData\MySQL\bin` and click button `Delete` on the right side
       - click button `OK`
     - in **System variables**, select **Path** and clik button `Edit`
       - select `C:\ProgramData\MySQL\bin` and click button `Delete` on the right side
       - click button `OK`
     - Click button `OK` to complete with path

### Congrats! You have done delete MySQL Workbench completely.

Reference: https://www.youtube.com/watch?v=IC7jmI4F_Ww
  
