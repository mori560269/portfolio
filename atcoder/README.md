# AtCoder 解答コード

AtCoder で解いた問題のコードを置く場所です。
ここに置いたファイルは、ポートフォリオの [AtCoder ページ](https://mori560269.github.io/portfolio/atcoder.html) に自動で一覧表示されます。

## 置き方

コンテストごとにフォルダを作り、問題ごとに 1 ファイルにします。

```
atcoder/
├── abc380/
│   ├── a.cpp
│   ├── b.cpp
│   └── c.py
├── arc188/
│   └── a.cpp
└── ahc040/
    └── main.cpp
```

- フォルダ名：コンテスト ID（URL の `https://atcoder.jp/contests/abc380` の `abc380` の部分）
- ファイル名：問題の記号（`a`、`b`、…）＋ 拡張子（`.cpp`、`.py` など）
- ファイル名をこの形にすると、一覧ページから問題ページへのリンクが自動で付きます。

## 追加のしかた

**GitHub の画面から**
1. このリポジトリで **Add file → Create new file** を開く
2. ファイル名に `atcoder/abc380/a.cpp` のように入力する（`/` を打つとフォルダになります）
3. コードを貼り付けて **Commit changes**

**ローカルから**
```bash
mkdir -p atcoder/abc380
# a.cpp を保存してから
git add atcoder && git commit -m "ABC380 A" && git push
```

push してから 1 分ほどで、ポートフォリオの一覧に反映されます。
