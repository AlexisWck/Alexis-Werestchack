---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Bienvenue sur mon site !

Je m'appelle Alexis Werestchack, et je suis étudiant en Master de Politique Publique et Développement Humain à l'Université de Maastricht. Ce site est un espace où je partage mes projets, mes réflexions et mes compétences techniques.

## Navigation
- [À propos]({{ site.baseurl }}/about)
- [CV]({{ site.baseurl }}/cv)
- [Blog]({{ site.baseurl }}/blog)
- [Projets]({{ site.baseurl }}/projects)
- [Téléchargements]({{ site.baseurl }}/download)

## Dernières actualités
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

---

### À propos de moi
Je m'intéresse à la réduction de la pauvreté, aux politiques du marché du travail et à l'aide humanitaire, en particulier dans les zones de conflit. J'explore également l'intersection entre la politique et la technologie.

[En savoir plus sur moi]({{ site.baseurl }}/about)
