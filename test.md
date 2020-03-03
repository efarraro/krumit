All item list!

{% for item in site.items %}
   <a href = '{{ item.url }}'>{{ item.name }}</a>
{% endfor %}

end of list
