---
title: Abilities
permalink: /ko_kr/abilities
lang: ko_kr
---
{% for ability in site.abilities %}
<h3 id = '{{ability.tile_id}}'>{{ ability["ko-KR_name"] }}</h3>
> {{ability["ko-KR_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
        </td>
        <td>{{ ability["ko-KR_description"] }}</td>
    </tr>
</table>
{% endfor %}

