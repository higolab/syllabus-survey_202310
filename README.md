# 大学におけるプログラミング教育のシラバス調査

## 各講義のシラバスURL

- [`lecture_syllabus_url.csv`](./lecture_syllabus_url.csv)

※ `シラバスURL` の列が空の場合は，HTML形式でシラバスが公開されていない講義です（PDFのダウンロードが求められる等）．

## 学習単元の対応状況

単元のカテゴリ単位でファイルを分けています．また，`学科名` と `講義名` を除く各列のラベルは単元の名称と対応しており，値が `0` の場合は「対応なし」，`1` の場合は@
対応あり」を表します．

### 講義

- カテゴリ1: [`lecture_matched_units_category1.csv`](./lecture_matched_units_category1.csv)
- カテゴリ2: [`lecture_matched_units_category2.csv`](./lecture_matched_units_category2.csv)
- カテゴリ3: [`lecture_matched_units_category3.csv`](./lecture_matched_units_category3.csv)

### 学科

- カテゴリ1: [`department_matched_units_category1.csv`](./department_matched_units_category1.csv)
- カテゴリ2: [`department_matched_units_category2.csv`](./department_matched_units_category2.csv)
- カテゴリ3: [`department_matched_units_category3.csv`](./department_matched_units_category3.csv)

## 学習単元のカバー率

`学科名` と `講義名` を除く各列のラベルはドメインを表し，講義（学科）と対応する単元がそのドメインにおいて占める割合が記載されています．ラベルとドメインの対応は以下の通りです．

- `カテゴリ1`: カテゴリ1の単元
- `カテゴリ2`: カテゴリ3の単元
- `カテゴリ3`: カテゴリ2の単元
- `全体`: 全カテゴリの単元

### 講義

- [`lecture_cover_rate.csv`](./lecture_cover_rate.csv)

### 学科

- [`department_cover_rate.csv`](./department_cover_rate.csv)
