---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: img_480068-1-26.jpg
  caption: 'Railway Tunnel, Mammoth Cave, Jenolan. Photo: Pete Baxter'
widget1:
  title: "Join a trip"
  url: '/triplist/'
  image: P3310145.jpg
  text: 'Come caving with SUSS! Want to try something really different? Then go underground with SUSS – we guarantee you experiences you will never forget!. All trips are beginner friendly unless stated otherwise. We run monthly caving trips to Jenolan and Wombeyan and regularly run caving trips further afield such as New Zealand and Tasmania.'
widget2:
  title: "New to caving?"
  url: '/learn/'
  text: 'Never been caving before? All of our trips are beginner friendly unless stated otherwise. Trips are catered to all abilities and members can borrow equipment for free from the club. Caving is a great way to do something different with your weekend; you will explore new places, meet new people and learn a lot of new skills. If you are lucky you may even go where no person has ever gone before.'
  video: '<a href="#" data-reveal-id="videoModal">
            <center><img src="/images/start-video-P5120065.jpg" alt=""/></center>
          </a>'
widget3:
  title: "About Us"
  url: '/about/'
  image: vintage_header_square.jpg
  text: 'SUSS is the oldest caving club on mainland Australia - <a href="/tojoin/">join us</a>. We have an extensive collection of caving literature and a number of caving publications available for purchase. Are you a member of another caving club. Learn more about our collections here. Get in touch with the <a href="/about/committee.html">committee</a>.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /tojoin/
  text: Join us now ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/KwvaeezmX4w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
