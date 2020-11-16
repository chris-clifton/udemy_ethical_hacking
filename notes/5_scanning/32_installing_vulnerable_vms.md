# Installing Vulnerable Virtual Machines
Metasploitable: https://sourceforge.net/projects/metasploitable/

- Download the VM
- Unzip it
- Create a new VM in VirtualBox
  - name Metasploitable or similar
  - 512MB Ram is plenty
  - Use existing hard disk, click the 'open' icon, find the `Metasploitable.vmdk` file and choose that
  - Once the VM is created, go to the VM settings, go to Network, change the type to 'Bridged Adapter', choose your network
- Start the VM
  - Click 'view' and choose 'Scaled Mode'
    - This is a command line VM with no GUI so we don't really care about full screen but the default is too tiny to even login on
  - Login with user 'msfadmin' and password 'msfadmin' (check docs if that doesn't work)
  - Run `ifconfig` and check a network connection
- We are now all set!
