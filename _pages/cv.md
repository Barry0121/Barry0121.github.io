---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- MSc in Applied Computing (MScAC), Department of Computer Science, University of Toronto, 2023-2025
  - Cumulative GPA: 4.00/4.00
  - Relevant courses: Knowledge Representation and Reasoning, Automated Reasoning with Machine Learning, Neural Networks and Deep Learning, Software Engineering for ML-Enabled Systems, Visual and Mobile Computing
- BS in Data Science, Halıcıoğlu Data Science Institute (HDSI), University of California San Diego, 2019-2023
  - Cumulative GPA: 3.54/4.00

# Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

# Preprints & In-submission
<ul>
{% for post in site.preprint reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>


# Research & Work Experience

- **Sanofi Canada**, Toronto, Canada\
  *Computational Scientist (Co-op)*
  May 2024 - December 2024
  - Developed DEWDROP, a novel active learning strategy that uses an ensemble of predictions to estimate epistemic uncertainty, optimizing in silico nanobody candidate development.
  - Outperformed BADGE, KMeans, and Random baseline strategies, reducing sample requirements by 25% for achieving target loss in nanobody structure prediction.
  - Fine-tuned the Nanofold model using DEWDROP, achieving a FAPE loss below 0.5 in just 5 rounds, utilizing 35% of the total dataset.
  - The DEWDROP-Nanofold pipeline is patented, and a manuscript is in preparation for submission to RECOMB.

- **REAP Lab @ University of Toronto**, Toronto, Canada\
  *Research Assistant*
  October 2023 - May 2025
  - Developed Vi-SATNet, a neural-symbolic architecture, combining CNN models with SATNet to learn implicit propositional rules in the feature space.
  - Achieved over 90% accuracy on the MNIST dataset using feature regeneration, even when 80% of the features were masked.
  - Work submitted to ICLR 2025 for review.

- **Abarbanel Computational Biophysics Lab @ UCSD**, San Diego, CA\
  *Research Assistant*
  September 2022 - June 2023
  - Developed a fast machine learning model based on the RBF network to simulate songbirds’ singing behavior.
  - Implemented GPU acceleration in PyTorch, reducing experiment runtime by 60%.
  - Developed the False Nearest Neighbor implementation, speeding up hyperparameter search by 10x.

- **Personalis**, Menlo Park, United States\
  *Data Warehouse Engineer Intern*
  June 2022 - August 2022
  - Developed ETL pipelines for processing gigabyte-scale human genome data between SQL servers and Google BigQuery.
  - Created a time series prediction model using Google Cloud's Dataflow and PySpark ML, and a collaborative filtering model for recommending relational tables.

# Skills

- **Programming**: Python, Java, SQL, C (basic)
- **Frameworks/Tools**: PyTorch, TensorFlow, Spark ML, Scikit-Learn, MMSeq2, ViennaRNA, BigQuery, Dataflow, Dagster, Selenium, AWS, Nvidia DGX

# Research Projects

- **[GPT-STEVE1: Long Horizon Action through Prompting Pre-trained Agent in Minecraft](https://github.com/Barry0121/gptsteve1)**
  - Injected GPT-4’s world knowledge through multi-modal prompts to enhance the long-horizon action capability of STEVE-1 in Minecraft.
  - Demonstrated GPT-4’s ability to compose feasible action plans for complex tasks.
  - Identified limitations in VPT pre-training for action generalization.

- **[DeepCache-MLX: Accelerated Stable Diffusion on Apple Silicon](https://github.com/horseee/DeepCache/tree/master)**
  - Developed DeepCache, a lightweight framework in MLX that caches high-level features during denoising, resulting in a 10x speedup in Stable Diffusion on Apple Silicon devices.

- **[Discovering Continuous Latent Space Representations for Graphs](https://dsc180-gnn.github.io/)**
  - Integrated autoregressive graph generation with Wasserstein GAN and VAE to benchmark model expressivity using MUTAG, ENZYME, and PROTEIN datasets.
  - Presented results at HDSI Capstone Showcase.

- **[Automate Image Captioning on Flask-based Web Application](https://github.com/Barry0121/albumy-autocaption)**
  - Enhanced the open-source Albumy platform with BLIP-2 image captioning and search functionality using DETR for object detection.

# Service and Leadership

- **Toronto AI Practitioner Network (TAPNET)**, Toronto, Canada \
  [*Organizer*](https://www.meetup.com/toronto-ai-practitioners-network/)
  September 2024 - Present
  - Organized events connecting AI practitioners (academics, engineers, and founders) in Toronto and across Canada, fostering collaboration between professors, students, and the AI community.
