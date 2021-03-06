# 第1章 Linuxとは

## 基本ソフトウェアと応用ソフトウェア

- 動作しているコンピュータは大きく分けて、ハードウェアとソフトウェアがある。
  - ハードウェアはコンピュータの機械そのもの
  - ソフトウェアは、ハードウェアで動作しているプログラム
- ソフトウェアも大きく分けて、基本ソフトウェアと応用ソフトウェアの2つがある
  - 基本ソフトウェアはOperating System(OS)のこと e.g.) Windows・Linux、Mac OS X
  - 応用ソフトウェアはその上で動くアプリーケーション e.g.) Word・Excel、PowerPoint



## Linuxの特徴

### カーネルとユーザランド

- 基本ソフトウェアは「カーネル」と「ユーザランド」の2つの領域に分かれる

**カーネル**

- OSの中核となる部分で、ハードウェアと直接やりとりするなどもっとも中心的な機能を受け持つ部分
- ハードウェアの違いを吸収して、プログラムがどのようなハードウェア上でも同じように動作する役割



**ユーザランド**

- OSが動作するのに必要な、カーネル以外の部分のこと。
- ファイルシステムやファイル操作コマンド、シェルなど基本的なソフトウェア群を指す



### Linuxを使う

- Linuxは基本的にはコマンドで操作する
- コマンドはユーザランドで動作する
- X Window SystemとGNOME、KDE、Xfceなどのデスクトップ環境を導入することでマウス入力可能に



### シェル

- Linuxにはシェルという対話型のコマンド入力環境が用意されている
- シェルは入力されたコマンドを理解し、実行する



## ディストリビューション

### ディストリビューション

- Linuxを使う上で必要なプログラムをまとめ、簡単にインストール→ディストリビューションの始まり