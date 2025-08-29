\# データの取り扱いについて



本リポジトリでは、Kaggle の「User Anime Dataset」を使用しています。  

ライセンスは \*\*CC BY 4.0\*\* で配布されています。



\- 出典: \[Kaggle — User Anime Dataset](https://www.kaggle.com/datasets/tavuksuzdurum/user-animelist-dataset)  

\- ライセンス: CC BY 4.0 (Creative Commons Attribution 4.0 International)



\## データ取得方法



1\. Kaggleの該当ページにアクセス  



2\. 右上の「Download」アイコンをクリックし、「Download dataset as zip (2GB)」をクリック 



3\. ジップファイルを解凍し、data/rawフォルダに移動します



\## 想定されるディレクトリ構成



```

data/

├─ raw/ # Kaggleから取得した生データ

│ ├─ animes.csv

│ └─ ratings.csv

├─ processed/ # 前処理後のデータ

└─ README.md # このファイル

```

※「animes.csv」、「ratings.csv」以外にもファイルが含まれていますが、本分析では使用しなかったため省略します。



\## ファイル概要



\- \*\*animes.csv\*\*
  
　- animeID (アニメID)

  - title (作品のタイトル)

  - alternatrive_title (作品の副タイトル)

　- year (発表された年)

　- episodes (エピソード数)

　- type (発表された形式。テレビアニメ、映画等)

　- score (投稿された評価の平均点)

　- sequel (続編か否か)

　- image_url (アニメのビジュアルイメージのurl)

　- mal_url (該当作品のレビューページ)

　- genres(ジャンル)

　- genres_detailed (詳細ジャンル)  





\- \*\*ratings.csv\*\*  

　- userID (ユーザーID)

　- animeID (アニメID)

　- rating (実際に投稿された評価点。1-10)




\## 注意事項

\- \*\*本リポジトリにはデータそのものは含まれていません。\*\*  

\- データ利用時は Kaggle のライセンス条件に従ってください。  

\- 大規模データのため、処理には十分なメモリ（例: 8GB以上）を推奨します。  











