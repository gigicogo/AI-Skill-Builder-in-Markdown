# 🧩 Esercitazione B — AI Skill Builder in Markdown

**AI Skill Builder in Markdown** è una web app didattica che aiuta a trasformare una procedura di lavoro in un file `SKILL.md`, utilizzabile come skill in Claude o in altri ambienti AI compatibili.

L’app è pensata per il **Modulo B** del percorso di upskilling sull’IA nella Pubblica Amministrazione. Permette di descrivere un metodo operativo — senza scrivere codice — e di ottenere un file Markdown strutturato, verificabile e riutilizzabile.

## 🎯 A chi è rivolto

L’esercitazione è pensata per dipendenti della Pubblica Amministrazione italiana e per chi vuole imparare a progettare skill AI in modo consapevole.

È particolarmente utile per:

- funzionari ed esecutori che vogliono rendere ripetibili procedure ricorrenti;
- direttori e dirigenti coinvolti nella governance dell’IA;
- referenti ICT, formazione e trasformazione digitale;
- docenti e formatori che vogliono proporre un laboratorio pratico;
- chi vuole passare da un prompt conservato in libreria a una skill riutilizzabile.

## 🧠 L’idea

Nella gestione tradizionale dei prompt, un’istruzione utile viene salvata, cercata, copiata e adattata ogni volta.

Con una skill, invece, si descrive un **metodo riutilizzabile**: scopo, informazioni necessarie, procedura, regole, formato dell’output e punti di arresto. Il file risultante non esegue azioni da solo, ma rende più coerente e trasparente il modo in cui si chiede supporto a un modello AI.

## 🕹️ Come funziona

Il percorso è semplice:

1. **Scegli un caso** tra gli esempi disponibili oppure parti da zero.
2. **Descrivi il metodo** compilando i campi della skill.
3. **Osserva il file `SKILL.md`** aggiornarsi in tempo reale.
4. **Controlla la struttura** tramite le verifiche integrate.
5. **Scarica la skill** in formato `.md` oppure `.zip`.

Non serve un server, un account, una chiave API o una configurazione: basta aprire `index.html` nel browser.

## 🧩 Modelli disponibili

| Modello | Nome skill | Caso d’uso |
|---|---|---|
| Sintesi di segnalazione | `sintesi-segnalazione` | Organizzare fatti dichiarati, richieste e informazioni mancanti di una segnalazione |
| Bozza di risposta | `bozza-risposta-cittadino` | Preparare una comunicazione chiara al cittadino, da verificare prima dell’invio |
| Verifica determina | `verifica-preliminare-determina` | Individuare elementi da controllare in una bozza di determina |
| Da zero | `mia-skill` | Creare una skill per una procedura scelta liberamente |

## 📝 Campi della skill

Ogni skill generata contiene queste sezioni:

| Campo | A cosa serve |
|---|---|
| `name` | Nome tecnico della skill, in minuscole e con trattini |
| `description` | Spiega che cosa fa la skill e quando utilizzarla |
| `# Scopo` | Definisce l’obiettivo concreto del compito |
| `## Informazioni necessarie` | Elenca i documenti o dati da fornire |
| `## Procedura` | Descrive i passaggi da seguire |
| `## Regole e limiti` | Indica cosa non fare e quali cautele osservare |
| `## Output atteso` | Definisce il formato del risultato |
| `## Quando fermarsi e chiedere verifica` | Stabilisce quando interrompersi o coinvolgere una persona competente |

## ✅ Controlli integrati

L’app verifica la **struttura formale** della skill, non la qualità delle risposte AI né la compatibilità con una specifica piattaforma.

I controlli includono:

- nome tecnico valido, con minuscole, numeri e trattini;
- descrizione presente e adeguatamente esplicativa;
- scopo compilato;
- procedura con almeno due passaggi;
- presenza di almeno una regola o limitazione;
- formato dell’output indicato;
- punto di arresto o verifica umana definito.

Il download è abilitato solo quando la struttura minima è completa.

## 🧪 Prova individuale

L’esercitazione guidata dura circa **10 minuti**:

1. Scegli **Sintesi di segnalazione** e leggi il file generato.
2. Modifica la **descrizione**, spiegando quando usare la skill.
3. Aggiungi un controllo alla **procedura** oppure alle **regole e limiti**.
4. Apri la visualizzazione **Come si legge**.
5. Scarica `SKILL.md` e lo `ZIP`.

La domanda finale è: rispetto a un prompt conservato in libreria, quali istruzioni non dovranno più essere riscritte? E chi dovrà comunque verificare il risultato?

## 💬 Prova facoltativa in chat

È possibile copiare le istruzioni e un caso fittizio per incollarli in una chat AI.

Questa prova è **manuale e didattica**: non equivale all’installazione di una skill nativa e non garantisce che l’ambiente riconosca automaticamente il file come skill.

Usa soltanto casi inventati e non inserire dati personali, pratiche reali o informazioni riservate.

## 💻 Come usare l’app

Il progetto è una **web app statica in un unico file HTML**.

- Non utilizza API o servizi esterni.
- Non richiede login o account.
- Non invia dati a un server.
- Non memorizza le risposte tra le sessioni.
- Funziona anche offline, dopo aver aperto il file.

### Aprire l’app

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Scegli un modello, compila i campi e scarica la skill.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/AI-Skill-Builder-in-Markdown.git](https://github.com/gigicogo/AI-Skill-Builder-in-Markdown.git)
cd AI-Skill-Builder-in-Markdown
```

## 📦 Download della skill

L’app consente di:

- scaricare il file `SKILL.md`;
- scaricare uno `ZIP` contenente una cartella con `SKILL.md`;
- copiare il Markdown negli appunti;
- visualizzare il file sia come codice sia in versione leggibile.

La compatibilità con l’ambiente AI scelto va sempre verificata direttamente in quell’ambiente.

## 🔐 Sicurezza e perimetro PA

L’app è pensata per un uso didattico e sicuro.

- Tutti gli scenari e i dati sono fittizi.
- Nessun dato viene trasmesso o tracciato.
- Non esistono connessioni a protocolli, gestionali o sistemi dell’ente.
- Non sono previste firme, invii automatici o azioni amministrative.
- Ogni output resta una **bozza da verificare**.

Una skill rende più coerente un metodo, ma non garantisce un risultato corretto, non attribuisce permessi e non sostituisce la valutazione del funzionario.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi modelli di skill per la PA.
- Esportazione in formati aggiuntivi.
- Esempi completi di skill e casi d’uso.
- Versione inglese dell’interfaccia.
- Integrazione con checklist organizzative e materiali di governance.
- Modalità per docenti con esempi proiettabili in aula.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi modelli, miglioramenti dell’interfaccia, esempi didattici e correzioni.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo modello.
3. Mantieni la struttura dei campi e le regole di sicurezza dell’app.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il
