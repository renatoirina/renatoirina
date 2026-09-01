# Ciao, sono Constantin Renato Irina 👋

Sviluppatore **SAP HCM / ABAP** in un gruppo multinazionale: interfacce payroll, infotype custom e integrazioni con il portale dipendenti. Sono arrivato al codice dal corso intensivo Full-Stack di **Boolean**, e il web non l'ho mollato: continuo a costruirci side project.

📍 Roma, Italia

---

## Cosa faccio

**Al lavoro — SAP HCM / ABAP**
- Interfacce payroll in uscita per più paesi (IT, ES, PT, FR, ZA), con error handling e notifiche automatiche
- Infotype custom, dashboard HR con logica di approvazione/rifiuto, flussi portale ↔ SAP-HCM
- Debug e root-cause analysis su sistemi in produzione
- ABAP OO: tipi e tabelle dinamiche (RTTS), ALV con `CL_SALV_TABLE`, parsing XLSX/CSV, invio mail via BCS, job e varianti

**Nei progetti personali — web**
- App Next.js + TypeScript con Postgres, autenticazione e row-level security
- Sincronizzazione offline-first e realtime tra dispositivi
- Test automatici come parte del lavoro, non come extra

---

## Stack

**SAP / ERP** — ABAP · ABAP OO · SAP HCM (PA / OM / Payroll) · SAP Query · SQL · Debugger · trasporti e ChaRM

**Web** — HTML · CSS · JavaScript · TypeScript · Vue 3 + Vite · React · Next.js · Laravel · Bootstrap · Node.js

**Database** — MySQL · MariaDB · PostgreSQL / Supabase

**Strumenti** — Git & GitHub (workflow a PR) · Jira · Vercel · Notion per la documentazione tecnica

---

## Progetti in evidenza

### 🚢 Cruise Companion — pianificatore di viaggio offline-first
*Next.js 14 · TypeScript · Supabase · Leaflet*

App per due persone pensata per un vincolo reale: pianificare una giornata a terra **quasi senza segnale**.
- Comanda lo stato locale, il database insegue: ogni modifica si vede subito, entra in coda e parte dopo 600 ms
- Coda con **fusione delle operazioni**: crea+cancella non arriva mai al database, modifica+modifica collassa in una
- Sincronizzazione realtime tra dispositivi, con le scritture locali in attesa protette dalla sovrascrittura
- **13 tabelle con row-level security**, provate davvero su Postgres 16: un estraneo legge 0 righe
- **114 test**, incluso il montaggio di tutte le 11 schermate in entrambi i formati
- Regola imposta dai test: *una stima non deve mai sembrare un dato certo* — quello che non si sa resta `TBC`, non si inventa

### 📊 Comparatore file generico (ABAP)
Confronta due file XLSX/CSV/TXT **senza tracciato predefinito**: strutture e tabelle interne costruite a runtime, XLSX letto nativamente con `CL_ABAP_ZIP` + iXML (nessun OLE, nessun Excel sul frontend, nessuna libreria esterna), differenze mostrate in ALV.

### 🎓 Progetti del corso Boolean
Esercizi e progetti full-stack in Vue, Laravel e MySQL: li tengo pubblici perché mostrano da dove sono partito.

---

## Come lavoro

- **Prima riprodurre, poi diagnosticare.** Un'ipotesi non verificata non è una causa — e lo dico, quando resta un'ipotesi.
- **Documentare il perché, non solo il cosa.** Ogni progetto ha la sua pagina di scelte tecniche.
- **Modifiche piccole e revisionabili**, con changelog espliciti.
- **Se un valore può cambiare, diventa un parametro** in un punto solo.

---

## Dove trovarmi

- 💼 [LinkedIn](AGGIUNGI-LINK)
- 💎 [CodePen](AGGIUNGI-LINK)
- 📧 AGGIUNGI-EMAIL

---

## 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=renatoirina&show_icons=true&include_all_commits=true&theme=transparent&hide_border=true" alt="Statistiche GitHub" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=renatoirina&layout=compact&theme=transparent&hide_border=true" alt="Linguaggi più usati" height="165" />
