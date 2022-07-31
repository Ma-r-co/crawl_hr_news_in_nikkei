# 🚀人事異動情報を収集するためのツールです

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Ma-r-co/crawl_hr_news_in_nikkei/main?labpath=crawl_hr_news_in_nikkei.ipynb)

免責事項:
当ツールによって生じた如何なるトラブル・損失・損害に対してもツール作成者は責任を負うものではないことを予めご了承ください。

## ⚙️ パラメータについて
|#|パラメータ名|とりえる値|説明|
|:--|:--:|:--:|:--|
|1|TARGET_DATE|'1'~'31'|収集対象の人事情報の掲載日|
|2|FI_WORDS|list[str]|企業が金融機関かどうかを判断するキーワード。この中のキーワードのいずれかが企業名に含まれていた場合に収集対象とする。|
|3|GRCS_WORDS|list[str]|人事異動情報の詳細を表示するかどうか判断するキーワード。この中のキーワードのいずれかが人事異動情報に含まれていた場合に、結果に企業名だけでなく人事異動情報の詳細を出力する。|

## 📖 使い方
1. パラメータ3つを適切な値に設定する
2. 実行
3. 最下部に結果が表示される

## 🔖 制約
- 当日更新分は取得不可
- 過去1−2週間程度のみ取得可能

## License
This project is licensed under the MIT License, see the LICENSE.txt file for details.