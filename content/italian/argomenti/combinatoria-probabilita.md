---
title: "Combinatoria e Probabilità"
meta_title: ""
description: ""
draft: false
---

Combinatoria e calcolo delle probabilità sono spesso considerate tra le parti più affascinanti della matematica olimpica.  
Uno dei motivi è che **non richiedono grandi conoscenze pregresse**: molti problemi si possono iniziare ad affrontare semplicemente ragionando.

Naturalmente, quando i problemi diventano più complessi, è utile conoscere alcune tecniche e strumenti tipici.  
Con il tempo si impara a riconoscere strutture ricorrenti e strategie di conteggio sempre più efficaci.

Di seguito trovi alcuni degli argomenti più importanti da conoscere.

---

### Argomenti fondamentali

{{< tabs >}}

{{< tab "Conteggio" >}}

#### Fattoriali

Il fattoriale di un numero naturale $n$, indicato con $n!$, rappresenta il prodotto di tutti i numeri interi positivi da 1 a $n$.  
Compare frequentemente nei problemi di conteggio e nelle formule di permutazione e combinazione.

#### Come conteggiare

Molti problemi combinatori si riducono a **contare in modo corretto gli oggetti possibili**.  
Imparare a organizzare il conteggio, evitare doppioni e suddividere i casi è una delle abilità più importanti nella combinatoria.

#### Coefficienti binomiali

I coefficienti binomiali

$$
\binom{n}{k} = \frac{n!}{k!(n-k)!}
$$

indicano il numero di modi in cui è possibile scegliere $k$ elementi da un insieme di $n$ elementi.  
Compaiono in moltissimi problemi di conteggio e sono collegati allo sviluppo del **binomio di Newton**.

{{< /tab >}}

{{< tab "Permutazioni e combinazioni" >}}

#### Permutazioni

Le permutazioni contano i modi possibili di **ordinare tutti gli elementi di un insieme**.  
Ad esempio, il numero di modi di ordinare $n$ oggetti distinti è $n!$.

#### Permutazioni circolari

Quando l’ordine è disposto **su un cerchio**, alcune permutazioni diventano equivalenti perché possono essere ottenute ruotando la configurazione.

#### Anagrammi

Gli anagrammi sono permutazioni delle lettere di una parola.  
Diventano particolarmente interessanti quando alcune lettere sono ripetute, perché bisogna evitare di contare configurazioni uguali.

#### Disposizioni

Le disposizioni contano i modi di **scegliere e ordinare** alcuni elementi di un insieme.  
Possono essere:

- **semplici**, se gli elementi non si ripetono  
- **con ripetizione**, se è possibile usare più volte lo stesso elemento

#### Combinazioni

Le combinazioni contano i modi di scegliere elementi **senza considerare l’ordine** (a differenza delle disposizioni).  

Possono essere:

- **semplici**  
- **con ripetizione**

Sono tra gli strumenti più utilizzati nella combinatoria.

{{< /tab >}}

{{< tab "Probabilità" >}}

#### Spazio degli eventi

Quando si studia un fenomeno casuale, si definisce lo **spazio degli eventi possibili**.  
La probabilità di un evento viene spesso calcolata come

$$
\frac{\text{casi favorevoli}}{\text{casi possibili}}
$$

quando tutti i risultati sono equiprobabili.

#### Tipi di eventi

Negli esercizi è importante riconoscere il tipo di relazione tra eventi:

- **eventi disgiunti**
- **eventi indipendenti**
- **eventi dipendenti**

Questo permette di applicare correttamente le regole del calcolo delle probabilità.

#### Probabilità condizionata

La probabilità condizionata misura la probabilità che un evento avvenga **sapendo che un altro evento è già avvenuto**.

#### Teorema di Bayes

Il teorema di Bayes permette di aggiornare una probabilità alla luce di nuove informazioni ed è uno strumento fondamentale in molte applicazioni moderne.

{{< /tab >}}

{{< /tabs >}}

---

### Da dove iniziare a prepararsi

I prerequisiti del calcolo combinatorio (fattoriali, permutazioni, combinazioni, disposizioni, anagrammi…) e del calcolo delle probabilità basato sul conteggio dei casi favorevoli si trovano normalmente nei manuali di matematica dei licei scientifici del quarto anno.

Tuttavia non è necessario partire da un libro scolastico. Qui sotto trovi alcune risorse particolarmente utili.

#### Corso online consigliato

Un ottimo punto di partenza è il corso online del **prof. Emanuele Callegari** (Università di Roma Tor Vergata).  
Ti consigliamo in particolare di iniziare dalle **lezioni 1, 2 e 3**.

🎬 https://www.problemisvolti.it/CorsoBaseOlimpiadiMatematica.html

Ulteriori informazioni le puoi trovare alla pagina dedicata [qui](/materiali/corso-callegari).

#### Dispensa di approfondimento ed esercizi

Segnaliamo anche la dispensa di Combinatoria molto completa del **prof. Luciano Mezzini**, docente emerito di matematica presso il Liceo Scientifico "Leonardo da Vinci" di Treviso e coach delle squadre del liceo che hanno vinto il titolo italiano nelle gare a squadre nel 2009 e nel 2011.

{{< button label="📑 Calcolo Combinatorio (Mezzini)" link="/pdf/Calcolo_combinatorio_2015_Luciano_Mezzini.pdf" style="solid" >}}

#### Libri consigliati

Per approfondire ulteriormente, sono molto utili alcuni volumi della collana **U Math**:

- **Calcolo combinatorio** ▸ Maurizio Trombetta  
  ISBN: 978-88-96973-68-4  
  https://scienzaexpress.it/catalogo/calcolo-combinatorio/

- **Probabilità** ▸ Luigi Amedeo Bianchi  
  ISBN: 979-12-800-6809-5  
  https://scienzaexpress.it/catalogo/probabilita/

- **Combinatoria per problemi** ▸ Emanuele Callegari  
  ISBN: 979-12-800-6811-8  
  https://scienzaexpress.it/catalogo/combinatoria-per-problemi/

Nella sezione [**Risorse**](/risorse/collana-u-math) del sito puoi trovare ulteriori informazioni sulla collana **U Math** e su altri materiali utili per l’allenamento.