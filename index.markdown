---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: ""
---

# About Me

<style>
  /* 기본 스타일 (모바일 우선) */
  .profile-wrapper {
    display: flex;
    flex-direction: column-reverse; /* 모바일에서 사진을 위로, 텍스트를 아래로 */
    align-items: center;
    text-align: center;
    gap: 20px;
    margin-bottom: 30px;
  }

  .profile-text {
    flex: 1;
  }

  .profile-image img {
    width: 200px; /* 사진 크기 조절 */
    height: 200px;
    border-radius: 50%; /* 원형 이미지 */
    object-fit: cover;
  }

  /* 데스크탑 스타일 (화면 너비 768px 이상일 때) */
  @media (min-width: 768px) {
    .profile-wrapper {
      flex-direction: row; /* 가로로 배치 */
      align-items: flex-start;
      text-align: left;
      justify-content: space-between;
    }
    
    .profile-image {
      margin-left: 40px;
    }
  }
</style>

<div class="profile-wrapper">
  <div class="profile-text">
    <p>
      Hi! 👋 I am a second-year MS/PhD integrated student in <a href="https://ece.snu.ac.kr/">Electrical and Computer Engineering</a> at <a href="https://www.snu.ac.kr/index.html">Seoul National University</a>. 
      Under the supervision of Professor <a href="https://icl.snu.ac.kr/">Se Young Chun</a>, my research interests include, but are not limited to:
    </p>
    <ul>
      <li><strong>Efficient AI</strong>: acceleration, pruning, quantization, etc.</li>
      <li><strong>Safety AI</strong>: watermark, machine unlearning, etc.</li>
    </ul>
    <p>Email: <a href="mailto:kr.lee@snu.ac.kr">kr.lee@snu.ac.kr</a></p>
  </div>
  
  <div class="profile-image">
    <img src="/profile_3.jpg" alt="Kyungryeol Lee">
  </div>
</div>

<!-- <img src="/profile_3.jpg" width="200px" align="right" style="margin-left: 20px; border-radius: 10px;"> -->

<!-- Hi! I am a second-year MS/PhD integrated student in [Electrical and Computer Engineering](https://ece.snu.ac.kr/) at [Seoul National University](https://www.snu.ac.kr/index.html). Under the supervision of Professor [Se Young Chun](https://icl.snu.ac.kr/), I am currently focusing on research in efficient generative models, vision-language-action models, and safety AI. -->
<!-- Hi! 👋 I am a second-year MS/PhD integrated student in [Electrical and Computer Engineering](https://ece.snu.ac.kr/) at [Seoul National University](https://www.snu.ac.kr/index.html). Under the supervision of Professor [Se Young Chun](https://icl.snu.ac.kr/), I am currently focusing on research in **Efficient AI** (e.g., acceleration, pruning, quantization) and **Safety AI** (e.g., watermark, machine unlearning), but not limited to. -->

<!-- Email: [kr.lee@snu.ac.kr](mailto:kr.lee@snu.ac.kr) \ -->
<!-- [[Google Scholar](https://scholar.google.co.kr/citations?user=Xei6FKcAAAAJ&hl=ko)]
[[Github](https://github.com/krlee1)]
[[LinkedIn](https://www.linkedin.com/in/kyungryeol-lee-60b999335/)] -->
<!-- [![CV](https://img.shields.io/badge/CV-PDF-B31B1B?style=flat&logo=adobeacrobatreader&logoColor=white)](/assets/cv.pdf) -->
<a href="/CV_krlee.pdf" target="_blank"><img src="https://img.shields.io/badge/CV-PDF-B31B1B?style=flat&logo=adobeacrobatreader&logoColor=white" alt="CV"></a>
[![Github](https://img.shields.io/badge/Github-181717?style=flat&logo=github&logoColor=white)](https://github.com/krlee1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kyungryeol-lee-60b999335/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=google-scholar&logoColor=white)](https://scholar.google.co.kr/citations?user=Xei6FKcAAAAJ)

<br>

# Research

#### 2026

- **Training-free Mixed-Resolution Latent Upsampling for Spatially Accelerated Diffusion Transformers**

  Wongi Jeong\*, **Kyungryeol Lee**\*, Hoigi Seo, Se Young Chun (\*co-first) \
  Accepted at Conference on Computer Vision and Pattern Recognition (**CVPR**), 2026. (<b style="color:blue;">Highlight</b>)

  [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Jeong_Training-free_Mixed-Resolution_Latent_Upsampling_for_Spatially_Accelerated_Diffusion_Transformers_CVPR_2026_paper.html)]
  [[arXiv](https://arxiv.org/abs/2507.08422)]
  [[project](https://ignoww.github.io/RALU_project/)]
  [[code](https://github.com/ignoww/RALU)]

- **Unlearning the Unpromptable: Prompt-free Instance Unlearning in Diffusion Models**

  **Kyungryeol Lee**\*, Kyeonghyun Lee\*, Seongmin Hong\*, Byung Hyun Lee, Se Young Chun (\*co-first) \
  Accepted at CVPR Workshop on Machine Unlearning for Vision, 2026.
  <!-- arXiv, 2026. -->

  [[arXiv](https://arxiv.org/abs/2603.10445)]

#### 2025

- **Efficient Personalization of Quantized Diffusion Model without Backpropagation**

  Hoigi Seo\*, Wongi Jeong\*, **Kyungryeol Lee**, Se Young Chun (\*co-first) \
  Conference on Computer Vision and Pattern Recognition (**CVPR**), 2025.

  [[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Seo_Efficient_Personalization_of_Quantized_Diffusion_Model_without_Backpropagation_CVPR_2025_paper.html)] 
  [[arXiv](https://arxiv.org/abs/2503.14868)]
  [[project](https://ignoww.github.io/ZOODiP_project/)]
  [[code](https://github.com/ignoww/ZOODiP)]

- **Robust Watermarks for Audio Diffusion Models by Quadrature Amplitude Modulation**

  **Kyungryeol Lee**\*, Seongmin Hong\*, Se Young Chun (\*co-first) \
  Pattern Recognition Letters, 2025.

  [[Paper](https://www.sciencedirect.com/science/article/pii/S0167865525003083)]