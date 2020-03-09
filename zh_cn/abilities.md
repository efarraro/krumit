---
title: 技能
permalink: /zh_cn/abilities
lang: zh_cn
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["zh-CN_name"] }}</h3>
> {{ability["zh-CN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["zh-CN_description"] }}</td>
    </tr>
</table>
{% endfor %}

