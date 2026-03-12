---
title: "コードメトリクスに着目した種類ごとの行単位バグ予測への影響調査"
authors:
- h-hashimoto
date: "2026-02-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-02-13"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 従来のバグ予測にはファイルやメソッド単位の手法があるが，バグが含まれるファイル内でも実際のバグ行はごく一部（1.2〜2.5\%）であり，箇所の特定には依然として多大な労力がかかるという課題がある．本研究では，この課題を解決するために提案された行単位バグ予測に着目し，バグの発生原因に基づいて16種類に分類されるSimple Stupid Bugs（SStuBs）を対象として，既存手法の改良とバグの種類別分析を行っている．バグ予測の基盤手法として，軽量な行単位バグ予測手法であるGLANCEを採用した．GLANCEは，トークン数（NT）や関数呼び出し数（NFC）による複雑度と，制御構造の有無（CE）を指標とする手法だが，本研究ではこれらに加え，バグの発生原因に関連が深いと考えられるリテラル数（NL）と演算子数（NOP）を新たなメトリクスとして導入した．これらを組み合わせた12通りの計算条件を設定し，80のオープンソースプロジェクトから成るデータセットManySStuBs4Jの計8,774個のバグ修正コミットを用いて評価実験を行った．調査結果として，まず全体の予測精度（RQ1）については，CE以外の全メトリクス（NT, NFC, NL, NOP）を採用した条件が最も高い性能を示した．メトリクスの変更による全体的な精度向上は顕著ではなかったが，上位20\%の検査でバグを発見できる割合（Recall@20\%）など，バグ行を上位に順位付けする性能において改善が見られた． 次に，バグの種類別精度（RQ2）では，メトリクス構成によって予測の得意・不得意が分かれることが判明した．例えば，リテラル数や演算子数を使用する場合，CEの有無は予測精度にほとんど影響しないことが示唆された．また，リテラルの誤りや関数名の誤りなどに関連した種類のバグでは，トークン数（NT）を除外して他のメトリクスの影響を強めた方が検出率が向上する傾向があった一方で，修飾子の変更などのバグではNTを用いることで性能が維持されることが分かった．結論として，単一の指標ですべてのバグを網羅的に捉えることは難しく，特定のバグ種別に特化した検出を行うには，メトリクスへの適切な重み付けなど精緻な設計が必要であることが示された．今後は，構造的特徴に加えてプロセスメトリクスなどの新たな指標を導入することが課題として挙げられる．

# Summary. An optional shortened abstract.
#summary: 
tags:
- 卒業論文
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

 
