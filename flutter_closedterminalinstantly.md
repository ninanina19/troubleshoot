**The Problem is**

I already install flutter on directory `C:\flutter` and setup my environment path. I got issue when running command `flutter doctor` in flutter_console. The terminal instantly closed.
But, It was work when I running command `flutter doctor` on cmd as administrator.  

**How do I solve this problem?**
1. Add this following to variable PATH
   - `C:\Windows\System32\WindowsPowerShell\v1.0`
   - `C:\Program Files\Git\bin`
   - `C:\Program Files\Git\cmd`
   - `C:\Windows\System32`
   - `C:\flutter\bin`
  OR
2. Check PowerShell version. Flutter required Windows Powershell 5.0 or newer. To check the version of PowerShell you are using on Windows 10;
   - open a PowerShell window,
   - enter `$PSVersionTable` into the prompt

But, still didn't work for me and I decided to reinstall flutter. 

**How do I reinstall flutter?**
1. Unistall dart and flutter in **Android Studio**
   - Open Android Studio
   - Go to File => Settings => Plugins
   - In search bar, type dart and klik *Unistall* button
   - After unistall dart, type flutter in search bar and klik *Uinstall* button
   - Closed settings window and android studio
2. Unistall dart and flutter in **Visual Studio Code**
   - Open VSCode
   - Go to Extensions
   - In search bar, type dart and klik *Unistall* button
   - Then type flutter in search bar and klik *Uinstall* button
3. Delete flutter file on C that I already installed
4. Delete `C:\flutter\bin` in variable PATH
5. Restart My PC

**Install Flutter for the second time**

I was following this video to install flutter, [Setup Flutter in Visual Studio Code](https://docs.flutter.dev/get-started/install/windows) and also [flutter documentation](https://docs.flutter.dev/get-started/install) for preference. 

**Problem solved!!!**
