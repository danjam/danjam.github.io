* [Slim Mustache View](./slim-mustache-view)
* [Clump](./clump)

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.url }})
{% endfor %}
