# nipca

Home Assistant custom component for NIPCA-compatible cameras.

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
        username: admin
        password: 486705
        mjpeg_url: http://192.168.x.x/video/mpegts.cgi
        still_image_url: http://192.168.x.x/image/jpeg.cgi


