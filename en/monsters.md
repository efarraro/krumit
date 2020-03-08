---
title: Monsters
permalink: /en/monsters
lang: en
---

<h1>Monsters</h1>
<table>
{% for monster in site.monsters %}
   <!-- <a href = '{{ item.url }}'>{{ item.name }}</a> -->
   <tr>
        <td width = '100'>
            <img width = '100' height = '100' src = '{{site.baseurl}}{{ monster.image }}' />
        </td>
        <td><a href = '{{site.baseurl}}{{ monster.url }}'>{{ monster.name }}</a></td>
        <td>{{ monster.description }}</td>
    </tr>
{% endfor %}
</table>

