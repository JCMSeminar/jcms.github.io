---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---


# The JCMS series

The Joint Condensed Matter Seminar (JCMS) series hosts talks with local and international guests,
    covering a wide spectrum of topics in **condensed matter physics**.

The JCMS series is organised by KTH -- Royal Insitute of Technology, Nordita -- Nordic Institute for Theoretical Physics, and SU -- Stockholm University.
    
### <span style="color:red">List of upcoming events:</span>
<ul>
  {% for post in site.upcomingposts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Check out [here](./fullCalendar.html) the complete list of the JCMS events!

## Where

The seminars are hosted by Nordita, in [Albano Building 3](https://campusalbano.se/view/79lbEXZtjqiYeCiUsAIAeG/open), **Mega Room 3:6228**. 

The events take place in **hybrid form**. The zoom link will be sent before the event through our mailing list. 
<br>
If you wish to join the mailing list, don't hesitate to [contact us](#contacts).

## When

The seminars take place on announced **Mondays**, **from 11 am to 12 am**. 

### Fika

Before the seminar, **from 10.45 am to 11 am**, we gather for a coffee/tea with the speaker.
<br>
We encourage you to join and bring your own mug/reusable glass if you have one!


<h2 id="contacts">Contacts</h2>

### The JCMS organising team

KTH: Yuliya Bilinskaya ([yuliyab@kth.se](mailto:yuliyab@kth.se)); Soumi Ghosh ([soumig@kth.se](mailto:soumig@kth.se))


Nordita: Yuefei Liu ([yuefei@kth.se](mailto:yuefei@kth.se))

SU: Lukas König ([lukas.konig@fysik.su.se](mailto:lukas.konig@fysik.su.se)); Caio Naves ([caio.naves@fysik.su.se](mailto:caio.naves@fysik.su.se))
 
 
### Former members of the JCMS organising team

Sreenath K. Manikandan ([sreenath.k.manikandan@su.se](mailto:sreenath.k.manikandan@su.se)); Lukas Rødland ([lukas.rodland@fysik.su.se](mailto:lukas.rodland@fysik.su.se)); Claudia Artiaco ([artiaco@kth.se](mailto:artiaco@kth.se)); Joris Schaltegger ([joriss@kth.se](mailto:joriss@kth.se)); Christoph Fleckenstein ([cfle@kth.se](mailto:cfle@kth.se)); Miguel Martínez ([mfmm@kth.se](mailto:mfmm@kth.se)); Maria Hermanns ([maria.hermanns@fysik.su.se](mailto:maria.hermanns@fysik.su.se)).
