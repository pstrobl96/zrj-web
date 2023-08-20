# zazitroudnicijinak.cz

Website for zazitroudnicijinak.cz. As main static web generator is used Hugo build upon Golang. Chosed theme is [Arcana](https://github.com/half-duplex/hugo-arcana)

## How run website?

### Hugo install

If you don't have Hugo installed then install it. Guide is available at [Hugo website](https://gohugo.io/installation/).

### Running server

Firstly you need to clone this repo.

`git clone https://github.com/pstrobl96/zrj-web.git`

And everything you need is to run webserver.

```
cd zrj-web
hugo server -D
```

### Generating static files

You know what they say... Slow and steady wins the race

## How to add page?

I dunno ¯\_(ツ)_/¯

## Directory structure for content creators

```
.
└── content
    ├── kontakt.md
    │   └── // contact information about team
    ├── onas.md
    │   └── // about page
    ├── images
    │   ├── ostatni
    │   │   └── // images for pages that aren't ZRJ ones
    │   └── zazit_roudnici_jinak
    │       └── // images for pages about ZRJ
    ├── ostatni
    │   └── <name_of_page>.md
    │       ├── // pages that aren't about ZRJ
    │       └── // name of file always with underscores
    └── zazit_roudnici_jinak
        └── zrj<year_of_event>.md
            ├── // pages that are about ZRJ
            └── // name is named always zrj + year of event.md
```