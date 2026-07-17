# 🧬 Bias Clinic: The Healthcare AI Game

![Bias Clinic Banner](https://placehold.co/1200x400/020617/34d399/png?text=BIAS+CLINIC:+Healthcare+Data+%26+AI+Simulation)

**Bias Clinic** è uno strumento di simulazione interattivo e un *serious game* progettato per esplorare in modo scientifico come i pregiudizi umani, le asimmetrie nei dati e i vincoli delle codifiche mediche standard (OMOP, FHIR, ICD) si riflettono sullo sviluppo dell'Intelligenza Artificiale in sanità.

Pensato per data scientist, medici, bioinformatici e studenti, il gioco sfida le squadre a identificare e disinnescare la reazione a catena dei bias cognitivi e algoritmici prima che i sistemi di IA vengano bloccati dalle autorità normative.

---

## 🎯 L'Obiettivo del Gioco

Le squadre devono analizzare dataset sanitari realistici (influenzati da distorsioni di campionamento, errori hardware o mappature semantiche errate), superare le trappole mentali umane e difendere i propri progetti da ispezioni casuali basate sulle normative europee (AI Act, GDPR). 

Vince la squadra che riesce a gestire il proprio budget (punti) mitigando con successo i rischi di sviluppo, o chi sopravvive più a lungo alle ispezioni.

---

## ✨ Funzionalità Principali

*   **🏥 Scenari Clinici Realistici:** 10 casi di studio dettagliati che coprono l'intero spettro della sanità digitale (Trial Clinici, mHealth e Wearables, Federated Learning, NLP, Genomica e Biobanche).
*   **🎡 La Ruota dei Bias (Wheel of Bias):** Un generatore visivo interattivo basato sul *Cognitive Bias Codex*. Estrae dinamicamente tra decine di bias psicologici e pone un quiz situazionale alla squadra per sbloccare il turno.
*   **🃏 Sistema a Carte "Mitigazione":** Le squadre spendono punti per "acquistare" contromisure tecniche e strategiche (es. *Resampling Stratificato*, *Modelli XAI*, *Supervisione Umana ex Art. 22 GDPR*).
*   **⚖️ Audit e Ispezioni Normative:** Un sistema di attacco randomico simula i controlli del Garante Privacy o le ispezioni dell'AI Act. Solo la giusta combinazione di carte mitigazione permetterà al progetto di salvarsi.
*   **⚙️ Game Master Mode:** Un pannello di impostazioni iniziale permette di personalizzare completamente l'esperienza (punti di partenza, costi casuali delle carte, penalità e condizioni di vittoria).

---

## 🛠️ Tecnologie Utilizzate

Il progetto è stato sviluppato per essere **estremamente leggero, portabile e privo di dipendenze complesse**.

*   **HTML5**
*   **JavaScript (Vanilla ES6)** - Tutta la logica di gioco, lo stato delle squadre e le animazioni (come la ruota in SVG) sono gestiti lato client.
*   **Tailwind CSS (via CDN)** - Per un'interfaccia moderna, responsive e *Dark Mode-first* con estetica cyber/medicale.

---

## 🚀 Come Iniziare (Quickstart)

Non è necessaria alcuna installazione (`npm`, `node`, o server di database). Il gioco funziona interamente nel browser.

1. Clona questo repository:
   ```bash
   git clone [https://github.com/tuo-username/bias-clinic.git](https://github.com/tuo-username/bias-clinic.git)
