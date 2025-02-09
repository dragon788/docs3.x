# APPLICATIONS


## Plug-ins

**Plug-ins** allows you to manage OpenWrt packages. You can install or remove any package. 

Remember to click `Update` whenever you access this packages repository.

![Plug ins](https://static.gl-inet.com/docs/en/3/setup/gl-mt1300/Plug_ins.jpg){class="glboxshadow"} 



---

## File Sharing

You can use an external USB storage or a MicroSD card with GL.iNet router. The file sharing features of the external storage device can be configured in **File Sharing**.

**Share via LAN**: Share the contents of the external storage device with all connected clients.

**Share via WAN**: The contents of the external storage device can be accessed from the WAN.

**Writable**: The contents of the external storage device/TF card can be edited.

**Current Directory**: You can select one directory from the root of external storage to mount and share on GL-Samba folder. 

![File sharing](https://static.gl-inet.com/docs/en/3/setup/gl-mt1300/File_sharing.jpg){class="glboxshadow"} 



For guidance on how to access the contents of the external storage device from your computer or smart phone, please refer to [file sharing](../../../tutorials/file_sharing/).


---

## Remote Access


### Cloud

**GL.iNet GoodCloud cloud management** services provide an easy and simple way to remotely manage routers. 

In our website, you can remotely check your router status, change the password, control clients, even set email alarm when a device is online or offline.

This is a default function for version 3.021 or above. Older versions require manual install using Plug-ins.

![Cloud](https://static.gl-inet.com/docs/en/3/setup/gl-ar750s/applications/cloud.png){class="glboxshadow"}


For the details, please refer to [Cloud](../../../tutorials/cloud/).

### DDNS

_**DDNS**_ (Dynamic Domain Name Service) is a service used to map a domain name to the dynamic IP address of a network device. 

You can remotely access your router with a url though this function. Example: myRouterDeviceID.glddns.com

This is a default function for version 3.021 or above. Older versions require manual install using Plug-ins.


![Remote Access](https://static.gl-inet.com/docs/en/3/setup/gl-mt1300/Remote_Access.jpg){class="glboxshadow"}


For guidance on how to set DDNS and access, please refer to [DDNS](../../../tutorials/ddns/).

---

## Captive Portal

You can set a _**captive portal**_ in our routers, when newly users connect to wifi, they need to access a web page before access the internet.

Only supported in version 3.022 or above.

![Portal](https://static.gl-inet.com/docs/en/3/setup/gl-mt1300/Captive_Portal.jpg){class="glboxshadow"}


For guidance on how to set this up, please refer to [Set a Captive portal](../../../tutorials/captive_portal).


## IGMP Snooping

You can enable _**IGMP snooping**_ to use the multicast functions on the router. 

_**IGMP Snooping**_ listens to the IGMP protocol package, extracts the corresponding information, establishes and maintains the layer 2 multicast forwarding publication, and then forwards the multicast group data to the host that joins the multicast group, while other hosts cannot receive the multicast group data.

_**IGMP V3**_ is compatible with _**v1**_ and _**v2**_, you can try _**v3**_ first and change it if you find any problem. 


![IGMP Snooping](https://static.gl-inet.com/docs/en/3/setup/gl-mt1300/IGMP_Snooping.jpg){class="glboxshadow"}