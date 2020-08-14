---
title: Dungeons
permalink: /cs_cz/dungeons
lang: cs_cz
---

{% for dungeon in site.dungeons %}

<h3> {{ dungeon["cs-CZ_name"] }} </h3>

> {{ dungeon["cz-CZ_description"] }}

**Tier {{ dungeon.tier }} Dungeon**

<table>
    <tr>
        {% for monster in dungeon.monsters %}
            <td width = '50'>
                <img width = '50' src = '{{site.baseurl}}{{ monster.image }}' />
            </td>
        {% endfor %}
    </tr>
    <tr>
        {% for monster in dungeon.monsters %}
            <td width = '50'>
                x{{ monster.quantity }}
            </td>
        {% endfor %}
    </tr>
</table>

{% endfor %}