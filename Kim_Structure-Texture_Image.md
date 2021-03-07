# Structure-Texture Image Decomposition Using Deep Variational Priors

## 著者
  Youngjung Kim, Bumsub Ham, Minh N. Do, Kwanghoon Sohn

## 何のための研究？
画像の構造-テクスチャ分離

## 従来のアプローチとその問題点は？
構造成分の特徴づけにはtotal variation がよく使われているが，エッジと高コントラストな
テクスチャとの区別が難しい．  
fig.1ではエッジがボケてしまっていたり，テクスチャを取り残してしまっていることがわかる．

![fig.1](https://user-images.githubusercontent.com/60766744/110082748-222ddd00-7dd1-11eb-9813-6019ff4f41bd.png)


## この論文ではどういうアプローチで問題を解決する？
構造画像 **u** のアップデートステップをノイズ除去ステップとみなし(式(9))，写像P(・,θ)を学習する．

構造成分の特徴づけをTVではなく事前に学習したモデルに置き換える．


## この論文の主定理，もしくは鍵となる式・図は？（最大2個まで）

![9](https://user-images.githubusercontent.com/60766744/110242542-e2662180-7f99-11eb-9f36-4d2eed53d2f3.png)

損失関数はL1

![11](https://user-images.githubusercontent.com/60766744/110242825-1aba2f80-7f9b-11eb-9a95-dea21ae4e394.png)

## この論文で何が出来るようになった？and/or 何が良くなった？　


## 実験と評価方法


## この論文の問題点や課題は？


## 実装はある？
未発見
