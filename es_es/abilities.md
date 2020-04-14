---
title: Habilidades
permalink: /es_es/abilities
lang: es_es
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["es-ES_name"] }}</h3>
> {{ability["es-ES_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["es-ES_description"] }}</td>
    </tr>
</table>
{% endfor %}

