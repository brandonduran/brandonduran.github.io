---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**2025**

**Duran, B.M.**, Wall, C.J., Lutsko, N.J., Michibata, T., Ma, P.L., Qin, Y., Duffy, M.L., Medeiros, B., and Debolskiy, M. A new method for diagnosing effective radiative forcing from aerosol-cloud interactions in climate models (2025). *Atmospheric Chemistry and Physics*. https://doi.org/10.5194/acp-25-2123-2025. ([manuscript](https://acp.copernicus.org/articles/25/2123/2025/))

Wall, C.J, Paynter, D., Qin, Y., Debolskiy, M., Duffy, M.L., Michibata, T., **Duran, B.M.**, Lutsko, N.J., Ma, P.L., Medeiros, B., Storelvmo, T., and Zhao, M. Decomposing Cloud Radiative Feedbacks by Cloud-Top Phase (2025). *Journal of Climate*. https://doi.org/10.1175/JCLI-D-24-0538.1. ([manuscript](https://journals.ametsoc.org/view/journals/clim/aop/JCLI-D-24-0538.1/JCLI-D-24-0538.1.xml))


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
