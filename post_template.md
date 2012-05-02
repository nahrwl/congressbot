{{description}}

[Govtrack.us Summary]({{link}})
{% if news_stories|length > 0 %}

Recent News:

{% for news_story in news_stories %}
[{{ news_story.title }}]({{ news_story.link }})

{% endfor %}
{% endif %}
