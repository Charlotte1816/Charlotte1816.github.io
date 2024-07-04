<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Charlotte"
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
# prepath = "yourproject"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
rss_website_title = "私と物理と芸術と"
rss_website_descr = "私と物理と芸術と"
rss_website_url   = "https://charlotte1816.github.io"
rss_full_content = true
+++

<!--
Add here global latex commands to use throughout your pages.
-->

<!--数式マクロ-->

\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}

<!--図マクロ-->

\newcommand{\figenv}[3]{
~~~
<figure style="text-align:center;">
<img src="!#2" style="padding:0;#3" alt="#1"/>
<figcaption>#1</figcaption>
</figure>
~~~
}

<!--定理環境-->

\newcommand{\truth}[2]{
  @@truth
  **事実**: (!#1)
  #2
  @@
}

\newcommand{\eg}[2]{
  @@eg
  **例**: (!#1)
  #2
  @@
}

\newcommand{\def}[2]{
  @@eg
  **定義**: (!#1)
  #2
  @@
}



