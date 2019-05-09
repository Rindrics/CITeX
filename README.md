# CITeX

ドキュメントの CI & CD 化を図り，業務を効率化する

## 対象とするドキュメント
以下の特徴のいずれかに当てはまる文書
- 複数人で執筆する
- 毎年発行される
- 見出しがある

## 計画

https://github.com/kikirinrin/CITeX/projects を参照

## 使い方
### Docker のインストール

### 実行
`./manuscript.txt` を編集

#### Windows users
``` sh
docker-compose run --rm latexmk manuscript.tex

# How to open file in Windows env???
```
#### OSX & Linux users
``` sh
docker-compose run --rm latexmk manuscript.tex && open manuscript.pdf

```
