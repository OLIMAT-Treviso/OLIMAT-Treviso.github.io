---
title: "Teoria dei Numeri"
meta_title: ""
description: ""
draft: false
---

Teoria dei numeri è una delle aree più classiche della matematica olimpica.  
Si occupa principalmente di **proprietà degli interi**, dei numeri primi e delle relazioni aritmetiche tra numeri.

A differenza della combinatoria, molti problemi di teoria dei numeri richiedono **alcune tecniche specifiche**.  
Una volta appresi gli strumenti fondamentali, però, diventa possibile affrontare problemi molto diversi tra loro utilizzando idee comuni come divisibilità, congruenze e fattorizzazioni.

Molti risultati di teoria dei numeri sono anche alla base di applicazioni moderne, ad esempio nei **sistemi crittografici** utilizzati nella sicurezza informatica.

Di seguito trovi alcuni degli argomenti più importanti da conoscere.

---

### Argomenti fondamentali

{{< tabs >}}

{{< tab "Divisibilità" >}}

#### Numeri primi e fattorizzazione

Un **numero primo** è un numero intero maggiore di 1 che ha come divisori solo 1 e sé stesso.  

Ogni numero naturale può essere scritto in modo unico (a meno dell’ordine dei fattori) come prodotto di numeri primi: questa proprietà è nota come **teorema fondamentale dell’aritmetica**.

La fattorizzazione in primi è uno degli strumenti più utilizzati nei problemi di teoria dei numeri.

#### Massimo comune divisore e minimo comune multiplo

Il **massimo comune divisore** (MCD) di due numeri è il più grande intero che li divide entrambi.  
Il **minimo comune multiplo** (mcm) è invece il più piccolo numero positivo che è multiplo di entrambi.

Spesso si calcolano utilizzando l’**algoritmo di Euclide**, una procedura molto efficiente basata sulla divisione con resto.

#### Identità di Bézout

Per due interi $a$ e $b$ esistono sempre interi $x$ e $y$ tali che

$$
ax + by = \gcd(a,b)
$$

Questa relazione è nota come **identità di Bézout** ed è fondamentale nello studio delle equazioni diofantee e delle congruenze.

{{< /tab >}}

{{< tab "Congruenze" >}}

#### Aritmetica modulare

Due interi $a$ e $b$ sono **congruenti modulo $n$** se hanno lo stesso resto nella divisione per $n$.

Si scrive

$$
a \equiv b \pmod{n}
$$

L’aritmetica modulare permette di lavorare con i resti delle divisioni e semplifica molti problemi aritmetici.

#### Classi di congruenza

Gli interi si suddividono in **classi di congruenza** modulo $n$, ciascuna rappresentata da uno dei resti possibili.

Questo punto di vista è molto utile per studiare proprietà dei numeri e per risolvere equazioni modulari.

#### Congruenze lineari

Una congruenza lineare ha la forma

$$
ax \equiv b \pmod{n}
$$

La sua risoluzione dipende dal rapporto tra $a$, $b$ e $n$, in particolare dal **massimo comune divisore** tra $a$ e $n$.

{{< /tab >}}

{{< tab "Teoremi e applicazioni" >}}

#### Piccolo teorema di Fermat

Se $p$ è un numero primo e $a$ non è multiplo di $p$, allora

$$
a^{p-1} \equiv 1 \pmod{p}
$$

Questo risultato è uno degli strumenti più utilizzati nei problemi olimpici che coinvolgono potenze modulo un numero primo.

#### Funzione di Eulero

La **funzione di Eulero** $\varphi(n)$ conta quanti numeri tra $1$ e $n$ sono coprimi con $n$.

Ha una proprietà molto importante: è **moltiplicativa**, cioè se $a$ e $b$ sono coprimi allora

$$
\varphi(ab) = \varphi(a)\varphi(b)
$$

Da questa funzione deriva il **teorema di Eulero**, una generalizzazione del piccolo teorema di Fermat.

#### Sistemi di congruenze

In alcuni problemi bisogna risolvere più congruenze contemporaneamente.  
Il risultato fondamentale in questo contesto è il **teorema cinese del resto**, che permette di trovare soluzioni quando i moduli sono coprimi.

#### Equazioni diofantee

Le **equazioni diofantee** sono equazioni che richiedono soluzioni intere.

Il caso più semplice è quello lineare:

$$
ax + by = c
$$

che può essere risolto utilizzando l’algoritmo di Euclide o l’identità di Bézout.

{{< /tab >}}

{{< /tabs >}}

---

### Da dove iniziare a prepararsi

La teoria dei numeri **non compare in modo esteso nei programmi scolastici**.  
Alcuni argomenti di base (come fattorizzazione, MCD e mcm) vengono trattati nei manuali di matematica, ma la maggior parte delle tecniche olimpiche richiede materiali specifici.

Qui sotto trovi alcune risorse particolarmente utili che consigliamo di seguire in ordine.

---

#### 1. Corso online del prof. Callegari

Un ottimo punto di partenza è il corso online del **prof. Emanuele Callegari** (Università di Roma Tor Vergata).  
Per la teoria dei numeri ti consigliamo in particolare di iniziare dalle **lezioni 4, 5, 6 e 7**.

🎬 https://www.problemisvolti.it/CorsoBaseOlimpiadiMatematica.html

Ulteriori informazioni le puoi trovare alla pagina dedicata [qui](/materiali/sito-callegari).

---

#### 2. Dispense della prof.ssa Archetti

Dopo aver visto le lezioni introduttive del corso di Callegari, puoi approfondire con alcune dispense utilizzate negli **Stage Olimpici Territoriali di Treviso**, preparate dalla **prof.ssa Maria Archetti**.

Le dispense coprono diversi argomenti importanti della teoria dei numeri olimpica. Puoi trovare tutti i materiali nella pagina dedicata:

📄 [Materiale della prof.ssa Archetti](/materiali/materiale_archetti)

---

#### Libri consigliati

Per approfondire ulteriormente, sono molto utili alcuni volumi della collana **U Math**:

- **Aritmetica modulare** ▸ Salvatore Damantino, Emanuele Campeotto  
  ISBN: 978-88-96973-87-5  
  https://scienzaexpress.it/catalogo/aritmetica-modulare/

- **Teoria dei numeri** ▸ Salvatore Damantino  
  ISBN: 978-88-96973-70-7  
  https://scienzaexpress.it/catalogo/teoria-dei-numeri/

Nella sezione [**Risorse**](/risorse/collana-u-math) del sito puoi trovare ulteriori informazioni sulla collana **U Math** e su altri materiali utili per l’allenamento.

Altri testi consigliati:

- **Algebra e matematica discreta** ▸ Andrea Facchini  
  ISBN: 978-8808097392  
  https://www.zanichelli.it/ricerca/prodotti/algebra-e-matematica-discreta

- **Elementi di algebra** ▸ Franciosi, De Giovanni  
  ISBN: 978-88-7999-024-0  
  https://www.aracne-editrice.it/index.php/pubblicazione.html?item=9788879990240