# 3D Model

This tool is for placing your 3D model data on the Re-Earth App.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/4a7a0339-f2f8-45a5-b7a4-62eed1bf508c)

<br>
<br>

## Supported Data Formats

* glTF

   - Supports glTF 1.0 or 2.0. Draco compression is also supported.

   - While there are various formats of glTF, we mainly support glTF Embedded (`.gltf`) or glTF Binary (`.glb`) formats, where all data including images are embedded in a single file.

   - The glTF Separated format (`.gltf` + .bin + image files, etc.) split into multiple files is not supported for upload display within Re:Earth. However, it may be possible to display if you directly specify the file URL that is being served on a server with proper CORS settings.

   - Other formats (e.g., .obj, .fbx) are not supported. Please convert to glTF format yourself in advance.
<br>
<br>

## How to set up 3D Model 

1. Drag and drop the 3D model marker to any desired location.<br>
   At this point, no markers or icons will be displayed.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/a1a07bbe-1fbd-44f5-bbb5-88253b3362a2)

<br>
<br>
2. A new "3D Model" item with a blue band will be added to the layer column on the left side.

3. The 3D model settings screen (properties) will be displayed in the right-side panel of the screen.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/d32a6738-40f0-4b5b-bcfe-02832fa7a787)

## 3D Model Properties
In the 3D model properties, you can adjust the following settings:

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/8c293ac3-7d3e-41ab-af70-a22ec0009541)

A. **URL**: This is where you can enter the URL of the uploaded **3D model** data to display it.

  - Clicking on the URL input field will display the asset modal. You can upload and select 3D models from here. See Asset Modal for details.

B. **Location**: In the Location section you can Set the latitude and longitude to display the 3D model.

C. **Altitude**: At the Altitude, you can set the height at which the 3D model will be displayed.

D. **Altitude Base**: You can select from "Default", "Fixed to the ground surface", or "Altitude from the ground surface". When "Default" is selected, the altitude is the absolute altitude from the WGS84 ellipsoid (digital earth). Fixed to Surface" and "Elevation from Surface" will be different from "Default" only if the "Terrain" setting is enabled in the scene.

E. **Heading:** This specifies the horizontal angle of the 3D model. The valid range is 0~360.

F. **Pitch**: The Pitch Specify the vertical angle of the 3D model. The Valid range is 0~360.

G. **Roll**: Specifies the tilt angle of the 3D model. The valid range is 0~360.

H. **Scale**: Specify the display size of the 3D model data in equal size.

I. **Max Scale**: The Max Scale is the Maximum scale displayed on the screen. The unit is the same as the "Size" setting. No larger than this will be displayed.

J. **Minimum display size**: Minimum size to be displayed on the screen. The unit is a pixel. It will not display any smaller size regard than the pixel.

K. **Animation**: Turn on/off the animation included in the 3D model data. Note that if you want to enable animation, you must also enable animation in the scene settings.
<br>
<br>

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/53f16cf5-5d43-435f-9089-7c0005319905)


L. **3D Model Shadows**: Turn on/off shadows on the 3D model. Note that if you want to use the 3D Model Shadows, you must also enable them in the scene settings.

M. **Color Blend**: Allows you to tint the 3D model with a specified color. You can select "Disable", "Highlight", "Replace", and "Mix". When "Disable" is selected, no color blending is performed. Highlight" multiplies the intrinsic color of the 3D model by the color you set. Replace" replaces the intrinsic color of the 3D model itself with the color you set. Mix" blends the intrinsic color of the 3D model with the color you set.

N. **Color**: Sets the color of the 3D model, HTML color codes are valid.

O. **Lighting Color**: Specify the lighting color of the 3D model.

P. **Silhouette**: Display the outline of the 3D model.

Q. **Silhouette Color**: Specify the outline color of the 3D model, HTML color code is valid.

R. **Silhouette size**: Set the width of the outline of the 3D model. Unit is the pixel. 
<br>
<br>

## Renaming a 3D model

Double-click the text "3D Model" in the layer to rename it.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/02ca1eb3-ba7f-4238-aac1-8a6e375c7f47)

<br>
<br>
## Hiding a 3D model:

Select the 3D model you want to hide and click the eye icon to the right of it.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/316d19ff-90f0-40ba-ac6e-b60cbe995e15)

<br>
<br>

## Deleting a 3D model

Select the 3D model you want to delete from the left panel, then click the trash can icon to delete it.

![image](https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/5b694dc3-f08f-4f68-b151-1ffd77e55297)
<br>
<br>
