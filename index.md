---
permalink: /
---

# The Old Android Game Archive
The Old Android Game Archive is a website which aims to catalogue and highlight old and otherwise forgotten games on the Android platform, with a timeframe of around 2008-2013.

***Note!** This website is still a work in progress.* But feel free to still browse around.

## Games list
This is a list of the games that currently have entries:

{% for game in site.games %}
- [{{ game.title }}]({{ game.url }})
{%- endfor %}

## Miscellaneous articles
Other articles written related to old versions of Android:

(nothing yet)

## Can I add games?
At the moment the games list is curated by ROllerozxa based on his personal experiences with mobile gaming back in the day, and it isn't accepting submissions from others currently.

To submit corrections for existing game pages, you can do so on [GitHub](https://github.com/rollerozxa/android.voxelmanip.se).
