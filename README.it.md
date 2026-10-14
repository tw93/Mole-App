# Mole App

[English](README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · [Español](README.es.md) · Italiano · [Português (Brasil)](README.pt-BR.md)

Documentazione ufficiale e supporto della community per **Mole for Mac** e **Mole for Windows**.

Le app per Mac e Windows sono app desktop native a pagamento, e l'acquisto di una licenza aiuta a finanziare sviluppo e aggiornamenti. Questo repository è dedicato a documentazione, domande e feedback e non contiene il codice sorgente delle app. La [Mole CLI](https://github.com/tw93/Mole) resta gratuita e open source.

## Scarica Mole

| App | Requisiti | Download | Guida utente |
| --- | --- | --- | --- |
| Mole for Mac | macOS 14 o successivo, Apple Silicon o Intel | [Sito Mac](https://mole.fit/it/?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Aiuto Mac](https://mole.fit/it/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Mole for Windows | Windows 10 22H2 o Windows 11, x64 o ARM64 | [Sito Windows](https://mole.fit/it/windows?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) | [Aiuto Windows](https://mole.fit/it/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

Entrambe le app riuniscono in un'unica interfaccia pulizia, gestione delle app, manutenzione, analisi del disco e stato del sistema in tempo reale.

### Mole for Mac

Mole for Mac è un'app nativa in SwiftUI creata e mantenuta da [Tw93](https://github.com/tw93), con strumenti rapidi nella barra dei menu.

![Schermata di pulizia di Mole for Mac](https://mole.fit/img/it/clean.jpg)

| Strumento | Cosa puoi fare | Guida |
| --- | --- | --- |
| Pulizia | Controlla cache di app e browser, log e file di build degli strumenti di sviluppo prima di scegliere cosa rimuovere | [Pulizia del Mac](https://mole.fit/it/mac-cleaner?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| App | Disinstalla le app, controlla i loro residui, cerca aggiornamenti e gestisci gli elementi di avvio | [Gestione delle app](https://mole.fit/it/mac-app-uninstaller?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Ottimizza | Esegui la manutenzione di macOS, usa Pulisci schermo o Schermo acceso | [Manutenzione del Mac](https://mole.fit/it/mac-optimizer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Analizza | Trova file e cartelle di grandi dimensioni con una treemap del disco, mostrali nel Finder o sposta nel Cestino gli elementi selezionati | [Analisi del disco](https://mole.fit/it/mac-disk-analyzer?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |
| Stato | Consulta CPU, memoria, spazio di archiviazione, rete e temperatura, con alcuni dati scelti nella barra dei menu | [Monitor di sistema](https://mole.fit/it/mac-system-monitor?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) |

#### Pulizia AI · Preview

La build Preview aggiunge Pulizia e manutenzione AI dentro Pulizia. Controlla cache, versioni vecchie, sessioni vecchie, worktree eliminabili e strumenti da riga di comando inattivi di Claude Code, Codex, Cursor e altri strumenti AI. Le cache sono selezionate in partenza, mentre sessioni e strumenti richiedono la tua verifica. Memorie, piani e skill sono esclusi. Per i modelli locali vengono elencati solo i modelli Ollama non usati da un mese, da selezionare e rimuovere tramite Ollama. Trovi i dettagli nella [guida alla pulizia AI](https://mole.fit/it/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#docs-ai).

### Inizia sul tuo Mac

1. Scarica il DMG dal sito Mac qui sopra, trascina Mole in Applicazioni e aprilo. Se usi già Homebrew, `brew install --cask mole-app` installa l'app per Mac.
2. Avvia una scansione e controlla i risultati prima di rimuovere qualsiasi cosa. Se Mole segnala che manca l'Accesso completo al disco, segui la guida ai permessi qui sotto e riavvialo.
3. Dopo l'acquisto, apri il pannello Licenza con `Cmd + Shift + L`, incolla la chiave ricevuta nell'email di Dodo Payments e fai clic su Attiva.

[Articoli Mac](https://mole.fit/it/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Note di rilascio Mac](https://mole.fit/it/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

### Guide Mac selezionate

- [Mole CLI vs app per Mac](https://mole.fit/it/blog/mole-cli-vs-mac-app?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): le differenze tra lo strumento da terminale gratuito e l'app nativa a pagamento.
- [Mole è sicuro per Mac?](https://mole.fit/it/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): cosa va nel Cestino, cosa viene rimosso in modo definitivo e cosa resta protetto.
- [Cos'è Dati di sistema su Mac?](https://mole.fit/it/blog/what-is-system-data-on-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): scopri cosa occupa spazio prima di eliminare qualsiasi cosa.
- [Controllare i residui della disinstallazione su Mac](https://mole.fit/it/blog/mac-uninstall-leftovers-review-before-delete?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): verifica a chi appartengono i file e i dati condivisi prima della rimozione.
- [Eliminare i modelli di Ollama e LM Studio](https://mole.fit/it/blog/how-to-remove-ai-tool-leftovers-mac?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): distingui modelli scaricati, cache e dati personali.
- [Provare le app per Mac con Mole](https://mole.fit/it/blog/testing-mac-apps-one-by-one?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme): cosa rivelano installazioni reali e prove di disinstallazione.

### Mole for Windows

L'app per Windows migliora a ogni rilascio.

![Schermata di pulizia di Mole for Windows](https://mole.fit/img/windows-it/clean.jpg)

[Articoli Windows](https://mole.fit/windows/blog?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) · [Note di rilascio Windows](https://mole.fit/windows/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme)

## Feedback

- [Segnala un bug dell'app per Mac](https://github.com/tw93/Mole-App/issues/new?template=mac_bug.yml)
- [Segnala un bug dell'app per Windows](https://github.com/tw93/Mole-App/issues/new?template=windows_bug.yml)
- [Suggerisci una funzionalità](https://github.com/tw93/Mole-App/issues/new?template=feature_request.yml)
- [Fai una domanda o partecipa a una discussione](https://github.com/tw93/Mole-App/discussions)

Issue e discussioni sono pubbliche. Per domande su acquisto, attivazione o rimborso, scrivi a [hi@mole.fit](mailto:hi@mole.fit). Invia le segnalazioni di sicurezza tramite il [canale di segnalazione privato](.github/SECURITY.md).

Per la diagnostica su Mac, apri il menu con il logo di Mole e scegli Esegui Doctor. Invia il rapporto in privato a [hi@mole.fit](mailto:hi@mole.fit), insieme alla versione dell'app e a cosa è successo.

Per bug e richieste di funzionalità della CLI, usa [tw93/Mole](https://github.com/tw93/Mole/issues).

## FAQ

### Un repository GitHub pubblico significa che le app sono open source?

Questo repository contiene documentazione e feedback della community. Il codice sorgente delle app per Mac e Windows è privato. La [Mole CLI](https://github.com/tw93/Mole) è gratuita e open source.

### Devo installare la CLI per usare le app?

No. Mole for Mac e Mole for Windows sono app desktop indipendenti. Installare la CLI non installa nessuna delle due app.

### Le app sono gratuite?

Le app usano licenze una tantum. Mole for Mac costa **$19 USD per due Mac**, senza abbonamento e con aggiornamenti gratuiti, versioni principali incluse. La [pagina ufficiale dei prezzi](https://mole.fit/pricing.md?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) riporta le condizioni attuali. Prezzi e disponibilità di Windows sono sul relativo sito. La CLI open source è gratuita.

### Posso provare l'app per Mac prima di acquistarla?

La scansione è gratuita e ogni strumento a pagamento offre due prove. Analisi del disco e stato del sistema si possono consultare senza licenza. Il [centro assistenza Mac](https://mole.fit/it/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) spiega come scaricare, provare e attivare l'app.

### Posso spostare la licenza Mac su un nuovo computer?

Apri il pannello Licenza sul vecchio Mac con `Cmd + Shift + L`, disattivala, poi attiva la stessa chiave sul nuovo Mac. Se il vecchio Mac non è disponibile, accedi al [Dodo Payments Customer Portal](https://customer.dodopayments.com/) con l'email di acquisto e disattivala da lì. Il numero di dispositivi dipende dalla licenza acquistata. L'edizione attuale copre due Mac.

### Dove trovo la chiave di licenza e la fattura?

Cerca Dodo Payments nella posta in arrivo e nello spam, oppure accedi al [Dodo Payments Customer Portal](https://customer.dodopayments.com/) con l'email usata al momento dell'acquisto per trovare chiave, ordine e fattura. Se ti serve ancora aiuto, scrivi a [hi@mole.fit](mailto:hi@mole.fit) indicando l'email di acquisto o il Payment ID. Non pubblicare questi dati nelle issue pubbliche.

### E se l'app per Mac non fa per me?

Scrivi a [hi@mole.fit](mailto:hi@mole.fit) entro 14 giorni dall'acquisto, indicando il Payment ID o l'email di acquisto. La [politica di rimborso](https://mole.fit/it/refund?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) riporta le condizioni complete.

### L'app per Mac carica i miei file o i risultati della scansione?

Scansione e pulizia avvengono in locale sul tuo Mac. Mole non carica contenuti dei file, nomi dei file né risultati della scansione, e il suo registro delle operazioni locale non viene caricato automaticamente. L'[informativa sulla privacy](https://mole.fit/it/privacy?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) spiega attivazione della licenza, aggiornamenti e altre funzioni che contattano servizi online.

### Perché Mole chiede l'Accesso completo al disco?

macOS limita l'accesso ad alcuni dati delle app. L'Accesso completo al disco permette a Mole di controllare quelle posizioni. I percorsi protetti e la tua whitelist restano validi, quindi concedere l'accesso non rende ogni file un candidato alla pulizia. Consulta la [guida ai permessi](https://mole.fit/it/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme#doctor-permission-fda).

### Posso ripristinare i file dopo la pulizia del Mac?

Le app disinstallate e i relativi file residui selezionati vanno nel Cestino e si possono ripristinare finché restano lì. La pulizia delle cache è definitiva per impostazione predefinita, con un'opzione per usare il Cestino in Impostazioni. Alcune azioni di manutenzione rimuovono i dati direttamente e non si possono annullare. La [guida alla sicurezza](https://mole.fit/it/blog/is-mole-safe?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) spiega ogni operazione.

### Come funzionano gli aggiornamenti del Mac e le funzioni Preview?

Mole ha un sistema di aggiornamento integrato, e le [note di rilascio ufficiali](https://mole.fit/it/releases?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) descrivono ogni versione. Le funzioni contrassegnate come Preview nella documentazione richiedono la build Preview finché non arrivano in una versione stabile.

### Posso usare Mole con la tastiera o con VoiceOver?

Mole supporta la navigazione da tastiera e VoiceOver. La treemap è visiva, e gli stessi file si possono scorrere nell'elenco degli elementi più grandi con la tastiera o con VoiceOver. Trovi dettagli e limiti attuali nella [guida all'accessibilità](https://mole.fit/it/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).

### Qual è il sito ufficiale?

**mole.fit** è il sito ufficiale delle app. Usa i link di download qui sopra per i pacchetti aggiornati. La CLI gratuita si trova su [tw93/Mole](https://github.com/tw93/Mole).

### Dove trovo istruzioni dettagliate?

La [documentazione Mac](https://mole.fit/it/docs?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) spiega gli strumenti e le loro regole di sicurezza. Il [catalogo delle app provate](https://mole.fit/it/tested-apps?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) contiene note su installazione, disinstallazione e residui delle singole app. Per configurazione, attivazione o risoluzione dei problemi, consulta il [centro assistenza Mac](https://mole.fit/it/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme) o il [centro assistenza Windows](https://mole.fit/it/windows/help?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme). I termini di licenza sono nei [termini di servizio](https://mole.fit/it/terms?utm_source=github.com&utm_medium=referral&utm_campaign=mole-app-readme).
