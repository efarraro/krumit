---
title: Perks
permalink: /en/perks
lang: en
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["EN_name"] }}</td>
        <td>{{ perk["EN_description"] }}</td>
    </tr>
{% endfor %}
</table>
