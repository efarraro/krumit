---
layout: default
---
<h2>{{ page.name }}</h2>
<p>
    Tier {{ page.tier + 1 }} Dungeon </br >
    <i> {{ page.description }} </i>
</p>

<h3>Enemies</h3>

<table>
    {% for monster in page.monsters %}
        <tr>
            <td width = '50'>
                <img width = '50' src = '{{ monster.image }}' />
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