# Adaptive Curvature-Guided Image Filtering for Structure + Texture Image Decomposition

## 著者
- Alexander Belyaev
- Pierre-Alain Fayolle

## 何のための研究？
画像の構造成分とテクスチャ成分の分離(テクスチャの抑制)

## 従来のアプローチとその問題点は？
#### 従来のアプローチ
構造成分：TV正則化  
テクスチャ成分：低ランク近似， 高周波成分であると仮定する　など  

#### 問題点
この論文では特に指摘はされていない  
個人的に思う問題点  
- 局所的なテクスチャに弱い  
- エッジが曖昧になる

## この論文ではどういうアプローチで問題を解決する？
主に2つのステップによって構成されている．  

1. TV項に, 入力画像のレベルセット曲率にローパスフィルタを適用したものを追加
2. 1の結果からパラメータを学習し決定する

## この論文の主定理，もしくは鍵となる式・図は？（最大2個まで）
![](https://github.com/hiran0/images/blob/master/main_f2.png)
![](https://github.com/hiran0/images/blob/master/main_f11.png)

## この論文で何が出来るようになった？and/or 何が良くなった？　
- エッジを保存しながらテクスチャの抑制に成功
- 高周波成分のテクスチャにも対応

## 実験と評価方法
![](https://github.com/hiran0/images/blob/master/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202020-06-16%200.31.12.png)


![](https://github.com/hiran0/images/blob/master/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%202020-06-16%200.31.29.png)
## この論文の問題点や課題は？
特に言及されていない

## 実装はある？

