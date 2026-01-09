# **Digitalisation of Carpet Deposit Service**  
Modernising a paper‑based retail workflow into a scalable digital service

---

## 📌 **Executive Summary**
SKY Carpet aims to transition from Excel and paper‑based workflows to a modern, data‑driven software solution for managing the **Carpet Deposit Service**.  
This project demonstrates a complete end‑to‑end business analysis lifecycle:

- AS‑IS process analysis  
- TO‑BE process redesign  
- data analysis and PowerBI dashboard  
- customer segmentation  
- MVP requirements definition  
- backlog creation (epics & user stories)  
- UI prototyping in Figma  
- recommendations and next steps  

Označenie **Carpet** je uprednostňované kvôli SK prostrediu; **Rug** sa používa len pri EN komunikácii.

Údaje použité v projekte sú **upravené a anonymizované**.  
*Data modified for demonstration purposes.*

---

## 🧩 **1. Business Context**
Carpet Deposit Service umožňuje zákazníkom zapožičať si kusový koberec domov pred nákupom.  
Aktuálny proces je:

- manuálny  
- neštandardizovaný z pohľadu kvality údajov  
- bez dátovej kontroly  
- bez digitálneho sledovania stavu  

Cieľom projektu je navrhnúť **digitálny MVP systém**, ktorý zlepší:

- prehľad o zapožičaných produktoch  
- konverziu zapožičania → predaj  
- zákaznícku skúsenosť  
- internú efektivitu predajcov  

### Artefakty:
- Stakeholder questions  
- User Stories & Epics  
- High‑Impact and High‑Level Requirements  

Pre malý rozsah a interné prostredie nebola vytvorená formálna stakeholder mapa.

---

## 🔍 **2. AS‑IS Analysis**
### Artefakty:
- AS‑IS deposit list  
- AS‑IS deposit template  
- Context Model  
- Functional Flow Diagram  
- Cross‑Functional Flow Diagram  

### Kľúčové zistenia:
- proces je manuálny a náchylný na chyby  
- neexistuje jednotný systém na sledovanie stavu  
- dĺžka zapožičania nie je reálne meraná  
- chýba dátová spätná väzba pre manažment  

---

## 🎯 **3. TO‑BE Process Design**
### Artefakty:
- komplexný BPMN 2.0 model  
- BPMN fragmenty pre špecifické scenáre  
- návrh digitálneho workflowu  

### Hlavné zlepšenia:
- digitalizácia vytvorenia zapožičky  
- automatizované pripomienky  
- jednotný prehľad o stave  
- prepojenie na predajný proces  
- zber dát pre reporting  

---

## 📊 **4. Data Analysis & PowerBI Dashboard**
### Použité transformácie:
- načítanie dát (batch xlsx súborov), výber tabuliek, nastavenie hlavičiek  
- čistenie dát (trim, remove duplicates, error handling)  
- normalizácia dátumov, zmena typov  
- výpočty dní, tvorba vlastných stĺpcov, transpozícia  
- merge & append  

### Dashboard obsahuje:
- počet zapožičiek  
- hodnotu zapožičaného tovaru  
- hodnotu predaja zo zapožičiek  
- dĺžku zapožičania  
- segmentáciu zákazníkov  
- heatmapu lokalít  
- percentilovú analýzu košíkov  

### Insights:
- 80 % predajov zo zapožičky je do 2000 €  
- najčastejšie zapožičiavané veľkosti sú 1,60×2,30 a 0,80×1,50  
- trend zapožičiek je stabilný, s poklesom v Q4  
- dĺžka zapožičania neodzrkadľuje realitu → odporúčanie na zmenu dátového modelu  

---

## 📌 **5. Jira BA Workflow**
Board kopíruje reálny BA lifecycle a umožňuje systematický rozpad úloh, prípravu podkladov a jasnú pripravenosť pre vývoj.

- Backlog štruktúrovaný podľa epikov a domén  
- User stories rozdelené na BA podúlohy (procesy, dáta, UI)  
- Workflow: **TO DO → IN ANALYSIS → READY FOR DEV**  
- Refinement príkladu „Vyhľadanie klienta“  
- AS‑IS analýza odhalila chyby z Excel vstupov a duplicity  
- Slúži ako základ pre TO‑BE proces, UI návrhy a akceptačné kritériá  

---

## 🎨 **6. UI Prototype (Figma)**
Prototyp obsahuje:

- Dashboard so všetkými zápožičkami  
- Detail zapožičky / vytvorenie  
- Vyhľadanie klienta  

Cieľ: demonštrovať, ako by MVP mohlo vyzerať v praxi.

---

## 🚀 **7. Recommendations**
- zaviesť reálne meranie dĺžky zapožičania  
- zaviesť kategorizáciu zákazníkov v systéme  
- automatizovať pripomienky pre dlhé zapožičania  
- vytvoriť API pre integráciu s fakturačným/pokladňovým systémom  
- rozšíriť dashboard o prediktívne metriky  

---

## 🧭 **8. Lessons Learned**
- dôležitosť dátovej kvality pri retail procesoch  
- BPMN je kľúčový pre komunikáciu medzi IT a biznisom  
- vizualizácie výrazne pomáhajú pri rozhodovaní  
- MVP musí byť jednoduché, nie perfektné  
- iteratívny prístup je efektívnejší než big‑bang  
- manuálnu prácu vo Figme je možné nahradiť AI generátormi CRUD šablón  
- projekt demonštruje šírku BA podkladov a analýz  

---

## 🔮 **9. Future Enhancements**
- mobilná aplikácia pre predajcov  
- automatické párovanie zapožičiek s predajom  
- prediktívny model konverzie  
- integrácia s CRM  
- digitálny podpis pri zapožičaní  

---

## 📝 **10. Disclaimer**
**Data modified for demonstration purposes.  
This project does not contain real company data.**

---

## 📜 **License**
This project is published under the **CC BY‑NC‑ND 4.0 license**.  
It is intended as a portfolio showcase for job applications.  
You may view and share it for non‑commercial, educational or evaluative purposes only.

© Zdenko Siegel, 2026
