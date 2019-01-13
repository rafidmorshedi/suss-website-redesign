---
layout: page
show_meta: false
title: "New to Caving?"
subheadline: "Layouts of Feeling Responsive"
header:
   image_fullwidth: "nz_header_1.jpg"
permalink: "/learn/"
---

Welcome to Sydney University Speleological Society (SUSS), we are a caving society open to everyone. All you need is a desire for adventure!

If you have just signed up for a trip see [Your First Trip]({{ site.url }}{{ site.baseurl }}/learn/first-trip.html) to find out what you need and what to expect.

Sitting on the fence? Don't want to take the plunge and sign up for a trip, but want to learn more? Come along to one of our [social events or monthly club meetings](/triplist.html) to chat to some cavers and learn more.

Not feeling like going underground? We regularly run [non-caving trips](/learn/notcaving,html) throughout the year including canyoning, climbing, liloing, abseiling. Just check the [triplist](/triplist.html) for details.

<ul>
    {% for post in site.categories.learn %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
