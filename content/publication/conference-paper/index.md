---
title: 'Total Harmonic Distortion Reduction Method of Improved Finite Control Set Model Predictive Control for Single-Phase Inverter with Twisted Parameter'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Po Li
  - Xiaoxiao Huo
  - Feng Guo

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-12-29T00:00:00Z'
doi: '10.1109/ICPET59380.2023.10367520'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 5th International Conference on Power and Energy Technology*
publication_short: In *ICPET2023*

abstract: The single-phase inverter is a commonly used DC/AC converter in the industrial field. Due to its fast dynamic performance and the ability to handle multiple constraints, Finite Control Set-Model Predictive Control (FCS-MPC) is capable of effectively tracking the current of single-phase inverters. However, the implementation of FCS-MPC is characterized by high computational demand, time delay, and a requirement for high model accuracy. In order to address these challenges, this study proposes a twisted parameter FCS-MPC method that artificially twists the model parameters. This method aims to reduce Total Harmonic Distortion (THD) as compared to the one-step delay compensation FCS-MPC. By ensuring accurate tracking of the single-phase inverter, this method can effectively save computational time. The study utilizes simulations to uncover the impact of model parameters on the THD of the grid current. It is discovered that reducing the control parameters of inductance can lead to a reduction in THD of the current. The simulation results demonstrate that, within a certain range, reducing the control parameters of inductance can effectively enhance the quality of the grid current without an increase in the number of switch operations. Furthermore, this method outperforms the delay compensation method by offering a lower computational burden, smaller prediction error, and lower switch loss.

# Summary. An optional shortened abstract.
summary: A twisted parameter FCS-MPC method that artificially twists the model parameters.

tags: [MPC, THD, Single-phase inverters]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: DOI
  url: 10.1109/ICPET59380.2023.10367520

url_pdf: 'https://ieeexplore.ieee.org/document/10367520'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
