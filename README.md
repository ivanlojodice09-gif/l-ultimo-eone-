

```markdown
# LAST EON

### Open Source Immersive Digital Experience
**Wildland Revolution**  
by **Ivan Nicola Lojodice**

> **Free Knowledge · One Race · One Face**  
> *Qui giace il Tempo. Qui comincia Noi.*

LAST EON è un progetto aperto, generativo e immersivo pensato per trasformare flussi informativi in esperienze visive, sonore e performative. Il sistema unisce cultura digitale, percezione ambientale e ricerca artistica per costruire un ecosistema in cui segnali, memoria e trasformazione si intrecciano.

Il progetto nasce come una ricerca critica e poetica sulla relazione tra dato e esistenza: tra il ritmo del mercato, i segnali biologici, i processi ambientali e la percezione umana.

---

## Visione del progetto

LAST EON non vuole riprodurre staticamente il mondo: vuole renderlo vivo, dinamico e sensibile. L’idea centrale è che i dati non siano semplicemente informazioni, ma forme di relazione.

Il progetto è organizzato attorno a tre grandi assi:

- **Segnale**: ciò che arriva, si misura e viene analizzato.
- **Relazione**: il modo in cui i sistemi si collegano tra loro.
- **Trasformazione**: la capacità di convertire i flussi in immagini, suono, movimento e reazione.

In questa prospettiva, la pianta, l’ambiente, il dispositivo, l’osservatore e la macchina non sono entità separate, ma parti di un sistema più ampio.

---

## Filosofia

LAST EON esplora la collisione tra:

- il tempo cosmico e la soglia dell’istante umano;
- la fragilità dei corpi e la permanenza delle strutture;
- il funzionamento dei sistemi e la loro relazione con il vivente;
- il dato quantitativo e la sua interpretazione simbolica.

Il progetto considera la crisi, l’evoluzione e la fine come possibilità di trasformazione. La ricerca non è tecnicamente e poeticamente neutra: cerca di collegare logica, arte ed esperienza.

---

## Architettura concettuale

Il modello del progetto si basa su una pipeline modulare:

```text
Sensori / WebSocket / OSC / Seriale
          ↓
    Data Layer & Network Core
          ↓
    Normalizzazione e filtraggio
          ↓
         DataCore / Memoria
          ↓
      Symbiosis Engine
      ↙               ↘
Visual Engine      Audio Engine
      ↓               ↓
  TouchDesigner    Synthesis / OSC
      ↓
   Output visivo e sonoro
      ↓
  Hardware / attuatori / installazione
```

### Componenti principali

- Data acquisition: sensori, feed esterni, JSON, WebSocket, OSC, seriale.
- DataCore: memorizzazione di snapshot, buffer, analisi della complessità.
- Symbiosis Engine: unione di variabili biologiche, ambientali e interattive.
- Visual Engine: rendering generativo, particelle, feedback, shader, motion.
- Audio Engine: elaborazione sonora, mappature dinamiche, spazializzazione.
- Physical Engine: controllo hardware e sistema fisico tramite attuatori e dispositivi.

---

## Struttura della repository

```text
LAST_EON/
├── README.md
├── LICENSE
├── index.html
├── project.json
├── assets/
│   └── ...
├── docs/
│   └── ...
├── src/
│   └── ...
└── config/
    └── ...
```

Il file `index.html` è la pagina web del progetto e carica i contenuti dal file `project.json`. Questa separazione consente di aggiornare testi, valori e impostazioni senza dover modificare la struttura HTML.

---

## Proposta di esperienza web

La pagina web di LAST EON fornisce una presentazione del progetto con:

- introduzione narrativa;
- blocchi di contenuto esplorativi;
- statistiche del progetto;
- principi ontologici;
- applicazioni possibili;
- grafico interattivo generato nel browser;
- sezione “nota dell’autore” e chiusura artistica.

Il grafico è dimostrativo e non rappresenta dati reali di mercato o misurazioni biologiche.

---

## Local usage

Poiché la pagina usa `fetch()` per leggere `project.json`, è consigliabile avviarla tramite un server locale invece di aprire direttamente il file HTML.

Con Python:

```bash
python -m http.server 8000
```

Quindi apri nel browser:

```text
http://localhost:8000
```

---

## Personalizzazione

I contenuti principali della pagina sono separati da `project.json`, che può essere aggiornato per modificare:

- titoli e sottotitoli;
- descrizione del progetto;
- statistiche;
- sezioni ontologiche;
- applicazioni;
- controlli e valori del grafico;
- nota dell’autore;
- footer finale.

---

## Tecnologie

- HTML
- CSS
- JavaScript
- JSON
- Canvas API
- WebSocket / OSC
- TouchDesigner (direzione progettuale)
- Python (sistema di orchestrazione)
- Arduino / hardware embedded (direzione progettuale)

---

## Nota etica e interpretativa

La sonificazione di segnali rilevati da sensori non dimostra da sola una comunicazione intenzionale della pianta o una forma di coscienza vegetale. È una pratica espressiva e interpretativa, utile a rendere visibile il segnale nel contesto di un progetto artistico e di ricerca.

La pagina e i contenuti di questo repository descrivono un framework artistico e sperimentale, non una prova scientifica di relazione biologica o di trasmissione del pensiero tra specie.

---

## Uso e commercializzazione

LAST EON è pensato come progetto di ricerca, espressione artistica e sistema aperto, con una logica di condivisione della conoscenza e della sua evoluzione.

L’uso commerciale del progetto, qualora previsto, deve essere regolato da autorizzazione esplicita e da condizioni concordate in modo trasparente. In particolare, l’eventuale utilizzo in ambito economico non può essere considerato automatico o libero senza un accordo scritto.

I profitti generati direttamente dall’uso del progetto, in forma diretta o indiretta, possono essere destinati alla sua evoluzione e alla cassa comune del progetto, secondo regole trasparenti e condivisi.

> Nota: questa sezione è da trattare come documento del progetto e non sostituisce una consulenza legale per la definizione di condizioni contrattuali, royalty o autorizzazioni commerciali.

---

## Community e sviluppo

Il progetto è pensato per favorire un modello di sviluppo aperto, trasparente e collettivo. Chi contribuisce con codice, documentazione, testi, design, installazioni o sperimentazioni può essere coinvolto nel percorso di evoluzione del progetto.

Il contributo alla crescita del progetto può essere reso visibile attraverso:

- aggiornamenti di documentazione;
- nuovi moduli e componenti;
- miglioramento dei file di configurazione;
- contenuti generativi e interpretazioni artistiche;
- supporto tecnico e guida all’utilizzo.

---

## Licenza

Questo progetto è distribuito con una licenza dedicata e i termini esatti sono riportati nel file [`LICENSE`](./LICENSE).

Il file `LICENSE` definisce le condizioni di utilizzo del software e i limiti applicabili. In ogni caso, testi, immagini, marchi e contenuti creativi non sono automaticamente inclusi nella licenza del codice, salvo diversa indicazione.

---

## Crediti

- Autore: **Ivan Nicola Lojodice**
- Progetto: **LAST EON**
- Manifesto: **Wildland Revolution**
- Natura del progetto: **Open immersive digital experience**

---

**LAST EON**  
*Open Source Immersive Digital Experience*  
**Wildland Revolution**  
by **Ivan Nicola Lojodice**
```