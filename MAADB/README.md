# 🗄️ Modelli e Architetture Avanzati di Basi di Dati (MAADB)

![Status: Finito](https://img.shields.io/badge/Status-%E2%9C%85%20Finito-success?style=for-the-badge)
![A.A. 2025/26](https://img.shields.io/badge/A.A.-2025%2F26%20%C2%B7%202%C2%B0%20sem.-blue?style=for-the-badge)

Appunti del corso di **Modelli e Architetture Avanzati di Basi di Dati** della Laurea Magistrale in Informatica, Università degli Studi di Torino.

---

## 📚 Materiale

| File | Descrizione | Pagine |
| :--- | :--- | :---: |
| 📄 [`appunti_MAADB.pdf`](appunti_MAADB.pdf) | Appunti completi della parte di teoria, presi a lezione e revisionati | 87 |
| 📝 [`maadb_exam.pdf`](maadb_exam.pdf) | Riassunto molto sintetico della teoria che serve per la parte di laboratorio | 25 |

## 🧭 Argomenti trattati

### `appunti_MAADB.pdf`: architettura interna di un DBMS

1. **Introduzione e storia dei modelli di dati**: livelli di astrazione, modelli gerarchico, reticolare, relazionale, a oggetti, semistrutturato e a grafo
2. **Architettura di un DBMS**: storage, buffer manager, recovery, controllo della concorrenza, query engine
3. **Dischi e memoria secondaria**: tempi di accesso, pre-fetching, organizzazione dei file
4. **Pagine e record**: record a lunghezza fissa e variabile, organizzazione delle pagine, heap file
5. **Indici**: ISAM, B+ tree, indici clusterizzati e non, chiavi composte, indici hash
6. **Analisi dei costi**: modello di costo in I/O e scelta dell'indice
7. **Buffer manager**: politiche di rimpiazzo, sequential flooding, algoritmo clock, Query Locality Set Model
8. **Valutazione degli operatori**: selezione, proiezione, ordinamento, algoritmi di join
9. **Ottimizzazione delle query**: piani logici e fisici, stima dei costi, ordine dei join, programmazione dinamica
10. **Concorrenza e transazioni**: proprietà ACID, anomalie, serializzabilità, controllo ottimistico, timestamp e MVCC
11. **Crash recovery**: politiche steal/no-force, Write-Ahead Logging, checkpoint

### `maadb_exam.pdf`: sistemi distribuiti e NoSQL

- **Sistemi data-intensive**: OLTP e OLAP, data warehouse, data lake, affidabilità e metriche di prestazione
- **Modelli di dati**: relazionale, a documenti, a grafo, schemi analitici, altri modelli NoSQL
- **Replicazione**: single-leader, multi-leader, leaderless, replication lag, scritture concorrenti
- **Sharding**: strategie di partizionamento, hot spot, ribilanciamento, request routing, indici secondari
- **Consistenza e consenso**: eventual vs strong consistency, linearizzabilità, teorema CAP, Two-Phase Commit
- **Batch e stream processing**: MapReduce, modello dataflow (Spark, Flink), message broker, Change Data Capture, CQRS
- **Casi di studio**: MongoDB, Neo4j (Cypher), Amazon DynamoDB

## 💻 Progetto di laboratorio

Il codice del progetto di laboratorio è in una repository separata:

🔗 **[AlessandroZappatore/Maadb_lab](https://github.com/AlessandroZappatore/Maadb_lab)**

---

⚠️ Sono appunti personali e possono contenere errori: se ne trovi uno, apri una issue o una pull request.

⬅️ [Torna all'elenco dei corsi](../README.md)
