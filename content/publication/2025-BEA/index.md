---
title: 'Instruction-tuned QwenChart for Chart Question Answering'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Viviana Ventura
  - Lukas Kleybolte
  - admin

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-07-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 5th Workshop on Scholarly Document Processing*'
publication_short: '*SDProc*'

abstract: Charts, where information is delivered holistically by visual and textual features, represent a challenge when it comes to downstream tasks such as chart question answering, where both kinds of information contribute to the task. The standard approach is to decouple the task in two steps, first extracting information from the charts, or representing it as a table, text or code, and then a second reasoning step to output the answers. Today, the advancements in visual encoding of Visual Large Language Models (VLLM) have shown their capabilities to solve such complex tasks without using inbetween representations of the charts or massive in-domain training. Our new instruction fine-tuned and chain-of-thought model Qwen-Chart showed that even in a complex new benchmark such as SciVQA general models can achieve great performances with low-cost training, matching the capabilities that LLMs have showed in unimodal downstream tasks. An out-of-domain evaluation showed satisfactory results, albeit with an expected drop in performance.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- QA
- data-centric
- evaluation
- industrial NLP
- applied NLP
- multimodal LLMs

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'Teach4NLP_poster.pdf'
url_project: ''
url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" # example
---
