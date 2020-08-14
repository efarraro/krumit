---
title: Odznaky
permalink: /cs_cz/perks
lang: cs_cz
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["cs-CZ_name"] }}</td>
        <td>{{ perk["cs-CZ_description"] }}</td>
    </tr>
{% endfor %}
</table>
