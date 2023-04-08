# Overview

This repository contains Musashino Art University's syllabus data extracted and stored in JSON format. It is intended to make syllabus data more easily accessible to developers and students. Since this is unofficial data, please use it at your own risk.

このリポジトリには、武蔵野美術大学のシラバスデータを、JSON形式で抽出・保存したものが保管されています。シラバスデータを開発者や学生がより簡単にアクセスできるようにするためのものです。非公式のデータであるため、利用にあたっては自己責任でお願いします。

## Data Structure

The JSON data is organized as follows:

JSONデータは以下のように構成されています：

```json
{
    "科目名": "科目名が入ります",
    "講義名": "講義名が入ります",
    "サブタイトル": "「前期」「後期」などの情報が入ります",
    "受講可能学科": "対象となる学科名が入ります",
    "担当研究室": "担当となる研究室の記載が入ります",
    "担当教員": "担当教員名が入ります",
    "クラス": "クラスの番号が入ります",
    "教育課程": "教育課程についての記載が入ります",
    "分野": "分野が入ります",
    "科目群": "科目群が入ります",
    "学年": "学年が入ります",
    "キャンパス区分": "キャンパス名が入ります",
    "開講期間": "「通年 2023/4/10-2023/12/23」のような形で期間が入ります",
    "曜日・時限": "曜日や時限の記載が入ります",
    "科目種別": "科目種別が入ります",
    "ナンバリング": "ナンバリングが入ります",
    "単位数": "単位数が入ります",
    "履修条件": "履修条件が入ります",
    "備考": "備考が入ります",
    "授業概要・カリキュラム上の位置づけ": "ここに授業概要・カリキュラム上の位置づけに関する説明が入ります",
    "到達目標": "ここに到達目標についての記載が入ります",
    "ディプロマポリシーとの関連": "ディプロマポリシーとの関連についての記載が入ります",
    "授業計画・課題に対するフィードバック": "ここに週ごとの授業計画や、課題へのフィードバックの説明が入ります",
    "履修上の留意点": "履修上の注意点についての記載が入ります",
    "準備学習内容・時間の目安": "ここに、準備学習などの講義時間外の学習に関する説明が入ります",
    "成績評価の方法": "単位認定の規定の原則や、評価方法についての説明が入ります",
    "テキスト": "書籍やテキストについての説明が入ります",
    "テキストISBN番号": "テキストISBN番号が入ります",
    "参考文献(作品）等": "参考文献の情報が入ります",
    "教員との連絡方法（オフィスアワー）": "オフィスアワーなどについての説明が入ります",
    "リンク1": "リンク1が入ります",
    "リンク2": "リンク2が入ります"
}
```

## Usage

You can use the JSON data in this repository to develop applications, parse syllabus data, or integrate data into other projects.

このリポジトリのJSONデータを使用して、アプリケーションの開発、シラバスデータの解析、または他のプロジェクトへのデータの統合を行うことができます。

## Disclaimer

- This information is for reference only and we do not guarantee its accuracy or completeness.
- We assume no responsibility for any actions taken or results obtained using this information.
- Any decisions or judgments made based on the Information are the sole responsibility of the user.
- We assume no responsibility for any problems that users may encounter with third parties in connection with the Information.
- We reserve the right to change the contents of this information without prior notice. Please be aware of this beforehand.
We assume no responsibility whatsoever for any damages resulting from the use of this information.


- 本情報はあくまでも参考情報であり、その正確性・完全性について保証するものではありません。
- 本情報を用いて行う一切の行為及びその結果について、当方は一切の責任を負いかねます。
- 本情報に基づいて行う判断や決定については、必ず自己の責任において行ってください。
- 本情報に関連して利用者が第三者とトラブル等を起こした場合でも、当方は一切の責任を負いません。
- 当方は本情報の内容を予告なしに変更する場合があります。予めご了承ください。
本情報の利用によって生じた損害について、当方は一切の責任を負いません。
