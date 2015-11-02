---
layout: home
---

<div class="index-content project">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/marshall/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/marshall/life"><span>Life</span></a></li>
            <li style="text-align:right"><a href="/marshall/fitness"><span>Fitness</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.life %}
            <li>
                <h2>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
