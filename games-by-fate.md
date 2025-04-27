---
title: Games (listed by fate)
---

This page lists the games in the archive based on the current fate of them.

When determining the fate of a game, the following classifications are used:

- [Abandonware](#abandonware)
- [Theseus'd](#theseusd)
- [Finished](#finished)
- [Active](#active)
- [Open Sourced](#open-sourced)
- [Complicated](#complicated)

---

## Abandonware
Games which have been abandoned by the original developer. While still copyrighted, there

<ul>
{% for game in site.games %}
	{% if game.fate == "Abandonware" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

## Theseus'd
Games which are still being actively developed, but have morphed to be more or less unrecognisable from what the game used to be during its early days. The entries for such games usually describe the game as it was back then, and usually a coarse cut-off date is determined for when things changed.

<ul>
{% for game in site.games %}
	{% if game.fate == "Theseus'd" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

## Finished
Games which are finished and is likely not seeing any further development, but is still being kept available by the developer in some form, potentially with fixes for newer devices but not much beyond that.

<ul>
{% for game in site.games %}
	{% if game.fate == "Finished" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

## Active
Games which are still being actively developed.

<ul>
{% for game in site.games %}
	{% if game.fate == "Active" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

*Nothing here yet...*

## Open sourced
Games which have been fully open sourced and lives on in some form being maintained and developed by the community. For sake of pragmatism, games which are under a non-free license but still one that allows for the community to further develop it is considered under this category.

<ul>
{% for game in site.games %}
	{% if game.fate == "Open sourced" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

## Complicated
It's complicated.

<ul>
{% for game in site.games %}
	{% if game.fate == "Complicated" %}
		<li><a href="{{ game.url }}">{{ game.title }}</a></li>
	{% endif %}
{% endfor %}
</ul>

*Nothing here yet...*
