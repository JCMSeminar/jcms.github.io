
## The JCMS events

The choice of speakers is still in progress.
<br>
We would like to hear about your interests: if you have a speaker to suggest, let us know by sending an email to the [organising team](https://jcmseminar.github.io/#contacts)!

A complete list of our past and future events can be found in the following.



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


