# Welcome to the iHRIS Blog

Discover updates, news, and insights about iHRIS. Use the categories and tags to explore specific topics.

## Categories
- [Announcements](/categories/#announcements)
- [Features](/categories/#features)
- [Guides](/categories/#guides)

## Recent Posts
```yaml
{%- for post in blog.posts[:5] %}
- [{{ post.title }}]({{ post.url | url }}) - {{ post.date.strftime('%B %d, %Y') }}
  {{ post.description }}
{%- endfor %}
