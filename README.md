# UninaSwap

**UninaSwap** è un'applicazione desktop Java creata per gestire la compravendita, lo scambio e il regalo di oggetti all'interno della comunità universitaria. Il progetto combina un frontend realizzato con **Java Swing** e un backend che si interfaccia con **Supabase** (PostgreSQL) per la gestione dei dati in cloud.

## 📋 Funzionalità

### 🔐 Gestione Utenti
* **Autenticazione Sicura**: Sistema di Login e Registrazione per nuovi studenti.
* **Profilo Utente**: Pannello dedicato per visualizzare e modificare i propri dati personali (Username, Email, Password).

### 📢 Gestione Annunci
Gli utenti possono creare e gestire annunci per diverse finalità:
* **Vendita**: Per cedere oggetti in cambio di denaro.
* **Scambio**: Per barattare oggetti con altri utenti.
* **Regalo**: Per cedere oggetti gratuitamente.

Le categorie di oggetti supportate includono:
* 📚 Libri
* 💻 Elettronica
* 👕 Abbigliamento
* 🎸 Strumenti Musicali
* 📦 Altro (Misc)

### 🤝 Marketplace e Offerte
* **Esplora Annunci**: Navigazione tra gli annunci disponibili con filtri di ricerca.
* **Sistema di Offerte**: Possibilità di inviare offerte monetarie o proposte di scambio con gli altri studenti.
* **Gestione Transazioni**: Visualizzazione delle offerte inviate e ricevute.

### 📊 Dashboard e Statistiche
* Visualizzazione di grafici e statistiche sull'utilizzo (tramite integrazione *JFreeChart*).

## 🛠️ Stack Tecnologico

* **Linguaggio**: Java (Versioni supportate: 11+)
* **GUI Framework**: Java Swing (con componenti personalizzati per un look & feel moderno).
* **Database**: Supabase (PostgreSQL).
* **Architettura**: Pattern MVC (Model-View-Controller) con DAO (Data Access Object) per la persistenza.
* **Dipendenze Esterne**:
    * `org.jfree.jfreechart`: Per la generazione di grafici.
    * `java.sql`: Per la connettività JDBC.
    * `java.desktop`: Per i componenti dell'interfaccia grafica.

## 🚀 Guida all'Installazione

### Prerequisiti
* **Java JDK** (versione 11 o superiore).
* **Git** per clonare il repository.
* Una connessione internet attiva (per il database cloud).

### Setup
1. **Clona il repository**:
   ```bash
   git clone [https://github.com/marcooo33/uninaswap.git](https://github.com/marcooo33/uninaswap.git)
   ```

2. **Compilazione ed Esecuzione**: Il progetto è un modulo Java. Puoi compilarlo ed eseguirlo tramite riga di comando o importarlo nel tuo IDE preferito. Punto di ingresso dell'applicazione: ``src/gui/Main.java``







