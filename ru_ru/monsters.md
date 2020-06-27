---
title: Монстры
permalink: /ru_ru/monsters
lang: ru_ru
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["ru-RU_name"] }}</h3>
> {{monster["ru-RU_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["ru-RU_description"] }}</td>
    </tr>
</table>
{% endfor %}

