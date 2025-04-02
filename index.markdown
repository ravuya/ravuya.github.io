---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% comment %}
FAQ? Links to the old archive page?
{% endcomment %}

I am in the process of migrating some of the content from [the old Ravuya Games website](https://web.archive.org/web/20241114190354/http://ravuya.com/) to this new one. Please check back soon (or subscribe to the RSS feed) to see more posts and journals!

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
