# Deep Texture and Structure Aware Filtering Network for Image Smoothing
## 著者
Kaiyue Lu, Shaodi You, Nick Barnes

## 何のための研究？
画像平滑化

## 従来のアプローチとその問題点は？
従来手法は大きく分けて２つ
- カーネルベース
- 分離ベース

従来のアプローチは特徴づけや事前情報に大きく依存しており，ロバスト性が低い．

## この論文ではどういうアプローチで問題を解決する？
テクスチャ画像と構造画像のガイダンス画像を予測するためのフィルタをDNNベースで学習．  
それらのガイダンス画像を用いて平滑化モデルを学習．

## この論文の主定理，もしくは鍵となる式・図は？（最大2個まで）
![fig](https://user-images.githubusercontent.com/60766744/110233772-af0b9e80-7f69-11eb-8429-94a05d3f1dab.png)

## この論文で何が出来るようになった？and/or 何が良くなった？　

## 実験と評価方法
データセット

## この論文の問題点や課題は？

## 実装はある？
https://github.com/JiaBob/TSAFN  
コードはあったけど，**データセットは論文見ながら自分で用意してね**とのこと．
