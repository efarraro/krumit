---
title: Heroes
permalink: /ko_kr/heroes
lang: ko_kr
---
<h3 id = 'warrior'>브루노</h3>
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

<h3 id = 'mage'>그레이비어드</h3>
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

<h3 id = 'rogue'>미스치프</h3>
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

<h3 id = 'necromancer'>멀도르프</h3>
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

<h3 id = 'priest'>로즈</h3>
<div>
{% for item in site.items %}
{% if item.hero == "priest" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "priest" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>

<h3 id = 'hunter'>바르파</h3>
<div>
{% for item in site.items %}
{% if item.hero == "hunter" %}
<a href = 'items#{{ item.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ item.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
{% for ability in site.abilities %}
{% if ability.hero == "hunter" %}
<a href = 'abilities#{{ ability.tile_id }}'>
<img width = '100' height = '100' src = '{{site.baseurl}}{{ ability.image }}' />
</a>
{% else %}
{% continue %}
{% endif %}
{% endfor %}
</div>