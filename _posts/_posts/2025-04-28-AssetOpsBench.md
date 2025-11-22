
layout: distill
title: [Your Blog Title]
description: [Your blog post's abstract - no math/latex or hyperlinks!]
date: 2025-04-28
future: true
htmlwidgets: true

# anonymize when submitting 
authors:
  - name: Anonymous 

# do not fill this in until your post is accepted and you're publishing your camera-ready post!
# authors:
#   - name: Albert Einstein
#     url: "https://en.wikipedia.org/wiki/Albert_Einstein"
#     affiliations:
#       name: IAS, Princeton
#   - name: Boris Podolsky
#     url: "https://en.wikipedia.org/wiki/Boris_Podolsky"
#     affiliations:
#       name: IAS, Princeton
#   - name: Nathan Rosen
#     url: "https://en.wikipedia.org/wiki/Nathan_Rosen"
#     affiliations:
#       name: IAS, Princeton 

# must be the exact same name as your blogpost
bibliography: 2025-04-28-distill-example.bib  

# Add a table of contents to your post.
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
toc:
  - name: [Section 1]
  - name: [Section 2]
  # you can additionally add subentries like so
    subsections:
    - name: [Subsection 2.1]
  - name: [Section 3]
---

# ... your blog post's content ...
You must change the title, discription, toc, and eventually the authors fields (ensure that the submission is anonymous for the review process).

Read our sample blog post carefully to see how you can add image assets, and how to write using 
! Read about rendering your post locally below.

Important: make sure your post is completely anonymized before you export and submit it!

Before going any further, it will be useful to highlight exactly what folders and files you are going to add or modify. Even if you use one of our simpler quickstart methods, this will always be what’s happening behind the scenes.

If you clone our repo or download a release, you will find a directory structure that looks like the following (excluding all files and directories that are not relevant to your submission):

your_blogpost_repo/
│
├── _posts
│   ├── 2025-04-28-[YOUR SUBMISSION].md         # <--- Create this markdown file; this is your blogpost
│   └── ...
├── assets
│   ├── bibliography
│   │   ├── 2025-04-28-[YOUR SUBMISSION].bib    # <--- Create this bibtex file
│   │   └── ...
│   ├── html
│   │   ├── 2025-04-28-[YOUR SUBMISSION]        # <--- Create this directory and add interactive html figures
│   │   │   └──[YOUR HTML FIGURES].html
│   │   └── ...
│   ├── img
│   │   ├── 2025-04-28-[YOUR SUBMISSION]        # <--- Create this directory and add static images here
│   │   │   └──[YOUR IMAGES].png
│   │   └── ...
│   └── ...
└── ...
