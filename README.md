#Install Any Linux Distro On Windows Using Windows Subsystem for Linux (WSL):

-Go To Windows Search.

-Type Programs and select Programs & Feature.

-Click on Turn Windows Feature On and Off.

-Select Windows Subsystem for Linux and restart your machine.

-Type either Command Prompt or Windows Powershell and run as administrator.

-In the administrator view, type `wsl --install`

-Type `wsl --install -d <Linux_Distro>`

-Installation may take few minutes. 
After installation, set your UNIX username and password (blind typing).

Update/Upgrade packages and software by typing this command `sudo apt update && sudo apt upgrade`.

[Follow this documentation for more information](https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-username-and-password)

[Top 50 Linux Commands A Regular User Should Know](https://www.digitalocean.com/community/tutorials/linux-commands)
