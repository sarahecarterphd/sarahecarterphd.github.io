---
permalink: /
title: "Technology Centered on Who We Are and What We Value"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Too often, we feel like technology has a hold of us, rather than using it to live the lives we value. It’s my firm belief that all technology and innovation should be grounded in who we are and what we value. In my research, I explore how we can design technology in a manner that empowers us and puts us back in the driver seat. 

Designing Technology Centered on our Personal Values
======

In particular, I look at how we can design technology to help us make more value-centered decisions when interacting with technology. To do this, I take insights from philosophy concerning human autonomy and translate them into design criteria, taking cues from other disciplines such as the psychology of decision-making, HCI, and value-sensitive design.

Work at TU Delft
======

In my current role, I’m also lucky to have the opportunity to teach and supervise the engineers and scientists of the future. As an educator, I encourage my students to emphatically consider the future people who will eventually be using the technology they will be building, including asking the tough questions: who is this technology for? Who is left out? Why is the technology being built? Are there other solutions? If we want technology that serves us, we need empathic engineers and scientists that are attuned to and willing to anticipate our needs. 

Looking forward
======

In the future, I wish to fulfill my dream of helping others by nurturing the next generation of scientist, continuing to teach ethics to scientists and engineers. I also wish to coach others on how to use technology in a manner that is fulfilling for their life or business. To accomplish this, I will be attending ICF-approved coach training and develop a model to help others use technology in a manner consistent with their values.

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
