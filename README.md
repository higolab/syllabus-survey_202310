# 大学におけるプログラミング教育のシラバス調査

## 1. 各講義のシラバスURL

シラバスデータの収集対象としたプログラミング講義の一覧です（学科数: 58，講義数: 316）．学科名・講義名・シラバスのリンクを確認できます．

- [`lecture_syllabus_url.csv`](./data/lecture_syllabus_url.csv)

ラベルの説明

- `学科名` : その講義が開講される学科
- `講義名` : その講義の名称
- `シラバスURL` : その講義のシラバスのリンク
  - リンクにアクセスしても個別のシラバス画面に遷移しない（トップページ等が表示される）場合は，別途講義名で検索のうえ閲覧していただく必要があります．

## 2. 単元の一覧

シラバスデータを分析した結果得られた，プログラミング単元の一覧です．

- [`programming_learning_units.md`](./data/programming_learning_units.md)

## 3. 単元の対応状況

各講義・学科と単元のマッチングにより得られたデータです．単元のカテゴリでファイルを分けています．ある講義（学科）が対応する単元を個別に確認できます．

### 講義

- カテゴリ1: [`lecture_matched_units_category1.csv`](./data/lecture_matched_units_category1.csv)
- カテゴリ2: [`lecture_matched_units_category2.csv`](./data/lecture_matched_units_category2.csv)
- カテゴリ3: [`lecture_matched_units_category3.csv`](./data/lecture_matched_units_category3.csv)

ラベルの説明

- `学科名` : その講義が開講される学科
- `講義名` : その講義の名称
- それ以外のラベル : 単元の名称
  - 値が `0` の場合は「対応なし」，`1` の場合は「対応あり」を表します．

### 学科

- カテゴリ1: [`department_matched_units_category1.csv`](./data/department_matched_units_category1.csv)
- カテゴリ2: [`department_matched_units_category2.csv`](./data/department_matched_units_category2.csv)
- カテゴリ3: [`department_matched_units_category3.csv`](./data/department_matched_units_category3.csv)

ラベルの説明

- `学科名` : その学科の名称
- それ以外のラベル : 単元の名称
  - 値が `0` の場合は「対応なし」，`1` の場合は「対応あり」を表します．

## 4. 単元カバー率

以下4種のドメインについて，各講義・学科に対応する単元がドメイン内に占める割合（単元カバー率）を算出した結果です．カテゴリごとにみた単元対応の分布等を確認できます．

- `カテゴリ1`: カテゴリ1の単元
- `カテゴリ2`: カテゴリ3の単元
- `カテゴリ3`: カテゴリ2の単元
- `全体`: 全カテゴリの単元

### 講義

- [`lecture_cover_rate.csv`](./data/lecture_cover_rate.csv)

ラベルの説明

- `学科名` : その講義が開講される学科
- `講義名` : その講義の名称
- それ以外のラベル : ドメインの名称
  - 値は単元カバー率を表します．

### 学科

- [`department_cover_rate.csv`](./data/department_cover_rate.csv)

ラベルの説明

- `学科名` : その学科の名称
- それ以外のラベル : ドメインの名称
  - 値は単元カバー率を表します．
