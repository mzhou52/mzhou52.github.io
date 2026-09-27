---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I am a 2<sup>nd</sup> year Ph.D. student in the Department of Cognitive Science at Johns Hopkins University, advised by [Prof. Leyla Isik](https://www.isiklab.org/). My research is centered on leveraging computational models to explore high-level human vision, with a particular focus on understanding how humans perceive and recognize thousands of objects and actions present in the natural world. Additionally, I have extensive experience in neuroimaging, including the development and organization of several large-scale neuroimaging datasets.

Prior to joining JHU, I received my bachelor's and master's degrees from Beijing Normal University (2018–2025), advised by Prof. Zonglei Zhen and Prof. Youyi Liu. I also had a remote internship (2024–present) with [Prof. Martin Hebart](https://hebartlab.com/) and Dr. Tonghe Zhuang (postdoctoral researcher) at the Max Planck Institute for Human Cognitive and Brain Sciences.


# 🔥 News
- *2026.09*: &nbsp;🎉 Our paper **NEvo: Neural-Guided Evolutionary Video Synthesis for Dynamic Visual Selectivity** has been accepted to **NeurIPS 2026**!
- *2026.09*: &nbsp;🚀 Started my second year as a Ph.D. student in the Department of Cognitive Science at Johns Hopkins University!
- *2026.08*: &nbsp;🧠 Presented our work on mid-level motion statistics and the lateral stream at [CCN 2026](https://openreview.net/pdf?id=XZQkHjYK23)!
- *2026.05*: &nbsp;🎤 Presented a poster on mid-level motion statistics and social perception at [VSS 2026](https://www.visionsciences.org/presentation/?id=3701)!
- *2025.09*: &nbsp;🏫 Joined the Johns Hopkins University as a first-year PhD Student!
- *2025.06*: &nbsp;🎓 Graduated from Beijing Normal University! Received my master degree!

# 📝 Publications

<div class='paper-box'><div class="badge badge-conference">NeurIPS 2026</div><div class='paper-box-image'><img src='images/nevo.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[NEvo: Neural-Guided Evolutionary Video Synthesis for Dynamic Visual Selectivity](https://arxiv.org/abs/2607.02317)&nbsp;&nbsp;&nbsp;&nbsp;[Project page](https://nevo-project.epfl.ch/)

Yingtian Tang<sup>\*</sup>, Sogand Salehi<sup>\*</sup>, **Ming Zhou**<sup>\*</sup>, Amir Zamir, Leyla Isik & Martin Schrimpf&nbsp;&nbsp;(<sup>\*</sup>equal contribution)

- NEvo pairs a dynamic brain-encoding model with an evolutionary search over a structured video-prompt space to synthesize hyper-activating dynamic stimuli that consistently surpass handcrafted localizers &mdash; going beyond what naturalistic videos alone can evoke. A searchlight analysis centered on the lateral stream reveals a progression toward increasingly complex social-dynamic features along this pathway, a result further supported by probing with synthesized, non-naturalistic stimuli.

</div>
</div>

<div class='paper-box'><div class="badge badge-workshop">CCN 2026</div><div class='paper-box-image'><img src='images/mid_level_motion.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Mid-level Motion Statistics as a Model for Dynamic Visual Perception in the Lateral Stream](https://openreview.net/pdf?id=XZQkHjYK23)

**Ming Zhou** & Leyla Isik

- We derive an image-computable model of second-order motion statistics, built from first principles and inspired by work on static textures, to characterize social motion responses along the lateral stream. Fit to fMRI data from participants viewing social video clips, these features capture meaningful motion structure (periodicity, curved contours, complex motion) and explain significantly more variance than first-order motion energy in mid- and high-level lateral regions such as EBA and pSTS.

</div>
</div>

<div class='paper-box'><div class="badge">Scientific Data</div><div class='paper-box-image'><img src='images/HAD.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Human Action Dataset (HAD)](https://www.nature.com/articles/s41597-023-02325-6)&nbsp;&nbsp;&nbsp;&nbsp;[Download dataset](https://openneuro.org/datasets/ds004488)

**Ming Zhou**, Zhengxin Gong, Yuxuan Dai, Yushan Wen, Youyi Liu & Zonglei Zhen

- HAD is a large-scale functional magnetic resonance imaging (fMRI) dataset for human action recognition, which contains fMRI responses to 21,600 naturalistic 2-seconds video clips from 30 participants. These clips cover a diverse range of 180 everyday action categories, including sports, eating, personal care, social interactions, and household activities. Preliminary analyses have demonstrated the dataset's high signal-to-noise ratio and promising potential for uncovering the representational structures across the visual cortex.

</div>
</div>

<div class='paper-box'><div class="badge badge-conference">CHI 2026</div><div class='paper-box-image'><img src='images/chi_error_awareness.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Enhancing Error Awareness Under Cognitive Load: How Neurostimulation Improves Self-Monitoring via Working Memory](https://doi.org/10.1145/3772318.3790889)

Xiaohan Huang, Jiayang Wu, **Ming Zhou**, & Xinyu Zhang

- Error awareness deteriorates under heavy cognitive load, and effective countermeasures remain scarce. Using a multi-rule task with EEG, we show that tDCS over the left DLPFC significantly improves error awareness under high load, reflected in both behavior and a neural index (ERN amplitude). Mediation analysis reveals this effect works by boosting working memory capacity, which in turn supports better real-time error detection &mdash; a mechanism we formalize as the **Dynamic Cognitive Resource Barrel Theory**: error awareness is limited by whichever cognitive resource is most depleted after the primary task's demands.

</div>
</div>

<div class='paper-box'><div class="badge">Scientific Data</div><div class='paper-box-image'><img src='images/nod_fmri.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Natural Object Dataset (NOD) &ndash; fMRI](https://www.nature.com/articles/s41597-023-02471-x)&nbsp;&nbsp;&nbsp;&nbsp;[Download dataset](https://openneuro.org/datasets/ds004496)

Zhengxin Gong, **Ming Zhou**, Yuxuan Dai, Yushan Wen, Youyi Liu & Zonglei Zhen

- NOD is a large-scale fMRI dataset probing the visual processing of naturalistic scenes, with responses from 30 participants to over 57,000 images drawn from ImageNet and COCO. Its scale and image diversity make it well suited for studying object recognition, testing the generalizability of brain-model correspondence, and comparing individual variability against population-level structure across the visual cortex.

</div>
</div>

<div class='paper-box'><div class="badge">Scientific Data</div><div class='paper-box-image'><img src='images/nod_megeeg.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Natural Object Dataset (NOD) &ndash; MEG & EEG](https://www.nature.com/articles/s41597-025-05174-7)

Zhang, G., **Zhou, M.**, Zhen, S., Tang, S., Li, Z., & Zhen, Z.

- This companion release extends NOD with MEG and EEG recordings from the same naturalistic image set, pairing the original fMRI data with high-temporal-resolution measurements. Together they let researchers examine object recognition in natural scenes with both the spatial precision of fMRI and the millisecond-scale dynamics of MEG/EEG within a single, unified dataset.

</div>
</div>

- Zhuang, T., Stoinski, L. M., **Zhou, M.**, St Laurent, M., Satzger, R., & Hebart, M. N. (2025). **Revealing the mental and neural representations of object words and object images.** *16th Annual Workshop on CONCEPTS, ACTIONS, and OBJECTS (CAOs).*
- Zhuang, T., Stoinski, L. M., **Zhou, M.**, & Hebart, M. N. (2025). **Comparing the multidimensional mental and neural representations of object words and object images.** *Journal of Vision, 25*(9), 2376-2376.
- Chen, X., **Zhou, M.**, Gong, Z., Xu, W., Liu, X., Huang, T., ... & Liu, J. (2020). **DNNBrain: A unifying toolbox for mapping deep neural networks and brains.** *Frontiers in Computational Neuroscience, 14*, 580632. [[link]](https://doi.org/10.3389/fncom.2020.580632)

# 📖 Educations
- 2022.09 - 2025.06, Beijing Normal University, State Key Laboratory of Cognitive Neuroscience and Learning, Master of Science.
- 2018.09 - 2022.06, Beijing Normal University, Falculty of Psychology, Bachelor of Science. 

