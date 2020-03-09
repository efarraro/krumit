---
title: Abilities
permalink: /en/abilities
lang: en
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["EN_name"] }}</h3>
> {{ability["EN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["EN_description"] }}</td>
    </tr>
</table>
{% endfor %}


