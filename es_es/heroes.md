---
title: Héroes
permalink: /es_es/heroes
lang: es
---
<h3 id = 'warrior'>Bruno</h3>
<div>
{% for item in site.items %}
{% if item.hero == "warrior" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "warrior" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>

<br /><br />

<h3 id = 'mage'>Barbagrís</h3>
<div>
{% for item in site.items %}
{% if item.hero == "mage" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "mage" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>

<br /><br />

<h3 id = 'rogue'>Travesuras</h3>
<div>
{% for item in site.items %}
{% if item.hero == "rogue" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "rogue" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>

<br /><br />

<h3 id = 'necromancer'>Muldorf</h3>
<div>
{% for item in site.items %}
{% if item.hero == "necromancer" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "necromancer" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>