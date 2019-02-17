---
layout: page-fullwidth
title: "About SUSS"
#subheadline: "How to use Feeling Responsive"
#teaser: "The documentation is a work in progress..."
permalink: "/about/"
header:
   image_fullwidth: "cooleman_camping.jpg"
---

Come caving with SUSS! Sydney University's only truly underground society!

Want to try something really different? Then go underground with SUSS – we guarantee you experiences you'll never forget!

Just imagine a room the size of a cathedral, over 100m high and totally dark. Then a torch beam emerges through a small hole in the floor, shafting upwards to pick out the shapes of shimmering shawls and dripping stalactites. You climb up through the boulders, straining to see the sides of this enormous cavern. As your companions join you, the chamber is lit up piece by piece, with the sounds of dripping water echoing around the walls; and somewhere in the distance, the mysterious rumbling of an underground river.

No matter what you're into – whether a full-on expedition to some of the Southern Hemisphere's deepest caves in New Zealand, abseiling down subterranean waterfalls to discover kilometres of passage never seen before, or merely a relaxing weekend trip to Jenolan or Wombeyan taking in the natural beauty of the caves and valleys – SUSS can assist.

With trips virtually every weekend catering for all levels of experience, you're certain to find an activity for you.

SUSS is great value – your membership fee entitles you to receive our bulletin, attend trips and use SUSS equipment such as lights, helmets, ladders and ropes.

Many SUSS members are experienced in abseiling and rope techniques, and field days are regularly conducted in order to instruct interested members free of charge. Informal meetings are held monthly at which slides are often shown and our future activities discussed. You also automatically become a member of the Australian Speleological Federation, the national caving body, and receive their magazine Caves Australia (not available to 1st time Sydney University members in their first year of membership).

But the great part of being a SUSS member is the experiences you'll have in some of the most beautiful yet rarely seen parts of the world, maybe even going where no-one has been before.

SUSS meetings are held on the first Thursday of every month (except January) in the Holme Common Room on the first floor of the Holme Building, Science Road, at Sydney University, from 7:30pm onwards. If you can't make it to a meeting, more information is available just by looking around on this website or feel free to contact anyone on the

<ul>
    {% for post in site.categories.about %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
