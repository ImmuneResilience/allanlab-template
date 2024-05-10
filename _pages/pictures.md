---
title: "Immune Resilience - Pictures"
layout: piclay
excerpt: "ImmRes -- Pictures"
permalink: /pictures/
---

# Pictures

## Halifax
Coming soon! We haven't been here very long...

# Perth
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/rainbowbridge2.jpg" width="60%">
</figure>
On the Rainbow Bride by PCH & TKI

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/team_art.jpg" width="60%">
</figure>
Everyone plays a part: putting together everyone's piece to get the picture.

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/frostbite.jpg" width="60%">
</figure>
Nothing like spending the day randomizing 1300 frozen samples together.

# Kintampo
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/khrc_team.jpg" width="60%">
</figure>
Site visit with the Maternal Probiotics study team

# Bissau
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/temkubali.jpg" width="60%">
</figure>
A beutiful view from the Bigajos

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/tmp2-2 bissauteam.jpg" width="60%">
</figure>
Our wonderful study team for our BCG InSitu study

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/tmp2-2 tklabbissau.jpg" width="60%">
</figure>
Prof. Kollmann tries to not get any sweat into the test tubes



## Gallery
(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>


