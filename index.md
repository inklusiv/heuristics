---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="row">
{% for heuristic in site.data.heuristic %}
    <div class="col-xs-4">
    <div class="box">
        <img src="{{ heuristic.img_url }}" alt="" />
        <h2>{{ heuristic.title }}</h2>
        <p>{{ heuristic.statement }}</p>
        <div class="align-center">
        <button type="button" class="dqpl-button-primary">Action 1</button>
        <button type="button" class="dqpl-button-primary">Action 2</button>
        </div>
    </div>
    </div>
{% endfor %}
</div>

