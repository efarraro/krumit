---
title: Monsters
permalink: /ko_kr/monsters
lang: ko_kr
---
{% for monster in site.monsters %}
<h3 id = '{{monster.tile_id}}'>{{ monster["ko-KR_name"] }}</h3>
> {{monster["ko-KR_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td>{{ monster["ko-KR_description"] }}</td>
    </tr>
</table>
{% endfor %}

