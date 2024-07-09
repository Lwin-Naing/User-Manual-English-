# Color-coded with multiple attributes 

In the coloring of the PLATEAU 3D city model, you can combine attributes and color-code buildings, not just using the "height" attribute as done on the previous page.

Here, in addition to the "height" attribute, the "use" attribute will also be used for coloring.

1. Open your favorite text editor (Notepad is fine). Please paste the following code:

- For buildings with a _height value of 50 or more and used as business facilities use: `#f8a99c`
  
- For buildings with a _height value of 10 or less and used as commercial facilities use: `#923b2d`

```jsx
{
    "show": "true",
    "color": {
        "conditions": [
	    [
                "(${_height} > 50) && (${用途} === '業務施設')",
                "color('#f8a99c')"
            ],
            [
                "(${_height} < 10) && (${用途} === '商業施設')",
                "color('#923b2d')"
            ]
        ]
    }
}
```
<br>
<br>

2. Save the file with the name of your choice and use the .json extension.

<img width="250" alt="jsonファイル画像" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/263c2958-97cd-4f70-9359-4541cbf08dea">
<br>
<br>


3. Select the style URL in the settings for the 3D Tiles layer.
<br>

<img width="980" alt="Color-coded with multiple attributes 3 " src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/673683b8-3e08-4c82-a166-4754f53f1aab">

<br>
<br>


4. Once the file is added to the assets through file upload, click to select it.
<br>

<img width="980" alt="stteing 4" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/281c2b95-06fc-4de1-946d-3f47b12655a4">

<br>
<br>


Then, it will be displayed like this.
<br>


<img width="980" alt="Color-coded with multiple attributes last（revised ver ）" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/16bed301-00fc-46fd-a53e-955035c57cd7">
