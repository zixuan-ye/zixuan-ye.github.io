---
title: 'StyleMaster: Stylize Your Video with Artistic Generation and Translation
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - "In Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2025)"
# authors:
#   - "Zixuan Ye"
#   - "Yutong Dai"  
  # - [Yutong Dai](),
  # [Chaoyi Hong](https://scholar.google.com/citations?user=N9YzPMcAAAAJ&hl=zh-CN),
  # [Zhiguo Cao](https://scholar.google.com.sg/citations?user=396o2BAAAAAJ&hl=zh-CN),
  # [Hao Lu](https://sites.google.com/site/poppinace/)
  # ’
  

date: '2025-02-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Proceedings of IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2025)

abstract: Automatic and interactive matting largely improve image matting by respectively alleviating the need for auxiliary input and enabling object selection. Due to different settings on whether prompts exist, they either suffer from weakness in instance completeness or region details. Also, when dealing with different scenarios, directly switching between the two matting models introduces inconvenience and higher workload. Therefore, we wonder whether we can alleviate the limitations of both settings while achieving unification to facilitate more convenient use. Our key idea is to offer saliency guidance for automatic mode to enable its attention to detailed regions, and also refine the instance completeness in interactive mode by replacing the binary mask guidance with a more probabilistic form. With different guidance for each mode, we can achieve unification through adaptable guidance, defined as saliency information in automatic mode and user cue for interactive one. It is instantiated as candidate feature in our method, an automatic switch for class token in pretrained ViTs and average feature of user prompts, controlled by the existence of user prompts. Then we use the candidate feature to generate a probabilistic similarity map as the guidance to alleviate the over-reliance on binary mask. Extensive experiments show that our method can adapt well to both automatic and interactive scenarios with more light-weight framework. 


summary: "__Zixuan Ye__, [Huijuan Huang](https://openreview.net/profile?id=~Huijuan_Huang1), [Xintao Wang](https://xinntao.github.io/), [Pengfei Wan](https://scholar.google.com/citations?user=P6MraaYAAAAJ&hl=en), [Di Zhang](https://openreview.net/profile?id=~Di_ZHANG3), [Wenhan Luo](https://whluo.github.io/)"


tags: [Style Transfer; Video Generation]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2412.07744'
url_code: 'https://github.com/KwaiVGI/StyleMaster'
# url_dataset: 'https://github.com/tiny-smart/in-context-matting'
# url_poster: ''
url_project: 'https://zixuan-ye.github.io/stylemaster/'
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
