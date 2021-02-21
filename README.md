# OffRoad-Challenge
オフロードでは、公道での自動運転等とは異なり、詳細な三次元地図や路車間通信等のインフラを利用することができません。そのため、オフロードでの自律走行のためには、周辺の環境について、走行できる領域や障害物を高精度かつ高速に認識することが重要です。
そこで、オフロード環境等の実走行で得られた画像を領域分割するアルゴリズムを作成し、認識精度と推論速度を競うコンテストを開催します。

## コンペ概要

オフロード画像をピクセル単位で４クラスに分類するセマンティックセグメンテーションが課せられた課題です。４クラスの内訳はroad,dirt road,other obstacle,それ以外です。
