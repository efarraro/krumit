---
title: Items
permalink: /ru_ru/items
lang: ru_ru
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["ru-RU_name"] }}</h3>
> {{item["ru-RU_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["ru-RU_description"] }}</td>
    </tr>
</table>
{% endfor %}

