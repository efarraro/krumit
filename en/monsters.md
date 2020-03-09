---
title: Monsters
permalink: /en/monsters
lang: en
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["EN_name"] }}</h3>
> {{monster["EN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["EN_description"] }}</td>
    </tr>
</table>
{% endfor %}