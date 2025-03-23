# Wターム

## 開発環境
手元に開発環境がある場合にはそれを使ってもらって結構です．  
ない場合には https://github.com/chibutsu-utokyo/debian を使ってください．

## ダウンロード
ターミナルで以下のように実行して必要なものをダウンロードしてください．

- シミュレーションコード
```bash
$ git clone https://github.com/zenitani/OpenMHD
```

- 解析例（このリポジトリ）
```bash
$ git clone https://github.com/amanotk/wterm.git
```

## 解析
### 計算済みのデータをプロット
`wterm.ipynb` を開いて実行してみてください．  
リポジトリに含まれている既に計算済みのデータをプロットします．

### シミュレーションの実行とプロット
1次元の標準的なテスト問題をそのまま動かしてみましょう．
```bash
$ cd OpenMHD/1D_basic  # コードのディレクトリへ移動
$ make                 # コンパイル
$ ./a.out              # 実行
```
シミュレーション結果は `OpenMHD/1D_basic/data/x-*.dat` に保存されます．  
`wterm.ipynb`を参考にして結果をプロットしてみてください．

ここまでできれば準備は完了です．
`wterm.ipynb` を参考にコードを編集して色々と試してみましょう．
