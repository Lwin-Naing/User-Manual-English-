# 3D Tiles

## What is 3D Tiling in Re-Earth App?

3D Tiling is an open specification for sharing, visualizing, fusing, and interacting with massive heterogenous 3D geospatial content across desktop, web, and mobile applications in Re-earth App. This feature allows various objects, such as three-dimensional buildings, to be displayed on the globe over a wide area.

![Untitled](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/fb597000-9a81-4e56-8438-a9c5de4aa5aa)
<br>
<br>
<br>

## How to use 3D tiles in Re-Earth App.

### Adding a 3D tile

- Drag and drop the 3D tile icon anywhere on the globe. (**Note**: The icon will not be displayed like a marker.)

![Untitled 1](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/3f449005-25fd-4e1f-a1ce-ed86b482f91f)
<br>
<br>

- When a 3D tile is dropped on the globe in the Re-Earth App, the word "3D tile" appears in blue in the layer on the left panel. The more 3D tiles you drop on the Re-earth app, the more 3D tiles appear in the layer.

![Untitled 2](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/00160d7f-a9da-44ab-a8e8-bd00455c2e51)
<br>
<br>
### Renaming a 3D tile

To rename a 3D Tile layer, double-click on the text of the 3D tile. This switches to an editable view where you can enter the new name and confirm by pressing Enter.

![Untitled 3](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/ff6b0027-91e0-460a-a6ff-045003c4fb80)
<br>
<Br>

### Hiding the 3D tiles

Click on the eye symbol on the right side of the 3D tile in the left panel to make the 3D portion of the globe disappear in the Re-earth APP.
<br>
<br>

**Before Hiding 3D Tiles**

![3Dtile5](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/3f4319c4-2a1e-4ab0-8318-1002172e46d1)

<br>
<br>

**After Hiding 3D Tiles**

![3Dtile6](https://github.com/CS-eukarya/User-Manual-Japanese-/assets/154571156/9564aabd-b6c8-4c4b-8a92-ef7cadc53a6c)

<br>
<br>

### Deleting a 3D tile

To delete a 3D tile, click on the 3D tile you wish to delete in the layers in the left panel, make sure it is selected in blue, and then press the "trash can" symbol on the right side of the layer to delete it.

![3Dtile7](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/a8c0560f-5a68-49ee-bc06-62ec411be36a)

<br>
<br>

## 3D Tile Properties

The properties of a 3D tile allow you to set the following items

![Untitled 7](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/89633bec-f79d-4529-96a8-8e5944b6f74d)

**A. Type:** Select from URL or OSMBuildings.

OSM Buildings is an open-source project that uses OpenStreetMap (OSM) data to generate 3D models of buildings, OSM Buildings can be integrated into web maps and mobile applications, allowing users to freely change the height, color, shape, texture, etc. of buildings. This allows the implementation of helpful information for urban planning and architectural design purposes.
<br>
<br>

**B. Tileset URL:** Specify the URL where the 3D tiles are distributed. Be sure to check that the URL ends with tileset.json.

1. click on the URL input field to display the set modal. 
2. Select the URL tab in the set modal. 
3. You can enter a URL. 
4. click the select button in the lower right corner.

![3Dtile9](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/4d6dc381-e8e3-4d82-bbf6-b7b4651d56f3)

<br>
<br>

**C.** **Style URL:** Specify the URL of a JSON file in 3D tiles styles format when you want to change the style of 3D tiles, separate them by color, attribute, etc.

1. click on the URL input field to display the set modal. 
2. Upload the json file in 3D tiles style format by clicking "Upload File". 
3. Select the uploaded jsond file in the asset. 
4. Click the Select button in the lower right corner.

![3Dtile10](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/2d3debeb-62cb-49c6-a2be-65300cfd8d8d)

<br>
<br>

**D. Shadow:** Enable/disable shadow expression for 3D objects and other objects. Note that if you want to enable shadows, you must also enable shadows in the scene settings.
<br>
<br>
<br>

## 3D tile data available in Re:Earth

We have prepared 3D tiles for use in Re:Earth and assumed that they are publicly available in PLATEAU to the server.

For more information about PLATEAU, please visit [official website](https://www.mlit.go.jp/plateau/).

As of the end of fiscal year 2021, Project PLATEAU offers 3DTiles data for 56 cities, which is available on the [G-Spatial Information Center](https://www.geospatial.jp/ckan/dataset/plateau).

Please refer to [this](https://github.com/Project-PLATEAU/plateau-streaming-tutorial/blob/main/README.md) for instructions on how to obtain the list of distribution URLs.

| Dataset Name | Subdivision | URL |
| --- | --- | --- |
| Building Model (Chiyoda Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13101_chiyoda-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13101_chiyoda-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13101_chiyoda-ku/low_resolution/tileset.json |
| Building Model (Chuo Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13102_chuo-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13102_chuo-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13102_chuo-ku/low_resolution/tileset.json |
| Building Model (Minato Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13103_minato-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13103_minato-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13103_minato-ku/low_resolution/tileset.json |
| Building Model (Shinjuku Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13104_shinjuku-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13104_shinjuku-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13104_shinjuku-ku/low_resolution/tileset.json |
| Building Model (Bunkyo Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13105_bunkyo-ku/notexture/tileset.json |
| Building Model (Taito Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13106_taito-ku/notexture/tileset.json |
| Building Model (Sumida Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13107_sumida-ku/notexture/tileset.json |
| Building Model (Koto Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13108_koto-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13108_koto-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13108_koto-ku/low_resolution/tileset.json |
| Building Model (Shinagawa Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13109_shinagawa-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13109_shinagawa-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13109_shinagawa-ku/low_resolution/tileset.json |
| Building Model (Meguro Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13110_meguro-ku/notexture/tileset.json |
| Building Model (Ota Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13111_ota-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13111_ota-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13111_ota-ku/low_resolution/tileset.json |
| Building Model (Setagaya Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13112_setagaya-ku/notexture/tileset.json |
| Building Model (Shibuya Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13113_shibuya-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13113_shibuya-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13113_shibuya-ku/low_resolution/tileset.json |
| Building Model (Nakano Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13114_nakano-ku/notexture/tileset.json |
| Building Model (Suginami Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13115_suginami-ku/notexture/tileset.json |
| Building Model (Toshima Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13116_toshima-ku/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13116_toshima-ku/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13116_toshima-ku/low_resolution/tileset.json |
| Building Model (Kita Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13117_kita-ku/notexture/tileset.json |
| Building Model (Arakawa Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13118_arakawa-ku/notexture/tileset.json |
| Building Model (Itabashi Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13119_itabashi-ku/notexture/tileset.json |
| Building Model (Nerima Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13120_nerima-ku/notexture/tileset.json |
| Building Model (Adachi Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13121_adachi-ku/notexture/tileset.json |
| Building Model (Katsushika Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13122_katsushika-ku/notexture/tileset.json |
| Building Model (Edogawa Ward) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13100_tokyo/13123_edogawa-ku/notexture/tileset.json |
| Building Model (Hachioji Minami Osawa) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13201_hachioji/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13201_hachioji/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13201_hachioji/low_resolution/tileset.json |
| Building Model (Higashimurayama) | Without Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13213_higashimurayama/notexture/tileset.json |
|  | With Texture | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13213_higashimurayama/texture/tileset.json |
|  | With Texture (Low Resolution) | https://plateau.geospatial.jp/main/data/3d-tiles/bldg/13213_higashimurayama/low_resolution/tileset.json |
