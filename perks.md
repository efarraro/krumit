---
title: Perks
permalink: /perks
---

<table>
{% for perk in site.perks %}

<tr>
        <td>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk.name }}</td>
        <td>{{ perk.description }}</td>
    </tr>
{% endfor %}
</table>
