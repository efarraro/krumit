---
title: Schopnosti
permalink: /cs_cz/abilities
lang: cs_cz
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["cs-CZ_name"] }}</h3>
> {{ability["cs-CZ_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["cs-CZ_description"] }}</td>
    </tr>
</table>
{% endfor %}


