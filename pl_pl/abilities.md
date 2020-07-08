---
title: UMIEJĘTNOŚCI
permalink: /pl_pl/abilities
lang: pl_pl
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["pl-PL_name"] }}</h3>
> {{ability["pl-PL_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["pl-PL_description"] }}</td>
    </tr>
</table>
{% endfor %}


