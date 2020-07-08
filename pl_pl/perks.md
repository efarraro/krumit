---
title: Zalety
permalink: /pl_pl/perks
lang: pl_pl
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["pl-PL_name"] }}</td>
        <td>{{ perk["pl-PL_description"] }}</td>
    </tr>
{% endfor %}
</table>
