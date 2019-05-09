# CITeX

ドキュメントの CI & CD 化を図り，業務を効率化する

## 対象とするドキュメント
以下の特徴のいずれかに当てはまる文書
- 複数人で執筆する
- 毎年発行される
- 見出しがある

## 計画
まずは小規模なもの，例えば漁海況予報業務のようなものから試す．

### 導入の順序

## 使い方
### Docker のインストール

### 実行
``` sh
cd tmp/
docker run -d --rm -it -w=/root -v $PWD:/root eisoku9618/kuroiwa_dockefiles_for_latexmk /bin/bash -c "latexmk -pvc manuscript.tex"
open .tmp/manuscript.pdf
```
Then write & update `tmp/manuscript.txt`
