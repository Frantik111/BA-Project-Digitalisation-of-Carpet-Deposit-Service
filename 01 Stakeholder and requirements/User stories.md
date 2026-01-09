# 💬 User Stories

## 🎯 Epic: Evidencia požičania koberca
→ cieľ: znížiť chybovosť a zrýchliť proces.

### User stories
- Ako predajca chcem digitálne vyplniť formulár aby som sa vyhol chybám a papierom
> Acceptance criteria:
> - Formulár sa uloží do databázy bez chýb
> - Povinné polia: Klient, Predajca, Dátum vystavenia, Dátum do vrátenia, Produkt, cena
> - Systém zobrazí chybu ak povinné polia nie sú vyplnené, nepustí dalej
> - Údaje sú dostupné pre ďalšie kroky
- Ako predajca chcem vyhľadať klienta v našej databázy klientov
> Acceptance criteria:
> - Vyhľadávanie funguje podľa priezviska, ičo, názvu firmy
> - Ak klient existuje, systém zobrazí údaje vo formulári
> - Ak klient neexistuje, systém ponúkne možnosť založenie nového klienta
> Acceptance criteria:
- Ako predajca chcem upraviť klienta, ak sa zmenili údaje o klientovi
> Acceptance criteria:
> - Upravením klienta vytvorím novšiu verziu klienta, pôvodné verzie informácií o klientovi archivujem
- Ako predajca chcem pridať do formulára koberec na základe Art. Num.
> Acceptance criteria:
> - Zadám číslo koberca a načíta mi do formulára - názov, cenu, rozmer
> - Klient na základe údajov vie jednoznačne identifkovať koberec vo formulári
- Ako predajca chcem vyžiadať spracovanie GDPR údajov formou, ktorá neobťažuje klienta
> Acceptance criteria:
> - Ak klient už súhlasil so spracovaním údajov, nežiadam na novo aby som neobťažoval klienta a neriskoval že mi zamietne spracovanie údajov
> - Odkaz na GDPR dokumenty na firemnej stránke s aktuálnym platným znením
- Ako klient nechcem nič podpísať navyše čo nemusím
> Acceptance criteria:
> - Podpisujem dodací list ku kobercom
- Ako klient chcem vedieť pravidlá služby
> Acceptance criteria:
> - Klient je informovaný stručne na papieri, plné znenie na webe
> - Klient sa k podrobným informáciam dostane viacerími metódami, a môže si vybrať, ktorá mu vyhovuje viac
- Ako predajca chcem vedieť, ktoré koberce sú aktuálne zapožičané
> Acceptance criteria:
> - Zoznam s informáciami o kobercoch a termínoch zápožičky a vrátenia
- Ako predajca chcem vedieť, ktoré zápožičky sú po termíne
> Acceptance criteria:
> - Farebne zvýraznené zápožičky
- Ako predajca chcem u produktu vidieť pôvodnú cenu a cenu poskytnutú klientovi
> Acceptance criteria:
> - Ak je cena rovnaká tak sa uvádza len raz
> - Vyčíslenie zľavy v eurách
> - Ak nie je zľava poskytnutá formulár neukazuje text zľava, aby klient nebol motivovaný k pýtaniu zľavy
- Ako predajca chcem mať možnosť doplniť prípadnú poznámku pre formulár Interne
> Acceptance criteria:
> Poznámku vidia iba zamestnanci, informácia je maskovaná ako pin kód od karty v bankovej aplikácií, aby zvedavý klient nevidel na monitore predajcu
- Ako predajca chcem mať možnosť doplniť prípadnú poznámku pre formulár viditeľný pre klienta
> Acceptance criteria:
> - Červeno zvýraznený text na objednávke
- Ako predajca chcem jednoducho vrátiť koberec
> Acceptance criteria:
> - kliknem v objednávke na vrátené
> - automaticky sa ku kobercu / objednávke priradí dátum s vrátením
> - tlačidlo že objednávka je vyriešená a uzavretá - nevrátené koberce boli vyfakturované
- Ako klient chcem potvrdenie o vrátení koberca a že nemám žiadne záväzky voči firme
> - V tlačenej forme
> - na jedno kliknutie
> Acceptance criteria:
> - Vytvorenie potvrdenia o vrátení koberca pre klienta na jendo kliknutie
- Ako predajca chcem digitálnu kópiu formulára klientovi na email
> Acceptance criteria:
> - objednávka v pdf
> - ak klient nemá email možnosť poslať email predajcovi, objednávku následne vytlačí
> - realizácia do 30 sekúnd
- Ako predajca chcem, digitálny podpis od klienta na zapožičanie, tak aby klient podpísal preberací protokol s QR kódom, ktorý následne naskenujem a elektronicky priložím k objednávke, aby som mal právne platný doklad o zapožičaní a nemusel uchovávať papierovú verziu.
  ➡️táto user story vyžaduje refainment
> Acceptance Criteria:
> - Klient podpíše protokol s QR kódom pri prevzatí koberca.
> - Po naskenovaní sa dokument automaticky uloží do systému k objednávke.
> - QR kód zabezpečí jednoznačnú identifikáciu dokumentu.
> - Papierová verzia sa po naskenovaní zlikviduje, elektronická verzia sa stáva originálom.
> - Dokument je dostupný pre manažéra a predajcu v archíve.

## 🎯 Epic: Reporting a štatistiky ➡️ z agilného prístupu budú informácie dopĺňané a zlepšované Just In Time
→ cieľ: podpora rozhodovania a marketingu.

### User stories
- Ako manažér predaja chcem aby predajca pri vrátení koberca evidoval dôvod vrátenia
- Ako manažér predaja chcem vedieť, ktoré zápožičky viedli k predaju koberca
- Ako manažér predaja chcem vidieť ktoré zápožičky sú aktívne
- Ako manažér predaja chcem mať daschboard s prehľadom viacerých KPI - nutné doplniť informácie u stakeholdera
- Ako manažér predaja chcem mať prístup k údajom o zápožičkách a klientoch pre marketingové údaje

## 🎯 Epic: Notifikácie 
→ cieľ: zlepšiť zákaznícku skúsenosť a kontrolu.

### User stories
- Ako klient chcem mať pripomienku že koberec mám vrátiť
- Ako predajca chcem mať upozornenie o zmeškaných výpožičkách
- Ako manažér predaja chcem mať stav o výkonnosti služby do emailu

