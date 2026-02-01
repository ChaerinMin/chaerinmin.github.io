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

# About 

I am a third year Ph.D. student at [Brown University](https://www.brown.edu/), working with [Prof. Srinath Sridhar](https://cs.brown.edu/people/ssrinath/index.html).
My research interest lies in Computer Vision in 3D.
I'm currently exploring 3D reconstruction, visual localization, and user interaction.
Here is my [Curriculum Vitae](pdf/CV_ChaerinMin_260131.pdf).
<!-- Here is my [Curriculum Vitae](pdf/CV.pdf). -->
Before coming to Brown, I received by Master's degree in Computer Science at [Hanyang University](https://www.hanyang.ac.kr/web/eng), advised by [Prof. Jongwoo Lim](https://rvlab.snu.ac.kr/people/jwlim).
I completed my Bachelor's degree at [University of Seoul](https://www.uos.ac.kr/en/main.do).
Feel free to reach out to me for future exciting collaboration!

# 📢 News 

- *2026.01*: My work during Google internship, [SLoFT](), is accepted to ICRA 2026. See you at Vienna&thinsp;🇦🇹!
- *2025.12*: Our [1st 4DWorldModels workshop](https://ivl.cs.brown.edu/4dworldmodels) has been accepted to CVPR 2026!

<details>
  <summary> &nbsp; Click to Expand</summary>

  <article markdown="1" class="post-content">
  - *2025.05*: I'm selected as a [Outstanding Reviewer](https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer) of CVPR 2025!
  - *2025.06*: I'm excited to join [Google](https://about.google/) as a Student Researcher. See you at Mountain View!
  - *2025.04*: [FoundHand](https://arxiv.org/abs/2412.02690) is accepted to CVPR 2025 as Highlight! Try our [**demo**](https://huggingface.co/spaces/Chaerin5/FoundHand)🤗 and see you at Nashville&nbsp;🎸
  - *2025.03*: I successfully defended my candidacy.
  - *2024.06*: [TSDF-Sampling](https://ieeexplore.ieee.org/abstract/document/10802100) is accepted to IROS 2024! See you at Abu Dhabi&nbsp;🐪
  <!-- - *2024.04*: Presented GenHeld at [**NASA event**](pdf/nasa.pdf) and [**NYC Vision Day**](pdf/nyc.pdf). -->
  - *2023.06*: Successfully defended my [**Master's thesis**](pdf/thesis.pdf)!
  <!-- and joined [Interactive 3D Vision & Learning Lab](https://ivl.cs.brown.edu/). -->
  - *2023.01*: [MLOF](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html) is accepted to WACV 2023! See you at Hawaii&nbsp;🏝️
  - *2022.12*: Granted a 9M KRW scholarship from LG Electronics!
  <!-- - *2022.03*: Recieved a [**patent**](pdf/patent.pdf) about event cameras.  -->
  <!-- &nbsp;🎉🎉 -->
  </article>
</details>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/SLoFT_loop.gif' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">


## [SLoFT: End-to-End Semantic Localization with Floorplan and Transformer]()

**Chaerin Min**, Hongsheng Yu, Fengtao Fan, Srinath Sridhar, Qiuxuan Wu, Chao Guo

<span style="color:black">ICRA 2026</span> <!--<span style="color:brown">oral pitch</span>-->

*Details coming soon..*

</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2024</div><img src='images/genheld.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/foundhand.jpg' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [FoundHand: Large-Scale Domain-Specific Learning for Controllable Hand Image Generation](https://arxiv.org/abs/2412.02690)

Kefan Chen$$^*$$, **Chaerin Min$$^*$$**, Linguang Zhang, Shreyas Hampali, Cem Keskin, Srinath Sridhar

<span style="color:black">CVPR 2025 <span style="color:#CC0000 "><i>Highlight</i></span></span> (Top <span style="color:#CC0000">2.98%</span> out of valid submissions)

<!-- <span style="color:grey">In Submission</span> -->
[**Paper**](https://arxiv.org/abs/2412.02690) [**Project**](https://ivl.cs.brown.edu/research/foundhand.html) [**Code**](https://github.com/arthurchen0518/FoundHand) [**Demo**](https://huggingface.co/spaces/Chaerin5/FoundHand)

</div>
</div>

<!-- <div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">In Submission</div><img src='images/genheld.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [GenHeld: Generating and Editing Handheld Objects](https://arxiv.org/abs/2406.05059)

**Chaerin Min**, Srinath Sridhar -->

<!-- <span style="color:grey">In Submission</span> -->

<!-- [**Paper**](https://arxiv.org/abs/2406.05059)  -->
<!-- [**Project**](https://ivl.cs.brown.edu/research/genheld.html) [**Code**](https://github.com/ChaerinMin/GenHeld) -->

<!-- </div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/tsdf.gif' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">


## [Fast Spatial Reasoning of Implicit 3D maps through Explicit Near-Far Sampling Range Prediction](https://ieeexplore.ieee.org/abstract/document/10802100)

**Chaerin Min**$$^*$$, Sehyun Cha$$^*$$, Changhee Won, Jongwoo Lim

<span style="color:black">IROS 2024</span> <!--<span style="color:brown">oral pitch</span>-->

[**Paper**](https://ieeexplore.ieee.org/abstract/document/10802100) [**Project**](https://chaerinmin.github.io/TSDF-sampling/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> [**Code**](https://github.com/ChaerinMin/TSDF-sampling)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2023</div><img src='images/mlof.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

## [Meta-Learning for Adaptation of Deep Optical Flow Networks](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html)

**Chaerin Min**, Tae Hyun Kim, Jongwoo Lim

<span style="color:black">WACV 2023</span>

[**Paper**](https://openaccess.thecvf.com/content/WACV2023/html/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.html) [**Video**](https://youtu.be/07pSNV6rBj4) [**Code**](https://github.com/ChaerinMin/MLOF)

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>
# 💻 Research Experiences
<div style="display: flex; align-items: center; margin-bottom: 20px; margin-top: 20px;">
  <img src="images/google_logo.jpg" alt="logo" style="margin-right: 45px; margin-left: 25px; width: 130px;" />
  <div style="text-align: left; line-height: 1.2;">
    <p style="font-size: 1.0em; color: #000;">
      Google
    </p>
    <p style="font-size: 1.0em;">Student Researcher (mentor: <a href="https://www.linkedin.com/in/hongsheng-yu-05788059/">Hongsheng Yu</a>)</p>
    <p style="font-size: 1.0em;">Mountain View / San Jose, CA</p>
    <p><em>Visual localization -> ICRA 2026</em></p>
    <p style="font-size: 1.0em;">06/2025 - 09/2025</p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px; margin-top: 20px;">
  <img src="images/brown_logo.png" alt="logo" style="margin-right: 45px; margin-left: 20px; width: 135px;" />
  <div style="text-align: left; line-height: 1.2;">
    <p style="font-size: 1.0em; color: #000;">
      Brown University
    </p>
    <p>Ph.D. Research Assistant @ <a href="https://ivl.cs.brown.edu/" target="_blank">Interactive 3D Vision & Learning Lab</a></p>
    <p><em>3D reconstruction and generation -> CVPR 2025 and current projects</em></p>
    09/2023 - Current
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 20px; margin-top: 20px;">
  <img src="images/multipleye_logo.png" alt="logo" style="margin-right: 45px; margin-left: 20px; width: 135px;" />
  <div style="text-align: left; line-height: 1.2;">
    <p style="font-size: 1.0em; color: #000;">
      MultiplEYE Co.
    </p>
    <p>Research Intern @ MultiplEYE</p>
    <p><em>Neural rendering in large real indoor scenes -> IROS 2024</em></p>
    09/2022 - 05/2023
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px; margin-top: 20px;">
  <img src="images/hyu_logo.png" alt="logo" style="margin-right: 75px; margin-left: 50px; width: 75px;" />
  <div style="text-align: left; line-height: 1.2;">
    <p style="font-size: 1.0em; color: #000;">
      Hanyang University
    </p>
    <p>Master's Research Assistant @ <a href="https://rvlab.snu.ac.kr/" target="_blank"> Computer Vision Lab</a></p>
    <p><em>Cross-domain generalization in optical flow -> WACV 2023</em></p>
    09/2021 - 08/2023
  </div>
</div>

<!-- - *2023.09 - current,* [Interactive 3D Vision & Learning Lab](https://ivl.cs.brown.edu/), Brown University
  - Ph.D. Research Assistant, 3D computer vision and generation -> CVPR 2025 and current projects
- *2022.09 - 2023.05,* [MultiplEYE Co.](https://multipleye.co/en/)
  - Research Intern, Neural rendering in large real indoor scenes -> IROS 2024
<!-- *2023.07*, Teaching Assistant, at [Samsung Electronics](https://www.samsung.com/us/about-us/our-business/) for one-day lab of AI Expert course -->
<!-- - *2021.09 - 2023.05,* [Computer vision Lab](https://rvlab.snu.ac.kr/), HYU
  - Master’s Research Assistant, Cross-domain generalization in optical flow -> WACV 2023 --> 

# 🎖 Honors and Awards

<details>
  <summary class="post-content"> &nbsp; Click to Expand </summary>

  <article markdown="1" class="post-content">
  - *2022.12* LG Electronics Scholarship, [LGE Vehicle Solutions](https://www.lg.com/global/mobility)
  - *2021.09* BrainKorea21, [National Research Foundation of Korea](https://www.nrf.re.kr/eng/index)
  - *2020.01* [ISEP](https://www.isepstudyabroad.org/programs/program-types-and-deadlines/isep-exchange) Exchange, United States
  - *2019.09* Scholarship for Excellent Achievement, University of Seoul
  - *2016.03* Merit-based [Seongnam Scholarship](https://snjh.or.kr/EH2017/) for high school students
  </article>
</details>

# 📖 Services
- Reviewer for ECCV'24, T-PAMI'24, SIGGRAPHP'25, AAAI'26, CVPR'24'25'26
- ⭐️ [Outstanding reviewer](https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer) ⭐️ of CVPR 2025
- Junior Organizer for [1st 4DWorldModels Workshop](https://ivl.cs.brown.edu/4dworldmodels) at CVPR 2026

# 📖 Educations
<!-- <details>
  <summary class="post-conent"> &nbsp; Click to Expand </summary>
  <article markdown="1" class="post-content"> -->
- *2023.09 - current*, Ph.D. in Computer Science, [Brown University](https://www.brown.edu/) (GPA: 4.0/4.0)
- *2021.09 - 2023.08*, M.S. in Computer Science, [Hanyang University](https://www.hanyang.ac.kr/web/eng) (GPA: 4.0/4.0)
- *2017.03 - 2021.08*, B.S. in Electrical and Computer Engineering, [University of Seoul](https://www.uos.ac.kr/en/main.do) (GPA: 4.3/4.5, <span style="color:#CC0000 ">2nd place</span>)
  <!-- </article>
<!-- </details> --> 

<!-- # 💬 Invited Talks
- *2021.08*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span style="color:grey">Last updated: Jan 31, 2026</span>
<div><br><br></div>