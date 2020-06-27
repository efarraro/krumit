---
title: Способности
permalink: /ru_ru/abilities
lang: ru_ru
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["ru-RU_name"] }}</h3>
> {{ability["ru-RU_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["ru-RU_description"] }}</td>
    </tr>
</table>
{% endfor %}

