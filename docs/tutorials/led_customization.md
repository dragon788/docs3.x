# LED Customization
 
 Support models: GL-AR150 series, GL-AR300 series, GL-MT300N-V2.

 To configure the LED of GL.iNet routers, please login to LuCI by clicking **Advanced settings** at the bottom-left corner of the web Admin Panel. 

![](https://static.gl-inet.com/docs/en/3/troubleshooting/ledadvanced.png){class="glboxshadow"}

![](https://static.gl-inet.com/docs/en/3/setup/gl-ar750s/more_settings/advanced.jpg){class="glboxshadow"}

Then please choose **System** > **LED Configuration**.

---

## Customize your mini travel router

(Take GL-MT300N-V2 as an example)

1. Go to LuCI -> System -> Led Configuration

    ![](https://static.gl-inet.com/docs/en/3/tutorials/led_configuration/config1.png){class="glboxshadow"}

2. Choose the **gl-mt300n-v2:blue:wan** which stand for the middle light in the LED Name list. The other two are power light(unchangeable) and wifi light(changeable).

    ![](https://static.gl-inet.com/docs/en/3/tutorials/led_configuration/config2.png){class="glboxshadow"}

3. Keep the **Trigger** in **netdev**. And you can select which interface you want the middle light stand for: 

    ra0 - main wifi

    ra1 - guest wifi 

    apclio - repeater wifi

    tun0 - vpn(this option will show up when vpn is on) 

    You can select the one you want. This function mainly use for vpn indication.

    ![](https://static.gl-inet.com/docs/en/3/tutorials/led_configuration/config3.png){class="glboxshadow"}

4. Next one is **Trigger Mode**, the **Link on** means solid light and if you enable **Transmit** and **Receive** the light will blink when having data transmission.

    ![](https://static.gl-inet.com/docs/en/3/tutorials/led_configuration/config4.png){class="glboxshadow"}

5. Have fun with your cusomized router.
