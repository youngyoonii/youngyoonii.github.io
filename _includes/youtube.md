<h2 id="Youtube" style="margin: 2px 0px -15px;">Publications</h2>

<ol class="bibliography">
  {% for video in site.data.youtube %}
  <li>
    <strong>{{ video.title }}</strong> <br>
    <small>{{ video.date }}</small>
    <p>{{ video.desc }}</p>
    <iframe width="420" height="236" src="{{ video.youtube }}" frameborder="0" allowfullscreen></iframe>
    <br><br>
  </li>
  {% endfor %}
</ol>
