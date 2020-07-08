---
title: PRZEDMIOTY
permalink: /pl_pl/items
lang: pl_pl
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["pl-PL_name"] }}</h3>
> {{item["pl-PL_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["pl-PL_description"] }}</td>
    </tr>
</table>
{% endfor %}
