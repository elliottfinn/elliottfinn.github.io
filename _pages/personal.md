---
layout: archive
title: ""
permalink: /personal/
author_profile: true
---

![](images/carrizo_nm.jpeg)

<img align="right" src="https://elliottfinn.github.io/images/elliott_mountain.jpeg" alt="Photo" style="width: 325px; border-radius: 10px; padding: 8px 8px 8px 8px"/>

I was raised in Corvallis, Oregon on the lands and waters traditionally used by the Kalapuya. I grew up giving up my bed to [berry researchers](https://www.vacciniumcap.org/node/51) from around the world, raising hogs in 4-H, mushroom hunting in the Coast Range, camping all across Oregon and the West, and exploring the forests and hills in the Willamette Valley. Before graduate school I spent a few years building [Passive Houses](https://en.wikipedia.org/wiki/Passive_house) and worked and traveled throughout Europe and South America, most extensively in Turkey and Colombia. 

When not in the office during the week you can find me running the nearest pickup courts, trail-running, gardening, or cooking tasty food. On the weekends you'll find me hiking, fly fishing, backpacking, and exploring public lands in the West.

![Image 1](images/sarracenia_pic.heic)
*Image taken by [Elliott Finn]*
![Image 1](images/ceramics_work.jpeg)
*Image taken by [Elliott Finn]*
![Image 1](images/Grandma_winona_inspiration.heic)
*Image taken by [Elliott Finn]*
![Image 1](images/catavina_sunglasses pic.jpeg)
*Image taken by [Elliott Finn]*
![Image 1](images/sunrise_bahia de los angeles 2.jpeg)
*Image taken by [Elliott Finn]*
![Image 1](images/mushroom huntin bounty.heic)
*Image taken by [Elliott Finn]*
![Image 1](images/Escameca grande cattle.jpeg)
*Image taken by [Elliott Finn]*


<style>
.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  grid-gap: 15px;
  align-items: stretch;
}

.image-grid img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

.image-caption {
  text-align: center;
  font-style: italic;
}
</style>

<div class="image-grid">
  {% for image in site.static_files %}
    {% if image.path contains 'images/' %}
      <figure>
        <img src="{{ image.path | relative_url }}" alt="Image taken by Elliott Finn">
        <figcaption class="image-caption">Image taken by Elliott Finn</figcaption>
      </figure>
    {% endif %}
  {% endfor %}
</div>




