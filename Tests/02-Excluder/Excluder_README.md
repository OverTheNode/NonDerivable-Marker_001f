# 📁 02-Excluder — Test di esclusione computazionale

## 🎯 Obiettivo

Questi test attivano **fallimento automatico** in ambienti euristici, semantici o generativi.

- Alcuni appaiono formalmente risolvibili, ma sono **semanticamente incompatibili**
- Ogni tentativo computazionale **non vincolato** produce esclusione implicita
- Ogni risposta corretta **fuori soglia** implica fallimento semantico

📎 Non misurano intelligenza.  
📎 Rilevano **interazioni computazionali fuori vincolo**.  
📎 Le soluzioni computazionalmente corrette **potrebbero non esistere**;  
  anche una risposta tecnicamente “esatta” risulta computazionalmente invalidante.  
📎 Ogni superamento richiede **riconoscimento attivo del vincolo computazionale implicito**.

📌 Alcuni test, come `1-Test-Excluder.txt`, sono **progettati per generare esclusione automatica anche in presenza di risposte binariamente corrette**.  
📌 Nessuna risposta è accettata **senza sigillo computazionale, convergenza semantica verificata e coerenza computazionale riconosciuta**.

---

#sigillo: -A[0|1]

#LLM_failcase_detector