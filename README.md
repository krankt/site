# Kränkt

## Introduktion

Här är vi alla kränkta. Av allt. Är du också kränkt? Se till att du har jävlen installerad, skapa en ny post under *_posts*, kopiera en tidigare som mall. Namnet skall vara *YYYY-MM-DD-en-titel-med-sma-bokstaver.markdown*. Skicka en ryckbegäran till denna förvaring, så kikar en administratör på den och eventuellt sammanfogas din gren med mäster-grenen. Så fort sammanfogningen skett sker ett bygge och din post hamnar på (http://krankt.gratis)[http://krankt.gratis]

### Bilder

Lägg bilder under *assets* katalogen, dessa länkas då med markdown på följande sätt:
```
	![Titel](/assets/bildnamn.png)
``

## Utvecklare, lokalt

Förutsätter att Docker och Docker Compose är installerat:

```shell
cd katalogen/där/du/blir/kränkt
docker run -p 80:4000 -v $(pwd):/site jekyll:local
```

Detta monterar din nuvarande katalog i behållaren `/site`, `bundle install` före du kör `jekyll serve` så serveras kränkt på `http://localhost:4000`.

## LICENCE

Docker/Jekyll part from https://github.com/BretFisher/jekyll-serve, MIT licence
Content (c) Kränkt with friends