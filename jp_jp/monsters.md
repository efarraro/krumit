---
title: 敵
permalink: /jp_jp/monsters
lang: jp_jp
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["jp-JP_name"] }}</h3>
> {{monster["jp-JP_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["jp-JP_description"] }}</td>
    </tr>
</table>
{% endfor %}

