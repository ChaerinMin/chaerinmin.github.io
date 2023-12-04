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

I'm a first year Ph.D. student at [Brown University](https://www.brown.edu/), working with [Prof. Srinath Sridhar](https://cs.brown.edu/people/ssrinath/index.html). Before coming to Brown, I received by Master's degree in Computer Science at [Hanyang University](https://www.hanyang.ac.kr/web/eng), advised by [Prof. Jongwoo Lim](https://rvlab.snu.ac.kr/people/jwlim). I completed my Bachelor's degree at [University of Seoul](https://www.uos.ac.kr/en/main.do). 

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat. -->


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

My research interest lies in Computer Vision in 3D. I work on generative models to explore fun and impactful frontier in 3D scenes and motions that captured the scenes. 
Here is my [CV](pdf/CV.pdf). I'm looking for a research internship for Summer 2024. Feel free to reach out to me for future exciting collaboration!

# 🔥 News 
- *2023.06*: I successfully denfended my Master's thesis&nbsp;<a href="pdf/thesis.pdf"><img src="images/icon_pdf5.png"></a> and joined [Interactive 3D Vision & Learning Lab](https://ivl.cs.brown.edu/).
- *2023.01*: I will present our work, *Meta-Learning for Adaptation of Deep Optical Flow Networks*, at WACV 2023 in Hawaii&nbsp;🇺🇸.
- *2022.12*: I was granted a 9M KRW scholarship from [LG Electronics](https://www.lg.com/global/mobility)!
- *2022.03*: I recieved a patent&nbsp;<a href="pdf/patent.pdf"><img src="images/icon_pdf5.png"></a> on a learning method for event cameras. 
<!-- &nbsp;🎉🎉 -->

# 📝 Publications 

Drawing Hands with Generative Models

Kefan Chen, **Chaerin Min**, Linguang Zhang, Shreyas Hampali, Cem Keskin, Srinath Sridhar (**Under Review**)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv 2023</div><img src='images/TSDFSampling6.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->
[TSDF-Sampling: Efficient Sampling for Neural Surface Field using Truncated Signed Distance Field](https://arxiv.org/abs/2311.17878)

**Chaerin Min**$$^*$$, Sehyun Cha$$^*$$, Changhee Won, Jongwoo Lim ($$^*$$ denotes equal contribution, **Under Review**)

[**Project**](https://tsdf-sampling.github.io/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
[**Code**]()(Coming in Feb)

This paper introduces a novel approach that substantially reduces the number of samplings by incorporating the Truncated Signed Distance Field of the scene.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2023</div><img src='images/Metalearning.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->
[Meta-Learning for Adaptation of Deep Optical Flow Networks](https://openaccess.thecvf.com/content/WACV2023/papers/Min_Meta-Learning_for_Adaptation_of_Deep_Optical_Flow_Networks_WACV_2023_paper.pdf)

**Chaerin Min**, Tae Hyun Kim, Jongwoo Lim

Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2023. [**Video**](https://youtu.be/07pSNV6rBj4) [**Code**](https://github.com/ChaerinMin/MLOF)

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

# 🎖 Honors and Awards
- *2023.09* [NASA EPSCoR](https://www.nasa.gov/learning-resources/established-program-to-stimulate-competitive-research/), 17k USD. 
- *2022.12* LG Electronics Scholarship, [LGE Vehicle Solutions](https://www.lg.com/global/mobility), 9M KRW.
- *2021.09* BrainKorea21, [National Research Foundation of Korea](https://www.nrf.re.kr/eng/index), 26M KRW.
- *2020.01* [ISEP](https://www.isepstudyabroad.org/programs/program-types-and-deadlines/isep-exchange) Exchange, United States, 21k USD.
- *2019.09* Scholarship for Excellent Achievement, University of Seoul, Half tuition.
- *2016.03* Merit-based [Seongnam Scholarship](https://snjh.or.kr/EH2017/) for high school students, 1 year tuition. 

# 📖 Educations
- *2023.09 - current*, Ph.D. in Computer Science, Brown University. 
- *2021.09 - 2023.08*, M.S. in Computer Science, Hanyang University.
- *2017.03 - 2021.08*, B.S. in Electrical and Computer Engineering, University of Seoul.

<!-- # 💬 Invited Talks
- *2021.08*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.07*, Teaching Assistant, [Samsung Electronics](https://www.samsung.com/us/about-us/our-business/), gave a lab on motion and flow, supervised by [Prof. Jongwoo Lim](https://rvlab.snu.ac.kr/people/jwlim).
- *2021.08, 2022.09 - 2023.06*, Research Intern, [MultiplEYE](https://multipleye.co/en/), worked on neural 3D reconstruction of scenes.