---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for job in site.jobs %}
  <h2>
    <a href="{{ job.url | relative_url }}">
      {{ job.title }}
    </a>
  </h2>
{% endfor %}
