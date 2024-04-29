---
title: 'In-Context Matting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - "In Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024) Highlight"
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
publication: In Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024) Highlight

abstract: We introduce in-context matting, a novel task setting of image matting. Given a reference image of a certain foreground and guided priors such as points, scribbles, and masks, in-context matting enables automatic alpha estimation on a batch of target images of the same foreground category, without additional auxiliary input. This setting marries good performance in auxiliary input-based matting and ease of use in automatic matting, which finds a good trade-off between customization and automation. To overcome the key challenge of accurate foreground matching, we introduce IconMatting, an in-context matting model built upon a pre-trained text-to-image diffusion model. Conditioned on inter- and intra-similarity matching, IconMatting can make full use of reference context to generate accurate target alpha mattes. To benchmark the task, we also introduce a novel testing dataset ICM-57, covering 57 groups of real-world images. Quantitative and qualitative results on the ICM-57 testing set show that IconMatting rivals the accuracy of trimap-based matting while retaining the automation level akin to automatic matting. 


summary: "He Guo, __Zixuan Ye__, [Zhiguo Cao](https://scholar.google.com.sg/citations?user=396o2BAAAAAJ&hl=zh-CN), [Hao Lu](https://sites.google.com/site/poppinace/)"


tags: [Image Matting; Diffusion Model]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.15789.pdf'
url_code: 'https://github.com/tiny-smart/in-context-matting'
url_dataset: 'https://github.com/tiny-smart/in-context-matting'
# url_poster: ''
url_project: 'https://tiny-smart.github.io/icm.github.io/'
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'

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
