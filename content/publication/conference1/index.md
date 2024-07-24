---
title: 'FairViT: Fair Vision Transformer via Adaptive Masking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bowei Tian
  - Ruijie Du
  - Yanning Shen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-07-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision (ECCV 2024)*
publication_short: In European Conference on Computer Vision (ECCV 2024)

abstract: Vision Transformer (ViT) has achieved excellent performance and demonstrated its promising potential on various computer vision tasks. The wide deployment of ViT in real-world tasks requires a thorough understanding of the societal impact of the model. However, most ViTs do not take fairness into account and existing fairness-aware algorithms designed for CNNs do not perform well on ViT. It is necessary to develop a new fair ViT framework. Moreover, previous works typically sacrifice accuracy for fairness. Therefore, we aim to develop an algorithm that improves fairness without sacrificing accuracy too much. To this end, we introduce a novel distance loss, and deploy adaptive fairness-aware masks on attention layers to improve fairness, which are updated with model parameters. Experimental results show the proposed methods achieve higher accuracy than alternatives, 6.72% higher than the best alternative while reaching a similar fairness result.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Vision Transformer, Accuracy, Fairness, Adaptive Masking]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2407.14799'
url_code: 'https://github.com/abdd68/Fair-Vision-Transformer'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
