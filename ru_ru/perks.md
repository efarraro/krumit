---
title: Perks
permalink: /ru_ru/perks
lang: ru_ru
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["ru-RU_name"] }}</td>
        <td>{{ perk["ru-RU_description"] }}</td>
    </tr>
{% endfor %}
</table>

