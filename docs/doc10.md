
## Overview

Many people start building ther own IoT devices nowdays. And we apprecate it so much. 
It change how we life now days.

Before start visualizing your devices on mapid the image below describe how IoT works on mapid. 

![geomapid street](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-31-35.png?version=1&modificationDate=1536906698379&cacheVersion=1&api=v2&width=1300&height=404)

## Create an ideas

Mapid as IoT platform have many function such as :
- Smart logistic system (gps) + sensors
- Automated vegetation monitoring system
- Water level sensor 
- Weather Station
- Earthquacke sensor
- and many things.

Building your own IoT can be done with a lot of online soource. 

Until this beta test, we still connect our Arduino IoT Devices to ThingSpeak. 

However we are building mapid Internet of Services for IoT Devices in near time. 

## Host your arduino data to Thingspeak

You can start host your arduino sensor by following this steps. 

Sign In to ThingSpeak™ using your MathWorks® Account, or create a new MathWorks account.

![thingspeak](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-32-47.png?version=1&modificationDate=1536906773117&cacheVersion=1&api=v2&width=960&height=300)

Create a new channel

![thingspeak](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-33-56.png?version=1&modificationDate=1536906838415&cacheVersion=1&api=v2&width=622&height=300)

On the new channel form, give the initial field 1 as latitude, field 2 as longitude, and field 3 as your sensor name.

![channelfill](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-35-17.png?version=1&modificationDate=1536906921869&cacheVersion=1&api=v2&width=590&height=800)

Ignore the other field and also ignore the latitude, longitude, and elevation box, we will initialize them on the Arduino program.

![channelfill](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-36-12.png?version=1&modificationDate=1536906974317&cacheVersion=1&api=v2&width=580&height=800)

On the channel dashboard, click "API Keys" bar and copy the "Update a Channel Feed" URL, including the "GET" word.

![channelfill](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-37-10.png?version=1&modificationDate=1536907032780&cacheVersion=1&api=v2&width=932&height=500)


## Devices and Wiring

After finish creating you channel on thingspeak, you might start building your basic IoT Devices. 

This parts is needed to building your IoT Devices. 

![channelfill](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-17+at+12.34.50.png)

You can start wiring your arduino to internet module. In this case, we are using SIM900.

![channelfill](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-4-28.png?version=1&modificationDate=1536905073142&cacheVersion=1&api=v2&width=1187&height=778)

Sensor wiring

![channelfill](https://mapidseeit.atlassian.net/wiki/download/thumbnails/16777353/image2018-9-14_13-6-39.png?version=1&modificationDate=1536905203512&cacheVersion=1&api=v2&width=1400&height=708)


## Start import code with arduino IDE

Download arduino ino file and import to your arduino devices.

[Arduiono ino file](https://s3.amazonaws.com/docs.mapid.io/data/one_analog_sensor_wo_gps_optimation2/one_analog_sensor_wo_gps_optimation2.ino)


Please set your personal thingspeak API to your arduino code. 
Please set your network seting such as APN, username and password to your own internet service provider. 