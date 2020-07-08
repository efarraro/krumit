---
title: PRZECIWNICY
permalink: /pl_pl/monsters
lang: pl_pl
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["pl-PL_name"] }}</h3>
> {{monster["pl-PL_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["pl-PL_description"] }}</td>
    </tr>
</table>
{% endfor %}