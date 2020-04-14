---
title: Monstruos
permalink: /es_es/monsters
lang: es_es
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["es-ES_name"] }}</h3>
> {{monster["es-ES_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["es-ES_description"] }}</td>
    </tr>
</table>
{% endfor %}

