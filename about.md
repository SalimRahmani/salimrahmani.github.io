---
title: About
layout: page
---
![Profile Image]({{ site.url }}/{{ site.picture }})

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<h2>Skills</h2>

{% for skill in site.data.skills %}
<div class="skillbar clearfix " data-percent="{{ skill.skillbar-percent }}">
	<div class="skillbar-title" style="background: {{ skill.skillbar-title-background }};"><span>{{ skill.title }}</span></div>
	<div class="skillbar-bar" style="background: {{ skill.skillbar-background }};"></div>
	<div class="skill-bar-percent">{{ skill.skillbar-percent }}</div>
</div>
{% endfor %}

<script src="{{ site.url }}/assets/js/skillbar.js"></script>

<h2>Projects</h2>

<ul>
	<li><a href="https://github.com/{{site.github}}/Netflow2Syslog">Netflow2Syslog</a></li>
	<li><a href="https://github.com/{{site.github}}/RhythmUnity">Rhythm Unity</a></li>
	<li><a href="https://github.com/{{site.github}}/CoffeeMachine">Coffee Machine</a></li>
</ul>
