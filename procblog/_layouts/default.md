<!doctype html>
<html>
  <head>
     <link rel="stylesheet" href="/assets/css/main.css"> 
    <meta charset="utf-8">
    <title>{{ page.title }} | {{site.title}}</title>
  </head>
  <body>
    <div class="container-fluid" style="padding-top: 1%;">
      {{ content }}
    </div>
    {% include navbar.html %}
  </body>
</html>