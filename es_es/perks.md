---
title: Beneficios
permalink: /es_es/perks
lang: es_es
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["es-ES_name"] }}</td>
        <td>{{ perk["es-ES_description"] }}</td>
    </tr>
{% endfor %}
</table>

