---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
limit: 10
show_excerpts: true
entries_layout: list
---

>- 15 years experience developing games and leading teams
>- Highly adaptable Technical Art and Technical Design skillset
>- See my full experience: [{{ site.data.icons.resume }} CV](/cv)


<!--
<br>

<h1 id="page-title" class="page-title p-name animated fadeInRight">Blog</h1>
{: .notice--accent}

{% capture blog_items %}
  {% include documents-collection.html collection='blog' sort_order='reverse' sort_by = 'date' %}
{% endcapture %}

{% include colcade-grid.html items = blog_items %}
-->



<br>


<h1 id="page-title" class="page-title p-name animated fadeInRight">Projects</h1>

{% capture projects_items %}
  {% include documents-collection.html collection='projects' sort_order='reverse' sort_by = 'date' %}
{% endcapture %}

{% include normal-grid.html items = projects_items %}
