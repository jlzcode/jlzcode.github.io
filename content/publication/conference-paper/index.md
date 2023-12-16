---
title: 'Progressive Frequency-Aware Network for Laparoscopic Image Desmoking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wenfeng Huang
  - Xiangyun Liao
  - Qiong Wang
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-10-13T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The 6th Chinese Conference on Pattern Recognition and Computer Vision*
publication_short: In *PRCV 2023*

abstract: 'Laparoscopic surgery offers minimally invasive procedures with better patient outcomes, but smoke presence challenges visibilityand safety. Existing learning-based methods demand large datasets andhigh computational resources. We propose the Progressive Frequency-Aware Network (PFAN), a lightweight GAN framework for laparoscopicimage desmoking, combining the strengths of CNN and Transformerfor progressive information extraction in the frequency domain. PFAN features CNN-based Multi-scale Bottleneck-Inverting (MBI) Blocks forcapturing local high-frequency information and Locally-Enhanced Axial Attention Transformers (LAT) for efficiently handling global low-frequency information. PFAN efficiently desmokes laparoscopic imageseven with limited training data. Our method outperforms state-of-the-art approaches in PSNR, SSIM, CIEDE2000, and visual quality on the Cholec80 dataset and retains only 629K parameters. Our code and models are made publicly available at \: https://github.com/jlzcode/PFAN.'

# Summary. An optional shortened abstract.
summary: Laparoscopic surgery offers better patient outcomes but smoke harms visibility and safety; we propose the lightweight Progressive Frequency-Aware Network that combines CNN and Transformer innovations for efficient multi-scale smoke removal from laparoscopic images using limited data.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/jlzcode/PFAN'
url_dataset: 'https://github.com/jlzcode/PFAN'
url_poster: 'https://github.com/jlzcode/PFAN/blob/main/Poster.pdf'

# https://github.com/jlzcode/PFAN/blob/main/Progressive%20Frequency-Aware%20Network%20for%20Laparoscopic%20Desmoking.pdf
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
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
