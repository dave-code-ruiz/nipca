# nipca

Home Assistant custom component for NIPCA-compatible cameras. I only use and update @yottatsa code https://github.com/yottatsa/hass_nipca and use for my dlink camera.

# ATTENTION ! Actually this integration have a problem that gui stops working or goes very slow 

Usage
=====

Copy content of custom_components directory in your HA custom_components directory and change configuration.yaml:

    nipca:
      username: [user]
      password: [pass]

    sensor:
      - platform: nipca
        name: Sensor Nipca
        url: http://192.168.x.x
        username: [user]
        password: [pass]

    camera:
      - platform: nipca
        name: Camera Nipca
        url: http://192.168.x.x
        username: your_username
        password: your_password
        mjpeg_url: http://192.168.x.x/video/mpegts.cgi
        still_image_url: http://192.168.x.x/image/jpeg.cgi

Hardware compatibility list
===========================

My D-Link camera DCS-P6000LH and other dlink cameras with nipca cgi .


Donate
=============
[![paypal](https://www.paypalobjects.com/en_US/ES/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=5U5L9S4SP79FJ&item_name=Create+more+code+and+components+in+github+and+Home+Assistant&currency_code=EUR&source=url)


<a href="https://www.buymeacoffee.com/davecoderuiz" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
