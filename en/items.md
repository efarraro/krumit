---
title: Items
permalink: /en/items
lang: en
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["EN_name"] }}</h3>
> {{item["EN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["EN_description"] }}</td>
    </tr>
</table>
{% endfor %}
