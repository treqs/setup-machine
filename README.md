# Setup Machine

> Configure Your Machine for data analytics and software development

## Task 1: Turn on Developer Settings

1. In Windows go to Settings / Update & Security / For Developers. 
1. Scroll down to "File Explorer". Grey checks are enabled, blue checks are not yet enabled. Verify the following settings are checked:
    - "Change settings to show file extensions"
    - "Change settings to show hidden and system files"
    - "Change settings to show full path in title bar" 
1. Click "Apply". Verify the above settings now have grey checks.
1. Scroll down to "PowerShell". Verify the following option is checked.
    - "Change execution policy to allow local PowerShell scripts to run without signing. Require signing for remote scripts."
1. Click "Apply". Check should now be grey.

## Learn about PowerShell

PowerShell allows us to type commands affecting our computer.
It allows us to create new files and folders, install programs, run programs, and more.

## PowerShell Privileges

By default, Windows will launch PowerShell without administrator privileges.
However, when using PowerShell to perform advanced functions such as installations,
you will need Admin priviledges which allow you to create, delete, and modify settings
and items such as files, folders, and environment variables.
PowerShell is often used with software development projects.

## Task 2: Add "Open PowerShell window here as administrator"

Windows File Explorer provides a context menu when you right-click inside a folder.
Open File Explorer, go to "My Documents" and try it.
We want to add an item to this context menu so that when we click in a working folder, we can open a PowerShell Admin window here - ready to execute commands in this specific location on our machine.

First, read [How to Add "Open PowerShell window here as administrator" context menu in Windows 10](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html)

Then, update your folder context menu:

1. Scroll down on the page linked above. 
2. Go to Step 2 and click Download.
3. Follow Steps 5-9.

Finally, verify. Open File Explorer, go to "Documents" and right-click on a folder. You should see the option to "Open PowerShell here as administrator". 

---

## Know These Terms

- Operating system - Software that provides a computer's most basic functions such as connecting devices and executing applications.  Popular operating systems are:
    - Windows
    - MacOS
    - Linux
- User - A person with account on a machine that allows access to authorized resources through the operating system.
- Administrator - A user with elevated permissions including create, delete, and modify settings and items.
- Command Line Interface (CLI) - A mode of interacting with a computer where commands are typed and the result is displayed as text.
- Graphical User Interface (GUI) - A mode of interacting with a computer where the user interacts with a 2-D window by using a pointing device and clicking to trigger operations. Windows often have a menu bar accross the top for easy access to common operations. In many cases, operations will need to use text to specify input for the operation.  The result can be a mix of graphics and text.
- Context menu - A pop-up menu, typically avaiable when right-clicking on an item in a window.
- Power Shell - A powerful CLI for Windows.
- Windows File Explorer - A program that uses a GUI to allow a user to browse their computers file systems.
File system - A heirachical way of organizing files that is based on directories (folders) that contain files and sub-directories.  The top of the file system is root.
- File name - The complete name + extension of the file OR the part that comes before the . and extension.
- File extension - The part at the end of the file that indicates its type (e.g. doc, xls, md, html).
- Hidden files - Files not displayed to typical users. Typically, their name starts with a period.
- System files - Files used by operating system that should not be modified by users.


## Next Steps

- See [Windows File Management](https://github.com/denisecase/windows-file-management)
- See [Get Setup With Chocolatey](https://github.com/denisecase/get-setup-with-chocolatey)

## See Also

- [Setting Up for Professional Software Development](https://github.com/denisecase/pro-dev-list)
