---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="intro">
<p align="justify">
I am Ahmad Bin Rabiah, a master's student in Electrical and Computer Engineering at Purdue University, currently working under the guidance of <a href="https://www.qiguo.org">Professor Qi Guo</a>. My research interests focus on artificial intelligence and deep learning. Specifically, my current research involves improving image reconstruction for multi-camera systems by leveraging the redundancy of objects present in multi-camera sensors. Prior to my current work, I spent time at <a href="https://www.psdsarc.org.sa/">PSDSARC</a> working on research and development of various signal processing systems. I completed my undergraduate studies at <a href="https://ksu.edu.sa/en">KSU</a>, where I was co-advised by Professors <a href="https://faculty.ksu.edu.sa/en/dsaleh">Saleh Alshebeili</a> and <a href="https://faculty.ksu.edu.sa/en/omaldayel">Omar Aldayel</a>.
</p>
</div>
  
<hr>

<div><h3>News</h3></div>
<div id="news">
<style> table, tr, td { border: none; }</style>
<div style="height:250px;overflow:auto;border:0px;border-collapse: collapse;">
	<table border="none" style="border:0px;border-collapse: collapse;" rules="none">
		<colgroup><col span="1" style="width: 12%;"><col span="1" style="width: 88%;"></colgroup>
		<tbody>
			<tr><td><b> November 2022:</b></td>
				<td> Our work on <a href="https://arxiv.org/abs/2211.07390"> StereoISP: Rethinking Image Signal Processing for Dual Camera Systems</a> is available on arXiv!</td></tr>
			<tr><td><b> August 2021:</b></td>
				<td> Began ECE MS at Purdue!</td></tr>
			<tr><td><b> January 2021:</b></td>
				<td> 
					Our work on <a href="https://ieeexplore.ieee.org/abstract/document/9266553"> Haiku: Efficient Authenticated Key Agreement with Strong Security Guarantees for IoT</a> was accepted to RadarConf 2020 in Florence, Italy!
				</td></tr>
			<tr><td><b> September 2020:</b></td>
				<td> Our work on <a href="https://dl.acm.org/doi/abs/10.1145/3427796.3427817"> SDR-Based Hardware Implementation and Performance Measurement of Transmit Beampattern Design Algorithms</a> was accepted to ICDCN 2021 in New York, NY!</td></tr>
		</tbody>
	</table>
</div>


<hr>


<div><h1>Publications</h1></div>
<div id="publications">
    <article>
        <a classa="pub_image"><img src="files/2_stereoisp/snapshot.png"></a>
        <div class="pub_text">
            <h3>StereoISP: Rethinking Image Signal Processing for Dual Camera Systems</h3>
            <h4 class="authors">
		    <b>Ahmad Bin Rabiah</b>, Qi Guo
            </h4>		
            <p>arXiv 2022</p>
            [<a href="https://arxiv.org/pdf/2211.07390">paper</a>]
        </div>
    </article>

    <article>
        <a classa="pub_image"><img src="files/1_haiku/snapshot.png"></a>
        <div class="pub_text">
            <h3>Haiku: Efficient Authenticated Key Agreement with Strong Security Guarantees for IoT</h3>
            <h4 class="authors">
		    Abdulrahman Bin Rabiah, KK Ramakrishnan, Silas Richelson, <b>Ahmad Bin Rabiah</b>, Elizabeth Liri, Koushik Kar
            </h4>
            <p>ICDCN 2021</p> [<a href="https://dl.acm.org/doi/pdf/10.1145/3427796.3427817">paper</a>]
        </div>
    </article>

    <article>
        <a class="pub_image"><img src="files/0_beamforming/snapshot.png"></a>
        <div class="pub_text">
            <h3>SDR-Based Hardware Implementation and Performance Measurement of Transmit Beampattern Design Algorithms</h3>
            <h4 class="authors">
                <b>Ahmad Bin Rabiah</b>, Mohammed Alsakabi, Omar Aldayel, Saleh Alshebeili
            </h4>
            <p>RadarConf 2020</p>
            [<a href="https://www.researchgate.net/profile/Ahmad-Bin-Rabiah/publication/347372921_SDR-Based_Hardware_Implementation_and_Performance_Measurement_of_Transmit_Beampattern_Design_Algorithms/links/5ff826fe299bf140887d99c8/SDR-Based-Hardware-Implementation-and-Performance-Measurement-of-Transmit-Beampattern-Design-Algorithms.pdf">paper</a>]
        </div>
    </article>




  
  
  

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
