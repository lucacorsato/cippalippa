---
layout: page
title: Istruzioni
---
<a id="inizio"></a>


* [Installare le archeostickers](#1)
* [Cos'è Telegram](#2)
* [Con cosa è fatto archeostickers.com](#3)
* [Caricare nuove sticker e creazione di un pacchetto su Telegram](#4)
* [Scaricare una archeosticker in vettoriale](#5)
* [Cosa posso fare da Github?] (#6)
* [Risorse per imparare Github - e diventare cintura nera di social coding] (#7)
* [Come si usa Jekyll](#8)
* [Altri dubbi o richieste?] (#9)



<a id="1"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Installare le archeostickers 

Clicchi 

<big>[https://telegram.me/addstickers/archeo](https://telegram.me/addstickers/archeo)</big>

e ti si aprirà una finestra che ti chiede se vuoi aprire nell'applicazione (di Telegram qualora fosse già installata) oppure di installare Telegram. *Non temere: non si tratta di nessun virus o tentativo di hackeraggio*



<a id="2"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Cos'è Telegram
Se non sai che cos'è Telegram te lo spiegano [qui](https://telegram.org/faq#q-what-is-telegram-what-do-i-do-here) ma, per capirci, è un Whatsapp con gli *addittivi*.

Questi *addittivi* sono:

1. [creare facilmente](https://telegram.org/blog/stickers) delle sticker personalizzate
2. [creare dei canali](https://telegram.org/blog/channels) (*questi dobbiamo ancora capire bene come usarlo)
3. [creare dei Bot](https://core.telegram.org/bots/faq)

significa che si possono fare un sacco di cose, ma a noi interessa principalmente:

 

<a id="3"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Con cosa è fatto archeostickers.com
Archeostickers.com è un riuso a sua volta. È fatto con strumenti opensource e hosting gratuito:

1. [Github](https://github.com) <small>[codice](https://github.com/archeostickers) e hosting</small>
2. [Jekyll](https://jekyllrb.com/) <small>pubblicazione di [archeostickers.com](http://archeostickers.com)</small>
3. [Desktop Github](https://desktop.github.com/) <small>gestire dal proprio computer le cartelle del repository github, potersi fare il proprio clone in locale del sito stesso, caricare e scarica immagini e file</small>
4. [Sublime Text](http://www.sublimetext.com/2) <small>editare codice (la versione 2 è gratuita e non ha scadenza, anche se chiederà periodicamente di aggiornare alla versione 3  - a pagamento</small>
5. [Gimp](http://www.gimp.org/) <small>editing delle immagini</small>
6. [Inkscape](https://inkscape.org/it/) <small>vettorializzazione delle immagini</small>




<a id="4"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Caricare nuove sticker e creazione di un pacchetto su Telegram
Se vuoi un pacchetto sticker su Telegram si fa tutto nella chat di [Telegram](https://telegram.org/): 

* si “chatta” con il bot @Stickers e si seguono le indicazioni
* */newpack* e si crea il pacchetto individuando il nome
* */addsticker* si aggiunge una nuova sticker
	* prima chiede di caricare l’emoticon di riferimento
	* si carica l’immagine della sticker (ATTENZIONE: non deve superare i 350k e 512x512px di dimensioni)
* NOTA BENE: l’immagine deve essere caricata come file e non come foto! i formati sono .jpg e .png (consiglio il .png se dovete tenere degli sfondi trasparenti)
* */publish* per pubblicare il pacchetto
* quando vengono aggiunte sticker ai pacchetti conviene disinstallare e reinstallare il pacchetto (controllando che si sia aggiornato con le nuove, occorre generalmente un paio di minuti)




<a id="5"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Scaricare una archeosticker in vettoriale
Le archeosticker sono distribuite in due formati:

* formato .png (dimensioni 512x512px) che sono quelle usate per creare le sticker su Telegram
* formato .svg (dimensioni 100x100px) che è [vettoriale](https://it.wikipedia.org/wiki/Grafica_vettoriale) che può essere più pesante del formato png ma che può essere stampato o riprodotto anche a dimensioni enormi senza perdere definizione

I formati vettoriali stanno nella cartella su github [stickers_vettoriali](https://github.com/archeostickers/archeostickers.github.io/tree/master/public/images/stickers_vettoriali) e per scaricarle tutte basta usare Desktop Github. Se invece ci arrivi dal post relativo, ecco cosa si deve fare:

1. ![link per scaricare l'archeosticker vettoriale](/public/images/tutorial/link_download_vettoriale.png)
2. ![finestra Github](/public/images/tutorial/finestra_github.png)
3. tasto destro "salva immagine con nome..." e si scarica un file "download.svg"
4. nella cartella di salvataggio ci sarà il file... non resta che rinominarlo e aprirlo con Inkscape



<a id="6"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Cosa posso fare da Github?
Innanzitutto ti puoi scaricare l'intero sito archeostickers.com compreso di tutte le immagini sia .png che vettoriali

![download_archeostickers.com](/public/images/tutorial/download_archeostickers.com.png)

* Se usate Desktop Github allora clicca "*Clone in Desktop*"
* Se vuoi direttamente tutto il pacchetto allora "*Download ZIP"

Inoltre se possiedi un account Github puoi clonarti il sito su un tuo repository e farci quello che ti pare. 

Un buon articolo sul rapporto tra archeologia e codice attraverso Github è [Archaeology and GitHub](http://www.poweredbyosteons.org/2013/08/archaeology-and-github.html) del 2013. Già da una ricerca su Github [si trova parecchio materiale](https://github.com/search?utf8=%E2%9C%93&q=archeology).

Per avere un'idea di come si sta espandendo l'uso di Github in ambito culturale, ecco una lista (la aggiorneremo man mano che le troveremo) di Enti Culturali:

* [Smithsonian Institution](https://github.com/Smithsonian)
* [Natural History Museum of London](https://github.com/NaturalHistoryMuseum)
* [MoMA](https://github.com/MuseumofModernArt)
* [Tate Gallery](https://github.com/tategallery)



<a id="7"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Risorse per imparare Github - e diventare cintura nera di social coding
Un po' di riferimenti:

* Un veloce **tutorial su github** è [questo](https://guides.github.com/activities/hello-world/).
* per esercitarsi (o rinfrescare la memoria) con esercizi online su [Git](https://git-scm.com/) (ovvero il papà di Github) lo trovate su **[try.github.io](https://try.github.io)
* i geniacci di [codeschool](https://www.codeschool.com) sono una risorsa per apprendere vari linguaggi
* altri grandissimi per far apprendere codice sono quelli di **[Codeacademy](https://www.codecademy.com/)**

Per qualsiasi dubbio o spunto, consigliamo l'eccellente canale YouTube di [GithubGuides](https://www.youtube.com/user/GitHubGuides). Ottimi anche i due video di [LearnCode Academy](https://www.youtube.com/user/learncodeacademy)

<iframe width="560" height="315" src="https://www.youtube.com/embed/0fKg7e37bQE" frameborder="0" allowfullscreen></iframe>


<a id="8"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Come si usa Jekyll?
Imprescindibile questo video per imparare a:

* creare un proprio sito con Jekyll
* modificarne uno scaricato o [*forkato*](https://it.wikipedia.org/wiki/Fork_(sviluppo_software))
* personalizzare un sito come archeostickers.com

<iframe width="560" height="315" src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>

Inoltre Jekyll viene scritto in [markdown](https://it.wikipedia.org/wiki/Markdown) che è molto simile alla sintassi di Wikipedia. Un buon prontuario per la sintassi lo trovate [nella guida di Daring Ball](https://daringfireball.net/projects/markdown/syntax).



<a id="9"></a>
##[<i class="fa fa-angle-up"></i>](#inizio) Altri dubbi o richieste?

* Se volete un aiuto su come riusare archeostickers.com mandateci una mail a <code>contact@opensensorsdata.it OGGETTO: riuso archeostickers.com</code>
* Se volete un sito come archeostickers.com con le gallerie del vostro Museo o Ente e avete bisogno di un aiuto, mandateci sempre una mail come sopra
* Se avete necessità di altra documentazione commentate pure qui sotto 