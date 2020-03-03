All item list!

{% for item in site.items %}
   {{ item.name }}
	<p>{{ item.content | markdownify }}</p>
{% endfor %}

end of list
