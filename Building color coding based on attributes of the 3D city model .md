# Building color coding based on attributes of the 3D city model 


The 3D city model of PLATEAU has an attribute with height values called "_height."

You can use this attribute to color-code based on height.

Open your favorite text editor (Notepad is fine).
Please paste the following code:

- Items with a _height value less than 60: #13293D

- Items with a _height value between 60 and less than 120: #1B98E0

- All others: #E8F1F2 with an opacity of 0.5.

```
{
    "show": "true",
    "color": {
        "conditions": [
            [
                "${_height} < 60",
                "color('#13293D')"
            ],
            [
                "${_height} < 120",
                "color('#1B98E0')"
            ],
            [
                "true",
                "color('#E8F1F2', 0.5)"
            ]
        ]
    }
}
```

<br>
<br>

2. 名前をつけて保存してください。拡張子は.jsonにしてください。ファイル名は自由です。

   <img width="250" alt="json file image" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/ef45d928-c46a-40c9-8c00-b7b6fff2074f">

<br>
<br>

3. 3Dtilesレイヤーの設定項目のスタイルURLを選択します。
<br>

<img width="980" alt="setting 3 " src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/3a784ce2-f188-495e-b878-793341be34ad">

<br>
<br>

4. ファイルアップロードよりファイルがアセットに追加されるので、クリックして選択します。
<br>

<img width="980" alt="stteing 4" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/5f823808-d2a9-4bc1-a222-c78b5fbf845b">

<br>
<br>

すると、このように表示されます。

<img width="980" alt="Building color coding based on attributes of the 3D city model last" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/f04db219-71c2-4e2f-9262-452257f02aa1">


   
