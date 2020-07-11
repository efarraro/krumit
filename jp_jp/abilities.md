---
title: アビリティ
permalink: /jp_jp/abilities
lang: jp_jp
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["jp-JP_name"] }}</h3>
> {{ability["jp-JP_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["jp-JP_description"] }}</td>
    </tr>
</table>
{% endfor %}

