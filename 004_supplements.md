---
layout: default
title: Supplements
number: 4
---

# Supplements

Do you have supplementary materials (such as media files) or links for further information for the reader? (minimum 3 additional media files or links)

# Timeline

<iframe class='timeline-iframe' src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1eg1BfdQVPwX_zLjttUXqMwWOeXI6uM8saoYlE_vK_Iw&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

# Supplementary Websites

[United States Holocaust Memorial Museum](https://www.ushmm.org/)

[Jewish Virtual Library Nazi War Crimes Database](https://www.jewishvirtuallibrary.org/nazi-war-crimes-and-trials)



# Supplementary Media Files

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'nurembergvid'" %}
{% include media.html pages=media %}
