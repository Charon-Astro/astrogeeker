---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ site.title }}</title>
  <link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">
</head>
<body>
  {% include header.html %}

  <main>
    <section id="成果展示">
      <h2>成果展示</h2>
      <ul>
        <li><a href="/成果展示/科研论文.html">科研论文介绍</a></li>
        <li><a href="/成果展示/科研项目.html">科研项目介绍</a></li>
      </ul>
    </section>

    <section id="科普资源">
      <h2>科普资源</h2>
      <ul>
        <li><a href="/科普资源/科普书.html">科普书</a></li>
        <li><a href="/科普资源/公开课.html">公开课</a></li>
      </ul>
    </section>

    <!-- 其他部分类似 -->
  </main>

  {% include footer.html %}
</body>
</html>
