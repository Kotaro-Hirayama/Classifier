クラスタリング
=================

urlを投げると、その記事のカテゴリを返してくれる。  
SmartNewsやGunosyのようなキュレーションと同様のアルゴリズム。  

/dev/_verificationget  
- できるか不明だったので、検証のための殴り書きコード
- get_sample_data.py: 学習用データ収集のスクレイピングコード
- read.py: 学習及び予測のコード。（学習結果を保存はしてない）
- train_data.db: ちょっと収集してみたデータなので、気になった人は、これでどんなもんか見てみてね。

/dev/model
- _じゃないディレクトリにちゃんと整理中....（手が回ってない（白目
