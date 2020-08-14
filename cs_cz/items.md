---
title: Předměty
permalink: /cs_cz/items
lang: cs_cz
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["cs-CZ_name"] }}</h3>
> {{item["cs-CZ_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["cs-CZ_description"] }}</td>
    </tr>
</table>
{% endfor %}
