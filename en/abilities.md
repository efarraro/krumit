---
title: Abilities
permalink: /en/abilities
---

<h1>Abilities</h1>
<table>
{% for ability in site.abilities %}
   
   <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{ site.baseurl }}{{ ability.image }}' />
        </td>
        <td><a href = '{{site.baseurl}}{{ ability.url }}'>{{ ability.name }}</a></td>
        <td>{{ ability.description }}</td>
    </tr>
{% endfor %}
</table>

