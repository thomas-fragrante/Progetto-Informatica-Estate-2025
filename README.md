# Progetto-Informatica-Estate-2025
## Descrizione dell'applicazione
Questa applicazione, sviluppata in Unity, simula un registro elettronico per la gestione di studenti e voti. Il progetto implementa un sistema di login per l'accesso, permette di aggiungere nuovi studenti, assegnare voti in diverse materie e visualizzare le medie. L'interfaccia utente è pensata per essere intuitiva, con schermate dedicate alla gestione degli studenti e all'inserimento dei voti.
<br>

### Tecnologie utilizzate
Unity: Ambiente di sviluppo per la creazione dell'applicazione e della UI.

C#: Linguaggio di programmazione per la logica di backend.

Unity UI: Framework per la creazione dell'interfaccia utente interattiva.

<br>

### Classi principali e loro ruolo
GestoreDati (Modello): Gestisce la logica dei dati. Contiene la lista degli studenti e implementa algoritmi di ordinamento e ricerca.

Studente (Modello): Rappresenta l'entità "Studente". Implementa un dizionario per associare ogni materia a una lista di voti.

GestoreUtenti (Modello): Gestisce il sistema di autenticazione e memorizza le credenziali di accesso.

GestoreUI (Vista & Controllore): Gestisce l'interfaccia utente, le interazioni (click, input) e la navigazione tra i pannelli.

ICalcolabile (Interfaccia): Definisce il contratto per il calcolo della media. La classe Studente la implementa, dimostrando il concetto di polimorfismo.

<br>

### Screenshot dell'interfaccia finale
(https://raw.githubusercontent.com/thomas-fragrante/Progetto-Informatica-Estate-2025/main/Screenshots/Screenshot%202025-09-05%20152423.png)
