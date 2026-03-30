# BEGRIPPENLIJST ITDS CONSULTANCY - STRATEGIE 2026-2028

*Een complete gids voor de strategische visie en marktanalyse*

---

## 1. WET- EN REGELGEVING (COMPLIANCE)

### DORA (Digital Operational Resilience Act)
Een Europese wet die sinds 17 januari 2025 actief is. DORA zorgt ervoor dat financiële instellingen (zoals verzekeraars) goed beschermd zijn tegen cyberaanvallen en digitale storingen. Het gaat niet alleen om hun eigen beveiliging, maar ook die van hun partners en leveranciers (Third-Party Risk Management). DNB voert thematisch toezicht uit in 2025-2026. Boetes kunnen oplopen tot €10M of 5% van de jaaromzet.

**In de praktijk:** Verzekeraars moeten een TPRM-platform hebben, regelmatig incident response tests uitvoeren, en binnen 4-72 uur incidenten rapporteren aan DNB.

### AI Act
De eerste Europese wet die het gebruik van kunstmatige intelligentie (AI) reguleert. De wet treedt augustus 2026 in werking. Het verbiedt gevaarlijke AI en stelt strenge eisen aan AI-systemen met een hoog risico (zoals pricing en underwriting bij verzekeraars). Verzekeraars moeten model registratie, bias testing en explainability (XAI) implementeren.

**In de praktijk:** NN Group heeft 191 AI use cases live en moet deze allemaal voor augustus 2026 AI Act-compliant maken.

### ESG (Environmental, Social, and Governance)
De criteria die de duurzaamheid en maatschappelijke impact van een bedrijf meten. Het gaat om milieu (E), sociale aspecten (S) en eerlijk bestuur (G). Sinds 2025 verplicht via CSRD-rapportage voor grote verzekeraars.

**In de praktijk:** Verzekeraars moeten rapporteren over CO2-uitstoot, klimaatrisico's in hun portefeuille, en groene investeringen.

### CSRD (Corporate Sustainability Reporting Directive)
EU-richtlijn die grote bedrijven (waaronder verzekeraars) verplicht om uitgebreid te rapporteren over duurzaamheid en ESG. Eerste rapporten verschijnen in 2025.

### Sanctiewet 2.0 & KYC (Know Your Customer)
Regels om criminaliteit zoals witwassen en terrorismefinanciering tegen te gaan. Verzekeraars moeten precies weten wie hun klanten zijn (KYC) en controleren of zij niet op internationale sanctielijsten staan (EU, UN, OFAC). Door geopolitieke ontwikkelingen (Rusland/Oekraïne, Midden-Oosten, China) veranderen sanctielijsten wekelijks.

**In de praktijk:** DNB deelt forse boetes uit - Rabobank €368M (2024), ING €775M (2018), verzekeraars €5-20M.

### Perpetual KYC
Een methode waarbij klanten niet eens in de paar jaar, maar continu en automatisch worden gecontroleerd op basis van actuele data. Bij elke trigger (adreswijziging, UBO-wijziging, sanctielijst update) wordt automatisch een nieuwe check uitgevoerd.

**Het probleem:** 30-40% van klantdossiers bij verzekeraars is incompleet, handmatige checks kosten €50-150 per stuk.

### UBO (Ultimate Beneficial Owner)
De persoon die uiteindelijk meer dan 25% van een bedrijf bezit. Sinds 2020 verplicht geregistreerd bij KvK. Belangrijk voor KYC omdat een bedrijf schoon kan lijken, maar de UBO op een sanctielijst kan staan.

**Voorbeeld:** Nederlandse BV → Cyprus Holding → Russische UBO (moet gedetecteerd worden).

### PEP (Politically Exposed Person)
Politici, ministers, parlementsleden, rechters, hoge ambtenaren, directeuren staatsbedrijven, én hun familieleden (partner, kinderen, ouders). PEP's krijgen Enhanced Due Diligence. Blijven 12 maanden na functie nog PEP.

