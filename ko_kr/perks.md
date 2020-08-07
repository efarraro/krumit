---
title: 특성
permalink: /ko_kr/perks
lang: ko_kr
---
<table>
{% for perk in site.perks %}

<tr>
        <td width = '75' height='75'>
            <img width = '75' height = '75' src = '{{site.baseurl}}{{ perk.image }}' />
        </td>
        <td>{{ perk["ko-KR_name"] }}</td>
        <td>{{ perk["ko-KR_description"] }}</td>
    </tr>
{% endfor %}
</table>

