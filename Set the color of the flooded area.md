# 複数の属性で色分け

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

<img width="250" alt="styljsonアイコン" src="https://github.com/user-attachments/assets/b287be03-7bd8-4e95-b267-79ba284492bc">

<br>
<br>

3. 3Dtilesレイヤーの設定項目のスタイルURLを選択します。


![３](https://github.com/user-attachments/assets/6d3f4fce-6db7-4ea7-a32a-1599d5bbbfa3)

<br>
<br>

4. ファイルアップロードよりファイルがアセットに追加されるので、クリックして選択します。

![４](https://github.com/user-attachments/assets/4f02d780-cc0c-450c-af86-655bf55f4344)

<br>
<br>

すると、このように表示されます。


<img width="980" alt="5" src="https://github.com/user-attachments/assets/162e9acf-7149-4eb4-9e58-678f0d647e5b">
