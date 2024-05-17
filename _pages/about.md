---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======
Hi! I am a computer science Ph.D. student at <b>[UCLA](https://www.ucla.edu/)</b> advised by [Prof. Nanyun (Violet) Peng](https://vnpeng.net/). Previously, I recieved my master's degree at the <b>University of Tehran</b> advised by [Prof. Yadollah Yaghoobzadeh](https://yyaghoobzadeh.github.io/){:target="_blank"} and [Prof. Mohammad Taher Pilehvar](https://pilehvar.github.io/){:target="_blank"}.
<!-- Hi! I am a master's student at the <b>University of Tehran</b>, and I have the pleasure of working with [Mohammad Taher Pilehvar](https://pilehvar.github.io/){:target="_blank"}, [Yadollah Yaghoobzadeh](https://yyaghoobzadeh.github.io/){:target="_blank"}, and [Azadeh Shakery](https://ece.ut.ac.ir/en/~shakery){:target="_blank"} on natural language processing (NLP) and deep learning. -->

My primary research interest lies in the area of <b>Natural Language Processing</b> (NLP), where I have done research on quantifying token attribution in Transformers [(ACL2023, ](https://aclanthology.org/2023.acl-long.149/)[NAACL2022)](https://aclanthology.org/2022.naacl-main.19), Metaphors in pre-trained language models [(ACL2022)](https://aclanthology.org/2022.acl-long.144/), layer-wise probing BERToids [(BlackboxNLP@EMNLP2021)](https://aclanthology.org/2021.blackboxnlp-1.29), and finding important examples by gradient-based dataset pruning [(ENLSP@NeurIPS2022)](https://arxiv.org/abs/2211.05610).
<!-- My B.Sc. final project was about assessing toxic detection knowledge of foundation models where I showed their interesting ability gained in pre-training as well as possible biases towards specific persons or groups. -->

Feel free to [email](mailto:mohsenfayyaz@cs.ucla.edu) me or check my [Curriculum Vitae](/files/MohsenFayyaz_CV.pdf){:target="_blank"}.

News
======
------
<font size="3">
<div style="overflow-y: auto; max-height: 300px; padding-right: 10px; font-size: 15.5px;">
<ul>
	<li>
		<b>Jul 2023</b>: Our paper "DecompX: Explaining Transformers Decisions by Propagating Token Decomposition" has been accepted to <b>ACL 2023</b>! 
		<a href="https://aclanthology.org/2023.acl-long.149/" target="_blank">[paper]</a>
	</li>
	<li>
		<b>Nov 2022</b>: Our paper "BERT on a Data Diet: Finding Important Examples by Gradient-Based Pruning" has been accepted to <b>ENLSP@NeurIPS2022</b>! 
		<a href="https://arxiv.org/abs/2211.05610" target="_blank">[paper]</a>
	</li>
	<li>
		<b>Apr 2022</b>: Our paper "GlobEnc: Quantifying Global Token Attribution by Incorporating the Whole Encoder Layer in Transformers" has been accepted to <b>NAACL 2022</b> main conference! 
		<a href="https://aclanthology.org/2022.naacl-main.19.pdf" target="_blank">[paper]</a>
		<a href="https://youtu.be/jgd9kUJlug4" target="_blank">[video]</a>
	</li>
	<li>
		<b>Mar 2022</b>: Our paper "Metaphors in Pre-Trained Language Models: Probing and Generalization Across Datasets and Languages" has been accepted to <b>ACL 2022</b> main conference! 
		<a href="https://aclanthology.org/2022.acl-long.144/" target="_blank">[paper]</a>
		<a href="https://www.youtube.com/watch?v=UKWFZSiP7OY" target="_blank">[video]</a>
	</li>
	<li>
		<b>Sep 2021</b>: Our paper "Not All Models Localize Linguistic Knowledge in the Same Place: A Layer-wise Probing on BERToids’ Representations" has been accepted to <b>EMNLP 2021</b> (BlackboxNLP)! 
		<a href="https://aclanthology.org/2021.blackboxnlp-1.29/">[paper]</a>
		<!-- <a href="/posts/layer-wise-probing-on-bertoids">[blog]</a> -->
	</li>
	<li>
		<b>Aug 2021</b>: Accepted to enroll in graduate school as a top student without passing the entrance examinations, University of Tehran
	</li>
	<li>
		<b>Dec 2020</b>: Received Faculty of Engineering Award for ranking 1st among all Computer Engineering students, University of Tehran
	</li>
	<li>
		<b>Dec 2020</b>: <a href="https://nlpdataset.ir/" target="_blank">nlpdataset.ir</a> is online for listing NLP datasets and tools for  research and development in Farsi NLP.
	</li>
	<li>
		<b>Dec 2019</b>: Received Faculty of Engineering Award for ranking 3rd among all Computer Engineering students, University of Tehran
	</li>
</ul>
</div>
</font>

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
