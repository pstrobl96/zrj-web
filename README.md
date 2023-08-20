# zazitroudnicijinak.cz

Website for zazitroudnicijinak.cz. As main static web generator is used Hugo build upon Golang. Chosed theme is [Arcana](https://github.com/half-duplex/hugo-arcana)

## To Do

Well website is not complete... yet. Most of content is here in repo.

- Image for page *Guerilla gardening*
- Image for page *Výsadba stromů*
- Text for page *ZRJ 2022* - wasn't included in backup, used text from facebook
- Enable dropdown menus for *Zažít Roudnici Jinak* and *Ostatní námi pořádané akce*
- Redo main page
- Header image...? Not sure for now
- Export static files and upload to Github pages
- DNS change

## How run website?

### Hugo install

If you don't have Hugo installed then install it. Guide is available at [Hugo website](https://gohugo.io/installation/).

### Running server

Firstly you need to clone this repo.

`git clone https://github.com/pstrobl96/zrj-web.git`

And everything you need is to run webserver.

```
cd zrj-web
git checkout hugo
hugo server -D
```

### Generating static files

You know what they say... Slow and steady wins the race

## How to add page?

Hugo use Markdown for formatting of pages. Guide of basic syntax can be found at [Markdown Guide](https://www.markdownguide.org/basic-syntax/).  

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