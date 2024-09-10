---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am currently a senior research scientist at [NEC Laboratories America](https://www.nec-labs.com/research/data-science-system-security/people/zhengzhang-chen/). Previously, I served as a research assistant professor in the [Department of Electrical Engineering & Computer Science at Northwestern University](http://cucis.ece.northwestern.edu/members/zzc472/), where I also completed a one-year postdoctoral fellowship under the supervision of [Prof. Alok Choudhary](http://www.eecs.northwestern.edu/~choudhar/). I received my Ph.D. degree from [Computer Science Department at North Carolina State University](https://www.csc.ncsu.edu/). 

My research aims to advance real-world applications and systems by incorporating advanced intelligence, improved security, and more effective decision-making. I have been primarily working on graph mining, anomaly detection, causal AI, AI security, graph neural networks, text mining, and their applications in computer security, IoT/OT systems, climate science, social media analytics, material science, bioinfomatics, and finance, enabling machine to better understand real-world complex dynamic systems. 

I have published over 80 peer-reviewed research papers in major academic venues such as CVPR, NeurIPS, KDD, ICLR, AAAI, WWW, and IJCAI. My work has been featured in various news media including [NSF News](https://www.nsf.gov/news/news_summ.jsp?cntn_id=125500&org=GEO&from=news), [DOE ASCR Discovery](https://ascr-discovery.science.doe.gov/2012/06/storm-tracking/), [NEC News](https://jpn.nec.com/press/201907/20190708_02.html), [The Conversation](https://theconversation.com/new-hurricane-detection-method-increases-predictability-9537), and [esciencenews](https://esciencenews.com/sources/physorg/2012/09/11/researchers.devise.more.accurate.method.predicting.hurricane.activity). Additionally, my research has led to the filing of more than 70 patents, with 37 patents granted.


News
-----
- \[07/2024\] Serve as SPC for AAAI 2025.
- \[07/2024\] Workshop proposal is accepted: [The 4th International Workshop on Data-Centric AI](https://data-centric-ai-dev.github.io/CIKM2024/) at CIKM2024
- \[06/2024\] Serve as Area Chair for KDD 2025 (August Cycle).
- \[06/2024\] Serve as Area Chair for ACML 2024.
- \[06/2024\] Release of [LEMMA-RCA datasets](https://lemma-rca.github.io/) and [root cause analysis benchmark codes](https://github.com/KnowledgeDiscovery/rca_baselines).
- \[05/2024\] One paper is accepted by KDD 2024.
- \[05/2024\] Serve as SPC for WSDM 2025.
- \[01/2024\] One paper is accepted by The Web Conference (WWW) 2024.
- \[09/2023\] One paper is accepted by NeurIPS 2023.
- \[06/2023\] Serve as SPC for AAAI 2024.
- \[05/2023\] Serve as SPC for WSDM 2024.
- \[05/2023\] Two papers are accepted by KDD 2023.





<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
