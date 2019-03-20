try! Swift Tokyo 2019
============================

## コンパイル

コンパイルにはLuaLaTeXが必要です。[TeXLive](https://www.tug.org/texlive/)（または[MacTeX](https://tug.org/mactex/)）をインストールしてください。
OSXでは次のコマンドでアニメーションあり・なし両方のスライドを生成することができます。

```
$ make all
```

このスライドでは標準でOSXのヒラギノフォントを利用してコンパイルが行なわれます。
OSXではない場合や、ヒラギノフォントが使用できない場合は下記の方法で、
TeXLive付属のIPAフォントなどを利用したコンパイルを行ってください。

### IPAフォントを利用する

次のように環境変数を設定してから`make`を実行してください。

```
$ export USE_IPAFONT=true
```

### 游フォントを利用する

次のように環境変数を設定してから`make`を実行してください。

```
$ export USE_YUFONT=true
```
