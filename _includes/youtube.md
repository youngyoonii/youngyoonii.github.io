<h2 id="youtube" style="margin: 2px 0px -15px;">YouTube</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.youtube.main %}

<li>
<div class="pub-row">
  <!-- 왼쪽 썸네일 -->
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    <a href="https://www.youtube.com/watch?v={{ link.youtube_id }}" target="_blank">
      <img src="https://img.youtube.com/vi/{{ link.youtube_id }}/0.jpg" class="teaser img-fluid z-depth-1" style="width:100%; height:auto;">
    </a>
  </div>

  <!-- 오른쪽 텍스트 -->
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title">
      <a href="https://www.youtube.com/watch?v={{ link.youtube_id }}" target="_blank">{{ link.title }}</a>
    </div>
    <div class="author"><small>{{ link.date }}</small></div>
    <div class="periodical"><em>{{ link.desc }}</em></div>
  </div>
</div>
</li>
<br>

{% endfor %}

</ol>
</div>
