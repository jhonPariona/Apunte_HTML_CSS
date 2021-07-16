<h1 align="center">
  <a href="https://www.w3schools.com/html/default.asp" target="_blank">
    <img src="https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif" alt="HTML" width="60"/>
  </a>
  <a href="https://www.w3schools.com/Css/default.asp" target="_blank">
    <img src="https://media.giphy.com/media/fsEaZldNC8A1PJ3mwp/giphy.gif" alt="HTML" width="60"/>
  </a>
</h1>

## 📜 INDICE

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">🎉{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## 📜 Paginas resueltas

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">🥽{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>
