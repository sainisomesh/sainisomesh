<h1 align="center">Somesh Saini</h1>
<p align="center"><strong>Computer Science × Biomedical AI × Healthcare Innovation</strong></p>
<p align="center">
  B.S. Computer Science + M.S. Biomedical &amp; Health Informatics<br>
  Case Western Reserve University
</p>
<p align="center">
  <a href="https://sainisomesh.github.io/someshsaini/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/someshsaini/">LinkedIn</a> ·
  <a href="https://www.vocalis.cc/">Vocalis</a>
</p>

I build machine learning systems to make healthcare more accessible. At **Cleveland Clinic**, I study what ECGs and overnight sleep recordings can reveal about disease risk. With **One Heart Health**, I work on models that use digital heart sounds to support pediatric cardiac screening. 

## Selected research

| Paper | Venue and role | What we studied |
| --- | --- | --- |
| [Deep Learning of Multimodal Features Derived from Raw Polysomnography for Cognitive Impairment Prediction](https://cinc.org/2026/Program/accepted/116.html) | **Computing in Cardiology 2026 · First author** | Combined EEG, other overnight physiological signals, and automated sleep-event annotations to predict future cognitive impairment. |
| [Learning from Leads: A 1D Dilated ResNet for ECG Chagas Disease Screening](https://commons.case.edu/studentworks/679/) | **Computing in Cardiology 2025 · First author** | Developed a dilated 1D ResNet that learns from 12-lead ECGs to support Chagas disease screening. |
| [Automated Detection of Poor-Quality Digital Heart Sounds via Noise Augmentation](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6749564) | **One Heart Health · SSRN preprint · Co-author** | Used noise augmentation and an Audio Spectrogram Transformer to identify recordings that may need to be retaken during cardiac screening. |

## Engineering work

- **[Pre-op triage agent](https://github.com/sainisomesh/preop-triage)** — Built a two-stage Python pipeline that extracts structured facts and source quotes from charts, verifies the quotes, and applies explicit rules to produce a scheduling recommendation and a nurse-readable audit trail. Evaluated the prototype across 50 labeled cases and compared consistency, latency, and caching across two language models.
- **Virtual staining with U-Net** — Built a PyTorch workflow that predicts two fluorescence channels from brightfield microscopy stacks. Compared model size and loss functions, then evaluated checkpoints on held-out microscopy fields.
- **Cross-cohort heart murmur detection** — Evaluated whether training-time augmentation helps an Audio Spectrogram Transformer generalize to recordings from external cohorts. 

## Languages & tools

| Area | How I use it |
| --- | --- |
| **Python · PyTorch · Hugging Face Transformers** | Train 1D convolutional networks for ECG and sleep signals, fine-tune spectrogram transformers for heart sounds, and build U-Net models for microscopy. |
| **NumPy · pandas · scikit-learn** | Prepare physiological signals and tabular features, train baselines, and evaluate models across held-out datasets. |
| **Python · LLM APIs** | Build structured extraction, validate source evidence, and implement deterministic decision rules with traceable outputs. |
| **TypeScript · React · Next.js · GitHub Actions** | Build and publish web interfaces, including my portfolio, through a Git-based workflow. |

## Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sainisomesh/sainisomesh/output/github-snake-dark.svg">
  <img alt="Animated snake eating squares from Somesh Saini's GitHub contribution grid" src="https://raw.githubusercontent.com/sainisomesh/sainisomesh/output/github-snake.svg" width="100%">
</picture>
