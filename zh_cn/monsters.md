---
title: 怪物
permalink: /zh_cn/monsters
lang: zh_cn
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["zh-CN_name"] }}</h3>
> {{monster["zh-CN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["zh-CN_description"] }}</td>
    </tr>
</table>
{% endfor %}

