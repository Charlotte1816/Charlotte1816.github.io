<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Charlotte"
mintoclevel = 2
maxtoclevel = 3

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
generate_sitemap = true
rss_website_title = "Physics Notes"
rss_website_descr = "Physics Notes"
rss_website_url   = "https://charlotte1816.github.io"
rss_full_content = true
keep_path = ["google2f11fcc6b81334b8.html"]
+++



<!--
Add here global latex commands to use throughout your pages.
-->

<!--数式マクロ-->

\newcommand{\R}{\mathbb{R}}
\newcommand{\N}{\mathbb{N}}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\dd}[1]{\mathrm{d}#1}
\newcommand{\dv}[2]{\frac{\mathrm{d}#1}{\mathrm{d}#2}}
\newcommand{\pdv}[2]{\frac{\partial #1}{\partial #2}}
\newcommand{\bm}[1]{\boldsymbol{#1}}
\newcommand{\grad}{\mathrm{grad}\,}

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

\newcommand{\note}[1]{
  @@note
  **Notation**:
  #1
  @@
}

\newcommand{\eg}[1]{
  @@eg
  **例**:
  #1
  @@
}

\newcommand{\def}[1]{
  @@def
  **定義**:
  #1
  @@
}

\newcommand{\thm}[1]{
  @@box
  **定理**:
  #1
  @@
}

\newcommand{\prop}[1]{
  @@box
  **命題**:
  #1
  @@
}

\newcommand{\lem}[1]{
  @@box
  **補題**:
  #1
  @@
}

\newcommand{\cor}[1]{
  @@box
  **系**:
  #1
  @@
}

\newcommand{\rem}[1]{
  @@rem
  **注意**:
  #1
  @@
}

