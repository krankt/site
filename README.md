# Site

## Getting Started

Assuming Docker and Docker Compose are installed:

```shell
cd dir/of/your/jekyll/site
docker run -p 80:4000 -v $(pwd):/site jekyll:local
```

It will mount your current path into the containers `/site`, `bundle install` before running `jekyll serve` to , serve it at `http://localhost:4000`.

## LICENCE

Docker/Jekyll part from https://github.com/BretFisher/jekyll-serve, MIT licence
Content (c) Kränkt with friends

## GA Code

UA-110469604-1

```
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-110469604-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-110469604-1');
</script>
```