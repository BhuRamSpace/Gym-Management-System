# Gym Management Application

## Descrizione del progetto

Gym Management Application è un progetto sviluppato per gestire le attività principali di una palestra attraverso un sistema di ruoli e permessi.

L’applicazione consente di gestire corsi, prenotazioni e utenti, differenziando le funzionalità disponibili in base al ruolo dell’account autenticato.

I ruoli disponibili sono:

- Admin
- Trainer
- Utente

## Funzionalità implementate

### Admin

L’amministratore ha il controllo completo dell’applicazione e può:

- visualizzare nella dashboard il numero totale di corsi, utenti registrati e membri dello staff;
- creare, modificare ed eliminare utenti, trainer e corsi;
- consultare tutte le prenotazioni effettuate;
- visualizzare informazioni dettagliate su corsi, utenti e trainer.

### Trainer

Il trainer può gestire esclusivamente i corsi assegnati e le relative prenotazioni.

Può:

- prenotare un utente a un proprio corso;
- annullare una prenotazione relativa ai propri corsi;
- visualizzare la lista degli utenti iscritti;
- consultare i corsi svolti con informazioni su data, orario e numero di prenotazioni.

### Utente

L’utente può gestire la propria partecipazione ai corsi.

Può:

- registrarsi ed effettuare il login;
- prenotarsi a un corso;
- annullare una prenotazione;
- aggiungere o rimuovere commenti ai corsi;
- visualizzare le proprie prenotazioni.

## Gestione dei ruoli

L’applicazione implementa una gestione delle autorizzazioni basata sui ruoli, limitando l’accesso alle funzionalità in base al profilo autenticato.

| Ruolo | Permessi |
|--------|-----------|
| Admin | Gestione completa del sistema |
| Trainer | Gestione dei corsi assegnati e delle prenotazioni |
| Utente | Prenotazione corsi e gestione delle proprie attività |

## Obiettivo del progetto

L’obiettivo del progetto è stato mettere in pratica la gestione di operazioni CRUD, autenticazione e autorizzazione basata sui ruoli, organizzando un piccolo sistema gestionale ispirato al contesto di una palestra.

Durante lo sviluppo ho lavorato sulla separazione delle responsabilità tra utenti, gestione delle prenotazioni e protezione dell’accesso alle funzionalità in base ai permessi disponibili.

## Tecnologie utilizzate

- Java
- Spring Boot
- PostgreSQL
- Maven
- Thymeleaf
- Hibernate / JPA
