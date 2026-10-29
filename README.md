# Esercitazione B — Skill Builder in Markdown

Web app statica per il Modulo B, rivolta a dipendenti della Pubblica Amministrazione italiana. Non usa API, servizi esterni, account o dati reali dell'Ente.

## Pubblicazione su GitHub Pages

1. Crea un repository pubblico (es. `AI-Skill-Builder-Markdown`).
2. Carica **`index.html` nella cartella principale** del repository.
3. Vai in **Settings → Pages**, scegli **Deploy from a branch**, `main` e `/ (root)` e salva.
4. Apri l'indirizzo GitHub Pages fornito dall'interfaccia e inseriscilo nella slide 30 del corso.

È sufficiente un solo file: `index.html`. Non serve un server, né configurare chiavi/API.

## Funzioni

- Esempi di skill PA: sintesi di segnalazione, bozza di risposta, verifica preliminare di una determina.
- Modello vuoto per creazione libera.
- Generazione in tempo reale di `SKILL.md` con frontmatter `name` e `description`.
- Visualizzazione del testo Markdown e resa leggibile.
- Verifiche formali: nome, descrizione, scopo, procedura, limiti, formato di output.
- Download di `SKILL.md`, o ZIP con `nome-skill/SKILL.md`.
- Test didattico manuale: copia istruzioni e un caso **fittizio** da incollare in chat AI.

**Importante:** i controlli sono semplici verifiche della struttura e non certificano la qualità della skill né la compatibilità con una specifica piattaforma. La prova in chat non equivale all'installazione di una skill nativa.

## Sicurezza

L'app funziona interamente nel browser. Non memorizza né invia dati. Il laboratorio va svolto usando soltanto esempi inventati. Non caricare dati personali o documenti riservati in chat AI non autorizzate.
