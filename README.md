# Kaggle Competitionに初日から参加
# [Riiid! Answer Correctness Prediction](https://www.kaggle.com/c/riiid-test-answer-prediction)


## 概要
kaggleコンペ初の本格参戦で、メダル圏で競い合い、コミュニティーへの貢献が可能か。

- コンペ種類：テーブルデータコンペ
- コンペ開始日：2020年10月06日
- コンペ終了日：2021年01月08日

## 結論
投稿したNotebookが2個のメダルを獲得し、そこから派生したNotebookが複数件([こちら](https://www.kaggle.com/johannesbruch/focus-on-important-features)と[こちら](https://www.kaggle.com/mamun18/riiid-lgbm-lii-hyperparameter-tuning-optuna))登場した事から、\
一定の貢献をする事ができたものと考えられる。

また、メダル圏で競い合うという目標もシルバーメダルからブロンズメダル圏の順位で推移している事から、\
一定のレベルで競い合う事ができたものと考えられる。\
リーダーボードの順位については、2個目のメダルを獲得したNotebookが投稿時に停滞していた最高スコアを上回るものを提供した事から、\
そのNotebookを投稿していなければより高い水準を保っていたものと考える。

## リポジトリ構造
```
.
├── code
│   ├── Riiid_Overview_and_Data.ipynb
│   ├── Riiid_EDA.ipynb
│   ├── lgbm-iii-part2.ipynb
│   └── lgbm-iii-part3-adding-lecture-features.ipynb
├── .gitignore
├── LICENSE
├── README.md
```

## データセット
データセットの容量は、5.45GBある。\
当リポジトリには、データセットの格納はしておらず、下記ページにて直接、または、Kaggle APIによるダウンロードが可能である。\
データセットダウンロードページ：[こちら](https://www.kaggle.com/c/riiid-test-answer-prediction/data)

## Notebook Medal 2個獲得
1個目のブロンズメダルを獲得したNotebook: [LGBM III part2](https://www.kaggle.com/takamotoki/lgbm-iii-part2)

2個目のブロンズメダルを獲得したNotebook: [LGBM III part3 adding lecture features](https://www.kaggle.com/takamotoki/lgbm-iii-part3-adding-lecture-features)

## Requirements
当該コンペは、カーネルベースのコンペである。\
ファイルの提出は、Kaggleカーネルを通して行う必要がある。\
ローカルマシンからの提出は、当該コンペで許容されていない。
