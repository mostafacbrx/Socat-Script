Socat-Script
IPv6 Socat Tunnel using Script
You can easily use this script by copying the following command:

```bash
bash <(curl -Ls https://raw.githubusercontent.com/Mehdi682007/Socat-Script/main/setup-socat.sh)

```
## To install, select option 1 and follow the steps.
The first thing you'll be asked is to enter the number of ports you want to tunnel. For example, if you want to tunnel two ports, enter the number 2.

Next, you'll be prompted to enter the port number, for example, port 443. After pressing Enter, you'll be asked to provide the IPv6 address of the external server. Enter the external IPv6 address. If you selected two ports, you'll be asked again to enter another port and its corresponding external IPv6 address. You can even use two different external servers with one Iranian server.

The installation process will then proceed, and you will be asked if you want to reboot the server. Type y to reboot. After the reboot, you can check the script again, and if the status shows "Status: Running" in green, it means the tunnel has been successfully set up and you can use it.

I will soon add more options and tunneling methods to the script. A video tutorial on how to install this tunnel will be provided below so you can follow along.

## To uninstall, simply select option 2 and confirm by typing yes to completely remove the script from the server.