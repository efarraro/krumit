---
title: ítems 
permalink: /es_es/items
lang: es_es
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["es-ES_name"] }}</h3>
> {{item["es-ES_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["es-ES_description"] }}</td>
    </tr>
</table>
{% endfor %}

