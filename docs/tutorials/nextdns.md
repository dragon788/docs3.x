# NextDNS

If you are using GL.iNet routers, you will find that DNS over TLS from Cloudflare has been added in the Admin Pannel(GL WebUI, not LuCI). 
Some of our fans also want to use NextDNS on GL.iNet routers. As we are planning to add NextDNS in our firmware from version 3.200. This is the instruction on how to setup a NextDNS on GL.iNet routers under version 3.200.

![WebUINextDNS](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/ndwebui.jpg){class="glboxshadow"}


Supporting List:
GL-AR750S-EXT, GL-AR750, GL-MT300N-V2, GL-AR300M series, GL-AR150 series, GL-MiFi, GL-E750, and GL-X750. 

## Register NextDNS Account

Go to [NextDNS](https://nextdns.io/?from=amdj8sqt), then click**mynextdns.io**.
![NextDNSWeb](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/website.jpg){class="glboxshadow"}
After that, go to sign up to register a new private account on NextDNS. 
![Signup](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/signup.jpg){class="glboxshadow"}


## Setup NextDNS on GL.iNet routers

Follow the instrcution to setup your NextDNS on GL.iNet routers:

1. Enable DNS over TLS(Cloudflare or NextDNS), then select Next DNS
![Setup](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/ndselect.jpg){class="glboxshadow"}

2. Go back to NextDNS website, add **New** endpoint. 
![addendpoint](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/addendpoint.jpg){class="glboxshadow"}
 
Input your endpoint name, click **Create**
![newendpoint](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/newendpoint.jpg){class="glboxshadow"}

Then you can get all necessary information of your new endpoint. Copy the ID in your configuration. 

![nextdnsid](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/epid.jpg){class="glboxshadow"}

3. Go to your GL Admin Panel, then input the ID below NextDNS. 
![inputid](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/idinput.jpg){class="glboxshadow"}

4. **Apply** settings. 

Okay, now you can login your NextDNS account to make all settings and check real-time Analytics data.

![analytics](https://static.gl-inet.com/docs/en/3/tutorials/nextdns/ndanalytics.jpg){class="glboxshadow"}
