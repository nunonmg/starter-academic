---
title: "IST-Unbabel 2021 Submission for the Explainable Quality Estimation Shared Task"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Marcos V. Treviso
- admin
- Ricardo Rei
- André F. T. Martins

date: "2021-11-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the Proceedings of the 2nd Workshop on Evaluation and Comparison of NLP Systems
publication_short: In *EMNLP | Eval4NLP*

abstract: We present the joint contribution of Instituto Superior Técnico (IST) and Unbabel to the Explainable Quality Estimation (QE) shared task, where systems were submitted to two tracks - constrained (without word-level supervision) and unconstrained (with word-level supervision). For the constrained track, we experimented with several explainability methods to extract the relevance of input tokens from sentence-level QE models built on top of multilingual pre-trained transformers. Among the different tested methods, composing explanations in the form of attention weights scaled by the norm of value vectors yielded the best results. When word-level labels are used during training, our best results were obtained by using word-level predicted probabilities. We further improve the performance of our methods on the two tracks by ensembling explanation scores extracted from models trained with different pre-trained transformers, achieving strong results for in-domain and zero-shot language pairs.


tags: []

show_date: true


# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2021.eval4nlp-1.14.pdf'
url_code: 'https://github.com/deep-spin/explainable_qe_shared_task/ '
---

