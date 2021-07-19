# Introduzione Progetto
Questa repository contiene tutti i documenti relativi allo sviluppo della prima prova d'esame.

Per poter accedere al progetto occorre seguire questi passi:

Step 1: creare una cartella vuota all'interno del proprio computer

Step 2: accedere nella cartella e aprire il terminale (File > Apri Windows Powershell)

Step 3: copiare e incollare questo comando
        ```
        git clone https://github.com/virginiamarega/its-esame-finale.git
        ```
        
All'interno della cartella creata in precedenza verrà creata un'altra cartella chiamata "its-esame-finale"

Step 4: accedere alla cartella "its-esame-finale" e per visualizzare il sito occorre ***cliccare due volte sul file index.html***
        si aprirà la pagina html sviluppatata

Step 5: per visualizzare il codice occorre aprire il file html con un editor, che può essere Blocco Note, Note++, Visual Studio o Visual Studio Code, oppure qualsiasi strumento che permette la visualizzazione del codice

# Link ai documenti
Per accedere alle piattaforme utilizzate per la fase di analisi è possibile accedervi tramite i link sottostanti:
- #### [Mirò](https://miro.com/app/board/o9J_l6MkzoQ=/)
- #### [Team Figma](https://www.figma.com/team_invite/redeem/VCxzwCAo70golS8wMFtxZi)
- #### [Mock Applicativo Figma](https://www.figma.com/file/gapy1TGFhutlHgAi2yHmw1/Applicativo?node-id=0%3A1)
- #### [Cartella in Drive](https://drive.google.com/drive/folders/1FQEXgmy4oxFInOlcd2wIREhmhkMsuFx6?usp=sharing)
- #### [Marega_Sistema_Innovativo Docs](https://docs.google.com/document/d/1-jHPAbyxrSvylMH0Qjzta6vDXQ8XkOgLEQB9oXpcWys/edit?usp=sharing)
- #### [Mock Sistema Innovativo Figma](https://www.figma.com/file/yFbcnxLfTM5d7f6pCT7t0a/Sistema-Innovativo?node-id=0%3A1)

Ps. I link relativi ai servizi di Google sono accessibili soltanto con ***l'account della scuola***, mentre i link realtivi a Mirò e Figma ***occorre avere un account*** (se no non si può accedere ai vari file).

# Task Iniziali Comuni

## Personas
La parte della personas è stata sviluppata seguendo le necessità sorte all'interno dell'esercizio, dove c'è la necessità di promuovere le attrazioni delle località italiane.  La personas è stata pensata come una persona che vuole viaggiare e conoscere nuove località e attrazioni, che ha delle passioni che vorrebbe accrescere visistando nuove città italiane che non aveva ancora visto.

## CJM
Il flusso che segue questa persona parte dalla prima fase di esigenza dove nasce la voglia di visitare una nuova attrazione italiana.
Seguendo con la fase di ricerca, dove cerca i diversi posti da visitare; segue la valutazione e la prenotazione dove confronta le offerte e infine decide di prenotare la sua visita. Successivamente troviamo la preparazione dove si prepara alla partenza (stampa documenti, prepara lo zaino, e così via), segue la partenza, l'arrivo e lo svolgimento, concludendo con il ritorno a casa dove immagazina tutto quello che ha visto e imparato durante la sua visita.

## STS
Il percorso che svolge all'interno del sistema inizia da una visualizzazione di un post su instagram che la porta all'interno di una Landing Page. Interessata visualizza le località offerte dall'azienda e ne visualizza il dettaglio di quella che più le interessata. Decide quindi il giorno e il numero di biglietti, dopo l'inserimento dei dati anagrafici e dei dati del pagamento, conferma la prenotazione e riceve la conferma via mail.

# Prototipizazzione
Il mock dell'sito è accessibile tramite questo link [Mock Applicativo Figma](https://www.figma.com/file/gapy1TGFhutlHgAi2yHmw1/Applicativo?node-id=0%3A1)

Esso è stato implementato seguento dei criteri:
- utilizzando dei ***colori neutri***, come nero/bianco e scala di grigi, ***colori più accesi*** (giallo, verde e rosso) per necessità come avvisi, bottoni per particolari necessità, icone, ed altro, e infine è stata creata una ***palette di blu*** come colori secondary (per ora non utilizzata);
- il font utilizzato è ***Roboto*** con le diverse taglie di font (regular, medium, bold, light, thin);

Inizialmente è stato creato un file per il design system, contentente tutti i colori, font, dimensioni e bottoni, per la realizzazione del prototipo.

Successivamente è stato sviluppato il prototipo seguendo le necessità che sono sorte durante l'analisi e la progettazione (personas, customer journey map e state transition storyboard).

Le pagine che sono state realizzate con Figma sono:
- Pagina di dettaglio
- Landing Page

La realizzazione del prototipo della Landing page è stato pensato cercando di inserire le varie località, con al di sotto una o più località che sono meno frequentate, così da poter promuovere anch'esse. In seguito, è stato pensato di risaltare i pacchetti acquistabili con i dettagli più interessanti, sarebbe possibile tramite un bottone ricondurre l'utente a delle maggiori informazioni riguardanti i pass.
È stato anche aggiunto un form di contatto in caso che un utente avesse la necessità di richidere informazioni.

Invece per la realizzazione del prototipo del dettaglio è stato pensato di mettere come prime informazioni delle immagini descrittive e delle informazioni relative alla località e al sito che offre questa esperienza. Sempre nella parte delle informazioni sono state aggiunti i dati relativi alla città (breve descrizione), le varie attrazioni presenti e il prezzo dei pass.
Seguono poi altre località che potrebbero interessare all'utente (filtrate in base alla somiglianza delle varie località).

# Sviluppo Applicativo
L'applicativo è stato strutturato in questo modo:
- ***file index.html*** - contiene il codice riguardante la landing page;
- ***cartella style*** - contiene tutti i file riguardanti gli stili, quali font (***font.css***), colori e dimensioni testi (***global_styles***), stili personalizzati degli elementi presenti nei file html globali, quali navbar, footer, etc(***custom_styles.css***);
        - successivamente sono stati creati dei file css contenenti gli stili personalizzati delle pagine:
                - landing page(***custom_landing_styles.css***)
- ***cartella assets*** - contiene due sottocartelle: ***font***, che contiene i file dei font, ***img*** che contiene tutte le immagini interessate all'sito;

Le pagine che sono state realizzate sono:
- Landing Page

La pagina è stata sviluppata cercando di essere più possibile coerente con il prototipo sviluppato precedentemente, seguendo i criteri decisi in precedenza.

# Sistema Innovativo
## Docs
La progettazione del sistema innovativo (file ***Marega_Sistema_Innovativo***) è accessibile tramite questo link [Marega_Sistema_Innovativo Docs](https://docs.google.com/document/d/1-jHPAbyxrSvylMH0Qjzta6vDXQ8XkOgLEQB9oXpcWys/edit?usp=sharing) .

All'interno del file è presente la progettazione del sistema, con un'introduzione, il flusso ed altre informazioni.

## Mock
Il mock è accessibile tramite questo link [Mock Sistema Innovativo Figma](https://www.figma.com/file/yFbcnxLfTM5d7f6pCT7t0a/Sistema-Innovativo?node-id=0%3A1)

La struttura è stata sviluppata seguendo gli stili già esistenti negli Apple Watch.