---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<div class="posts">
    {% for post in site.posts %}
    <div class="post">
        <a href="{{ post.url }}">
            <h2>{{ post.title }}</h2>
            <div class="post-excerpt">
                {{ post.excerpt }}
            </div>
        </a>
    </div>
    {% endfor %}
</div>