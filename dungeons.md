---
title: Dungeons
permalink: /dungeons
---

{% for dungeon in site.dungeons %}
<!-- <a href = '{{ item.url }}'>{{ item.name }}</a> -->
<!--<tr>
        <td><a href = '{{ dungeon.url }}'>{{ dungeon.name }}</a></td>
    </tr>-->

<h3> {{ dungeon.name }} </h3>

> {{ dungeon.description }}

**Tier {{ dungeon.tier }} Dungeon**

<table>
        {% for monster in dungeon.monsters %}
            <tr>
                <td width = '50'>
                    <img width = '50' src = '{{site.baseurl}}{{ monster.image }}' />
                </td>
                <td width = '50'>
                    x{{ monster.quantity }}
                </td>
                <td>
                    <!-- TODO add a URL here -->
                    {{ monster.name }}
                </td>
            </tr>
        {% endfor %}
</table>


    
{% endfor %}

