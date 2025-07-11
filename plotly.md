---
layout: default
title: My Page with Plotly
description: Page with the Plotly.
---
 
## Welcome to another page


This is my interactive Plotly chart:

# {% include_relative my_interactive_plot.html %}
<iframe src="{{ '/my_interactive_plot.html' | relative_url }}"
        width="100%"
        height="600px"
        frameborder="0"
        scrolling="no"
        seamless="seamless"></iframe>
        
[back](./)
