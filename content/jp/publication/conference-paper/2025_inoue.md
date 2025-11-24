---
title: 'コメントに着目したLLM生成コードの検出精度の比較調査'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- t-inoue
- e-choi

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-11-06'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-06'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 第32回ソフトウェア工学の基礎ワークショップ(FOSE2025) 
#publication_short: In *ICW*

abstract: LLM生成コードには，人間が書いたコードとは異なる特徴が現れる可能性がある．特に，LLMが生成した自然言語文には，人間が書いた文とは異なる特徴があることが知られているため，コード中のコメントにもLLM特有の特徴が表れている可能性がある．しかし，LLM生成コードの検出においてファインチューニングに用いられているデータ中のコメントの有無が検出精度に与える影響については調査した既存研究は，我々が知る限り存在しない．そこで本研究では，LLMを用いたLLM生成コード検出において，ファインチューニングに用いるデータに含まれるコメントの有無が検出精度にどのように影響をするかを調査した．具体的には，T5，CodeT5，BERT，GraphCodeBERTの4つのLLMを用い，コメントの有無が異なるPythonコードデータセットを用いてファインチューニングおよび評価を行った．その結果，コメントを含むデータでファインチューニングしたLLMは，コメントを含むコードに対しては高い検出精度を示した一方で，コメントを含まないコードに対しては検出精度が著しく低下することが確認された．また，コメントを含まないデータでファインチューニングしたLLMは，コメントの有無にかかわらず安定して高い検出精度を示した．

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [国内会議, 日本語]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
