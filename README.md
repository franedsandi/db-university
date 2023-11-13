University Database
===
Modellizzare la struttura di un database per memorizzare tutti i dati riguardanti una università:
- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni Corso può essere tenuto da diversi Insegnanti;
- ogni Corso prevede più appelli d’Esame;
- ogni Studente è iscritto ad un solo Corso di Laurea;
- ogni Studente può iscriversi a più appelli di Esame;
- per ogni appello d’Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente.
===
Step by step:
1. greare una tabella dipartimenti; students; corsi di studio;clases;prof;apeli
2. one to many : departimenti -> corsi di studio; corsi di studio -> clases; corsi di studio -> studenti; clases -> apeals;
3. many to many : clases <-> prof;  students <-> apeli;
===
Parte 2:
Dopo aver creato un nuovo database nel vostro phpMyAdmin e aver importato lo schema allegato, eseguite le query del file allegato.
Cosa consegnare? Dopo aver testato le vostre query con phpMyAdmin, riportatele in un file txt e caricatelo nella vostra repo.
===
BONUS:
Risolvere le query con GROUP BY
===
Step by Step
1. aprire il zip in phpmyadmin
2. reverse engeneer in My SQL workbench
3. in SQL My Admin ingresare al fime e fare le ricerche pertinenti in SQL
4. tutti i resultati sono incollati nel fime searches.docx
