---
title: Items
permalink: /items
---

<h1>Items</h1>
<table>
{% for item in site.items %}
<!-- <a href = '{{ item.url }}'>{{ item.name }}</a> -->
<tr>
        <td>
            <img width = '100' height = '100' src = '{{ item.image }}' />
        </td>
        <td><a href = '{{ item.url }}'>{{ item.name }}</a></td>
        <td>{{ item.description }}</td>
    </tr>
{% endfor %}
</table>
