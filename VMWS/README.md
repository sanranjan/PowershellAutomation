# Setup VMware Workstation RestAPI


## Run VMware RestAPI

First configure users details on VMware Workstartion using below command.

`vmrest.exe -C`

When propted, enter user name and password for the configuration

Once configuration completes, Start RestAPI using below command.

`vmrest.exe -i 192.168.1.2 -c host.crt -k host.key`

Change the IP, host certificate and host private key.
This will start the REST API for VMware workstation which can we reached at 
`https://192.168.1.2:8697`  Change IP as per your environment setup.
