---
layout: page
permalink: /join/
---

## Join

[Scouting]({{ site.data.units.programs.scouting }}) is a game with a purpose! It is fun because scouts learn by doing fun
activities with their family and friends. They wear the scout uniform, serve
their community, learn scout skills, explore the outdoors, build
self-confidence, develop an understanding of the scout ideals, and learn
leadership skills... all to become their very best future selves.

Scouting is for all youth! Our youngest scouts can begin their adventure as a
[Cub Scout]({{ site.data.units.programs.cub_scouts }}) in Pack 226 when they are in kindergarten. The Pack serves both boys
and girls up through the fifth grade, at which point they can join one of our
two troops in [Scouts BSA]({{ site.data.units.programs.scouts_bsa }}). Both troops serve scouts from sixth grade up through
18 years old.

[{{ site.data.units.church.name }}]({{ site.data.units.church.url }}) is our fantastic home! You can find us meeting
most Monday nights during the school year at, [{{ site.data.units.church.address }}]({{ site.data.units.church.maps_url }}).

The Pack and both troops, all begin at their meetings at 7:00. The Cub Scouts
wrap up by 8:00 and the troops end between 8:15 and 8:30.

To get more information about any of our scout units or to join, please use the
following links:

<ul>
{% for unit in site.data.units.join %}
  <li>{{ unit.audience }}: <a href="{{ unit.more_info }}">{{ unit.label }}</a></li>
{% endfor %}
</ul>
