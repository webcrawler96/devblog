# Welcome to Webcrawler96's Dev Blog!
The purpose of this blog is to record my progress during the 2022 Learn Jam!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: 'https://webcrawler96.github.io/devblog/'}}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
