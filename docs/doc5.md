## Upload your data

There are two options to upload your data :

- Upload your data trough https://mapshaper.org/ (Upload > Convert)
- Upload your data trough https://flow.mapid.io/ (Upload)
- Upload your data trough Editor (FLOW) (Upload > Edit)


## Upload trough mapshaper

Upload your data to **mapshaper** could be more stable than using FLOW instead.
Due to FLOW Beta Version, uploading shapefile could still unstable.
This is the reason we are recommend you to use mapshaper to upload data.

The using of mapshaper is not integrated to FLOW in this beta version.
Mapshaped in mapid is used to upload your data and convert to GeoJSON

**Mapshaper supported files**

The file supported by mapshaper are :

  - Shapefile (shapefile.zip required)
  - GeoJSON
  - TopoJSON
  - DBF
  - CSV

**Upload Data to Mapshaper**

Please go to mapshaper page **https://mapshaper.org/**

Before upload your file, mapid.io only accept global reference system for geospatial information.
Mapid.io only support file with **WGS84** with **EPSG:4326** reference system.

*If you have UTM reference system, please convert to WGS84 first.*

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.01.04.png)

After selected your files, you can start upload your file by :

- Click select and choose your file from pop up folder/finder.
- Drag your file to 'Quick Import' box.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.30.07.png)

When upload process is finish, you will see all containing data.
Shapefile has 4 data such as **.shx, .shp, .prj, and .dbf.**

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.30.13.png)

After choose **import**, the features will be displayed on the maps window.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.30.19.png)

By clicking on export (top right), you will have an option to download with some extension.
Please choose GeoJSON as your data format and click on export at the pop up box.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.32.56.png)

## Upload trough FLOW

Upload data to FLOW could be unstable due to BETA Version.
However, upload your .GeoJSON data has better result than upload shapefile.zip.

To upload your shapefile, GeoJSON, or converted GeoJSON from Mapshaper, please go to

https://flow.mapid.io

Please login first if you are logged out.
After login please choose **upload** tab.
and click or drag on upload box. (*before upload please read next step*)

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.35.57.png)

When you download your data from mapshaper, make sure you change the **.JSON** file extension to **.GeoJSON.**

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.38.57.png)

After your data is ready to upload to FLOW, than click on **upload**.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.40.48.png)

After **File Uploaded Successfully** show in below upload button, Please check your data at **Layer List** tab.
Your uploaded data should be appear on the bottom of the layer management.

As we are on BETA Version, All uploaded layer will be not updated to your geoportal page due to style references.
To make your data appear on your geoportal, please edit your layer by click on **edit**.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.40.56.png)

After a pop up box appear, please click **OK**.

If a **pop up blocker** appear, please allow it. Click **OK** after edit layer pop up appear.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.47.39.png)

Please change your features color at editor and make sure all layers has colors.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.47.55.png)

After finish editing your features, please choose save option and choose MAPID to apply your style editing.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.48.03.png)

When you have your personal geoportal already open in your webbrowser, Please close it and add new tab.

After that, you can check on geo.mapid.io/yourusername to look if everything gona be alright.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+19.50.39.png)

## Upload your data trough Editor

Beside mapshaper and FLOW, Editor could be used to upload your data also.

The files supported by Editor are :

- GeoJSON
- TopoJSON
- GTFS
- KML
- CSV
- GPX
- and OSM XML

Firstly, go to **Layer List**. And please click on **New Layer**.
For a detail explanation about **creating new layer**, please go to **[create maps](doc4)**

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.26.02.png)

After New Layer is created, please choose **edit**.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.32.35.png)

As on this tutorial we are going to use editor for upload supported file, please choose **open** and click on **file**.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.32.46.png)

After an explorer or finder pop up box appear, please choose on data you want to upload.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.57.08.png)

After finish upload, your features should be visible on the maps.

Before save your uploaded data to mapid, you can also edit the geometry, new features and attribute first.


![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.33.04.png)

After finish editing your data, you can **save** to **MAPID**.

On **Layer List**, please click on **Show/Hide** and choose **Show**.

Please check your data at **geo.mapid.io/yourusername**

And find your just created data on your **layer management.**

Click on the **eye logo** to make it appear, and please **choose symbol.**

*actually symbol should be able to set from FLOW, and we are still fixing this issues*.

![enter image description here](https://s3.amazonaws.com/docs.mapid.io/images/Screen+Shot+2018-09-09+at+20.39.04.png)
