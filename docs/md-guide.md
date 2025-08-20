# Markdown 入門ガイド

このページでは、Miniblox Wiki で使える Markdown の書き方を詳しく解説します。


ぜひ[こちら](https://hayato040404.github.io/markdown)でmarkdownを簡単に生成してみてください！！

---

## 1. 見出し

Markdown では `#` の数で見出しのレベルを指定できます。

```markdown
# 見出し1
## 見出し2
### 見出し3
```

結果:

# 見出し1

## 見出し2

### 見出し3

---

## 2. 強調

* **太字**: `**太字**` → **太字**
* *斜体*: `*斜体*` → *斜体*
* ~~取り消し線~~: `~~取り消し線~~` → ~~取り消し線~~

---

## 3. リスト

### 箇条書き（unordered list）

```markdown
- 項目1
- 項目2
  - サブ項目
```

* 項目1
* 項目2

  * サブ項目

### 番号付きリスト（ordered list）

```markdown
1. 項目1
2. 項目2
```

1. 項目1
2. 項目2

---

## 4. リンク

```markdown
[Google](https://www.google.com)
```

[Google](https://www.google.com)

---

## 5. 画像の挿入

```markdown
![代替テキスト](https://via.placeholder.com/150)
```

例:

![サンプル画像](https://via.placeholder.com/150)

> ⚠️ GitHub Pages ではリポジトリ内の画像も使えます
> 例: `![画像](images/pic1.png)`
> 画像は `docs/images/` フォルダに置くと管理しやすいです

---

## 6. 表（Table）

```markdown
| 名前 | レベル | HP |
|------|-------|----|
| A | 1 | 50 |
| B | 3 | 120 |
```

| 名前   | レベル | HP  |
| ---- | --- | --- |
| A | 1   | 50  |
| B | 3   | 120 |

---

## 7. コードブロック

### インラインコード

`` `ls -la` `` → `ls -la`

### 複数行のコードブロック

```bash
# コマンド例
git status
git add .
git commit -m "変更"
```

---

## 8. 引用

```markdown
> これは引用です
```

> これは引用です

---

## 9. 水平線

```markdown
---
```

---

## 10. 注意・ヒント

* 空白行を入れないと、リストや表が正しく表示されません
* 画像やリンクの URL は正しく入力してください
* コードブロックには言語を指定すると色付きで表示されます（例: `bash` や `python`）

---

## 11. 便利なTips

* 画像をリポジトリにアップ → `docs/images/` に保存 → Markdown で挿入
* ページ内リンク: `[このページの見出し](#見出し1)`
* GitHub 上で編集 → push で即反映

---


* [貢献する方法](contribute.md)

