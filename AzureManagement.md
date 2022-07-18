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

The Azure CLI is available to install in Windows, macOS and Linux environments. It can also be run in a Docker container and Azure Cloud Shell.

<h3> Task 3: Install Tools</h3
The current version of the Azure CLI is 2.38.0. For information about the latest release, see the release notes. To find your installed version and see if you need to update, run az version.

Install Azure CLI: 
[Install on Windows](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows)
 
[Install on macOS](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos)

Download and install VS Code
[VS Code](https://code.visualstudio.com/download)
 
Open Terminal
 ```
CTRL+SHIFT+`
 ```
 
Run the login command.
 
```
az login
```

If the CLI can open your default browser, it will initiate authorization code flow and open the default browser to load an Azure sign-in page.
Sign in with your account credentials in the browser.

<h3>Task 4: Finding commands</h3>

Azure CLI commands are organized as commands of groups. Each group represents an Azure service, and commands operate on that service.
To search for commands, use az find. For example, to search for command names containing secret, use the following command:

```
az find secret
```
 
Use the --help argument to get a complete list of commands and subgroups of a group. For example, to find the CLI commands for working with Network Security Groups (NSGs):

```
az network nsg --help
```

Interactive mode

The CLI offers an interactive mode that automatically displays help information and makes it easier to select subcommands. You enter interactive mode with the az interactive command.

```
az interactive
```
 
<h3>Task 5: Managing subscriptions using Azure CLI</h3 
Change the active tenant
To switch tenants, you need to sign in as a user within the desired tenant. Use az login to change the active tenant and update the subscription list to which you belong.

```
# sign in with a different tenant
 
az login --tenant <myTenantID>
```
 
Change the active subscription
 ```
 # change the active subscription using the subscription name
az account set --subscription "<name>"

# change the active subscription using the subscription ID
az account set --subscription "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"

# change the active subscription using a variable
subscriptionId="$(az account list --query "[?isDefault].id" -o tsv)"
az account set --subscription $subscriptionId
 ```
 
<h3>Task 6: Managing resource Groups using Azure CLI</h3 
 
