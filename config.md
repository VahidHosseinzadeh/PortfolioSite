<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Vahid Hosseinzadeh"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Vahid Hosseinzadeh Portfolio"
website_descr = "Personal site for Vahid Hosseinzadeh"
website_url   = "VahidHosseinzadeh.github.io"
+++

<!-- @def prepath("PortfolioSite") -->
<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\col}[2]{~~~<span style="color:~~~#1~~~">~~~!#2~~~</span>~~~}
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\bolditalic}[1]{_**!#1**_}


@def prepath = "PortfolioSite"
