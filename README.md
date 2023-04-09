# Welcome
This is my website created to demonstrate my skills learned in KNES 381.  
The theme that I used is the jekyll theme “Minimal Mistakes”.

# Adding New Posts
Addition of a new post can be done by adding a file to “ _posts”. The file name should be listed as the following: “YEAR-MONTH-DAY-Title.md”.   

This is the recommended front matter:   

defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

# Adding New Images
The addition of new images, videos, or files (such as excel) should be added to “assets/images”.

# Support
If more instructions are needed, please go to the creator of this theme’s [website](https://mmistakes.github.io/minimal-mistakes/)
