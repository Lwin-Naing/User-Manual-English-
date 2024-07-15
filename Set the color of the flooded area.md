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

<img width="94" alt="styljsonアイコン" src="https://github.com/user-attachments/assets/b287be03-7bd8-4e95-b267-79ba284492bc">

<br>
<br>

3. 3Dtilesレイヤーの設定項目のスタイルURLを選択します。


![複数の属性で色分け３](https://github.com/CS-eukarya/User-Manual-Japanese-/assets/154571156/a6dbf5ec-6410-47cf-a7b9-b33e28f44577)

<br>
<br>

4. ファイルアップロードよりファイルがアセットに追加されるので、クリックして選択します。


![複数の属性で色分け４](https://github.com/CS-eukarya/User-Manual-Japanese-/assets/154571156/0c4652eb-60f1-43aa-bacf-033abb8ccab9)

<br>
<br>

すると、このように表示されます。


<img width="980" alt="複数の属性で色分け完了（変更版）" src="https://github.com/CS-eukarya/User-Manual-Japanese-/assets/154571156/14724870-20b5-4d7a-8776-4f99bb53eddc">
