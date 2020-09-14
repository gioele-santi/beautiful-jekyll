---
layout: post
title: Tanti auguri
subtitle: Conosci già la programmazione, ma non te ne rendi conto!
cover-img: /assets/img/happy-birthday.png
thumbnail-img: /assets/img/happy-birthday.png
share-img: /assets/img/happy-birthday.png
gh-repo: gioele-santi/gioele_dev
gh-badge: []
tags: [programmazione, musica]
comments: true
---

Programmare significa dare istruzioni ad un computer per risolvere un problema o completare un compito.  
Potremmo scrivere definizioni più complesse ed approfondire diversi dettagli, ma ora voglio concentrarmi su quello che già conoscete.

La chiave è predere un'**azione complessa** e suddividerla in una serie di **azioni semplici**.

Le azioni semplici sono combinate e ripetute finché non si ottiene il risultato desiderato.

### Consideriamo una canzone 

Il testo di una canzone è una serie di *istruzioni* che indicano al cantante le parole che deve cantare.  
Possiamo considerarlo come un **unico blocco di testo** ma sappiamo che una canzone può essere divisa in pezzi più piccoli: **ritornello** e **strofe**. 

Ritoernello e strofe sono combinati, ordinati e ripetuti per creare una canzone completa e dunque una performance (esecuzione).

Sappiamo che il ritornello può essere ripetuto più volte, quindi non ci serve riscriverlo ogni volta. Ci basta indicarlo.

### Scommetto che questa la conoscete

Ogni bambino dovrebbe conoscere questo classico.

{% highlight javascript linenos %}
Tanti auguri a te  
Tanti auguri a te   
Tanti auguri caro/a [nome]  
Tanti auguri a te 
{% endhighlight %}

Come potete vedere, le righe 1, 2 e 4 sono solo ripetizioni del ritornello. Allora possiamo riscrivere così:

{% highlight javascript linenos %}
ritornello:
    Tanti auguri a te (x 2) 
strofa:
    Tanti auguri caro/a [nome]  
ritornello (x 1)
{% endhighlight %}

Abbiamo etichettato il testo  usando **ritornello** e **strofa** ed abbiamo anche scritto le ripetizioni.

Uno dei punti chiave della programmazione è ripeter un'istruzione più volte.  
Vedi lo sai già fare!

### Variabile

*Tanti auguri* + una canzone peculiare. Il testo va sempre bene, chiunque sia la persona.
Questo perché sostituiamo `[nome]` con il nome della persona festeggiata.

`[nome]` è quella che chiamiamo **variabile**. Ci permette di generalizzare il testo o un pezzo di codice e riutilizzarlo in situazioni differenti.

Questo è solo un primo passo, ma rendersi conto che i principi della programmazione sono già attorno a noi, sarà di grande aiuto per capire il mondo della programmazione.

[Immagine da WikiMedia Commons](https://commons.wikimedia.org/wiki/File:The_Everyday_Song_Book_-_1922_-_Good_Morning.png)