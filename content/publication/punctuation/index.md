---
title: "Towards better subtitles: A multilingual approach for punctuationrestoration of speech transcripts"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Ricardo Rei
- Fernando Baptista

date: "2020-05-12T00:00:00Z"
doi: "https://doi.org/10.1016/j.eswa.2021.115740"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Expert Systems with Applications
publication_short: In *Expert Systems with Applications*

abstract: This paper proposes a flexible approach for punctuation prediction that can be used to produce state-of-the-artresults in a multilingual scenario. We have performed experiments using transcripts of TED Talks from theIWSLT 2017 and IWSLT 2011 evaluation campaigns. Our experiments show that the recognition errors of theASR output degrade the performance of our models, in line with related literature. Our monolingual modelsperform consistently in Human-edited transcripts of German, Dutch, Portuguese and Romanian, suggesting thatcommasmay be more difficult to predict thanperiods, using pre-trained contextual models. We have trained asingle multilingual model that predicts punctuation in multiple languages that achieves results comparable withthe ones achieved by monolingual models, revealing evidence of the potential of using a single multilingualmodel to solve the task for multiple languages. Then, we argue that usage of current punctuation systemsin the literature are implicitly dependent on correct segmentation of ASR outputs for they rely on positionalinformation to solve the punctuation task. This is too big of a requirement for use in a real life application.Through several experiments, we show that our method to train and test models is more robust to differentsegmentation. These contributions are of particular importance in our multilingual pipeline, since they avoidtraining a different model for each of the involved languages, and they guarantee that the model will be morerobust to incorrect segmentation of the ASR outputs in comparison with other methods in the literature. Tothe best of our knowledge, we report the first experiments using a single multilingual model for punctuationrestoration in multiple languages

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0957417421011180'
url_code: 'https://github.com/Unbabel/caption'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
