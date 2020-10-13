---
title: Heroes
permalink: /jp_jp/heroes
lang: jp_jp
---
<h3 id = 'warrior'>ブルーノ</h3>
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

<h3 id = 'mage'>グレイベアード</h3>
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

<h3 id = 'rogue'>ミスチーフ</h3>
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

<h3 id = 'necromancer'>モルドフ</h3>
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

<h3 id = 'priest'>ローズ</h3>
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

<h3 id = 'hunter'>ヴァルファ</h3>
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