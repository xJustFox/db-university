### Nome repo: `db-university`
Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:
- sono presenti diversi `Dipartimenti` (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni `Dipartimento` offre più `Corsi di Laurea` (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- ogni `Corso di Laurea` prevede diversi `Corsi`(Materie) (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni `Corso` può essere tenuto da diversi Insegnanti;
- ogni `Corso` prevede più appelli d'`Esame`;
- ogni `Studente` è iscritto ad un solo `Corso` di Laurea;
- ogni `Studente` può iscriversi a più appelli di `Esame`;
- per ogni appello d'`Esame` a cui lo `Studente` ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente. 

Pensiamo a quali entità (tabelle) creare per il nostro database e cerchiamo poi di stabilirne le relazioni. Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.


### Esercizio di oggi: DB UNiversity
Dopo aver creato un nuovo database nel vostro phpMyAdmin e aver importato lo schema allegato (non dovete scompattare il file zip, semplicemente andate nella sezione importa, e fate drag and drop oppure prendetelo dai file delle vostre cartelle, esattamente come visto a lezione), eseguite le query del file allegato. <br>
Cosa consegnare? <br>
Dopo aver testato le vostre query con phpMyAdmin, riportatele in un file txt, md o altro e caricatelo nella vostra repo. <br>
#### BONUS:
Selezionare nome, descrizione e periodo di tutti i corsi che hanno sito web diverso da null, cfu compresi tra 9 e 12 e che sono del primo anno ed ordinarli in ordine decrescente