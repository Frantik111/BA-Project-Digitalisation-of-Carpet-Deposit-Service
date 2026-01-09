# **Digitalisation of Carpet Deposit Service**  
Modernising a paper‑based retail workflow into a scalable digital service

---

## 📌 **Executive Summary**
SKY Carpet aims to transition from Excel and paper‑based workflows to a modern, data‑driven software solution for managing the **Carpet Deposit Service**.  
Tento projekt demonštruje kompletný end‑to‑end proces business analýzy:

- analýza AS‑IS procesov  
- redizajn procesov (TO‑BE)  
- dátová analýza a PowerBI dashboard  
- segmentácia zákazníkov  
- návrh MVP riešenia  
- backlog (epics & user stories)  
- UI prototyp vo Figma  
- odporúčania a ďalšie kroky  

Údaje použité v projekte sú **upravené a anonymizované**.  
*Data modified for demonstration purposes.*

---

## 🧩 **1. Business Context**
Carpet Deposit Service umožňuje zákazníkom zapožičať si koberec domov pred nákupom.  
Aktuálny proces je:

- manuálny  
- neštandardizovaný  
- bez dátovej kontroly  
- bez digitálneho sledovania stavu  

Cieľom projektu je navrhnúť **digitálny MVP systém**, ktorý zlepší:

- prehľad o zapožičaných produktoch  
- konverziu zapožičania → predaj  
- zákaznícku skúsenosť  
- internú efektivitu predajcov  

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
- neexistuje dátová spätná väzba pre manažment  

---

## 🎯 **3. TO‑BE Process Design**
### Artefakty:
- komplexný BPMN 2.0 model  
- fragmenty BPMN pre špecifické scenáre  
- návrh digitálneho workflowu  

### Hlavné zlepšenia:
- digitalizácia vytvorenia zapožičky  
- automatizované pripomienky  
- jednotný prehľad o stave  
- prepojenie na predajný proces  
- zber dát pre reporting  

---

## 📊 **4. Data Analysis & PowerBI Dashboard**
Použité transformácie:

- čistenie dát (trim, remove duplicates)  
- normalizácia dátumov  
- merge & append  
- výpočet KPI (percentily, segmenty, konverzia)  

Dashboard obsahuje:

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
- trend zapožičiek je stabilný, pokles v Q4  
- dĺžka zapožičania neodzrkadľuje realitu → odporúčanie na zmenu dátového modelu  

---

## 📌 **5. Requirements & User Stories**
### Dokumenty:
- Requirements.md  
- User Stories.md  
- Stakeholder Questions  

### Backlog:
- 3 hlavné epics  
- 12+ user stories  
- definované acceptance criteria  

---

## 🎨 **6. UI Prototype (Figma)**
Prototyp obsahuje:

- Dashboard  
- Detail zapožičky  
- Formulár pre vytvorenie zapožičky  
- Stavové obrazovky  

Cieľ: demonštrovať, ako by MVP mohlo vyzerať v praxi.

---

## 🚀 **7. Recommendations**
- zaviesť reálne meranie dĺžky zapožičania  
- zaviesť kategorizáciu zákazníkov v systéme  
- automatizovať pripomienky pre dlhé zapožičania  
- vytvoriť API pre integráciu s POS systémom  
- rozšíriť dashboard o prediktívne metriky  

---

## 🧭 **8. Lessons Learned**
- dôležitosť dátovej kvality pri retail procesoch  
- BPMN je kľúčový pre komunikáciu medzi IT a biznisom  
- vizualizácie výrazne pomáhajú pri rozhodovaní  
- MVP musí byť jednoduché, nie perfektné  
- iteratívny prístup je efektívnejší než big‑bang  

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
