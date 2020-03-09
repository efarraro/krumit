---
title: 能力
permalink: /zh_cn/perks
lang: zh_cn
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["zh-CN_name"] }}</td>
        <td>{{ perk["zh-CN_description"] }}</td>
    </tr>
{% endfor %}
</table>

