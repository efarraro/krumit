---
title: Dungeons
permalink: /dungeons
---

<table>
{% for dungeon in site.dungeons %}
<!-- <a href = '{{ item.url }}'>{{ item.name }}</a> -->
<tr>
        <td><a href = '{{ dungeon.url }}'>{{ dungeon.name }}</a></td>
    </tr>
{% endfor %}
</table>
