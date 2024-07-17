# Color-Coding by Multiple Attributes
In the color coding of PLATEAU's 3D city model, it is possible to combine attributes and color-code buildings, not only using the "height" attribute as done on the previous page.

Here, in addition to the "height" attribute, we will also use the "usage" attribute for color coding.

<br>
<br>

1. Open your preferred text editor (Notepad is fine).<br>Paste the following code:

- If the value of _height is 50 or more and the usage is office facility, use `#f8a99c`
  
- If the value of _height is 10 or less and the usage is commercial facility, use `#923b2d`

```jsx
{
    "show": "true",
    "color": {
        "conditions": [
	    [
                "(${_height} > 50) && (${`usage} === 'office facility')",
                "color('#f8a99c')"
            ],
            [
                "(${_height} < 10) && ($`{usage} === 'commercial facility`)",
                "color('#923b2d')"
            ]
        ]
    }
}
```
<br>
<br>

2. Save the file with a name of your choice. Ensure the file extension is .json.

<img width="250" alt="styljsonアイコン" src="https://github.com/user-attachments/assets/b287be03-7bd8-4e95-b267-79ba284492bc">

<br>
<br>

3. In the settings for the 3D tiles layer, select the Style URL option.

![３](https://github.com/user-attachments/assets/6d3f4fce-6db7-4ea7-a32a-1599d5bbbfa3)

<br>
<br>

4. From the file upload option, add the file to the assets. Click on it to select it.

![４](https://github.com/user-attachments/assets/4f02d780-cc0c-450c-af86-655bf55f4344)

<br>
<br>

Then, it will be displayed like this.

<img width="980" alt="5" src="https://github.com/user-attachments/assets/162e9acf-7149-4eb4-9e58-678f0d647e5b">
