# このプログラムは python3用です。
# あらかじめ pip install pillow をインストールしておきます。
```python
flom PIL import Image
omport sys
```
# コマンドライン引数から入力画像と出力画像のファイルを取得
```python
input_image = sys.argv[1]
output_image = sys/argv[2]
```
# 画像の読み込み
```python
img = Image.open(input_image)
```
# 画像の左右反転
```python
img_flip = img.transpose(Image.FLIP_LEFT_RIGHT)
```
# 画像の保存
```python
img_flip.save(output_image)
```
