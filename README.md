# EnrollmentSelector

Enrollment Selectorは、大学生向けの講義推薦アプリです。
過去の履修科目や成績などを基に、ユーザーに最適な講義を提案します。

## **主な機能**
- 履修済みの授業内容を基に、ユーザーの興味にあった新しい講義を推薦します。
- **段階的なフィルタリング**
    - 推薦された講義を、担当教員や成績評価法（試験重視、レポート重視など）、開講年次に応じて絞り込むことが可能です。
- **ランキング表示**
    - 類似度スコアやフィルタリング条件を考慮し、トップ10のオススメ講義をランキング形式で表示します。

---

## **特徴**
- **コンテンツベースの推薦システム**
    - TF-IDF + コサイン類似度を使い、授業内容に基づいたパーソナライズされた講義提案が可能
- **学習済みモデルとシラバスデータの結合**
    - 学習用データセットをcsv形式で管理し、簡単にアップデート可能。
- **直感的なフィルタリング**
    - ユーザーの好みや履修条件にあった授業を見つけることができます。