# Miniblox Wiki に貢献する方法

このページでは、誰でも安全に Miniblox Wiki に情報を追加・編集できる方法を詳しく解説します。

---

## 1. GitHub アカウントを作成

1. [GitHub](https://github.com/) にアクセス
2. 「Sign up」からアカウントを作成
3. メール認証とユーザー名設定を完了

> ⚠️ Wiki への貢献には GitHub アカウントが必要です

---

## 2. リポジトリをフォークする（Fork）

1. [Miniblox Wiki リポジトリ](https://github.com/username/miniblox-wiki) にアクセス
2. 右上の「Fork」ボタンをクリック
3. 自分のアカウントにコピーが作られます

---

## 3. Markdown を編集する方法

### ① GitHub 上で直接編集（初心者向け）

1. フォークしたリポジトリを開く
2. `docs/` フォルダから編集したいファイルをクリック
3. ペンのアイコン（✏️）をクリック
4. Markdown を編集
5. 「Commit changes」で変更を保存

### ② ローカルで編集（慣れてきたら）

```bash
# リポジトリをクローン
git clone https://github.com/username/miniblox-wiki.git
cd miniblox-wiki

# ファイルを編集
nano docs/play/index.md

# 変更をステージしてコミット
git add docs/play/index.md
git commit -m "遊び方ページ更新"

# フォーク先リポジトリに push
git push origin main

---

## 4. 画像やスクリーンショットの追加

1. `docs/images/` フォルダを作成（まだなければ）
2. 画像ファイルをアップロード
3. Markdown に挿入

```markdown
![画像説明](images/sample.png)
```

* 表示例:
  ![サンプル画像](https://via.placeholder.com/150)

> ⚠️ URL ではなく、リポジトリ内の画像を使うと安定します

---

## 5. 表の追加方法

```markdown
| 名前 | コイン | レベル |
|------|-------|----|
| A | 1 | 50 |
| B | 3 | 120 |
```

| 名前   | コイン | レベル  |
| ---- | --- | --- |
| A | 1   | 50  |
| B | 3   | 120 |

---

## 6. ページ内リンクや見出しリンク

* ページ内リンク: `[このページの見出し](#見出し名)`
* 別ページリンク: `[キャラクター一覧](characters/index.md)`

---

## 7. 変更を提案する（Pull Request）

1. 編集が完了したら GitHub で「Pull Request」を作成
2. 元リポジトリの `main` に対して変更を提案
3. レビュー後、Wiki に反映されます

> ⚠️ PR を使うことで、荒らしを防ぎつつ安全に誰でも貢献可能です

---

## 8. Markdown の便利Tips

* コードブロックは言語指定で色付き表示

```bash
git status
```

* 引用は `>` で書く
* 箇条書き・番号リストで整理
* 画像やリンクは必ず正しいパスを使う

---

## 9. 最後に

* 小さな修正でも Wiki の改善になります
* 分からない場合は PR の説明に「初心者なのでチェックお願いします」と書くと安心
* まずは Markdown ガイド（[md-guide.md](md-guide.md)）を見ながら編集すると簡単です


