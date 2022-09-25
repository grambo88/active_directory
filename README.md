# 00 - Install VMs


1. Installed Windows Server 2022 as a Virtual machine on VMWare Workstation
2. Installed Windows 11 as a Virtual machine on VMWare Workstation


# 01 - Install the Domain Controller


1. Use 'scconfig' to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to our own IP address

2. Install the Active Diretory Windows Feature

...shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
...