Welcome to Terminal K. Here be rambling.

## Pinned

- [My photography gear](https://kaiboyjiang.github.io/2026/11/04/my-photography-gear.html)

- [What I'm reading right now](https://kaiboyjiang.github.io/2026/08/31/reading-list.html)

## Posts

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
