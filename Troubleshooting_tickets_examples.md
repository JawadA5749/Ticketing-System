# Troubleshooting IT Helpdesk Ticket Scenarios 

## Use Spiceworks or Jira to generate the tickets. Make sure to get approval by the Manager alwasys before working on the tickets. 

### Scenario 1:
- I’m a new admin assistant that started today. I need calendar, contact access to Kevin calendar. I will need to scan business cards and import them into his contacts. Please provide access asap.

#### How to handle:
- For this ticket, go to Outlook. Then go to account settings after clicking on File. From there, click on Delegate access. Add the right person and make sure to only delegate access to Calendar and Contacts. Click on Ok and it's done.

### Scenario 2:
- I accidentally deleted a file from the share drive. Can you restore it?

#### How to handle:
- For this ticket, go to the shared folder's properties (the folder where the file got deleted from). Then go to Previous Versions. From there, you can open up the file directory and add it back.

### Scenario 3:
- I need to run Macabacus on excel but it requires admin rights. Can you please install it?

#### How to handle:
- For this ticket, simply download and install Macabacus. Make sure to download the correct version. Go to 'About Excel' to find what version you need. Once it's installed, Excel should automatically load Macabacus once it's opened.

### Scenario 4:
- I’m a software developer that just started today. I need admin rights on my computer. Can you grant me admin rights?

#### How to handle:
- In the search bar look for Computer Management. Go to the file location first. Now, hold Shift and then right-click on Computer Management. Enter your admin credentials. Then go to Local Users and Groups. From there, go to Groups and double click on Administrators. Then add the person in the group.

 ### Scenario 5:
 - I have a meeting tomorrow. Can you install zoom on my computer?

#### How to handle:
- For this ticket, simply download and install zoom. Once the zoom installer is downloaded, click on 'Run as different user' and enter your admin credentials.

 ### Scenario 6:
 - Good Morning. Every time I open a pdf file it opens up on edge. I need to open this up on Adobe Acrobat. Thanks.

#### How to handle:
- Download Adobe Acrobat reader from google (or use deployment apps to deploy the app). After downloading it, simply open the pdf file with Adobe Acrobat.

 ### Scenario 7:
- Good Morning. I just started today and I need Adobe Creative Cloud on my machine. Can you install adobe creative cloud on my machine? Thanks.

#### How to handle:
- Simply download Adobe Creative Cloud from google, and then install it as admin.

 ### Scenario 8:
 - Good Morning. Can you convert my pdf file into a word document? Thanks.

#### How to handle:
- Right-click on the pdf file and choose to open with Word. Another way to do that is through Adobe. Open the file in Adobe, and go to File. Then click on 'Save as'. Choose a folder and then in the 'Save as type' option, choose Word. Then save the file.

### Scenario 9:
- My adobe keeps crashing and won’t open any pdf files. Fatal Error: Acrobat Failed to connect to a DDE server. 

#### How to handle:
- This might happen if a file is clicked on too many times. If this happens, close the Adobe Acrobat from the Task Manager by clicking on End Task. Then reopen the file.
- Another probable error is the Runtime error. This means Runtime may need to be repaired or installed. Click on 'Help' in Adobe and choose 'Repair Installation' or look up 'c++ runtime download' and download it.

### Scenario 10:
- Good Morning. I work for the fashion department. Adobe keeps crashing and it won’t let me uninstall it. Thanks.

#### How to handle:
- If simply uninstalling doesn't work, look up 'creative cloud uninstaller' on google. Run the app after downloading it. This will uninstall all the apps that work with creative cloud. Creative Cloud should be gone now. Reinstall the application if needed.

### Scenario 11:
- Good Afternoon. Can someone remove Adobe Acrobat and focused inbox from my outlook?

#### How to handle:
- To remove focused inbox, simply click on View on Outlook and uncheck 'Show Focused Inbox'. To remove Adobe Acrobat, go to File, then Options. Then click on Add-ins. Click on 'Go', and from there, uncheck Adobe Acrobat. That should remove it.

### Scenario 12:
- Good Morning. I have to keep installing stuff on my machine. I got approval for full admin rights. Can you give me admin rights to my computer? Also, can you add me to remote user so I can remote into my machine?

#### How to handle:
- Go to File Explorer. Then right-click on 'This PC' and click on Properties. Go to 'Advanced system settings'. Click on Remote. Check the 'Allow remote connections to this computer' option and then in 'Select users', you can add the person to it.
- Go to Computer Management and click on Local Users and Groups. Then go to Groups. From there, double-click on the Administrators group and add the person to the group. 'Remote Desktop Users' group should be in the same place. Double-click on it and add the person to it as well. 

### Scenario 13:
- Good Morning. I need to do trading today and I noticed I’m missing Bloomberg and the add in on excel. Can you install it for me?

#### How to handle:
- Download Bloomberg first. Then install it. Install Bloomberg office Add-ins next. After that Bloomberg should be visible when Excel is opened.

### Scenario 14:
- Good Morning. It’s me again. Can you please install anaconda on my machine?

#### How to handle:
- Simply download and install Anaconda from google.

### Scenario 14:
- Good Morning. I’m a software developer and I need to sql on my machine in order to run database services. 

#### How to handle:
- Download and install SQL studio from google. The software developer can connect to server from there once the installation is done.

### Scenario 15:
- Good Morning. I can’t login to my computer. It says “The trust relationship between this workstation and the primary domain failed.”

#### How to handle:
- In this case the computer has fallen off the domain. Check the AD users and computers. The computer is not listed there.
- Log into the computer that is off the domain as local admin. Type in ".\administrator" in the username field.
- Once logged in, go to the file explorer and right click on "This PC". Select 'properties' and then click on 'change settings'. In the 'Computer Name/Domain Changes' window, put the computer in a Workgroup. The computer should restart after that.
- Once it reboots, readd it back to the domain that it was in before. It will restart one more time, and after that, the computer should show up in the AD users and computers.  

### Scenario 16:

#### How to handle:

