---
layout: default
title: Analysis
number: 2
---

# Analysis 1
## by Brian Davis
When examining Germany during World War II, it becomes clear that the country committed a plethora of war crimes. This writing will discuss the mistreatment of Jewish people inside camps during the Holocaust. This essay will focus on forced labor, transit camps, and death camps, as these were the locations where most atrocities against Jewish people were committed.  From starvation, overworking, overcrowding, and poor sanitation these are the crimes committed by Germany during WW2. 


# Embedding a Single Image

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'siemensfactory'" %}
{% include media.html pages=media %}

# Embedding a Single Video
{% assign media = site.media_metadata | where_exp: "item", "item.name == 'RiseOfPrussia'" %}
{% include media.html pages=media %}

# Linking to a PDF File

[Download PDF file]({{ site.baseurl }}/media_files/pdfs/newspaper1942.pdf)
