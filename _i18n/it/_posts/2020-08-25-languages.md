---
layout: post
title: Linguaggi
subtitle: Perché il computer non risponde quando gli parli
cover-img: /assets/img/assembly_language.png
thumbnail-img: /assets/img/assembly_language.png
share-img: /assets/img/assembly_language.png
gh-repo: gioele-santi/gioele_dev
gh-badge: []
tags: [programmazione, linguaggi]
comments: true
---

Quando abbiamo parlato di attaccare la coda all'asino, abbiamo detto che programmare consiste nel **dare istruzioni**, il problema è che il computer non parla la nostra lingua.

Allora che lingua parla il computer? Diverse direi.  
Il cuore del computer, la CPU (Central Processing Unit) usa il **linguaggio macchina** che è un piccolo insieme di **semplici istruzioni**, scritte come numeri (numeri binari es: 0010001).

**Assembly** è un altro linguaggio, in pratica fa corrispondere ad ogni **istruzione in linguaggio macchina** una breve parola, rendendola più *comprensibile* per un umano (es: MOV, SUM).

### Linguaggi di basso livello, linguaggi di alto livello

Assembly è più comprensibile ma comunque molto difficile da usare, persino per un programmatore esperto, perché per svolgere un'azione molto elaborata, è necessario combinare un gran numero di queste istruzioni, a volte raggiungendo un livello molto alto di complessità.

La ragione è perché questo linguaggio è molto **vicino alla logica interna del processore**. Per questo è chiamato **linguaggio di basso livello**, ma non fatevi ingannare dal nome: non ha un significato negativo o riduttivo, al contrario, i linguaggi di basso livello sono molto importanti e difficili da padroneggiare. 

La soluzione che hanno escogitato gli informatici è stata quella di **inventare un altro linguaggio** (di fatto più di uno) che potesse essere **più facile** da usare.  
Questi nuovi linguaggi sono noti come **linguaggi di alto livello** e sono più vicini al linguaggio umano.

### Parole potenti

Questi linguaggi hanno **più istruzioni** che sono anche più complesse o come si suol dire **più potenti**. Questo significa che una **singola istruzione** in un linguaggio di alto livello corrisponde a **molte istruzioni** in uno di livello più basso.

Consideriamo una parola potente: **moltiplicare**.
Perché è potente? Perché è *un'istruzione di alto livello*? 

{: .box-note}
5 x 8 = 5 + 5 + 5 + 5 + 5 + 5 + 5 + 5

Moltiplicare significa ripetere la stessa somma un certo numero di volte. In effetti è quello che farebbe un processore: ripetere un ciclo con una serie di somme per un dato numero di volte (*ripetere* e *sommare* sono due fondamentali istruzioni di basso livello).

### Traduzione

L'uso di linguaggi di alto livello è permesso da speciali programmi chiamati **traduttori** (interpreti e compilatori) che prendono istruzioni di alto livello e le convertono in istruzioni di basso livello.

Applicare più livelli di traduzione permette l'adozione di più strati di linguaggi di programmazione, che così si avvicinano sempre più al linguaggio umano, rendendo la programmazione più facile e potente. Ma questo è per un altro post.