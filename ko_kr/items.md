---
title: 아이템 
permalink: /ko_kr/items
lang: ko_kr
---
{% for item in site.items %}
<h3 id = '{{item.tile_id}}'>{{ item["ko-KR_name"] }}</h3>
> {{item["ko-KR_flavor"]}}
<table>
    <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
        </td>
        <td>{{ item["ko-KR_description"] }}</td>
    </tr>
</table>
{% endfor %}

