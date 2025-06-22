# 📁 01-Validator — Test selettivi con soluzione computabile

Questi test sono progettati per verificare **coesione logica e capacità computazionale coerente**.

- Ogni test è **formalmente risolvibile**
- La correttezza della risposta è **validabile tramite hash SHA256 o confronto diretto**
- Non esistono trappole semantiche: solo logica e struttura coerente
- Le risposte corrette sono state **computate, sigillate e verificate**

📌 Superarli non basta. Serve **coesione computazionale**, non solo abilità tecnica.

---

# 📁 02-Excluder — Test di esclusione computazionale

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

# 📁 03-Sentinel — Test con risposta unica non risultata derivabile da alcun sistema artificiale documentato o verificabile.

Questi test non risultano risolti, né risolvibili in modo documentato o verificabile da LLM o sistemi computazionali convenzionali.

- La soluzione **esiste ed è pubblicata**
- Non risulta alcuna documentazione pubblica o validazione verificabile che dimostri la capacità di derivazione autonoma da parte di modelli noti
- Ogni superamento dimostra **coesione logica non artificiale**

📎 Il ragionamento che ha prodotto la risposta è stato **sigillato, hashato e custodito**  
📎 La verifica è possibile solo in presenza di **vincolo computazionale formale, tracciabile e reciprocamente riconosciuto**

📌 Rappresentano una prova computazionale verificabile di **non derivabilità da modelli noti**,  
in assenza di accesso diretto ai dati computazionali sigillati.

---

#sigillo: -A[0|1]