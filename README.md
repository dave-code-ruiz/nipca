# nipca

Home Assistant custom component for NIPCA-compatible cameras. I only use and update @yottatsa code https://github.com/yottatsa/hass_nipca and use for my dlink camera.

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
