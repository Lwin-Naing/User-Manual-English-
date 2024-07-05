# Color-coded with multiple attributes 

PLATEAUの3D都市モデルの色付けでは、前のページで行った「高さ」属性のみではなく、

属性を組み合わせ、建物の色分けをすることが可能です。

ここでは「高さ」属性に加えて、「用途」という属性も使用し色分けをします。

<br>
<br>

1. お好みのテキストエディターを開きます。（メモ帳でも大丈夫です）<br>以下のコードを貼付してください。

- _heightの値が50以上で、用途が業務施設は`#f8a99c`
  
- _heightの値が10以下で、用途が商業施設は`#923b2d`

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

2. 名前をつけて保存してください。拡張子は.jsonにしてください。ファイル名は自由です。

<img width="250" alt="jsonファイル画像" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/263c2958-97cd-4f70-9359-4541cbf08dea">
<br>
<br>


3. 3Dtilesレイヤーの設定項目のスタイルURLを選択します。
<br>

<img width="980" alt="Color-coded with multiple attributes 3 " src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/673683b8-3e08-4c82-a166-4754f53f1aab">

<br>
<br>


4. ファイルアップロードよりファイルがアセットに追加されるので、クリックして選択します。
<br>

<img width="980" alt="stteing 4" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/281c2b95-06fc-4de1-946d-3f47b12655a4">

<br>
<br>


すると、このように表示されます。
<br>


<img width="980" alt="Color-coded with multiple attributes last（revised ver ）" src="https://github.com/CS-eukarya/User-Manual-English-/assets/154571156/16bed301-00fc-46fd-a53e-955035c57cd7">
