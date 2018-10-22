# Indicații documentare proiect

Scopul documentației este să vă ajute să vă aliniați ca echipa asupa ce veți livra la finalul proiectului.  

## Introducere (250 - 350 cuvinte)

* Care este principala nevoie/problemă pe care o rezolvă produsul vostru?
* Cărui tip de utilizatori se adresează produsul vostru?
* Ce alte produse similare există în piață?

## Interfețe aplicație

* se vor realiza mock-up-uri pentru interfețele aplicației (desenate sau folosind un tool online) 

## API REST

* descrie metodele expuse de backend, parametrii de request și exemple de response

Exemplu request

```
GET /messages?search={searchParam}&orderBy={orderByParam}
```

Exemplu response

```json
[ 
  {
    "subject": "Some text",
    "from": "some@email.com",
    "message": "Some more text"
  }
]
```



## Format documentatie

* Documentația va fi inclusă în repository în fișierul README.md folosind markdown
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

