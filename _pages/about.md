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

My name is Muyao Li (李沐遥), an undergraduate student in the Tong Class at Peking University. You can reach me at li_muyao@stu.pku.edu.cn.

I am currently an intern at [CraftJarvis](https://craftjarvis.github.io/), where we focus on building autonomous agents that can operate in open world. To me, true autonomy consists of three layers: (1) the ability to robustly follow user instructions in dynamic, uncertain settings; (2) the capacity to comply with predefined rules and constraints; and (3) ultimately, the emergence of self-directed, value-aligned behavior over time.

While the latter two remain open challenges, I see instruction-following as the essential first step. My current work explores how visual language models can be adapted into long-horizon, instruction-following agents. I am particularly interested in augmenting these models with memory and lightweight reasoning capabilities, aiming to bridge the gap between passive perception and active decision-making.

As Rich Sutton wrote in *The Bitter Lesson*,

> The biggest lesson... is that general methods that leverage computation are ultimately the most effective, and by a large margin.

This insight continues to shape my perspective. While end-to-end training remains a viable path, I believe leveraging foundation models as flexible substrates — and teaching them to interact, remember, and reason — may be a more pragmatic route toward building truly autonomous systems.


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 The Paper "JARVIS-VLA: Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse" are accepted by ACL 2025

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/jarvis-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JARVIS-VLA: Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse](https://craftjarvis.github.io/JarvisVLA/)

**Muyao Li\***, Zihao Wang, Kaichen He, Xiaojian Ma, Yitao Liang

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=QDWK5-YAAAAJ&citation_for_view=QDWK5-YAAAAJ:u5HHmVD_uO8C) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
-  The first VLA models in Minecraft that can follow human instructions on over 1k different atomic tasks
-  Introduce a novel approach, Act from Visual Language Post-Training, which refines Visual Language Models (VLMs) through visual and linguistic guidance in a self-supervised manner.
</div>
</div>


# 📖 Educations
![](images/PKU.png) &nbsp;&nbsp;*2022.09 - now*, Undergraduate, Yuanpei College, Peking University, Beijing

