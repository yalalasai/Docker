# Docker
This documents helps you for the installatoin of Docker on any Windows VM 
Step 1:
  Install Docker on the VM as you do on Local Machine
Step 2:
  Open powershell and Enter the following Commands anywhere
  #Ensure Windows Hyper-V featutes are enabled by running PowerShell cmdlet:
  Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All -Verbose

  #Ensure Windows Containers feature is enabled by running PowerShell cmdlet:
  Enable-WindowsOptionalFeature -Online -FeatureName Containers -All -Verbose
Step 3:
  Open Commandprompt with admin privilages and enter the following command from anywhere
  #Ensure Hypervisor is set to auto start in the Boot Configuration Database (BCD) by running in elevated command prompt the command:
  bcdedit /set hypervisorlaunchtype Auto
