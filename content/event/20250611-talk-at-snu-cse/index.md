---
title: Talk @ SNU Computer Science & Engineering

event: SNU CSE Seminar
event_url: https://cse.snu.ac.kr/community/seminar

# location: Hugo Blox Builder HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Bypass Training Stagnation and Accelerate Your Deep Learning
abstract: 'Directly bypassing training slowdowns for neural networks is possible, by temporarily expanding the model with learnable activations, exploring new descent directions, and then contracting back. This strategy can accelerate gradient-based training of deep learning models.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-06-18T11:00:00Z'
date_end: '2025-06-18T12:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-06-01T00:00:00Z'

authors:
  - admin

tags: [theory]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Alpine Mag**](https://alpinemag.com/mont-blanc-new-normal-routes/)'
  # focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - theory
---


For more information on the research in the talk, see [the publication from AIML@K](https://aiml-k.github.io/publication/2024tnnls-jung-lee/).

{{< spoiler text="View Talk Details" >}}

## Talk Title

Bypass Training Stagnation and Accelerate Your Deep Learning

## Abstract

What would you do when your deep learning training slows down? Tired of ad-hoc methods hoping for a better outcome by restarting, perturbing, or adding momentums? This talk introduces Bypass, a well-principled active method that directly rescues gradient-based optimizers from stagnation near stationary points such as saddle points and suboptimal local minima.

Bypass uses a simple yet powerful idea: temporarily extend the model, explore new directions in this richer space, and then contract back to the original architecture while preserving the learned function. This extension-contraction principle is mathematically well-grounded, requiring no explicit identification of stationary regions, and is easy to implement in standard training pipelines. I will present both the mathematical foundation and algorithmic design of the Bypass pipeline, explain how algebraic constraints can enforce a safe return to the original model, and show how this method can naturally unlock new descent paths to gradient-based optimizers. Empirical validations on regression and classification tasks demonstrate that Bypass consistently leads to better training, and surprisingly, improved generalization as well.

Bypass also offers a new lens on neural network morphism and neural architecture search, suggesting ways to navigate model space dynamically during training. Whether your specialty is in optimization theory, dynamics of deep learning models, or practical improvements of deep learning applications, this talk will be of interest to you, since Bypass is a versatile method that integrates naturally with existing model architectures and optimizers.
{{< /spoiler >}}

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
