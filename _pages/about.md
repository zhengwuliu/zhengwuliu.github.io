---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Research Assistant Professor in the Department of Electrical and Electronic Engineering at the [University of Hong Kong](https://hku.hk) (HKU). I earned my Ph.D. degree from the School of Integrated Circuits at [Tsinghua University](https://www.tsinghua.edu.cn) (THU) in 2023, following my Bachelor of Engineering degree in Microelectronics from the [University of Electronic Science and Technology of China](https://www.uestc.edu.cn) (UESTC) in 2018.

My research interests include compute-in-memory, brain-computer interface and biomedical information processing.

<!-- 这是一个注释，它将不会显示在最终输出中 -->
<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

Selected publications
======

- **Z. Liu**, J. Tang, B. Gao, P. Yao, X. Li, D. Liu, Y. Zhou, H. Qian, B. Hong, H. Wu, “Neural Signal Analysis with Memristor Arrays Towards High-Efficiency Brain-Machine Interfaces”, [Nature Comm.](http://www.nature.com/articles/s41467-020-18105-4), 11, 4234 (2020).

- **Z. Liu**, J. Tang, B. Gao, X. Li, P. Yao, Y. Lin, D. Liu, B. Hong, H. Qian, H. Wu, “Multi-Channel Parallel Processing of Neural Signals in Memristor Arrays”, [Science Adv.](https://doi.org/doi:10.1126/sciadv.abc4797), 6, eabc4797 (2020).

- H. Zhao#, **Z. Liu**#, J. Tang, B. Gao, Q. Qin, J. Li, Y. Zhou, P. Yao, Y. Xi, Y. Lin, H. Qian, H. Wu. “Energy-efficient high-fidelity image reconstruction with memristor arrays for medical diagnosis”, [Nature Comm.](https://www.nature.com/articles/s41467-023-38021-7), 14, 2276 (2023). 

- H. Zhao#, **Z. Liu**#, J. Tang, B. Gao, Y. Zhou, P. Yao, Y. Xi, H. Qian, H. Wu, “Implementation of Discrete Fourier Transform using RRAM Arrays with Quasi-Analog Mapping for High-Fidelity Medical Image Reconstruction”, [IEDM Tech. Dig.](https://ieeexplore.ieee.org/document/9720547), 12.4.1-12.4.4 (2021).

Awards
=====
- ‘IOP Trusted Reviewer’ status, Institute of Physics (IOP) Publishing, 2024
- Integrated Circuit Talent Development Scholarship, China Education Development Foundation, 2023
- President WANG Dazhong Scholarship, Tsinghua University, 2022
- Integrated Circuit Scholarship, Chinese Institute of Electronics, 2022
- National Scholarship for Postgraduates, Ministry of Education, PRC, 2020
- National Scholarship for Undergraduates, Ministry of Education, PRC, 2016

<!-- 
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).-->

<!-- 
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

-->
