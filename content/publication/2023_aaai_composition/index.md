---
title: 'Infusing Definiteness into Randomness: Rethinking Composition Styles for Deep Image Matting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - "In Proceedings of AAAI Conference on Artificial Intelligence (AAAI 2023)"
# authors:
#   - "Zixuan Ye"
#   - "Yutong Dai"  
  # - [Yutong Dai](),
  # [Chaoyi Hong](https://scholar.google.com/citations?user=N9YzPMcAAAAJ&hl=zh-CN),
  # [Zhiguo Cao](https://scholar.google.com.sg/citations?user=396o2BAAAAAJ&hl=zh-CN),
  # [Hao Lu](https://sites.google.com/site/poppinace/)
  # ’
  



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of AAAI Conference on Artificial Intelligence (AAAI 2023)

abstract: We study the composition style in deep image matting, a notion that characterizes a data generation flow on how to exploit limited foregrounds and random backgrounds to form a training dataset. Prior art executes this flow in a completely random manner by simply going through the foreground pool or by optionally combining two foregrounds before foreground-background composition. In this work, we first show that naive foreground combination can be problematic and therefore derive an alternative formulation to reasonably combine foregrounds. Our second contribution is an observation that matting performance can benefit from a certain occurrence frequency of combined foregrounds and their associated source foregrounds during training. Inspired by this, we introduce a novel composition style that binds the source and combined foregrounds in a definite triplet. In addition, we also find that different orders of foreground combination lead to different foreground patterns, which further inspires a quadruplet-based composition style. Results under controlled experiments on four matting baselines show that our composition styles outperform existing ones and invite consistent performance improvement on both composited and real-world datasets. 

summary: Zixuan Ye, [Yutong Dai](https://dongdong93.github.io/), [Chaoyi Hong](https://scholar.google.com/citations?user=N9YzPMcAAAAJ&hl=zh-CN), [Zhiguo Cao](https://scholar.google.com.sg/citations?user=396o2BAAAAAJ&hl=zh-CN), [Hao Lu](https://sites.google.com/site/poppinace/)


tags: [Image Matting; Data Composition]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2212.13517'
url_code: 'https://github.com/zixuan-ye/composition_styles'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtu.be/wmvP3YcGcSQ'

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


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
