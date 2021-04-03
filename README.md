# Basic-Visualization
* 基本的な可視化手法

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
├── notebook                  jupyter notebook
└── data                      dataファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Basic-Visualization）
```
cd Desktop/Basic-Visualization
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Basic_Visualization）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Basic_Visualization.ipynb : 基本的な可視化手法のnotebook
* Basic_Visualization_xkcd.ipynb : 基本的な可視化手法（xkcd風）のnotebook
* matplotlib_recipe.ipynb : matplotlibの可視化手法のnotebook
* seaborn_recipe.ipynb : seabornの可視化手法のnotebook
* plotly_recipe.ipynb : plotly, plotlyexpressの可視化手法のnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
