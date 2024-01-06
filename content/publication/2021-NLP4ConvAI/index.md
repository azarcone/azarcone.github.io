---
title: "Not So Fast, Classifier – Accuracy and Entropy Reduction in Incremental Intent Classification"
authors:
- Lianna Hrycyk
- admin
- Luzian Hahn
date: "2021-11-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 3rd Workshop on Natural Language Processing for Conversational AI*'
publication_short: '*NLP4ConvAI*'

abstract: Incremental intent classification requires the assignment of intent labels to partial utterances. However, partial utterances do not necessarily contain enough information to be mapped to the intent class of their complete utterance (correctly and with a certain degree of confidence). Using the final interpretation as the ground truth to measure a classifier’s accuracy during intent classification of partial utterances is thus problematic. We release inCLINC, a dataset of partial and full utterances with human annotations of plausible intent labels for different portions of each utterance, as an upper (human) baseline for incremental intent classification. We analyse the incremental annotations and propose entropy reduction as a measure of human annotators’ convergence on an interpretation (i.e. intent label). We argue that, when the annotators do not converge to one or a few possible interpretations and yet the classifier already identifies the final intent class early on, it is a sign of overfitting that can be ascribed to artefacts in the dataset.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- crowdsourcing
- data-centric
- human upper bound
- incremental intent classification
- incremental processing
- Information Density
- Information Theory
- NLU

featured: true

links:
- name: ACL Anthology
  url: https://aclanthology.org/2021.nlp4convai-1.6/
url_pdf: 'https://aclanthology.org/2021.nlp4convai-1.6.pdf'
url_code: ''
url_dataset: 'http://dx.doi.org/10.24406/fordatis/140'
url_poster: 'NLP4ConvAI_poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  #focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
- speaker
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

---
