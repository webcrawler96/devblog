# Welcome to Webcrawler96's Dev Blog!
The purpose of this blog is to record my progress during the 2022 Learn Jam!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
