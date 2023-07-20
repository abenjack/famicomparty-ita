+++
title = "Introduzione"
weight = 1
+++

Nell'autunno del 1990, i miei genitori mi regalarono un Nintendo Entertainment
System Action Set: un Control Deck squadrato e grigio, due controller, una light gun arancio accesso denominata "Zapper"
e una cartuccia che conteneva sia _Super Mario
Bros._ che _Duck Hunt_. {% sidenote(id="nes-console-set",
img=["NES-Console-Set.jpg", ""]) %}
Una console NES con il controller.\
Foto di [Evan Amos](https://commons.wikimedia.org/wiki/User:Evan-Amos).
{% end %}
La console era collegata al grande televisore a tubo catodico
che avevamo al seminterrato tramite uno switch RF, fondamentalmente un'antenna 
che portava il segnale video dalla console alla TV quando veniva sintonizzata sul Canale 3.
Era la prima console di gioco che avevamo mai avuto, e io la adoravo.

Ho trascorso molto tempo nel seminterrato quell'anno. All'inizio lo fece anche mio padre -
si stava facendo strada con _Super Mario Bros._, imparando dove si trovavano i passaggi segreti
e come superare i minacciosi Hammer Bros.
Alla fine sconfisse Bowser (o “il drago”, come lo chiamava lui), salvò la
principessa, e non ha più giocato a un gioco per NES.

Io in compenso ero preso. Abbiamo ricevuto una lettera promozionale tramite posta
dove ci informavano che avrebbero offerto una copia gratuita di _Dragon Warrior_
abbonandoci alla rivista Nintendo Power; sottoscrivere
un abbonamento ad una rivista per $20 dollari per ottenere un gioco che ne valeva $50
era una follia. {% sidenote(id="dragon-warrior-box",
img=["Dragon_Warrior-box.jpg", "Dragon Warrior box"]) %}
Dragon Warrior (box art statunitense).
{% end %}
_Dragon Warrior_ mi ha iniziato ai giochi di ruolo cosi come
 _Super Mario Bros._ ha fatto con i platformer. 
C'erano molti altri giochi con i quali ho trascorso molto tempo: _Ducktales_, _Final Fantasy_,
_Contra_, e _Mega Man III_ erano alcuni dei miei preferiti.

Alla fine il NES mi ha indirizzato verso una professione. Da bambino sapevo 
che i videogiochi erano qualcosa di speciale e che fare videogiochi era ciò che avrei
voluto fare da grande. Avevo la (errata) convinzione che che una carriera come sviluppatore di videogiochi
equivalesse alla carriera di **giocare** ai videogiochi. Dopo che la mia famiglia ebbe un computer ho iniziato
ad imparare il linguaggio C++, poiché era ciò che utilizzavano i programmatori "reali". (Non sapevo che i programmatori NES 
non usassero il C++, ma in mia difesa ero giovane e ingenuo).
Ad ogni modo, non ho mai realizzato alcun gioco. Lo sviluppo di videogiochi mi è sempre sembrato
più complicato di quanto mi aspettassi, e in aggiunta, non mancavano altri giochi di altre persone in attesa di essere giocati.

That dream stuck with me, and after years of being a professional web
developer I started learning NES development. (I got a strong nudge in the
right direction from Nathan Altice’s excellent _I Am Error_.){% sidenote(id="i-am-error",
img=["i-am-error.jpg", "I Am Error, front cover"]) %}
[_I Am Error_](https://mitpress.mit.edu/books/i-am-error).
{% end %}
It was hard to know where to begin. There were plenty of resources around the
internet, but they were all incomplete or inaccurate in some way. I got started
with bunnyboy's ["Nerdy Nights"](https://nerdy-nights.nes.science) series on the NintendoAge forums. Then I found
tepples' [NROM template](https://github.com/pinobatch/nrom-template)
on GitHub, and started learning the ca65 assembler.
After months of struggling to understand PPU writes, attribute tables, and
scroll registers, it all started to click. I'm glad that I had the experience
of fighting with these concepts to learn on my own, but I wish that I could
have had a guide that started from scratch and taught all of the essentials of
NES development.

My hope is that the book you are now reading will serve as that guide.
