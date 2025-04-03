---
layout: home
title: tdTomato's Blog
permalink: /
---

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y/%m/%d" }}
{% endfor %}


## Acknowledgements

### 🔧 Theme License

The theme used in this project, [jekyll-gitbook](https://github.com/sighingnow/jekyll-gitbook), is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).  
See the original [LICENSE](https://github.com/sighingnow/jekyll-gitbook/blob/master/LICENSE) for full details.

Special thanks to [@sighingnow](https://github.com/sighingnow) for the fantastic [jekyll-gitbook](https://github.com/sighingnow/jekyll-gitbook) theme.

### ✍️ Content License

All original content in this repository – including blog posts, images, and other media – is © 2025 tdTomato.  

> Please do not reuse blog content without appropriate credit or permission.

> The contents on this site are solely those of the author  
> and do not reflect those of any employer, organization, or affiliated entity.
