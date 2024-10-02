---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**2024**

**Duran, B.M.**, Wall, C.J., Lutsko, N.J., Michibata, T., Ma, P.L., Qin, Y., Duffy, M.L., Medeiros, B., and Debolskiy, M. A new method for diagnosing effective radiative forcing from aerosol-cloud interactions in climate models (preprint). *Atmospheric Chemistry and Physics*. https://doi.org/10.5194/egusphere-2024-3063. ([manuscript](https://egusphere.copernicus.org/preprints/2024/egusphere-2024-3063/))

Wall, C.J, Paynter, D., Qin, Y., Debolskiy, M., Duffy, M.L., Michibata, T., **Duran, B.M.**, Lutsko, N.J., Ma, P.L., Medeiros, B., Storelvmo, T., and Zhao, M. Decomposing Cloud Radiative Feedbacks by Cloud-Top Phase (submitted). *Journal of Climate*.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
