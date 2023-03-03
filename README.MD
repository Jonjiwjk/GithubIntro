# Git e GitHub

## Che cosa sono i VCS?

Un *`VCS`* (Version Control System) è un sistema software che gestisce le modifiche apportate ai file di un progetto e mantiene traccia delle versioni precedenti.

Le proprietà che un VCS deve avere sono:

* Tracciamento delle modifiche al codice nel tempo
* Gestione di versioni multiple del codice
* Facilità di collaborazione tra team di sviluppo
* Possibilità di tornare a versioni precedenti del codice
* Monitoraggio delle modifiche effettuate da diverse persone

## Che cos'è Git?

Git è un sistema di controllo versione (VCS) open source basato su istantanee (snapshot) dei file, che ha le seguenti **funzionalità aggiuntive**:

* Creazione di branch per sviluppare in parallelo
* Gestione di merge tra branch
* Risoluzione dei conflitti
* Utilizzo di tag per marcare versioni importanti (milestone)
* Supporto per repository remoti per la collaborazione

## Che cos'è GitHub?

GitHub è una piattaforma web che offre hosting per progetti software basati su Git. Oltre a offrire hosting per i repository Git, GitHub fornisce anche una vasta gamma di strumenti per la collaborazione, la documentazione e la gestione delle attività.

Le proprietà di GitHub sono:

* Hosting di repository Git
* Strumenti di collaborazione come issue tracker, pull request e code review
* Funzionalità di documentazione come wiki e README
* Integrazione con altri strumenti di sviluppo [CI/CD](https://www.redhat.com/it/topics/devops/what-is-ci-cd)
* Interfaccia utente intuitiva e collaborazione con altri utenti e team
* Possibilità di scegliere tra versioni pubbliche e private del repository
* Supporto per la gestione dei branch e dei merge.

## Perchè usare Git e GitHub?

Git e GitHub sono utilizzati insieme per gestire il ciclo di vita del codice software. Git permette di tracciare le modifiche apportate al codice e di collaborare con altri sviluppatori, mentre GitHub fornisce un'infrastruttura per l'hosting del codice e offre una serie di strumenti per la collaborazione, la documentazione e la gestione delle attività.

Gli sviluppatori usano Git e GitHub per:

* Tracciare le modifiche al codice nel tempo
* Collaborare con altri sviluppatori su un progetto
* Risolvere conflitti di codice e gestire il merging di codice
* Documentare il codice e le attività di sviluppo
* Automatizzare il processo di sviluppo con integrazioni CI/CD
* Condividere il codice con il pubblico o con un team chiuso.

In sintesi, Git e GitHub sono usati per rendere più efficiente e collaborativo il processo di sviluppo software.

---

## Approfondimenti

## Gli stati e le azioni

In Git, ogni file nella cartella di lavoro può trovarsi in uno dei tre possibili stati: *`staged`*, *`modified`* o *`committed`*.

* Lo stato *`staged`* si verifica quando un file viene modificato e la nuova versione viene contrassegnata per essere aggiunta al repository locale. Questo avviene utilizzando il comando *`git add`*.

* Lo stato *`modified`* si verifica quando un file è stato modificato ma non è ancora stato contrassegnato per essere aggiunto al repository. In altre parole, le modifiche al file non sono ancora state registrate.

* Lo stato *`committed`* si verifica quando le modifiche a un file sono state aggiunte al repository locale. Questo avviene utilizzando il comando *`git commit`*, che salva le modifiche in modo permanente nel repository.

Inoltre, Git offre tre azioni per gestire questi stati e sincronizzare il repository locale con il repository remoto.

* Il comando *`git push`* viene utilizzato per aggiungere tutti i file commessi presenti nel repository locale al repository remoto, rendendoli visibili a chiunque abbia accesso al repository remoto.

* Il comando *`git fetch`* viene utilizzato per ottenere i file dal repository remoto e aggiornare il repository locale, ma senza aggiornare la cartella di lavoro.

* Il comando *`git merge`* viene utilizzato per unire le modifiche presenti nel repository locale con la cartella di lavoro.

* Il comando *`git pull`*, combina l'effetto di *`git fetch`* e *`git merge`*, ottenendo i file dal repository remoto e aggiornando la cartella di lavoro con le modifiche presenti nel repository locale.

![gli stati e le azioni](./assets/images/status_actions.png)

---

### GUIDE PER L'INSTALLAZIONE E CONFIGURAZIONE

[Git](./GUIDE/GIT.MD)

[GitHub](./GUIDE/GITHUB.MD)

---

### ESERCITAZIONI

[ESERCITAZIONE 01 - Creazione Repository Locale](./ESERCITAZIONI/ESERCITAZIONE-01.MD)

[ESERCITAZIONE 02 - Creazione di un Repository Remoto](./ESERCITAZIONI/ESERCITAZIONE-02.MD)

[ESERCITAZIONE 03 - Clonazione di un Repository Remoto](./ESERCITAZIONI/ESERCITAZIONE-03.MD)

[ESERCITAZIONE 04 - Modifica di un Repository Remoto](./ESERCITAZIONI/ESERCITAZIONE-04.MD)
