
### Zadefinovanie filmu

- stiahni film - mp4
- stiahni titulky - vtt
- stiahni obrázok/poster pre film

#### Film s dabingom

- doplň linku na film priamo do `index.html`

`<div class="c"><a href="film.mp4"> <img src="poster.jpg"></a></div>
`

#### Film s titulkami

- skopíruj `film-s-titulkami.html` a zaedituj v ňom cestu k `mp4` a `vtt`
- na takto vyrobený súbor vytvor linku v `index.html`

`<div class="c"><a href="film-s-titulkami.html"> <img src="poster.jpg"></a></div>`

- pri spustení filmu použi `node` `http-server` aby bolo možné posúvať prehrávanie filmu - návod nižšie

#### Seriál

- skpíruj a zaedituj `serial.html`

### Inštalácia a spustenie nodejs http servra

#### Inštalácia nodejs - MAC

- otvor terminál a nainštaluj brew package manager 

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)`

- nainštaluj nodejs

`brew install node`

#### Inštalácia nodejs - Windows

- download nodejs zip a unpack do cieľového adresára
- nastav `PATH` aby bolo možné spustiť nodejs z `CMD`

#### Install http-server

`npm install http-server -g`

#### Run http-server

`cd to-your-movies-dir`

`http-server -p 8000`

#### Open movies page

- v brovseri otvor  http://127.0.0.1:8080/


