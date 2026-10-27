---
title: 'Multi-modal, multi-species, and multi-task latent-space model for decoding level of consciousness'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - The team of Axoft, Inc


date: '2025-12-06T00:00:00Z'
doi: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Foundation Models for the Brain and Body*
publication_short: In *BrainBodyFM*

abstract: >-
  Assessing the degree and characteristics of consciousness is central to caring for patients with Disorders of Consciousness (DoC), yet current standard of care is a bedside questionnaire. Using a laminar neural probe we introduce a self-supervised, multi-modal representation learning approach that constructs an interpretable 2-D latent space of brain state from continuous neural recordings. We jointly encode local field potentials (LFPs), single-unit firing rates, and a movement proxy into a time-aware autoregressive VAE (TN-VAE). In rats, pigs and humans undergoing controlled depth anesthesia experiments, the learned latent trajectories nonlinearly, but smoothly, separate four expert-defined states (awake, light, moderate, deep) at 2s resolution, exceeding the temporal granularity of behavioral scoring (15m). The latent space supports linear readout of both coarse state and individual behavioral components, and its axes align with known physiology: delta/alpha power differentiates unconscious sub-states, while gamma and unit firing distinguish wakefulness. To enable cross-species use and incomplete modality sets, we add lightweight, species-specific stitching layers. This model pretrained on tri-modal rat data and fine-tuned with unimodal (LFP) pig data and unimodal human intraoperative data, successfully separates awake versus anesthetized states in new unseen human subjects, demonstrating zero-shot multi-subject transfer without per-patient calibration. The model further generalizes in a multi-task manner to predict the results of additional stimuli. These results highlight a path toward a foundation model for DoC that generalizes across sessions, subjects, species, and stimuli to enable scalable, continuous brain-state monitoring and clinical decision support.
tags:
  - Disorders of Consciousness

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=fk2hDc9DyL'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Anesthesia'
  focal_point: ''
  preview_only: false
---
