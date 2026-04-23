# 📊 Database Relazionali - Appunti & Progetti

Questo repository contiene i miei appunti, esercizi e progetti mentre imparo i **database relazionali**.

## 📚 Obiettivi
- Comprendere i concetti base dei database relazionali  
- Imparare a progettare database efficienti  
- Scrivere query SQL corrette e ottimizzate  
- Applicare tutto in piccoli progetti pratici  

---

## 🧠 Argomenti trattati

- Modello relazionale  
- Tabelle, righe e colonne  
- Chiavi:
  - Primary Key
  - Foreign Key  
- Relazioni:
  - 1:1
  - 1:N
  - N:M  
- Normalizzazione (1NF, 2NF, 3NF)  
- SQL base:
  - `SELECT`
  - `INSERT`
  - `UPDATE`
  - `DELETE`  
- Join:
  - `INNER JOIN`
  - `LEFT JOIN`
  - `RIGHT JOIN`  

---

## 🛠️ Tecnologie utilizzate

- SQL  
- MySQL / PostgreSQL / SQLite  

---

## 📁 Struttura del progetto

/appunti        -> teoria e spiegazioni  
/esercizi       -> query di pratica  
/progetti       -> mini progetti completi  

---

## 🚀 Esempio di query

```sql
SELECT nome, cognome
FROM utenti
WHERE eta > 18;