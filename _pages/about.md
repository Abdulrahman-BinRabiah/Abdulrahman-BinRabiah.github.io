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
I am Ahmad Bin Rabiah, a master's student in Electrical and Computer Engineering at Purdue University. I am currently working under the guidance of <a href="https://www.qiguo.org">Professor Qi Guo</a>. My research interests focus on artificial intelligence and deep learning. Specifically, my current research involves improving image construction for multi-camera systems by leveraging the redundancy of objects present in multi-camera sensors. Prior to my current work, I spent time at <a href="https://www.psdsarc.org.sa/">PSDSARC</a> working on research and development of various signal processing systems. I did my undergrad at <a href="https://ksu.edu.sa">KSU</a>, where I was co-advised by Professors <a href="https://faculty.ksu.edu.sa/en/dsaleh">Saleh Alshebeili</a> and <a href="https://faculty.ksu.edu.sa/en/omaldayel">Omar Aldayel</a>.
</p>
</div>
  
  
<div><h1>Publications</h1></div>
<div id="publications">
    <article>
        <a classa="pub_image"><img src="files/publications/6_shaders21k/snapshot.png"></a>
        <div class="pub_text">
            <h3>Procedural Image Programs for Representation Learning</h3>
            <h4 class="authors">
                <b>Manel Baradad</b>, Chun-Fu (Richard) Chen, Jonas Wulff, Tongzhou Wang, Rogerio Feris, Antonio Torralba, Phillip Isola
            </h4>
            <p>NeurIPS 2022</p>
            [<a href="https://arxiv.org/abs/2211.16412">paper</a>]
            [<a href="shaders21k">webpage</a>]
            [<a href="https://github.com/mbaradad/shaders21k">code</a>]
        </div>
    </article>

    <article>
        <a classa="pub_image"><img src="files/publications/5_noise_learning/snapshot.png"></a>
        <div class="pub_text">
            <h3>Learning to See by Looking at Noise</h3>
            <h4 class="authors">
                <b>Manel Baradad*</b>, Jonas Wulff*, Tongzhou Wang, Phillip Isola, Antonio Torralba
            </h4>
            <p>NeurIPS 2021 (Spotlight)</p>
            [<a href="https://arxiv.org/pdf/2106.05963.pdf">paper</a>]
            [<a href="https://mbaradad.github.io/learning_with_noise/">webpage</a>]
            [<a href="https://github.com/mbaradad/learning_with_noise">code</a>]
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
<!--             [<a href="https://github.com/mbaradad/im2pcl">code</a>] -->
<!--             [<a href="https://www.youtube.com/watch?v=qtb-tKgcTJw">video</a>] -->
        </div>
    </article>
<\div>
	

	



  
  
  

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
