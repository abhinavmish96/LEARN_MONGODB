# Module 1 : Getting Stated

## This Chapter focuses on the MongoDB basics, installation and set-up.

### Topics covered in this module include:

- **Installing MongoDB Copmpass**
- **Run MongoDB**
- **Connect and Use MongoDB**

### Installing MongoDB Copmpass

- Please download Compass from the [MongoDB Download Center](https://www.mongodb.com/download-center/compass). If you downloaded Compass before today, please make sure you are using latest (Stable) version of Compass and upgrade if necessary. Please ensure you don't download "Community Edition Stable" version.
- Install Compass on your computer from the download.
- Launch Compass.
- Use the following information to complete this form, but do not click "Connect" yet.

Hostname: cluster0-shard-00-00-jxeqq.mongodb.net

Username: m001-student

Password: m001-mongodb-basics

Replica Set Name: Cluster0-shard-0

Read Preference: Primary Preferred
- Click "Add to Favorites" and enter M001 RS as the Favorite Name. Adding this connection as a favorite will enable you to easily connect to our class MongoDB deployment after closing and restarting Compass at some point in the future.
- Now, click "Connect" and load the databases in the M001 class MongoDB deployment.

- #### Enable Geographical Visualizations
    - MongoDB Compass uses a 3rd party plugin for the geographical visualization of geospatial fields in your documents.
    - If you are not able to see a map box in your Schema tab, when analyzing the coordinates field of ships.shipwrecks, you should check the option to enable geographical visualization.
    - To do that you will have to click on the menu:<br>
        <pre>
        Help -> Privacy Settings</pre> 
    - and then enable this feature.


### Note: The Apply button in MongoDB Compass has been renamed Analyze.

### For more information, check out our resources on [MongoDB Geospatial operators](https://docs.mongodb.com/manual/reference/operator/query-geospatial/).

### Please review the [JSON spec](http://www.json.org/) for more detail on the data types directly supported in JSON.

# Module 2 : MongoDB Query + Atlas

## This Chapter focuses on the MongoDB query and Atlas.

### Topics covered in this module include:

- **MongoDB Query and Shell**
- **Connect and Use MongoDB**

### MongoDB Query and Shell

- 