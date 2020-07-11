---
title: パーク
permalink: /jp_jp/perks
lang: jp_jp
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["jp-JP_name"] }}</td>
        <td>{{ perk["jp-JP_description"] }}</td>
    </tr>
{% endfor %}
</table>

