# MORE SETTINGS

## Admin Password

Change the password of the web Admin Panel, which must be at least 5 characters. You have to input your current password in order to change it.

![admin password](https://static.gl-inet.com/docs/en/3/setup/gl-mv1000/more_settings/admin_password.png){class="glboxshadow"}

---

## LAN IP

LAN IP is the IP address that you use to connect to this router. The default IP address of GL.iNet router is 192.168.8.1. If it conflicts with the IP address of your main router, you can change it.

![lan ip](https://static.gl-inet.com/docs/en/3/setup/gl-mv1000/more_settings/lan_ip.png){class="glboxshadow"}

---

## Time Zone

The time of the router's activities will be recorded according to the router time. Therefore, choosing the time zone of your location is recommended.

![time zone](https://static.gl-inet.com/docs/en/3/setup/gl-mv1000/more_settings/time_zone.png){class="glboxshadow"}

---

## Custom DNS Server

You can configure the DNS server of the router in order to prevent DNS leak or other purposes.

**DNS Rebinding Attack Protection**: Some network may require authentication in captive portal. Disable this option if the captive portal of your network cannot be resolved.

**Override DNS Settings for All Clients**: Enabling this option will capture DNS request from all connected clients.

**DNS over TLS from Cloudflare**: Cloudflare DNS over TLS uses the TLS security protocol for encrypting DNS queries, which helps increase privacy and prevent eavesdropping.

**Manual DNS Server Settings**: Input a custom DNS server manually.

![custom dns server](https://static.gl-inet.com/docs/en/3/setup/gl-mv1000/more_settings/custom_dns.png){class="glboxshadow"}

---

## Button Settings

Configure the function of the mode switch. It doesn't have any function by default. You can set it as a toggle to turn on or off WireGuard/OpenVPN client or Power saving mode.

![button settings](https://static.gl-inet.com/docs/en/3/setup/gl-e750/more_settings/button_setting.png){class="glboxshadow"}

---

## MCU Settings

Configure the contents displayed on OLED including **main screen**, **WiFi infomation**, **LAN IP**, **VPN information** and **cutomized contents**. You just enable or disable the display contents and click ***Apply***. 

**Show the WIFI password**: Whether or not to show the WI-FI password in the OLED.

**Show the main screen**：Whether or not to show the first (main) screen.

**Show the 2.4G WIFI info**：Whether or not to show the second (2.4G WIFI info) screen.

**Show the 5G WIFI info**：Whether or not to show the second (5G WIFI info) screen.

**Show the LAN IP**：Whether or not to show the forth (LAN IP info) screen.

**Show the VPN info**：Whether or not to show the forth (LAN IP info) screen.

**Show customized**：The content of the user customized screen.

![MCU settings](https://static.gl-inet.com/docs/en/3/setup/gl-e750/more_settings/MCUsetting.jpg){class="glboxshadow"}

---
## Network Mode

Change the network mode to cater your usage scenario. You may need to reconnect your client device whenever you change the network mode of the router.

Be aware that you may not be able to access the web Admin Panel with the default IP 192.168.8.1 if you use the router in **Access Point**, **Extender** or **WDS** mode. If you want to access the web Admin Panel in this case, you have to use the IP address assigned by the main router to the GL.iNet router.

**Router**: Create your own private network. The router will act as NAT, firewall and DHCP server.

**Bridge mode**: Bridge to a wired network.

![network mode](https://static.gl-inet.com/docs/en/3/setup/mini_router/more_settings/network_mode.jpg){class="glboxshadow"}

---

## Revert Firmware

Revert the router to factory default settings. All your settings, applications and data will be erased.

![revert firmware](https://static.gl-inet.com/docs/en/3/setup/gl-mv1000/more_settings/revert_firmware.png){class="glboxshadow"}

---

## Advanced

If you can not find Advanced menu item, please follow the steps to install it.

![how to instlal luci](https://static.gl-inet.com/docs/en/3/setup/gl-e750/more_settings/how_to_install_luci.png){class="glboxshadow"}

After it install successfully, you will find the Advanced menu item.

Click `Advanced` to direct to LuCI which is the default web interface of OpenWrt. You can check the detailed system log or conduct more advanced configurations there.

![advanced](https://static.gl-inet.com/docs/en/3/setup/gl-e750/more_settings/luci.png){class="glboxshadow"}

*Note: The username is **root**. The password is same as the one that you use to access the web Admin Panel.*