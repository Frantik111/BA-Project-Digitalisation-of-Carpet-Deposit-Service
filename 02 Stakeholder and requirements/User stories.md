# 💬 User Stories

## 🎯 Epic: Evidencia požičania koberca
→ cieľ: znížiť chybovosť a zrýchliť proces.

### User stories
- Ako predajca chcem digitálne vyplniť formulár aby som sa vyhol chybám a papierom
> Acceptance criteria:
> Formulár sa uloží do databázy bez chýb
> Povinné polia: Klient, Predajca, Dátum vystavenia, Dátum do vrátenia, Produkt, cena
> Systém zobrazí chybu ak povinné polia nie sú vyplnené, nepustí dalej
> Údaje sú dostupné pre ďalšie kroky
- Ako predajca chcem vyhľadať klienta v našej databázy klientov
> Acceptance criteria:
> Vyhľadávanie funguje podľa priezviska, ičo, názvu firmy,
> Ak klient existuje, systém zobrazí údaje vo formulári
> Ak klient neexistuje, systém ponúkne možnosť založenie nového klienta
- Ako predajca chcem upraviť klienta, ak sa zmenili údaje o klientovi
> Upravením klienta vytvorím novšiu verziu klienta, pôvodné verzie informácií o klientovi archivujem
- Ako predajca chcem pridať do formulára koberec na základe Art. Num.
> Zadám číslo koberca a načíta mi do formulára - názov, cenu, rozmer
> Klient na základe údajov vie jednoznačne identifkovať koberec vo formulári
- Ako predajca chcem vyžiadať spracovanie GDPR údajov formou, ktorá neobťažuje klienta
> Ak klient už súhlasil so spracovaním údajov, nežiadam na novo aby som neobťažoval klienta a neriskoval že mi zamietne spracovanie údajov
> Odkaz na GDPR dokumenty na firemnej stránke s aktuálnym platným znením
- Ako klient nechcem nič podpísať navyše čo nemusím
> Podpisujem dodací list ku kobercom
- Ako klient chcem vedieť pravidlá služby
- Ako predajca chcem vedieť, ktoré koberce sú aktuálne zapožičané
- Ako predajca chcem vedieť, ktoré zápožičky sú po termíne
- Ako predajca chcem u produktu vidieť pôvodnú cenu a cenu poskytnutú klientovi
- Ako predajca chcem mať možnosť doplniť prípadnú poznámku pre formulár Interne
- Ako predajca chcem mať možnosť doplniť prípadnú poznámku pre formulár viditeľný pre klienta
- Ako predajca chcem jednoducho vrátiť koberec
- Ako predajca chcem digitálnu kópiu formulára klientovi na email
- Ako predajca chcem digitálny podpis od klienta za zápožičku
- Ako predajca chcem, aby klient podpísal preberací protokol s QR kódom, ktorý následne naskenujem a elektronicky priložím k objednávke, aby som mal právne platný doklad o zapožičaní a nemusel uchovávať papierovú verziu.
> Acceptance Criteria:
> Klient podpíše protokol s QR kódom pri prevzatí koberca.
> Po naskenovaní sa dokument automaticky uloží do systému k objednávke.
> QR kód zabezpečí jednoznačnú identifikáciu dokumentu.
> Papierová verzia sa po naskenovaní zlikviduje, elektronická verzia sa stáva originálom.
> Dokument je dostupný pre manažéra a predajcu v archíve.
- Ako klient chcem potvrdenie o vrátení koberca a že nemám žiadne záväzky voči firme

## 🎯 Epic: Reporting a štatistiky - z agilného prístupu budú informácie dopĺňané Just In Time
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

