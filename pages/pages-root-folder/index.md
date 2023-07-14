---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
# 
# O layout frontpage faz o ultimo arquivo de _posts aparecer na pagina inicial
#
layout: page-fullwidth
title: "SEMESO 2023"
header:
   image_fullwidth: "header_unsplash_4.jpg"
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

{% include semeso.md %}
