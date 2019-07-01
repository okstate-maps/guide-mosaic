## About
Last Updated *[add date here]*   
Created by [OSU Maps and Spatial Data](https://info.library.okstate.edu/map-room)


## Table of Contents
- Introduction 
- *[Mosaic Datasets]*
- - Photoshop
- - Creating a Mosaic Dataset
- Conclusion
- Further Reading/Resources

## Introduction
Mosaic datasets allow you to easily work with large collections of raster and image data. These datasets can be created in ArcPro and make data management simple.

## *[Mosaic Datasets]*

#### Photoshop
When working with black and white images, it is important to make sure they are all in Grayscale. If they are not, this can be changed. We will start with one image to create an action and use this action to complete the rest.

1. Open photoshop and add one of the images you are using for the mosaic.
2. Select the *Windows* tab on the toolbar and click **Actions**.

![Actions](images/Actions.PNG)

3. A pop up should appear. Select the folder icon to **Create new set**.

![Create new](images/CreateNew.PNG)

4. Name the set and click **OK**.
5. Create a new action by clicking the **Create new action** icon in the *Actions* pane.

![CNAction](images/CNAction.PNG)

6. Name the action, put it in the set that was just created and choose a function key and color if desired. Click record.

![Record](images/Record.PNG)

7. Click the *Image* tab, hover over **Mode** and choose **Grayscale**.

![Grayscale](images/Grayscale.PNG)

8. A message should pop up. Click **Discard**.

![Discard](images/Discard.PNG)

9. Save the image and click **Stop playing/recording** in the *Actions* pane.

![Stop](images/Stop.PNG)

10. To use this newly created action on the remaining files, select the *File* tab, choose **Automate** and **Batch**.

![Batch](images/Batch.PNG)

11. In the new pane, select the desired folder of files and click **OK**. It should toggle through the files and convert them into Grayscale images.

12. Close Photoshop when finished.

![Pane](images/Pane.PNG)

#### Creating a Mosaic Dataset
1. Start a new project in ArcPro and set the file location as the file containing the images you wish to use for the mosaic dataset.
2. Add a folder connection to this file in the *Catalog* pane.
3. Select the files you wish to use and add them to the project. 
4. Right click on the geodatabase and click **Add to project**.

![GDB](images/GDP.PNG)

5. In the *Contents* pane, remove the images. They are now synchronized with the geodatabase.
6. Click the *Analysis* tab on the toolbar and select **Tools**.

![Tools](images/Tools.PNG)

7. Search for and select **Create Mosaic Dataset** in the new *Geoprocessing* pane. 

![CMD](images/CMD.PNG)

8. Set the output location as the project's geodatabase, give it a name, set the coordinate system to that of the current map and ensure **Product Definition** is set to **None**. Then click **Run**.

![CMD2](images/CMD2.PNG)

9. In the *Catalog* pane, you should find the mosaic dataset by expanding the geodatabase. Right click the mosaic dataset and select **Add Rasters**.

![Add Rasters](images/AddRasters.PNG)

10.


## Conclusion

## Further Reading/Resources


[Return to Top](#about)
