# Introduzione Progetto
Questa repository contiene tutti i documenti relativi allo sviluppo della prima prova d'esame.

Per poter accedere al progetto occorre seguire questi passi:

Step 1: creare una cartella vuota all'interno del proprio computer

Step 2: accedere nella cartella e aprire il terminale (File > Apri Windows Powershell)

Step 3: copiare e incollare questo comando
        ```
        git clone https://github.com/virginiamarega/Esame_Marega_Virginia.git
        ```
        
All'interno della cartella creata in precedenza verrà creata un'altra cartella chiamata "Esame_Marega_Virginia"

Step 4: accedere alla cartella "Esame_Marega_Virginia" e per visualizzare il sito occorre ***cliccare due volte sul file index.html***
        si aprirà la pagina html sviluppatata

Step 5: per visualizzare il codice occorre aprire il file html con uno strumento, che può essere Blocco Note, Note++, Visual Studio o Visual Studio Code, oppure qualsiasi strumento che permette la visualizzazione del codice

# Link ai documenti
Per accedere alle piattaforme utilizzate per la fase di analisi è possibile accedervi tramite i link sottostanti:
- #### [Mirò](https://miro.com/app/board/o9J_l6MkzoQ=/)
- #### [Team Figma](https://www.figma.com/team_invite/redeem/VCxzwCAo70golS8wMFtxZi)
- #### [Mock Applicativo Figma](https://www.figma.com/file/gapy1TGFhutlHgAi2yHmw1/Applicativo?node-id=0%3A1)
- #### [Cartella in Drive](https://drive.google.com/drive/folders/1FQEXgmy4oxFInOlcd2wIREhmhkMsuFx6?usp=sharing)
- #### [Marega_Sistema_Innovativo Docs](https://docs.google.com/document/d/1-jHPAbyxrSvylMH0Qjzta6vDXQ8XkOgLEQB9oXpcWys/edit?usp=sharing)
- #### [Mock Sistema Innovativo Figma](https://www.figma.com/file/yFbcnxLfTM5d7f6pCT7t0a/Sistema-Innovativo?node-id=0%3A1)

Ps. I link relativi ai servizi di Google sono accessibili soltanto con ***l'account della scuola***, mentre i link realtivi a Mirò e Figma ***occorre avere un account*** (se no non si può accedere ai vari file).

# Prototipizazzione
Il mock dell'sito è accessibile tramite questo link [Mock Applicativo Figma](https://www.figma.com/file/gapy1TGFhutlHgAi2yHmw1/Applicativo?node-id=0%3A1)

Esso è stato implementato seguento dei criteri:
- utilizzando dei ***colori neutri***, come nero/bianco e scala di grigi, ***colori più accesi*** (giallo, verde e rosso) per necessità come avvisi, bottoni per particolari necessità, icone, ed altro, e infine è stata creata una ***palette di blu*** come colori secondary (per ora non utilizzata);
- il font utilizzato è ***Roboto*** con le diverse taglie di font (regular, medium, bold, light, thin);

Inizialmente è stato creato un file per il design system, contentente tutti i colori, font, dimensioni e bottoni, per la realizzazione del prototipo.

Successivamente è stato sviluppato il prototipo seguendo le necessità che sono sorte durante l'analisi e la progettazione (personas, customer journey map e state transition storyboard).

Le pagine che sono state realizzate con Figma sono:
- Pagina con lista, contenente la possibilità di filtraggio e ordinamento
- Pagina di dettaglio, contenente tutti i dettagli di un elemento
- Landing Page, contenente tutte le informazioni riguardanti ai servizi proposti dall'azienda


# Sviluppo Applicativo
L'applicativo è stato strutturato in questo modo:
- ***file index.html*** - contiene il codice riguardante la landing page;
- ***file details_item.html*** - contiene il codice riguardante il dettaglio di un elemento;
- ***cartella style*** - contiene tutti i file riguardanti gli stili, quali font (***font.css***), colori e dimensioni testi (***global_styles***), stili personalizzati degli elementi presenti nei file html globali, quali navbar, footer, etc(***custom_styles.css***);
        - successivamente sono stati creati dei file css contenenti gli stili personalizzati delle pagine:
                - landing page(***custom_landing_styles.css***)
- ***cartella assets*** - contiene due sottocartelle: ***font***, che contiene i file dei font, ***img*** che contiene tutte le immagini interessate all'sito, ***icons*** che contiene i file png delle icone;

Le pagine che sono state realizzate sono:
- Landing Page

# Sistema Innovativo
## Docs
La progettazione del sistema innovativo (file ***Marega_Sistema_Innovativo***) è accessibile tramite questo link [Marega_Sistema_Innovativo Docs](https://docs.google.com/document/d/1-jHPAbyxrSvylMH0Qjzta6vDXQ8XkOgLEQB9oXpcWys/edit?usp=sharing) .

All'interno del file è presente la progettazione del sistema, con un'introduzione, il flusso ed altre informazioni.

## Mock
Il mock è accessibile tramite questo link [Mock Sistema Innovativo Figma](https://www.figma.com/file/yFbcnxLfTM5d7f6pCT7t0a/Sistema-Innovativo?node-id=0%3A1)

La struttura è stata sviluppata seguendo gli stili già esistenti negli Apple Watch.