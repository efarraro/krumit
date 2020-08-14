---
title: Nepřátelé
permalink: /cs_cz/monsters
lang: cs_cz
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["cs-CZ_name"] }}</h3>
> {{monster["cs-CZ_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["cs-CZ_description"] }}</td>
    </tr>
</table>
{% endfor %}