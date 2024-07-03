# Adding and Removing Datasets

- Image

A. Add Dataset: You can import data from your local PC.
B. Delete Button: This button appears when you hover your mouse over a dataset card.

Currently, dataset management is limited to adding (importing) and deleting datasets.<br>
We plan to expand these features in future development.

## How to Add a Dataset

1. Click "Datasets" from the dropdown menu next to the title.

- Image

2. Click "Add Dataset."

- Image

3. Select the file and click "Open."

- Image

4. The CSV data will be added. Click the "Edit" button (the pencil icon) on the globe to return to the editing page.

- Image


## How to Import an Uploaded Dataset



1. Click on the CSV data that was added in the "Datasets" tab in the left panel.

- Image 



2. Confirm that there are no garbled characters and click on "Layer Type."

- Image

3. Select the layer type.

- Image



You can choose from the following six layer types:

   - [Marker](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Marker.md) 

   - [Photo Overlay](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Photo%20Overlay.md)

   - [Sphere](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Sphere.md)

   - [3D Model](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/3D%20Model.md)

   - [3D Tiles](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/3D%20Tiles.md)

   - [File](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/File.md)

4. Click "Import."

- Image 

5. The selected layer will be added to the map.
In the case of a sphere, it will be displayed like this.

-Image


## How to Set Properties for All Layers in a Batch

1. Click on the "Outline" tab in the left panel, then select the CSV data that has been added to the layer.

- Image


2. Move to the right panel and click on the text you want to set.<br>
   A small pop-up will appear, so click on "Link from Dataset."

- Image

3. When you click "Link from Dataset," the columns in the CSV that can be used as settings will be displayed, so select the item you want to set.

- Image

 - When the text "This value is linked to {dataset field}" is displayed in blue, it means that the setting is correct.

- Image

 - Set "Link from Dataset" for all the items you want to link.
 - Be sure to select the parent tree of the layer in the left panel before setting "Link from Dataset."

- Image

 - When you expand the CSV data in the layer, the layer name is not included. You can add it manually.
(Double-click to change the name)
<br>

<br>
## Reflecting CSV Information in Infoboxes

1. Click on the "Outline" tab in the left panel, then select the CSV data that has been added to the layer.

- Image

2. Click on "Create Infobox" in the Infobox tab on the right panel.

- Image

3. Select the block [無効な URL を削除しました] you want to add to the infobox.

- Image

4. Click on the text you want to set.

A small pop-up will appear, so click on "Link from Dataset."

- Image

5. When you click "Link from Dataset," the columns in the CSV that can be used as settings will be displayed, so select the item you want to set.

- Image

- Set "Link from Dataset" for all the items you want to link.

6. Even if you enter text directly, the same text you entered will be displayed in all infoboxes.

- Image

7. When you click on a sphere, the information of the facility will be reflected in each infobox.

- Image

## Important Points When Creating CSV Data

- To plot multiple points at once, you need to organize the points in a CSV file.

- Start entering items from row A1.

- The CSV file must contain columns of latitude and longitude values to be plotted, and the column names must be "lat" and "lng" respectively. (Enter in decimal degrees)

- Save the CSV file in "CSV-UTF8" format.

- Image 


Note: The CSV file in this example has been modified for this manual. Please note that it is different from the actual information.

- **Importing a large amount of CSV data (over 100 items) can put a load on the server and significantly slow down Re:Earth's operation, so please refrain from doing so.**

## How to Delete a Dataset



1. Click "Datasets" from the dropdown menu next to the title.

- Image

2. Hover your mouse over the dataset card, and a delete button will appear. Click the delete button.

- Image

3. A confirmation message "Are you sure you want to delete?" will appear. Click the delete button again to confirm.

- Image

<aside>

⚠️Caution⚠️

Before deleting a dataset, make sure it is not being used in any projects. If the dataset is connected to any project, deleting it may cause the connected project to become incomplete.

</aside>
