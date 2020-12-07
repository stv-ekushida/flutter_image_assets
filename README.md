# flutter_image_assets

@2x / @3xなど

## 設定
pubspec.yaml
```
  assets:
    - images/
    - images/2.0x/
    - images/3.0x/
```    

## 呼び方
```
Image.asset('images/ic_list_off_on.png')
```
## 参考情報
https://qiita.com/takkyun/items/814aa45beee422a5f0c6

|iOS| Android |
|---|---|
|@1.0x | mdpi |
|@1.5x | hdpi | 
|@2.0x | xhdpi | 
|@3.0x | xxhdpi | 
