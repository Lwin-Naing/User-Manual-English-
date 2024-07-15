# Adding and Removing Datasets

![Dataset 1](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/9c697874-cfb5-4a92-ab5b-0600fb3fa561)

![スクリーンショット 2024-07-04 225653.png](Adding%20and%20Deleting%20Dataset%202d35fb380d1a43b08fd853acd717769d/%25E3%2582%25B9%25E3%2582%25AF%25E3%2583%25AA%25E3%2583%25BC%25E3%2583%25B3%25E3%2582%25B7%25E3%2583%25A7%25E3%2583%2583%25E3%2583%2588_2024-07-04_225653.png)

A. Add Dataset: You can import data from your local PC.

B. Delete Button: This button appears when you hover your mouse over a dataset card.

Currently, dataset management is limited to adding (importing) and deleting datasets.<br>
We plan to expand these features in future development.

## How to Add a Dataset

1. Click "Datasets" from the dropdown menu next to the title.

![Dataset 2](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/cfdf259c-85e6-44b2-a025-a296448dace5)

![2024-07-04_23h03_49.png](Adding%20and%20Deleting%20Dataset%202d35fb380d1a43b08fd853acd717769d/2024-07-04_23h03_49.png)


2. Click "Add Dataset."

![Dataset 3](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/eb2f06e1-06ef-42c2-96ef-5b394a98d280)

![2024-07-04_23h19_33.png](Adding%20and%20Deleting%20Dataset%202d35fb380d1a43b08fd853acd717769d/2024-07-04_23h19_33.png)



3. Select the file and click "Open."

![Dataset 4](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/26ad7e58-a9d4-4e61-8cd3-da0f5540dd2c)

![2024-06-06_15h25_36.png](Adding%20and%20Deleting%20Dataset%202d35fb380d1a43b08fd853acd717769d/2024-06-06_15h25_36.png)



4. The CSV data will be added. Click the "Edit" button (the pencil icon) on the globe to return to the editing page.

![Dataset 5](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/8fd296e7-7854-41b0-99b4-55f333fdd8c0)

![2024-07-04_23h46_03.png](Adding%20and%20Deleting%20Dataset%202d35fb380d1a43b08fd853acd717769d/2024-07-04_23h46_03.png)



## How to Import an Uploaded Dataset

1. Click on the CSV data that was added in the "Datasets" tab in the left panel.

![Dataset 6](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/60baedcb-8759-4e2a-a3ae-3c8a898aa879)
 
2. Confirm that there are no garbled characters and click on "Layer Type."

![Dataset 7](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/79cf23fb-9bb0-470c-aeae-09149b942062)

3. Select the layer type.

![Dataset 8](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/495dbd26-3e53-4edd-8283-a0e3dca6dea7)

You can choose from the following six layer types:
- [Marker](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Marker.md) 
- [Photo Overlay](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Photo%20Overlay.md)
- [Sphere](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/Sphere.md)
- [3D Model](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/3D%20Model.md)
- [3D Tiles](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/3D%20Tiles.md)
- [File](https://github.com/CS-eukarya/User-Manual-English-/blob/Re-Earth-layers/File.md)

4. Click "Import."

![Dataset 9](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/d1fbd20a-93fa-4ee1-830f-a8b16bdee4ad)
 
5. The selected layer will be added to the map.
In the case of a sphere, it will be displayed like this.

![Dataset 10](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/2245b939-7947-4198-891d-d50a10ab93fd)

## How to Set Properties for All Layers in a Batch

1. Click on the "Outline" tab in the left panel, then select the CSV data that has been added to the layer.

![Dataset 11](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/50f5c404-9c79-4ff9-a277-3d28e30da661)


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
