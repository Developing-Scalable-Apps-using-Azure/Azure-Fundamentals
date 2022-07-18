<h1> Azure Management using PowerShell and Azure CLI</h1>
 
<h3>Task 1: Use the PowerShell CLI</h3>
Launch the cloud shell from the Azure Portal
<img width="1303" alt="image" src="https://user-images.githubusercontent.com/11691661/179504416-f2175247-d747-491c-88e2-2723ede65d35.png">

Half the screen will be in PowerShell command line interface (CLI) mode. If you’re familiar with PowerShell, you can manage your Azure environment using PowerShell commands.

<img width="1440" alt="image" src="https://user-images.githubusercontent.com/11691661/179504508-50d24e73-d824-48d6-957d-e740dfce3eb5.png">

```
**Tip**
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

<h3>Task 2: Use the BASH CLI</h3>
If you’re more familiar with BASH, you can use BASH command instead by shifting to the BASH CLI.

Enter bash to switch to the BASH CLI.

```
bash
```

```
**Tip**
You can tell you're in BASH mode by the username displayed on the command line. It will be your username@azure.
```

Again, use the Get-date command to get the current date and time.

```
Get-date
```

You received an error because Get-date is a PowerShell specific command.

Screenshot of BASH error message get-date command not found.
<img width="1440" alt="image" src="https://user-images.githubusercontent.com/11691661/179505428-d8c0d1f1-f818-4db4-b25a-3fd3e4f9b0f8.png">Use the date command to get the current date and time.

```
date
```



