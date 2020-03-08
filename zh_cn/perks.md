---
title: Perks
permalink: /zh_cn/perks
lang: zh_cn
---

<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk.name }}</td>
        <td>{{ perk.description }}</td>
    </tr>
{% endfor %}
</table>
