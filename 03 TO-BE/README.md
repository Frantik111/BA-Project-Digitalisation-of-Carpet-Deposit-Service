# 03 TO-BE - Budúci Stav Procesu

## ℹ️ Popis priečinka

Priečinok `03 TO-BE` obsahuje dokumentáciu budúceho stavu (TO-BE - To Be) digitalizovaného procesu služby depozitu kobercov. Ide o cieľový stav po implementácii digitalizácie vrátane všetkých očakávaných zlepšení a optimalizácií.

### 📊 BPMN Model

#### 📄 [BMPN Processes.bpmn](BMPN%20Processes.bpmn)
Úplný Business Process Model and Notation (BPMN) model popisujúci budúcich procesov. Súbor obsahuje detailnú špecifikáciu nasledovných procesov:
Vo formáte *.bpmn vytvorený v https://bpmn.io/

**1. Notification Engine (Notifikačný Engine)**
- Automatizovaný systém pre správu notifikácií
- Dva hlavné procesy:
  - **Proces nájdenia zmeškanych pôžičiek** (Overdue Reminders)
    - Spustenie: Denne o 8:00
    - Akcia: Automatické vyhľadanie zmeškaných pôžičiek v Lending DB
    - Výstup: Posielanie pripomienok predajcom
  - **Proces pripomienok na koniec pôžičky** (Ending Reminders)
    - Spustenie: Denne o 8:00
    - Akcia: Automatické vyhľadanie pôžičiek končiacich zajtra
    - Výstup: Posielanie notifikácií zákazníkom

**2. Proces zapožičania kobercov (Customer Processes)**
- Zobrazené väzby medzi klientom, predajcom, skladom
- Ukážka procesu, digitalizované sub-procesy

**3. Proces vrátenia kobercov (Salesperson Processes)**
- Zobrazené väzby medzi klientom, predajcom, skladom
- Ukážka procesu, digitalizované sub-procesy


### 🖼️ Screenshots

Priečinok obsahuje obrázky procesov z bpmn súboru:
- **BPMN 1.jpg** - Diagram vytvorenia zápožičky
- **BPMN 1-1.jpg, BPMN 1-2.jpg** - Detaily podprocesov
- **BPMN 2.jpg** - Diagram vrátenia zápožičky
- **BPMN 2-1.jpg, BPMN 2-2.jpg** - Detaily podprocesov
- **BPMN 3.jpg** - Diagram notifikačného systému

## 📊 Business Analytický Pohľad

### Zlepšenia v porovnaní s AS-IS

1. **Automatizácia** - Nahradenie manuálnych úloh automatizovanými servismi
2. **Časovanie** - Plánované denné procesy vo fixných časoch (8:00)
3. **Integracia** - Priame spojenie medzi participantmi (zákazníci, predajcovia, SKY Carpet)
4. **Databáza** - Centralizované úložisko v Lending DB
5. **Notifikácie** - Automatické upozornenia pre zákazníkov a predajcov

## Ďalšie Kroky

Tento model slúži ako základňa pre:
1. Technickú implementáciu systému
2. Konfiguraci workflow engine-u
3. Definíciu API integrations
4. Testing a validácia procesov
