---
layout: post
title: Attacca la coda all'asino
subtitle: Traformare un gioco da bambini in un'esperienza di programmazione
cover-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
thumbnail-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
share-img: /assets/img/Pin_the_Tail_On_the_Donkey-example.jpg
tags: [programmazione, gioco]
---

Un problema ed un semplice insieme di sitruzioni per risolverlo. Un buon punto di partenza  per un gioco ma anche per la programmazione.  
Uno dei due giocatori è **bendato** e deve attaccare una coda di carta nella posizione giusta. Può fare solo alcune azioni: andare **su**, **giù**, **sinistra** o **destra** ed infine **attaccare** la coda.  
L'altro giocatore può vedere il disegno e deve aiutare dando **istruzioni**.

### Confrontiamo con i computer

Un computer è **stupido** e può svolgere solo un insieme limitato di istruzioni. Potresti pensare che il tuo computer o il tuo smartphone sia molto potente ma in fondo è sempre solo un povero **stupido** processore che muove bit e fa somme.

L'unico modo per far lavorare un computer è fornirgli delle istruzioni. Quindi i programmatori devono usare un insieme di azioni disponibili e combinarle in diversi modi, creando così azioni più complesse.

### Giocare

Quando i bambini giocano, muovono liberamente la coda di fronte al disegno ed inconsapevolmente aggiungono qualche *comando* extra, come **stop** o **vai avanti**.
Questi comandi extra sono di fatto un modo di comunicare al bambino bendato  che un'azione deve essere **ripetuta finché** una certa **condizione** è raggiunta.

Quindi conosciamo il concetto di **ciclo**. Facciamo un esempio, ma per renderlo comprensibile dobbiamo usare una griglia di quadrati. In futuro lo renderà compatibile con i computer.

|   	| A 	| B 	| C 	| D 	| E 	| F 	| G 	| H 	|
|---	|---	|---	|---	|---	|---	|---	|---	|---	|
| 1 	| C 	|   	|   	|   	|   	|   	|   	|   	|
| 2 	|   	|   	|   	|   	|   	|   	|   	|   	|
| 3 	|   	|   	|   	|   	|   	|   D 	|   	|   	|
| 4 	|   	|   	|   	|   	|   	|   	|   	|   	|
| 5 	|   	|   	|   	|   	|   	|   	|   	|   	|

All'inizio la coda (C) è nella posizione **(A,1)** mentre il didietro dell'asino (D) è nella posizione **(F,3)**.  
I comandi per il giocatore bendato saranno: **destra**, **destra**, **destra**, **destra**, **destra**, **giù**, **giù**.

Ma possiamo anche **generalizzare** questi comandi, dobbiamo solo pensare a cosa succede nella mente dell'osservatore:
{% highlight javascript linenos %}
se D è a destra di C:
    finché D è a destra:
        muovi C a destra
altrimenti se D è a sinistra di C:
    finché D è a sinistra:
        muovi C a sinistra
se D è sotto C:
    finché D è sotto:
        muovi C giù
se D è sopra C:
    finché D è sopra:
        muovi C su
{% endhighlight %}

Come potete vedere non è una soluzione ad un singolo problema, ma un **approccio generico** che può essere usato **per ogni posizione di C e D**.

Se ci pensate, potremmo scrivere le stesse istruzioni con molte meno linee, ma l'ottimizzazione merita un intero capitolo a parte.

[Immagine da WikiMedia Commons](https://commons.wikimedia.org/wiki/File:Pin_the_Tail_On_the_Donkey-example.jpg)