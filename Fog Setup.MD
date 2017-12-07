# FOG SETUP
1. Install ubuntu with default settings
2. Setup IP address
3. Download FOG 
4. Run below commands
```
tar -xzvf fog_x.x.x.tar.gz
cd fog_x.x.x/bin
sudo ./install.sh
```
5. Install with default settings
  - What type of installation would you like to do? [N/s (Normal/Storage)]
    - Choose: N
  - What is the IP address to be used by this FOG Server? [TheIpYouSetUpEarlier]
    - Confirm with Enter
  - Would you like to change the default network interface from [YourNetworkInterfaceName]?
    - Choose: N
  - Would you like to setup a router address for the DHCP Server? [Y/n]
    - Choose: Y and enter the IP Address of your Router / DHCP Server
  - Would you like DHCP to handle DNS?
    - Choose: Y
  - What DNS address should DHCP allow? [IP of your Router or DNS Server you use]
    - Confirm with Enter or Change the IP Accordingly
  - Would you like to use the FOG Server for DHCP Service? [y/N]
    - Choose: N
  - This version of FOG has internationalization support, would you like to install the additional language packs? [y/N]
    - Choose: N, or Yes if you need it.
  - Are you sure you wish to continue (Y/N)
    - Check if everything is correct and confirm with Y
