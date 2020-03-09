---
title: 道具
permalink: /zh_cn/items
lang: zh_cn
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["zh-CN_name"] }}</h3>
> {{item["zh-CN_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["zh-CN_description"] }}</td>
    </tr>
</table>
{% endfor %}

