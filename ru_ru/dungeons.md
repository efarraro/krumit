---
title: Dungeons
permalink: /ru_ru/dungeons
lang: ru_ru
---

{% for dungeon in site.dungeons %}
<!-- <a href = '{{ item.url }}'>{{ item.name }}</a> -->
<!--<tr>
        <td><a href = '{{ dungeon.url }}'>{{ dungeon.name }}</a></td>
    </tr>-->

<h3> {{ dungeon["ru-RU_name"] }} </h3>

> {{ dungeon["ru-RU_description"] }}

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