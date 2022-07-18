<h1> Azure Management using PowerShell and Azure CLI</h1>
 
Task 1: Use the PowerShell CLI
Launch the cloud shell from the Azure Portal
<img width="1303" alt="image" src="https://user-images.githubusercontent.com/11691661/179504416-f2175247-d747-491c-88e2-2723ede65d35.png">

Half the screen will be in PowerShell command line interface (CLI) mode. If you’re familiar with PowerShell, you can manage your Azure environment using PowerShell commands.

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/11691661/179504508-50d24e73-d824-48d6-957d-e740dfce3eb5.png">
```
Tip
You can tell you're in PowerShell mode by the PS before your directory on the command line.
```
Use the PowerShell Get-date command to get the current date and time.
```
Get-date
```
Most Azure specific commands will start with the letters az. The Get-date command you just ran is a PowerShell specific command. Let's try an Azure command to check what version of the CLI you're using right now.
```
az version
```

