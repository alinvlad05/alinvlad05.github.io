Hello World
# My interests
I'm interested in gaming and programming!

# My Blog
I like my blog.

# Get in touch
<ul>
<li><a href="https://www.youtube.com">Youtube</a></li>
<li><a href="https://github.com/alinvlad05">GitHub</a></li>
</ul>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<ul>
<li><a href="https://sarah-wecan.github.io/HelloWorld/">Hello World Project</a></li>
<li><a href="https://github.com/thewecanzone/GitHubForDummiesReaders">GitHub For Dummies Repo</a></li>
</ul>
