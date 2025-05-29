---
title: 'Predictive variational autoencoder for learning robust representations of time-series data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Dexter Tsin
  - Tatiana Engel


date: '2023-12-12T00:00:00Z'
doi: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Unifying Representations in Neural Models*
publication_short: In *UniReps*

abstract: Variational autoencoders (VAEs) have been used extensively to discover low-dimensional latent factors governing neural activity and animal behavior. However, without careful model selection, the uncovered latent factors may reflect noise in the data rather than true underlying features, rendering such representations unsuitable for scientific interpretation. Existing solutions to this problem involve introducing additional measured variables or data augmentations specific to a particular data type. We propose a VAE architecture that predicts the next point in time and show that it mitigates the learning of spurious features. In addition, we introduce a model selection metric based on smoothness over time in the latent space. We show that together these two constraints on VAEs to be smooth over time produce robust latent representations and faithfully recover latent factors on synthetic datasets.
tags:
  - Representation Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://pmc.ncbi.nlm.nih.gov/articles/PMC10760197/'
url_code: 'https://github.com/engellab/braivest'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Manifold'
  focal_point: ''
  preview_only: false
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
