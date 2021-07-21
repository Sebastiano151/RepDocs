# RepDocs

RepDocs è un sito web dove tutti gli utenti registrati possono caricare file esclusivamente in formato pdf.
I file devono essere documenti di qualsiasi tipologia e su qualsiasi argomento.
L'Utilizzo di RepDocs è molto intuitivo, pertanto verrà omessa la Guida.

# Realizzazione

RepDocs è stato realizzato senza l'uso di nessuna libreria esterna o framework sia per quanto riguarda il lato Front-End che per quanto riguarda il Lato Back-End.
La Responsività è stata implementata usando le CSS Grid e le CSS Media Query. Per quanto riguarda il lato Back-End è stato realizzato usando il linguaggio di programmazione lato server PHP. Le chiamate Asincrone al Server sono state implementate in Javascript usando AJAX, infine l'aggiornamento automatico degli item nei client è stato implementato usando la funzione Javascript setInterval e attraverso l'uso delle chiamate asincrone. Infine, RepDocs è dotato di un semplice Database Relazione implementato in SQL che ha lo scopo di memorizzare gli utenti registrati e i documenti caricati. La Connessione al Databese è implementata attraverso PDO. Sono state implementate le sessioni php per mantenere l'accesso di un utente loggato, e nel caso in cui l'utente non dovesse ricordare la password è stato implementato anche l'invio delle E_Mail per dare la possibilità di recuperarla.

# Linguaggi Utilizzati
HTML, CSS, JS (Lato Client); <br>
PHP (Lato Server); <br>
SQL (Creazione Modello Fisico DB Relazionale).

# Implementazione DB Relazionale

## Modello Entità-Relazioni
![ER](https://user-images.githubusercontent.com/28182917/126484423-3590513f-d528-44a7-90c8-56254dfead13.jpeg)

## Modello Logico

![ML](https://user-images.githubusercontent.com/28182917/126486189-4905d105-fdd5-47d5-bb46-83583547d0dd.jpeg)

## Modello Fisico (In linguaggio SQL)

![Documento](https://user-images.githubusercontent.com/28182917/126486365-7e43304f-992d-4311-9f89-980aead9afe7.JPG)

![Utente](https://user-images.githubusercontent.com/28182917/126486379-1e6aaea9-735a-4d04-bdfe-8d3f96665ba8.JPG)

Nel Lato Back-End sono implementate anche operazioni di interrogazione, cancellazione e modifica dei record del Database.

# Riferimenti

## SQL<br><br>
Operazioni Interrogazione DB: https://www.w3schools.com/sql/sql_select.asp<br>
Operazioni Eliminazione Record DB: https://www.w3schools.com/sql/sql_delete.asp<br>
Operazioni Modifica Record DB: https://www.w3schools.com/sql/sql_update.asp<br>
Operazioni Creazione Tabella DB: https://www.w3schools.com/sql/sql_create_table.asp<br>
Operazione Creazione Database: https://www.w3schools.com/sql/sql_create_db.asp<br><br><br>

## JS AJAX<br><br>
https://www.w3schools.com/js/js_ajax_intro.asp<br>
https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX<br><br><br>

## Connessione DB attraverso PDO

https://www.w3schools.com/php/php_mysql_connect.asp<br>
https://www.php.net/manual/en/class.pdo.php<br><br>

## Sessioni PHP

https://www.w3schools.com/php/php_sessions.asp







