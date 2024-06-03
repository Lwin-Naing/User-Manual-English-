# Tiles
<br>

# What are tiles?

Tiles are created by dividing the entire map into square segments and laying them out on digital Earth. This method allows for the efficient display of maps in various styles. By using tiles instead of a single map image for the entire viewport, it's possible to maintain high performance during zooming in and out, significantly enhancing the user experience.
<br>

# Tile Groups
Tile groups allow you to configure the map tiles displayed on digital Earth. You can select from several existing tile sets or apply externally hosted map tiles by specifying a URL.

![basic 1.png](Tiles%20759a5fb32fc64432865e641ca6858d85/basic_1.png)
<br>
<br>

### What are tiles?

There are several advantages to tiled maps. Each time the user pans, most of the tiles are still relevant and can be kept displayed, while new tiles are fetched. This greatly improves the user experience, compared to fetching a single map image for the whole viewport. It also allows individual tiles to be pre-computed, a task easy to parallelize. Also, displaying rendered images served from a web server is less computationally demanding than rendering images in the browser, a benefit over technologies such as Web Feature Service (WFS). While many map tiles are in raster format (a bitmap file such as PNG or JPG), the number of suppliers of vector tiles is growing. Vector tiles are rendered by the client browser, which can thus add a custom style to the map. Vector map tiles may also be rotated separately from any text overlay so that the text remains readable.
<br>
<br>

### Re-Earth tiles list

The Tiles settings are comprised of a Tile List that shows all the map tiles to be displayed on the Digital Earth and settings for the currently selected tile. You can choose from several existing map tiles, or you can apply externally distributed map tiles by specifying a URL.

![456 2.png](Tiles%20759a5fb32fc64432865e641ca6858d85/456_2.png)

Click on the Plus Button: Add a tile.

Click on Trash Button: Delete a tile.
<br>
<br>

### Tile type

Selects the tile type of the selected item. 

![5 1.png](Tiles%20759a5fb32fc64432865e641ca6858d85/5_1.png)

![Screenshot 2023-02-05 120558.png](Tiles%20759a5fb32fc64432865e641ca6858d85/Screenshot_2023-02-05_120558.png)
<br>
<br>
<br>

## Tile Types

**Default**

![5 1 (1).png](Tiles%20759a5fb32fc64432865e641ca6858d85/5_1_(1).png)
<br>
<br>

**Labeled**

![1.png](Tiles%20759a5fb32fc64432865e641ca6858d85/1.png)
<br>
<br>

**Road Map**

![2.png](Tiles%20759a5fb32fc64432865e641ca6858d85/2.png)
<br>
<br>

**Stamen Watercolor**

![3.png](Tiles%20759a5fb32fc64432865e641ca6858d85/3.png)
<br>
<br>

**Stamen Toner**

![4.png](Tiles%20759a5fb32fc64432865e641ca6858d85/4.png)
<br>
<br>

**OpenStreetMap**

![5.png](Tiles%20759a5fb32fc64432865e641ca6858d85/5.png)
<br>
<br>

**ESRI Topography**

![6.png](Tiles%20759a5fb32fc64432865e641ca6858d85/6.png)
<br>
<br>

**Earth at night**

![7.png](Tiles%20759a5fb32fc64432865e641ca6858d85/7.png)
<br>
<br>

**Japan GSI Standard Map**

![8.png](Tiles%20759a5fb32fc64432865e641ca6858d85/8.png)
<br>
<br>

**Using your own Tiles**

you can apply externally distributed map tiles by specifying a URL

![54.png](Tiles%20759a5fb32fc64432865e641ca6858d85/54.png)

![9 1.png](Tiles%20759a5fb32fc64432865e641ca6858d85/9_1.png)
<br>
<br>

### Tiles Setting

![57 1.png](Tiles%20759a5fb32fc64432865e641ca6858d85/57_1.png)
<br>
<br>

### Zoom level

Minimum zoom level: Sets the minimum zoom level for the tile data to be displayed.

![rfgdg.png](Tiles%20759a5fb32fc64432865e641ca6858d85/rfgdg.png)

 Maximum zoom level: Sets the maximum zoom level for the tile data to be displayed.

![ghj.png](Tiles%20759a5fb32fc64432865e641ca6858d85/ghj.png)
<br>
<br>

### Opacity

Provides the ability to change the transparency of Earth

![sd.png](Tiles%20759a5fb32fc64432865e641ca6858d85/sd.png)
