# 絶対のルール

**ブランチを作るな。** 必ず `main` に直接コミット・pushする（todoアプリと同じ）。

## このアプリについて

国際子ども図書館で『サンチャイルド・ビッグサイエンス』を出納する時の、読んだ号のチェック表。`index.html` 一枚。
Firebase は todoアプリと同じプロジェクト（todo-mutsuki-ea166）。データは Firestore の `bigsci/suitou` の `marks`（{"巻-号": "読んだ日 YYYY-MM-DD"}）。ルールはムツキ本人だけ。
公開先は GitHub Pages：https://mutsukigit762.github.io/bigsci-suitou/
号の一覧と回分けは `index.html` の `ISSUES`。元の表は `~/claude/dokusho/ビッグサイエンス出納リスト.md`。
