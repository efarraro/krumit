---
title: アイテム
permalink: /jp_jp/items
lang: jp_jp
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["jp-JP_name"] }}</h3>
> {{item["jp-JP_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["jp-JP_description"] }}</td>
    </tr>
</table>
{% endfor %}