### CDD (Customer Due Diligence)
Het proces van klantonderzoek:
- **Simplified CDD:** Laag risico, basis checks
- **Standard CDD:** Normaal, identiteit + bron vermogen
- **Enhanced CDD:** Hoog risico (PEP's, high-risk landen), deep-dive research

### AML (Anti-Money Laundering)
Voorkomen dat crimineel geld wordt "gewassen". Bij verzekeringen: premie betalen met zwart geld, uitkering ontvangen als "wit" geld.

### Poortwachtersrol
Wettelijke term (Wwft - Wet witwassen en financieren terrorisme). Verzekeraars zijn "poortwachters": houden criminelen tegen door KYC en AML-maatregelen.

### OFAC (Office of Foreign Assets Control)
VS sanctielijst - extreem belangrijk voor internationale business. Ook EU bedrijven moeten checken (secondary sanctions).

### SAR (Suspicious Activity Report)
Melding aan FIU-NL (Financial Intelligence Unit) bij vermoeden witwassen/terrorisme financiering. Verplicht, en de klant mag het NIET weten (tipping off = strafbaar).

### AVG / GDPR (Algemene Verordening Gegevensbescherming)
Europese privacywet die regelt hoe bedrijven met persoonsgegevens omgaan. Boetes tot €20M of 4% van omzet.

### NIS2 (Network and Information Security Directive 2)
EU-richtlijn voor cybersecurity bij kritieke infrastructuur. Vervangt NIS1, strengere eisen vanaf oktober 2024.

---

## 2. FINANCIËLE STRATEGIE & RISICO

### Solvency II
Europese regels die bepalen hoeveel kapitaal een verzekeraar als reserve moet aanhouden om met zekerheid claims te kunnen uitbetalen. Hoofdonderdelen: SCR (Solvency Capital Requirement), MCR (Minimum Capital Requirement), en ORSA (Own Risk and Solvency Assessment).

**Herziening 2024-2025:** Risicomarge daalt 15-30%, Volatility Adjustment +20-30bp, groene investeringen krijgen lagere kapitaaleis. Impact: €3-8B kapitaal vrijval sectorbreed. Deadline implementatie: 30 januari 2027.

### SCR (Solvency Capital Requirement)
Het kapitaal dat een verzekeraar moet aanhouden om een "1-in-200 jaar" gebeurtenis te overleven. Berekend via standaardformule of Partial Internal Models.

**Voorbeeld:** SCR ratio 180% betekent: verzekeraar heeft 1,8x meer kapitaal dan het minimum vereist.

### Partial Models (Gedeeltelijke Modellen) / PIM (Partial Internal Models)
Eigen rekenmodellen van verzekeraars die (na DNB-goedkeuring) risico's nauwkeuriger berekenen dan de standaardformule. Dit kan €50-200M kapitaal vrijspelen per verzekeraar. DNB eist rigoreuze validatie: data lineage, model validation, back-testing.

**Joint Effort kans:** Risk valideert modellen (actuarieel), Data bouwt infrastructuur (data lineage, automated reporting).

### Run-off Portfolios (Gesloten boeken)
Verzekeringen die niet meer worden verkocht, maar nog wel jarenlang moeten worden afgehandeld. Vaak oude levensverzekeringen (1980-2010) met gegarandeerd rendement 4-5%, lijfrentes met complexe fiscale regels, pensioencontracten die niet passen in nieuwe systemen.

**Het probleem:**
- €10-30M jaarlijkse beheerkosten per middelgroot portfolio
- Legacy IT (mainframes, COBOL) - expertise sterft uit door vergrijzing
- Kapitaal geblokkeerd (reserves vastzit, niet beschikbaar voor groei)
- DORA, Solvency II, CSRD compliance blijft vereist

**Concrete voorbeelden:**
- Aegon legacy: €100B+ oude lijfrentes
- VIVAT: Zoekt buyers voor run-off
- ASR Schade + Reaal + Europeesche: Drie legacy boeken na overnames

### Vrijval van kapitaal
Wanneer een verzekeraar door slimmere rekenmethodes (Partial Models) of regelgevingswijzigingen (Solvency II Review) minder geld in de reservepot hoeft te houden, komt dit geld vrij voor andere investeringen of dividenden.

### Kapitaaloptimalisatie
Het proces van het zo efficiënt mogelijk inzetten van reserves om de balans van het bedrijf te verbeteren. Combinatie van Solvency II optimization, Run-off sanering, en ALM (Asset Liability Management).

### ALM (Asset Liability Management)
Het beheren van de match tussen activa (beleggingen) en passiva (verplichtingen). Doel: voldoende rendement behalen om claims te kunnen betalen, zonder te veel risico.

### ORSA (Own Risk and Solvency Assessment)
Jaarlijkse eigen beoordeling door verzekeraar van alle risico's en kapitaalbehoefte. Verplicht onder Solvency II.

### SFCR (Solvency and Financial Condition Report)
Jaarrapport aan DNB en publiek over solvabiliteit, risico's en governance. Bevat o.a. SCR ratio, risicoanalyse, vooruitblik.

### QRT (Quantitative Reporting Templates)
Gedetailleerde kwantitatieve rapportages aan DNB. Duizenden datapunten, kwartaal- en jaarlijkse frequentie.

---

## 3. TECHNOLOGIE & AUTOMATISERING

### Legacy systemen
Verouderde computersystemen die nog in gebruik zijn. Ze zijn vaak duur in onderhoud (€10-30M/jaar) en moeilijk te koppelen aan nieuwe techniek zoals AI. Voorbeelden: mainframes met COBOL-code uit de jaren 80, oude verzekeringssystemen die niet cloud-ready zijn.

**Het probleem:** Expertise sterft uit - weinig developers kennen nog COBOL (€150-250/uur).

### Hyper-automatisering
Het streven om zo veel mogelijk bedrijfsprocessen volledig automatisch te laten verlopen met software en robots. Target: 80% van claims binnen 3 jaar volledig geautomatiseerd.

**Voorbeelden:**
- Achmea: >93% aanvragen online, >90% volledig digitaal
- Lemonade: 3 minuten gemiddeld, 32% volledig geautomatiseerd

### STP (Straight-Through Processing)
Volledig automatische verwerking van bijvoorbeeld een claim, van aanvraag tot uitbetaling, zonder menselijke tussenkomst. Bij simpele claims (autokras <€5k, glasschade standaard) kan dit binnen enkele minuten.

### RPA (Robotic Process Automation)
Software "robots" die repetitieve taken automatiseren: data-entry, rapportages, compliance checks. RPA kan 40-60% kostenreductie opleveren bij back-office operaties.

**Voorbeeld:** NN Group target: van 5 bots naar 50+ bots, met governance via Center of Excellence.

### API (Application Programming Interface)
Technische koppeling waarmee systemen met elkaar kunnen praten. API-first architectuur betekent: alle functionaliteit is beschikbaar via API's, zodat makkelijk geïntegreerd kan worden met partners (garages, makelaars, ziekenhuizen, apps).

### MLOps (Machine Learning Operations)
De technische werkwijze om AI-modellen betrouwbaar te gebruiken, te controleren en te onderhouden. Vergelijkbaar met DevOps maar dan voor AI/ML.

**Onderdelen:** Model registry, automated testing, monitoring (drift detection), automated retraining, version control.

### Human-in-the-loop
Een veiligheidsprincipe waarbij een mens altijd de uiteindelijke beslissing neemt of controleert bij belangrijke automatische processen. Belangrijk voor AI governance: niet alles volledig automatiseren, vooral niet bij high-risk beslissingen (claim afwijzen, polis weigeren).

### Responsible AI framework / AI Governance
Afspraken die zorgen dat AI eerlijk en ethisch wordt gebruikt, zonder bijvoorbeeld groepen mensen onbewust te discrimineren. Onderdelen: bias testing, explainability (XAI), model registry, 2nd/3rd line controls.

**AI Act eisen (augustus 2026):**
- Model registry (wat doet elk model?)
- Bias testing (discrimineert het niet?)
- Explainability (waarom deze beslissing?)
- Human oversight (wie controleert?)

### XAI (Explainable AI)
Technieken om AI-beslissingen uitlegbaar te maken. SHAP values, LIME, counterfactuals. Belangrijk voor AI Act compliance en klantcommunicatie ("waarom is mijn premie verhoogd?").

### Bias testing
Testen of een AI-model discrimineert op basis van gender, leeftijd, etniciteit, postcode, etc. AFM eist dit voor verzekeringsalgoritmes.

### Cloud (computing)
IT-infrastructuur die via internet wordt geleverd ipv eigen servers. Voordelen: schaalbaarheid, flexibiliteit, lagere kosten. Nadeel: afhankelijkheid van leveranciers (vendor risk), DORA-compliance vereist.

**Typen:** Public cloud (AWS, Azure, Google), Private cloud, Hybrid cloud.

### DevOps / DevSecOps
Werkwijze waarbij ontwikkeling (Dev), operations (Ops) en security (Sec) samenwerken om sneller en veiliger software te leveren.

### TPRM (Third-Party Risk Management)
Het proces van het beoordelen, monitoren en beheren van risico's bij externe leveranciers en partners. DORA verplicht dit voor alle kritieke ICT-leveranciers.

**DORA classificatie:**
- **Kritiek:** Uitval >2 uur = significante impact
- **Belangrijk:** Uitval >24 uur = beperkte impact
- **Niet-kritiek:** Geen directe impact

### SOC (Security Operations Center)
Team dat 24/7 netwerken en systemen monitort op cyberdreigingen. DORA vereist dit voor verzekeraars.

---

## 4. ORGANISATIE & MARKT

### Tiers (bijv. Tier 1, Tier 2)
Indeling van verzekeraars op basis van grootte, budgetten en strategisch belang:

**Tier 0 - Insurtechs (3):** Lemonade, Allianz Direct, Assurant - AI-first, geen legacy, kleine NL-budgets

**Tier 1 - Top Targets (5):** a.s.r., Achmea, NN Group, Aegon, CZ - €4-8B premie, grote budgetten (€10-50M projecten), post-merger integratie

**Tier 2-6 - Anderen (54):** Healthcare (VGZ, Menzis), Direct (FBTO, InShared), International (Generali, AIG), Niche (TT Club, UK P&I Club)

### Consolidatie
Het proces waarbij bedrijven samengaan of worden overgenomen, waardoor er minder maar grotere spelers in de markt overblijven.

**Voorbeelden:**
- a.s.r. + Aegon: €4,9B (grootste EU insurance deal 2023)
- VGZ + ONVZ: Samenwerking vanaf 2027
- Dealwaarde H1 2025: €565M totaal

### Synergie
Het extra voordeel (zoals kostenbesparing) dat ontstaat wanneer twee bedrijven samengaan.

**Voorbeeld:** a.s.r./Aegon target €185M jaarlijkse synergie door:
- IT-systemen consolideren (dubbele kosten weg)
- Back-office samenvoegen (minder FTE)
- Productportfolio rationaliseren (overlap elimineren)
- Inkoopvoordeel (grotere volumes)

### PMO (Project Management Office)
Centraal team dat grote transformaties coördineert. Bij post-merger integraties: PMO coördineert 50-100+ projecten tegelijk (IT, HR, legal, compliance, products).

### Strategic Risk Advisory
Advies waarbij risico's (zoals klimaat, cyber, Solvency II) worden gebruikt om betere zakelijke beslissingen te nemen en waarde te creëren, in plaats van alleen "voldoen aan de wet". Dit is de herpositionering van ITDS: van "Compliance as a Service" naar "Strategic Risk Advisory".

**Drie pijlers:**
1. **Kapitaaloptimalisatie:** Solvency II Partial Models, Run-off, ALM
2. **Operationele Efficiëntie:** Legacy migratie, automatisering, AI governance
3. **Strategische Compliance:** DORA, KYC, AI Act als enablers (niet als doel)

### Gap-analyse
Een onderzoek dat het verschil (het "gat") in kaart brengt tussen de huidige situatie en de gewenste situatie of nieuwe wetgeving.

**Voorbeeld:** DORA gap-analyse toont aan: beleidsdocumenten aanwezig (✓), maar TPRM platform ontbreekt (✗).

### Joint Effort BL Risk & BL Data
De unieke ITDS differentiator: Business Line Risk (compliance, actuarieel, governance) en Business Line Data (IT delivery, MLOps, platforms) werken samen aan complexe vraagstukken.

**Voorbeelden waar dit cruciaal is:**
- Solvency II Partial Models: Risk valideert, Data bouwt infrastructuur
- DORA: Risk doet assessments, Data bouwt TPRM platform
- AI Act: Risk maakt governance, Data implementeert MLOps + XAI
- Run-off: Risk begrijpt producten, Data migreert systemen

### Insurtechs
Verzekeraars die vanaf oprichting volledig digitaal en AI-first zijn. Voorbeelden: Lemonade (3 min claims), Allianz Direct (100% online), Root (app-based auto insurance). Vaak geen legacy, maar ook kleine NL-markt.

### Volmacht / Gevolmachtigde agent
Een tussenpersoon die namens de verzekeraar polissen mag sluiten en soms ook schades mag afhandelen. Vergt strenge governance en DORA third-party risk management.

---

## 5. GEZONDHEIDSZORG

### IZA (Integraal Zorgakkoord)
Afspraken tussen overheid en zorgsector (2022) om de Nederlandse zorg betaalbaar en toegankelijk te houden. Impact voor verzekeraars: druk op kostenbeheersing, focus op preventie, digitalisering.

### Hybride zorg
Een combinatie van fysieke zorg (bezoek aan de arts) en digitale zorg (via apps of beeldbellen). VGZ target: 70% van zorgpaden hybrid.

**Voorbeelden:**
- Diabetes management: glucosemeter via app, online consult bij afwijkingen
- Fysiotherapie: eerste 3 sessies fysiek, oefeningen via app met video check-ins
- GGZ: intake fysiek of online, therapie via app (Minddistrict), maandelijkse video-sessies

**Voordelen:** 20-40% reductie ziekenhuisopnames, 50% goedkoper, betere toegankelijkheid.

### Databeschikbaarheid
Het veilig en eenvoudig kunnen delen van medische gegevens tussen zorgverleners voor betere patiëntzorg. GDPR-compliant, met patient consent.

**Uitdaging:** Interoperabiliteit - systemen van huisarts, ziekenhuis, apotheker, verzekeraar moeten kunnen praten.

### eHealth
Digitale gezondheidszorg via apps, wearables, thuismonitoring, beeldbellen. Zorgverzekeraars stimuleren dit via vergoedingen.

### Thuismonitoring
Patiënten thuis monitoren via sensoren en apps. Bijv. hartfalen-patiënten met dagelijks gewicht/bloeddruk meten, data naar ziekenhuis. 30% minder ziekenhuisopnames mogelijk.

### Zorginkoop
Het proces waarbij zorgverzekeraars contracten sluiten met zorgaanbieders (ziekenhuizen, huisartsen, fysiotherapeuten). Bepaalt welke zorg vergoed wordt en tegen welk tarief.

### Zilveren Kruis AI-strategie eis
Zilveren Kruis (grootste zorgverzekeraar, 3,8M klanten) eist dat **alle zorgaanbieders eind 2026 een AI-strategie hebben**. Impact: 5,000+ zorgaanbieders moeten ineens AI-readiness assessment, governance framework, model documentation, en AI Act compliance regelen.

**ITDS via-model opportunity:** €425M (5,000 × €50k-€200k gemiddeld).

---

## 6. CYBERRISICO'S & BEVEILIGING

### Ransomware
Malware die bestanden versleutelt en losgeld eist. **58% van grote claims (>€1M)** wordt veroorzaakt door ransomware. Gemiddeld losgeld: €500k-€5M. Recovery kost gemiddeld €4,2M in Nederland (IBM 2024).

### Datalek / Data breach
Ongeautoriseerde toegang tot persoonsgegevens. AVG verplicht melden binnen 72 uur aan Autoriteit Persoonsgegevens. Boetes tot €20M of 4% omzet. Reputatieschade vaak groter dan boete.

**Voorbeeld:** Lemonade 2024 datalek met rijbewijsgegevens - herstelmaatregelen doorgevoerd, reputatieschade.

### Penetration testing / Pen test
Ethische hackers proberen binnen te dringen in systemen om zwakke plekken te vinden. DORA verplicht dit jaarlijks voor verzekeraars.

### TLPT (Threat-Led Penetration Test)
Geavanceerde vorm van pen test waarbij een "red team" een echte aanval simuleert. Verplicht voor grote verzekeraars onder DORA. Om de 2-3 jaar.

### Incident response
Het proces van reageren op een cyberincident: detecteren, indammen, herstellen, leren. DORA eist incident response playbooks en regelmatige tests.

**Timeline DORA incident reporting:**
- 4 uur: Eerste notificatie aan DNB (major incident)
- 24-72 uur: Tussenrapportage met impact assessment
- 1 maand: Final report met root cause en remediation

### BCP (Business Continuity Plan)
Plan om de business draaiende te houden bij grote verstoringen (cyberaanval, brand, overstroming). Bevat procedures, contactpersonen, escalatie.

### DRP (Disaster Recovery Plan)
Technisch plan om IT-systemen te herstellen na een calamiteit. Definieert RTO en RPO.

### RTO (Recovery Time Objective)
Maximale acceptabele downtime. Bijv. RTO 4 uur = systeem moet binnen 4 uur weer werken.

### RPO (Recovery Point Objective)
Maximaal acceptabel dataverlies. Bijv. RPO 1 uur = max 1 uur aan transacties mag verloren gaan (dus: backups elk uur).

---

## 7. KLIMAAT & DUURZAAMHEID

### Klimaatrisico's
Fysieke risico's (overstromingen, stormen, droogte, hittegolven) en transitierisico's (verschuiving naar groene economie) die impact hebben op verzekeraars.

**Status 2025:** Klimaat #5 wereldwijd (Allianz Risk Barometer), hoogste positie ooit. Voor het 5e jaar >$100B insured losses wereldwijd.

**Nederland specifiek:**
- €100B+ schade bij dijkdoorbraak Randstad
- 75% klimaatschade onverzekerd (€450B protection gap EU)
- 30-40% premiestijging klimaatgevoelige gebieden laatste 5 jaar

### Climate Data Hub
Systeem dat real-time klimaatdata integreert (KNMI, NASA, ESA satellieten) en koppelt aan verzekeringsportefeuilles. Scenario analyses (1,5°C / 2°C / 3°C / 4°C warming), geospatial risk mapping (postcode-level overstromingsrisico).

### Net-zero targets
Doelstellingen om netto-nul CO2-uitstoot te bereiken. Verzekeraars committeren zich vaak aan 2040-2050 targets voor hun beleggingsportefeuilles en operaties.

### Green bonds
Obligaties waarvan de opbrengst gebruikt wordt voor groene projecten (windenergie, zonnepanelen, energiebesparing). Onder Solvency II Review krijgen deze 20-30% lagere kapitaaleis, wat €10-30B groene deals stimuleert sectorbreed.

### Parametrische verzekering
Verzekering die automatisch uitkeert bij objectieve trigger (bijv. >50mm regen in 24u, windsnelheid >100 km/u). Geen schade-expertise nodig, snelle uitkering.

---

## 8. DATA & ANALYTICS

### Data governance
Het raamwerk van regels, rollen en processen voor het beheren van data: wie is eigenaar, wie mag toegang, hoe is kwaliteit geborgd, hoe lang bewaren.

### MDM (Master Data Management)
Systeem om "golden record" te creëren van belangrijke data (klanten, producten, polissen). Zorgt voor één waarheid over hele organisatie.

### Data lineage
Het kunnen traceren waar data vandaan komt, welke transformaties het ondergaat, en waar het eindigt. Cruciaal voor Solvency II Partial Models - DNB eist dat elk datapunt traceerbaar is.

### Data quality
Meting van hoe goed data is: compleetheid, accuraatheid, consistentie, tijdigheid. Slechte datakwaliteit = "garbage in, garbage out" bij AI en risico modellen.

### Predictive modelling
Gebruik van statistiek en machine learning om toekomstige uitkomsten te voorspellen. Bijv. schadefrequentie, klantenverloop (churn), fraude.

### Data lake / Data warehouse
Centrale opslag van grote hoeveelheden data. Data lake = ruw formaat, data warehouse = gestructureerd en geoptimaliseerd voor analyse.

---

## 9. PROJECTMANAGEMENT & CHANGE

### Agile
Wendbare werkwijze met korte sprints (2-4 weken), frequente oplevering, nauwe samenwerking met stakeholders. Tegenovergestelde van waterfall (alles vooraf specificeren).

### Scrum
Populaire agile framework. Rollen: product owner, scrum master, development team. Ceremonies: sprint planning, daily stand-up, sprint review, retrospective.

### Change management
Het begeleiden van organisaties en mensen door veranderingen. Belangrijk bij IT-transformaties, fusies, nieuwe regelgeving. Weerstand aanpakken, training, communicatie.

### Center of Excellence (CoE)
Centraal expertteam dat standaarden, best practices en governance verzorgt voor een specifiek domein. Bijv. RPA CoE, AI CoE, Data CoE.

---

## 10. AANVULLENDE TERMEN (uit Sela's analyse)

### Vendor risk / Third-party risk
Risico's die voortvloeien uit afhankelijkheid van externe leveranciers. DORA maakt dit zeer actueel - cloud providers, SaaS-platforms, herverzekeraars moeten allemaal geaudit worden.

### Embedded insurance
Verzekering geïntegreerd in een ander product of dienst. Bijv. reisverzekering bij vliegticket boeken, apparatuurverzekering bij smartphone kopen, autoverzekering bij lease contract.

### Adverse media screening
Automatisch monitoren van negatief nieuws over klanten in media. Bijv. "Jan Jansen arrested for fraud" triggert KYC review.

### False positives
Alerts die onterecht afgaan. Bij KYC: 60-80% van sanctie-matches zijn false positives (bijv. "Mohamed Ali" match met "Muhammad Alii" op sanctielijst, maar niet dezelfde persoon). Frustreert compliance teams.

### Combined ratio
Schadelast + kosten gedeeld door premie-inkomsten. <100% = winst, >100% = verlies. McKinsey: Commercial P&C behaalde 91% combined ratio (2023) - gezonde marge.

### CAT exposure (Catastrophe exposure)
Blootstelling aan grote catastrofes (aardbevingen, overstromingen, stormen). Vereist herverzekering en scenario-modellering.

### Herverzekering / Reinsurance
Verzekering voor verzekeraars. Grote risico's worden gedeeltelijk "doorverkocht" aan herverzekeraars om eigen risico te beperken.

---

## 11. AFKORTINGEN REFERENTIE

**Toezicht & Regelgeving:**
- DNB: De Nederlandsche Bank (toezichthouder)
- AFM: Autoriteit Financiële Markten (toezichthouder)
- EBA: European Banking Authority
- EIOPA: European Insurance and Occupational Pensions Authority

**Organisatie:**
- RvB: Raad van Bestuur
- RvC: Raad van Commissarissen
- CFO: Chief Financial Officer
- CRO: Chief Risk Officer
- CIO: Chief Information Officer / Chief Investment Officer
- COO: Chief Operating Officer

**IT & Data:**
- API: Application Programming Interface
- SaaS: Software as a Service
- PaaS: Platform as a Service
- IaaS: Infrastructure as a Service
- ETL: Extract, Transform, Load (data pipelines)
- BI: Business Intelligence

**Projectmanagement:**
- PMO: Project Management Office
- POC: Proof of Concept
- MVP: Minimum Viable Product
- KPI: Key Performance Indicator

---

**Versie:** 1.0  
**Datum:** 23 januari 2026  
**Bron:** ITDS Consultancy Strategic Research 2026-2028  
**Auteur:** Ronald van Wanrooij, CFA  
**Aanvullende bron:** Sela Tilahun Gudeta - Analyse verzekeringen overview (69 slides)

**Deze begrippenlijst ondersteunt:**
- Website ITDS_VOLLEDIG_2025_VERIFIED_AMOUNTS.html
- Executive Summary EXECUTIVE_SUMMARY_COMPACT.md
- Uitgebreide trends UITGEBREIDE_UITLEG_TRENDS_ITDS.md

---

**EINDE BEGRIPPENLIJST**
