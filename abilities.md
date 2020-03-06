---
title: Abilities
---

<h1>Abilities</h1>
<table>
{% for ability in site.abilities %}
   
   <tr>
        <td>
            <img width = '100' height = '100' src = '{{ ability.image }}' />
        </td>
        <td><a href = '{{ ability.url }}'>{{ ability.name }}</a></td>
        <td>{{ ability.description }}</td>
    </tr>
{% endfor %}
</table>

