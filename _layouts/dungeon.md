---
layout: default
---
<h2>{{ page.name }}</h2>
{{ page.description }}

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
                {{ monster.name }}
            </td>
        </tr>
    {% endfor %}
</table>