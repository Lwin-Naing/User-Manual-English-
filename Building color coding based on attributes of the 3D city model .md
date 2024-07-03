# Building color coding based on attributes of the 3D city model 

PLATEAUの3D都市モデルには「_height」という高さの値が入った属性があります。<br>

この属性を使って高さ別に色分けをすることが可能です。

<br>
<br>

1. お好みのテキストエディターを開きます。（メモ帳でも大丈夫です）

以下のコードを貼付してください。

- _heightの値が60未満のものは`#13293D`

- 60以上120未満のものは`#1B98E0`
  
- それ以外は`#E8F1F2`、透明度0.5として設定されます。

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


   
