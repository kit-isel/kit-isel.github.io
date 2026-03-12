---
title: 'オープンソースソフトウェアでのChatGPT提案コードの再利用動向分析'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - s-miyanaga
  - e-choi
  - 西浦 生成
  - 水野 修

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-06-01'
doi: 'https://doi.org/10.60241/ssproceedings.202406.0_22'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ソフトウェアシンポジウム2024論文集, pp.22-31
#publication_short: In *ICW*

abstract: ChatGPTのような大規模な言語モデルの登場は，ソフトウェア開発の状況を一変させた．ソフトウェア開発における ChatGPTの利用は普及しており，GitHub上のオープンソースプロジェクトにおいては，ChatGPTを使用して提案されたコードを再利用している場合がある．本研究では，ソフトウェア開発におけるChatGPTの利用動向を明らかにする．具体的には，まず，ChatGPTが提案したコードは開発者によってどのように再利用されているかを，次に，開発者は ChatGPTが提案したコードを再利用するまでにどの程度の回数 ChatGPTと会話しているかを調査した．調査の結果，ChatGPTが提案したコードは開発者によって再利用される際，修正せず再利用されることが最も多く，次に，コードの機能的な修正をして再利用されることが多いとわかった．また，開発者は ChatGPTが提案したコードを再利用するまでに，複数回ChatGPTと会話していることが多いとわかった．さらに，その会話回数は，修正せず再利用するとき，少なくなる傾向にあり，機能的な修正をして再利用するとき，多くなる傾向にあるとわかった．

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
