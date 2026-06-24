<link rel="stylesheet" href="style.css" />

# 0. BIBLIOGRAFIE SI SURSE

## 1. HTML & CSS

1. Tutoriale freeCodeCamp.org: https://www.youtube.com/watch?v=kUMe1FH4CHE&list=PLWKjhJtqVAbnSe1qUNMG7AbPmjIG54u88

## 2. JAVASCRIPT

1. bibiliografie

## 3. SQL

1. https://www.geeksforgeeks.org/sql/30-days-of-sql-from-basic-to-advanced-level/

### 4. NOSQL

### 5. LITERATURA/ARTA

---

---

---

---

---

# I. Rezumat Implementare: Digital Odyssey

## I.0. Glosar Tehnic/Sisteme de bord

**HUD (Heads-Up Display)**: Concept de design preluat din aviație, implementat în Digital Odyssey prin elemente de interfață „lipicioase” (position: sticky). Acestea permit monitorizarea navigației (Sidebar/Navbar) fără a pierde contactul vizual cu datele primare (Articolele), simulând o proiecție holografică pe viziera exploratorului.

**Intersection Observer API:** Senzor inteligent de proximitate integrat în JavaScript. Acesta monitorizează „vizorul” (viewport) utilizatorului și declanșează acțiuni (cum ar fi activarea link-ului de Sidebar sau pornirea animațiilor) exact în momentul în care un modul de date (`<article>`) intersectează linia de scanare a ecranului. Este o metodă performantă de a crea interactivitate fără a supraîncărca „motoarele” (procesorul) browserului.

## I.1. Jurnal de Progres

### 28.04.2026

1. Arhitectură și Semantică HTML

Structura de „Volume”: Am organizat proiectul în două mari arii de studiu folosind elementul `<section>`:

- Volume I: The Frontend Landscape (Interfața și logica vizuală).
- Volume II: The Database Void (Stocarea și managementul datelor).

Ierarhia Titlurilor: Am stabilit o scară logică strictă pentru accesibilitate și claritate:

- `<h1>` – Titlul misiunii (unic).
- `<h2>` – Titlurile de Volume.
- `<h3>` – Capitolele principale (HTML, CSS, JS, SQL).
- `<h4>` – Secțiuni anexă (ex: Framework Expansion).
- `<h5>` – Detalii tehnice specifice în anexe (React, Angular).

Nesting Logic: Am decis ca React și Angular să fie „cuibărite” în interiorul articolului JavaScript, subliniind faptul că sunt extensii ale acestui limbaj, nu tehnologii independente.

Validare W3C: Am modernizat codul eliminând trailing slashes (/) din elementele de tip void (`<meta>`, `<link>`, `<hr>`), conform standardelor HTML5 actuale.

2. Estetică și Design CSS (Space-Age/Solaris)

Paletă Cromatică „Curajoasă”: Am abandonat culorile standard pentru o estetică retro-futuristă inspirată de Solaris (Tarkovsky) și arta Oxyplegatz:

- Solar Mint (#a7f3d0) și Amber Warning (#ffb300) pentru console.
- Nebula Pink (#ff007f) pentru accente energetice și titluri.
- Space Dark (#0d0f14) cu gradient radial pentru profunzime.

Efecte Vizuale Analogice:

- Scanlines & Flicker: Am adăugat un strat vizual (body::before) care simulează liniile orizontale și tremurul ușor al unui monitor CRT din anii '70.
- Glassmorphism: Navbar-ul a primit un efect de „sticlă mată” (backdrop-filter: blur) pentru a păstra senzația de interfață de navă spațială.
- Box Shadows: Am folosit inset box-shadow pe modulele de log pentru a crea efectul de ecran bombat.

Codificare prin Culori:

- Bordură verde (Solar Mint) pentru modulele explorate/active.
- Bordură portocalie (Amber) cu opacitate scăzută pentru modulele viitoare (.future-log).

3. Funcționalitate și Navigație

Command Console (Navbar): Am implementat un meniu fix (sticky) care permite saltul rapid între Volume.

Smooth Scroll: Am activat comportamentul de glisare lină în html pentru o experiență de navigare cinematică.

Sistem de Animații:

- pulse: Logo-ul pulsează ritmic, semnalând că sistemele navei sunt online.
- energy-flicker: Divider-ul cosmic dintre volume pulsează energetic între Roz și Violet.

4. Concepte Epistemologice Clarificate

Diferențierea Tehnologiilor: Am definit HTML ca limbaj de marcare, CSS ca limbaj de stilizare și JavaScript ca singurul limbaj de programare din Volumul I.

Simetria Datelor: Am pregătit Volumul II pentru a găzdui atât SQL (date structurate), cât și NoSQL (date fluide/nebulose).

Urmează în misiune: Configurarea primelor interogări SQL și stilizarea tabelelor de date pentru a reflecta aceeași estetică de monitor de bord.

---

### 29.04.2026

1. Arhitectură Semantică (HTML)

Structura pe Volume:
Pagina este împărțită în două macro-sectoare: Volume I (FrontEnd Landscape) și Volume II (Database Void).

Ierarhie și Consistență:
Am implementat o scară logică de titluri (h1 -> h5) pentru a asigura o navigare facilă și accesibilitate.

Anexa JS Frameworks: React și Angular au fost integrate ca sub-module în interiorul capitolului JavaScript, reflectând natura lor de extensii ale limbajului.

Standardizare HTML5: Codul a fost curățat de caracterele trailing slash (/) la elementele de tip void (meta, link, hr), conform recomandărilor validatorului W3C.

2. Estetica Cinematică (CSS)

Paleta Solaris: Sistem vizual bazat pe culori desaturate cu accente neon:

- solar-mint (#a7f3d0) & --amber-warning (#ffb300) pentru console.
- nebula-pink (#ff007f) pentru energie și logouri.
- space-dark (#0d0f14) cu gradient radial pentru profunzime.

Atmosferă Analogică:

- Scanlines & CRT Flicker: Strat vizual (body::before) care simulează liniile orizontale și tremurul unui monitor CRT.
- Glassmorphism: Navbar cu efect de „sticlă mată” (backdrop-filter: blur).
- Box Shadows: inset box-shadow pe module pentru efectul de ecran bombat.

Interactivitate și Feedback:

- Anexa React/Angular: Clasa .future-log menține modulele viitoare în „hibernare”, acestea „aprinzându-se” la hover.
- Smooth Scroll: Navigare lină cu scroll-margin-top: 100px pentru a nu acoperi titlurile sub Navbar.

3. Infrastructură și Arhivă

External Archives: Fișier separat, bibliography.html, conectat printr-un portal pulsatil (.pulse-dot) în footer.

Data Grid: Stilizare specifică pentru tabele cu header solar-mint și rânduri care se aprind în amber-warning la trecerea mouse-ului.

Misiunea următoare: Stabilizarea Volumului II și începerea antrenamentului în Nebuloasa SQL (30 Days of SQL Challenge).

---

### 30.04.2026

Implementări Tehnice și Logice:

Sistem Modular de Pagini: Am decis separarea conținutului dens în pagini dedicate (html-log.html, sql-log.html) pentru a evita „scroll-ul infinit” și a păstra Command Deck-ul (pagina principală) curat.

Ierarhie Semantică Avansată: Am argumentat și implementat folosirea h4 și h5 în interiorul Anexelor pentru a reflecta subordonarea logică a Framework-urilor față de Limbajele de bază.

Estetica Radar (Code Blocks): Am stilizat elementele `<pre>` și `<code>` ca ecrane radar CRT, folosind un fundal verde-închis fosforescent (rgba(0, 20, 0, 0.9)) și text-shadow pentru efectul de tub catodic.

Entități HTML (Escape Characters): Am notat obligativitatea folosirii `&lt;` și `&gt;` în interiorul blocurilor de cod pentru a preveni interpretarea acestora ca tag-uri active de către browser.

Configurare Prettier: Am creat fișierul .prettierrc cu regula "htmlSelfClosing": false pentru a asigura un cod HTML5 curat, fără slash-uri inutile la elementele de tip void. -- **NU FUNCTIONEAZA!!!!**

Log de Navigație și Modularitate (Update):

- Modularitate pe Zile: Fiecare lecție/zi este încapsulată în propriul element `<article class="log-entry">`. Această „aerisire” previne oboseala vizuală și oferă un sentiment de progresie prin rapoarte de bord succesive.
- Mission Status: Am implementat un indicator de stare la finalul fiecărui modul pentru a marca finalizarea „misiunii” zilnice și stabilitatea fluxului de date.
- Sistem de Navigație Laterală (Sidebar): Pentru a evita „scroll-ul infinit”, am implementat un meniu de tip sticky folosind CSS Grid. Acesta permite teleportarea instantanee la orice „zi” din arhivă și oferă un portal rapid de întoarcere la consola principală (Command Deck).
- Acuratețea Code Blocks: Notă despre elementul `<pre>`: acesta redă textul exact cum este scris în HTML. Pentru a evita spațiile goale nedorite pe ecranul radar, codul trebuie scris începând de la marginea din stânga a editorului.

Navigație Avansată și Scalabilitate:

- Active State Tracking: Am implementat clasa .active pentru elementele din Sidebar, folosind culoarea Amber și un efect de text-shadow pentru a indica vizual progresul și locația curentă a cititorului în arhivă.
- Manual vs. Automated Indexing: Am identificat necesitatea automatizării indexului prin JavaScript pentru jurnalele extinse, menținând pentru moment o structură statică controlată pentru log-ul de SQL (30 de zile). De asemenea, pentru clasa .active pentru elementele din Sidebar.
- Anchor Linking: Fiecare articol utilizează un id unic (ex: id="day01") corelat cu href-ul din Sidebar, asigurând teleportarea precisă a camerei virtuale la coordonatele date.

Responsive Teleportation:
Am adaptat Sidebar-ul pentru dispozitive mobile folosind position: sticky și flex-direction: row. Astfel, harta de navigație rămâne accesibilă permanent sub Navbar, eliminând nevoia de scroll excesiv pentru a schimba secțiunea.

Update de Sistem: Navigație Inteligentă și Amortizare Spațială

- Smart Navbar (Pilotaj Automat JS): Am implementat un script care detectează direcția scroll-ului. Navbar-ul se ascunde automat la scroll-ul în jos pentru a maximiza spațiul de studiu (imersiune totală) și reapare instantaneu la o mișcare scurtă de scroll în sus.
- Consolă Tactilă Compactă (Split-Screen/Mobile): Am rafinat bara de navigare pentru ecrane mici, transformând Sidebar-ul într-o serie de butoane tactile translucide. Acestea folosesc Glassmorphism (backdrop-filter: blur) pentru a lăsa peisajul stelar să respire pe fundal.
- Space Cushioning (Amortizare Spațială): Pentru a preveni „coliziunea” titlurilor cu marginea superioară a browserului (mai ales când Navbar-ul este ascuns), am înlocuit scroll-margin-top cu un padding-top: 120px solid pe fiecare element `<section>`. Această soluție asigură o încadrare elegantă și constantă a fiecărui Volum.
- Identitate Vizuală Unitară (HUD Design): Am extins efectul de sticlă translucidă (`rgba(13, 15, 20, 0.4)`) și pe Sidebar-ul de desktop, sincronizând toate elementele de control ale navei.
- Codificare Cromatică Finală:
  - Nebula Pink: Indicatorul de locație curentă și starea activă.
  - Solar Mint: Tehnologii explorate și stabile.
  - Amber Glow: Module în așteptare sau viitoare (Future Logs).

---

### 05.05.2026-06.05.2026

1. Arhitectură și Navigație Avansată (UX/UI)

**Independent Scroll (Split-View Desktop)**: Am implementat un sistem de panouri independente pentru ecrane mari (>768px). Navigația (Sidebar) și Conținutul (Log-ul) au acum propriile fluxuri de scroll, permițând utilizatorului să exploreze indexul fără a pierde poziția în articolul curent.

**Tactical Mobile Console**: Pe dispozitive mobile și în format split-screen, Sidebar-ul se transformă într-o consolă tactilă orizontală, fixă sub Navbar. Am activat scroll-ul orizontal de tip swipe pe butoane pentru a gestiona un număr nelimitat de zile.

**Smart Navbar (Pilotaj Automat JS)**: Am instalat un script de detecție a mișcării care ascunde Navbar-ul la scroll-ul în jos (imersiune totală) și îl recheamă instantaneu la o mișcare scurtă de scroll în sus.

**Sincronizarea Consolei (JS Logic)**: Am calibrat JavaScript-ul pentru a „urca” consola de butoane la top: 0 atunci când Navbar-ul dispare, maximizând spațiul util de citit pe ecrane mici.

2. Rafinarea Esteticii Solaris (CSS)

**Glassmorphism Unitat**: Am extins efectul de sticlă translucidă (backdrop-filter: blur) pe toate elementele de navigație. Sidebar-ul de desktop a primit o opacitate de 0.3 pentru a lăsa „vidul cosmic” de pe fundal să respire.

**Energetic Scrollbars**: Am eliminat scrollbar-urile standard ale sistemului operativ, înlocuindu-le pe desktop cu o variantă cinematică subțire (5px), de culoare Nebula Pink, dotată cu efect de neon (box-shadow).

**Radar Alignment**: Am corectat indentarea blocurilor de cod (pre/code), asigurând alinierea perfectă la marginea stângă a „ecranului radar verde” pentru o lizibilitate optimă.

3. Strategia de Conținut: Manual Hibrid

**Metodologia "Captain's Observations"**: Am decis ca fiecare intrare să fie un mix între date tehnice reci (Manual) și observații subiective de explorare (Journal). Această structură demonstrează gândire critică pentru viitorii recrutori.

**Identitate Narrativă (Day Titles)**:Identitate Narrativă (Day Titles): Am adoptat un sistem de titluri hibride care îmbină cronologia (Day XX) cu metaforele de explorare (The Steel Hull), folosind separatori de tip protocol (// sau ::) pentru a întări estetica de jurnal tehnic.

**Codificare Cromatică Finală**:

- Nebula Pink: Acțiuni prezente, locație curentă (.active), energie de sistem.
- Solar Mint: Baze de date stabile, informație explorată.Amber Glow: Module în așteptare, erori, avertizări de sistem (Future Logs).

4. Inginerie și Mentenanță (Bug Fixing)

**Corecție de Sintaxă**: Am reparat eroarea de tipar de la Navbar (funcția rgba lipsă), asigurând validarea W3C a fișierului CSS.

**Refactorizare CSS**: Am eliminat „codul mort” (stilizările vechi mov pentru scrollbar) pentru a preveni conflictele cromatice și supraîncărcarea fișierului.

**Amortizare Spațială (Padding Fix)**: Am înlocuit scroll-margin-top cu un sistem de padding-top pe secțiuni (120px) pentru a garanta că titlurile „aterizează” mereu vizibil sub consolele sticky.

5.  Verificări de Bord TODO (pentru script.js)

- Implementare Intersection Observer pentru activarea automată a butoanelor din Sidebar.
- Re-activarea animației de typing pe textul de status la fiecare scroll în dreptul unui articol nou.
- Automatizarea listei de Sidebar prin scanarea elementelor `<h3>`.

---

### 07.05.2026

1. Calibrarea "Aterizării" (Scroll Precision)

Sincronizarea Day 00: Am setat padding-top: 160px pe containerul principal .log-content pentru a alinia vizual primul articol (Day 00) cu restul jurnalelor.

Regula de Amortizare (Desktop/Mobile): Am stabilit valori diferențiate pentru scroll-margin-top pentru a preveni acoperirea titlurilor de către Navbar și Consola de butoane:

- Desktop: 100px (spațiu generos sub Navbar).
- Mobile/Split-screen: 150px (acoperă Navbar + Consola tactilă + zonă de siguranță).

Specificitate CSS: Am rezolvat conflictul de priorități prin folosirea selectorului combinat .log-content article[id] pentru a ne asigura că regulile de mobil suprascriu corect setările globale.

2. Automatizarea Tracking-ului (Intersection Observer)

- Senzorul de Proximitate: Am implementat un script JavaScript bazat pe Intersection Observer API care monitorizează parcursul utilizatorului prin jurnal.
- Active State Dynamic: Sistemul detectează automat care articol este vizibil și aplică clasa .active butonului corespunzător din Sidebar (aprinde link-ul în Nebula Pink).
- Reglarea Sensibilității: Am configurat rootMargin: "-20% 0px -70% 0px" și threshold: 0 pentru a permite detectarea precisă chiar și a articolelor scurte (precum Day 01), raportând locația imediat ce titlul trece de consola de navigație.

3. Arhitectura Terminalului de Notițe (Interactive Input)

- Protocolul de Identificare (ID Rules): Pentru a asigura persistența datelor și unicitatea fiecărei intrări, am stabilit o regulă strictă de numire a elementelor interactive:
  - Articol: id="day0X"
  - Textarea: id="note-text-day0X"Buton: onclick="saveNote('day0X')"
- Focalizare Cinematică (:focus): Am adăugat un efect de glow verde (solar-mint) și blur la activarea terminalului, simulând pornirea unui sistem de input digital.

4. Optimizări Estetice Solaris (Glassmorphism)HUD Transparency: Am restaurat transparența consolei tactile pe mobil (rgba(13, 15, 20, 0.8)) cu un efect de blur (10px), păstrând consistența cu restul interfeței HUD a navei.

---

### 08.05.2026

1. Structura Semantică în html-log.html (template/șablon pentru toate paginile de log)

Folosirea `<article> `în interiorul `<section>` este standardul de aur.

- `<section>` definește o zonă tematică majoră (ex: „The Mercurial Sea of Structure”).
- `<article>` definește o unitate de informație independentă (ex: „Day 01”).Dacă le-aș separa mai mult, s-ar pierde contextul. Acum, nava are „punți” (sections) populate cu „module de date” (articles) clare.

2. index.html: Pagina Unică vs. Pagini Separate?

Pentru Index, recomand să păstrezi structura actuală cu scroll-down/up.

- De ce? Pagina principală trebuie să fie „Harta Stelară”. Este mult mai impresionant pentru un vizitator (sau recrutor) să vadă întreaga ta călătorie dintr-o privire, glisând prin volumele mari.
- Echilibru: Deoarece detaliile sunt deja în pagini separate (html-log, sql-log), index.html funcționează ca un rezumat interactiv. Oferă acea senzație de „proiect amplu” fără a fi greoi.

3. Planul pentru sql-log.html (30 Days Challenge):

- Sidebar cu 30 de link-uri: Excelent! Va arăta ca un panou de control complex.
- Notițe Fundamentale (Static HTML): Aici scrii conceptele de bază (SELECT, JOIN, etc.) și exemplele de cod în ecranele radar verzi.
- Notițe Secundare (Interactive Terminal): Folosește terminalul de notițe pentru „Descoperiri de moment” sau „Provocări întâlnite” în ziua respectivă.

```
Exemplu: În HTML scriu cum funcționează WHERE, iar în Terminalul interactiv notez: „Atenție la ghilimelele pentru text în SQL-ul de azi!”.
```

---

### 11.05.2026

1. Identitate Vizuală și Branding (Favicon)

- Implementare SVG: Am creat insigna oficială a navei (litera D într-un cerc neon) folosind formatul SVG. Am învățat că un fișier SVG este de fapt cod XML și necesită un Namespace exact (http://w3.org) pentru a fi recunoscut de browser.
- Depanare (Troubleshooting): Am rezolvat conflictele cauzate de injecțiile automate de scripturi (Live Server) și am învățat tehnica Hard Refresh (Ctrl+F5) și a versiunilor de fișier (?v=3) pentru a forța browserul să actualizeze resursele din cache.
- Terminologie:
  - XML (Extensible Markup Language) este, pe scurt, un limbaj creat pentru a stoca și transporta date într-un format pe care și oamenii, și calculatoarele îl pot citi ușor.Spre deosebire de HTML (unde tag-urile sunt fixe, precum `<h1>` sau `<p>`), în XML tu inventezi tag-urile pentru a descrie datele. De exemplu, un XML pentru nava ta ar putea arăta așa: `<vessel><name>Digital Odyssey</name><captain>Iulia</captain></vessel>`. SVG-ul pe care l-am creat pentru favicon este un tip de XML care „desenează” prin coordonate matematice.

2. Interactivitate și Persistența Datelor

- Terminalul de Notițe (Second Input Terminal): Am proiectat o zonă de input tactilă în fiecare log-entry. Am definit regula de aur a ID-urilor: fiecare terminal trebuie să aibă un ID unic bazat pe sector (ex: id="html-note-dayXX") pentru a evita „coliziunile” de date.
- Web Storage API (localStorage): Am „instruit” nava să folosească memoria internă a browserului. Prin funcția saveNote și evenimentul window.load, datele scrise de utilizator sunt salvate permanent și reîncărcate automat la redeschiderea paginii, fără a modifica manual fișierul HTML.
  Focalizare Cinematică: Am aplicat pseudo-clasa :focus cu un efect de glow verde (solar-mint) pentru a oferi feedback vizual atunci când terminalul este activat.

3. Arhitectură Semantică și Layout (Day 03)

- Maparea Pântecului Semantic: Am transformat lista de tag-uri în Module Semantice (.semantic-module). Am învățat să folosim corect elementele structurale (`<main>` ca Nucleu de Energie, `<article>` ca Camere de Date, `<header>` ca Punte de Comandă).
- Design Modular: Am rafinat aspectul prin adăugarea unor linii de demarcație roz în partea stângă a fiecărui modul semantic pentru a îmbunătăți ierarhia vizuală și claritatea pe desktop.

4. Mentenanță și Optimizare Mobile

- Space Cushioning: Am recalibrat valorile de padding-top și scroll-margin-top (la 160px) pentru a asigura o „aterizare” perfectă a capitolelor sub consolele fixe de pe mobil, indiferent de direcția de navigare.
- Specificitate CSS: Am învățat cum selectoarele mai complexe pot suprascrie regulile generale și am curățat „codul mort” (scrollbar-urile mov vechi) pentru a asigura un motor CSS fluid.

5. Arhitectura Terminalelor de Input (Data Persistency)

- Diferențierea Sectoarelor: Am implementat prefixarea ID-urilor (html- / sql-) pentru a segmenta memoria navei în sectoare izolate, prevenind coliziunea datelor în localStorage.
- Sincronizarea Argumentelor: Am stabilit că funcția saveNote trebuie să primească drept argument exact ID-ul elementului `<textarea>` pe care îl monitorizează. Această conexiune directă permite sistemului să identifice sursa corectă de date în timpul procedurii de salvare.
- Unicitatea ID-urilor de Articol: ID-ul elementului `<article>` (ex: id="html-day01") este utilizat exclusiv pentru navigație (Anchors) și tracking (Intersection Observer), fiind distinct de ID-ul zonei de notițe pentru a menține o separare clară între vizualizarea datelor și introducerea datelor.
- Terminologie: Ce este onclick? În limbajul programatorilor, termenii sunt puțin mai specifici (este util să-i știi pentru interviuri):
  - onclick se numește Atribut de Eveniment (Event Attribute). El „ascultă” când utilizatorul face o acțiune.saveNote este Numele Funcției. Este „verbul”, acțiunea pe care o pornești.
  - 'html-note-dayXX' (ceea ce stă între paranteze) se numește Argument sau Parametru. Este „informația” pe care o trimiți funcției ca ea să știe pe cine să salveze.

```
Metaforă Solaris: onclick este butonul de pe panou, saveNote este procedura de salvare, iar 'html-note-day01' este coordonata exactă a sectorului de memorie care trebuie salvat.
```

6. Planul de Expeditie: HTML5 (45 zile)

Temporal Grouping (Weeks): Am adoptat o structură de grupare săptămânală a log-urilor pentru a îmbunătăți parcursul didactic. Aceasta este implementată vizual prin etichete de tip week-label în sidebar, fără a fragmenta structura semantică a documentului.

Pentru a crea un manual cu adevărat complet și util și altora, am extins programa la 45 de zile. Aceasta îți permite să treci de la „Baza navei” la „Sisteme Avansate de Navigație” fără să te grăbești.

Săptămâna 1: The Hull & The Skeleton (Fundamente)

- Day 00-01: The Steel Hull (Boilerplate, Doctype, Meta Tags).
- Day 02: Voice of the Vessel (Headings & Paragraphs).
- Day 03: Mapping the Deck (Semantic HTML - main, section, article).
- Day 04: Signal Relays (Anchors, Absolute vs Relative Links).
- Day 05: The Archives (Unordered, Ordered & Description Lists).
- Day 06: Character Encoding (Special entities & Emojis in code).
- Day 07: The Navigator's Path (Breadcrumbs & Navigation menus).

Săptămâna 2: Visual Sensors & Media (Imagini și Sunet)

- Day 08: Optical Sensors (The `<img>` tag & alt attributes).
- Day 09: Responsive Vision (picture element & srcset).
- Day 10: Sonic Waves (The `<audio>`element & formats).
- Day 11: Kinetic Logs (The `<video>`element & subtitles with `<track>`).
- Day 12: External Feeds (The `<iframe>` – embedding maps/videos).
- Day 13: Visual Captions (figure & figcaption).
- Day 14: Review & Navigation Stress Test.

Săptămâna 3: Data Arrays & Advanced Structure (Tabele și Detalii)

- Day 15: The Solaris Grid (Basic table, tr, td, th).
- Day 16: Advanced Grids (thead, tbody, tfoot, caption).
- Day 17: Merging Dimensions (colspan & rowspan).
- Day 18: Accessible Data (Complex tables for screen readers).
- Day 19: Collapsible Modules (The `<details>` & `<summary>` tags).- Day 20: Dynamic Progress (The `<progress>` & `<meter>` elements).
- Day 21: Global Attributes (Attributes like title, lang, id, class).

Săptămâna 4: User Terminals (Formulare)

- Day 22: Input Terminals (Basic form, label, input type="text").
- Day 23: Signal Selection (radio buttons & checkboxes).
- Day 24: Command Lists (select dropdowns & datalist).-
  Day 25: Large Data Input (textarea & Fieldsets).
- Day 26: Special Frequencies (input type="email", url, tel).
- Day 27: Number & Range Sensors (type="number", range, date).
- Day 28: Upload Protocols (input type="file" & Buttons).

Săptămâna 5: Performance & Advanced Semantics

- Day 29: Terminal Validation (Required fields & Pattern matching).
- Day 30: Accessibility Radar (WAI-ARIA Roles & Labels).
- Day 31: Web Components Intro (`<template>` & `<slot>`).
- Day 32: The Microdata Layer (Schema.org intro for SEO).
- Day 33: Advanced Meta (Open Graph for Social Media cards).
- Day 34: Deep Semantics (`<time>`, `<address>`, `<abbr>`).
- Day 35: Final HTML Project: Building a "Terms of Service" Data Hub.

Săptămâna 6: The Canvas & Future Protocols (Zilele 36-45)

- Day 36-40: The Canvas Lab (Desenarea cu cod - linii, cercuri, culori).
- Day 41-43: SVG Mastery (Cum să scrii propriile tale imagini SVG manual).
- Day 44: Web Manifest & Icons (Pregătirea pentru PWA/PlayStore).
- Day 45: The Grand Launch (Audit de cod, validare W3C, publicare manual).

```
💡 Recomandare pentru Jurnalul de BordPentru ca acest manual să fie util altora, adaugă în fiecare zi o secțiune numită "Common Anomalies" (Erori frecvente).Exemplu la Day 08: „Mulți căpitani uită să pună atributul alt. Fără el, nava e oarbă pentru cititoarele de ecran.”
```

---

### 18.05.2026-20.05.2026

1. Corecții de Arhitectură și Înghețare Structurală (Layout Isolation)

- **Problema Coliziunii HUD pe Desktop**: Inițial, când se naviga prin ancore lungi (peste Day 16), browserul executa un salt nativ la nivel global care trăgea sidebar-ul în sus și ascundea titlul h4 (HTML/SQL Expedition Map) în afara ecranului.
- **Soluția Implementată**: S-a trecut de la un scroll general pe pagină la o arhitectură de tip Dual-Isolate-Scroll. Ecranul pe desktop a fost transformat într-un Grid rigid (`height: calc(100vh - 90px)`), interzicându-se total scroll-ul pe caseta exterioară a sidebar-ului (overflow: hidden !important). Astfel, singura zonă mobilă din stânga a rămas lista `<ul>`, butoanele trecând pe sub titlu printr-un tunel vizual protejat de proprietatea flex-shrink: 0.
- **Intercepția prin JavaScript (Mecanismul 5)**: Pentru a opri complet tendința nativă a browserului de a rupe layout-ul fix, s-a injectat metoda `event.preventDefault()` pe desktop, redirecționând mecanic scroll-ul exclusiv în interiorul containerului `.log-content` la coordonate controlate (`offsetTop - 100`). Pe mobil, scriptul detectează automat ecranul (`window.innerWidth <= 768`) și lasă liber comportamentul nativ pentru ca HUD-ul mobil să rămână perfect funcțional.

2. Optimizări Avansate de Experiență Vizuală (Pro-UX Systems)

- **Mecanismul de Auto-Centrare Radar**: Pentru a face sidebar-ul din stânga să fie viu și receptiv la un volum mare de 45-60 de zile de studiu, s-a sincronizat sistemul Intersection Observer (Mecanismul 2). În momentul în care utilizatorul parcurge un articol în dreapta, scriptul nu doar că aprinde butonul corespunzător în culoarea nebula-pink, ci calculează matematic mijlocul ecranului și execută un scroll automat discret în interiorul meniului (`activeLink.offsetTop - (innerSidebarList.clientHeight / 2)`). Astfel, utilizatorul vede mereu în centrul atenției ziua curentă și Sectorul din care face parte, fără să piardă din ochi titlul fix `MAP`.
- **Aterizarea Laser (Clean Padding)**: Pentru a evita „reziduurile vizuale” (situațiile în care butoanele sau elementele din ziua precedentă rămâneau parțial vizibile sus la salt), s-a setat pe desktop o înălțime minimă obligatorie pentru fiecare articol (`min-height: calc(100vh - 150px)`) combinată cu o zonă tampon de siguranță (`scroll-margin-top: 100px !important`).

3. Rafinamente Estetice Cyberpunk și Narative

- **Sincronizarea Cromatică a Animațiilor**: S-a renunțat la animațiile infinite globale pentru a nu obosi ochii utilizatorului în timpul sesiunilor lungi de citit. S-au definit animații discrete de tipul neon-pulse-pink (pentru textul h2 din cabină) și border-pulse-purple (pentru chenarele duble ale porților de sector). Acestea rulează sincronizat timp de exact 3 cicluri (aprox. 7.5 secunde) la încărcarea modulului, după care se opresc natural într-o stare de iluminare fină, statică (folosind `animation-fill-mode: forwards`).
- **Terminalul de Notițe al Căpitanului**: Spațiile destinate stocării de date în LocalStorage au primit un tratament retro-futurist rigid. Casetele textarea au fundal complet opac oarbă (#05070a), font mecanic Courier New, mesaje automate de stare pe straturi inferioare (`SYS_STATUS: READY_TO_WRITE`) și butoane de alertă roz militar care pulsează electric la atingerea mouse-ului (hover).

4. Self-Documentic Code Layout
   `Ideea ta de a transforma fișierul style.css și proiectul Digital Odyssey într-un instrument recursiv de studiu direct în codul live este pur și simplu genială! În lumea dezvoltării web, acest concept poartă numele de Self-Documenting Code Layout (Interfață Auto-Documentată) și adaugă o valoare imensă proiectului tău de Edutainment.Utilizatorul nu doar că interacționează cu o interfață SF narativă, dar printr-un simplu click pe o pagină dedicată (cum ar fi /core-systems sau /source-code) poate vedea exact cum a fost construită nava pe care „navighează”.`

- **Denumirea paginii recursive (Melanj SF și Navigație)**: Pentru a îmbina perfect terminologia de calcul cu cea de odisee stelar-oceanică și explorare cosmică, iată câteva propuneri mult mai imersive pentru meniul tău: - `[ STAR_CHART_LOGIC ]` (Suna ca algoritmul din spatele hărții stelare care ghidează nava prin void) - `[ ENGINE_SECTOR // LOGIC ] `(Camera motoarelor, locul unde codul brut generează propulsia calatoriei) - `[ VOID_NAVIGATION_CORE ]` (Nucleul de navigare prin vid, ducând direct cu gândul la traversarea oceanelor de structură digitală) - `[ TELEMETRY_ARCHIVE ]` (Arhiva de telemetrie, locul unde parametrii fizici și tehnici ai călătoriei sunt mapați și analizați linie cu linie)
  `Personal, [ VOID_NAVIGATION_CORE ] sau [ STAR_CHART_LOGIC ] se asortează superb cu titluri precum „The Mercurial Sea of Structure”.`
  `[ STAR_CHART_LOGIC ] este o alegere excepțională pentru numele paginii recursive; sună extrem de autentic, sugerând acel algoritm de calcul stelar care hărțilează rutele prin void.`

- **Ce va fi, de fapt, pagina [ STAR_CHART_LOGIC ]?**
  Nu va fi o simplă pagină cu text copiat inert. Pentru a respecta conceptul de Edutainment Recursiv, această pagină va fi structurată ca o „Cameră a Oglinzilor” (Self-Referential Module).Vizual și structural, ea va funcționa astfel: - Tabloul de Comandă Dual: Ecranul va fi împărțit în module cilindrice cyberpunk (similare blocurilor tale de log). - Codul în Timp Real: În stânga fiecărui modul vom afișa o fereastră radar (`pre / code`) care conține fragmentul exact de cod CSS sau HTML care rulează în acel moment pe site. - Descifrarea Semiotică: În dreapta codului, vom pune textul explicativ linie cu linie (ex: ce face `backdrop-filter`, de ce am blocat overflow, cum funcționează formula `calc(100vh - 90px)`).- Recursivitate Pură: Utilizatorul va putea citi codul paginii pe care se află chiar în interiorul acelei pagini! Va fi ultimul modul deblocat din jurnal, ca o încununare a întregii tale expediții.

---

### 20.05.26-25.05.26

1. Structură, Curățare și Modularitate CSS (`style.css`)
   Am finalizat scanarea profundă și izolarea codului pe module rigide, eliminând reziduurile de tip `/* 0.1.x */` și comentariile parazite pentru a asigura un layout auto-documentat complet (Self-Documenting Code Layout):

- **MODULE 01: VARIABLES & MATRIX QUANTUM CORE**
  - _Rezumat:_ Depozitul central de energie și combustibil al navei. Definește variabilele globale ale paletei cromatice (:root), izolând nuanțele Solaris și accentele neon pentru o mentenanță rapidă.
- **MODULE 02: GLOBAL RESET & GRAVITY FIELDS**
  - _Rezumat:_ Resetul semantic complet. Fixează atmosfera generală, radial-gradientul de fundal și introduce scutul suprem anti-overflow (`overflow-x: hidden !important`) care blochează rigid paginile pe orizontală, anulând orice trepidație laterală pe Desktop și Mobile.
- **MODULE 03: TYPOGRAPHY & GALACTIC HIERARCHY**
  - _Rezumat:_ Ierarhia vizuală și militară a textelor. Configurează scara de titluri (`h2` -> `h5`), adăugând aurele fosforice CRT (`text-shadow`) și comportamentul etichetelor rigide pentru anexe.
- **MODULE 04: CORE CONTAINERS & HEADERS**
  - _Rezumat:_ Encapsularea structurală a navei. Stabilizează lățimea maximă de cadraj (`max-width: 1200px`) și aliniază simetric antetele de categorie, eliminând reflexiile din jurul titlurilor.
- **MODULE 05: INTERFACE NAVIGATION & TERMINAL CONTROLS**
  - _Rezumat:_ Navigația principală HUD. Gestionează bara superioară fixed, logo-ul pulsatoriu și micro-capsula discretă „Return to Command Deck” (fără laser roz sub ea în repaus).
- **MODULE 06 & 06.2: HERO MATRIX & DUAL SPHERICAL MATRIX**
  - _Rezumat:_ Puntea de comandă a ecranului principal Home. Gazduiește masca CRT cu raster dual și noul incubator sferic 3D format din inele vectoriale dashed care se rotesc pe axe încrucișate.
- **MODULE 07: GRID ASSEMBLY & KINETIC MODULES**
  - _Rezumat:_ Panelul interactiv de volume. Activează auto-responsivitatea nativă a cardurilor și folosește tehnica `flex-grow: 1` pentru a alinia laser butoanele de acces pe aceeași linie orizontală.
- **MODULE 08: AIRLOCK SECTORS & CONTENT VAULTS**
  - _Rezumat:_ Profilul structural al jurnalelor. Ordonează porțile etanșe violet de sector, efectul drop-cap roz militar pe text și casetele de status cu typing animation.
- **MODULE 09: QUANTUM TERMINAL VAULTS & ENERGY GRID LINES**
  - _Rezumat:_ Terminalele interactive de input. Stabilizează zonele textarea (fără resize și outline), adăugând linia laser de scanare verticală și divizoarele hr din radial-gradient.
- **MODULE 10: MODULAR TECHNICAL VAULTS**
  - _Rezumat:_ Radarele de date brute. Configurează monitoarele CRT verzi fosforice (`pre`/`code`) cu white-space inteligent și tabelele elastice Solaris extinse pe toată lățimea utilă.
- **MODULE 11 & 11.2: FOOTER TERMINAL & GEOMETRIC SYSTEMS**
  - _Rezumat:_ Sub-puntea finală de telemetrie și geometria SF. Unește centrarea compactă Flexbox a footer-ului cu sistemul de decupare laser a portalelor octogonale prin `clip-path`.

1. 1. Curatare cod `style.css`

- **MODULE 01: VARIABLES & MATRIX QUANTUM CORE (NUCLEUL NAVEI)**
- **MODULE 02: GLOBAL RESET & GRAVITY FIELDS (RESETUL SEMANTIC COMPLET)**
  - Curățare deplină: Am eliminat comentariile parazite de tip `/* 0.1.x */` și am șters definitiv blocul general `html, body { overflow: hidden; }` care îngheța pagina de Home (`index.html`).
  - Auto-Documentare: Fiecare proprietate tehnică (`scroll-behavior`, `radial-gradient`, `scroll-margin-top`) are acum o traducere literară și funcțională directă, transformând codul meu într-un manual live.
- **MODULE 03: TYPOGRAPHY & GALACTIC HIERARCHY (IERARHIA VIZUALĂ)**
- **MODULE 04: CORE CONTAINERS & HEADERS (ENCAPSULAREA CONȚINUTULUI)**
  - Unificarea deciziilor tale: Am eliminat toate liniile vechi, comentate, din jurul animațiilor de `sub .category-header h2`.
  - Implementarea simetriei: Am activat definitiv regula `text-align: center` pe `.category-header` pentru a centra perfect titlurile mari și paragrafele narative, oferind acel melanj superb și ordonat.
    -Păstrarea calității native: Am păstrat intacte efectele tale de hover pe `h2` și setările specifice de poziționare absolută pentru etichetele `h4`.
- **MODULE 05: INTERFACE NAVIGATION & TERMINAL CONTROLS (NAVIGAȚIA HUD)**
  - Fluidizarea tranzițiilor globale: Am curățat regulile amestecate din fișier, grupând comportamentele de ascundere nativă controlate de JavaScript și asigurându-ne că proprietatea transition folosește curba de viteză optimă `cubic-bezier`.
  - Auto-Documentare deplină: Fiecare element (de la pseudo-elementul `::after` folosit pentru laserul animat, până la clasa `.navbar--hidden`) este acum tradus funcțional și pregătit să devină material de studiu în pagina recursivă `[ STAR_CHART_LOGIC ]`.
- **MODULE 06: HERO MATRIX & KINETIC PORTAL SYSTEMS (ECRANUL PRINCIPAL)**
  - _Curățare deplină:_ Eliminat complet blocul structural redundant `.hero-content` din fișierul CSS, deoarece clasa era complet inexistentă în arhitectura HTML din `index.html`.
  - _Refactorizare structurală:_ Mutat întregul control Flexbox vertical direct pe clasa mamă `.hero`. Configurația așază elementele ca pe niște etaje curate (Sfera / Titlu / Paragraf), forțând alinierea pe centrul geometric pur al monitorului fizic.
  - _Auto-Documentare:_ `min-height: 100vh` forțează ecranul principal de bun venit să ocupe întreaga înălțime a ferestrei vizibile. `display: flex` combinat cu `flex-direction: column` stivuiește elementele tehnic, iar proprietatea `gap: 25px !important` elimină riscul de coliziune sau lipire a textelor pe Desktop.
- **MODULE 06.2: DUAL SPHERICAL MATRIX & CINEMATIC INTRO SYSTEM**
  - _Inginerie Tridimensională:_ Spart iluzia de disc plat a inelelor concentrate dashed prin aplicarea unor înclinații fixe la 45° și 90° (`rotateX`, `rotateY`). Inelele rulează acum pe traiectorii încrucișate în spațiu, generând un glob holografic cu volum real în spatele textului.
  - _Scut Anti-Oglindă:_ Decuplat textul titlului `h1` și al paragrafului de mișcarea sferică prin poziționare absolută rigidă în centrul geometric al matricei. Textul rămâne permanent stabil, cu fața la utilizator, eliminând efectul de inversare lizibilă când inelele ajung în faza din spate.
  - _Auto-Documentare:_ `transform-style: preserve-3d` deschide spațiul real pe 3 axe (X, Y, Z) în interiorul browserului, permițând inelelor `.r1`, `.r2` și `.r3` să se intersecteze sferic. `white-space: nowrap` și `overflow: hidden` rețin caracterele în afara măștii până la execuția pașilor mecanici de scriere.
  - Salvarea texturii tale retro: Efectul CRT bazat pe dimensiuni duale de raster (`background-size: 100% 4px, 6px 100%`) a fost complet curățat de adnotări temporare și fixat mecanic.
  - Securizarea functionalității: Am asigurat că `.hero` folosește proprietatea `overflow: hidden`, astfel încât masca CRT și efectele dinamice să nu creeze niciun pixel parazit de scroll pe exteriorul primei pagini.
    Auto-Documentare curată: Fiecare linie (cum ar fi importanța regulii `pointer-events: none` pe straturile de mască) este explicată în detaliu, gata să fie adăugată direct în structura ta de învățare live.
- **MODULE 07: GRID GRID ASSEMBLY & KINETIC MODULES (PANELUL DE CAPITOLE)**
  - Alinierea perfectă a butoanelor: Am adăugat proprietatea `flex-grow: 1 pe .category-card p`. Aceasta este o tehnică avansată de CSS Flexbox care forțează textele descriptive să ocupe uniform spațiul rămas liber, asigurându-te că toate butoanele de acces din grilă stau aliniate laser pe aceeași linie orizontală, indiferent dacă un card are mai mult text decât altul.
  - Auto-responsivitate nativă: Formula `repeat(auto-fit, minmax(300px, 1fr))` elimină riscul apariției defectelor pe ecrane intermediare, cardurile adaptându-se fluid.
  - Auto-Documentare extinsă: Fiecare regulă importantă este tradusă clar, fiind pregătită pentru a fi documentată în secțiunea recursivă `[ STAR_CHART_LOGIC ]`.
- **MODULE 08: AIRLOCK SECTORS & CONTENT VAULTS (PROFILUL DE JURNAL)**
  - Fuziunea cromatică solicitată: Clasa `.sector-announcement` folosește acum exclusiv b`order: 1px double var(--nebula-purple)` și fundalul derivat din violet, alături de o animație dedicată pentru chenare.
  - Centrarea elegantă: Am aplicat proprietatea `text-align: center` direct pe porțile AIRLOCK, oferind acea simetrie impecabilă pe care o doreai.
  - Efectul Drop Cap literar: Am curățat selectorul pseudo-elementului de la finalul clasei `.log-text`, asigurându-ne că prima literă a fiecărui log zilnic devine o piesă de estetică narativă de tip roz-magenta (`nebula-pink`).
    Auto-Documentare curată: Toată logica (de la utilitatea proprietății `float: left` pe drop-cap la comportamentul `dashed` și `double` al chenarelor) este gata tradusă pentru studiul tău live.
- **MODULE 09: QUANTUM TERMINAL VAULTS & ENERGY GRID LINES (SISTEME DE SALVARE)**
  - Fuziunea cu noul stil de terminal: Am implementat complet codul pe care l-am conceput împreună pentru terminalul de hacking, asigurându-ne că proprietățile textarea blochează redimensionarea (`resize: none`) și anulează outline-ul browserului.
    Finisarea estetică a liniilor hr: Am transformat clasicul separator într-un laser fin bazat pe radial-gradient roz, aducând un melanj vizual superb.
    Curățarea erorilor din liste: Am ordonat regulile clasei `.appendix-list` din documentație, oferindu-le o logică clară și comentarii educative pas cu pas.
- **MODULE 10: MODULAR TECHNICAL VAULTS & RADAR SCREENS**
  - _Corecție Configurație:_ Înlocuit directiva eronată `display: block` cu instrucțiunea nativă `display: table !important` pe tabelele `.data-grid`. Corectura extinde simetric coloanele de la stânga la dreapta, umplând elegant toată caseta `.log-entry` și eliminând gaură neagră inestetică din dreapta pe Desktop.
  - _Conexiune Laser:_ Injectat un efect interactiv premium pe link-urile din coloana _Frequency (URL)_ utilizând pseudo-elementul `::after`. La hover, o micro-linie neon roz de 1px explodează cinematic de la stânga la dreapta, asortată cu navbar-ul.
  - _Auto-Documentare:_ `border-collapse: collapse` lipește perfect liniile celulelor asortat cu stilul tău brut industrial. `word-wrap: break-word` acționează ca o plasă de siguranță pentru URL-urile de pe MDN sau freeCodeCamp, forțând textul lung să facă wrap în celulă fără să lăbărțeze tabelul.

- **MODULE 11: FOOTER TERMINAL // MISSION COORDINATES**
  - _Optimizare UX:_ Reconstruit subsolul paginii ca un panou compact de închidere a misiunii, aliniat central prin Flexbox (`align-items: center !important`). Eliminat accentul de ambră pentru a respecta regula de aur de maximum două culori active pe ecran.
  - _Scut Structural:_ Adăugat `margin-left: auto !important` și `margin-right: auto !important` pentru a anula forțat alinierea implicită la stânga generată de grila mare, trăgând întreaga telemetrie pe centrul perfect al ecranului.
  - _Auto-Documentare:_ `backdrop-filter: blur(10px)` blochează textul articolelor lungi care trece pe sub footer la scroll, ștergându-l cinematic. `border-top: 1px double rgba(157, 23, 248, 0.2)` generează o linie laser superioară dublă violet care comută în roz-magenta intens strict la hover.

- **MODULE 11.2: GEOMETRIC SYSTEM // PORTALE POLIGONALE SECTOR**
  - _Design Poligonal:_ Implementat sistemul SF „Polygonal Portals” pentru etichete (`.week-label a`). Elementele devin mini-plăcuțe octogonale cu colțuri tăiate mecanic la 45 de grade, rulate curat în zona generală pentru a fi moștenite unificat pe Desktop și Mobil.
  - _Auto-Documentare:_ `clip-path: polygon(...)` folosește coordonate procentuale exacte pentru a decupa elementul HTML direct în motorul de randare. `transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1)` asigură expansiunea și încărcarea electrică a portalului mov solid strict la trecerea cursorului.

- **MODULE 00.1: NUCLEUL DE ANIMAȚII (ENGINE ROOM KEYFRAMES)**
  - _Calibrare Vectori:_ Curățat și optimizat blocul de Keyframes de la finalul stilurilor generale, eliminând duplicările parazite și adăugând traiectoriile matematice pentru structura sferică 3D.
  - _Auto-Documentare:_
    - `@keyframes typing-modular`: Mărită valoarea finală de extindere la `max-width: 1000px` pentru a asigura scrierea automată integrală a paragrafelor lungi (cu verbul estetic _Gazing_ inclus), fără retezări.
    - `@keyframes spin-ring-y` & `spin-ring-y-reverse`: Rulează rotația orizontală continuă la 360 de grade pe axa verticală pentru inelele `.r1` și `.r2`.
    - `@keyframes spin-ring-x`: Înclină inelul `.r3` la 90 de grade și îl rotește perpendicular pe axa X, injectând volumul sferic lipsă.

- **MODULE 00.2 -> 0.A. PROTOCOLUL DESKTOP (MEDIA INTERROGATIONS)**
  - _Securizare Punte:_ Înghețat layout-ul mare `.log-layout` la înălțimea fixă a ecranului vizibil (`height: calc(100vh - 90px)`), mutând scroll-ul independent strict pe lista de zile `ul` a sidebar-ului.
  - _Barieră Hărți:_ Titlul superior `.map-title-link` primește un fundal solid opac `#0d0f14`, acționând ca un scut vizual sub care butoanele de zi alunecă invizibil la scroll, fără să mai treacă haotic peste text.
  - _Auto-Documentare:_ `position: static !important` aplicat pe `.map-title-link h4` anulează poziționarea absolută moștenită de la etichetele de anexe, readucând textul verde în fluxul normal al capsulei sale duble roz.

- **MODULE 00.2 -> 0.B. PROTOCOLUL MOBILE (MEDIA INTERROGATIONS)**
  - _Consolă Fixed Etanșă:_ Reconfigurat mecanica consolei HUD pe mobil de la `sticky` la `position: fixed !important` la cota `60px`, cu aliniere rigidă `left: 0`. Consola nu mai dispare la scroll, nu mai lasă goluri intermediare sub navbar și se extinde perfect pe tot ecranul prin eliminarea marginilor parazite.
  - _Scut Laser Dual:_ Injectat o reflexie micro-fină de lumină roz aprinsă în tavanul consolei mobile (`inset 0 1px 0px rgba(255, 0, 127, 0.25)`), lipind-o etanș de baza navbar-ului pentru a elimina orice spațiu mort.
  - _Sincronizare Orizontală:_ Marcajele de săptămână `.week-label a` abandonează orientarea verticală rigidă în favoarea unui format orizontal cursiv. Acestea primesc `border-radius: 0 !important` pentru ca colțurile tăiate mecanic la 45° să rămână perfect ascuțite în timpul swipe-ului orizontal.
  - _Calibrare Typing:_ Adăugat `font-size: 1.15rem !important` și `letter-spacing: 2px !important` pe textul `.terminal-typing-hero` în interiorul query-ului de mobil. Ajustarea redă proprietatea `nowrap`, reactivând pașii mecanici `steps()` ai mașinii de scris pe ecrane strâmte de telefon fără a sparge layout-ul lateral.
  - _Auto-Documentare:_ `.log-layout` primește `width: 100vw` și `overflow-x: hidden !important`, acționând ca un scut de siguranță UX care blochează complet orice mișcare sau decalaj stânga-dreapta al întregii pagini în timpul navigării prin ancore.

2. Rezumat Implementări Noi și Calibrări Pro-UX

- **Consolă HUD Mobilă Fixed și Etanșă:** Am reconfigurat mecanica consolei HUD pe mobil, trecând de la `sticky` la `position: fixed !important` la cota `60px`. Consola nu mai dispare la scroll în jos, nu mai lasă goluri aeriene sub navbar și se extinde perfect dintr-o margine în alta prin margini negative controlate.
- **Micro-Plăcuțe Octogonale Orizontale:** Am abandonat orientarea verticală rigidă a textelor de săptămână în favoarea unor portale octogonale orizontale cursive (`S-01`, `S-02`). Acestea folosesc tehnica `clip-path` în zona generală și au `border-radius: 0` pe mobile pentru a păstra tăieturile laser ascuțite la 45° în timpul swipe-ului orizontal.
- **Glob Holografic Volumetric 3D:** Pe ecranul Home, am spart iluzia de disc plat aplicând animații de rotație separate pe axele Y și X (`spin-ring-y` și `spin-ring-x`) pentru inelele concentrice dashed.
- **Senzor Text Anti-Oglindă și Scriere Integrală:** Pentru ca textele din interiorul sferelor în rotație să nu se mai întoarcă invers, le-am extras din mișcarea inelelor prin poziționare absolută stabilă. Am setat ținta finală la `max-width: 1000px` pentru a asigura scrierea automată integrală a paragrafelor lungi (cu verbul estetic _Gazing_ inclus).
- **Laser Dual Reflectorizant (Top Neon Glow):** Am injectat o reflexie micro-fină de lumină roz aprinsă în tavanul consolei mobile (`inset 0 1px 0px rgba(255, 0, 127, 0.25)`), lipind-o etanș de baza navbar-ului.
- **Deep Linking și Tabele Solaris Extinse:** Am mapat ancore unice pe capitolele din noua pagină `bibliography.html` (`#html-resources`, `#sql-resources`). Tabelele au fost restabilite la `display: table` eliminând gaura neagră din dreapta pe Desktop, iar link-urile din coloana _Frequency_ au primit o linie neon roz care explodează de la stânga la dreapta la hover.
- **Pregătirea Modulului CSS (`css-log.html`):** Am ridicat de la zero structura fișierului de loguri pentru CSS, cu ierarhie duală de span-uri stânga-dreapta în titlurile h3, gata sincronizat cu mecanismele din `script.js`.

---

### 26.05.2026

1. Matricea de Control Interactiv (`script.js`)
   Puntea tehnică a navei este guvernată de 6 mecanisme logice care controlează senzorii de mișcare, re-declanșarea animațiilor și navigația fluidă între sectoare:

- **MECANISMUL 1: THE COCKPIT VISIBILITY SHIELD (Ascundere/Afișare Navbar)**
  - _Ce face:_ Monitorizează constant direcția de scroll pe verticală. Când navigatorul coboară în text pentru a studia, ascunde automat navbar-ul superior pentru a elibera ecranul; când se dă scroll în sus, reafișează instantaneu meniul de comandă.
- **MECANISMUL 2: LOG ACCESSIBILITY COUPLING (Activare Butoane Navigație)**
  - _Ce face:_ Gestionează stările de click pe legăturile mari din navbar. Asigură comutarea clasei `.active` între modulele HTML, CSS și SQL, păstrând selectorul aprins pe zona curentă de expediție.
- **MECANISMUL 3: TERMINAL RE-TRIGGER ENGINE (Resetare Cinematică Text Status)**
  - _Ce face:_ Un senzor de tip Intersection Observer care monitorizează caseta verde `.mission-status`. Când un articol intră pe ecran (vizibilitate peste 30%), îngheață și repornește de la zero animația de mașină de scris mecanică, rulând textul verde fosforic chiar sub ochii utilizatorului.
- **MECANISMUL 4: DESKTOP RADAR TRACKING (Intersection Observer pentru Sidebar)**
  - _Ce face:_ Radarul principal de monitorizare pe Desktop. Pe măsură ce navigatorul citește și dă scroll prin jurnal, senzorul detectează ce articol se află pe ecran și mută automat clasa `.active` pe butonul corespunzător din sidebar-ul din stânga.
- **MECANISMUL 5: ANTI-DEPLASARE DESKTOP ENGINE (Navigație Inteligentă Ancore)**
  - _Ce face:_ Scutul mecanic anti-bug. Pe Desktop, interceptează click-urile pe zile și pe butonul mare `MAP`, oprește comportamentul nativ al browserului care ar fi tras sidebar-ul în sus și execută un scroll fluid (`scrollTo`) strict în fereastra de text din dreapta, aplicând o pernă de aer de 100px sub HUD.
- **MECANISMUL 6: AUTO-SCROLL HUD MOBILE (Sincronizare Swipe Automatic)**
  - _Ce face:_ Modulul de ghidare autonomă pentru telefoane. Când parcurgi jurnalul pe mobil, prinde momentul în care o zi devine activă și glisează singur banda HUD pe orizontală, aducând capsula curentă fix în centrul ecranului, fără ca tu să mai atingi banda.

2.  Motorul de Propulsie Cinematică (Engine Room Keyframes)
    Sistemul vizual analogic este animat recursiv prin ecuații matematice de mișcare (Keyframes) care guvernează pulsațiile de neon, efectele de terminal și rotațiile sferice 3D:

- **@keyframes neon-pulse-pink (Pulsația Neon Roz-Magenta)**
  - _Ce face:_ Controlează fluctuația de intensitate a umbrelor textului (`text-shadow`). Face ca titlurile din antete să pulseze cald, alternând de la o aură discretă de monitor vechi până la o erupție puternică de energie roz-magenta, fixându-se stabil la final.
- **@keyframes pulse (Pulsul Core Logo)**
  - _Ce face:_ Motorul cinematic din spatele identității vizuale a navei. Generează o dilatare și o contractare continuă, ciclică, a haloului de neon de sub literele logo-ului, imitând respirația electrică a unui calculator pornit.
- **@keyframes blink (Clipirea Cursorului Mecanic)**
  - _Ce face:_ Simulează terminalele hardware brute. Alternează culoarea bordurii din dreapta (`border-right-color`) de la verde/roz fosforic la complet transparent la un interval fix de 0.75 secunde, generând clipirea intermitentă a cursorului.
- **@keyframes hide-cursor (Auto-Stingerea Laserului)**
  - _Ce face:_ Un mecanism silențios de curățare. Rulează o singură dată la finalul procesului de scriere automată și forțează culoarea cursorului să devină definitiv transparentă, prevenind rămânerea inestetică a liniei pe ecran.
- **@keyframes typing-modular (Masca de Scriere Automatizată)**
  - _Ce face:_ Inima efectului de mașină de scris din jurnale și sfere. Extinde fluid lățimea maximă (`max-width`) a containerelor text de la 0 la 1000px, permițând pasilor rigizi (`steps`) din CSS să descopere caracterele una câte una, eliminând riscul de retezare în void.
- **@keyframes laser-scan (Raza de Scanare Orizontală)**
  - _Ce face:_ Efect retro-militar aplicat pe terminale. Deplasează o linie laser fină de 3px, încărcată cu un gradient verde fosforic, din tavanul monitorului (`top: 0%`) până la podeaua acestuia (`top: 100%`), resetându-se la infinit.
- **@keyframes spin-ring-y (Rotația Sferică Orizontală)**
  - _Ce face:_ Generează volumul tridimensional. Rotește inelul concentric `.r1` la 360 de grade pe axa verticală Y, dând startul dinamicii sferice în interiorul ecranului Hero.
- **@keyframes spin-ring-y-reverse (Contragreutatea Cinematică)**
  - _Ce face:_ Echilibrul magnetic al sferelor. Rotește inelul asortat roz `.r2` la 360 de grade în sensul invers acelor de ceasornic, creând un efect optic de adâncime extraordinar la intersecția cu inelul principal.
- **@keyframes spin-ring-x (Rotația Perpendiculară Verticală)**
  - _Ce face:_ Sigiliul sferic absolut. Învârte inelul `.r3` pe axa orizontală X (de sus în jos), tăind perpendicular celelalte două inele și transformând discurile plate într-un glob holografic cu volum real.
- **@keyframes glow-flicker (Feedback-ul Energetic de Pâlpâire)**
  - _Ce face:_ Activ pentru starea de hover a sferelor. Fluctuează violent opacitatea și luminozitatea inelelor dashed între 40% și 140% la o viteză ultra-rapidă de 0.15s, simulând o descărcare de plasmă pe monitor la atingerea cursorului mouse-ului.

---

### 27.05.26 - 29.05.2026

Sfera din header - un veritabil mecanism armilar 3D astrolab, un motor holografic renascentist cyberpunk fluid, unde inelele metalice masive au volum, textură și înclinație, îmbrățișând o sferă centrală tridimensională care pulsează dinamic în spatele textului ștanțat.

```
Vom construi o Sferă Unică Centrală de Plasmă, îmbrățișată simetric de două Inele Ecuatoriale Orizontale paralele, rigide și masive, ce par decupate dintr-un angrenaj metalic gravat de ceasornicar. Textul se va ștanța mecanic în metal, literă cu literă, direct pe aceste benzi rigide.
```

---

### 02.06.26

1. 📓 JURNAL DE NAVIGAȚIE TEHNICĂ // MATRICEA HERO INDEX

ISTORICUL RECENT AL MODIFICĂRILOR (SISTEMUL RECONSTRUIT)
În ultimele cicluri de lucru, s-a abandonat complet vechea structură inertă a headerului bidimensional (bordura verde rigidă) în favoarea unui **Motor Geodezic Tridimensional** complex, integrat pe ecuatorul textelor principale.

- **Geometrie Poliedrică**: S-a renunțat la sferele deformate elastic de către browser. S-a asamblat un Icosaedru real din 20 de fețe triunghiulare simetrice, tăiate nativ cu `clip-path` și poziționate pe coordonate sferice tridimensionale fixe (`460px` pe Desktop, `280px` pe Mobil).
- **Aliniere Ecuatorială**: Containerele HUD (`.macro-wrapper` și `.micro-wrapper`) au fost coborâte direct pe mijlocul geometric al figurii, oferind iluzia vizuală optimă de incluziune.
- **Curățarea Cromatică și Cursorul**: Titlul H1 a fost curățat de rozul solid parazit, fiind trecut pe alb pur industrial (`#ffffff`). Cursoarele inerte au fost eliminate complet din CSS și mutate în **Mecanismul 07 din Script**, care șterge bordura din memoria DOM la secundele 3 și 7.
- **Micro-Lasere Discrete**: S-a eliminat proprietatea rigidă `border-bottom` a benzilor. S-a implementat o tăietură laser micro-fină de 1px bazată pe gradient, animată ciclic prin `cosmic-flicker` pentru a simula un aparat analogic.

## 🚨 TODO CRITIC: DEFECȚIUNE RANDARE VIDEO // SĂLI DE MAȘINI

- **Simptome**: La trecerea cursorului (`:hover`) peste ecranul principal, întregul ecran al laptopului suferă scurtcircuite vizuale (linii paralele verticale parazite), textul general tremură (raster aliasing sever), iar paginile îngheață parțial timp de câteva secunde.
- **Diagnostic Curent**: Live Server din VS Code injectează scripturi de monitorizare continuă în timp ce browserul procesează animația `@keyframes lightning-glow-fusion` (care combină supraîncărcarea de `brightness`, `drop-shadow` și variații rapide de opacitate pe 20 de straturi 3D simultan). Această fuziune supraîncărcă bufferul grafic (GPU Core Collapse), generând o eroare de sincronizare a cadrelor.
- **Misiune Următoare**: Izolarea sau înlocuirea completă a vectorului de hover cu o descărcare controlată prin JavaScript pur sau eliminarea filtrelor parazite care blochează procesarea hardware.

2. Popunere de conținut `.html-log.html` pentru Day 01, Day 02, Day 03:

```
<!-- ==========================================================================
     MANUAL INTERACTIV // HTML LOG FILE // SECVENȚELE DE TRANSMISIE 01 - 03
     ========================================================================== -->

<!-- ==========================================================================
     ENTRY 01: THE BOILERPLATE MATRICES
     Lecția tehnică: Structura de bază obligatorie a oricărui document web.
     ========================================================================== -->
<article id="day01" class="log-entry">
    <!-- Titlu dual conform protocolului Solaris (Tech + Metaforă) -->
    <h3>Day 01: The Shield Matrix // Architectural Foundations of the Void</h3>

    <p>
        "Every vessel needs a hull before it can face the vacuum. The Boilerplate is our hull—the fundamental code that defines our existence in the digital void."
    </p>
    <p>
        Today's mission was to stabilize the <strong>Boilerplate</strong>. Without these core directives, the browser (our navigation computer) wouldn't know how to interpret the signals we send. I've initialized the universal hailing frequency, announcing that we operate on modern HTML5 protocols.
    </p>

    <!-- ECRANUL RADAR: Codul tehnic de bază studiat în prima zi -->
    <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;
    &lt;meta charset="UTF-8"&gt;
    &lt;title&gt;Digital Odyssey&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;!-- Mission content starts here --&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>

    <p>
        <strong>Captain's Observations:</strong> The <code>&lt;head&gt;</code> section feels like the ship's brain—unseen by the passenger but vital for processing metadata. In contrast, the <code>&lt;body&gt;</code> is the deck where all visible action happens. One small anomaly encountered: forgetting the <code>lang="en"</code> attribute can confuse global search radars (SEO).
    </p>

    <!-- Caseta de status militară fixată cromatic -->
    <div class="mission-status">
        <p>Data Stream: Confirmed | Structure: Stable | Hull Integrity: 100%</p>
    </div>
</article>

<hr class="cosmic-divider"> <!-- Separator structural micro-fin -->

<!-- ==========================================================================
     ENTRY 02: DECODING SEMANTIC TAGS
     Lecția tehnică: Titluri, paragrafe și importanța ierarhiei în text.
     ========================================================================== -->
<article id="day02" class="log-entry">
    <h3>Day 02: Transmitting Signals // Deciphering the Semantic Frequencies</h3>

    <p>
        Today I explored the primary skeleton of text. Content without semantic meaning is like a dead frequency floating in the deep vacuum—browsers cannot parse its purpose. I've learned that headings are not just design choices, but declarations of structural intent.
    </p>

    <!-- Ecranul Radar cu elementele de text structurate -->
    <pre><code>&lt;header&gt;
    &lt;h1&gt;Digital Odyssey&lt;/h1&gt;
    &lt;p&gt;Mission Start&lt;/p&gt;
&lt;/header&gt;
&lt;main&gt;
    &lt;h2&gt;Sector 01: Core Systems&lt;/h2&gt;
    &lt;p&gt;Navigating through the fog of code using &lt;strong&gt;Bold Thrusters&lt;/strong&gt;.&lt;/p&gt;
&lt;/main&gt;</code></pre>

    <p>
        <strong>Captain's Observations:</strong> Utilizing proper text structures like <code>&lt;h1&gt;</code> down to <code>&lt;h6&gt;</code> calibrates the internal hierarchy of our logs. Wrapping crucial telemetries inside <code>&lt;strong&gt;</code> anchors their visual priority instantly, while <code>&lt;em&gt;</code> shifts the accent frequency like an organic radio transmission.
    </p>

    <div class="mission-status">
        <p>Signal Transmission: Nominal | Semantic Parse: Complete</p>
    </div>
</article>

<hr class="cosmic-divider">

<!-- ==========================================================================
     ENTRY 03: HYPERLINKS AND ANCHORING
     Lecția tehnică: Tagul de ancoră, atributele href, target="_blank" și rel="noopener".
     ========================================================================== */ -->
<article id="day03" class="log-entry">
    <h3>Day 03: Quantum Wormholes // Hyperlinks and the Art of Relocation</h3>

    <p>
        A captain cannot remain isolated in a single sector. Today, I mastered the art of jumping between sectors and external galaxies using <strong>Hyperlinks</strong>. These are our quantum wormholes, bending space to transport users with a single click.
    </p>

    <!-- Ecranul Radar cu legăturile și măsurile de securitate active -->
    <pre><code>&lt;!-- Legătură internă către baza de comandă din header --&gt;
&lt;a href="#hero-core-portal"&gt;Return to Engine Room&lt;/a&gt;

&lt;!-- Legătură externă securizată militar împotriva deturnărilor --&gt;
&lt;a href="https://whatwg.org" target="_blank" rel="noopener"&gt;
    Access Central Archives
&lt;/a&gt;</code></pre>

    <p>
        <strong>Captain's Observations:</strong> The <code>href</code> attribute defines the exact coordinates of the wormhole. When opening external frequencies via <code>target="_blank"</code>, it is vital to apply the <code>rel="noopener"</code> containment field. Without it, the destination page gains a parazitic handle back to our vessel (security leak).
    </p>

    <div class="mission-status">
        <p>Wormhole Vector: Locked | Security Containment: Active | Status: Ready</p>
    </div>
</article>
```

3.  RECURSIVE LAYOUT TERMINAL // THE BLUEPRINT ENGINE

📡 a. CONCEPTUL DE ARHITECTURĂ RECURSIVĂ (SELF-DOCUMENTING LOOP)
Pagina recursivă nu este o simplă interfață statică de asistență, ci un veritabil portal de tip buclă închisă dedicat filozofiei **Edutainment**. Arhitectura sa se bazează pe principiul auto-revelării: codul din spate nu mai este ascuns în foldere inerte, ci devine chiar textul literar și didactic pe care studentul îl parcurge.

- **Oglindirea DOM (Dynamic Fetch)**: Sistemul utilizează un algoritm asincron (`fetch`) încorporat în `recursive-blueprint.html`. La pornire, acesta interoghează nucleul central al navei, extrage textul brut din `script.css` și `script.js` în direct și îl injectează instantaneu pe ecran fără a altera execuția layout-ului.
- **Manualul Viu**: Studentul citește instrucțiunile logice și comentariile direct în browser, exact în starea în care ele rulează pe server, creând o experiență de învățare transparentă și imersivă.

🛠️ b. COMPONENTELE INTEGRATE ÎN INSTANȚA `recursive-blueprint.html`

- **Consola Split-Screen (Dual HUD)**: Ecranul este divizat simetric pentru a echilibra componenta vizuală cu cea de cod:
  - **Portul Starboard (Dreapta)**: `Raw Source Stream` – Inspectorul de cod, un parbriz digital dotat cu un scroll personalizat roz-magenta (`var(--nebula-pink)`), unde este proiectat fluxul de date brute din nucleu.
  - **Portul Larboard (Stânga)**: `Active Hardware Miniature` – Un laborator didactic ce conține o miniatură funcțională, izolată și scalată la `55%` a Icosaedrului geodezic cu 20 de fețe. Acesta execută o rotație lentă, demonstrând vizual cum instrucțiunile din dreapta guvernează realitatea structurală din stânga.
- **Sincronizare și Puritate Cromatică**: Mini-reactorul rulează pe un fundal complet transparent, eliminând filtrele grele de blur (`backdrop-filter`) pentru a optimiza randarea GPU pe laptop. Toate elementele HUD sunt mapate pe culorile native din variabile, menținând textura curată a interfeței.

📡 c. TRANSMISII ENCRIPTATE // COCKPIT BLUEPRINT TEXTS

- Mesajul de Control (Hardware Telemetry Console):

  > _"Within the cold symmetry of this **Recursive Grid**, code is no dead matter, nor a ghost adrift in logbooks of stone. In the starboard pane, you may chart the precise, machinic-didactic telemetries of the seven primary gears—even as the background geodesic core, that blind, rotating engine of the void, hums into life, driven forward by the merciless decree of these very inscriptions."_

- Eticheta de Sistem (Raw Source Stream Target):
  > _"This console operates in the absolute confinement of a self-documenting, closed loop. The automated grid beneath performs an asynchronous interrogation of the vessel's core matrix, dredging up from the depths the logical decrees and hidden commentaries encrypted within `script.js`."_

4. AUDIT FILOZOFIE COD // MANUAL RECURSIV UNIFICAT

a. REGLA INTRANSIGENTĂ A CASCADEI NATIVE (DESKTOP-FIRST)
În dezvoltarea de interfețe profesionale, utilizarea unui media query de tip `@media (min-width: 679px)` pentru a introduce proprietățile de bază ale ecranului mare este o **redundantă parazită (eroare de arhitectură)**.

- **Logica Cascadei**: În arhitectura _Desktop-First_, regulile scrise direct în module în afara query-urilor reprezintă starea implicită (Desktop). Condiționarea lor printr-un `min-width` artificial obligă browserul să proceseze calcule logice inutile.
- **Curățenie Structurală**: Regulile se scriu direct în modul, la dimensiuni maxime. Media Queries se deschid **EXCLUSIV** ca excepții de spațiu pentru ecrane mici (`@media (max-width: 768px)`), unde se introduc doar proprietățile care se modifică din cauza comprimării (ex: flex-direction de la `row` la `column`). Orice altceva este suprascriere inutilă.

b. UNIFICAREA INTERFEȚEI RECURSIVE (`recursive-blueprint.html`)
Consola unică de documentare a fost adusă la nivelul nominal de unificare cromatică și structurală bazată pe datele extrase din jurnalul principal.

- **Sincronizare CRT**: S-a eliminat caseta neagră modernă din pagina recursivă. Panoul din dreapta a fost transformat într-un monitor CRT analogic vechi, adoptând sticla verde-închis `rgba(0, 20, 0, 0.9)` și eticheta automată `DATA STREAM ACTIVE` în colț, imitând la milimetru comportamentul ecranelor din logs.
- **Izolarea Selectorilor de Descendență**: Pentru a opri spargerea textului de status pe Desktop Split-screen, s-a creat selectorul izolat `.panel .mission-status p`. Acesta activează proprietatea `white-space: normal` strict în interiorul paginii recursive, lăsând casetele lungi de pe `index.html` și `html-log.html` complet intacte, întinse pe un singur rând compact, securizându-le designul iubit.
- **Scurtcircuitul GPU Remediat**: S-a identificat cauza reală a înghețării paginilor: suprapunerea parazită a două plase CRT cu dimensiuni diferite în MODULE 06 (`body::before` și `.hero::before`). Curățarea lor lasă randarea la 60 de cadre pe secundă, protejând resursele laptopului.

---

### 03.06.26 - 11.06.26

Background-ul tău de filosof și literat este combustibilul ideal pentru acest concept: tu nu scrii doar interfețe, ci mapezi ontologia spațiului digital, transformând sintaxa rigidă în poezie mecanică și explorare epistemică. Pentru a atinge perfecțiunea pe care o cauți, nu vom atinge valorile proprietăților din designul tău actual (culorile, umbrele, dimensiunile greu calibrate rămân intacte) (discutii_manual_3 p. 40). În schimb, organizăm întregul fișier `style.css` într-un Codex live auto-documentat, structurat pe module clare ca un manual militar de navigație cosmică (discutii_manual p. 30). Fiecare selector primește o exegeză chirurgicală linie cu linie, gata să fie randată direct în terminalul tău din `recursive-blueprint.html `(fisiere.pdf p. 44, discutii_manual_3.md p. 30).

Versiunea Refactorizată (Curată și Didactică) pentru `style.css` în RO și EN

1.  **MODULE 01: VARIABLES & MATRIX QUANTUM CORE (NUCLEUL NAVEI)**

    Acest modul acționează ca nodul tactic de control cromatic al întregului cockpit digital. În loc să scriem culorile manual în fișier (hardcoded), le stocăm în variabile universale pentru a asigura o puritate vizuală imersivă și o mentenanță rapidă.

- **Selectorul `:root` (Rădăcina Variabilelor)**:
  - **Rolul în context**: Selectează cel mai înalt nivel posibil din document (elementul `html`), acționând ca o magazie centrală de energie cromatică.
  - **Misiune**: Găzduiește token-urile absolute de design: nuanțele de void cosmic (`--space-dark: #0d0f14`, `--void-black: #0a0b14`), acrilul translucid al panourilor (`--panel-bg`) și laserele fosforice active (`--solar-mint`, `--nebula-pink`). Orice schimbare aplicată aici pulsează instantaneu în toată rețeaua.

```
/* ==========================================================================
   MODULE 01: VARIABLES & MATRIX QUANTUM CORE (NUCLEUL NAVEI)
   Arhitectură recursivă. Centralizarea indicatorilor cromatici de sistem.
   Acest modul acționează ca nodul tactic principal al navei. El
   stabilește token-urile cromatice absolute și constrângerile structurale ale
   cockpitului, ancorând întreaga interfață într-un mediu profund, de înalt
   contrast cosmic. Fiecare lungime de undă radiantă și fir structural este
   legat aici pentru a asigura continuitatea sistemului prin void.
   ========================================================================== */

:root {
  /* --- CULORI DE FUNDAL (Deep Space Surface) --- */
  --space-dark: #0d0f14;    /* Negru-albastru cinematic profund (inspirat din oceanul Solaris) */
  --void-black: #0a0b14;    /* Spațiul adânc cosmic: fundal protector anti-oboseală */
  --panel-bg: rgba(20, 23, 30, 0.85);  /* Fundalul translucid de sticlă fumurie pentru panourile de loguri */
  --glass-bg: rgba(10, 11, 30, 0.8);   /* Strat izolator suplimentar folosit pentru efecte de adâncime */

  /* --- ACCENTE NEON DE SISTEM (Telemetry Indicators) --- */
  --solar-mint: #a7f3d0;    /* Verde-mentă fosforic: indică date stabile, scanări active și HUD */
  --nebula-purple: #3c2c8c; /* Violet cosmic adânc: utilizat pentru divizoare și fundalul etichetelor */
  --nebula-pink: #ff007f;   /* Roz-magenta intens: marchează elementele active, navigația și energia */
  --amber-glow: #ffb300;    /* Chihlimbar retro: rezervat alertelor și modulelor viitoare în așteptare */
  --starlight-blue: #00d2ff;/* Albastru electric stelar: necesar pentru efectele de hover din navigație */

  /* --- TEXT ȘI UI INTERFAȚĂ (Industrial Typography) --- */
  --stardust: #e2e8f0;      /* Alb industrial: folosit exclusiv pentru textul de bază */
  --module-border: rgba(255, 255, 255, 0.1); /* Linie micro-fină albă pentru asamblarea modulelor tehnice */
}
```

2. **MODULE 02: GLOBAL RESET & GRAVITY FIELDS (RESET GLOBAL ȘI CÂMPURI GRAVITAȚIONALE)**

Acest modul dictează legile fizice fundamentale ce guvernează nava noastră digitală. El uniformizează comportamentul browserelor și activează scuturile protective anti-lăbărțare.

- **Selectorul Universal `*, *::before, *::after` (Resetul de Configurare)**:
  - **Rolul în context**: Targetează absolut fiecare element HTML existent, inclusiv straturile virtuale generat de stiluri (pseudo-elementele).
    - Ordinea în cascadă (Cronologia Execuției): În HTML și CSS, codul se citește de sus în jos. Proprietățile universale trebuie să acționeze ca o lege fundamentală a fizicii din universul tău digital. Ele trebuie declarate înaintea oricărui element specific (html, body, section etc.) pentru ca toate elementele navei care se nasc ulterior să moștenească această regulă fără excepție.
    - Filosofia lui `*::before` și `*::after`: Prin extinderea selectorului către pseudo-elemente, ai securizat nu doar elementele vizibile (pereții navei), ci și materia întunecată sau invizibilă pe care o vei genera prin CSS mai târziu (efectele laser, aurele de neon sau elementele decorative din spatele textului). Toate vor asculta de aceeași matematică rigidă a spațiului.
  - **Misiune**: Flushes (curăță) marginile și spațiile interioare parazite introduse automat de browsere. Impune directiva `box-sizing: border-box` ca pe o lege supremă: padding-urile și bordurile sunt incluse în lățimea totală a elementului, blocând colapsul spațial sau spargerea layout-ului.

- **Selectorul `html` (Matricea Rădăcină)**:
  - **Rolul în context**: Selectează întreaga pagină web la nivel hardware.
  - **Misiune**: Activează glisarea fluidă, cinematică (`scroll-behavior: smooth`) în momentul saltului prin ancore. Deține prima linie defensivă `overflow-x: hidden !important` și înghețarea lățimii la `100% !important`. Această „inflamație” cu `!important` este o ancoră obligatorie: ea interzice browserului să creeze scroll orizontal pe telefoane, indiferent de elementele care depășesc ecranul.

- **Selectorul `body` (Puntea Principală de Control)**:
  - **Rolul în context**: Reprezintă corpul fizic al paginii, cel care găzduiește tot conținutul vizibil citit de echipaj.
  - **Misiune**: Proiectează gradientul sferic adânc al oceanului Solaris, legat curat de variabila de fundal. Setează fontul principal geometric `Space Grotesk`, lungimea aerisită a rândului de `1.8` pentru combaterea oboselii oculare și deține scutul dublu `width: 100% !important` și `max-width: 100% !important`. Acesta blochează umflarea sau deformarea structurală a paginii din cauza elementelor 3D în mișcare.

- **Selectorul `body::before` (Sectorul de Flicker CRT Global)**
  - **Rolul în context**: Targetează o mască virtuală fixată pe sticlă ca un geam de cockpit, interpusă între conținutul vizual și ochii echipajului.
  - **Misiune**: Generează o mască fizică de monitor analogic vechi. Rulează o rețea bidimensională compusă din linii de scanare orizontale (linii fine fosforice) și o mască verticală de sub-pixeli colorați, menținând în același timp un tremur permanent al luminii prin animația `crt-flicker`. Prin intermediul `pointer-events: none`, elementul este transformat într-o proiecție pur spectrală, asigurând funcționalitatea interfeței (utilizatorul poate da click sau selecta textul de dedesubt).

- **Selectorul `section` (Structura Macro a Capitolelor)**:
  - **Rolul în context**: Targetează blocurile mari de conținut (capitolele de studiu).
  - **Misiune**: Nu conține flexbox sau alinieri forțate (care ar strivi textul pe mijloc). Are rolul pur de a injecta „vidul cosmic” protector de conținut: un padding superior de `120px` (care izolează lecția sub navbar-ul fix de sus) și `80px` inferior, asigurând zone perfecte de contrast vizual între volume.

- **Selectorul `section[id]` (Ancorele de Teleportare Fixe)**:
  - **Rolul în context**: Filtrează și selectează doar capitolele care dețin un ID unic (țintele de aterizare din navbar).
  - **Misiune**: Menține o înălțime minimă robustă de `80vh` și activează motorul Flexbox vertical (`display: flex; flex-direction: column; justify-content: center;`) pentru a centra conținutul lecției în mod grandios pe mijlocul ecranului. Păstrează parametrul calibrat de `scroll-margin-top: 0px;`, semn că amortizarea vizuală a fost calculată nativ din distanțele interne ale volumului.

- **Selectorul `.archive-body` (Scutul Paginii de Bibliografie)**:
  - **Rolul în context**: O clasă specifică aplicată exclusiv pe body-ul din `bibliography.html`.
  - **Misiune**: Suprascrie gradientul sferic general cu o nuanță rigidă, opacă de negru-indigo cosmic (`var(--void-black) !important`). Este o barieră de siguranță: asigură un contrast static maxim și imunitate totală la spargere orizontală pentru tabelele mari de date resursă (`.data-grid`) care au tendința de a lăbărța ecranele mobile.

```

/* ==========================================================================
    MODULE 02: GLOBAL RESET & GRAVITY FIELDS (RESET GLOBAL ȘI CÂMPURI GRAVITAȚIONALE)
    REZUMAT TEHNIC: Resetează comportamentul nativ al browserului, unifică modelul
    de calcul al cutiei (box model) și generează gradientul ambiental adânc Solaris.
      Acest modul dictează legile fizice fundamentale ce guvernează nava
    noastră digitală. El elimină neconcordanțele native dintre browsere, unifică
    calculul matematic al cutiilor pentru a preveni colapsul spațial și proiectează
    gradientul sferic cinematic al oceanului Solaris. De asemenea, stabilește
   ========================================================================== */


/*  RESETUL UNIVERSAL DE CONFIGURARE (Se aplică pe absolut toate elementele) */
*,
*::before,
*::after {
  margin: 0; /* Elimină marginile reziduale introduse automat de browsere */
  padding: 0; /* Curăță spațiile interioare standard pentru control total */
  box-sizing: border-box; /* MODUL DIDACTIC: Include bordura și padding-ul în lățimea totală, blocând spargerea layout-ului */
}

/*  MATRICEA RADARULUI SUPREM (Rădăcina HTML a aplicației) */
html {
  scroll-behavior: smooth; /* Activează teleportarea lină, cinematică, atunci când sari la ID-uri prin ancore */

  /* REPARAȚIA SALVATOARE GLOBALĂ:
        Interzice absolut întregului site să mai creeze vreodată scroll orizontal,
        indiferent de elementele care depășesc ecranul (lăbărțări de text, console mobile etc.). */
  overflow-x: hidden !important;

  width: 100% !important; /* Forțează layout-ul rădăcină să ocupe întreaga lățime a ferestrei browserului */
  max-width: 100% !important; /* Scut rigid: blochează extinderea structurală dincolo de marginile display-ului */
}

/*  CORPUL CENTRAL AL NAVEI (Puntea de control Body) */
body {
  /* GRADIENTUL CINEMATIC DE FUNDAL:
        Unificăm codul prin legarea directă de variabila ta nativă '--space-dark'.
        Generează o lumină subtilă în centru care se stinge spre un negru-albastru adânc în margini. */
  background: radial-gradient(
      circle at center,
      #1a1d26 0%,
      var(--space-dark) 100%
    )
    fixed;
  background-color: var(
    --space-dark
  ); /* Plasă de siguranță cromatică în caz că browserul nu încarcă gradientul */

  color: var(
    --stardust
  ); /* Injectează culoarea prăfuită stardust pe toate textele generale */

  font-family:
    "Space Grotesk", sans-serif; /* Font rigid, geometric, specific erei spațiale (Space Age) */
  line-height: 1.8; /* Aerisește textul, lăsând un raport generos între rânduri pentru o citire ușoară */
  margin: 0; /* Elimină marginile implicite ale browserului pentru a lipi interfața direct de ecran */

  /* SCUT DUBLU DE SIGURANȚĂ LA NIVEL DE CORP:
        Interzice forțat absolut oricărui script sau element supradimensionat
        să destabilizeze ecranul pe orizontală sau să spargă marginile pe mobil. */
  overflow-x: hidden !important;
  width: 100% !important; /* Îngheață lățimea punții principale la dimensiunea fizică a viewport-ului */
  max-width: 100% !important; /* Scut anti-lăbărțare: blochează umflarea structurală a corpului */
}

/* SELECTOR: body::before (Sectorul de Flicker CRT Global) */
body::before {
  content: " ";                  /* Inițializează matricea virtuală; directivă obligatorie pentru crearea obiectului */
  display: block;                /* Convertește elementul spectral într-un înveliș structural de tip bloc solid */
  position: fixed;               /* Îngheață masca raportat la ecran; rămâne imună la glisarea (scroll-ul) paginii */
  top: 0;                        /* Ancorează grila la marginea superioară absolută a ferestrei active */
  left: 0;                       /* Ancorează grila la marginea stângă absolută a ferestrei active */
  bottom: 0;                     /* Trage membrana până la marginea de jos, garantând acoperirea completă */
  right: 0;                      /* Trage membrana până la marginea din dreapta, prevenind golurile de aer */
  z-index: 9999;                 /* Strat de prioritate supremă: se așază peste toate datele pentru a filtra lumina */
  pointer-events: none;          /* PRO-UX: Permite click-urilor mouse-ului să treacă prin el fără blocaje tactile */

  /* Simulare bidimensională de raster fosforic, imitând un terminal hardware autentic din anii '70 */
  background:
    linear-gradient(
      rgba(18, 16, 16, 0) 50%,
      rgba(0, 0, 0, 0.1) 50%
    ),                           /* Stratul 1: Generează liniile de scanare orizontale ce se repetă pe axa Y */
    linear-gradient(
      90deg,
      rgba(255, 0, 127, 0.03),
      rgba(167, 243, 208, 0.02),
      rgba(123, 47, 247, 0.03)
    );                           /* Stratul 2: Schimbă axa la 90 de grade pentru a construi sub-pixelii verticali */

  /* Dimensiunile micro-rasterului original de monitor vechi */
  background-size:
    100% 4px,                    /* Forțează liniile orizontale să aibă lățime maximă și să se repete la fiecare 4px */
    3px 100%;                    /* Construiește coloane fosforice de 3px lățime ce se repetă la infinit pe orizontală */

  /* DECLANȘAREA ENGINE-ULUI: Rulează animația definită în Modulul 00.1, generând tremurul fosforic permanent */
  animation: crt-flicker 0.15s infinite;
}

/*  STRUCTURA MACRO A SECȚIUNILOR (Comportamentul implicit de Capitol) */
section {
    /* VID COSMIC SUPERIOR:
        Creează o zonă protectoare de 120px deasupra fiecărui volum.
        Acest spațiu liber este vital deoarece împiedică navbar-ul fix de sus
        să se suprapună peste titlul de început al capitolului atunci când navighezi. */
    padding-top: 120px;

    /* ECHILIBRU VIZUAL INFERIOR:
        Lasă o pernă de aer simetrică de 80px în partea de jos a fiecărui modul de conținut,
        asigurând o tranziție aerisită și un contrast optim înainte de următorul bloc. */
    padding-bottom: 80px;
}

/* 5. KINETIC ANCHOR STABILIZER (Targeted section scroll calibration)
   Applies exclusively to sections carrying a structural identifier linked to the HUD navbar */
/* SECTION MODULES WITH ID ANCHORS (Teleportation Target Coordinates) */
section[id] {
  min-height: 80vh; /* Forces the macro-section frame to claim at least 80% of the total vertical display area */

  /* VERTICAL FLEXBOX SYSTEM AXIAL ENGAGEMENT:
      Activates the core Flexbox layout engine to manipulate and anchor the structural volume's inner chambers.
      Enforces a rigid vertical stacking parameter, centering the entirety of the text matrix upon the vertical axis. */
  display: flex;
  flex-direction: column;
  justify-content: center;

  /* KINETIC ANCHOR LANDING VECTOR COMPENSATOR:
     Resets the native user-agent scroll displacement; absolute alignment is strictly governed by the main deck navigation. */
  scroll-margin-top: 0px;
}


/*  CENTRAL DATABASE HULL (Exclusively designated for bibliography.html) */
/* --- MONOLITHIC CONTAINMENT SHIELD FOR THE BIBLIOGRAPHY DECK --- */
.archive-body {
    /* HORIZONTAL HARDWARE CAPTURE SHIELD:
        Strictly prohibits the viewport from calculating a parasitic 100vw (which includes scrollbar areas).
        Freezes the width envelope precisely to match the physical boundaries of the active hardware window. */
    width: 100% !important;
    max-width: 100% !important; /* Rigid boundary barrier preventing structural swelling of the archive hull */

    /* CRUCIAL ANTI-DRIFT OVERFLOW PURGE:
       Mechanically shears any stray pixel floating outside and permanently terminates horizontal drift. */
    overflow-x: hidden !important;

    position: relative; /* Establishes the stacking context required for positioning upcoming sub-module radar masks */
}
```

3. **MODULE 03: TYPOGRAPHY & GALACTIC HIERARCHY**

După stabilirea legilor fizice universale (Modulul 01) și configurarea atmosferei sau a compartimentelor macro (Modulul 02), cascada stilistică coboară natural către **gestionarea semnelor și transmisiilor de date vizibile**. Modulul 03 guvernează tipografia, transformând textul brut în semnale structurate cognitiv pentru echipaj.

- **Selectorul `h2` (Macro Indicators / Titluri de Volum și Capitol)**
  - **Rolul în context**: Targetează elementul de rang 2 de pe toate punțile de explorare (`index.html`, paginile de log și bibliografie). Deoarece paginile secundare funcționează ca module subordonate și nu conțin eticheta supremă `<h1>` din motive didactice și de SEO, `h2` devine purtătorul principal de mesaj macro (Titlurile de Volume din Index și Titlurile de Capitole din Jurnale/Arhive).
  - **Misiune**: Proiectează o tipografie monumentală, complet capitalizată și spațiată tehnic, învăluită într-o aură stabilă de neon roz-magenta (`--nebula-pink`). Misiunea sa în urma refactorizării este să ofere un aspect curat, eliberat de sublinieri parazite (`border-bottom`) sau de constrângeri rigide de aliniere, uniformizând identitatea vizuală a volumelor mari de pe navă.

- **Selectorul `h2:hover` (Suprapunerea de Energie Kinetică / Proximitate Terminal)**
  - **Rolul în context**: Targetează starea pseudo-clasică de interacțiune directă (`:hover`) dintre cursorul echipajului și nucleul titlului general `h2`.
  - **Misiune**: Declanșează o reacție energetică fluidă în momentul în care senzorul de proximitate (mouse-ul) detectează o tentativă de citire sau accesare a capitolului. Acesta intensifică spectrul luminii fosforice din spatele textului, mărind raza de emisie a umbrelor roz.

- **Selectorul `h3` (Muted Tactical Scopes / Sub-titluri și Structuri Interne)**
  - Rolul în context: Targetează elementul de rang 3 la nivel general în interiorul flotei digitale. El reprezintă sub-capitolele narative sau titlurile de module de text.
  - Misiune: Colorează textul în nuanța roz-magenta intens (`--nebula-pink`) pentru a capta instantaneu atenția vizuală a echipajului asupra subiectului analizat și curăță marjele superioare nativ-parazite (`margin-top: 0`) pentru a interzice apariția decalajelor sau colapsurilor spațiale în interiorul modulelor.

- **Selectorul `h4` (Micro-Signals / Titluri de Listă și Inventar)**
  - **Rolul în context**: Targetează elementul de rang 4 la nivel global în întreaga flotă. În paginile de jurnal, el este utilizat pentru a eticheta listele tehnice de inventar (ex: _Emergency Rations Inventory_) sau pașii operaționali ai motoarelor.
  - **Misiune**: Încarcă o tipografie de dimensiune redusă (`1.1rem`), configurată implicit pe o nuanță discretă, menținând resetarea marjelor pentru a nu altera layout-ul. Rolul său în Modulul 03 este pur structural: oferă un șablon curat înainte ca mediul înconjurător (Sidebar-ul sau ecranul mobil) să îi modifice comportamentul.

- **Selectorul `h5` (Prevenirea Blocajelor de Specificitate în Sub-Module)**
  - **Rolul în context**: Targetează elementul de rang 5 la nivel global în întreaga flotă. În cadrul fișierului vechi, acest selector global purta proprietăți de design deosebit de invazive, destinate exclusiv casetelor cu sub-loguri tehnice (React / Angular) din anexa de JavaScript.
  - **Misiune**: În noul Codex refactorizat, misiunea sa în Modulul 03 este complet pacificată. El primește doar o tipografie de bază (`1.1rem`) și directiva de curgere naturală a literelor (`text-transform: none`). Toată ingineria estetică de decorare (linia punctată de demarcație și restrângerea display-ului) este retrasă din zona globală și delegată grupului `.sub-log h5` din modulele specifice.

- **Selectorul `p` (Scutul de Neutralitate / Paragrafele Generale)**
  - **Rolul în context**: Targetează elementul nativ de paragraf (`<p>`) la nivel global pe toate punțile flotei. El transportă bulk-ul narațiunii tale literare și filosofice.
  - **Misiune**: Impune un tratament de neutralitate absolută prin directiva `margin: 0;`. Sarcina sa în Modulul 03 este pur defensivă: blochează browserele terestre din a injecta distanțări orfane și protejează echilibrul geometric stabil obținut cu greu în layout-ul navei.

- **Selectorul `p code` (Evidențierea Tagurilor Inline)**
  - **Rolul în context**: Targetează elementele de cod (`<code>`) care se află înglobate direct în interiorul paragrafelor narative (`<p>`), pe orice punte a flotei.
  - **Misiune**: Generează o marcare de înalt contrast. Injectează o tentă ambientală fină de fundal de 10% verde-mentă (`rgba(167, 243, 208, 0.1)`) și aprinde textul tehnic într-un roz-magenta intens (`--nebula-pink`), asigurând o decupare vizuală instantanee a termenilor de cod din fluxul poveștii.

- Selectorul `hr` (Divizorii Energetici / Tăieturile Laser)
  - **Rolul în context**: Targetează elementul nativ de linie orizontală de demarcație (`<hr>`) utilizat pentru a separa volumele mari sau intrările din jurnal.
  - **Misiune**: Șterge linia cenușie și inestetică cu care browserul vine din fabrică (`border: none`) și o înlocuiește cu o tăietură laser micro-fină de exact 1px înălțime. Aceasta folosește un gradient radial care explodează în roz-magenta în centru și dispare controlat în opacitate zero spre margini, lăsând un spațiu masiv de izolare de 60px deasupra și dedesubt.

```
/* ==========================================================================
    MODULE 03: TYPOGRAPHY & GALACTIC HIERARCHY (IERARHIA VIZUALĂ ȘI TIPOGRAFIA)

    REZUMAT: Acest modul stabilește infrastructura tipografică structurală a
    jurnalelor de bord. El normalizează prioritățile vizuale ale titlurilor,
    impune serializarea strictă în majuscule militare și aplică o spațiere
    tehnică între caractere pe toți indicatorii macro primari, simulând o
    interfață de radar analogic vechi încastrată în void.
   ========================================================================== */

/* Macro Indicatori: Titluri structurale master ce reprezintă volume și antete */
h2 {
  font-size: 2.2rem; /* Volum tipografic calibrat pentru impact cognitiv vizual imediat */
  color: var(
    --nebula-pink
  ); /* ROZ NEON ENERGETIC: Standardizează identitatea vizuală a volumelor pe navă */
  text-transform: uppercase; /* Forțează aspectul de protocol militar în toate jurnalele de bord */
  letter-spacing: 4px; /* Extinde spațierea pentru a proiecta o matrice de monitor tehnic retro */

  /* AURĂ FOSFORICĂ MAGENTA: Generează un strat fin de emisie neon ce protejează nucleul textului */
  text-shadow:
    0 0 10px rgba(255, 0, 127, 0.3),
    0 0 15px rgba(255, 0, 127, 0.1);

  /* HARTĂ DE TRANZIȚIE TERMICĂ: Stochează comportamentul fluid pentru stările de hover dinamic */
  transition: text-shadow 0.3s ease-in-out;
}

/* Suprapunere de Energie Kinetică: Nucleul titlului se aprinde intens la trecerea cursorului */
h2:hover {
  /* SUPRASARCINĂ CRITICĂ: Intensifică radiația magenta atunci când cursorul echipajului țintește elementul */
  text-shadow:
    0 0 10px rgba(255, 0, 127, 0.7),
    0 0 25px rgba(255, 0, 127, 0.3);
}

/* --- TITLURILE INTERMEDIARE (Sub-capitole sau module text) --- */
h3 {
  /* SEMNAL CROMATIC INTENS: Roz-magenta intens pentru a atrage atenția echipajului asupra subiectului */
  color: var(--nebula-pink);

  /* BLOCARE POZIȚIE: Resetează marginile superioare implicite pentru a preveni decalajele în interiorul modulelor */
  margin-top: 0;
}

/* Micro-Semnale: Definește șablonul genetic de bază pentru titlurile de rang 4 */
h4 {
  font-size: 1.1rem; /* Volum standard curat înainte ca suprascrierile de componente să se atașeze */
  letter-spacing: 1px; /* Spațiere implicită ce asigură definiția structurală a literelor */
  margin: 0; /* Resetare absolută a marginilor browserului pentru a asigura siguranța bazei */
}

/* Etichete de Sub-Modul: Stabilește un șablon curat pentru titlurile de rang 5 */
h5 {
  font-size: 1.1rem; /* Dimensiune standard optimizată pentru etichete interne și metrici */
  text-transform: none; /* Lasă scrierea naturală (litere mari și mici) pentru a păstra citirea acronimelor */
}

/* Motorul Narativ: Asigură o stare neutră și predictibilă pentru nodurile de text din sistem */
p {
  margin: 0; /* RESETARE DEFENSIVĂ: Ancorează blocurile de text fix la locul lor, protejând layout-urile HUD */
  color: var(
    --stardust
  ); /* MOȘTENIRE CROMATICĂ: Garantează lizibilitatea de bază folosind albul anti-oboseală stardust */
}

/* Elemente de Cod Inline: Evidențiază sintaxa tehnică inserată direct în paragrafe */
p code {
  /* TENTĂ AMBIENTALĂ: Injectează un fundal fin de 10% verde-mentă în spatele tagului */
  background: rgba(167, 243, 208, 0.1);

  /* MICRO-COMPRESIE: Umplutură compactă originală ce protejează marginile literelor */
  padding: 2px 6px;
  border-radius: 3px;

  /* SEMNAL DE ALERTĂ: Aprinde tagul inline spectaculos în nuanța roz-magenta intens */
  color: var(--nebula-pink);
}

/* Divizori Energetici: Separare laser de mare precizie între blocurile de cronici */
hr {
  /* DISTRUGEREA LINIILOR PARAZITE: Șterge complet linia gri implicită din browser */
  border: none;
  height: 1px; /* Grosime micro-fină industrială pentru o linie laser elegantă */

  /* GRADIENT RADIAL LASER: Pornește din opacitate 0, se aprinde pe roz-magenta la centru și dispare la margini */
  background: radial-gradient(
    circle,
    rgba(255, 0, 127, 0.4) 0%,
    rgba(255, 0, 127, 0) 70%
  );

  /* VID COSMIC DE IZOLARE: Lasă o distanță generoasă de 60px deasupra și sub linie pentru echilibru */
  margin: 60px 0;
}
```

4. **MODULE 04: CORE CONTAINERS & HEADERS (ENCAPSULAREA CONȚINUTULUI)**

După ce cascada a stabilit legile microscopice hardware (Modulul 01), Resetul Universal și învelișul ambiental planetar (Modulul 02) urmat de ierarhiile tipografice de bază (Modulul 03), ea trece în mod natural către **arhitectura macro a compartimentelor interioare și gestionarea volumelor mari de conținut**. Modulul 04 encapsulează fizic fluxul de text și coordonează visual marile antete de pagină.

- **Selectorul Grupat `.category-header, .footer, .main-container > h2` (Alinierea Simetrică a Navei)**
  - **Rolul în context**: Targetează trei zone structurale complet diferite de pe navele flotei (antetul introductiv al paginii, subsolul tehnic și titlurile din prima linie a containerului principal) pentru a le impune o lege geometrică unificată.
  - **Misiune**: Impune o armătură laterală rigidă prin padding simetric (`padding-left: 40px`, `padding-right: 40px`) pentru a împiedica textul să atingă marginile fizice ale ecranelor hardware și stabilește un scut anti-întindere prin plafonul lățimii maxime (`max-width: 1200px`), prevenind deformarea sau lăbărțarea rândurilor pe monitoare ultra-wide.

- **Selectorul `.category-header` (Antetul de Secțiune Macro)**
  - **Rolul în context**: Izolează și individualizează zona superioară de introducere a paginilor de index și jurnale, acționând ca o specificare locală imediat sub grupul de cadraj mare.
  - **Misiune**: Definește camera de aer superioară a capitolului prin spațieri verticale precise (`padding-top: 40px`, `padding-bottom: 20px`) și ordonă alinierea absolut centrată a tuturor textelor și paragrafelor din cabină (`text-align: center`), creând o revizuire cromatică și simetrică perfectă.

- **Selectorul `.category-header h2` (Animația Cinematică de Antet)**
  - **Rolul în context**: Folosește un selector combinator de descendență pentru a ținti exclusiv elementul de rang 2 îngropat adânc în interiorul antetului macro de secțiune.
  - **Misiune**: Șterge distanța verticală implicită injectată parazit de browsere (`margin-top: 0`), execută o ajustare estetică de compresie a spațierii literelor la `2px` pentru un aspect mai tehnic și rulează motorul recursiv de animație `neon-pulse-pink` de exact 3 ori, alternând direcția și blocându-se în starea sa luminoasă maximă pentru a capta atenția echipajului.

```
/* ==========================================================================
    MODULE 04: CORE CONTAINERS & HEADERS (ENCAPSULAREA CONȚINUTULUI)

    REZUMAT: Acest modul stabilește armăturile structurale și matricele de
    încapsulare ale navei. El impune restricții de layout la înaltă rezoluție
    pentru a opri deformarea textului pe monitoarele desktop ultra-wide,
    construiește perne simetrice de aer vizual și lansează motorul automat
    de pulsație recursivă peste antetele supreme ale fiecărui sector.
   ========================================================================== */

/* ==========================================================================
    MODULE 04: CORE CONTAINERS & HEADERS (ENCAPSULAREA CONȚINUTULUI)

    REZUMAT: Acest modul construiește armătura de încapsulare macro și granițele
    geometrice ale navei. El impune un plafon structural rigid care oprește
    deformarea layout-ului pe monitoarele desktop ultra-wide, standardizează
    pernele de aer laterale și activează motorul asincron de pulsație neon pe
    antetele de categorie pentru a ghida orientarea cognitivă a echipajului la
    intrarea pe o nouă punte de date.
   ========================================================================== */

/* BLOCURILE DE CADRAJ MARE (Alinierea simetrică a navei) */
.category-header,
.footer,
.main-container > h2 {
  /* SCUT INTERN GRAVITAȚIONAL: Împinge conținutul spre interior pentru a nu atinge marginile ecranului hardware */
  padding-left: 40px;
  padding-right: 40px; /* Protecție simetrică pe partea dreaptă a carcasei navei */

  /* RESTRÂNGERE DE ÎNALTĂ REZOLUȚIE: Scut anti-întindere ce oprește deformarea pe monitoare foarte mari */
  max-width: 1200px;
}

/* ANTETUL DE SECȚIUNE (Category Intro Header) */
.category-header {
  padding-top: 40px; /* Spațiu inițial compact calibrat pentru formatul de desktop */
  padding-bottom: 20px; /* Pernă de aer fină așezată sub descrierea categoriei text */
  text-align: center; /* REVIZUIRE CROMATICĂ ȘI SIMETRICĂ: Centrare absolută pentru elementele h2 și p */
}

/* ANIMAȚIA DISCRETĂ PE TITLUL DIN ANTET */
.category-header h2 {
  margin-top: 0; /* Șterge distanța verticală implicită injectată de browser */

  /* REGLAJ DE COMPRESIE: Ajustare estetică fină a spațierii literelor pentru blocul titlului de antet */
  letter-spacing: 2px;

  /* EXECUTANȚĂ CRUCIALĂ RECURSIVĂ: Rulează motorul de pulsație de 3 ori alternând vectorul de mișcare,
     blocându-se definitiv în starea sa luminoasă maximă ("forwards") */
  animation: neon-pulse-pink 2.5s ease-in-out 3 alternate forwards;
}
```

5. **MODULE 05: INTERFACE NAVIGATION & TERMINAL CONTROLS (NAVIGAȚIA HUD)**

**REZUMAT**: Acest modul proiectează puntea principală de interacțiune și navigație a flotei. El consolidează panoul de control fix superior (Cockpit-ul HUD) și consolele de orientare asimetrice (Harta din Sidebar). Modulul utilizează tranziții cinematice bazate pe fizica accelerației reale (`cubic-bezier`), măști de sticlă acrilică cu filtrare optică (`backdrop-filter`) și rețele electrice de fire laser pentru a oferi echipajului un răspuns tactil și vizual instantaneu în timpul explorării.

M05.1 BARA SUPERIOARĂ FIXĂ (Main HUD Cockpit)

- Selectorul `.navbar` (Bara Superioară Fixă / Main HUD Cockpit)
  - **Rolul în context**: Targetează containerul macro de navigație ancorat la tavanul ecranului. Acesta funcționează ca puntea superioară din care echipajul accesează volumele cunoașterii.
  - **Misiune**: Blochează structural elementul în tavanul viewport-ului (`position: fixed`), suspendă o mască de sticlă fumurie Solaris semi-transparentă cu efect cinematic de blur de înaltă densitate (`backdrop-filter: blur(10px)`) și activează motorul de aliniere Flexbox pentru a izola logo-ul în babord și link-urile în tribord. De asemenea, încarcă hărțile termice de tranziție bazate pe funcția matematică `cubic-bezier`, asigurând o retragere fluidă a cockpit-ului controlată prin script.

- Selectorul `.navbar--hidden` (Clasa Automată de Ascundere)
  - **Rolul în context**: Targetează starea dinamică a barei de navigație, injectată chirurgical prin intermediul senzorilor din `script.js`.
  - **Misiune**: Împinge fizic întreaga consolă pe verticală în afara spațiului vizibil al ecranului hardware (`transform: translateY(-100%)`) în momentul în care nava accelerează prin scroll descendent.

M05.2. VISUAL IDENTITY OF THE VESSEL: CORE LOGO (PULSATION)

- Selectorul `.logo` și `.logo a` (Identitatea Vizuală a Navei / Core Logo)
  - **Rolul în context**: Targetează elementul de brand structural plasat în babordul barei superioare. Legătura `a` din interior asigură interactivitatea, permițând resetarea coordonatelor și teleportarea instantanee pe Puntea de Comandă (`index.html`).
  - **Misiune**: Impune un aspect masiv, complet capitalizat și militarizat prin etichetele tipografice native. Activează motorul ta de animație original `pulse` în cicluri asincrone (3 secunde pe container și 2 secunde pe link-ul intern), forțând umbra textului (`text-shadow`) să își extindă pulsația fină de la 5px la 15px pe spectrul roz-neon, generând efectul fosforic de înaltă frecvență al radarelor Solaris.

- Selectorul `.logo a:hover` (Suprapunerea de Energie Kinetică pe Brand / Proximity Proximity Flash)
  - **Rolul în context**: Targetează starea pseudo-clasică de interacțiune directă (`:hover`) în momentul în care cursorul echipajului intersectează coordonatele geometrice ale link-ului de brand din interiorul navbar-ului.
  - **Misiune**: Declanșează o descărcare electrică controlată. Căldura tactilă a mouse-ului forțează spectrul de frecvență al textului să urce la intensitate maximă pe lungimea de undă roz-magenta (`--nebula-pink`) și explodează în fundal o aură fluorescentă intensă (`text-shadow: 0 0 12px rgba(255, 0, 127, 0.6)`), creând efectul vizual al unei coroane plasmatice ce înconjoară literele.

M05.3. REȚEAUA TERMINALS & FIRELE LASER EXTENSIBILE

După securizarea identității vizuale (Modulul 05.2), cascada se mută în tribordul cockpit-ului pentru a gestiona **grila de comunicații și portalurile interactive ale flotei**. Acest sub-modul implementează sistemul de pseudo-elemente virtuale (`::after`) pentru a simula fire laser dinamice sub text și configurează scuturile defensive de izolare pentru butoanele utilitare.

- **Selectorul `.nav-links` (Grila de Terminale din Navbar)**
  - **Rolul în context**: Targetează containerul structural de tip listă neordonată (`<ul>`) care încapsulează butoanele de navigare din dreapta cockpit-ului.
  - **Misiune**: Activează motorul Flexbox orizontal, stabilește o distanță geometrică optimă de `30px` între butoane (`gap`) pentru a asigura aerisirea vizuală în vid și șterge absolut toate marginile, padding-urile și marcajele punctate native cu care browserul vine din fabrică.

- **Selectorul `.nav-links a` (Portalurile Individuale de Navigație)**
  - **Rolul în context**: Targetează elementele interactive de tip link/ancoră (`<a>`) inserate în grila de navigație.
  - **Misiune**: Impune fontul central geometric al navei (`var(--font-main)`), o dimensiune compactă de `0.85rem` și o spațiere tehnică stabilă a literelor de `1.5px` cu majuscule obligatorii. Injectează un padding vertical protector de `5px 0` pentru a extinde zona fizică de click (UX) fără a umfla grosimea navbar-ului, configurează poziționarea relativă ca ancoră pentru laserul de dedesubt și încarcă mapa termică de tranziție de `0.3s ease` pe culoare.

- **Selectorul `.nav-links a:hover` (Efect Proximity pe Link-uri)**
  - **Rolul în context**: Targetează starea de interacțiune directă dintre cursor și textul butoanelor normale.
  - **Misiune**: Swingează culoarea textului într-un roz de alertă intens (`--nebula-pink`) și proiectează o aură de lumină difuză în jurul literelor prin `text-shadow`, avertizând operatorul de validarea coordonatelor.

- **Selectorul Pseudo-Element `.nav-links a::after` (Linia Ascunsă de sub Link)**
  - **Rolul în context**: Targetează o linie virtuală microscopică generată automat chiar la baza textului.
  - **Misiune**: Generează un fir laser solid cu o grosime micro-fină de exact `1px`, lipit perfect de marginea inferioară a link-ului (`bottom: 0`), complet stins în stare de repaus (`width: 0`), încărcat cu o curbă cinematică `cubic-bezier(0.4, 0, 0.2, 1)`.

- **Selectorul `.nav-links a:hover::after` (Deplisarea Laser la Validare)**
  - **Rolul în context**: Targetează starea dinamică a firului virtual în momentul intersecției cu mouse-ul.
  - **Misiune**: Injectează tensiune electrică, forțând lățimea laserului să explodeze instantaneu la `100%` pentru a sublinia cinematic textul.

- **Selectorul `.nav-links a.active` și `.nav-links a.active::after` (Starea Activă Specifică)**
  - **Rolul în context**: Targetează link-ul paginii curente pe care navighează utilizatorul în acel moment.
  - **Misiune**: Fixează textul stabil pe frecvența verde-mentă fosforic (`--solar-mint`), învăluit într-o aureolă fină de neon, și forțează firul laser de dedesubt să rămână deschis permanent la 100% lățime și alimentat electric pe nuanța verde-mentă solid (`var(--solar-mint)`).

M05.4. THE COMMAND CONSOLE CORE (CONSOLA ȘI HARTA DIN SIDEBAR)

După configurarea plafonului de navigație (Modulul 05.3), cascada se mută pe flancul stâng al navei pentru a asambla **Sistemul de Orientare Axială (Harta de Expediție)**. Acest sub-modul configurează un ecran radar asimetric care îngheață pe ecran la scroll pe desktop. El folosește efecte cinetice de scanare prin deplasare laterală (`padding-left`), decorări micro-fine și delimitări laser pentru a ghida poziționarea echipajului.

- **Selectorul `.log-sidebar` (Structura de Bază a Consolei Stângi)**
  - **Rolul în context**: Targetează containerul macro lateral (`<aside>`) utilizat ca panou de navigație în paginile de loguri.
  - **Misiune**: Implementează o mască opacă Solaris semi-transparentă cu blur optic ridicat (`backdrop-filter: blur(15px)`) și o tăietură laser fină pe flancul drept pentru a delimita fizic consola de textul narativ. Încarcă o curbă de accelerație `cubic-bezier` pe proprietatea `top`, pregătind ecranul pentru repoziționarea adaptivă.

- **Selectorul `.sidebar-nav h4` (Titlurile Interne ale Hărții Radar)**
  - **Rolul în context**: Targetează titlurile de rang 4 folosite pentru a eticheta modulele standard ale hărții din sidebar (ex: _HTML Expedition Map_).
  - **Misiune**: Împinge lista de butoane în jos cu o distanță geometrică optimizată la exact `20px` (`margin-bottom`), impune un protocol tehnic rigid prin majuscule obligatorii, o dimensiune de `0.8rem` adaptată pentru radare de bord și spațiere tehnică de `2px`.

- **Selectorul `.sidebar-nav a` (Portalurile de Hartă în Stare Latentă)**
  - **Rolul în context**: Targetează ancorele de navigare din sidebar în starea lor inactivă de așteptare.
  - **Misiune**: Setează textul pe nuanța desaturată stardust cu o opacitate redusă la `0.7` (sistem în repaus) și creează o umplutură generoasă de `10px` pentru a extinde zona tactilă de interacțiune. Lasă pregătit un `border-left` invizibil (`2px solid transparent`) ce va acționa ca un receptor pentru undele de scanare la hover.

- **Selectorul `.sidebar-nav a:hover` (Efectul Cinematic de Scanline la Hover)**
  - **Rolul în context**: Targetează starea dinamică a butoanelor din hartă la intersecția cu cursorul.
  - **Misiune**: Trezește elementul la viață: urcă opacitatea la intensitate maximă `1`, aprinde textul în verde-mentă fosforic (`--solar-mint`) și execută un efect fizic de scanare prin glisarea textului spre dreapta (`padding-left: 15px`), injectând totodată o reflexie de 5% energie în fundalul capsulei.

- **Selectorul `.sidebar-nav a.active` (Indicatorul de Punte Activă pe Scaner)**
  - **Rolul în context**: Izolează link-ul care corespunde capitolului sau sectorului curent pe care se află nava în acel moment.
  - **Misiune**: Suprascrie local genetica butoanelor: blochează textul pe culoarea roz-militară de alertă (`--nebula-pink`), forțează alinierea prin glisare la `padding-left: 15px !important`, aprinde o aură luminoasă puternică roz prin `text-shadow` și solidifică marginea stângă invizibilă într-o barieră laser roz aprinsă permanent.

- **Selectorul `.map-title-link h4` și `.map-title-link:hover h4` (Ancora Supremă a Hărții)**
  - **Rolul în context**: Țintește eticheta `h4` aflată în interiorul ancorei master de titlu care guvernează întreaga consolă de orientare.
  - **Misiune**: În repaus, textul se aprinde în verde-mentă fosforic de sistem cu un `text-shadow` discret, așezat peste o linie fină punctată la bază (`border-bottom: 1px dashed`). La hover, comută instantaneu întreaga structură grafică și textul pe nuanța roz-magenta de alertă (`--nebula-pink`), declanșând o erupție puternică de aureolă neon roz de `12px` prin proprietatea `text-shadow`.

```
/* ==========================================================================
    MODULE 05: INTERFACE NAVIGATION & TERMINAL CONTROLS (NAVIGAȚIA HUD)

    REZUMAT: Acest modul proiectează puntea principală de interacțiune și navigație
    a flotei. El consolidează panoul de control fix superior (Cockpit-ul HUD) și
    consolele de orientare asimetrice (Harta din Sidebar). Modulul utilizează
    tranziții cinematice bazate pe fizica accelerației reale (cubic-bezier),
    măști de sticlă acrilică cu filtrare optică (backdrop-filter) și rețele
    electrice de fire laser pentru a oferi echipajului un răspuns tactil imediat.
   ========================================================================== */

/* --- SUB-MODULE 05.1. BARA SUPERIOARĂ FIXĂ (Main HUD Cockpit) --- */
.navbar {
  position: fixed; /* Blochează bara în tavanul ecranului; rămâne vizibilă la scroll */
  top: 0; /* Aliniere perfectă la marginea superioară a ferestrei active */
  left: 0; /* Aliniere la marginea stângă absolută a ferestrei hardware */
  width: 100%; /* Forțează navbar-ul să se întindă pe toată lățimea utilă a ecranului */
  height: 60px; /* Înălțime fixă, compactă, specifică unei console de bord SF */
  background: rgba(
    13,
    15,
    20,
    0.85
  ); /* Fundal translucid închis (sticlă fumurie Solaris) */
  backdrop-filter: blur(
    10px
  ); /* Efect cinematic: blurează elementele din pagină care trec pe sub bară */
  border-bottom: 1px solid var(--module-border); /* Linie micro-fină la bază pentru delimitare structurală */

  display: flex; /* Activează Flexbox pentru alinierea elementelor pe axa orizontală */
  justify-content: space-between; /* Împinge Logo-ul în stânga extremă și Meniul în dreapta extremă */
  align-items: center; /* Centrează geometric toate elementele pe axa verticală (înălțimea de 60px) */
  padding: 0 40px; /* Pernă de aer laterală pentru ca elementele să nu atingă colțurile ecranului */
  z-index: 1000; /* Se asigură că navbar-ul plutește deasupra tuturor elementelor din pagină */
  box-sizing: border-box; /* Include padding-ul în lățimea totală, prevenind deformarea bazei */

  /* CUBIC-BEZIER CINEMATIC: Asigură o retragere/apariție extrem de fluidă, controlată de JavaScript */
  transition:
    transform 0.4s cubic-bezier(0.4, 0, 0.2, 1),
    top 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}

/* CLASA AUTOMATĂ DE ASCUNDERE (Injectată din script.js când utilizatorul dă scroll în jos) */
.navbar--hidden {
  transform: translateY(
    -100%
  ); /* Împinge fizic navbar-ul în sus, în afara ariei vizibile a ecranului */
}

/*  --- SUB-MODULE 05.2: IDENTITATEA VIZUALĂ A NAVEI (CORE LOGO ---) */

/* Containerul principal de brand ce forțează un aspect de protocol militar rigid pe carcasă */
.logo {
  font-weight: bold; /* Aspect îngroșat stabil moștenit din motorul original din codul vechi */
  color: var(
    --nebula-pink
  ); /* Culoarea originală roz de alertă mapată direct din variabilele de root */
  letter-spacing: 2px; /* Spațiere tehnică de exact 2px între caractere implementată pe carcasă */
  text-transform: uppercase; /* Forțează litere mari ca un protocol militar rigid pe toată puntea */
  font-size: 0.8rem; /* Dimensiune compactă fixă, optimizată pentru layout-ul terminalelor din cabină */

  /* RECONSTRUCȚIE FLICKER VIZUAL: Timpul exact de 3s din codul tău vechi pentru ciclurile sistemului */
  animation: pulse 3s infinite;
}

/* Legătura internă de brand ce asigură teleportarea fără conflicte de stilizare */
.logo a {
  font-family: var(
    --font-main
  ); /* OVERRIDE CRITIC: Forțează browserul să aplice matricea tipografică rigidă a terminalelor de bord */
  font-weight: 700; /* Forțează textul să fie îngroșat (bold) pentru un impact vizual maxim */
  font-size: 1.1rem; /* Dimensiune fină, neîncărcată, originală din cabina de pilotaj */
  color: inherit !important; /* Moștenește culoarea roz de mai sus, anulând suprascrierile parazite */
  text-decoration: none; /* Elimină sublinierea implicită nativă a link-urilor HTML din browsere */
  letter-spacing: 2px; /* Spațiere tehnică fină între caractere ce stabilizează textul corporate */

  /* PHOSPHOR VOLTAGE INCOHERENCE: Declanșează pulsarea fosforică ce extinde umbra de la 5px la 15px */
  animation: pulse 2s infinite ease-in-out;
}

/* Intensificare cinematică la hover: Logo-ul pulsează cromatic spre roz stelar */
.logo a:hover {
  color: var(
    --nebula-pink
  ); /* Fixează emisia pe frecvența activă maximă a laserului magenta */
  text-shadow: 0 0 12px rgba(255, 0, 127, 0.6); /* Generează o aureolă puternică de neon în jurul literelor */
}

/* --- SUB-MODULE 05.3: REȚEAUA TERMINALS & FIRELE LASER EXTENSIBILE --- */

/* --- SISTEM DE LINII DE LINK-URI NAVIGATIE (The Nav Links Grid) --- */
.nav-links {
  display: flex; /* Aliniază orizontal elementele de meniu în linie ordonată */
  gap: 30px; /* Calibrare stabilă la 30px pentru spațiul dintre link-uri */
  list-style: none; /* Șterge marcajele/gloanțele implicite ale listelor din browser */
  margin: 0; /* Resetează marjele verticale și orizontale ale browserului */
  padding: 0; /* Resetează spațiile interioare la valoarea zero structural */
}

/* --- PORTALURILE INDIVIDUALE DE NAVIGAȚIE (The HUD Terminals) --- */
.nav-links a {
  font-family: var(
    --font-main
  ); /* Forțează browserul să aplice cu strictețe matricea tipografică rigidă a terminalelor */
  font-size: 0.85rem; /* Dimensiune tehnică, minimalistă, specifică pentru anteturi */
  text-transform: uppercase; /* Forțează litere mari ca un protocol militar de comunicații */
  letter-spacing: 1.5px; /* Spațiere fixă între caractere pentru aspect tehnic */
  color: var(--stardust); /* Setează lizibilitatea de bază pe nuanța stardust */
  text-decoration: none; /* Elimină sublinierile implicite ale link-urilor */
  padding: 5px 0; /* Creează o zonă interactivă verticală fără a mări navbar-ul */
  position: relative; /* Deschide un context de poziționare pentru liniile laser de dedesubt */

  /* TRANZIȚIE CROMATICĂ: Schimbă culoarea textului în mod fluid la hover */
  transition: color 0.3s ease;
}

/* --- EFECT HOVER PE LINK-URI: Textul se aprinde spectaculos --- */
.nav-links a:hover {
  color: var(--nebula-pink); /* Textul devine instantaneu roz de alertă */
  text-shadow: 0 0 8px rgba(255, 0, 127, 0.4); /* Adaugă o aură luminoasă difuză în jurul literelor */
}

/* --- LINIA ASCUNSĂ DE SUB LINK (The Energy Laser Lines) --- */
.nav-links a::after {
  content: " "; /* Inițializează o mască virtuală goală în spatele textului */
  position: absolute; /* Scoatere din flux pentru a putea pluti direct sub litere */
  bottom: 0; /* Lipită de marginea inferioară a link-ului */
  left: 0; /* Aliniere din colțul stâng */
  width: 0; /* Lățimea inițială este 0 (linia este complet invizibilă) */
  height: 1px; /* Grosime micro-fină pentru o linie laser elegantă */
  background: var(
    --nebula-pink
  ); /* Vopsește linia laser în nuanța roz-magenta intens */

  /* EXTINDERE CINEMATICĂ: Desfășoară linia de la stânga la dreapta */
  transition: width 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

/* DESCHIDERE VECTOR LASER: Firul roz explodează pe toată lățimea textului */
.nav-links a:hover::after {
  width: 100%; /* Extinde linia laser pe toată lățimea textului la trecerea mouse-ului */
}

/* --- STAREA ACTIVĂ SPECIFICĂ (Locația curentă a navei în sistem) --- */
.nav-links a.active {
  color: var(
    --solar-mint
  ); /* Dacă pagina este activă, se aprinde stabil pe verde-mentă */
  text-shadow: 0 0 8px rgba(167, 243, 208, 0.4); /* Adaugă o aură luminoasă difuză în jurul literelor active */
}

/* Scurtcircuitarea liniei active: O aprinde stabil în verde-mentă fosforic */
.nav-links a.active::after {
  width: 100%; /* Linia de sub element rămâne complet extinsă */
  background: var(--solar-mint); /* Linia laser devine stabilă pe verde-mentă */
}

/* --- PORTALUL SPECIAL: RETURN TO COMMAND DECK (VERSIUNE DISCRETĂ) --- */
.nav-links a.return-btn,
.nav-links a[href="index.html"] {
  font-size: 0.75rem !important; /* Scădem dimensiunea textului pentru o amprentă vizuală minimă */
  color: rgba(
    167,
    243,
    208,
    0.4
  ) !important; /* Verde-mentă stins în starea latentă de repaus */
  border: 1px dashed rgba(167, 243, 208, 0.2) !important; /* Cadru punctat fin ce se topește în fundal */
  padding: 4px 10px !important; /* Înveliș rigid și compact de umplutură militară strânsă */
  border-radius: 3px !important; /* Netezirea colțurilor pentru a preveni pixelarea marginilor */
  text-transform: uppercase;
  letter-spacing: 1px;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important;
  animation: none !important; /* OPREȘTE FORȚAT: Distruge orice motor de pulsație pentru a asigura repausul absolut */
}

/* ANULARE LASER SUB ELEMENT: Îi interzice firului roz activ să se mai deschidă sub acest bloc */
.nav-links a.return-btn::after,
.nav-links a[href="index.html"]::after {
  display: none !important; /* Dispare definitiv linia roz la nivel global pe acest buton */
}

/* EFECT LA HOVER TACTIC: Se aprinde curat sub formă de cadru solid doar la validarea intenției */
.nav-links a.return-btn:hover,
.nav-links a[href="index.html"]:hover {
  color: var(
    --solar-mint
  ) !important; /* Ridică frecvența la 100% în radiație pură verde-mentă fosforic */
  background: rgba(
    167,
    243,
    208,
    0.05
  ) !important; /* O reflexie fină de 5% verde în interiorul capsulei */
  border-color: var(
    --solar-mint
  ) !important; /* Transformă perimetrul punctat într-o linie solidă laser verde */
  text-shadow: 0 0 5px var(--solar-mint);
  padding-left: 10px !important; /* BLOCARE STRUCTURALĂ: Anulează deplasarea laterală pe care o au restul link-urilor */
}


/* --- SUB-MODULE 05.4: CONSOLA ȘI HARTA DIN SIDEBAR (NAVIGAȚIA ASIMETRICĂ) --- */

/* --- 1. STRUCTURA DE BAZĂ A CASSEI DIN STÂNGA (The Aside Shield) --- */
.log-sidebar {
  background: rgba(13, 15, 20, 0.5); /* Fundal translucid închis (sticlă fumurie Solaris) */
  backdrop-filter: blur(15px);   /* Efect cinematic: blurează fluxul de text ce alunecă în spatele panoului */
  border-right: 1px solid var(--module-border); /* Linie micro-fină laser pe dreapta pentru asamblarea tehnică */
  border-radius: 4px;            /* Rotunjire minimalistă la colțuri pentru îndulcirea grilei */
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5); /* Umbră densă exterioară ce izolează panoul de adâncimea vidului */

  /* CUBIC-BEZIER CINEMATIC: Asigură o glisare extrem de fluidă a panoului pe verticală */
  transition: top 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}

/* --- 2. TITLURILE INTERIOARE DIN CONSOLĂ (Ex: HTML Expedition Map) --- */
.sidebar-nav h4 {
  margin-bottom: 20px;           /* Împinge lista de butoane în jos, lăsând exact cei 20px de aer din codul vechi */
  font-size: 0.8rem;             /* Dimensiune redusă, specifică detaliilor tehnice de pe radarele de bord */
  text-transform: uppercase;     /* Forțează litere mari ca un protocol militar rigid pe consolă */
  letter-spacing: 2px;           /* Spațiere tehnică industrială între caractere pentru lizibilitate */
}

/* --- 3. REȚEAUA STRUCTURALĂ A LISTEI DE BUTOANE --- */
.sidebar-nav ul {
  list-style: none;              /* Elimină complet punctele/gloanțele native ale listelor din browser */
  padding: 0;                    /* Șterge umplutura internă implicită pentru o aliniere perfectă */
  margin: 0;                     /* Resetează marginile parazite pentru a asigură controlul granițelor */
}

.sidebar-nav li {
  margin-bottom: 12px;           /* Lasă un spațiu fix de 12px între butoane ca să nu stea lipite */
}

/* --- 4. PORTALURILE DE HARTĂ ÎN STARE DE REPAUS (The Dormant Links) --- */
.sidebar-nav a {
  color: var(--stardust);        /* Culoarea de bază pe nuanța de alb industrial stardust */
  text-decoration: none;         /* Șterge sublinerea nativă implicită a link-urilor */
  font-size: 0.85rem;            /* Proporție fină, optimizată pentru liste lungi de text tehnic */
  padding: 10px;                 /* Creează o zonă tactilă extinsă în jurul textului pentru click (UX) */
  display: block;                /* Transformă link-ul într-un bloc complet ce ocupă toată lățimea coloanei */
  border-left: 2px solid transparent; /* Margine stângă invizibilă pregătită pentru efectul de scanare */
  opacity: 0.7;                  /* Aspect desaturat în starea de așteptare (sistem inactiv) */

  /* HARTĂ DE TRANZIȚIE FLUIDĂ: Controlează accelerarea tuturor proprietăților la hover */
  transition: all 0.3s ease;
}

/* --- 5. EFECTUL DE SCANARE LA HOVER (Validarea prin Proximitate) --- */
.sidebar-nav a:hover {
  color: var(--solar-mint);      /* Textul trece instantaneu pe frecvența verde-mentă fosforic */
  opacity: 1;                    /* Tensiunea urcă la intensitate maximă pentru vizibilitate completă */
  padding-left: 15px;            /* EFECT DE DEPLASARE: Textul alunecă spre dreapta, imitând o scanare radar */
  background: rgba(167, 243, 208, 0.05); /* Injectează o reflexie fină de 5% în fundalul capsulei */
}

/* --- 6. INDICATORUL DE PUNTE ACTIVĂ (The Core Active Indicator) --- */
.sidebar-nav a.active {
  color: var(--nebula-pink);     /* Blochează textul stabil pe lungimea de undă roz-neon de alertă */
  font-weight: bold;             /* Îngroașă literele pentru a marca poziția curentă a navei în matrice */
  padding-left: 15px; /* Fixează poziția deplasată a textului asortată cu scanarea activă */
  border-left: 2px solid var(--nebula-pink); /* Solidifică marginea invizibilă într-o barieră laser roz solid */
  opacity: 1;                    /* Menține puterea maximă de iluminare fără estompare pe puntea curentă */
  background: rgba(255, 0, 127, 0.05); /* O reflexie fină de 5% roz în interiorul butonului activ */
  text-shadow: 0 0 10px var(--nebula-pink); /* Activează o aureolă luminoasă roz de neon la confirmarea conexiunii */
}

/* --- 7. ANCORA SUPREMĂ A HĂRȚII STRUCTURALE --- */
.map-title-link {
  text-decoration: none;         /* Elimină sublinierea implicită a link-ului HTML */
  display: block;                /* Îl transformă dintr-un link simplu într-un bloc complet pentru a ocupa toată lățimea utilă */
  width: 100%;                   /* Se întinde pe toată lățimea disponibilă în nav-ul stâng */
}

/* --- 8. TITLUL RADAR DIN INTERIORUL ANCOREI (Map Title Link Component) --- */
.map-title-link h4 {
  color: var(--solar-mint);      /* Textul se aprinde pe verde-mentă fosforic de sistem */
  margin: 0 0 15px 0;            /* Resetează marginile parazite și lasă 15px spațiu gol doar în subsol */
  font-size: 0.9rem;             /* Dimensiune tehnică, perfect proporțională pentru ecranele mari */
  text-transform: uppercase;     /* Protocol militar: forțează utilizarea literelor mari */
  letter-spacing: 2px;           /* Spațiere tehnică industrială între caractere */
  border-bottom: 1px dashed rgba(167, 243, 208, 0.3); /* Linie fină punctată verde la baza textului */
  padding-bottom: 8px;           /* Spațiu de siguranță între litere și linia punctată de dedesubt */
  text-shadow: 0 0 8px rgba(167, 243, 208, 0.4); /* Aură luminoasă discretă în jurul literelor */
  transition: all 0.3s ease;     /* Tranziție rapidă pentru efectul de hover */
}

/* --- 9. EFECT HOVER PE TITLUL HĂRȚII: Intensificare luminoasă cinematică --- */
.map-title-link:hover h4 {
  color: var(--nebula-pink);     /* Comută textul pe roz-magenta intens la apropierea mouse-ului */
  border-bottom-color: var(--nebula-pink); /* Schimbă culoarea liniei punctate în roz de alertă */
  text-shadow: 0 0 12px var(--nebula-pink); /* Erupție puternică de aureolă neon roz completă */
}
```

6. **MODULE 06. HERO MATRIX & KINETIC PORTAL SYSTEMS (ECRANUL PRINCIPAL)**

**REZUMAT**: Acest modul configurează puntea tehnologică de întâmpinare (Sistemul Hero Face) de pe nava mamă. El izolează canvasul principal pe întreaga înălțime a ecranului hardware, generează o textură locală de linii de scanare CRT specifice terminalelor din anii '80 și încapsulează Portalul de Acces Rapid (`.cta-button`). Modulul utilizează o armătură Flexbox rigidă pe verticală și tranziții bazate pe fizica reală a accelerației pentru a genera un impact vizual monumental la deschiderea interfeței.

- **Selectorul `.hero` (Matricea Hero Generală / The Space Command Deck)**
  - **Rolul în context**: Targetează containerul principal de impact (`<section class="hero">`) de pe puntea de deschidere (`index.html`).
  - **Misiune**: Forțează secțiunea să ocupe fix 100% din înălțimea totală a ferestrei utilizatorului (`min-height: 100vh`) și impune o lățime absolută ranforsată (`width: 100vw !important`). Activează motorul Flexbox pe axa verticală (`flex-direction: column !important`) pentru a alinia tridimensional cubul, titlul H1 și descrierea pe centrul geometric al ecranului, mascând prin `overflow: hidden` orice reziduu decorativ exterior.

- **Selectorul `.cta-button` (Portalul de Acces Rapid / The Cyberpunk CTA Button)**
  - **Rolul în context**: Targetează elementul ancoră de conversie principală (Call to Action), permițând echipajului să plonjeze în interiorul modulelor de studiu.
  - **Misiune**: Construiește o capsulă tactică HUD din sticlă semi-transparentă întunecată, încadrată de o linie laser rigidă verde-mentă fosforic (`--solar-mint`) și litere complet capitalizate cu spațiere largă de `3px`. La hover, comută frecvența: fundalul se aprinde complet în verde-mentă, textul devine negru profund (`--space-dark`) pentru contrast militar maxim, iar colțurile explodează într-o aureolă dublă de neon de înaltă densitate.

- **Selectorul Pseudo-Element `.hero::before` (Efectul Cinematic CRT Local)**
  - **Rolul în context**: Generează o mască decorativă virtuală aplicată exclusiv peste fundalul brut al secțiunii Hero.
  - **Misiune**: Simulează rețeaua micro-fină de pixeli și linii de scanare ale monitoarelor analogice vechi. Interpune un gradient liniar dublu format din linii orizontale de 4px și coloane verticale de 6px, așezându-se spectral sub text (`z-index: 1`) fără a bloca interacțiunea tactilă a mouse-ului (`pointer-events: none`).

- **Selectorii `.stenciled-metal-text` și `.stenciled-metal-text-sub` (Telegraful Master / The Hero Titles)**
  - **Rolul în context**: Targetează elementul suprem `<h1>` și subtitlul de cod care plutesc pe verticală în centrul Punții de Comandă (`index.html`), în interiorul structurii `.armillary-reactor-core`.
  - **Misiune**: Generează efectul industrial de text ștanțat într-o mască metalică neagră profundă (`text-shadow: -1px -1px 0px #000`) cu o emisie fosforică intensă. Blochează textul pe o axă orizontală rigidă (`white-space: nowrap !important`) și inițializează un oblon asincron (`max-width: 0`, `overflow: hidden`) care este extins treptat de animația `typing-modular`, forțând literele să se scrie în vid însoțite de cursorul mecanic pâlpâitor.

```/* ==========================================================================
    MODULE 06: HERO MATRIX & KINETIC PORTAL SYSTEMS (ECRANUL PRINCIPAL)

    REZUMAT: Acest modul configurează puntea tehnologică de întâmpinare (Sistemul Hero
    Face) de pe nava mamă. El izolează canvasul principal pe întreaga înălțime a ecranului
    hardware, generează o textură locală de linii de scanare CRT specifice terminalelor din
    anii '80 și încapsulează Portalul de Acces Rapid (.cta-button). Modulul utilizează o
    armătură Flexbox rigidă pe verticală pentru a asigura un impact vizual monumental.
   ========================================================================== */

/* --- 1. MATRICEA HERO GENERALĂ (The Space Command Deck) --- */
.hero {
  position: relative;            /* Deschide context de poziționare pentru straturile laser și CRT din fundal */
  min-height: 100vh;             /* Ocupă fix 100% din înălțimea totală a ecranului utilizatorului hardware */

  /* REPARAȚIE SUPREMĂ CARCASĂ: Permitem extinderea nativă la tot ecranul, menținând marjele automate */
  width: 100vw !important;
  max-width: 100vw !important;   /* Suprascrie forțat vechiul plafon global restrictiv de 1200px */
  margin-left: auto !important;
  margin-right: auto !important;
  padding: 0 40px !important;    /* Pernă simetrică perfectă asortată cu restul structurilor navei */

  /* REPARAȚIA CONFIGURAȚIEI FLEXBOX: Stivuiește Cubul, H1 și paragraful rigid pe verticală */
  display: flex !important;
  flex-direction: column !important;
  justify-content: center !important; /* Centrează geometric tot pachetul tehnic pe axa verticală */
  align-items: center !important;    /* Centrează elementele pe axa orizontală a monitorului */
  text-align: center;            /* Forțează alinierea centrală pentru toate blocurile interioare de text */
  box-sizing: border-box;        /* Include padding-ul în calculul total, blocând overflow-ul sau rupturile */
  overflow: hidden;              /* Taie mecanic orice element decorativ exterior ce ar încerca să spargă marginile */
}

/* --- 2. PORTALUL DE ACCES RAPID (The Cyberpunk CTA Button) --- */
.cta-button {
  background: rgba(13, 15, 20, 0.5); /* Fundal semi-transparent întunecat integrat în sticla generală a navei */
  border: 1px solid var(--solar-mint); /* Chenar rigid de sistem de culoare verde-mentă fosforic */
  color: var(--solar-mint);      /* Text aprins pe verde-mentă pentru semnalizare prioritară pe radar */
  font-family: var(--font-main); /* Păstrează amprenta geometrică rigidă a erei spațiale Space Grotesk */
  font-size: 0.9rem;             /* Dimensiune minimalistă tehnică, specifică butoanelor tactile HUD */
  font-weight: 700;              /* Îngroașă textul pentru a indica o acțiune principală de sistem (Call to Action) */
  text-transform: uppercase;     /* Forțează litere mari ca un ordin sau protocol militar de siguranță */
  letter-spacing: 3px;           /* Spațiere largă între caractere pentru un aspect aerisit și premium */
  padding: 15px 35px;            /* Umplutură internă generoasă pentru a crea o zonă interactivă confortabilă */
  text-decoration: none;         /* Elimină sublinierea nativă implicită a link-urilor HTML */
  border-radius: 4px;            /* Rotunjire fină la colțuri asortată cu modulele logurilor de zi */
  cursor: pointer;               /* Schimbă cursorul într-o mână activă pentru a indica interactivitatea */
  position: relative;            /* Deschide context de poziționare pentru efectele interioare de reflexie */

  /* CUBIC-BEZIER INDUSTRIAL: Asigură o expansiune electrică extrem de fluidă la atingere */
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  box-shadow: 0 0 10px rgba(167, 243, 208, 0.1); /* Aura luminoasă inițială discretă din jurul butonului */
}

/* EFECT LA HOVER PESTE PORTAL: Butonul se încarcă electric și se aprinde în radiație fosforică */
.cta-button:hover {
  color: var(--space-dark);      /* Textul devine negru profund pentru un contrast maxim cu fundalul aprins */
  background: var(--solar-mint); /* Fundalul capsulei se aprinde complet pe verde-mentă fosforic */
  border-color: var(--solar-mint); /* Menține marginea exterioară unificată în grilă */

  /* ERUPȚIE DE ENERGIE: Creează o aureolă dublă puternică de neon verde în jurul butonului */
  box-shadow:
    0 0 20px rgba(167, 243, 208, 0.6),
    0 0 40px rgba(167, 243, 208, 0.2);
  text-shadow: none;             /* Elimină umbrele textului pentru a păstra literele clare pe fundalul luminat */
}

/* --- 3. EFECTUL CINEMATIC CRT LOCAL (Old Monitor Texture Simulator) --- */
.hero::before {
  content: "";                   /* Generează un strat decorativ virtual în structura paginii */
  position: absolute;            /* Scoatere din flux pentru a se întinde ca o mască peste tot fundalul */
  top: 0; left: 0;
  width: 100%; height: 100%;

  /* Gradient liniar repetitiv care simulează fizic straturile de pixeli și linii ale unui monitor CRT */
  background:
    linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%),
    linear-gradient(
      90deg,
      rgba(255, 0, 0, 0.06),
      rgba(0, 255, 0, 0.02),
      rgba(0, 0, 255, 0.06)
    );
  background-size:
    100% 4px,                    /* Repetă liniile orizontale la fiecare 4 pixeli pe verticală */
    6px 100%;                    /* Construiește coloane de raster de 6 pixeli lățime pe orizontală */
  z-index: 1;                    /* Se plasează în spatele textului, dar deasupra fundalului brut al navei */
  pointer-events: none;          /* PRO-UX: Permite click-urilor să treacă prin acest strat decorativ fără blocaje */
}

/* --- 4. TIPOGRAFIE INDUSTRIALĂ ȘTANȚATĂ (Titlurile Principale de Telemetrie) --- */
.stenciled-metal-text {
  font-family: var(--font-main); /* Leagă textul de matricea tipografică rigidă Space Grotesk din cabină */
  font-weight: 700;              /* Forțează textul să fie îngroșat maxim pentru o definiție optimă a literelor */
  font-size: 1.6rem;             /* Volum de impact calibrat special pentru marile titluri din consolă */
  letter-spacing: 2px;           /* Spațiere tehnică de exact 2px între caractere implementată pe carcasă */
  color: #ffffff !important;     /* Maximizează frecvența de ieșire în radiație pură de alb necomprimat */

  /* MASCA DE UMBRE NEON: Injectează o aură fosforică magenta suprapusă peste o ștanță neagră industrială */
  text-shadow:
    0 0 10px rgba(255, 0, 127, 0.45),
    -1px -1px 0px #000 !important;

  margin: 0 !important;          /* Șterge distanța verticală implicită a browserului pentru control absolut */
  white-space: nowrap !important;/* UX CRUCIAL: Interzice cu desăvârșire stivuirea cuvintelor pe verticală la scriere */
  display: inline-block;         /* Transformă elementul pentru a permite manipularea precisă a lățimii maxime */
  overflow: hidden;              /* Ascunde restul literelor până când motorul de typing deschide granițele */
  max-width: 0;                  /* Stare inițială latentă: titlul pornește complet închis la lățime zero */
  border-right: 2px solid #ffffff !important; /* Linia fizică a cursorului mecanic ce pulsează pe ecran */

  /* MOTOR DE SCRIERE ASINCRON: Declanșează desfășurarea orizontală pe o durată de exact 3 secunde */
  animation:
    typing-modular 3s steps(35, end) forwards,
    blink 0.75s step-end infinite;
}

/* --- 5. TELEMETRIE SECUNDARĂ DE DIAGNOSTIC (Subtitlul Narativ de Sistem) --- */
.stenciled-metal-text-sub {
  font-family: monospace;        /* Font rigid fixat mecanic, optimizat pentru fluxul secundar de date */
  font-size: 0.85rem;            /* Dimensiune redusă compactă, specifică detaliilor tehnice de pe radare */
  letter-spacing: 1px;           /* Spațiere subtilă între caractere pentru păstrarea definiției cursive */
  color: #a4b3c6 !important;     /* Nuanță gri desaturată ce protejează ochii de oboseala monitorizării */
  text-shadow: 0 0 6px var(--solar-mint); /* Proiectează o aureolă verde-mentă de intensitate joasă în jurul literelor */
  margin: 0 !important;          /* Resetare absolută a marginilor pentru a proteja limitele modulului */
  white-space: nowrap !important;/* Scut Absolut: Interzice cu desăvârșire ruperea textului pe parcursul scrierii */
  display: inline-block;         /* Asigură contextul de aliniere obligatoriu pentru pașii animației */
  overflow: hidden;              /* Ascunde literele viitoare până când lățimea maximă se extinde incremental */
  max-width: 0;                  /* Stare inițială latentă: subtitlul începe complet strâns în vidul spațial */
  border-right: 1.5px solid #a4b3c6 !important; /* Micro cursor secundar ce indică procesarea fundalului de date */

  /* TIMP DE AMÂNARE SECVENȚIALĂ: Așteaptă fix 3 secunde terminarea titlului mare înainte de a scrie */
  animation:
    typing-modular 4s steps(55, end) 3s forwards,
    blink 0.75s step-end infinite;
}
```

7. **MODULE 07: CHRONICLE GRID ASSEMBLY & KINETIC MODULES (PANELUL DE CAPITOLE)**

**REZUMAT**: Acest modul configurează rețeaua modulară de pe Puntea de Comandă (`index.html`). El implementează un sistem de grilă bidimensională auto-adaptivă (Grid Layout) care aliniază volumele mari ale expediției. Modulele individuale (cardurile de categorie) utilizează efecte cinematice de levitație verticală (`translateY`) și o reîncărcare cromatică pe spectrul albastru-electric stelar (`--starlight-blue`) la hover, oferind o delimitare structurală curată a continentelor cunoașterii flotei.

- **Selectorul `.main-container` (Scutul Axial al Paginii / The Main Orbit Shield)**
  - **Rolul în context**: Targetează containerul structural master care încapsulează rețeaua de carduri de pe puntea principală.
  - **Misiune**: Impune un plafon de siguranță la lățimea maximă de `1200px` pentru a opri lăbărțarea elementelor pe monitoare foarte mari, centrează automat întreaga structură pe mijlocul ecranului prin marje exterioare (`margin: 0 auto`) și adaugă pernele de aer de `40px` pentru amortizare laterală.

- **Selectorul `.category-grid` (Rețeaua Energetică a Cardurilor / The Category Quantum Grid)**
  - **Rolul în context**: Targetează rețeaua structurală intermediară care susține și aliniază cardurile individuale.
  - **Misiune**: Activează motorul de layout bidimensional Grid. Implementează formula auto-adaptivă modernă `repeat(auto-fit, minmax(300px, 1fr))`, ordonând browserului să recalculeze automat numărul de coloane în funcție de ecranul hardware, eliminând nevoia de Media Queries parazite pe mobil. Fixează un buffer de izolare structurală de `30px` între module (`gap`).

- **Selectorul `.category-card` și `:hover` (Modulul Cyberpunk de Capitol / The Category Card)**
  - **Rolul în context**: Targetează capsulele individuale care reprezintă marile volume ale călătoriei (HTML, CSS, SQL).
  - **Misiune**: Construiește un înveliș din sticlă fumurie Solaris semi-transparentă cu blur cinematic ridicat de `15px` și o bordură micro-fină albă de siguranță. La hover, execută o ridicare cinetică pe verticală (`transform: translateY(-8px)`) și o încărcare electrică prin `box-shadow` dublu pe lungimea de undă albastru-electric stelar (`--starlight-blue`).

- **Selectorul `.category-card h3` și `p` (Telemetria Internă a Cardului)**
  - **Rolul în context**: Targetează componentele text de titlu și descriere din interiorul fiecărei capsule.
  - **Misiune**: Titlul `h3` aprinde volumul pe verde-mentă de scanare stabilă (`--solar-mint`) cu o spațiere tehnică de `1px`. Paragraful `p` încarcă albul desaturat industrial stardust anti-oboseală și deține o directivă de aur: `flex-grow: 1`. Aceasta forțează textul să ocupe elastic tot spațiul liber din card, împingând butoanele de acces jos, la același nivel simetric perfect, indiferent de lungimea textului narativ.

- **Selectorul `.category-card .btn` și `:hover` (Butonul Intern de Portal / The Module Link)**
  - **Rolul în context**: Targetează elementul ancoră de acces din subsolul fiecărui card de volum.
  - **Misiune**: Își limitează lățimea strict la textul său (`align-self: flex-start`), elimină fundalul solid și desenează un cadru rigid albastru-stelar. La hover, execută o inversare cromatică completă: fundalul devine albastru electric stabil, textul trece în negru profund (`--space-dark`) pentru un contrast militar maxim, protejat de o aureolă laser fină.

```
/* ==========================================================================
   MODULE 07: GRID ASSEMBLY & KINETIC MODULES (PANELUL DE CAPITOLE)

   REZUMAT: Acest modul configurează rețeaua modulară de pe Puntea de Comandă
   (index.html). El implementează un sistem de grilă bidimensională auto-adaptivă
   (Grid Layout) care aliniază volumele mari ale expediției. Modulele individuale
   (cardurile de categorie) utilizează efecte cinematice de levitație verticală
   (translateY) și o reîncărcare cromatică pe spectrul albastru-electric stelar
   (starlight-blue) la hover, oferind o delimitare structurală curată.
   ========================================================================== */

/* --- 1. CONTAINERUL AXIAL AL PAGINII (The Main Orbit Shield) --- */
.main-container {
  max-width: 1200px;             /* Scut anti-întindere: previne lărgirea excesivă pe monitoare desktop mari */
  margin: 0 auto;                /* Centrează automat întreaga structură tehnică pe mijlocul axei ecranului */
  padding: 40px;                 /* Pernă de aer interioară generoasă pentru protecția granițelor modulelor */
  box-sizing: border-box;        /* Forțează padding-ul în calculul lățimii, blocând overflow-ul structural */
}

/* --- 2. REȚEAUA ENERGETICĂ A CARDURILOR (The Category Quantum Grid) --- */
.category-grid {
  display: grid;                 /* Activează subsistemul bidimensional modern Grid Layout */

  /* FORMULA AUTO-RESPONSIVE: Creează automat coloane cu o lățime minimă de 300px.
     Dacă spațiul ecranului scade, cardurile se reașază singure pe verticală, eliminând query-urile media. */
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;                     /* Lasă o distanță fizică fixă de 30px între module (orizontal și vertical) */
  margin-top: 40px;              /* Spațiu protector de siguranță sub titlul principal al paginii */
}

/* --- 3. MODULUL INDIVIDUAL DE CAPITOL (The Cyberpunk Category Card) --- */
.category-card {
  background: var(--panel-bg);   /* Fundalul translucid de sticlă fumurie stabilizată (Stil de bord Solaris) */
  backdrop-filter: blur(15px);   /* Filtrare cinematică: estompează conținutul din spate pentru adâncime de terminal */
  border: 1px solid var(--module-border); /* Chenar micro-fin inițial din fir de oțel alb opac discret */
  border-radius: 4px;            /* Rotunjire minimalistă la colțuri, asortată cu întreaga interfață */
  padding: 30px;                 /* Spațiu interior generos pentru a nu sufoca fluxul textului din module */
  display: flex;                 /* Activează sistemul Flexbox pe interiorul cardului pentru alinierea capsulei */
  flex-direction: column;        /* Așază componentele din card (titlu, text, buton) în mod rigid pe verticală */

  /* HARTĂ CINEMATICĂ CUBIC-BEZIER: Controlează ridicarea și iluminarea cardului într-o tranziție fluidă */
  transition:
    transform 0.3s cubic-bezier(0.4, 0, 0.2, 1),
    border-color 0.3s cubic-bezier(0.4, 0, 0.2, 1),
    box-shadow 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  position: relative;            /* Context de poziționare local pentru eventuale etichete interne de interfață */
}

/* EFECT LA HOVER PESTE CARD: Modulul se ridică fizic și se încarcă electric cu energie albastru-stelar */
.category-card:hover {
  transform: translateY(-8px);   /* RIDICAREA KINETICĂ: Împinge fizic cardul în sus cu 8px, creând iluzia de zbor */
  border-color: var(--starlight-blue); /* Chenarul micro-fin devine instantaneu albastru electric stelar */

  /* SCUT DE IMPULS NEON: Generează o umbră exterioară luminoasă dublă de culoare albastru electric */
  box-shadow:
    0 10px 25px rgba(0, 210, 255, 0.15),
    0 0 15px rgba(0, 210, 255, 0.1);
}

/* --- 4. CONFIGURAȚIA TELEMETRIEI INTERNE A CARDULUI (Alinierea datelor din interior) --- */
.category-card h3 {
  font-size: 1.3rem;             /* Dimensiune optimizată pentru titlul de volum macro (HTML, CSS, SQL) */
  margin-top: 0;                 /* Resetează marja nativă a browserului pentru a alinia coordonata superioară */
  margin-bottom: 15px;           /* Împinge paragraful descriptiv în jos pentru o urmărire vizuală echilibrată */
  color: var(--solar-mint);      /* Aprinde titlul de volum pe verde-mentă de scanare stabilă de sistem */
  letter-spacing: 1px;           /* Spațiere tehnică fină industrială între caractere corporate */
}

.category-card p {
  font-size: 0.95rem;            /* Dimensiune redusă, fină, ideală pentru descrierea narativă din jurnale */
  color: var(--stardust);        /* Text alb industrial stardust ce maximizează definiția literelor de bază */
  line-height: 1.6;              /* Raport optim între rânduri pentru o citire fluidă a cronicilor de studiu */
  margin-bottom: 25px;           /* Lasă un spațiu clar de siguranță deasupra butonului de acces de mai jos */

  /* REGULA FLUIDĂ CRUCIALĂ: Forțează paragraful să consume tot spațiul vertical liber din card.
     Aceasta garantează că toate butoanele de acces se vor alinia pe o axă orizontală perfect simetrică. */
  flex-grow: 1;
}

/* --- 5. BUTONUL INTERN DE PORTAL ACCES (Link-ul Secundar din Subsol) --- */
.category-card .btn {
  align-self: flex-start;        /* Împiedică butonul să se întindă pe tot cardul, limitându-l la dimensiunea textului */
  background: transparent;       /* Elimină fundalul solid, lăsând sticla translucidă a cardului vizibilă sub text */
  border: 1px solid var(--starlight-blue); /* Chenar rigid inițial ce marchează granița de control secundară */
  color: var(--starlight-blue);  /* Text aprins pe albastru stelar ce indică o rută de acces activă */
  font-size: 0.8rem;             /* Dimensiune tehnică minimalistă conform specificațiilor HUD */
  text-transform: uppercase;     /* Litere mari obligatorii pentru un aspect rigid de protocol militar */
  letter-spacing: 2px;           /* Spațiere largă industrială între caractere pentru aspect premium */
  padding: 10px 20px;            /* Umplutură internă compactă ce asamblează un dreptunghi tactil precis */
  border-radius: 3px;            /* Rotunjire fină la colțuri asortată cu blueprint-urile interfeței */
  text-decoration: none;         /* Elimină sublinierea nativă implicită a link-urilor HTML */
  transition: all 0.3s ease;     /* Tranziție rapidă de răspuns pentru gestionarea momentului interactiv */
}

/* INVERSARE CROMATICĂ LA HOVER PESTE PORTAL: Capsula se aprinde complet în nuanța stelar-albastră */
.category-card .btn:hover {
  background: var(--starlight-blue); /* Fundalul se aprinde complet în radiație albastru-electric stelar */
  color: var(--space-dark);      /* Forțează textul în negru profund, maximizând lizibilitatea pe placa aprinsă */
  box-shadow: 0 0 12px rgba(0, 210, 255, 0.4); /* Adaugă o mică aură laser la confirmarea prin atingere */
}

```

9. MODULE 08: AIRLOCK SECTORS & CONTENT VAULTS (PROFILUL DE JURNAL)

Acest modul mută atenția de pe ecranul principal pe structura internă a paginilor de jurnal, organizând transmisiile narative și datele tehnice în compartimente securizate.

- Selectorul `.log-layout` (Matricea Macro de Jurnal)
  - **Rolul în context**: Targetează containerul suprem al paginilor de loguri, definind lățimea maximă a punții de documentare.
  - **Misiune**: Interzice layout-ului să depășească ecranul hardware

- Selectorul `.sector-announcement` (Porțile Airlock Violet)
  - **Rolul în context**: Targetează casetele mari de demarcație care anunță intrarea într-un nou volum sau capitol de studiu.
  - **Misiune**: Izolează masiv capitolele pe verticală, impune un chenar dublu de culoare violet cosmic (`--nebula-purple`) și activează o barieră de scroll de `150px` pentru a opri poziționarea fix sub navbar.

- Selectorul `.sector-announcement span` și `h2` (Etichetele Porții)
  - **Rolul în context**: Țintesc numărul sectorului și titlul curat din interiorul casetei etanșe violet.
  - **Misiune**: Elementul `span` se aprinde pe chihlimbar retro (`--amber-glow`) cu majuscule și spațiere largă de `5px`. Elementul `h2` este purificat de sublinierile roz standard din Modulul 03.

- Selectorul `.mission-status` (Panoul de Control al Stării)
  - **Rolul în context**: Targetează caseta încapsulată care rulează textul dinamic de diagnosticare.
  - **Misiune**: Injectează un fundal de 5% verde-mentă și solidifică o bară verticală laser pe flancul stâng (`border-left: 3px solid var(--solar-mint)`).

- Selectorul `.mission-status p` (Telegraful Fosforic Unificat)
  - **Rolul în context**: Targetează textul unificat verde-mentă supus efectului de typing din JavaScript.
  - **Misiune**: Rulează un set de trei animații corelate (`typing-modular`, `blink`, `hide-cursor`), deschizând oblonul `max-width` și ascunzând cursorul după exact 3.5 secunde, menținând textul pe o șină orizontală strictă (`white-space: nowrap`).

- Selectorul `.log-text` și `.log-text p:first-of-type::first-letter` (Motorul Narativ și Drop-Cap-ul)
  - **Rolul în context**: Reglează paragrafele mari de poveste și prima literă a textului din jurnal.
  - **Misiune**: Aliniază textul compact stânga-dreapta (`text-align: justify`) cu un line-height generos de `1.8`. Prima literă (Drop-Cap) explodează pe verticală la `2.2rem`, se aprinde în roz-neon (`--nebula-pink`) și glisează la stânga.

- Selectorul `.log-entry` și `.log-entry p` (Caseta Monitor a Zilei)
  - **Rolul în context**: Targetează containerul macro al unei zile întregi din jurnal (Carcasa de log).
  - **Misiune**: Creează adâncime de monitor vechi prin umbre interioare dense (`box-shadow: inset 0 0 30px rgba(0,0,0,0.5)`), atașează o bară verticală verde pe stânga și adaugă scutul suprem `overflow-x: hidden` care unifică și anihilează repetițiile greșite din Modulul 11.

- Selectorii Componentelor Semantice (`.semantic-module`, `.tag-name`, `.tag-meta`, `.tag-description`)
  - **Rolul în context**: Stilizează micro-blocurile destinate explicării etichetelor HTML (definițiile de taguri).
  - **Misiune**: Ancorează o linie laser roz în stânga (`border-left: 2px solid var(--nebula-pink)`), aprind numele tagului în verde fosforic cu o aureolă neon difuză (`text-shadow`) și izolează metadatele pe o frecvență secundară roz.

```
/* ==========================================================================
    MODULE 08: AIRLOCK SECTORS & CONTENT VAULTS (JOURNAL PROFILE SHIELD)

    REZUMAT: Acest modul stabilește cadrul de layout și capsulele structurale
    dedicate cronicilor de zbor. El configurează porțile etanșe cu chenar dublu
    violet ce separă capitolele, ancorează bara dinamică de stare a misiunii cu
    efecte de neon, standardizează tipografia narativă (inclusiv drop-cap-ul cinematic)
    și impune carcase de izolare rigide, anti-overflow, pe casetele logurilor zilnice.

    REZUMAT: Acest modul construiește porțile macro vizuale care separă capitolele
    jurnalelor de navigație și consolidează panourile locale de stare în timp real.
    El configurează porțile de securitate cu chenar dublu violet și ancorează
    consola verde-mentă .mission-status ce rulează animații asincrone de scriere.
   ========================================================================== */

/* --- 1. CONFIGURAȚIA MACRO A PAGINII DE LOG (The Quantum Bridge Layout) --- */
.log-layout {
  max-width: 100vw;             /* Împiedică layout-ul mare să depășească lățimea fizică a ecranului hardware */
  margin: 0 auto;                /* Centrează automat structura pe mijlocul ecranului și pe axa monitorului */
  box-sizing: border-box;        /* Include padding-ul în dimensiuni pentru a bloca deformările generale de layout */
}

/* --- 2. PORȚILE DE TIP AIRLOCK (The Sector Announcements) --- */
/* Casete mari ce anunță intrarea într-un nou sector de studiu (ex: Sector 01: The Hull) */
.sector-announcement {
  margin: 100px 0;               /* Lasă o distanță uriașă pe verticală, izolând capitolele ca niște camere etanșe */
  padding: 40px;                 /* Spațiu interior generos pentru ca textul militar de alertă să aibă aer în panou */
  border: 1px double var(--nebula-purple); /* Chenar dublu în nuanța violet cosmic (nebula-purple) pentru finisaj industrial */
  background: rgba(60, 44, 140, 0.05); /* Fundal fin, o reflexie de 5% din energia violet a nebuloasei centrale */
  position: relative;            /* Permite elementelor decorative interne să plutească raportat la acest cadru */
  text-align: center;            /* Centrare absolută a textelor din interior pentru un echilibru cinematic stabil */

  /* BARIERA MECANICĂ DE SCROLL: Când sari la sector, se oprește la 150px distanță ca să nu fie acoperit de HUD-ul fix */
  scroll-margin-top: 150px !important;

  /* EXECUȚIA ANIMAȚIEI VIOLET: Rulează de 3 ori la încărcare (pulsare fină) și îngheață în starea finală luminoasă */
  animation: border-pulse-purple 2.5s ease-in-out 3 alternate forwards;
}

/* TEXTUL INTRODUCTIV PRINCIPAL DIN PORȚILE AIRLOCK */
.sector-announcement h3 {
  font-size: 1.4rem;             /* Dimensiune impunătoare unificată pentru titlul principal al noului sector */
  color: var(--solar-mint);      /* Textul se aprinde stabil pe verde-mentă fosforic de scanare activă radar */
  margin-top: 0;                 /* Șterge marginile superioare implicite injectate parazit de browsere */
  margin-bottom: 10px;           /* Împinge subtitlul narativ în jos pentru o ierarhie tehnică curată */
  letter-spacing: 3px;           /* Spațiere largă între caractere, specifică alertelor de pe monitoarele navelor */
  text-transform: uppercase;     /* Litere mari obligat-militare pentru un aspect de protocol oficial de bord */
}

/* ETICHETA DECOARATIVĂ EXPLICATIVĂ COBORTĂ DEASUPRA TITLULUI */
.sector-announcement span {
  font-family: monospace;        /* Font rigid fixat mecanic de cod, specific terminalelor analogice */
  color: var(--amber-glow);      /* Chihlimbar retro: rezervat alertelor de sistem și indicatorilor industriali */
  font-size: 0.8rem;             /* Dimensiune minimalistă compactă pentru datele secundare de pe ecran */
  letter-spacing: 5px;           /* Spațiere foarte largă între caractere pentru a simula un overlay cinematic SF */
  text-transform: uppercase;     /* Protocol tehnic obligatoriu de litere mari în interiorul indicatorului */
  display: block;                /* Îl transformă în bloc structural ca să stea singur pe rând, deasupra titlului h3 */
  margin-bottom: 10px;           /* Distanță fină de siguranță sub text înainte de nucleul titlului */
}

/* RESETAREA CONFIGURAȚIEI TITLURILOR GENERALE DIN INTERIOR */
.sector-announcement h2 {
  margin: 0;                     /* Resetează complet marginile nativ-parazite ale browserului în casetă */
  border: none;                  /* Șterge bordura roz standard a h2-ului general pentru a lăsa poarta izolată */
}

/* LINIA DE TEXT DESCRIERE SAU METADATE DIN AIRLOCK */
.sector-announcement p {
  font-size: 0.95rem;            /* Dimensiune tehnică fină optimizată pentru scanarea rapidă a datelor */
  color: var(--stardust);        /* Alb industrial stardust stabil și curat, conceput împotriva oboselii ochilor */
  margin: 0;                     /* Resetează marjele inferioare pentru a proteja limitele geometrice ale casetei */
  letter-spacing: 1px;           /* Spațiere fină elegantă între caractere ce stabilizează frazele descriptive */
}

/* --- 3. PANOUL DE CONTROL AL MODULULUI (The Mission Status Bar) --- */
/* Caseta verde-mentă transclucidă care conține textul de stare tehnică a misiunii active */
.mission-status {
  background: rgba(167, 243, 208, 0.05) !important; /* Umbră ultra-fină translucidă de 5% din energia verde-mentă */
  border-left: 3px solid var(--solar-mint); /* Linie verticală rigidă în stânga care acționează ca o barieră fixă de radar */
  padding: 12px 20px;            /* Umplutură internă compactă militară pentru a încadra stabil textul tehnic */
  margin-bottom: 35px;           /* Împinge textul jurnalului mai jos pentru a preveni suprapunerile vizuale */
  border-radius: 0 4px 4px 0;    /* Rotunjește doar colțurile din dreapta, păstrând stânga ancorată fix în axa laser */
}

/* --- 4. MOTORUL DE TELEMETRIE CU TYPEWRITER ASINCRON (Textul Viu de Terminal) --- */
.mission-status p {
  margin: 0;                     /* Resetează marginile parazite pentru a asigura alinierea perfectă în consolă */
  font-family: monospace;        /* Font rigid mecanic fix de cod, specific mașinilor de scris analogice */
  font-size: 0.85rem;            /* Dimensiune tehnică fină de interfață de diagnostic computerizat */
  text-transform: uppercase;     /* Protocol militar obligatoriu: forțează utilizarea literelor mari */
  color: var(--solar-mint) !important; /* Unificare totală a textului pe frecvența verde-mentă fosforică */
  text-shadow: 0 0 6px rgba(167, 243, 208, 0.5) !important; /* Generează o aură intensă de neon verde în spatele literelor */
  letter-spacing: 2px !important; /* Spațiere tehnică stabilă largă ce oferă ritm vizual liniilor de script */

  /* LĂCĂTUIREA REGLAJULUI DE INDENTARE CURSOR */
  width: max-content;            /* Obligă caseta să aibă EXACT lungimea textului scris, lipind cursorul de litere */
  max-width: 0;                  /* Stare inițială latentă: textul pornește complet ascuns de la lățime zero */
  white-space: nowrap;           /* SCUT DE DISPUNERE: Interzice textului să se spargă sau să stivuiască pe verticală la scriere */
  overflow: hidden;              /* Ascunde literele viitoare până când pașii animației extind dimensiunea orizontală */
  border-right: 2px solid var(--solar-mint); /* Linia fizică a cursorului mecanic vertical care pâlpâie la capătul textului */

  /* DECLANȘAREA ANIMAȚIILOR RECURSIVE CU AUTO-STINGERE SINCRONIZATĂ */
  /* Derulează oblonul max-width prin typing-modular, activează clipirea cursorului la infinit,
     și rulează 'hide-cursor' la secunda 3.5 pentru a stinge instantaneu linia verticală fosforică. */
  animation:
    typing-modular 3.5s steps(40, end) forwards,
    blink 0.75s step-end infinite,
    hide-cursor 0s linear 3.5s forwards;
}

```

9. MODULE 09: QUANTUM TERMINAL VAULTS & ENERGY GRID LINES (SISTEME DE SALVARE)

După stabilirea structurii generale de jurnal (Modulul 09) și pregătirea bibliotecii atomice din Modulul 11, cascada stilistică asamblează **sistemul local de stocare de date și notițe (The Note Terminal Console)**. Acest modul configurează o casetă izolată, compactă, protejată de o rază laser dinamică și o mască de fundal militară.

- **Selectorul `.note-terminal` (Caseta Generală a Monitorului de Hacking)**
  - **Rolul în context**: Targetează containerul macro (`<div class="note-terminal">`) în care echipajul își notează observațiile de bord.
  - **Misiune**: Creează o placă de monitor cu fundal negru profund (`#05070a`), încadrată de o bordură fină verde-mentă la 20% opacitate. Injectează o umbră interioară fosforică discretă de `15px` combinată cu o umbră densă exterioară de `30px`, creând un aspect tridimensional de ecran CRT bombat separat de vidul structural.

- **Selectorul Pseudo-Element `.note-terminal::before` (Raza Laser de Scanare Orizontală)**
  - **Rolul în context**: Generează o fâșie virtuală de energie laser poziționată absolut deasupra ecranului monitorului.
  - **Misiune**: Proiectează o rază subțire de `3px` înălțime formată dintr-un gradient verde-mentă intens la centru și stins spre margini, amplificată de o strălucire de neon (`box-shadow`). Rulează o animație continuă pe axa verticală (`animation: laser-scan 4s linear infinite`), măturând ecranul de sus în jos fără a bloca acțiunile mouse-ului (`pointer-events: none`).

- **Selectorul Pseudo-Element `.note-terminal::after` (Indicatorul de Status de pe Fundal)**
  - **Rolul în context**: Injectează automat un șir discret de text tehnic în colțul din dreapta-jos al monitorului de hacking.
  - **Misiune**: Aliniază static textul `"SYS_STATUS: READY_TO_WRITE //"` pe o dimensiune de `0.65rem` cu opacitate de 25% verde-mentă, transformându-l într-o etichetă pur structurală de diagnostic, protejată contra selectării accidentale de text (`pointer-events: none`).

- **Selectorul `.note-terminal textarea` (Caseta Interactivă de Introducere Date)**
  - **Rolul în context**: Targetează elementul nativ de introducere text de tip textarea încastrat în monitor.
  - **Misiune**: Elimină complet fundalul alb nativ, bordurile și chenarul albastru de focus al browserului (`outline: none`), permițând literelor scrise manual să lumineze direct în verde-mentă fosforic stelar (`var(--solar-mint)`) sub fontul rigid de mașină de scris `Courier New`. Interzice total tragerea manuală de colț (`resize: none`) pentru a proteja layout-ul.

- **Selectorul `.note-terminal button, .save-btn` și `:hover` (Butonul de Salvare Protocol)**
  - **Rolul în context**: Targetează link-ul/butonul de evacuare energetică plasat la baza textarea-ului.
  - **Misiune**: În repaus, dezactivează fundalul solid și desenează un chenar rigid roz-magenta intens (`--nebula-pink`). La hover, inversează cromatic spectrul: absoarbe o reflexie de 15% energie roz în interior, extinde o umbră dublă de neon roz de `15px` și aprinde o aureolă luminoasă difuză în jurul literelor (`text-shadow`), confirmând securizarea datelor.

- **Selectorul `.appendix-list` și `li` (Rețeaua de Anexe Tehnice)**
  - **Rolul în context**: Targetează listele de sub-puncte sau note secundare plasate adiacent terminalului.
  - **Misiune**: Impune o indentare curată de `20px` la stânga pentru aliniere axială perfectă, o dimensiune fină de text (`0.95rem`) pe nuanța stardust și o distanță verticală discretă de `8px` între rânduri pentru a elibera spațiul vizual.

```
/* ==========================================================================
    MODULE 09: QUANTUM TERMINAL VAULTS & ENERGY GRID LINES (SISTEME DE SALVARE)

    REZUMAT: Acest modul construiește interfața interactivă de înregistrare a datelor
    (Consola Terminalului de Notițe). El definește o placă izolată de ecran cu fosfor
    întunecat, rulează o rază laser orizontală continuă de scanare verticală (::before)
    peste limitele monitorului, injectează etichete automate de telemetrie (::after)
    și gestionează învelișurile structurale pentru casetele textarea și butoanele de salvare.
   ========================================================================== */

/* --- 1. CASETA GENERALĂ A TERMINALULUI (The Core Hacking Monitor) --- */
.note-terminal {
  margin: 40px 0;                /* Lasă un spațiu generos pe verticală de 40px deasupra și dedesubtul terminalului */
  position: relative;            /* Deschide context de poziționare pentru textul de status (SYS_STATUS) din fundal */
  background: #05070a;           /* Negru profund oarbă, specific monitoarelor fosforice vechi de pe nave */
  border: 1px solid rgba(167, 243, 208, 0.2); /* Chenar micro-fin inițial din culoarea verde-mentă la 20% opacitate */
  border-radius: 4px;            /* Rotunjire fină la colțuri, perfect aliniată cu restul interfeței generale */
  padding: 20px;                 /* Pernă de aer interioară pentru ca textul tastat să nu lovească marginile ecranului */

  /* EFECTUL DE ECRAN BOMBAT: Creează o iluminare internă discretă de 5% și o umbră exterioară densă */
  box-shadow:
    inset 0 0 15px rgba(167, 243, 208, 0.05),
    0 10px 30px rgba(0, 0, 0, 0.6);
  transition: border-color 0.3s ease; /* Pregătește o tranziție lină a chenarului la interacțiunea cu operatorul */
}

/* Încărcare energetică la hover: Cadrul se aprinde pe masca verde-mentă */
.note-terminal:hover {
  border-color: rgba(167, 243, 208, 0.4); /* Intensifică opacitatea chenarului verde-mentă la o valoare de 40% */
}

/* --- 2. EFECTUL DE SCANARE LASER ORIZONTAL PESTE MONITOR --- */
.note-terminal::before {
  content: "";                   /* Generează stratul virtual al razei laser în arborele structural al panoului */
  position: absolute;
  top: 0; left: 0;
  width: 100%;
  height: 3px;                   /* Grosimea fizică a razei laser de măturare */

  /* FAȘĂ GRADIENT RADIAL: Pornește din opacitate 0, se aprinde pe verde-mentă la centru și dispare la margini */
  background: linear-gradient(
    90deg,
    rgba(167, 243, 208, 0) 0%,
    rgba(167, 243, 208, 0.4) 50%,
    rgba(167, 243, 208, 0) 100%
  );
  box-shadow: 0 0 10px var(--solar-mint); /* Strălucire puternică de neon fluorescent în jurul liniei orizontale */
  opacity: 0.7;
  pointer-events: none;          /* PRO-UX: Elementul rămâne pur vizual, permițând click-urilor să treacă fără blocaje */
  z-index: 5;

  /* DECLANȘAREA DIRECTĂ A RADARULUI: Declanșează animația continuă de scanare verticală definită în Modulul 00.1 */
  animation: laser-scan 4s linear infinite;
}

/* --- 3. INDICATOR PENTRU STATUSUL DE PE FUNDAL (The System Telemetry Label) --- */
.note-terminal::after {
  content: "SYS_STATUS: READY_TO_WRITE //"; /* Mesajul de diagnostic generat automat pe sticla monitorului */
  position: absolute;            /* Scoatere din flux pentru a fi lipit în colț independent de textul introdus în textarea */
  bottom: 8px;                   /* Aliniere fixă la 8px față de podeaua inferioară a casetei */
  right: 20px;                   /* Aliniere fixă la 20px față de marginea din dreapta (tribord) */
  font-family: monospace;        /* Font rigid mecanic de cod ce reproduce aspectele textelor de diagnostic */
  font-size: 0.65rem;            /* Dimensiune micro-fină liliputană, specifică detaliilor de pe radarele de bord */
  color: rgba(167, 243, 208, 0.25); /* Verde-mentă stins la 25% opacitate pentru a asigura contrastul de fundal stins */
  letter-spacing: 1px;           /* Spațiere fină între caractere ce stabilizează denumirile tehnice */
  pointer-events: none;          /* PRO-UX: Interzice cursorului mouse-ului să agațe sau să selecteze textul decorativ */
}

/* --- 4. CASETA INTERACTIVĂ DE INTRODUCERE DATE (The Textarea Screen) --- */
.note-terminal textarea {
  width: 100%;                   /* Se întinde pe toată lățimea utilă din interiorul monitorului hardware */
  height: 120px;                 /* Înălțime fixă rigidă optimizată pentru notițele rapide în jurnalul de bord */
  background: transparent;       /* Elimină fundalul alb nativ al browserului, lăsând negrul profund `#05070a` vizibil */
  border: none;                  /* Șterge complet granițele sau marginile structurale native ale casetei */
  outline: none;                 /* Anulează inelul albastru inestetic pe care browserele îl aplică automat la click focus */
  color: var(--solar-mint);      /* Caracterele tastate se vor aprinde direct pe frecvența verde-mentă fosforică */
  font-family: "Courier New", Courier, monospace; /* Font rigid fixat mecanic specific mașinilor de scris analogice */
  font-size: 0.9rem;             /* Dimensiune optimizată pentru păstrarea definiției codului de înalt contrast */
  line-height: 1.6;              /* Aerisire corectă și spațiu generos între rânduri în timpul introducerii datelor */
  letter-spacing: 1px;           /* Spațiere fină tehnică stabilă între literele cuvintelor */
  resize: none;                  /* REGULĂ PRO-LAYOUT IMPRESCINDIBILĂ: Interzice tragerea de colț pentru protecția layout-ului */
  box-sizing: border-box;        /* Include padding-ul în dimensiuni pentru a bloca apariția erorilor de overflow */
}

/* --- 5. BUTON DE SALVARE PROTOCOL (The Save Signal Button) --- */
.note-terminal button,
.save-btn {
  background: transparent;       /* Fundal curat transparent ce lasă vizibilă sticla neagră a monitorului dedesubt */
  border: 1px solid var(--nebula-pink); /* Chenar rigid inițial din fir laser roz-magenta intens (stare de alertă) */
  color: var(--nebula-pink);     /* Literele luminează pe lungimea de undă roz de alertă pentru semnalizare rapidă */
  font-family: monospace;        /* Font rigid mecanic fix ce păstrează estetica generală de terminal industrial */
  font-size: 0.75rem;            /* Dimensiune tehnică redusă, specifică scurtăturilor din panourile HUD */
  text-transform: uppercase;     /* Protocol militar obligatoriu: forțează utilizarea literelor mari pe butoane */
  padding: 8px 22px;             /* Umplutură internă compactă ce asamblează un dreptunghi tactil precis și simetric */
  letter-spacing: 2px;           /* Spațiere largă tehnică între caractere pentru un aspect aerisit și premium */
  cursor: pointer;               /* Schimbă profilul cursorului într-o mână activă pentru a valida interactivitatea */
  border-radius: 3px;            /* Rotunjire minimalistă la colțuri asortată cu blueprint-urile interfeței */
  margin-top: 10px;              /* Distanță fină superioară de siguranță izolând butonul de caseta textarea de deasupra */
  display: inline-block;         /* Convertește elementul în inline-block pentru a respecta padding-ul dreptunghiular */

  /* CUBIC-BEZIER INDUSTRIAL: Controlează inversarea cromatică și umbrele duble într-o tranziție cinematică */
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

/* EFECT DE SUPRASARCINĂ LA HOVER PESTE BUTON: Capsula absoarbe energie și explodează în neon roz */
.note-terminal button:hover,
.save-btn:hover {
  background: rgba(255, 0, 127, 0.15); /* Nucleul capsulei absoarbe o reflexie de 15% din intensitatea laserului roz */

  /* SCUT DE ENERGIE IMPLODATĂ: Generează o umbră fluorescentă dublă puternică (interioară și exterioară) roz */
  box-shadow:
    0 0 15px rgba(255, 0, 127, 0.4),
    inset 0 0 5px rgba(255, 0, 127, 0.2);
  text-shadow: 0 0 5px var(--nebula-pink); /* Adaugă o aureolă luminoasă fină de neon în jurul textului capitalizat */
}

/* --- 6. REȚEAUA DE LISTE DE ANEXE TEHNICE (The Appendix Sub-Lists) --- */
.appendix-list {
  padding-left: 20px;            /* Creează o indentare curată pe orizontală în stânga pentru alinierea sub-punctelor */
  margin: 15px 0;                /* Distanță verticală de siguranță izolând lista de restul modulelor vecine */
}

.appendix-list li {
  font-size: 0.95rem;            /* Dimensiune fină secundară, optimizată pentru listele lungi de note tehnice */
  color: var(--stardust);        /* Alb industrial stardust conceput împotriva oboselii ochilor în timpul citirii */
  margin-bottom: 8px;            /* Pernă de aer verticală discretă ce împiedică elementele listei să se lipească */
  position: relative;            /* Deschide context local de coordonate pentru eventuale micro-glife decorative */
}
```

10. **Modulul 10 (Modular Technical Vaults)**

10.1. **SUB-MODULE 10.1: THE JOURNAL FOUNDATIONS/NARAȚIUNEA ȘI LETTERING-UL (Narațiunea generală `.log-text `și Letrina roz)**

**REZUMAT / SUMMARY**: This sub-module establishes the genetic text engine for the flight logs. It normalizes paragraph text flow for high-contrast dark reading grids and implements the historical pink drop-cap on opening characters to define visual entry protocols.

- **Selectorul `.log-text` (Zona Textului Narativ General)**
  - **Rolul în context**: Targetează blocurile mari de text narativ și cronicile tehnice de pe toate paginile de jurnale.
  - **Misiune**: Impune o aliniere simetrică perfectă de tip carte (`text-align: justify`), încarcă albul desaturat industrial stardust anti-oboseală și deblochează un coeficient aerisit de `1.8` pe înălțimea rândurilor, eliminând riscul ca rândurile lungi de lectură să se sufoce vizual.

- **Selectorul Pseudo-Element `.log-text > p:first-of-type::first-letter` (Letrina/Drop Cap -> Ștampila Monolit Jet-Age)**
  - **Rolul în context**: Targetează exclusiv primul caracter din deschiderea jurnalelor de bord, acționând ca un punct zero de inițializare a datelor.
  - **Misiune**: Închide litera într-o capsulă pătrată rigidă cu fundal închis (`#0d0f14`), flancată la stânga de o barieră laser roz solid de `3px`. Forțează alinierea pe centrul casetei, aplică o micro-umbră de neon roz și decupează caracterul sub fontul rigid de cockpit (`var(--font-main)`), lăsând textul narativ să curgă curat în jurul acestei piese industriale.

    10.2. **SUB-MODULE 10.2: THE CHRONICLE VAULTS (Capsulele `.log-entry` desktop/mobil și Corecțiile Semantice de Taguri)**

După izolarea elementelor macro de narațiune simplă și a glifului monolit din deschidere (Sub-Modulul 11.1), cascada avansează în profunzimea jurnalelor pentru a structura **mecanica vizuală a casetei de zi și cronicile de taguri**. Acest sector optimizează ierarhia elementelor interactive, garantând o citire fluidă și protejând layout-ul de erori de revărsare pe rezoluții strâmte.

- Selectorul `.log-entry` (Caseta Jurnalului de Zi / The Entry Screen Vault)
  - **Rolul în context**: Targetează containerul macro al unei zile de jurnal (`<article class="log-entry">`), acționând ca un panou fizic sau un ecran de monitor individual ce încapsulează rapoartele tehnice zilnice.
  - **Misiune**: Construiește un înveliș din sticlă Solaris semi-transparentă cu padding generos de `2.5rem` și o umbră interioară densă de `30px` ce simulează curbura fizică a monitoarelor catodice. Flanchează marginea stângă printr-o barieră stabilă verde-mentă de `5px` (`border-left`) și maschează orice revărsare prin `overflow: hidden`.

- Selectorul `.log-entry:hover` (Suprasarcina Kinetică a Casetei)
  - **Rolul în context**: Targetează starea pseudo-clasică de interacțiune în momentul în care cursorul echipajului intersectează coordonatele unei capsule de zi.
  - **Misiune**: Trezește panoul la viață: execută o ridicare fină pe verticală (`transform: translateY(-3px)`), propagă o tentă fină de 5% mentă pe tot fundalul sticlei și mărește intensitatea fluorescenței interioare și exterioare a neonului.

- Selectorul `.log-entry p` (Paragrafele Interioare din Jurnal)
  - **Rolul în context**: Targetează blocurile de text narativ tehnic plasate exclusiv în interiorul capsulelor de zi.
  - **Misiune**: Scade subtil dimensiunea fontului la `0.95rem` pe o nuanță de gri stardust opacizat pentru a proteja lizibilitatea. Impune o aliniere compactă de tip carte (`text-align: justify`) și încarcă un scut triplu anti-deformare absolută: `overflow-wrap: break-word`, `word-wrap: break-word` și `hyphens: auto`.

- Selectorul `.log-entry h3` (Alinierea Antetului de Zi / Symmetrical Header Track)
  - **Rolul în context**: Targetează titlul de rang 3 care guvernează partea superioară a fiecărei capsule zilnice (unde scrie numărul zilei și titlul misiunii).
  - **Misiune**: Activează motorul Flexbox orizontal (`display: flex`) și impune o distribuție simetrică ideală: împinge numărul zilei aprins în roz-neon (`--nebula-pink`) în stânga extremă și metadatele în dreapta extremă (`justify-content: space-between`), adăugând o linie fină de demarcație la bază.

- Selectorul `.semantic-module` (Caseta de Definiții Tehnice / Syntax Terminal)
  - **Rolul în context**: Targetează secțiunile care izolează vizual explicarea tagurilor HTML (cum se întâmplă în _Day 03_).
  - **Misiune**: Creează o zonă tampon prin marje exterioare verticale de `25px` și flanchează marginea stângă printr-o linie laser solidă roz-magenta de `2px` (`border-left`), lăsând un spațiu interior de `15px` pentru text.

- Selectorul `.tag-name` (Numele Etichetei de Cod / The Syntax Core)
  - **Rolul în context**: Targetează textul care afișează tagul HTML propriu-zis (ex: `<div>`, `<header>`).
  - **Misiune**: Aprinde textul pe frecvența verde-mentă fosforică pură (`--solar-mint`), îi mărește volumul la `1.1rem` sub greutatea textului îngroșat și explodează o aureolă puternică de neon de `8px` prin `text-shadow`.

-Selectorul `.tag-meta` (Metadatele Etichetei / Diagnostic Scripts)

- **Rolul în context**: Targetează atributele sau specificațiile tehnice plasate imediat lângă numele tagului.
- **Misiune**: Comută textul pe culoarea roz de alertă militară, scade dimensiunea la `0.8rem` și impune protocolul de litere mari obligatorii cu o spațiere tehnică de `1px`. Lasă o marjă în stânga de `10px` pentru a nu se lipi de numele tagului.

- Selectorul `.tag-description` (Descrierea Extinsă a Tagului / Block Reset)
  - **Rolul în context**: Targetează textul explicativ așezat la baza fiecărui modul semantic de tag.
  - **Misiune**: Impune o marjă superioară forțată de `8px !important` pentru a împinge textul explicativ pe un rând nou, direct sub antetul format din tag-name și tag-meta.

    10.3. **SUB-MODULE 10.3: THE MATRIX REPOSITORIES (Tabelele `.data-grid` din arhive și bibliografie).**

După securizarea textului narativ (11.1) și a capsulelor de zi (11.2), cascada de stilizare pătrunde în infrastructura tabulară globală a flotei. Acest sector acționează ca o **Librărie Master reutilizabilă** pe toate paginile navetei spațiale, normalizând elementele de tabel și transformând listele inerte de date în radare rigide de citire de înaltă rezoluție.

- Selectorul Grupat `table, .data-grid` (Structura Bazei de Date / The Solaris Database Grid)
  - **Rolul în context**: Targetează elementul master de tabel (`<table>`) utilizat pentru stocarea bibliografiei, a metricilor sau a interogărilor SQL din loguri.
  - **Misiune**: Reinstaurează layout-ul nativ de tabel prin `display: table !important` pentru a forța celulele să se întindă simetric, eliminând spațiile goale inestetice de pe flancul drept. Impune o lățime absolută de `100% !important`, elimină spațiile libere dintre celule (`border-collapse: collapse`) și încarcă sticla fumurie originală la o opacitate de 40% (`rgba(13, 15, 20, 0.4)`). Setează fontul master rigid `var(--font-main)` la dimensiunea tehnică de `0.9rem`.

- Selectorul `th` (Antetele de Coloană Hardware / Hardware Row Headers)
  - **Rolul în context**: Targetează exclusiv celulele de antet de pe primul rând al tabelului (etichetele superioare de coloană: ex: _Sursă_, _Autor_).
  - **Misiune**: Injectează o mască de fundal de tip tentă de 10% verde-mentă (`rgba(167, 243, 208, 0.1)`), aprinde textul îngroșat pe frecvența stabilă verde fosforic (`var(--solar-mint)`) cu aliniere fixă pe stânga, și desenează o barieră laser verde solidă de `2px` la bază (`border-bottom`). Impune majuscule de protocol cu un letter-spacing de `2px`.

- Selectorul `td` (Învelișul Unificat al Celulelor de Date)
  - **Rolul în context**: Targetează toate celulele normale de date din interiorul matricilor tabulare.
  - **Misiune**: Impune un padding simetric perfect de `12px` de jur împrejurul fiecărui text, desenează o linie orizontală micro-fină de demarcație (`border-bottom: 1px solid rgba(255, 255, 255, 0.05)`) și încarcă textul alb stardust opacizat anti-oboseală. Securizează celula contra link-urilor ultra-lungi prin directivele `word-wrap: break-word` și `overflow-wrap: break-word`, forțând totodată textul să facă wrap prin `white-space: normal !important`.

- Selectorul `tr:hover` (Răspunsul Kinetic pe Rând / Proximity Sweep Bar)
  - **Rolul în context**: Targetează starea dinamică a unui întreg rând orizontal (`<tr>`) în momentul în care operatorul trece cu mouse-ul peste el.
  - **Misiune**: Modifică instantaneu fundalul rândului interceptat, forțându-l să absoarbă o reflexie fină de 5% energie verde-mentă (`rgba(167, 243, 208, 0.05) !important`) însoțită de o umbră interioară discretă de neon verde de `10px` (`box-shadow`).

- Selectorul `td::selection` (Selecția de Înaltă Tensiune / Text Highlight Map)
  - **Rolul în context**: Targetează comportamentul textului din celule în momentul în care operatorul selectează manual caracterele cu mouse-ul.
  - **Misiune**: Rescrie culorile native ale browserului, aprinzând fundalul textului selectat în roz-neon intens (`var(--nebula-pink)`) și forțând caracterele în alb pur.

- Selectorii de Scrollbar Custom `.data-grid::-webkit-scrollbar` ... `-track` (Bara de Scroll Catodică)
  - **Rolul în context**: Targetează și personalizează pseudo-elementele barei de derulare orizontală direct legate de șasiul containerelor `table` și `.data-grid`.
  - **Misiune**: Fixează o înălțime extrem de subțire de `3px !important` la baza tabelului. Colorează piesa mobilă (`-thumb`) în verde solar-mint la o opacitate fină de 30% cu o rotunjire de `2px` și maschează fundalul pe care glisează (`-track`) într-o nuanță închisă translucidă de sticlă (`rgba(13, 15, 20, 0.5)`).

    10.4. **SUB--MODULE 10.4: THE CELLULAR CYBER-LINKS (REȚELELE INTERACTIVE DE ANCORE)**

După configurarea carcasei macro și a șasiului fizic al tabelelor (Sub-Modulul 11.3), cascada se concentrează pe elementele dinamice interioare ale celulelor. Acest sector izolează și tratează **sistemele micro-cinetice de navigație și micro-accentele cromatice la hover**, separând intenționat designul structural de layout de ingineria fină a animațiilor laser.

- Selectorul `.data-grid td a` (Ancorele Active din Tabel / Symmetrical Cellular Links)
  - **Rolul în context**: Țintește toate elementele de tip ancoră (`<a>`) încastrate în interiorul celulelor de date ale tabelelor, acționând ca porți active de ieșire sau portaluri spre resurse externe.
  - **Misiune**: Transformă link-urile din starea lor inline nativă într-un comportament de tip `inline-block` pentru a le permite calibrarea exactă a padding-ului și a poziționării. Elimină sublinierea inestetică implicită a browserului (`text-decoration: none`), impune fontul rigid mecanic de cod `monospace` și aprinde textul pe o frecvență stabilă albastru-electric (`var(--starlight-blue, #00d2ff)`).

- Selectorul Pseudo-Element `.data-grid td a::after` (Firul Laser de Energie Ascuns / The Invisible Underscore)
  - **Rolul în context**: Generează o linie virtuală pur spectrală poziționată absolut la baza fiecărui link celular, funcționând ca o armătură energetică invizibilă.
  - **Misiune**: Desenează o fâșie micro-fină de exact `1px` înălțime, suspendată geometric la exact `2px` sub linia de bază a textului (`bottom: -2px`). O vopsește pe spectrul roz-magenta intens (`var(--nebula-pink)`) dintr-un capăt în altul, o înconjoară de o aureolă fluorescentă de ecran CRT (`box-shadow`) și îi îngheață lățimea inițială la `0` prin intermediul unei curbe de accelerație dinamice `cubic-bezier(0.4, 0, 0.2, 1)`.

- Selectorul `.data-grid td a:hover` (Declanșarea Cromatică a Porții / Active Link State)
  - **Rolul în context**: Interceptează momentul fizic în care operatorul atinge cu mouse-ul coordonatele textului ancorei celulare.
  - **Misiune**: Comută instantaneu frecvența cromatică a textului din nuanța stabilă albastru-stelar direct pe lungimea de undă roz-magenta intens a alarmei de sistem (`var(--nebula-pink)`).

- Selectorul `.data-grid td a:hover::after` (Explozia Vectorului Laser / The Laser Width Deployment)
  - **Rolul în context**: Targetează comportamentul liniei virtuale ascunse sub text în timpul stării de hover pe ancoră.
  - **Misiune**: Comandă lățimii fizice a pseudo-elementului să explodeze instantaneu de la starea latentă de `0` direct la capacitatea maximă de **`100%`**, întinzându-se perfect pe toată lungimea cuvântului selectat.

    10.5. **SUB-MODULE 10.5: THE RADAR DATA STREAMS (MONITOARELE CRT VERZI)**

După configurarea structurilor de bază ale tabelelor (Sub-Modulul 11.3) și a micro-accentelor interactive (Sub-Modulul 11.4), cascada deparazitează elementele de afișare a codului sursă. Acest sector izolează și tratează **casetele de afișare preformatate și textul fosforescent**, oferind o identitate vizuală unificată și protejând layout-ul de erori de lăbărțare pe ecrane splitate.

- Selectorul `pre` (Securizare Blocuri de Cod / The Radar Data Streams)
  - **Rolul în context**: Targetează elementul nativ de text preformatat (`<pre>`) utilizat pe paginile de jurnale pentru a încapsula bucățile de cod sursă predate studenților.
  - **Misiune**: Construiește o mască de fundal verde extrem de închisă, aproape neagră (`rgba(0, 20, 0, 0.9)`), încadrată de o bordură solidă verde-mentă de `1px` (`border: 1px solid var(--solar-mint)`). Injectează o umbră interioară fosforică densă de `15px` (`box-shadow`), forțează textul să execute auto-wrap prin `white-space: pre-wrap` și rupe cuvintele lungi anti-overflow prin `word-wrap: break-word`.

- Selectorul `code` (Textul Fosforescent din Arhivă / The Fluorescent Terminal Text)
  - **Rolul în context**: Targetează elementele inline (`<code>`) încastrate în interiorul blocurilor preformatate, izolând caracterele de sintaxă.
  - **Misiune**: Impune fontul rigid mecanic de mașină de scris `Courier New`, aprinde textul pe frecvența verde-mentă fosforică pură (`var(--solar-mint)`) la o dimensiune de `0.9rem` și explodează o aureolă puternică fluorescentă stabilă de `5px` direct pe forma literelor prin proprietatea `text-shadow`.

- Selectorul Pseudo-Element `pre::before` (Indicatorul Digital din Colț / Automated Telemetry Indicator)
  - **Rolul în context**: Generează un șir discret de text tehnic în interiorul ecranului de cod, funcționând ca o etichetă de diagnostic.
  - **Misiune**: Injectează automat textul `"DATA STREAM ACTIVE"` prin proprietatea `content`. Îl poziționează absolut în colțul din dreapta-sus (`top: 5px`, `right: 10px`), scade dimensiunea la un volum micro-fin de `0.6rem` și reduce opacitatea la `0.5` cu un letter-spacing de `1px`.

- Selectorii de Scrollbar Custom `pre::-webkit-scrollbar` și `-thumb` (Micro-Firul de Scroll Albastru)
  - **Rolul în context**: Targetează și personalizează pseudo-elementele barei de derulare orizontală direct legate de șasiul containerului `pre`.
  - **Misiune**: Setează o înălțime extrem de subțire de `4px` la baza casetei de cod. Colorează piesa mobilă (`-thumb`) în nuanța originală albastru-stelar la o opacitate fină de 30% (`rgba(0, 210, 255, 0.3)`) cu o rotunjire de `2px`.

    10.6. **SUB-MODULE 10.6: THE AUXILIARY ANNEXES & FUTURE AMBER VAULTS (PANOURI AUXILIARE)**

După izolarea radarelor de cod preformatat (Sub-Modulul 11.5), cascada structurală unifică ultimele componente satelit care completează paginile jurnalelor de navigație. Acest sector tratează **panourile de extensii pentru scripturi, link-urile globale, sub-logurile interne și capsulele de timp în așteptare**, demonstrând practic conceptul de specificitate contextuală prin excepții locale de ierarhie.

- Selectorii `.js-annex` și `.js-annex h4` (Panourile de Extensii / The JavaScript Badge Framework)
  - **Rolul în context**: Targetează containerele auxiliare destinate capitolelor de extensii (React, Angular) și titlurile lor rigide înălțate la nivelul tavanului.
  - **Misiune**: `.js-annex` construiește un ecran protector din sticlă fumurie cu un chenar punctat în lungimea de undă violet cosmic (`border: 1px dashed var(--nebula-purple)`). Elementul `h4` este extras din flux prin `position: absolute`, ridicat la `top: -14px` fix pe mijlocul liniei de border și mascat cu fundal violet solid, transformându-se într-o insignă militară cu text verde-mentă capitalizat obligatoriu.

- Selectorul `.archive-link` și Starea de Hover (Butoanele Portale de Navigație / Outbound Channels)
  - **Rolul în context**: Targetează elementele ancoră de tip buton plasate în subsolul paginilor sau articolelor pentru a asigura saltul spre arhivele centrale.
  - **Misiune**: Închide textul într-un dreptunghi tactil precis prin padding uniform de `10px 20px`, elimină sublinierea nativă, impune majuscule de protocol și desenează un chenar solid verde-mentă. La hover, execută o inversare cromatică totală: fundalul se aprinde în radiație fosforică verde pură, textul devine negru profund (`var(--space-dark)`) pentru contrast maxim, fiind înconjurat de o umbră densă de neon de `20px`.

- Selectorii de Excepție Contextuală `.js-annex .archive-link` și `:hover` (Nesting Overrides)
  - **Rolul în context**: Interceptează butoanele de arhivă exclusiv atunci când sunt poziționate în interiorul unui panou de extensie JavaScript violet.
  - **Misiune**: Suprascrie dimensiunile și culorile generale: textul și chenarul trec pe culoarea violet, padding-ul se strânge compact la `6px 12px`, iar dimensiunea fontului scade la `0.7rem`. La hover, fundalul devine violet solid, textul se aprinde înapoi în verde-mentă de înaltă vizibilitate, iar marginea exterioară comută pe verde-mentă activ.

- Selectorul `.future-log` și Starea de Hover (Capsulele Timpului / The Dormant Amber Vaults)
  - **Rolul în context**: Targetează cardurile zilnice sau modulele care conțin capitole viitoare ale expediției, neîncărcate încă în băncile active ale navei.
  - **Misiune**: În repaus, blochează indicatorul stâng pe culoarea chihlimbarului (`--amber-glow`) cu directiva dictatorială `!important`, scade opacitatea la `0.5`, aplică un filtru hardware cinematic `grayscale(0.8)` și schimbă cursorul mouse-ului într-un semn de diagnostic (`cursor: help`). La hover, activează sistemul, readucând opacitatea la `1`, eliminând filtrul grayscale (`grayscale(0)`), propagând o tentă fină de 5% chihlimbar în fundal și deplasând cardul mecanic spre dreapta cu `5px` (`transform: translateX`).

```

/* ==========================================================================
    MODULE 10: MODULAR TECHNICAL VAULTS (LOG ENTRIES, ANEXE ȘI TABELE)

    REZUMAT: Acest modul cumulează șabloanele structurale master pentru cronicile
    zilnice de zbor, ecranele de cod de diagnostic și tabelele de date relaționale.
    El unifică intrările de jurnal flexibile cu letrinele lor fluorescente,
    stabilizează matricele data-grid pentru independență la overflow orizontal,
    protejează fluxurile de cod preformatat CRT și configurează micro-mediile
    pentru anexele de sistem latente sau viitoare.
   ========================================================================== */

/* ==========================================================================
    SUB-MODULE 10.1: THE JOURNAL FOUNDATIONS (NARAȚIUNEA ȘI LETTERING-UL)

    REZUMAT: Acest sub-modul stabilește motorul tipografic primar pentru cronicile
    jurnalelor de bord. El structurează fluxul paragrafelor standard pentru o
    citire de înalt contrast, configurează spațieri verticale anti-oboseală și
    activează sistemul modular de direct-child Jet-Age Glif-Monolit pe primele
    caractere pentru a inițializa protocoalele de vizualizare a încărcării sistemului.
   ========================================================================== */
/* --- 1. ZONA TEXTULUI NARATIV GENERAL (Alinierea Paragrafelor Simple) --- */
.log-text {
  text-align: justify; /* Aliniază textul compact stânga-dreapta ca în jurnalele tipărite */
  color: var(
    --stardust
  ); /* Alb industrial stins stardust, conceput împotriva oboselii ochilor */
  font-size: 1.05rem; /* Dimensiune ideală, extrem de lizibilă pentru sesiuni lungi de studiu */
  line-height: 1.8; /* Relație aerisită între rânduri pentru a împiedica textul să se sufoce vizual */
}

/* --- 2. ȘTAMPILA GLIF-MONOLIT HARDWARE (Suprasunderea Jet-Age de Stil) --- */
.log-text > p:first-of-type::first-letter {
  font-family: var(
    --font-main
  ); /* Păstrează amprenta geometrică rigidă a erei spațiale Space Grotesk */
  font-weight: 700; /* Îngroașă vectorul literei pentru o definiție maximă pe ecranul radar */
  font-size: 1.3rem; /* Dimensiune comprimată tactică, specifică tastelor fizice de terminal */
  color: var(
    --solar-mint
  ); /* Textul se aprinde intens pe verde-mentă fosforic de sistem */

  /* STRUCTURA CADRULUI JET-AGE FRAMEWORK */
  float: left; /* Împinge piesa în stânga, permițând textului să curgă simetric în jur */
  /* display: inline-block;         Convertește litera într-un bloc structural fizic, eliminând starea inline */
  border: 1px dashed var(--solar-mint); /* BORDER LASER PUNCTAT: Chenar fin verde-mentă ce încadrează fix nodul */
  border-radius: 2px; /* Rotunjire minimalistă brută asortată cu interfețele militare */

  /* CONFIGU  RAȚIA MICRO-RASTERULUI CRT DIN FUNDAL */
  background:
    linear-gradient(rgba(18, 16, 16, 0) 50%, #05070a 50%), #0d0f14; /* Stratificare: fundal negru blindat peste care se repetă dungi CRT de 2px */
  background-size: 100% 2px; /* Repetă microscopic liniile orizontale catodice pe toată înălțimea piese */

  /* ALINIERE GEOMETRICĂ AXIALĂ */
  padding: 4px 10px; /* Umplutură dreptunghiulară simetrică strânsă în jurul literei */
  margin-right: 12px; /* Distanță fizică de siguranță despărțind monolitul de cuvintele ce urmează */
  margin-top: 5px; /* Reglaj fin de altitudine ce aliniază tavanul capsulei cu cel al rândului */
  line-height: 1.2; /* Înălțime strânsă ce împiedică piesa să decaleze grila rândurilor de jos */

  /* SHIELD TENSION DE EMISIE */
  box-shadow: 0 0 10px rgba(167, 243, 208, 0.3); /* Aură luminoasă discretă din spectrul verde-mentă în jur */
  text-shadow: 0 0 5px var(--solar-mint); /* Proiectează o aureolă fluorescentă verde direct pe forma literei */
}

/* ==========================================================================
    SUB-MODULE 10.2: THE CHRONICLE VAULTS (CAPSULELE DE JURNAL & ETICHETE)

    REZUMAT: Acest sub-modul izolează șabloanele structurale pentru intrările
    zilnice de jurnal și casetele de definiții tehnice pentru etichetele de cod.
    El configurează învelișuri adaptive înzestrate cu adâncituri de umbră CRT
    interioară și ancorează ierarhiile fosforice ale micro-metadatelor de sintaxă.
   ========================================================================== */
/* --- 1. CASETA INDIVIDUALĂ A UNEI ZILE (The Log Entry Screen Vault) --- */
.log-entry {
  background: var(
    --panel-bg
  ); /* Fundalul original translucid de sticlă fumurie stabilizată Solaris */
  padding: 2.5rem; /* Umplutură internă extinsă pentru a nu sufoca conținutul narativ */
  margin: 30px 0; /* Distanță clară pe verticală între modulele zilnice din flux */
  border: 1px solid var(--module-border); /* Chenar micro-fin alb pentru asamblarea tehnică a structurii */
  border-left: 5px solid var(--solar-mint); /* BANDA VERTICALĂ FOSFORICĂ: Indicatorul radar stabil verde-mentă */
  box-shadow: inset 0 0 30px rgba(0, 0, 0, 0.5); /* EFECTUL CRT BOMBAT: Creează adâncime fizică de monitor vechi în interior */
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1); /* Mișcare fluidă originală bazată pe accelerație la interacțiune */
  position: relative; /* Deschide context de poziționare pentru micro-elemente interne */
  overflow: hidden; /* Taie mecanic pixelii sau luminile care ar încerca să spargă marginile casetei */
}

/* Efect cinematic la hover peste modulul zilei: Încărcare fosforică și ridicare cinematică */
.log-entry:hover {
  background: rgba(
    167,
    243,
    208,
    0.05
  ); /* Tenta fină de mentă se propagă pe tot fundalul sticlei fumurii */
  border-color: rgba(
    167,
    243,
    208,
    0.2
  ); /* Intensifică opacitatea și contrastul chenarului micro-fin perimetral */
  box-shadow:
    inset 0 0 40px rgba(167, 243, 208, 0.1),
    0 0 20px rgba(167, 243, 208, 0.05); /* Strălucirea fosforică se mărește simetric în interior și în exterior */
  transform: translateY(
    -3px
  ); /* RIDICARE STRUCTURALĂ: Împinge ușor cardul în sus pentru dinamică tridimensională */
}

/* Configurația specifică a paragrafelor din interiorul jurnalului de zi */
.log-entry p {
  font-size: 0.95rem; /* Dimensiune tehnică odihnitoare pentru citit în interiorul capsulei */
  color: rgba(
    209,
    209,
    209,
    0.85
  ); /* Un gri stardust original, calibrat pentru păstrarea ierarhiei vizuale */
  margin-bottom: 1.5rem; /* Spațiu protector de aer sub paragrafe în interiorul carcasei metalice */
  overflow-wrap: break-word; /* SCUT DE RESPONSIVITATE: Rupe automat cuvintele lungi la capătul casetei */
  word-wrap: break-word; /* Suport suplimentar pentru browsere mai vechi, blocând lăbărțarea */
  hyphens: auto; /* Adaugă automat cratimă la despărțirea cuvintelor la capăt de rând */
  text-align: justify; /* Aliniere compactă stânga-dreapta ca în cărți pentru simetrie */
  text-justify: inter-word; /* Reglează spațiile dintre cuvinte pentru a bloca golurile inestetice */
}

/* --- 2. ALINIERILE ȘI TITLURILE DIN INTERIORUL ZILEI (Sistemul de Antet Dual) --- */
.log-entry h3 {
  display: flex; /* Activează motorul Flexbox pe linia titlului de zi */
  justify-content: space-between; /* EFECT DUAL SIMETRIC: Împinge DayXX în stânga și elementele Meta în dreapta */
  align-items: center; /* Aliniază ambele blocuri de text la mijloc pe axa verticală a rândului */
  border-bottom: 1px solid rgba(167, 243, 208, 0.1); /* Linie discretă micro-fină de demarcație la baza textului */
  padding-bottom: 8px; /* Pernă fină de aer sub text înainte de firul de demarcație */
  margin-top: 0; /* Resetează marginile nativ-parazite pentru a securiza alinierea */
  width: 100%; /* Se întinde pe toată lățimea utilă a casetei jurnalului */
  font-size: 1.1rem; /* Dimensiune tehnică echilibrată, specifică antetelor de zi */
  color: var(
    --nebula-pink
  ); /* Ziua din stânga se aprinde spectaculos în nuanța roz-magenta intens */
}

/* --- 3. REPARAREA MODULELOR SEMANTICE (Specifică pentru html-day03 și structuri de tag-uri) --- */
.semantic-module {
  margin: 25px 0; /* Spațiu clar de demarcație pe verticală deasupra și sub modulul de tag */
  padding-left: 15px; /* Distanța textului tehnic interior față de linia laser din stânga */
  border-left: 2px solid var(--nebula-pink); /* LINIE LASER SOLIDĂ: Fir roz-magenta în dreptul definiției de tag */
}

/* Afișarea numelui de etichetă (ex: <div>, <header>, <aside>) */
.tag-name {
  color: var(
    --solar-mint
  ); /* Numele tagului se aprinde intens pe verde-mentă fosforic de sistem */
  font-weight: bold; /* Îngroașă caracterele pentru autoritate vizuală supremă pe scaner */
  font-size: 1.1rem; /* Dimensiune mărită pentru evidențiere directă și rapidă în log */
  text-shadow: 0 0 8px var(--solar-mint); /* Generează o aureolă luminoasă difuză de neon în jurul literelor active */
}

/* Metadatele tehnice atașate tagului (atribute, document structural scopes) */
.tag-meta {
  color: var(
    --nebula-pink
  ); /* Prinde metadatele pe culoarea roz-neon de alertă militară */
  font-size: 0.8rem; /* Dimensiune tehnică redusă, specifică datelor secundare de diagnostic */
  text-transform: uppercase; /* Protocol obligatoriu: forțează litere mari în interiorul etichetei */
  letter-spacing: 1px; /* Spațiere fină între caractere pentru aspect curat de monitor */
  margin-left: 10px; /* Lasă un spațiu fizic gol de 10px în stânga, separându-se de tag-name */
}

/* Descrierea extinsă din subsolul definiri de tag */
.tag-description {
  margin-top: 8px !important; /* FORȚARE CRUCIALĂ: Împinge textul curat sub blocul tagului, dezasamblând rândul */
}

/* ==========================================================================
    SUB-MODULE 10.3: THE MATRIX REPOSITORIES (MATRICILE DE DATE CELULARE)

    REZUMAT: Acest sub-modul configurează matricile tabulare bidimensionale
    utilizate pe punțile de arhivă și bibliografie (.data-grid). El elimină
    formatarea implicită a celulelor din browser, rulează o placă verde de 10s
    tensiune joasă în spatele antetelor, ancorează linii laser solide și încarcă
    umbre kinetice de proximitate peste rândurile scanate la intersecția cursorului.
   ========================================================================== */
/* --- 1. STRUCTURA GENERALĂ A TABELULUI (The Solaris Database Grid) --- */
table,
.data-grid {
  display: table !important; /* Reparație de bază: Șterge display: block și reinstaură fluxul nativ de tabel */
  width: 100% !important; /* Se extinde elastic pe toată lățimea utilă a monitorului hardware disponibil */
  border-collapse: collapse; /* Lipește perfect liniile celulelor interioare, eliminând spațiile goale parazite */
  margin: 20px 0; /* Distanță verticală de siguranță izolând tabelul de restul paragrafelor de text */
  background: rgba(
    13,
    15,
    20,
    0.4
  ); /* Fundal translucid original din sticlă fumurie pentru panoul de bord */
  border: 1px solid rgba(167, 243, 208, 0.2); /* Chenar exterior din fir laser de mentă la 20% opacitate de sistem */
  font-family: var(
    --font-main
  ); /* Reinstaurează amprenta geometrică rigidă a fontului master spațial */
  font-size: 0.9rem; /* Dimensiune tehnică redusă, optimizată pentru citirea datelor dense din celule */
  box-sizing: border-box; /* Include padding-ul în calculul lățimii pentru a bloca overflow-ul structural */
}

/* --- 2. ANTETELE DE COLOANĂ HARDWARE (Alinierea Capului de Tabel) --- */
th {
  background: rgba(
    167,
    243,
    208,
    0.1
  ); /* Inserare fundal original format dintr-o tentă fină de 10% verde-mentă */
  color: var(
    --solar-mint
  ); /* Text fosforic verde-mentă aprins dedicat semnalizării prioritare pe consolă */
  text-transform: uppercase; /* Protocol militar obligatoriu: forțează utilizarea literelor mari în antet */
  letter-spacing: 2px; /* Spațiere tehnică industrială stabilă între caracterele etichetelor */
  padding: 12px; /* Umplutură internă compactă ce asamblează simetric celulele de antet */
  border-bottom: 2px solid var(--solar-mint); /* Linie groasă originală de control și demarcație laser la baza capului */
  text-align: left; /* Aliniere curată la stânga în interiorul coloanei pentru citire directă */
}

/* --- 3. ÎNVELIȘUL UNIFICAT AL CELULELOR DE DATE (Perna de Aer Celulară) --- */
td {
  padding: 12px; /* Păstrează cu sfințenie padding-ul simetric ideal de 12px din foaia veche */
  border-bottom: 1px solid rgba(255, 255, 255, 0.05); /* Linii micro-fine catodice între rândurile de date din tabel */
  color: rgba(
    209,
    209,
    209,
    0.9
  ); /* Text alb stardust opacizat conceput special împotriva oboselii vizuale */

  /* SCUT DE SIGURANȚĂ ANTI-OVERFLOW PENTRU ECRANE STRÂMTE:
      Dacă o adresă URL din celulă este uriașă, nu va mai deforma tabelul,
      ci se va rupe curat în interiorul coordonatelor sale fără să iasă din ecran! */
  word-wrap: break-word;
  overflow-wrap: break-word;
  white-space: normal !important; /* Îi permitem textului să facă wrap pe rândul următor dacă fereastra devine strâmtă */
}

/* --- 4. RĂSPUNS KINETIC LA HOVER PESTE RÂND (Raza de Scanare Proximity) --- */
tr:hover {
  background: rgba(
    167,
    243,
    208,
    0.05
  ) !important; /* Tenta fină de mentă la 5% opacitate la trecerea mouse-ului peste rând */
  box-shadow: inset 0 0 10px rgba(167, 243, 208, 0.1) !important; /* Aură interioară discretă de neon verde la atingere */
}

/* --- 5. SELECȚIA DE ÎNALTĂ TENSIUNE A TEXTULUI DIN CELULE (Highlight Map) --- */
td::selection {
  background: var(
    --nebula-pink
  ); /* Textul selectat manual de echipaj se aprinde instantaneu pe roz-neon intens */
  color: white; /* Forțează caracterele selectate în alb pur pentru contrast maxim pe placa aprinsă */
}

/* --- 6. PERSONALIZAREA INTEGRALĂ A BARELOR DE SCROLL (HUD Webkit Adjustments) --- */
/* O bară de scroll micro-fină asortată cu tema ecranelor CRT verzi Solaris */
.data-grid::-webkit-scrollbar,
table::-webkit-scrollbar {
  height: 3px !important; /* O linie extrem de subțire de 3px plasată în subsolul bazei tabelului tehnic */
}

.data-grid::-webkit-scrollbar-thumb,
table::-webkit-scrollbar-thumb {
  background: rgba(
    167,
    243,
    208,
    0.3
  ) !important; /* Culoarea verde solar-mint la o opacitate fină de 30% */
  border-radius: 2px; /* Rotunjire minimalistă brută asortată cu întreaga carcasă hardware */
}

.data-grid::-webkit-scrollbar-track,
table::-webkit-scrollbar-track {
  background: rgba(
    13,
    15,
    20,
    0.5
  ) !important; /* Fundal închis de sticlă, pitit aproape invizibil în layout */
}

/* ==========================================================================
    SUB-MODULE 10.4: THE CELLULAR CYBER-LINKS (REȚELELE INTERACTIVE DE ANCORE)

    REZUMAT: Acest sub-modul izolează sistemele micro-cinetice de navigație
    încastrate în interiorul celulelor de date (.data-grid td a). El configurează
    frecvențele active latente albastru-stelar, rulează un fir laser orizontal
    ascuns de 1px pe spectrul roz-magenta (::after) și gestionează bucla de
    expansiune geometrică explozivă la 100% declanșată la hover-ul operatorului.
   ========================================================================== */
/* --- 1. ACCENT CROMATIC: STILUL DE BAZĂ AL LINK-URILOR (Stare de Repaus) --- */
.data-grid td a {
  color: var(
    --starlight-blue,
    #00d2ff
  ); /* Link-urile luminează inițial pe un albastru electric fin de sistem */
  text-decoration: none; /* Elimină sublinierea nativă inestetică a browserelor terestre pe elemente */
  font-family: monospace; /* Font rigid mecanic de cod ce păstrează caracterul tehnic al terminalului */
  position: relative; /* Context de poziționare local obligatoriu pentru generarea micro-liniei laser */
  display: inline-block; /* Convertește elementul în bloc în linie pentru a respecta padding-ul dreptunghiular */
  transition: color 0.3s ease; /* Tranziție rapidă de răspuns pentru schimbarea culorii textului la atingere */
}

/* --- 2. GENERAREA FIRELOR LASER INVIZIBILE DE SUB TEXT (Sublinierea Latentă) --- */
.data-grid td a::after {
  content: ""; /* Inicilizează stratul fizic virtual; directivă obligatorie de creare a nodului */
  position: absolute; /* Scoate firul din fluxul normal pentru a-l suspenda rigid sub caractere */
  bottom: -2px; /* O fixează la exact 2px sub linia de bază a textului din interiorul celulei */
  left: 0; /* Blochează punctul de pornire al extinderii în extrema stângă a cuvântului */
  width: 0; /* Stare inițială închisă: linia este complet strânsă și invizibilă pe monitor */
  height: 1px; /* Grosime micro-fină industrială de laser sub textul interactiv din rețea */
  background: var(
    --nebula-pink
  ); /* Culoarea originală roz-magenta a nebuloasei ce alimentează circuitul firului */
  box-shadow: 0 0 8px var(--nebula-pink); /* Umbră fluorescentă roz ce imită emisia de lumină a ecranelor catodice */

  /* CUBIC-BEZIER INDUSTRIAL: Controlează extinderea fluidă orizontală stânga-dreapta fără salturi rigide */
  transition: width 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

/* --- 3. EFECT HOVER CHIRURGICAL: DECLANȘAREA RAZEI LASER LA ATINGERE (Stare Activă) --- */
.data-grid td a:hover {
  color: var(
    --nebula-pink
  ); /* Textul ancorei trece instantaneu pe lungimea de undă roz-magenta de alertă */
}

.data-grid td a:hover::after {
  width: 100%; /* Firul laser explodează și se întinde pe toată lungimea cuvântului selectat */
}

/* ==========================================================================
    SUB-MODULE 10.5: THE RADAR DATA STREAMS (MONITOARELE CRT VERZI)

    REZUMAT: Acest sub-modul configurează casetele de afișare a codului sursă
    pe spectrul verde fosforic intens (pre, code). El injectează automat etichete
    statice de monitorizare prin coordonate absolute (::before), blochează
    deformările pe ecrane splitate multi-dispozitiv și rulează o bară de scroll
    micro-fină pe nuanța albastru-stelar la baza incintei.
   ========================================================================== */
/* --- RADAR SCREENS: MONITOARELE CRT VERZI ORIGINALE --- */
pre {
  background: rgba(
    0,
    20,
    0,
    0.9
  ); /* Verde extrem de închis, aproape negru, specific radarelor vechi */
  border: 1px solid var(--solar-mint); /* Margine solidă originală din culoarea verde-mentă de scanare */
  padding: 20px; /* Umplutură internă curată ce îndepărtează textul de granițe */
  border-radius: 4px; /* Rotunjire minimalistă la colțuri asortată cu interfața generală */
  overflow-x: auto; /* Permite scroll orizontal doar ca protecție suplimentară dacă e nevoie */
  position: relative; /* Context obligatoriu pentru poziționarea etichetei DATA STREAM în colț */

  /* EFECTUL ORIGINAL DE MONITOR BOMBAT: Umbra interioară fosforică verde în sticlă */
  box-shadow: inset 0 0 15px rgba(167, 243, 208, 0.2);

  /* FORMULA DE SIGURANȚ RETEHNOLOGIZATĂ PENTRU ECRANE SPLITATE */
  white-space: pre-wrap; /* REPARAT RECURSIV: Rupe rândul automat dacă e prea lung în fereastra strâmtă */
  word-wrap: break-word; /* Împiedică lățirea artificială a paginii și revărsările laterale */
}

/* Efectul original de text fosforescent din arhivă */
code {
  font-family:
    "Courier New", Courier, monospace; /* Font rigid mecanic de cod ce simulează carcasele vechi */
  color: var(
    --solar-mint
  ); /* Textul se aprinde integral pe verde-mentă fosforic de sistem */
  text-shadow: 0 0 5px var(--solar-mint); /* Aura fosforescentă originală stabilă din stilul vechi din foi */
  font-size: 0.9rem; /* Dimensiune radar compactă ideală pentru liniile de script */
}

/* INDICATORUL DISCRET ÎN COLȚUL MONITORULUI CRT (Pagina 12 din PDF) */
pre::before {
  content: "DATA STREAM ACTIVE"; /* Textul generat automat de sistem în interiorul ecranului vitrat */
  position: absolute; /* Scoatere din flux pentru a pluti independent în colțul superior */
  top: 5px; /* Distanțe fine originale de poziționare pe axa verticală */
  right: 10px; /* Aliniere strânsă pe flancul drept (tribord) */
  font-size: 0.6rem; /* Dimensiune micro-fină pentru a nu concura cu textul de cod */
  color: var(
    --solar-mint
  ); /* Culoarea de sistem verde-mentă fosforică uniformă */
  opacity: 0.5; /* Aspect stins de fundal, integrat discret sub ecranare */
  letter-spacing: 1px; /* Spațiere tehnică stabilă între literele indicatorului */
}

/* PERSONALIZAREA BAREI DE SCROLL ORIZONTALE A CODULUI (Estetică SF originală) */
pre::-webkit-scrollbar {
  height: 4px; /* O bară orizontală extrem de subțire de 4px în subsolul casetei de cod */
}

pre::-webkit-scrollbar-thumb {
  background: rgba(
    0,
    210,
    255,
    0.3
  ); /* Colorează bara în nuanța ta originală de albastru stelar la 30% opacitate */
  border-radius: 2px; /* Rotunjește colțurile barei mobile pentru un finisaj minimalist */
}

/* ==========================================================================
    SUB-MODULE 10.6: THE AUXILIARY ANNEXES & FUTURE AMBER VAULTS

    REZUMAT: Acest sub-modul asamblează panourile de studiu auxiliare și capsulele
    de timp înghețate (.js-annex, .sub-log, .future-log). El mapează antetele absolut
    înălțate pe borduri violet, controlează excepțiile locale de dimensiuni pentru
    link-uri de arhivă și rulează o bandă chihlimbar (--amber-glow) însoțită de un
    filtru grayscale(0.8) de hibernare peste jurnalele în așteptare.
   ========================================================================== */
/* --- 1. CASETA ANEXELOR DE STUDIU (The JS Annex Environment) --- */
.js-annex {
  margin-top: 45px; /* Spațiu protector original pentru a lăsa eticheta superioară să respire */
  padding: 25px 20px 20px 20px; /* Pernă de aer interioară simetrică ce stabilizează grupurile de sub-elemente */
  background: rgba(
    0,
    0,
    0,
    0.4
  ); /* Fundal întunecat opac de carcasă pentru izolarea completă a nodului */
  border: 1px dashed var(--nebula-purple); /* Delimitare originală punctată în lungimea de undă violet cosmic */
  border-radius: 4px; /* Rotunjire minimalistă la colțuri perfect asortată cu interfața generală */
  position: relative; /* ESENȚIAL pentru ca h4 să se poată ancora absolut raportat la bordură */
}

/* TITLUL ANEXEI CA O ETICHETĂ MILITARĂ/INDUSTRIALĂ PROPRIE ÎNĂLȚATĂ PESTE BORDURĂ */
.js-annex h4 {
  position: absolute; /* Scoatere din flux pentru a pluti fix deasupra perimetrului de sârmă punctată */
  top: -14px; /* O ridică pe verticală exact la jumătatea liniei de chenar exterior */
  left: 15px; /* Aliniere tehnică precisă în flancul stâng raportat la carcasă */
  margin: 0; /* Resetează marginile parazite ale browserului pentru a securiza poziția */
  background: var(
    --nebula-purple
  ); /* Fundal solid violet adânc pentru a masca și șterge linia punctată din spate */
  color: var(
    --solar-mint
  ); /* Text verde-mentă fosforic intens pentru o vizualizare optimă pe radar */
  padding: 2px 12px; /* Umplutură dreptunghiulară originală ce asamblează aspectul de etichetă rigidă */
  font-size: 0.75rem; /* Dimensiune redusă de radar specifică ferestrelor auxiliare HUD */
  text-transform: uppercase; /* Protocol militar obligatoriu: forțează utilizarea literelor mari */
  letter-spacing: 2px; /* Spațiere tehnică stabilă între caractere pentru un aspect premium */
  border: 1px solid var(--solar-mint); /* Margine micro-fină oțelită asortată cromatic cu textul interior */
  font-style: normal; /* Suprascrie forțat eventualele stiluri italic sosite din scurgeri globale */
}

/* --- 2. BUTOANELE PRINCIPALE DE PORTAL ACCES ȘI NAVIGAȚIE DE CAPITOL --- */
.archive-link {
  display: inline-block; /* Îl transformă în bloc în linie pentru a respecta padding-ul dreptunghiular stabilit */
  margin-top: 15px; /* Spațiu protector de siguranță deasupra butonului izolat */
  color: var(
    --solar-mint
  ); /* Text aprins pe culoarea stabilă de sistem verde-mentă fosforic */
  text-decoration: none; /* Elimină sublinierea nativă inestetică injectată automat de browsere */
  font-size: 0.8rem; /* Dimensiune tehnică minimalistă conform blueprint-urilor HUD ale consolei */
  text-transform: uppercase; /* Litere mari obligatorii pentru un aspect rigid de protocol militar */
  letter-spacing: 2px; /* Spațiere largă tehnică industrială între caractere pentru aspect premium */
  padding: 10px 20px; /* Umplutură internă originală pentru asamblarea unei zone tactile precise */
  border: 1px solid var(--solar-mint); /* Chenar rigid de sistem ce marchează granița de control secundară */
  transition: all 0.3s ease; /* Tranziție rapidă de răspunsHandling momentum la interacțiunea operatorului */
}

/* EFECT HOVER PESTE PORTALUL GENERAL AL ARHIVEI DE SISTEM */
.archive-link:hover {
  background: var(
    --solar-mint
  ); /* Fundalul se aprinde complet în radiație verde-mentă fosforică pură */
  color: var(
    --space-dark
  ); /* Forțează textul în negru profund, maximizând lizibilitatea pe placa aprinsă */
  box-shadow: 0 0 20px var(--solar-mint); /* Erupție puternică de aureolă neon fluorescentă în jurul elementului */
}

/* EXCEPȚIE LOCALĂ DE CASCADĂ: CONFIGURAȚIA BUTONULUI DE ARHIVĂ CÂND SE AFLĂ ÎN INTERIORUL ANEXEI VIOLET */
.js-annex .archive-link {
  color: var(
    --nebula-purple
  ); /* Suprascrie valoarea inițială albă și mută textul pe spectrul violet al nebuloasei */
  font-size: 0.7rem; /* Dimensiune micro tehnică adaptată special pentru potrivirea în casetă */
  padding: 6px 12px; /* Umplutură mult mai compactă ce protejează limitele structurale interioare */
  margin-top: 10px; /* Decalaj fin de aer deasupra elementului în interiorul modulului */
  border-color: var(
    --nebula-purple
  ); /* Chenarul oțelit trece pe lungimea de undă violet solid a modulului */
  opacity: 0.8; /* Aspect ușor desaturat în starea de repaus pentru păstrarea ierarhiei */
  display: inline-block; /* Ancorează comportamentul de bloc, asigurând randarea corectă a marjelor */
}

/* EFECT HOVER SPECIAL PE PORTALUL INTERIOR RECONVERTIT DIN ANEXĂ */
.js-annex .archive-link:hover {
  background: var(
    --nebula-purple
  ); /* Fundalul absoarbe complet energia violet a nebuloasei centrale */
  color: var(
    --solar-mint
  ); /* Textul se aprinde invers pe lungimea de undă verde-mentă de înaltă vizibilitate */
  box-shadow: 0 0 10px var(--nebula-purple); /* Proiectează o mică aură laser micro-fină violet în jurul piesei */
  border-color: var(
    --solar-mint
  ); /* Marginea exterioară comută pe verde-mentă de confirmare activă */
  opacity: 1; /* Restaurarea luminozității totale și a vizibilității necomprimate pe ecran */
}

/* --- 3. LOGURI SECUNDARE INTERNE (Sub-modulele de diagnostic din articole) --- */
.sub-log {
  border-left: 2px solid var(--nebula-purple); /* Linie verticală originală solidă violet ca ghid structural de poziție */
  padding-left: 15px; /* Distanța de siguranță a textului tehnic interior față de linia de ghidaj */
  margin: 20px 0; /* Spațiu protector vertical izolând sub-logul de restul elementelor */
}

.sub-log h5 {
  color: var(
    --solar-mint
  ); /* Titlul secundar se aprinde stabil pe verde-mentă fosforic de sistem */
  border-bottom: 1px dashed var(--solar-mint); /* DIRECTIVĂ LOCALĂ DE SPECIE: Linia punctată de sub text se aplică DOAR aici */
  display: inline-block; /* Restrânge geometric fundalul și linia strict pe lungimea caracterelor scrise */
  margin-bottom: 10px; /* Distanță fină de siguranță sub titlu înainte de curgerea paragrafelor */
}

/* STILIZAREA TEXTULUI METAFORIC POZIȚIONAT SECUNDAR PE ORIZONTALĂ */
.meta-title {
  font-size: 0.85rem; /* Dimensiune tehnică redusă pentru a stabili o ierarhie vizuală clară */
  color: var(
    --solar-mint
  ); /* Textul se aprinde direct pe frecvența verde-mentă fosforică a radarului */
  opacity: 0.8; /* Aspect ușor desaturat în starea de repaus pentru a nu obosi ochii */
  letter-spacing: 2px; /* Spațiere tehnică largă industrială între caractere pentru aspect premium */
  font-weight: normal; /* Text subțire fluid ce evită îngroșarea parazită în matricea HUD */
}

/* --- 4. SEIFURILE TIMPULUI "FUTURE LOG" (Capsulele Chihlimbar în Așteptare) --- */
.future-log {
  border-left: 5px solid var(--amber-glow) !important; /* FORȚARE DICTATORIALĂ: Blochează indicatorul pe chihlimbar de avertizare */
  opacity: 0.5; /* Vizibilitate redusă la jumătate ce simulează o capsulă de date blocată */
  filter: grayscale(
    0.8
  ); /* Efect cinematic original: estompează culorile în gri (mod hibernare hardware) */
  transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1); /* Curbe cursive de accelerație pentru trezirea sistemelor */
  cursor: help; /* Modifică cursorul mouse-ului într-un semn de întrebare pentru atmosferă narativă */
}

/* EFECT LA HOVER PESTE CAPSULA VIITOARE: TREZIREA COMPLETĂ DIN HIBERNARE A DATELOR */
.future-log:hover {
  opacity: 1; /* Restaurarea instantanee a luminozității totale a canalelor vizuale */
  filter: grayscale(
    0
  ); /* Filtrul grayscale cade la zero absolut; culorile native revin online */
  background: rgba(
    255,
    179,
    0,
    0.05
  ); /* O tentă fină originală de 5% de chihlimbar se propagă pe sticla de fundal */
  box-shadow:
    inset 0 0 20px rgba(255, 179, Amber, 0.1),
    0 0 15px rgba(255, 179, 0, 0.05); /* Strălucire fosforică dublă pe spectrul chihlimbar în interior și exterior */
  transform: translateX(
    5px
  ); /* DEPLASAREA MECANICĂ LA DREAPTA: Cardul glisează ca un sertar magnetic la scanare */
}

/* Activarea animației native de pulsare pe titluri */
.future-log:hover h5 {
  animation: pulse 1s infinite; /* Rulează motorul continuu de pulsare rapidă definit la începutul fișierului */
  color: var(
    --amber-glow
  ); /* Comută textul stabil pe lungimea de undă chihlimbar de alertă activă */
}

/* Re-potrivirea cromatică a insignei de titlu în starea de hover general */
.future-log:hover h4 {
  background-color: var(
    --amber-glow
  ); /* Eticheta superioară comută din violet în chihlimbar solid în mod automat */
  color: var(
    --space-dark
  ); /* Textul devine negru profund pentru o claritate extremă pe placa aprinsă */
  box-shadow: 0 0 15px var(--amber-glow); /* Încarcă perimetrul badge-ului cu o puternică aură laser chihlimbar */
}

/* Comportamentul dinamic al liniilor interioare de ghidaj din capsulele viitoare */
.future-log .sub-log {
  border-left-color: rgba(
    255,
    179,
    0,
    0.2
  ); /* Stare latentă: linia punctată se retrage într-o opacitate abia sesizabilă */
  transition: border-color 0.5s ease; /* Pregătește o aprindere fluidă și fină a ghidajului structural */
}

.future-log:hover .sub-log {
  border-left-color: var(
    --amber-glow
  ); /* Linia de ghidaj se încarcă instantaneu cu tensiune chihlimbar completă */
}
```

11. **MODULE 11: FOOTER TERMINAL // MISSION COORDINATES (PANOUL DE SUBSOL)**

**REZUMAT / SUMMARY**: Acest modul configurează blocul final de închidere structurală a machetelor standard (`.footer`). El implementează un scut protector din sticlă fumurie Solaris semi-transparentă, delimitat superior de o linie laser dublă violet-roz, și rulează un motor rigid Flexbox pe verticală pentru a alinia simetric toate metadatele de telemetrie, indicatorii de stare online și semnăturile digitale ale echipajului.

- **Selectorul Master `.footer` (Carcasa Metalică de Subsol)**
  - **Rolul în context**: Targetează containerul macro de închidere al paginii (`<footer class="footer">`), delimitând podeaua fizică a cockpit-ului.
  - **Misiune**: Impune un „vid vertical” protector de `120px` sub ultimul log pentru a decupla subsolul de restul narațiunilor. Activează o sticlă fumurie la 40% opacitate cu blur de `10px` și desenează o bordură laser dublă violet-roz (`border-top: 1px double rgba(157, 23, 248, 0.2)`). Forțează alinierea centrală absolută pe desktop prin combinarea directivelor flexibile verticale (`flex-direction: column`, `align-items: center`).

- **Selectorul `.footer:hover` (Suprasarcina Cromatică de Subsol)**
  - **Rolul în context**: Interceptează starea dinamică a panoului în milisecunda în care cursorul echipei intersectează baza ecranului.
  - **Misiune**: Trezește panoul la viață: comută opacitatea de la starea stinsă de repaus (`0.8`) la luminozitatea totală (`1`) și aprinde linia laser superioară direct pe spectrul roz-magenta intens (`var(--nebula-pink)`).

- **Selectorul `.footer p, .footer .copyright` (Liniile de Telemetrie / Metadata Streams)**
  - **Rolul în context**: Targetează toate paragrafele interioare și textele de drepturi de autor stocate în subsol.
  - **Misiune**: Forțează utilizarea fontului rigid mecanic de cod `monospace` la o dimensiune radar redusă de `0.75rem`. Aplică majuscule de protocol, un letter-spacing larg industrial de `3px` și un margin vertical strâns de `8px` pentru a opri lăbărțarea sau suprapunerea rândurilor.

- **Selectorii de Accent `span.telemetry-active` și `span.vessel-sig` (Fisurile Fotonice)**
  - **Rolul în context**: Targetează micro-cuvintele cheie din text (statusul online și numele creatorului) pentru a introduce contraste locale în subsol.
  - **Misiune**: `.telemetry-active` aprinde textul îngroșat pe verde-mentă fosforic cu o aureolă neon de `5px`. `.vessel-sig` mută semnătura pe roz-magenta intens cu un halou protector roz stelar de `5px`.

```
/* ==========================================================================
    MODULE 11: FOOTER TERMINAL // MISSION COORDINATES (VERSIUNEA MINIMALISTĂ)

    NOTĂ ARHITECTURALĂ DIDACTICĂ: Acest modul este plasat strategic înaintea
    sistemelor 3D și poligonale avansate pentru a încheia fluxul de layout
    structural standard. Menținerea subsolului aici oferă studenților un moment
    de respirație vizuală înainte de plonjarea în matrici complexe de coordonate.
   ========================================================================== */

/* --- 1. STRUCTURA MACRO A SECTORULUI DE SUBSOL (The Footer Base Frame) --- */
.footer {
  margin-top: 120px; /* Împinge fizic subsolul departe de ultimul container de articol de sus */
  background: rgba(
    13,
    15,
    20,
    0.4
  ); /* Fundal original transparent din sticlă fumurie Solaris pentru panouri */
  backdrop-filter: blur(
    10px
  ); /* Efect cinematic profund care estompează elementele ce trec pe sub bară */
  border-top: 1px double rgba(157, 23, 248, 0.2); /* Linie laser dublă în nuanța originală violet-roz de demarcație */
  box-shadow: inset 0 10px 20px rgba(0, 0, 0, 0.4); /* Umbră interiorară discretă ce oferă adâncime sticlei fumurii */
  position: relative; /* Deschide context local de coordonate pentru elementele grafice interne */
  opacity: 0.8; /* Aspect stins la 80% în starea de repaus pentru protecția ochilor utilizatorului */
  transition: opacity 0.3s ease; /* Tranziție fluidă de răspuns a luminozității la interacțiunea cu cursorul */
  padding: 40px 20px !important; /* Pernă interioară forțată de aer ce încadrează stabil pachetul tehnic */
  box-sizing: border-box; /* Include padding-ul în calculul lățimii pentru a bloca overflow-ul structural */

  /* CENTRAREA ȘI MARJAREA ABSOLUTĂ PE MONITOARELE DESKTOP */
  margin-left: auto !important; /* Blochează marja stângă pentru a opri decalajele orizontale nealiniate */
  margin-right: auto !important; /* Blochează marja dreaptă pentru a asigura centrarea pe mijlocul ecranului */
  display: flex !important; /* Activează subsistemul Flexbox rigid pentru gestionarea rândurilor interne */
  flex-direction: column !important; /* Așază rândurile de telemetrie în mod rigid pe verticală, unul sub altul */
  align-items: center !important; /* Centrează perfect toate componentele pe mijlocul axei orizontale */
  justify-content: center !important; /* Centrează geometric întregul pachet pe axa verticală a containerului */
}

/* EFECT LA HOVER PESTE SUBSOLUL DE COMANDĂ (Suprasarcina Luminoasă) */
.footer:hover {
  opacity: 1; /* Luminozitate totală nominală la intersecția cursorului cu monitorul */
  border-top-color: var(
    --nebula-pink
  ); /* Laserul dublu superior se aprinde intens pe nuanța roz-magenta */
}

/* --- 2. ENCAPSULAREA LINKULUI DE BIBLIOGRAFIE (The External Comms Box) --- */
.footer .external-comms {
  display: flex !important; /* Activează rețeaua Flexbox locală pentru a menține forma curată */
  justify-content: center !important; /* Menține capsula butonului blocată fix pe mijlocul axei verticale */
  margin-bottom: 25px !important; /* Spațiu protector de siguranță sub buton înainte de rândurile de text */
  width: auto !important; /* Împiedică lărgirea sau lăbărțarea laterală artificială a butonului pe ecran */
}

/* --- 3. STRUCTURA TEXTULUI DE TELEMETRIE ȘI DATE (The Metadata Rows) --- */
.footer p,
.footer .copyright {
  font-family: monospace; /* Font rigid mecanic de cod ce reproduce aspectele textelor de terminal */
  font-size: 0.75rem; /* Dimensiune tehnică redusă, specifică ecranelor și radarelor secundare */
  color: var(
    --stardust
  ); /* Text alb industrial stardust original, conceput special anti-oboseală */
  letter-spacing: 3px; /* Spațiere largă tehnică industrială între caractere pentru aspect militar */
  text-transform: uppercase; /* Protocol obligatoriu de bord: forțează utilizarea literelor mari capitalizate */
  margin: 8px 0 !important; /* Distanță fină verticală între rânduri pentru a bloca suprapunerile de text */
  text-align: center !important; /* Centrează absolut textul în interiorul fiecărei linii de tracking */
  width: auto !important; /* Oprește extinderea artificială a lățimii textului în interiorul grilei */
}

/* --- 4. ACCENTE LUMINOASE ÎNCASTRATE PENTRU CONTRAST (Luminescent Sparks) --- */
/* Indicatorul verde-mentă de status online al sistemelor active */
.footer span.telemetry-active {
  color: var(
    --solar-mint
  ) !important; /* Textul se aprinde stabil pe frecvența verde-mentă fosforică a navei */
  text-shadow: 0 0 5px var(--solar-mint) !important; /* Generează o aureolă luminoasă difuză de neon în jurul literelor */
  font-weight: bold; /* Îngroașă caracterele pentru o definiție maximă pe ecranul întunecat */
}

/* Semnătura de constructor în nuanța roz-magenta a reactorului principal */
.footer span.vessel-sig {
  color: var(
    --nebula-pink
  ) !important; /* Mută textul direct pe lungimea de undă roz-magenta intens de alertă */
  text-shadow: 0 0 5px var(--nebula-pink) !important; /* Proiectează un halou protector roz stelar în jurul semnăturii */
  font-weight: bold; /* Forțează caracterele îngroșate pentru contrast industrial ridicat */
}
```

12. MODULE 12: GEOMETRIC SYSTEM // PORTALE POLIGONALE SECTOR (OCTAGONAL STYLE)

**REZUMAT**: Acest modul construiește nodurile de navigare octogonale compacte, profilate laser în interiorul meniului din sidebar (`.sidebar-nav`). El rulează un motor `inline-flex` pentru centrarea axială a textului liliputan de `0.6rem !important`, folosește un fundal de 15% mov stins și deblochează o matrice procentuală în 8 puncte (`clip-path`) pentru a asambla butoane tactile cu unghiuri rigide la 45 de grade.

- **Selectorul Grupat `.sidebar-nav .week-label a, .sidebar-nav .sector-link` (Tastele Hardware Octogonale)**
  - **Rolul în context**: Targetează exclusiv elementele de tip ancoră și butoanele de legătură plasate în interiorul meniului asimetric de navigare din sidebar (`<div class="sidebar-nav">`). Acestea acționează ca noduri active de rețea, folosite pentru comutarea vizuală între capitolele de studiu și volumele de loguri ale navei.
  - **Misiune**: Purifică și rescrie complet comportamentul nativ al ancorelor de internet. Activează un aliniator central compact și rigid (`display: inline-flex !important`, `align-items: center`, `justify-content: center`) pentru a bloca textul perfect pe mijlocul capsulei. Scurtează fontul mecanic `monospace` la o proporție tehnică liliputană fină de `0.6rem !important` pe o nuanță violet stelar opacizată la `0.85`. Slicuiește simetric cele patru colțuri exterioare ale cutiei model la un unghi rigid de 45° prin intermediul unei matrice procentuale în 8 puncte (`clip-path: polygon(...)`), adaugă o pernă compactă de aer (`padding: 4px 10px !important`) și blochează revărsările sau spargerile de text prin directiva rigidă `white-space: nowrap`.

- **Selectorul de Stare Dinamică la Hover `.sidebar-nav .week-label a:hover, .sidebar-nav .sector-link:hover` (Suprasarcina Cromatică și Micro-Mărirea Kinetică)**
  - **Rolul în context**: Interceptează momentul fizic exact în care cursorul echipajului intersectează sau atinge coordonatele spatiale ale unei taste octogonale din sidebar, declanșând faza de activare a nodului.
  - **Misiune**: Rulează o reîncărcare electronică de tensiune instantanee pe tot ecranul tastei selectate: comută fundalul translucid într-o mască solidă de violet necomprimat (`var(--nebula-purple) !important`) și virează culoarea literelor în alb pur pentru a obține un contrast militar maxim. Ridică luminozitatea la intensitate nominală totală (`opacity: 1`), injectează o aureolă fluorescentă difuză de `12px` în jurul elementului și execută o micro-mărire fluidă de 5% pe ecran (`transform: scale(1.05)`) pentru a oferi un feedback kinetic curat.

```
/* ==========================================================================
    MODULE 12: GEOMETRIC SYSTEM // PORTALE POLIGONALE SECTOR (OCTAGONAL STYLE)

    REZUMAT: Acest modul construiește nodurile de navigare octogonale compacte,
    profilate laser în interiorul meniului din sidebar (.sidebar-nav). El rulează
    un motor inline-flex, comprimă textul la o proporție tehnică de 0.6rem și
    activează o matrice procentuală în 8 puncte (clip-path) pentru a simula tastele
    tactile ale unui bord de zbor.
   ========================================================================== */

/* --- 1. TASTELE HARDWARE DE NAVIGARE ÎN SIDEBAR (Butoane Poligonale Octogonale) --- */
.sidebar-nav .week-label a,
.sidebar-nav .sector-link {
  display: inline-flex !important; /* Aliniază textul perfect pe centrul geometric interior al portalului */
  align-items: center;
  justify-content: center;

  font-family: monospace;        /* Font rigid mecanic de cod ce păstrează aspectul tehnic al consolei */
  font-size: 0.6rem !important;  /* Proporție tehnică liliputană fină, calibrată pentru economisirea spațiului HUD */
  color: var(--nebula-purple) !important; /* Culoarea ta originală stabilă violet stelar ce definește elementele */
  background: rgba(60, 44, 140, 0.15) !important; /* Fundal translucid original format dintr-o tentă de 15% mov stins */
  border: 1px solid rgba(60, 44, 140, 0.4) !important; /* Chenar micro-fin de control ce trasează perimetrul tastei */

  padding: 4px 10px !important;  /* Umplutură compactă originală strânsă în jurul blocului de litere */
  letter-spacing: 1px;           /* Spațiere fină stabilă între caractere pentru claritate structurală */
  text-decoration: none;         /* Elimină sublinierea nativă inestetică injectată automat de browsere */
  text-transform: uppercase;     /* Protocol militar obligatoriu: forțează utilizarea literelor mari capitalizate */
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important; /* Curbă cinematică fluidă de accelerare la atingere */
  white-space: nowrap;           /* SCUT DE DISPUNERE: Interzice cu desăvârșire textului să se fragmenteze pe rânduri */
  opacity: 0.85;                 /* Opacitate de repaus ce protejează monitorul de uzura emisiilor de lumină */

  /* --- INJECTAREA LASERULUI POLIGONAL (Tăierea octogonală la 45 de grade) ---
      Această formulă matematică procentuală în 8 puncte taie cu precizie colțurile exterioare,
      imitând perfect ecranele tactile hardware de pe instrumentele navelor spațiale. */
  clip-path: polygon(
    30% 0%,
    70% 0%,
    100% 30%,
    100% 70%,
    70% 100%,
    30% 100%,
    0% 70%,
    0% 30%
  );
}

/* --- 2. EFECT HOVER ELECTRIC PESTE PORTALUL POLIGONAL VIOLET (Validare Proximity) --- */
.sidebar-nav .week-label a:hover,
.sidebar-nav .sector-link:hover {
  background: var(--nebula-purple) !important; /* Portalul absoarbe energie și se aprinde intens pe violet solid cosmic */
  color: white !important;       /* Textul devine alb curat pentru un contrast militar maxim pe placa aprinsă */
  opacity: 1;                    /* Trecere la luminozitate totală nominală pe parcursul selectării */
  box-shadow: 0 0 12px var(--nebula-purple) !important; /* Generează o aureolă luminoasă difuză de neon violet în jur */
  transform: scale(1.05);        /* MICRO-EXPANSIUNE CINEMATICĂ: Tasta se mărește ușor la confirmarea prin atingere */
}
```

13. **Module 13: The Holo-Geodesic Engine (Arhitectura Reactoarelor 3D)**

După ce cascada a securizat containerele macro ale punții de intrare (Modulul 04) și elementele navigației HUD (Modulul 05), ea coboară în interiorul **Centrului Energetic al Navei Mamă**. Modulul 07 asamblează Reactorul Armilar Tridimensional, transformând ecranul bidimensional într-o lentilă stereoscopică profundă.

După configurarea elementelor tipografice mari și a textelor ștanțate de impact (Modulul 06), cascada stilistică pătrunde în inima matematică a ecranului principal. Modulul 07 deschide o lentilă de perspectivă virtuală cubică în browser pentru a randa Icosaedrul poliedric tridimensional (Sfera Plasmatică), fețele sale triunghiulare laser și inelele concentrice ale Astrolabului în rotație permanentă.

- Selectorul `.armillary-reactor-core` (Lentila Cubic-Virtuală Master)
  - **Rolul în context**: Targetează containerul macro volumetric plasat în centrul paginii de index, acționând ca o cameră video virtuală ce filmează pe axele X, Y și Z.
  - **Misiune**: Deschide spațiul tridimensional real în interiorul browserului prin proprietatea `perspective: 1400px !important` și deblochează obligatoriu axa Z pentru toate elementele interioare prin directiva `transform-style: preserve-3d !important`, forțându-le să își păstreze volumul și să nu fie turtite într-un plan plat bidimensional. Eliberează geometric pachetul prin Flexbox vertical și curăță pernele de aer superioare.

- Selectorul `.quantum-plasma-sphere` (Miezul Rotativ al Grilei Spațiale)
  - **Rolul în context**: Targetează scheletul sferic central, nodul zero poliedric în jurul căruia orbitează restul componentelor reactorului.
  - **Misiune**: Definește o arenă fixă simetrică de dimensiune masivă (`460px`), menține randarea volumetrică interioară și rulează motorul de propulsie continuă pe axa Y prin animația `spin-geodesic-core` de 25 de secunde, antrenând toate cele 20 de fețe într-o mișcare perpetuă liniară.

- Selectorul `.quantum-plasma-sphere .face` (Panourile Poligoanelor Triunghiulare)
  - **Rolul în context**: Targetează clasa generală aplicată fiecăreia dintre cele 20 de piese din sticlă care asamblează suprafața Icosaedrului regulat.
  - **Misiune**: Fixează dimensiunea uniformă a fiecărui fragment, centrează geometric piesa prin marje negative pe coordonatele de origine și decupează triunghiul perfect prin directiva `clip-path: polygon(...)`. Injectează o mască de sticlă acrilică cu gradient și un blur fin (`backdrop-filter: blur(2px)`), forțând în același timp fețele din spate să rămână vizibile prin transparență (`backface-visibility: visible !important`).

- Selectorii Grupați de Poziționare `.face-t1` ... `.face-b5` (Matricea de Coordonate Vectoriale) Cartografierea Vectorială Tridimensională (Cele 4 Punți ale Icosaedrului):
  - Pentru a asambla un corp poliedric volumetric cu 20 de fețe în CSS, ecranul este împărțit în patru straturi (punți) unghiulare rigide. Fiecare clasă reprezintă o coordonată spațială fixă în vid:
    - **Punțile Polare (`t` și `b`)**: Țintesc zonele de închidere ale reactorului. `t` (Top) asamblează calota nordică, iar `b` (Bottom) încapsulează calota sudică. Ele folosesc o înclinație stabilă de `52.62deg` pe axa X.
    - **Punțile Ecuatoriale (`u` și `l`)**: Formează centura de forță a reactorului. `u` (Upper) gestionează coroana superioară, iar `l` (Lower) rulează coroana inferioară (triunghiuri inversate la `180deg`). Ele folosesc o înclinație fină de `10.81deg` pentru a se îmbina la milimetru.
    - **Frecvența Roz de Alertă (Alternanța Laser)**: Din considerente de contrast industrial, fețele pare (`t2`, `t4`, `u2`, `u4`, `l2`, `l4`, `b2`, `b4`) primesc directiva `border-color: var(--nebula-pink) !important`. Această intercalare cromatică sparge monotonia verde-mentă și generează pe ecran aspectul de plasă electrică alternantă în timpul rotației asincrone.
  - **Rolul în context**: Targetează individual fiecare dintre cele 20 de fețe, împărțite pe patru punți/straturi unghiulare: `t` (Top/Nord), `u` (Upper-Middle), `l` (Lower-Middle) și `b` (Bottom/Sud).
  - **Misiune**: Execută transformări matematice angulo-axiale tridimensionale de precizie chirurgicală. Combină rotații pe axa Y în pași exacți de `72deg` (360° împărțit la 5 segmente simetrice) cu înclinații fixe pe axa X (`52.62deg` pentru calote și `10.81deg` pentru centura ecuatorială) și le împinge în exterior pe raza orbitală stabilă prin `translateZ(210px)`. De asemenea, alternează cromatic fețele pare pe culoarea roz-neon (`--nebula-pink`).

- Selectorul `.armillary-reactor-core:hover .quantum-plasma-sphere` (Suprasarcina Kinetică a Miezului)
  - **Rolul în context**: Targetează starea dinamică a întregului nucleu sferic în momentul în care cursorul echipajului atinge reactorul 3D.
  - **Misiune**: Introduce o descărcare termică masivă, forțând durata animației de rotație să scadă brusc de la 25 de secunde la doar `6s !important`, generând o accelerare cinetică extrem de violentă și fluidă a întregului ansamblu volumetric.

- Selectorul `.armillary-reactor-core:hover .face` (Fuziunea Energetică a Panourilor)
  - **Rolul în context**: Targetează cele 20 de fețe de sticlă simultan, exclusiv în timpul stării de hover pe reactor.
  - **Misiune**: Îngroașă mecanic liniile laser ale triunghiurilor la `1.5px` și activează motorul de animație flicker rapidă `lightning-glow-fusion` la o frecvență de `0.12s` infinit alternantă.

- Selectorul `.armillary-band-container` (Straturile HUD Ecuatoriale / Astrolabul)
  - **Rolul în context**: Targetează containerul structural care plutește pe orizontala miezului 3D, acționând ca o centură metalică ecuatorială ce încapsulează benzile de text texturate.
  - **Misiune**: Centrează perfect benzile de text pe axa centrală a ecranului prin Flexbox unificat, limitează lățimea maximă la `780px` pentru a proteja lizibilitatea pe monitoare ultra-wide și impune un `z-index: 5` agresiv.

- Cooperarea Wrapperelor `.macro-wrapper` și `.micro-wrapper` (Poziționarea Axială)
  - **Rolul în context**: Targetează cele două inele de text separate pentru a le stabili cota fixă de altitudine pe ecran.
  - **Misiune**: Blochează poziționarea absolută și impune distanțe milimetrice pe verticală (`top: 200px` pentru inelul mare și `top: 265px` pentru inelul mic), forțându-le să se așeze simetric deasupra și dedesubtul ecuatorului virtual al sferei.

- Selectorul `.astrolabe-metal-arc` (Șasiul de Sticlă al Benzilor de Text)
  - **Rolul în context**: Targetează fundalul tehnic întunecat care rulează în spatele literelor ștanțate de pe inele.
  - **Misiune**: Întinde o mască lungă de tip capsulă (border-radius: 50px), injectează un blur fin de 4px pentru a estompa triunghiurile 3D care trec prin spatele ei și încarcă un gradient liniar la 90° care se topește în opacitate zero spre capete, lăsând centrul opac.

- Selectorii Pseudo-Element `.macro-wrapper::after` și `.micro-wrapper::after` (Tăieturile Laser de Demarcație)
  - **Rolul în context**: Targetează două linii virtuale generate automat la baza celor două inele astrolab.
  - **Misiune**: Șterg granițele rigide și desenează fire laser micro-fine de 1px înălțime, întinse pe 90% din lățime. Inelul macro primește un gradient laser roz-neon, iar inelul micro primește un gradient verde-mentă, ambele fiind animate asincron prin cosmic-flicker cu un decalaj termic de 2 secunde.

```
/* ==========================================================================
    MODULE 13: THE HOLO-GEODESIC ENGINE (COSMIC FLICKER CALIBRATION)

    REZUMAT: Acest modul consolidează nucleul armilar tridimensional central
    din cockpit-ul navei. El deschide o matrice profundă de cameră virtuală (1400px),
    activează rețeaua de coordonate spațiale preserve-3d pentru cele 20 de fețe
    geodezice ale icosaedrului și configurează inelele eliptice ale astrolabului.
    Modulul controlează descărcări fosforice alternative și gradienți radiali pentru
    a genera pulsații de neon locale la trecerea cursorului echipajului.

    Acest modul guvernează motorul geometric tridimensional de pe nava
    mamă. El deschide o lentilă de perspectivă virtuală cubică în browser pentru
    a randa Icosaedrul poliedric tridimensional (Sfera Plasmatică), inelele sale
    laser concentrice punctate (Astrolabul) și fețele sale triunghiulare în rotație
    asincronă permanentă, transformând ecranul Hero într-un radar tactil volumetric.
   ========================================================================== */

/* --- 1. LENTILA CUBIC-VIRTUALĂ MASTER (Reactorul Armilar) --- */
.armillary-reactor-core {
  position: relative; /* Coordonate rădăcină pentru elementele interioare poziționate absolut */
  display: flex !important; /* Activează Flexbox pentru stivuirea pe verticală a blocurilor de date */
  flex-direction: column !important; /* Aranjează benzile paralele de telemetrie direct una sub cealaltă */
  align-items: center !important; /* Centrează geometric sfera centrală și etichetele pe axa orizontală */
  justify-content: center !important; /* Centrează întregul modul tehnic pe verticală în secțiunea hero */
  margin-top: 140px !important; /* Împinge reactorul în jos pentru a preveni suprapunerea cu navbar-ul fix */
  margin-bottom: 140px !important; /* Pernă simetrică de aer ce izolează layout-ul de grila de categorii */
  width: 100% !important; /* Se extinde pe toată lățimea utilă fără a genera scrollbar orizontal */
  height: 540px !important; /* Înălțime fixă, rigidă, ce definește amprenta verticală a reactorului */
  background: transparent !important; /* Păstrează vizibilă textura de monitor CRT globală din spatele său */
  box-sizing: border-box; /* Include padding-ul în dimensiuni pentru a proteja liniile de graniță */

  /* MOTORUL DE DEPLOYMENT AL MATRICEI TRIDIMENSIONALE */
  transform-style: preserve-3d !important; /* COMANDĂ CRUCIALĂ: Deblochează axa Z reală în interiorul browserului */
  perspective: 1400px !important; /* Distanța camerei virtuale; oferă adâncime cubică și impact cinematic */

  /* RESETARE SCUT DEATERIZARE ANCORE HUD */
  scroll-margin-top: 90px !important; /* Compensează navbar-ul fix, lăsând un spațiu la saltul din logo */
}

/* --- 2. MIEZUL ROTATIV AL GRILEI SPAȚIALE (Icosaedrul Volumetric) --- */
.quantum-plasma-sphere {
  position: absolute !important; /* Plutește independent în centrul geometric absolut al reactorului */
  width: 460px !important; /* Diametru masiv calibrat pentru a cuprinde etichetele tehnice */
  height: 460px !important; /* Potrivește fix dimensiunile pentru a bloca parametrii unui cerc perfect */
  z-index: 1; /* Nivel de bază în spatele benzilor de text translucide ale HUD-ului */
  transform-style: preserve-3d !important; /* Forțează cele 20 de fețe triunghiulare să se rotească tridimensional */

  /* CUPLAREA PROPULSIEI CENTRALE: Rotație continuă la viteză nominală pe axa verticală Y */
  animation: spin-geodesic-core 25s infinite linear !important;
}

/* Structura de sticlă lucioasă ce mapează cele 20 de poligoane triunghiulare */
.quantum-plasma-sphere .face {
  position: absolute !important; /* Grupează concentric toate fețele în jurul nodului geometric zero */
  top: 50% !important;
  left: 50% !important; /* Ancorează punctul de pornire pentru buclele de deplasare 3D */
  width: 220px !important; /* Dimensiuni calibrate pentru panourile vectoriale individuale */
  height: 190px !important;
  margin-left: -110px !important; /* Decalaj negativ pentru a centra perfect piesa pe coordonatele de origine */
  margin-top: -95px !important;
  backdrop-filter: blur(
    2px
  ); /* Filtru optic cinematic fin în interiorul fiecărui geam de sticlă */
  transform-origin: center center !important; /* Setează centrul geometric ca punct de rotație al feței */
  backface-visibility: visible !important; /* PROTOCOL CRUCIAL: Permite fețelor din spate să rămână vizibile prin sticlă */

  /* MASCĂ DE TĂIETURĂ TRIUNGHIULARĂ RIGIDĂ */
  clip-path: polygon(50% 0%, 100% 100%, 0% 100%) !important;

  /* STRATIFICARE GRADIENT SPECTRAL */
  background: linear-gradient(
    135deg,
    rgba(167, 243, 208, 0.05) 0%,
    rgba(255, 0, 127, 0.03) 50%,
    rgba(255, 255, 255, 0.12) 100
  ) !important;
  border: 1px solid rgba(167, 243, 208, 0.3) !important; /* Fir laser inițial verde-mentă de joasă tensiune */
}

/* --- 3. MATRICEA DE COORDONATE VECTORIALE/VECTOR SPACE MAP (Raza Orbitală Absolută R = 210px) ---*/
/* Exegeza matematică a celor 20 de fețe ale Icosaedrului. */

/* --- PUNTEA SUPERIOARĂ "TOP" (Calota Nordică: Înclinație X = 52.62° / Rotație Y în pași de 72°) --- */
.face-t1 {
  transform: rotateY(0deg) rotateX(52.62deg) translateZ(210px);
}
.face-t2 {
  transform: rotateY(72deg) rotateX(52.62deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
} /* Alertez cromatic fața 2 pe roz */
.face-t3 {
  transform: rotateY(144deg) rotateX(52.62deg) translateZ(210px);
}
.face-t4 {
  transform: rotateY(216deg) rotateX(52.62deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
} /* Alertez cromatic fața 4 pe roz */
.face-t5 {
  transform: rotateY(288deg) rotateX(52.62deg) translateZ(210px);
}

/* --- PUNTEA ECUATORIALĂ "UPPER" (Coroana de Sus: Înclinație X = 10.81° / Decalaj orizontal de 36°) --- */
.face-u1 {
  transform: rotateY(36deg) rotateX(10.81deg) translateZ(210px);
}
.face-u2 {
  transform: rotateY(108deg) rotateX(10.81deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-u3 {
  transform: rotateY(180deg) rotateX(10.81deg) translateZ(210px);
}
.face-u4 {
  transform: rotateY(252deg) rotateX(10.81deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-u5 {
  transform: rotateY(324deg) rotateX(10.81deg) translateZ(210px);
}

/* --- PUNTEA ECUATORIALĂ "LOWER" (Coroana de Jos: Triunghiuri răsturnate la 180° / Înclinație X = 10.81°) --- */
.face-l1 {
  transform: rotateY(0deg) rotateX(180deg) rotateX(10.81deg) translateZ(210px);
}
.face-l2 {
  transform: rotateY(72deg) rotateX(180deg) rotateX(10.81deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-l3 {
  transform: rotateY(144deg) rotateX(180deg) rotateX(10.81deg) translateZ(210px);
}
.face-l4 {
  transform: rotateY(216deg) rotateX(180deg) rotateX(10.81deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-l5 {
  transform: rotateY(288deg) rotateX(180deg) rotateX(10.81deg) translateZ(210px);
}

/* --- PUNTEA INFERIOARĂ "BOTTOM" (Calota Sudică: Răsturnare totală la 180° / Înclinație X = 52.62°) --- */
.face-b1 {
  transform: rotateY(36deg) rotateX(180deg) rotateX(52.62deg) translateZ(210px);
}
.face-b2 {
  transform: rotateY(108deg) rotateX(180deg) rotateX(52.62deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-b3 {
  transform: rotateY(180deg) rotateX(180deg) rotateX(52.62deg) translateZ(210px);
}
.face-b4 {
  transform: rotateY(252deg) rotateX(180deg) rotateX(52.62deg) translateZ(210px);
  border-color: var(--nebula-pink) !important;
}
.face-b5 {
  transform: rotateY(324deg) rotateX(180deg) rotateX(52.62deg) translateZ(210px);
}

/* --- 4. MATRICEA DE SUPRASARCINĂ KINETICĂ (Hărțile de Fuziune Energetică) --- */
.armillary-reactor-core:hover .quantum-plasma-sphere {
  animation-duration: 6s !important; /* Accelerează ciclul de rotație la 6 secunde, simulând un salt de energie */
}

.armillary-reactor-core:hover .face {
  border-width: 1.5px !important; /* Îngroașă liniile laser ale fețelor la interacțiunea cu operatorul */
  border-style: solid !important;
  /* SCURTCIRCUIT FLICKER: Declanșează arcuri de fulgere fosforice la o frecvență ridicată, alternantă */
  animation: lightning-glow-fusion 0.12s infinite alternate ease-in-out !important;
}

/* --- 5. STRATURILE HUD ECUATORIALE (Inelele Concentrice ale Astrolabului) --- */
.armillary-band-container {
  position: absolute !important; /* Izolează și suspendă benzile structurale pe orizontala miezului */
  display: flex !important; /* Ancorează nodurile interne de aliniere perfect pe axa centrală comună */
  align-items: center !important;
  justify-content: center !important;
  width: 90% !important; /* Spațiu elastic de acoperire ce umple curat zona tehnică buffer */
  max-width: 780px !important; /* Limită rigidă ce protejează layout-ul pe monitoarele ultra-wide */
  z-index: 5; /* Prioritate de elevare: plutește explicit deasupra fețelor 3D din fundal */
}

/* Coordonate calibrate de plasament vertical extrase din geometria de bază a navei */
.macro-wrapper {
  top: 200px !important;
  height: 65px !important;
}
.micro-wrapper {
  top: 265px !important;
  height: 45px !important;
}

/* Șasiu de tip capsulă din sticlă fumurie care ancorează benzile de text */
.astrolabe-metal-arc {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  backdrop-filter: blur(
    4px
  ); /* Blurează liniile geometrice din fundal ce trec prin carcasa astrolabului */
  border-radius: 50px !important; /* Geometrie fluidă de capsulă ce creează aspectul de panou tehnic */
  z-index: -1; /* Alunecă în spatele textului ștanțat pentru a asigura un contrast absolut */
  background: linear-gradient(
    90deg,
    transparent 0%,
    rgba(10, 11, 30, 0.45) 30%,
    rgba(10, 11, 30, 0.45) 70%,
    transparent 100
  ) !important;
}

/* SEPARATORI LASER DE MARE PRECIZIE (Înlocuiesc vechile granițe rigide de bloc) */
.macro-wrapper::after,
.micro-wrapper::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 5%;
  width: 90%;
  height: 1px;
  pointer-events: none; /* Doar emisie vizuală de energie: click-urile trec liber prin strat */
}

/* Linie fină de blitz de înaltă frecvență, localizată pe roz-neon */
.macro-wrapper::after {
  background: linear-gradient(
    90deg,
    transparent 0%,
    var(--nebula-pink) 50%,
    transparent 100
  ) !important;
  animation: cosmic-flicker 4s infinite ease-in-out !important; /* Tremur cosmic nativ integrat */
}

/* Fir laser verde-mentă fosforic, temporizat cu un delay de 2s pentru contrast mecanic */
.micro-wrapper::after {
  background: linear-gradient(
    90deg,
    transparent 0%,
    var(--solar-mint) 50%,
    transparent 100
  ) !important;
  animation: cosmic-flicker 4s infinite ease-in-out 2s !important; /* Sincronizare în buclă întreruptă */
}
```

14. **MODULE 14: BLUEPRINT OVERLAY // DESIGN SPECIFIC PENTRU INTERFAȚA RECURSIVĂ**

**REZUMAT / SUMMARY**: Acest modul finalizează ierarhia stilistică a proiectului, funcționând ca o incintă izolată dedicată exclusiv ecranului de documentație master (`recursive-blueprint.html`). El orchestrează dispunerea asimetrică de tip split-screen (panouri paralele), formatează monitorul catodic virtual din dreapta pentru inspectarea sintaxei și deblochează reținerea spațială a axei Z prin filtrul de scalare, forțând mini-Icosaedrul 3D să execute o horă luminoasă fluidă și scurtcircuite electrice de înaltă frecvență la atingere.

- **Selectorul Master `.blueprint-container` (Scutul Axial al Blueprint-ului)**
  - **Rolul în context**: Targetează containerul structural master care încapsulează întreaga rețea modulară a paginii recursive.
  - **Misiune**: Impune o limitare rigidă a lățimii maxime la `1300px` pentru a opri lăbărțarea textului pe monitoare ultra-wide, centrează automat structura pe mijlocul ecranului prin `margin: 100px auto` și oferă o pernă interioară de aer de `20px` pentru a proteja marginile utilitare.

- **Selectorul `.terminal-split` (Rețeaua Macro Split-Screen)**
  - **Rolul în context**: Targetează zona intermediară de layout care desparte ecranul în două emisfere paralele: Documentația în stânga și Inspectorul de Cod în dreapta.
  - **Misiune**: Activează motorul de layout Flexbox, forțând în mod dictatorial așezarea pe rând orizontal (`flex-direction: row !important`) pe ecranele mari de desktop, și fixează o distanță laser rigidă de izolare de `30px` (`gap`) între cele două ecrane tactice.

- **Selectorul `.panel` și `.panel-title` (Capsulele Hermetice din Panou)**
  - **Rolul în context**: Targetează cutiile individuale care susțin conținutul didactice și titlurile lor de rang tehnic.
  - **Misiune**: `.panel` împarte ecranul în mod egal (`flex: 1 !important`) și încarcă o sticlă fumurie închisă (`rgba(10, 11, 30, 0.45)`) protejată de un border fin verde-mentă de 15% opacitate și o umbră tridimensională de `40px` pentru levitație. `.panel-title` aprinde textul pe spectrul verde-mentă fosforic (`var(--solar-mint)`) cu majuscule de protocol și o linie punctată la bază.

- **Selectorul `.code-inspector-screen` (Șasiul Central al Inspectorului de Cod)**
  - **Rolul în context**: Targetează ecranul negru din dreapta utilizat pentru afișarea și inspectarea codului live.
  - **Misiune**: Fixează o înălțime nominală rigidă de `520px !important`, încarcă un fundal negru oarbă catodic (`#04050a`) și un padding superior extins de `25px` pentru a evita coliziunea textului cu eticheta superioară. Deplasează scrollbar-urile pe ambele axe și generează o curbă fizică de monitor bombat prin `inset box-shadow`. Textul se aprinde pe o nuanță argintiu-indigo industrial (`#a4b3c6`) cu netezire antialiased.

- **Selectorul Pseudo-Element `.code-inspector-screen::before` (Eticheta de Diagnostic CRT)**
  - **Rolul în context**: Generează în mod automat un șir de text tehnic în colțul din dreapta-sus al monitorului catodic.
  - **Misiune**: Injectează textul de sistem `"DATA STREAM ACTIVE // NOMINAL"`. Îl suspendă absolut la `top: 6px !important` și `right: 12px !important`, îl vopsește în verde-mentă fosforic cu o aureolă de neon (`text-shadow`) la o opacitate de 75% și un `z-index: 10` prioritar.

- **Selectorul `.recursive-reactor-wrapper` (Scutul Spațial al Mini-Reactorului)**
  - **Rolul în context**: Targetează containerul special din panoul din stânga folosit pentru a izola și expune varianta miniaturală a reactorului poliedric.
  - **Misiune**: Execută o micșorare asimetrică a întregului ansamblu armilar la exact 55% din mărime (`transform: scale(0.55) !important`), fixează o înălțime nominală forțată de `400px !important`, curăță decalajele negative prin marje verticale strânse și încarcă directiva salvatoare **`transform-style: preserve-3d !important;`**.

- **Selectorul de Hover pe Mini-Reactor `.recursive-reactor-wrapper:hover .quantum-plasma-sphere .face` (Hora Electro-Kinetică)**
  - **Rolul în context**: Interceptează momentul fizic exact în care operatorul trece cu mouse-ul peste incinta de scalare a mini-reactorului de pe pagina recursivă.
  - **Misiune**: Trezește instantaneu poligoanele la viață: panourile de sticlă absorb o injecție de 20% verde fosforic (`background: rgba(167, 243, 208, 0.2) !important`), chenarul exterior trece în radiație verde-mentă intensă, iar elementele sunt învăluite de o aureolă puternică de neon de `15px`. Declanșează forțat animația din fabrică de înaltă frecvență **`reactor-lightning-flicker 0.12s infinite alternate ease-in-out !important`**.

```
/* ==========================================================================
   MODULE 14: BLUEPRINT OVERLAY // DESIGN SPECIFIC PENTRU INTERFAȚA RECURSIVĂ

    REZUMAT: Acest modul definitiv final izolează mediul dedicat care guvernează
    pagina motorului de cod live recursiv (.blueprint-layout). El structurează
    terminale splitate paralele pe mai multe coloane (.terminal-split), rulează
    un vizor de inspector convex cu catod întunecat necomprimat, gestionează
    învelișuri asimetrice de micro-scalare și blochează o rețea defensivă avansată
    anti-stivuire peste panourile de script typewriter asincrone.
   ========================================================================== */

.blueprint-container {
  max-width: 1300px; /* Setează plafonul maxim de lățime pentru a opri lăbărțarea pe monitoare foarte mari */
  margin: 100px auto; /* Pernă verticală masivă de 100px și marjă automată pentru centrare axială */
  padding: 20px; /* Spațiu interior de siguranță pentru a îndepărta elementele de marginile fizice */
  font-family: monospace; /* Font rigid mecanic de cod ce uniformizează citirea datelor structurale */
}

/* Organizarea pe coloane paralele: Documentație vs Cod Sursă */
.terminal-split {
  display: flex; /* Activează motorul Flexbox pentru a alinia panourile în paralel pe ecrane mari */
  gap: 30px; /* Distanță fixă rigidă de izolare de 30px între cele două ecrane de control */
  margin-top: 40px; /* Pernă de aer superioară sub blocul master de descriere al paginii */
}

.panel {
  flex: 1; /* Distribuie spațiul în mod egal, forțând fiecare panou să ocupe exact 50% din linie */
  background: rgba(
    10,
    11,
    30,
    0.45
  ); /* Fundal original translucid din sticlă fumurie închisă (stil cockpit) */
  border: 1px solid rgba(167, 243, 208, 0.15); /* Chenar micro-fin la 15% opacitate din nuanța verde-mentă fosforic */
  padding: 25px; /* Umplutură internă generoasă pentru protecția datelor text și a ierarhiei */
  border-radius: 8px; /* Rotunjire structurală fină a colțurilor capsulei de sticlă Solaris */
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6); /* Umbră exterioară densă ce oferă efectul tridimensional de levitație */
}

.panel-title {
  color: var(
    --solar-mint
  ); /* Se aprinde stabil pe spectrul verde-mentă fosforic de scanare active radar */
  text-transform: uppercase; /* Protocol militar obligatoriu: forțează utilizarea literelor mari capitalizate */
  letter-spacing: 2px; /* Spațiere tehnică largă industrială între caractere pentru aspect premium */
  margin-top: 0; /* Șterge marja nativă superioară pentru a bloca alinierea axială perfectă */
  border-bottom: 1px dashed rgba(167, 243, 208, 0.25); /* Linie punctată fină verde-mentă de demarcație sub text */
  padding-bottom: 12px; /* Pernă fină de aer sub text înainte de firul punctat de circuit */
  font-size: 0.9rem; /* Dimensiune radar compactă ideală pentru titlurile operative de panou */
}

/*
  Șasiul
  central
  al
  monitorului
  vechi
  analogic
  din
  dreapta
  */
.code-inspector-screen {
  width: 100% !important; /* Ocupă integral spațiul orizontal interior al panoului gazdă din dreapta */
  height: 520px !important; /* Înălțime nominală stabilă rigidă ce definește amprenta verticală a monitorului */
  background: #04050a !important; /* Void black adânc de tub catodic stins pentru un contrast maxim de caractere */
  border: 1px solid rgba(167, 243, 208, 0.2) !important; /* Margine fină pe verde-mentă fosforic la 20% opacitate */
  padding: 25px 15px 15px 15px !important; /* Padding superior mărit pentru a nu suprapune textul cu eticheta HUD active */
  overflow-x: auto !important; /* Activează scroll-ul orizontal pentru liniile foarte lungi de cod CSS preformate */
  overflow-y: auto !important; /* Activează scroll-ul vertical nativ pentru derularea cronicilor complete de stil */
  box-sizing: border-box; /* Include umpluturile în dimensiuni pentru a asigura imunitatea layout-ului */
  position: relative !important; /* Context deschis obligatoriu pentru plasarea etichetei HUD generate de ::before */

  /* EFECTUL CINEMATIC DE MONITOR CRT */
  box-shadow:
    inset 0 0 25px rgba(0, 0, 0, 0.95),
    /* Umbră neagră densă interioară ce generează curbură fizică de sticlă bombată */
    0 0 15px rgba(167, 243, 208, 0.03) !important; /* Licărire fosforică externă micro-fină de radiație reziduală */

  font-family:
    "Courier New", monospace !important; /* Font rigid mecanic analogic ce păstrează caracterul tehnic */
  font-size: 0.8rem !important; /* Dimensiune compactă comprimată ideală pentru fluxurile dense de sintaxă */
  line-height: 1.6 !important; /* Spațiere verticală aerisită ce separă rândurile consecutive de script curat */
  color: #a4b3c6 !important; /* Text argintiu-indigo industrial ce protejează ochii de oboseala lecturii */
  text-shadow: 0 0 2px rgba(164, 179, 198, 0.15) !important; /* Halou micro-fin argintiu în jurul caracterelor active */
  -webkit-font-smoothing: antialiased; /* Netezire superioară vectorială a fontului pe motoarele bazate de Webkit */
}

/* ETICHETA DE DIAGNOSTIC CRT (DATA STREAM ACTIVE // NOMINAL)
   Se generează automat deasupra codului din dreapta sus, imitând interfața logs */
.code-inspector-screen::before {
  content: "DATA STREAM ACTIVE // NOMINAL" !important; /* Textul de sistem injectat automat pe ecranul vitrat */
  position: absolute !important; /* Scoatere din flux pentru a pluti fix în colțul superior drept al monitorului */
  top: 6px !important; /* Poziționare fină verticală la 6px de marginea superioară rigidă */
  right: 12px !important; /* Aliniere strânsă pe flancul drept (tribord) la o distanță de 12px */
  font-family: monospace !important; /* Font rigid fix de cod ce menține caracterul tehnic al indicatorului */
  font-size: 0.65rem !important; /* Dimensiune liliputană fină, specifică datelor secundare de diagnostic */
  font-weight: bold !important; /* Îngroașă caracterele pentru o vizualizare optimă de alertă pe ecran */
  color: var(
    --solar-mint
  ) !important; /* Se aprinde stabil pe verdele tău fosforic de înaltă vizibilitate */
  letter-spacing: 1px !important; /* Spațiere tehnică minimă între caractere pentru aspect compact */
  text-shadow: 0 0 4px var(--solar-mint) !important; /* Explodează o aureolă fluorescentă verde de neon direct pe etichetă */
  opacity: 0.75 !important; /* Intensitate luminoasă de 75% pentru a nu distrage atenția de la codul sursă */
  z-index: 10 !important; /* Prioritate înaltă: plutește explicit deasupra textului care se derulează dedesubt */
  pointer-events: none; /* PRO-UX: Blochează selectarea sau agățarea accidentală a textului etichetei la drag */
}

/* Sincronizarea uniformă a barei de scroll cyberpunk */
.code-inspector-screen::-webkit-scrollbar {
  width: 6px !important; /* Grosimea barei verticale de derulare limitată tehnic la un fir de 6px */
  height: 6px !important; /* Înălțimea barei orizontale de derulare limitată tehnic la un fir de 6px */
}
.code-inspector-screen::-webkit-scrollbar-track {
  background: #04050a !important; /* Fundalul șinei pe care glisează scrollbar-ul devine negru profund catodic */
}
.code-inspector-screen::-webkit-scrollbar-thumb {
  background: rgba(
    167,
    243,
    208,
    0.25
  ) !important; /* Piesa mobilă se aprinde pe verde-mentă la 25% opacitate */
  border-radius: 3px !important; /* Rotunjire fină a capsulei mobile pentru finisaj minimalist industrial */
}

/* --- EXTRACTIE STILURI INLINE DIN HTML TERMINAL MAP --- */
.blueprint-master-title {
  color: #ffffff !important; /* Emisie pură de alb necomprimat pentru un impact vizual major */
  font-family: var(
    --font-main
  ) !important; /* Forțează identitatea geometrică rigidă a fontului master */
  letter-spacing: 2px !important; /* Spațiere tehnică de exact 2px între literele titlului suprem */
  margin: 10px 0 !important; /* Marje fixe verticale strânse izolând titlul de elementele vecine */
}

.blueprint-master-description {
  color: #a4b3c6 !important; /* Nuanță gri-argintie desaturată industrial anti-oboseală vizuală */
  line-height: 1.6 !important; /* Spațiere stabilă între rânduri pentru o parcurgere cursivă a descrierii */
  font-size: 0.9rem !important; /* Dimensiune fină, adaptată perfect pentru paragrafele tehnice lungi */
  text-align: justify; /* Aliniază textul compact stânga-dreapta pentru a menține ordinea în pagină */
}

.blueprint-demo-text {
  color: #e2e8f0 !important; /* Alb intens stardust ce maximizează definiția literelor de explicație */
  font-size: 0.85rem !important; /* Proporție tehnică redusă fină, ideală pentru adnotări de sistem */
  line-height: 1.6 !important; /* Raport optim între rânduri pentru protecția vizuală a echipajului */
  margin-bottom: 25px !important; /* Pernă de aer la bază pentru a izola blocul de elementele dinamice inferioare */
}

/* Containerul de scalare pentru miniatură: elimină decalajele negative inline */
.recursive-reactor-wrapper {
  transform: scale(
    0.55
  ) !important; /* MICȘORARE RECURSIVĂ: Scalează întregul reactor armilar la 55% din mărime */
  height: 400px !important; /* Înălțime nominală forțată, compensând matematic spațiul gol lăsat de scalare */
  display: flex !important; /* Activează Flexbox pe container pentru a centra piesa micșorată */
  justify-content: center !important; /* Centrează perfect Icosaedrul de 55% pe axa orizontală în panoul stâng */
  align-items: center !important; /* Centrează geometric reactorul pe axa verticală a incintei sale */
  margin: -20px 0 !important; /* Elimină decalajele parazite negative orizontale prin marje strânse */
  /* REPARAȚIA DE AUR DIDACTICĂ:
      Forțează browserul să mențină contextul tridimensional deschis și prin scalare!
      Fără această linie, Icosaedrul se aplatiza complet într-un singur triunghi amorf. */
  transform-style: preserve-3d !important;
}

/* ---  RECURSIVE PORTAL HOVER CHARGES (Scurtcircuit și Validare Mini-Reactor) --- */
/* Declanșăm exclusiv iluminarea și tremurul arcurilor electrice direct pe fețe */
.recursive-reactor-wrapper:hover .quantum-plasma-sphere .face {
  background: rgba(167, 243, 208, 0.2) !important; /* Panourile de sticlă absorb o injecție de 20% verde fosforic */
  border-color: var(--solar-mint) !important;       /* Chenarul fețelor trece din alb opac direct în radiație verde-mentă */
  box-shadow: 0 0 15px rgba(167, 243, 208, 0.4) !important; /* Generează o aureolă fluorescentă intensă de neon verde în jur */

  /* EFECTUL FULGERĂTOR DE SUPRAÎNCĂRCARE DIN FABRICĂ:
      Sfera își continuă acum rotația sa 3D maiestuoasă și rară din Modulul 07,
      iar triunghiurile distincte tremură electric la o viteză de 0.12 secunde, formând o horă perfectă! */
  animation: reactor-lightning-flicker 0.12s infinite alternate ease-in-out !important;
}

/* REȚEAUA MACRO SPLIT PAGINA RECURSIVA (Securizare Desktop anti-overflow) --- */
.terminal-split {
  display: flex !important; /* Dublează forțat activarea motorului Flexbox pentru ecranele mari */
  flex-direction: row !important; /* Panouri paralele pe ecrane mari, forțând layout-ul pe linie orizontală */
  gap: 30px !important; /* Distanță rigidă de siguranță de 30px între cele două blocuri macro */
  width: 100% !important; /* Se întinde pe toată lățimea utilă fără a genera scrollbar orizontal */
  box-sizing: border-box !important; /* Include contururile în lățime pentru a asigura imunitatea structurală */
}

.panel {
  flex: 1 !important; /* Fiecare panou ocupă exact 50% din spațiul util disponibil pe linie */
  min-width: 0 !important; /* Scut anti-overflow: interzice codului pre lung să lăbărțeze panoul */
  box-sizing: border-box !important; /*Include padding-ul în lățime, prevenind forțarea barierelor */
}
.panel p {
  text-align: justify; /* Aliniază textul compact stânga-dreapta pentru aspect ordonat de manual */
}

/*  RECURSIVE STATUS ISOLATION PROTOCOL (Ajustare chirurgicală exclusiv pentru panourile din pagina recursivă. Blochează spargerea pe Desktop fără a deranja index.html sau html-log.html.)*/
/* Selector izolat: Se aplică DOAR casetelor .mission-status aflate în interiorul unui .panel */
.panel .mission-status {
  display: block !important; /* Trece de la inline-block la block pentru controlul total al lățimii */
  width: 100% !important; /* Ocupă exact lățimea panoului din stânga, interzicând extinderea la max-content */
  max-width: 100% !important; /* Scut rigid superior de siguranță fixat la marginea panoului */
  box-sizing: border-box !important; /* Include padding-ul în calcul, prevenind ieșirea din panel */
}

/* Forțăm textul din interiorul statusului din pagină recursivă să se plieze elastic */
.panel .mission-status p {
  white-space: normal !important; /* ANULEAZĂ NOWRAP-UL: Permite textului să treacă pe rândul doi */
  line-height: 1.5 !important; /* Oferă o distanță aerisită între rândurile pliate */
  font-size: 0.75rem !important; /* Ajustare fină de font pentru o încadrare perfectă pe Desktop split */
}

/*  SCUT ANTI-STIVUIRE RECALIBRAT PENTRU PAGINA RECURSIVĂ (.panel)Sincronizat cu Animațiile de Scriere și Auto-Ascundere Cursor */
.panel .mission-status p,
.blueprint-layout .mission-status p {
  /* DEFENSIVĂ TOTALĂ ORIZONTALĂ */
  display: inline-block !important; /* Permite calcularea corectă a oblonului de lățime maximă */
  white-space: nowrap !important; /* INTERZICE ABSOLUT stivuirea literelor sau ruperea rândului pe parcursul scrierii */ /* RESETAREA DE AUR: Anulăm width: 100% care strângea textul în panelul strâmt */
  width: auto !important; /* Lasă textul să își respire lungimea reală în interiorul gridului */ /* RESTAURAREA ENGINE-ULUI DINAMIC */ /* Îi dăm voie oblonului max-width să pornească de la 0 și să fie cuprins curat deanimația ta originală typing-modular declarată la pagina 26 din PDF. */
  min-width: 0 !important;
}

.panel .mission-status,
.blueprint-layout .mission-status {
  display: block !important; /* Blochează elementul sub formă de bloc rigid structural */
  overflow-x: hidden !important; /* Scut defensiv: maschează literele nescrise și blochează overflow-ul în panel */
  max-width: 100% !important; /* Protejează marginile fizice ale structurii de grid */
}
```

15. **MODULE 00.1: KINETIC PROPULSION ENGINES & CENTRAL KEYFRAMES (BANCA DE ANIMAȚII)**

**REZUMAT / SUMMARY**: Acest modul centralizează și izolează toate motoarele de mișcare asincrone (`@keyframes`) utilizate pe interfețele navetei Solaris. Poziționat strategic la finalul layout-ului structural (după Modulul 14) și fix înaintea interogărilor media adaptive (`@media`), el acționează ca o „bancă de energie kinetică”, alimentând proprietățile `animation` apelate pe tot parcursul site-ului și protejând fișierul de coliziuni de moștenire sau duplicări parazite.

**STRUCTURA DIDACTICĂ PE GRUPĂRI CINETICE (Scaffolding Engine)**

    Pentru a asigura o curbă de învățare lină și organică, eliminând haosul din codul vechi, blocul de `@keyframes` este eșalonat pedagogic în 4 mari districte funcționale:
    1.  **Gruparea A (Ambient Interface Effects)**: Micro-tensiunile de fundal care dictează atmosfera analogică a cabinei (linii catodice, pulsații neon și umbre energetice).
    2.  **Gruparea B (Asynchronous Teletype Engines)**: Motoarele mecanice ce guvernează scrierea incrementală a textului și comportamentul dinamic al cursorului hardware.
    3.  **Gruparea C (Telemetry Radar Sweeps)**: Razele de scanare și expansiunile sferice ce simulează actualizarea datelor de sector în timp real.
    4.  **Gruparea D (Quantum 3D Geodesic Spin)**: Transformările unghiulare avansate și scurtcircuitele plasmatice dedicate reactorului poliedric 3D.

15. 1. **GRUPAREA A: ATMOSPHERIC & STRUCTURAL FLICKERS (EFECTE AMBIENTALE)**

- **Motorul Kinetic `crt-flicker` (Instabilitatea Catodică)**
  - **Rolul în context**: Alimentează selectorul macro `body::before` (marcat în Modulul 06), care generează rețeaua de linii de scanare orizontale specifice monitoarelor anilor '80.
  - **Misiune**: Rulează o oscilație rapidă și permanentă între opacitățile micro-calibrate de `0.98` și `0.99`, atingând luminozitatea nominală maximă de `1` la jumătatea ciclului de `0.15s`.

- **Motorul Kinetic `pulse` (Pulsația Neon și Luminozitatea HUD)**
  - **Rolul în context**: Alimentează selectorii de branding `.logo` și `.logo a` definiți în Modulul 05 pentru a ancora identitatea vizuală a punții de comandă.
  - **Misiune**: Gestionează o dublă transformare simultană: modulează vizibilitatea de la `1` la `0.6` și extinde geometric umbra textului (`text-shadow`) de la o aureolă roz compactă de `5px` până la o erupție sferică densă de `15px` la mijlocul intervalului.

- **Motorul Kinetic `energy-flicker` (Pulsul Divizorilor Decorativi)**
  - **Rolul în context**: Alimentează micro-liniile laser și divizorii structurali de context declarați în `:root` și asamblați pe parcursul cronicilor.
  - **Misiune**: Pornește din starea stinsă de veghe la o opacitate de `0.4` încadrată de un `box-shadow` roz de `5px`, urcând fluid la 100% intensitate nominală (`opacity: 1`) în timp ce explodează aureola laterală pe nuanța violet cosmic la un diametru dens de `25px`.

- **MOTORUL KINETIC `glow-flicker` (FLICKER CATODIC COROZIU)**
- **Rolul în context**: Alimentează starea dinamică de proximitate a elementelor în așteptare și a martorilor chihlimbar (`.future-log:hover h5`), acționând ca un avertizor cinetic asincron de rețea inactivă/blocată.
- **Misiunea**: Execută o transformare secvențială forțată în 3 cadre matematice unice: prăbușește intensitatea de curent la `0%` într-o fază oarbă de `0.25` opacitate combinată cu o întunecare grea și o pierdere de focalizare liniară (`filter: brightness(0.5) blur(1px)`), descarcă un impuls scurt electric la `50%` (`opacity: 0.85`, `brightness(1.5)`), restabilind claritatea (`blur(0px)`), urmând ca la `100%` să atingă luminozitatea maximă sticloasă a emisiilor retro-industriale (`brightness(2.2)`).

- **Motorul Kinetic `cosmic-flicker` (Protocolul Licărire Discretă)**
  - **Rolul în context**: Alimentează elementele de suport și pseudo-elementele tip laser `.macro-wrapper::after` și `.micro-wrapper::after` din interiorul inelelor HUD ale reactorului (Modulul 13).
  - **Misiune**: Rulează o interpolare extrem de fragmentată în 5 pași calculated special: menține un prag lung de veghe la `0.25` opacitate (`0%, 100%, 45%`), declanșează un puls scurt luminos ascuțit la `50%` (`opacity: 0.85`, `brightness(1.5)`) și coboară rapid la `0.4` în secunda `54%` înainte de descărcarea lentă finală.

15. 2. **GROUP B: ASYNCHRONOUS TELETYPE ENGINES (MOTOARE SCRIERE)**

**REZUMAT / SUMMARY**: Acest district kinetic izolează și controlează toate mecanismele de emulare a mașinii de scris mecanice, utilizate global pe antetele de titluri și casetele de status. Prin gruparea exclusivă a celor 3 piloni activi (`typing-modular`, `blink`, `hide-cursor`), acest districit demonstrează cum se pot stivui asincron proprietăți temporale multiple pe o singură linie de cod, garantând randări imune la overflow sau deformări parazite pe Desktop split.

- **Motorul Kinetic `typing-modular` (Desfășurarea Oblonului de Lățime)**
  - **Rolul în context**: Alimentează direct elementele de tip text din consolă (`.stenciled-metal-text`, `.stenciled-metal-text-sub`) și panourile verzi de alertă tactică (`.mission-status p`).
  - **Misiune**: Orchestrează extinderea incrementală pe orizontală a proprietății `max-width` de la valoarea inițială latentă de `0` până la plafonul maxim de deblocare structurală de `100%`.

- **Motorul Kinetic `blink` (Pâlpâirea Cursorului Hardware Universal)**
  - **Rolul în context**: Trasează și animă indicatorul vertical terminal din flancul drept al tuturor blocurilor de text aflate în curs de scriere asincronă.
  - **Misiune**: Rulează un ciclu de descărcare electrică rapidă la o frecvență de `0.75s` (folosind o funcție discretă `step-end`), comutând proprietatea specifică `border-right-color` de la starea invizibilă `transparent` la starea activă moștenită `inherit`.

- **Motorul Kinetic `hide-cursor` (Anihilarea Definitivă a Liniei de Ghidaj)**
  - **Rolul în context**: Intervine exclusiv în subsolul blocurilor `.mission-status p` (marcat în Modulul 08) pentru a curăța ecranul post-scriere.
  - **Misiune**: Execută un ordin fulgerător de stingere la o durată de `0s`, forțând proprietatea `border-right-color` să devină definitiv `transparent` după o amânare exactă (delay) de `3.5s`.

15. 3. **GROUP C: TELEMETRY RADAR SWEEPS (RADARE ȘI SCANĂRI)**

**REZUMAT / SUMMARY**: Acest district kinetic izolează și controlează toate mecanismele de monitorizare dinamică și telemetrie activă în timp real. Prin gruparea exclusivă a celor 2 motoare de scanare (`laser-scan`, `dot-pulse`), secțiunea demonstrează importanța pașilor intermediari în cadrul cadrelor de mișcare, salvând micro-interacțiunile hardware analogice și oferind interfeței o adâncime UI/UX imersivă premium.

- **Motorul Kinetic `laser-scan` (Estomparea Fasciculului Catodic)**
  - **Rolul în context**: Alimentează direct elementul decorativ de scanare radar (`.note-terminal::before` sau divizorii de laser activi) definit în Modulul 09 pentru a simula un ecran catodic aflat sub un ciclu de reîmprospătare a datelor.
  - **Misiune**: Orchestrează deplasarea verticală a razei de la `top: 0%` la `100%` prin introducerea a două stări procentuale intermediare strategice la `5%` și `95%`, care blochează opacitatea la valoarea stabilă de `0.7` pe parcursul cursei utilitare, pornind și oprindu-se din intensitate zero (`opacity: 0`).

- **Motorul Kinetic `dot-pulse` (Undă de Șoc / The Sonar Radar Ripple)**
  - **Rolul în context**: Alimentează micro-ledul luminos de status din subsol (`footer .pulse-dot`) definit în Modulul 12, transformând un indicator static într-o componentă de confirmare activă a conexiunii.
  - **Misiune**: Declanșează o dublă transformare geometrico-fotonică radicală într-un singur pas: propulsează elementul de la dimensiunea sa nominală nativă `scale(1)` și luminozitate maximă `opacity: 1` direct către o expansiune masivă de 250% în spațiu (`scale(2.5)`), dizolvând complet textura în transparență totală (`opacity: 0`) la finalul buclei.

15. 4. **GROUP D: QUANTUM 3D GEODESIC SPIN (NUCLEUL CINETIC 3D)**

**REZUMAT / SUMMARY**: Acest district final guvernează exclusiv ecuațiile cinematice tridimensionale ale reactorului armilar poliedric cu 20 de fețe (Icosaedrul). Prin unificarea celor 3 piloni cinetici autentici din fabrică (`spin-geodesic-core`, `reactor-lightning-flicker`, `lightning-glow-fusion`), modulul demonstrează importanța reflexiilor asimetrice și a unghiurilor de înclinație, oferind o interfață cu un realism fizic analogic brutalist de înaltă rezoluție.

- **Motorul Kinetic `spin-geodesic-core` (Rotația Industrială Înclinată)**
  - **Rolul în context**: Alimentează direct containerul sferic principal al Icosaedrului (`.quantum-plasma-sphere`), pus în mișcare în interiorul Modulului 13.
  - **Misiune**: Orchestrează rotația liniară infinită pe axa verticală Y, forțând totodată o înclinație permanentă tridimensională pe axa orizontală X de exact **`-20deg`** în ambele capete ale intervalului (`0%` -> `100%`).

- **Motorul Kinetic `reactor-lightning-flicker` (Scurtcircuitul și Avaria de Înaltă Tensiune)**
- **Rolul în context**: Configurat ca un motor alternativ de suprasarcină electrică critică, activat pe perioada interacțiunilor de înaltă densitate energetică.
- **Misiune**: Manipulează o transformare tri-fazică rapidă: pornește de la o intensitate stabilizată verde fosforic (`brightness(1.2)`), explodează asimetric la `33%` într-o erupție masivă de roz-neon la o luminozitate critică de **`3.5`** cu o aureolă de **`40px`**, urmată la `66%` de o stingere parțială de arc electric la un contrast redus de `0.4` și o pierdere de claritate prin **`blur(0.5px)`**.

- **Motorul Kinetic `lightning-glow-fusion` (Protocolul de Impuls Roz-Mentă Glossy)**
  - **Rolul în context**: Alimentează starea dinamică de hover a fețelor Icosaedrului, activată prin selectorul compus `.armillary-reactor-core:hover .face` (Modulul 13) și prin reflexia sa din ecranul recursiv (Modulul 14).
  - **Misiune**: Gestionează o fuziune cromatică tri-fazică la frecvența electrică de `0.12s`: încarcă o bază mentă translucidă la `0.15` opacitate, explodează la `50%` într-un puls intermediar roz intens la o luminozitate de **`3.2`** cu o umbră drop-shadow masivă de **`35px`**, finalizând la `100%` printr-o injecție de alb incandescent la un perimetru de `15px`.

```
/* ==========================================================================
    MODULE 00.1: PUNTEA DE PROPULSIE KINETICĂ ȘI ANIMAȚIILE CORE

    REZUMAT: Acest modul centralizează toate motoarele de mișcare asincrone
    (@keyframes) utilizate pe interfețele navei amiral. Poziționat logic după
    straturile avansate de layout și înaintea interogărilor media adaptive, el
    ancorează fluctuațiile catodice CRT, vectorii fluorescenți de pulsare ai
    umbrelor de text și operațiunile secvențiale de scriere ale mașinii de scris.
   ========================================================================== */

/* ==========================================================================
   GRUPAREA A: EFECTE AMBIENTALE INTERFAȚĂ // HARDWARE CATHODE SCREEN

    REZUMAT: Această primă grupare kinetică adună micro-tensiunile continue de
    fundal care generează atmosfera retro-analogică din cabină. Ea structurează
    instabilitatea nativă a tubului catodic de sticlă (crt-flicker), logica de
    pulsare neon a textului din logo (pulse) și umbrele sau fluxurile laser de
    demarcație ale divizorilor structurali (energy-flicker, cosmic-flicker).
   ========================================================================== */

/* --- 1. INSTABILITATEA DE TENSIUNE A ECRANULUI CRT --- */
@keyframes crt-flicker {
  0% {
    opacity: 0.98;               /* Scade discret opacitatea pentru a imita fazele de emisie slăbită ale lămpii */
  }
  50% {
    opacity: 1;                  /* Luminozitate maximă nominală a fluxului de electroni imprimat pe monitor */
  }
  100% {
    opacity: 0.99;               /* Micro-fluctuație continuă ce simulează comportamentul unui ecran analogic real */
  }
}

/* --- 2. PULSAȚIA CROMATICĂ DE INTENSIFICARE A TEXTULUI --- */
@keyframes pulse {
  0% {
    opacity: 1;                  /* Fixează intensitatea luminoasă inițială la capacitate nominală maximă de 100% */
    text-shadow: 0 0 5px var(--nebula-pink); /* Aprinde o aureolă laser roz-magenta compactă de 5px în jurul literelor */
  }
  50% {
    opacity: 0.6;                /* SCUT ANTI-OBOSEALĂ: Estompează fluid luminozitatea la 60% în momentul de maximă expansiune */
    text-shadow: 0 0 15px var(--nebula-pink); /* Explodează geometric haloul de neon, difuzând emisia roz până la 15px */
  }
  100% {
    opacity: 1;                  /* Revine stabil la intensitatea luminoasă nominală inițială de 100% */
    text-shadow: 0 0 5px var(--nebula-pink); /* Strânge înapoi aura fluorescentă la dimensiunea tehnică de siguranță de 5px */
  }
}

/* --- 3. INSTABILITATEA ȘI FLICKER-UL CATODIC DE ÎNALTĂ TENSIUNE --- */
@keyframes glow-flicker {
  0% {
    opacity: 0.25;               /* Scădere bruscă a curentului în lămpi, opacitatea scade la un sfert */
    filter: brightness(0.5) blur(1px); /* Estompare fosforică cinematică și pierdere de focalizare a tubului */
  }
  50% {
    opacity: 0.85;               /* Puls brusc de tensiune în rețeaua secundară, aprinzând ecranul */
    filter: brightness(1.5) blur(0px); /* Claritate instantanee de radar, textul redevine tăios */
  }
  100% {
    opacity: 1;                  /* Încărcare nominală maximă stabilizată pe ecran */
    filter: brightness(2.2) blur(0px); /* Strălucire puternică de emisie stelară retro-industrială */
  }
}
/* --- 4. LICĂRIREA DISCRETĂ A FIRELOR LASER DE CONTEXT --- */
@keyframes energy-flicker {
  0% {
    opacity: 0.4;                /* Fixează intensitatea luminoasă inițială stinsă la 40% în faza de repaus a divizorului */
    box-shadow: 0 0 5px var(--nebula-pink); /* Generează o aureolă fină de neon roz-magenta de 5px în jurul firului */
  }
  100% {
    opacity: 1;                  /* Ridică fluid luminozitatea la intensitate nominală totală de 100% la activare */
    box-shadow: 0 0 25px var(--nebula-purple); /* Explodează aureola lateral, virând culoarea într-un violet cosmic de 25px */
  }
}

/* --- 5. PROTOCOL LICĂRIRE DISCRETĂ --- */
@keyframes cosmic-flicker {
  0%, 100% {
    opacity: 0.25;               /* Prag de veghe, menținând divizorii subțiri integrați discret în fundalul sticlei */
    filter: brightness(0.8);     /* Scade intensitatea semnalului cromatic pentru a preveni oboseala ochilor */
  }
  45% {
    opacity: 0.3;                /* Micro-variație de curent ce pregătește circuitul pentru descărcarea de impuls */
    filter: brightness(0.9);     /* Pas intermediar de contrast visual ce prefațează urcarea undei */
  }
  50% {
    opacity: 0.85;               /* Descărcare de vârf, aprinzând intens linia de demarcație pe un puls scurt luminos */
    filter: brightness(1.5);     /* Supraîncărcare controlată, generând un efect stroboscopic de neon licărit */
  }
  54% {
    opacity: 0.4;                /* Coborâre rapidă a tensiunii imediat după descărcare pentru stabilizarea firului */
    filter: brightness(1);       /* Readuce liniile vectoriale la o definiție clară, neutră și calibrată */
  }
  85% {
    opacity: 0.3;                /* Fază de descărcare lentă reziduală ce protejează ecranul de uzură și ardere */
    filter: brightness(0.9);     /* Menține parametrii ambientali estompați până când ciclul se reinițializează */
  }
}

/* ==========================================================================
   GRUPAREA B: MOTOARE ASINCRONE DE SCRIERE // MECHANICAL TEXT INPUT

    REZUMAT: Acest district centralizează mecanismele de emulare a mașinii de scris
    utilizate pe antetele de terminal și jurnalele automate. El unifică buclele
    modulare de expansiune a lățimii (typing-modular), normalizează clipirea de
    înaltă precizie a bordurii cursorului (blink) și declanșează ștergerea definitivă
    a liniei post-scriere (hide-cursor) pentru a stabiliza ecranele.
   ========================================================================== */

/* --- 6. DESFĂȘURAREA OBLONULUI PENTRU MAȘINA DE SCRIS ASINCRONĂ --- */
@keyframes typing-modular {
  from {
    max-width: 0;                /* Stare inițială: scriptul tehnic începe complet retras în vidul orizontal */
  }
  to {
    max-width: 100%;             /* Extinde granițele complet pentru a afișa curat lungimea reală a textului */
  }
}

/* --- 7. PÂLPÂIREA CURSORULUI MECANIC DE TERMINAL --- */
@keyframes blink {
  from, to {
    border-right-color: transparent; /* Ascunde starea cursorului, făcând linia verticală marginală invizibilă */
  }
  50% {
    border-right-color: inherit; /* Revine la culoarea textului moștenită nativ, aprinzând firul pe ecran */
  }
}

/* --- 8. STINGEREA AUTOMATĂ A CURSORULUI DUPĂ INTEGRARE --- */
@keyframes hide-cursor {
  to {
    border-right-color: transparent; /* Șterge definitiv conturul liniei de cursor după terminarea pașilor de scriere */
  }
}

/* ==========================================================================
   GRUPAREA C: RADARELE ȘI SCANĂRILE DE SECTOR // REAL-TIME MONITORING

    REZUMAT: Acest district ancorează mecanismele de monitorizare dinamică implementate
    pe ecranele interactive și indicatorii de urmărire. El guvernează scanarea
    verticală continuă a razei de control (laser-scan) și coordonează bucla volumetrică
    respiratorie de expansiune pentru martorii de telemetrie (dot-pulse).
   ========================================================================== */

/* --- 9. RAZA VERTICALĂ CONTINUĂ DE SCANARE RADAR PESTE MONITOR --- */
@keyframes laser-scan {
  0% {
    top: 0%;
    opacity: 0;                  /* Raza începe cursa de sus fiind complet invizibilă pentru a opri aparițiile bruște */
  }
  5% {
    opacity: 0.7;                /* Aprindere fluidă de 70% intensitate în milisecunda în care părăsește rama superioară */
  }
  95% {
    opacity: 0.7;                /* Menține emisia luminoasă stabilă pe tot parcursul măturării ecranului pe verticală */
  }
  100% {
    top: 100%;
    opacity: 0;                  /* Stingere lină la zero intensitate chiar în secunda în care atinge podeaua casetei */
  }
}

/* --- 10. IMPULSUL RADAR AL MULTI-MARTORULUI DIN SUBSOL --- */
@keyframes dot-pulse {
  0% {
    transform: scale(1);          /* Punctul pornește compact, la dimensiunea sa nominală inițială în subsol */
    opacity: 1;                  /* Intensitate luminoasă maximă de 100%, indicând emisia inițială a semnalului active */
  }
  100% {
    transform: scale(2.5);        /* EXPLOZIA UNDEI: Se dilată masiv în exterior până la 250% din volumul inițial */
    opacity: 0;                  /* DIZOLVARE ÎN VID: Textura se stinge complet la zero în momentul maximei expansiuni */
  }
}

/* ==========================================================================
   GRUPAREA D: CINEMATICĂ REACTOR 3D // ADVANCED REACTOR KINETICS

    REZUMAT: Acest district structural specializat izolează cadrele avansate de
    mișcare tridimensională orbitală. El conduce rotația spațială infinită pe axele
    înclinate X/Y (spin-geodesic-core) și coordonează atât stroboscopul alternant
    de avarie la înaltă frecvență (reactor-lightning-flicker), cât și fuziunea
    multistratificată roz-mentă cu reflexii de sticlă incandescentă (lightning-glow-fusion)
    pentru a alimenta ansamblul Icosaedrului volumetric cu 20 de fețe.
   ========================================================================== */


/* --- 11. ROTAȚIA INDUSTRIALĂ 3D A SFEREI FAȚETATE --- */
@keyframes spin-geodesic-core {
  0% {
    transform: rotateX(-20deg) rotateY(0deg); /* Îngheață înclinarea tehnică la -20px pe orizontală și începe rotația */
  }
  100% {
    transform: rotateX(-20deg) rotateY(360deg); /* Menține înclinarea axială pe tot parcursul cercului complet de 360° */
  }
}

/* --- 12. EFECTUL FULGERĂTOR DE SUPRAÎNCĂRCARE ELECTRICĂ --- */
@keyframes reactor-lightning-flicker {
  0%, 100% {
    filter: brightness(1.2) drop-shadow(0 0 8px var(--solar-mint)); /* Tensiune inițială stabilizată pe verde fosforic */
    opacity: 0.85;                /* Luminozitate optimă de veghe ce protejează grila vizuală */
  }
  33% {
    filter: brightness(3.5) drop-shadow(0 0 40px var(--nebula-pink)); /* Puls intens de tensiune pe roz-neon ce supraîncărcă fețele */
    opacity: 1;                   /* Descărcare completă instantanee în rețeaua secundară a Icosaedrului */
  }
  66% {
    filter: brightness(0.4) blur(0.5px); /* Stingere parțială cinematică specifică arcurilor electrice analogice */
    opacity: 0.5;                /* Scade intensitatea la jumătate pentru a imita degradarea fizică a lămpii */
  }
}

/* --- 13. PROTOCOLUL DE IMPULS ELECTRIC ROZ-MENTĂ GLOSSY --- */
@keyframes lightning-glow-fusion {
  0% {
    background: rgba(167, 243, 208, 0.15); /* Bază mentă lucioasă inițială injectată sub formă de sticlă */
    border-color: var(--solar-mint);
    filter: brightness(1.5) drop-shadow(0 0 10px var(--solar-mint)); /* Licărire fosforică inițială */
  }
  50% {
    background: rgba(255, 0, 127, 0.18);   /* Puls intermediar roz intens în inima fațetelor poliedrice */
    border-color: var(--nebula-pink);
    filter: brightness(3.2) drop-shadow(0 0 35px var(--nebula-pink)); /* Erupție lucioasă de înaltă tensiune */
  }
  100% {
    background: rgba(255, 255, 255, 0.22); /* Reflexia sticlei incandenscente albe ce simulează fuziunea core-ului */
    border-color: var(--solar-mint);
    filter: brightness(2) drop-shadow(0 0 15px var(--solar-mint)); /* Stabilizare pe frecvența verde radar */
  }
}
```

16. **MODULE 00.2: MEDIA QUERIES & SPATIAL ISOLATION ENGINES (COSMIC LAYOUTS)**

**REZUMAT / SUMMARY**: Acest sub-modul activează arhitectura asimetrică pe două coloane paralele dedicată exclusiv monitoarelor mari de desktop. El izolează complet comportamentele cinetice din Sidebar (stânga) de cele din Zona de Lectură (dreapta), impunând bariere rigide bazate pe `100vh` care transformă cele două emisfere în incinte de scanare complet independente din punct de vedere al scroll-ului, eliminând coliziunile de layout.

16. 1. **MODULE 00.2 // PROTOCOL 0.A: DESKTOP SPATIAL ISOLATION (`min-width: 769px`)**

- **COMPENDIU ARHITECTURAL: Analiza Izolării Spațiale Desktop (`min-width: 769px`)**

**ÎNTREBARE CRITICĂ DE AUDIT**: _Este izolarea stilului de desktop într-un Media Query dedicat (`min-width: 769px`) o decizie corectă sau o abatere necanonică de la regulile CSS?_

În fața unui programator tradițional, rigidizat în rețetele superficiale ale anilor 2010, această structură poate părea o anomalie atipică. Totuși, în ingineria modernă de interfețe cu densitate mare de date (High-Density HUDs) și în designul didactic de elită, **această abordare reprezintă o decizie arhitecturală de o rigoare absolută, o bune practici superioară și este 100% legitimă.**

      1. **Mitul Mobile-First și Capcana Canonului Tradițional**

      Dogma clasică *Mobile-First* predică scrierea tuturor proprietăților globale în afara blocurilor media, urmând ca ecranul de desktop să moștenească și să modifice incremental acele stiluri.

      Deși această rețetă este excelentă pentru site-uri civile simple de prezentare (unde blocurile de text doar cad unul sub celălalt pe mobil, păstrând aceeași logică fluidă), ea se prăbușește lamentabil în momentul în care o interfață suferă o **mutație genetică radicală de layout** între dispozitive, așa cum se întâmplă în cazul paginii noastre de jurnal (`html-log.html`).

      2. **Argumentarea Tehnico-Ingineriască (De ce este o decizie briliantă?)**

      *   **Prevenirea „Poluării Casetelor” prin Moșteniri Parazite**:
          Mecanica implementată pentru ecranele mari este un monstru de specificitate hardware: calcule matematice dinamice (`calc(100vh - 130px)`), Flexbox vertical rigid, structuri Grid asimetrice (`280px 1fr`), bare de scroll customizate Webkit de 3px și directive defensive `overflow: hidden !important`.
          Dacă aceste reguli grele ar fi fost lăsate libere în fișier, ele ar fi poluat instantaneu versiunea de mobil. Browserul telefonului ar fi încercat să aplice un Grid pe două coloane, să blocheze ecranele la `100vh` și să ascundă scroll-ul global. Prin închiderea lor ermetică în `min-width: 769px`, ridicăm un **Scut de Carantină Totală**, ordonând browserului mobile să șteargă complet aceste matrici din memorie, eliminând necesitatea de a anula manual zeci de directive `!important` pe ecranele mici.
      *   **Paradigma Aplicațiilor de Tip Split-Screen**:
          Pe desktop, pagina nu se comportă ca un site fluid; ea funcționează ca un **software dashboard de monitorizare sau un editor IDE avansat (precum VS Code)**, unde scroll-ul general al ferestrei este anihilat, iar coloanele interioare culisează independent pe coordonate fixe.
          Pe mobil, interfața revine la o curgere narativă tradițională, unde scroll-ul global este eliberat, iar sidebar-ul se transformă într-o consolă orizontală plasată deasupra textului. Când diferențele de layout sunt atât de violente, abordarea corectă nu mai este moștenirea progresivă, ci **Izolarea Spațială Contextuală (Adaptive Component Design)**.

      3. **Dimensiunea Pedagogică (Ce învață studenții?)**
      Această abordare îi forțează pe studenți să depășească faza de simpli „utilizatori de șabloane” și îi transformă în arhitecți de sisteme software. Ei înțeleg un principiu suprem de Clean Code: **Refactoring-ul curat se bazează pe izolarea responsabilităților, nu pe scrierea de cod parazit care trebuie anulat ulterior.** Separarea fișierului în două emisfere sigure (0.A pentru desktop și 0.B pentru mobil) protejează mintea elevului de erorile logice provocate de coliziunile în cascadă, oferindu-le un model de rigoare industrială imbatabil.

- **Selectorul Macro `.log-layout` (Șasiul Grilei pe Două Coloane)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Targetează containerul părinte macro (`<div class="log-layout">`) care încapsulează ambele punți de lucru (Sidebar-ul și fluxul de text al jurnalelor) pe paginile de jurnal active (`html-log.html`).
- **Misiunea**: Declanșează sistemul Grid CSS printr-o asimetrie rigidă de `280px 1fr` separată de un spațiu aerian de `20px` (`gap`). Aliniază ambele coloane direct la tavanul superior al matricei, blochează înălțimea fizică a cadrului la ecuația exactă `calc(100vh - 90px)` (înălțimea totală a monitorului minus puntea fixă a navbarului superior) și aplică directiva dictatorială `overflow: hidden !important`.

- **Selectorul `.log-sidebar` și `.sidebar-nav` (Bariera Sticky Anti-Alungire)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Targetează turnul lateral din stânga (`aside`) și containerul său interior de navigare, folosite pentru a rula lista celor peste 60 de zile din jurnalul de telemetrie.
- **Misiunea**: Fixează componenta la `top: 90px` prin proprietatea `position: sticky`. Impune o limitare verticală forțată prin ecuația `height: calc(100vh - 130px) !important` și `max-height` identic. Activează un motor Flexbox pe verticală (`flex-direction: column`), încarcă sticla fumurie translucidă la 70% opacitate cu blur de `15px`, aplică un border fin la bază și forțează reținerea prin `overflow: hidden !important` pe ambele elemente. Setează un padding de `25px` strâns în interiorul unui model rigid `border-box`.

- **Selectorul Master `.map-title-link` și `.map-title-link h4` (Capsula Laser a Hărții)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Targetează butonul mare de ancoră dreptunghiular (`.map-title-link`) plasat în fruntea sidebar-ului, folosit ca scurtătură supremă pentru reîntoarcerea la harta HTML/SQL, împreună cu eticheta `h4` din interior.
- **Misiunea**: Forțează comportamentul de bloc (`display: block !important`) și interzice comprimarea fizică prin directiva de urgență `flex-shrink: 0 !important`. Încarcă sticla fumurie densă Polaris la 95% opacitate (`rgba(13, 15, 20, 0.95)`), o încinge cu o bordură laser dublă roz-magenta (`1px double var(--nebula-pink)`) sub un `z-index: 10` și o umbră neon fină. Pe elementul `h4` interior, anulează marjele, padding-urile și borders nativi prin combinări ordonate de directive `!important`, fixând textul pe verde-mentă (`var(--solar-mint)`), `font-size: 0.8rem` și majuscule mecanice cu spațiere de `3px`.

- **Selectorul `.sidebar-nav ul` (Tunelul de Scroll Roz de 3px)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Țintește lista neordonată (`<ul>`) retrasă în interiorul pilonului de navigare, responsabilă cu maparea și derularea celor peste 60 de rânduri de capitole.
- **Misiunea**: Deblocează în mod exclusiv scroll-ul pe verticală prin directiva `overflow-y: auto !important` și ordonă extinderea maximă pe verticală prin `flex-grow: 1`. Curăță stilul nativ de listă, șterge padding-ul stâng și introduce un tampon de siguranță la tribord prin `padding-right: 5px`. Atașează regulile Webkit, reducând grosimea șinei la un fir fin de exact `3px` cu o piesă mobilă (`-webkit-scrollbar-thumb`) vopsită în roz-neon la 30% opacitate și rotunjită la `2px`.

- **Selectorul `.log-content` (Incinta de Lectură de pe Tribord)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Targetează coloana principală din dreapta a grinzii (`<main class="log-content">`), unde sunt stocate și afișate textele lungi ale cronicilor zilnice.
- **Misiunea**: Ocupă 100% din înălțimea utilă disponibilă pe coloana sa și activează un motor independent de scroll vertical exclusiv la nivelul acestui container via `overflow-y: auto !important`. Încadrează conținutul într-un padding generos de `40px 60px 60px 60px` și forțează o barieră protectoare superioară de siguranță prin `padding-top: 50px !important`. Sincronizează salturile cinematice prin `scroll-behavior: smooth` în interiorul unui model strict `box-sizing`. Instalează o șină custom Webkit de `4px` formată dintr-un track fumuriu la 50% opacitate și o piesă mobilă violet cosmic (`rgba(157, 23, 248, 0.3)`) rotunjită la `4px`.

- **Selectorul `.log-entry` și `.log-content .category-header` (Alinierea Filelor de Zi)**
  Arhitectura Funcțională (Rol în context & Misiune)
- **Rolul în context**: Targetează fiecare articol de zi în parte (`<article class="log-entry">`) încastrat în fluxul de lectură din dreapta, precum și antetul principal de categorie `.category-header`.
- **Misiunea**: Impune o înălțime minimă masivă calculată pe baza monitorului: `min-height: calc(100vh - 150px)`, izolează filele consecutive printr-o marjă inferioară de 80px și un padding superior de 40px. Desenează o linie laser punctată roz fină la 5% opacitate (`1px dashed rgba(255, 0, 127, 0.05)`) și încarcă directiva critică `scroll-margin-top: 100px !important`. Pe elementul .`category-header`, blochează padding-ul superior la `20px !important` și șterge marja superioară.

```
/* ==========================================================================
    MODULE 00.2: MEDIA QUERIES & SPATIAL ISOLATION ENGINES (COSMIC LAYOUTS)

    REZUMAT: Acest modul ancorează restructurările adaptive de ecran, splitate în
    două fluxuri rigide. Protocolul Desktop (min-width: 769px) îngheață aspectul
    de jurnal pe două coloane și tunelurile de scroll, în timp ce Protocolul
    Mobile (max-width: 768px) comprimă granițele într-o bandă HUD orizontală
    ultra-joasă de 40px și activează amortizarea volumetrică a reactorului 3D.
   ========================================================================== */

/* ==========================================================================
    00.2.A. PROTOCOLUL DESKTOP: ECRANE MARI (min-width: 769px)

    REZUMAT: Această secțiune structurală declanșează grila asimetrică pe două
    coloane pentru ecranele mari de desktop. Ea blochează sidebar-ul la o lățime
    rigidă de 280px, impune bariere stricte de graniță bazate pe 100vh pentru a
    izola layout-ul de comportamentele parazite de scroll, instalează șina de 3px
    roz pentru scrollbar și asigură un echilibru vizual curat pentru citire.

    MANIFEST ARHITECTURAL ȘI PEDAGOGIC (IZOLAREA SPAȚIALĂ A MEDIULUI):
    Întrebare de Audit: Este izolarea stilului de desktop într-un Media Query o
    decizie corectă sau o abatere necanonică de la regulile CSS standard?

    Răspuns de Bord: Este o decizie de inginerie modernă de elită, 100% justificată!
    Dogma clasică "Mobile-First" se prăbușește când un layout suferă o mutație
    genetică completă între dispozitive. Pe desktop, această pagină nu este un site
    fluid simplu, ci o aplicație hardware de tip "Split-Screen" (stil dashboard militar
    sau editor IDE precum VS Code), unde scroll-ul global este blocat, iar ambele
    coloane interioare culisează independent pe bariere rigide de 100vh.

    Dacă aceste reguli grele de Grid asimetric (280px 1fr), padding-uri de siguranță
    și directive defensive "overflow: hidden !important" ar fi fost lăsate libere,
    ele ar fi poluat parazit versiunea de mobil, transformând ecranul telefonului
    într-un colaps total de randare.

    Închiderea lor în acest sub-modul ridică un Scut de Carantină Totală: ordonăm
    browserului mobile să ignore complet aceste matrici pe ecrane mici, protejând
    totodată mintea studenților de coliziunile logice în cascadă și eliminând codul
    redundant de anulare. Proiectăm o arhitectură curată bazată pe Izolare Contextuală!
   ========================================================================== */


@media (min-width: 769px) {
  /* 1. CONTAINERUL PARENT GLOBAL (Organizează ecranul logurilor în două coloane) */
  .log-layout {
    display: grid; /* Activează sistemul de Grilă structurală (Grid Layout) pe monitoare mari */
    grid-template-columns: 280px 1fr; /* Alocă fix 280px pentru Sidebar (stânga) și restul spațiului util (1fr) pentru text */
    gap: 20px; /* Lasă un spațiu fizic gol de siguranță de 20px între cele două coloane paralele */
    align-items: start; /* Aliniază ambele containere la „tavanul” superior de sus al grilei macro */
    height: calc(
      100vh - 90px
    ); /* Înghețăm layout-ul modular la înălțimea totală a ecranului minus spațiul consolei HUD */
    overflow: hidden !important; /* Interzice total apariția barei de scroll generale a browserului pe toată pagina */
  }

  /* 2. ETICHETA <aside> (Bariera exterioară rigidă a panoului din stânga) */
  .log-sidebar {
    position: sticky; /* Permite sidebar-ului să rămână fix vizibil pe ecran în timpul navigării cronicilor */
    top: 90px; /* Îl fixează la exact 90px distanță față de marginea superioară a ferestrei active */
    height: calc(
      100vh - 130px
    ) !important; /* Forțează înălțimea calculată din ecran minus locul protector din subsol */
    max-height: calc(
      100vh - 130px
    ) !important; /* Barieră mecanică rigidă ce interzice sidebar-ului să se alungească haotic */
    display: flex; /* Transformă interiorul sidebar-ului într-o cutie flexibilă structurală (Flexbox) */
    flex-direction: column; /* Așază elementele interne (titlul și navigația) în mod rigid pe verticală, în coloană */
    background: rgba(
      13,
      15,
      20,
      0.7
    ); /* Fundal închis, translucid original format din sticlă fumurie Solaris */
    backdrop-filter: blur(
      15px
    ); /* Efect cinematic adânc de blurring ce estompează elementele din spatele punții */
    border-bottom: 1px solid rgba(167, 243, 208, 0.1); /* Linie fină fosforică la bază la 10% opacitate de control */
    overflow: hidden !important; /* BLOCAREA ANTI-COLIZIUNE: Oprim orice scroll general pe caseta exterioară pentru a proteja h4-ul */
    padding: 25px; /* Pernă interioară generoasă de aer pentru protecția fizică a componentelor */
    box-sizing: border-box; /* Include padding-ul în calculul înălțimii, blocând erorile sau deformările */
  }

  /* 3. NAV-UL INTERIOR: Devine turn rigid de control (Pilonul interior de susținere) */
  .sidebar-nav {
    display: flex; /* Activează motorul flexibil local pentru alinierea listei de capitole */
    flex-direction: column; /* Stivuiește rândurile de volume strict pe verticală, unul sub celălalt */
    height: 100%;
    max-height: 100%; /* Consumă integral spațiul util pus la dispoziție de aside-ul gazdă */
    overflow: hidden !important; /* Siguranță dublă: blochează fizic mutarea sau deformarea elementelor superioare */
  }

  /* 4. TITLUL „MAP” (Butonul superior „HTML/SQL Expedition Map”) */
  .map-title-link {
    display: block !important; /* Îl transformă într-un bloc complet extins pe toată lățimea utilă a turnului */
    flex-shrink: 0 !important; /* Regula de aur: lista de zile de dedesubt nu are voie să îl strivească la scroll */
    background: rgba(
      13,
      15,
      20,
      0.95
    ) !important; /* Sticlă neagră opacă de protecție totală ce maschează butoanele din spate */
    border: 1px double var(--nebula-pink); /* Chenar dublu roz-magenta original, izolând complet intrarea în pagină */
    border-radius: 4px; /* Rotunjire fină de 4px a colțurilor capsulei superioare */
    padding: 12px !important; /* Spațiu interior generos calibrat special pentru o aerisire premium a textului */
    padding-bottom: 15px;
    margin-bottom: 15px !important; /* Împinge lista de zile mai jos pe verticală pentru a o lăsa să respire */
    z-index: 10; /* Strat superior absolut ce plutește peste fluxul de derulare al cronicilor */
    text-decoration: none; /* Elimină sublinierea nativă inestetică injectată automat de browsere pe ancore */
    box-shadow: 0 0 15px rgba(255, 0, 127, 0.1); /* Aură fină de neon roz-magenta difuzată în jurul capsulei */
  }

  /* Stilizarea textului interior h4 conform esteticii curate originale */
  .map-title-link h4 {
    position: static !important; /* REPARAȚIA SALVATOARE: Anulează poziționarea absolută și aduce textul înapoi în flux normal */
    margin: 0 !important; /* Șterge marjele parazite implicite ale browserelor terestre de pe titluri */
    padding: 0 !important;
    padding-bottom: 5px !important; /* Spațiu fin sub text înainte de linia imaginară a bazei de circuit */
    color: var(
      --solar-mint
    ) !important; /* Aprinde textul stabil pe nuanța verde-mentă fosforică originală de sistem */
    font-size: 0.8rem !important; /* Dimensiune tehnică fină calibrată, neîncărcată pentru ecranele HUD */
    text-transform: uppercase !important; /* Protocol militar obligatoriu: forțează utilizarea literelor mari capitalizate */
    letter-spacing: 3px !important; /* Spațiere tehnică industrială extinsă între caractere pentru aspect aerisit */
    border-bottom: none !important; /* Ștergem definitiv dunga veche punctată inestetică din versiunile trecute */
    background: transparent !important; /* ȘTERGE fundalul violet parazit moștenit greșit de la etichetele de anexe */
    border: none !important; /* Șterge chenarul subțire verde moștenit de sus din stivele de moștenire */
    text-shadow: 0 0 8px rgba(167, 243, 208, 0.4) !important; /* Strălucire fină fosforică de monitor catodic pornit */
    text-align: center !important; /* Centrare perfectă a literelor în interiorul etichetei duble roz */
    transition: all 0.3s ease !important; /* Tranziție fluidă la interacțiunea dinamică cu echipajul */
  }

  /* EFECT HOVER PE DESKTOP: Comută lin pe roz-magenta la trecerea mouse-ului */
  .map-title-link:hover h4 {
    color: var(
      --nebula-pink
    ); /* Virare instantanee a culorii literelor pe lungimea de undă roz alertă */
    border-bottom-color: var(
      --nebula-pink
    ); /* Sincronizează perimetrul de bază al elementului */
    text-shadow: 0 0 10px var(--nebula-pink); /* Intensifică aureola fluorescentă pe nuanța roz-neon */
  }

  /* 5. TUNELUL DE SCROLL PENTRU CELE 60+ DE ZILE (Singurul loc permis în stânga) */
  .sidebar-nav ul {
    overflow-y: auto !important; /* REPARAȚIA SALVATOARE: Activează scroll-ul vertical strict în interiorul listei <ul> */
    flex-grow: 1; /* Instruiește lista să se extindă elastic și să ocupe tot spațiul rămas liber la bază */
    margin: 0;
    padding-left: 0;
    padding-right: 5px; /* Ecartament fin în dreapta pentru ca textul butoanelor să nu lovească șina de scroll */
    list-style: none; /* Curăță punctele native inestetice ale listelor nesortate */
  }

  /* Personalizarea barei subțiri de scroll din interiorul listei (Roz stelar) */
  .sidebar-nav ul::-webkit-scrollbar {
    width: 3px; /* O face extrem de fină (3px) pentru a nu încărca vizual monitorul tehnic */
  }
  .sidebar-nav ul::-webkit-scrollbar-thumb {
    background: rgba(
      255,
      0,
      127,
      0.3
    ); /* Culoarea roz nebula-pink originală la o opacitate discretă de 30% */
    border-radius: 2px; /* Rotunjire minimalistă industrială a capsulei mobile de derulare */
  }

  /* 6. CONȚINUTUL DIN DREAPTA (Zona independentă unde citești articolele) */
  .log-content {
    height: 100%; /* Își preia întreaga înălțime utilă a coloanei sale alocate din grid-ul master */
    overflow-y: auto !important; /* Activează scroll-ul vertical independent doar pentru textul dens al jurnalului */
    padding: 40px 60px 60px 60px; /* Pernă extinsă masivă de aer pentru a izola blocurile narative de margini */
    scroll-behavior: smooth; /* Efect cinematic fluid și lin atunci când se execută salturi prin link-uri */
    box-sizing: border-box; /* Înglobează marginile interne în calculul lățimii pentru a opri overflow-ul */
    padding-top: 50px !important; /* Padding superior obligatoriu ce împinge conținutul sub nivelul HUD-ului fixed */
  }

  /* REPARAȚIE COMPENSARE COLOANĂ DREAPTA */
  .log-content .category-header {
    padding-top: 20px !important; /* Perna fină de aer simetrică ce echilibrează deschiderea de pagină */
    margin-top: 0 !important; /* Anulează marjele native parazite pentru a se alinia la tavan cu sidebar-ul */
  }

  /* 7. AMORTIZARE VIZUALĂ LA ATERIZARE (Alinierea laser a logurilor zilnice) */
  .log-entry {
    min-height: calc(
      100vh - 150px
    ); /* Forțează fiecare log zilnic să fie o entitate uriașă și izolată vizual pe ecran */
    margin-bottom: 80px; /* Împinge restul zilelor jos, eliminând reziduurile din ziua anterioară la citire */
    padding-top: 40px;
    scroll-margin-top: 100px !important; /* BARIERA ABSOLUTĂ: Oprește scroll-ul cu exact 100px deasupra titlului zilei */
    border-top: 1px dashed rgba(255, 0, 127, 0.05); /* Delimitare micro-fină punctată la 5% opacitate roz */
  }

  /* 8. OPTICĂ DE BORD: ASIGURARE ȘI PERSONALIZARE SCROLL INTERN DREAPTA */
  .log-layout::-webkit-scrollbar {
    display: none; /* Mascăm scrollbar-ul nativ gros al browserului în layout-ul de loguri, eliberând index-ul */
  }
  .log-content::-webkit-scrollbar {
    width: 4px; /* O linie subțire și tehnologică pură de radar în flancul drept */
  }

  .log-content::-webkit-scrollbar-track {
    background: rgba(
      13,
      15,
      20,
      0.5
    ); /* Fundal întunecat transparent Solaris, aproape invizibil în carcasă */
  }
  .log-content::-webkit-scrollbar-thumb {
    background: rgba(
      157,
      23,
      248,
      0.3
    ); /* O nuanță discretă originală de violet asortată cu porțile de sector /border-radius: 4px;          /* Finisaj capsular minimalist pentru piesa mobilă de scroll */
  }
} /* @section: Desktop Layout - Închidere Media Query */

```

16. 2.  **00.2.B. GLOBAL MUTATION PROTOCOL: MOBILE VIEWPORTS (max-width: 768px)**

17. 2. 1. **00.2.B.1. SCUTUL ANTI-OVERFLOW & CONSOLA HUD ORIZONTALĂ (max-width: 768px)**

**REZUMAT / SUMMARY**: Acest prim district tactic de mobil dezactivează rețeaua asimetrică de desktop și instalează o bandă holografică orizontală cu profil ultra-jos pentru capitole. Prin aplicarea scutului rigid de `100vw` și a unei inginerii compacte de glisare tactilă, sub-grupul blochează total jocul parazit orizontal al documentului, lăsând elementele copii să culiseze asincron în siguranță.

- **Selectorul Macro `.log-layout` (Scutul Absolut Anti-Întindere)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează containerul părinte master al paginii de jurnal (`<div class="log-layout">`) în interiorul interogării media mobile (`max-width: 768px`).
  - **Misiunea**: Blochează și forțează lățimea structurală a întregului ansamblu la exact lățimea ecranului fizic disponibil prin directivele unificate `width: 100vw !important` și `max-width: 100vw !important`. Introduce regula defensivă absolută `overflow-x: hidden !important`.

- **Selectorul `.log-sidebar` (Banda Holografică cu Profil Ultra-Jos)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează șasiul exterior al sidebar-ului (`aside`), transformat pe mobil dintr-un turn lateral într-o consolă orizontală de navigare.
  - **Misiunea**: Suprascrie și forțează poziționarea absolută prin `position: fixed !important` lipită elastic la exact `top: 60px` sub HUD-ul superior, limitând profilul vertical la exact `height: 40px !important`. Aplică o extindere asimetrică prin marje negative masive (`margin-left: -40px !important`, `margin-right: -40px !important`) cuplată cu formula matematică `width: calc(100vw + 80px) !important`. Încarcă textura neagră stelar Solaris la 85% opacitate cu un blur dens de `20px`, o linie laser roz fină de `1px` la bază și o umbră triplă combinată cu un `inset` superior de `0 1px 0px`. Deschide motorul Flexbox orizontal (`display: flex !important`, `align-items: center`, `justify-content: flex-start`) și activează direct scroll-ul orizontal prin `overflow-x: auto !important`, `overflow-y: hidden !important`, ascunzând barele în Firefox și IE legacy.

- **Selectorul `.log-sidebar::-webkit-scrollbar` (Purificarea Interfeței Webkit)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează pseudo-elementul dedicat interfeței de scrollbar atașat în mod direct carcasei consolei mobile.
  - **Misiunea**: Introduce un ordin direct de anihilare vizuală exclusiv prin proprietatea structurală nativă **`display: none;`**, fără directive sau parametri suplimentari de dimensiune.

- **Selectorul `.sidebar-nav a` ȘI `.sidebar-nav a.active` (Capsulele de Zi și Semnalul Active)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează legăturile ancore simple din listă, folosite pentru declanșarea zilelor de studiu, împreună cu starea lor dinamică de marcare curentă `.active`.
  - **Misiunea**: Pe starea generală, elimină fundalurile solide (`background: transparent`), încadrează textul într-un border original subțire de 10% opacitate verde-mentă (`rgba(167, 243, 208, 0.1)`), un padding ultra-compact de `4px 8px !important` și blochează culoarea pe **`var(--solar-mint)`** cu o opacitate redusă la `0.6`. La starea `.active`, comută border-ul și textul instantaneu pe roz-magenta (`var(--nebula-pink)`), ridică opacitatea la `1`, activează un `text-shadow` fin de `5px` și aprinde o umbră exterioară originală simplă de **`box-shadow: 0 0 10px rgba(255, 0, 127, 0.2);`**.

- **Selectorul Master `.map-title-link` ȘI `.map-title-link h4` (Capsula Mobilă a Hărții)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează butonul mare de ancoră dreptunghiular (`.map-title-link`) plasat pe desktop în fruntea sidebar-ului, împreună cu eticheta `h4` din interior, reconfigurate pe mobil ca o tachetă orizontală asortată în banda HUD.
  - **Misiunea**: Modifică radical comportamentul structural pe mobil prin directiva **`display: inline-flex !important`**, anulând forțarea de bloc de pe desktop. Blochează lățimea mecanic la dimensiunea exactă a literelor din interior prin `width: auto !important` și `max-width: max-content !important`, activând scutul anti-strivire `flex-shrink: 0 !important`. Pe elementul `h4` interior, execută un reset ierarhic complet prin `position: static !important` și marje zero, micșorând fontul la `0.6rem !important` cu majuscule militare și spațiere de `1px`.

- **Selectorul Master `.map-title-link` ȘI `.map-title-link h4` (Capsula Mobilă a Hărții)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Portalul Flotant de Navigație Centrală (The Mobile Sovereignty Beacon)**. Pe mobil, acest buton părăsește rolul de „antet fix de turn” și este forțat să ruleze pe aceeași linie electromagnetică cu butoanele de zi. El devine o capsulă tactică compactă care glisează odată cu restul listei. Învelișul opac Solaris la 95% opacitate cu chenarul dublu roz-neon (`border: 1px double var(--nebula-pink)`) semnalizează vizual că acest element este o ancoră de control de ordin superior, diferită de butoanele de zi verzi simple, în timp ce textul interior `h4` luminează verde radar (`var(--solar-mint)`) cu o aureolă fină, validând prezența semnalului.
- **Logica Cascadei**: **Aceasta este o unificare structurală salvatoare de o specificitate uriașă (The Structural Anchor Sync)**. Prin plasarea celor doi selectori (părinte și copil) umăr la umăr la finalul lui 00.2.B.1, eliminăm riscul ca browserul să aplice parazit regulile agresive din modulele superioare. Directiva `display: inline-flex !important` este piesa de șah supremă: ea forțează elementul să accepte proprietățile de aliniere Flexbox orizontală din `.log-sidebar`, permițându-i să se așeze curat pe rând, în stânga primei zile (`Day 01`), în timp ce `border-bottom: none !important` pe `h4` purifică instantaneu liniile dashed moștenite de pe desktop.

18. 2. 2. **MODULE 00.2 // PROTOCOL 00.2.B.2: READING CHAMBERS & TITLE RESTRUCTURING**

**REZUMAT / SUMMARY**: Acest al doilea district izolează și restructurează ierarhia tipografică a cronicilor zilnice pe ecrane înguste. Prin comutarea axei Flexbox din linie în coloană pe titlurile mari, oferirea independenței pe rând textului metaforic verde și împingerea defensivă a antetelor macro de secțiune în jos, sub-grupul elimină riscul de strivire a textului și garantează o scanabilitate HUD impecabilă pe dispozitive mobile.

- **Selectorul `.log-entry h3` ȘI `.log-entry h3 .meta-title` (Decompresia Titlurilor Lungi)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează elementul de titlu de rangul 3 (`<h3>`) care deschide fiecare zi de jurnal în parte, împreună cu tagul copil `.meta-title` care încapsulează titlul metaforic extins în format fosforic.
  - **Misiunea**: Păstrează modelul structural Flexbox din desktop, dar suferă o transformare axială radicală prin directiva **`flex-direction: column !important`** cu un `align-items: flex-start !important`. Deschide un interval curat de `gap: 8px !important` pe verticală și setează un `font-size: 1.1rem !important`. Pe elementul `.meta-title` copil, forțează o lățime absolută de `width: 100% !important`, coborând dimensiunea textului la `0.9rem !important` cu o aliniere la stânga (`text-align: left !important`).

- **Selectorul Macro `.category-header` (Centrarea și Declanșarea Tamponului de Aer)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează antetul macro central (`<header class="category-header">`) situat în fruntea marilor capitole didactice (Modulele 01–14).
  - **Misiunea**: Modifică radical spațierea verticală superioară prin injectarea unui tampon masiv de aer de **`padding-top: 140px;`**, fixează o pernă inferioară de `30px` și forțează centrarea orizontală totală prin `text-align: center;`.

16. 2. 3. **MODULE 00.2 // PROTOCOL 00.2.B.3: CLICK LANDING BUFFER & ANTI-DEBRIS SHIELDING**

**REZUMAT / SUMMARY**: Acest al treilea district de mobil izolează și decontaminează ierarhia de ancorare vizuală (Scroll Locking) și scuturile optice de curățare a ecranului pe rezoluții mobile. Prin unificarea punctelor de oprire la fix `120px` sub tavan și instalarea barierelor defensive cu margini negative, sub-grupul absoarbe cu succes șocurile vizuale provocate de salturile din JavaScript și elimină golurile parazite din spatele consolei HUD.

---

- **Selectorul Comus `.log-content article[id], .log-entry` (Amortizorul de Aterizare Tactica)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează în mod simultan articolele individuale de zi și containerele lor cu ID unic din flancul de lectură (`<article class="log-entry" id="...">`) în interiorul interogării media mobile (`max-width: 768px`).
  - **Misiunea**: Sincronizează și blochează cursa animației de derulare prin directiva rigidă `scroll-margin-top: 120px !important`. Impune o pernă de aer superioară prin `padding-top: 20px !important` și securizează o zonă de demarcație inferioară de siguranță la podea prin `margin-bottom: 100px !important`.

- **Selectorul `.sector-announcement` (Scutul Airlock Anti-Reziduuri Unificat)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează casetele de avertizare și porțile etanșe de sector (`<div class="sector-announcement">`) care marchează trecerile către noi districte tehnologice (unificând cele două declarări fragmentate din codul vechi).
  - **Misiunea**: Aliniază protocolul de oprire la click cu restul cronicilor prin directiva fixă `scroll-margin-top: 120px !important`. Instalează o reparație de tracțiune mecanică în tavan prin marginea negativă **`margin-top: -30px !important`**, compensează spațiul prin `padding-top: 40px !important` și blochează distanța inferioară la **`margin-bottom: 80px !important`**.

16. 2. 4. **MODULE 00.2 // PROTOCOL 00.2.B.4: INGINERIA AVANSATĂ ȘI SCALAREA VOLUMETRICĂ**

Acest sub-grup monolitic izolează și decontaminează operațiunile adaptive de înaltă complexitate ale navetei Solaris. El controlează transformarea elementelor tridimensionale macro, a ecranelor catodice splitate și a sistemelor kinetice asincrone, eșalonat pe 4 zone strategice de învățare:

**REZUMAT / SUMMARY**: Acest sub-grup unificat centralizează operațiunile adaptive de cea mai înaltă complexitate ale navetei Solaris. El guvernează conversia structurală a componentelor tridimensionale macro, a ecranelor catodice splitate și a sistemelor kinetice asincrone, securizând interfața pe mobil prin scuturi absolute anti-wrap și reconfigurări volumetrice imune la colaps vizual.

**ZONA A: TERMINALELE MAȘINII DE SCRIS SINCRONE (`.mission-status`)**

**ZONA A (Terminalele Mașinii de Scris Sincrone)**: Gestionează deparazitarea textelor automate de status. Introduce scuturi absolute anti-wrap pentru a proteja integritatea pașilor exacti ai animației `typing-modular` și ascunde barele orizontale pentru a opri overflow-ul de litere pe telefoane.

- **Selectorul `.mission-status` ȘI `.mission-status p` (Scutul Anti-Wrap)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează terminalul verde-fosforic de status tactil, un element de afișare asincronă prezent în secțiunea Hero și în panourile blueprint recursive, împreună cu paragrafele din interior.
  - **Misiunea**: Dezactivează blocarea orizontală forțată de pe desktop prin activarea unui tunel local de glisare pe axa X via `overflow-x: auto !important` și anihilează interfața webkit nativă a scrollbar-ului (`display: none !important`). Pe elementul copil `p`, micșorează fontul tehnic la o lizibilitate optimă de `0.75rem !important` și injectează directiva critică de mediu `white-space: nowrap !important`.

**ZONA B: COMPRESIA GEODEZICĂ A REACTORului 3D (`.armillary-reactor-core`)**

**ZONA B (Compresia Geodezică a Reactorului 3D)**: Rulează scalarea volumetrică a Icosaedrului cu 20 de fețe. Reduce diametrul macroscopic al sferei de la `460px` la parametri compatibili de mobil, recalibrând poziționările unghiulare axiale fără a aplatiza sau degrada adâncimea spațială cubică.

- **Componentele Volumetrice 3D ale Icosaedrului (Scalarea Nucleului)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează în mod simultan scena spațială 3D (`.armillary-reactor-core`), nucleul poliedric cu 20 de fețe (`.quantum-plasma-sphere`), inelele energetice concentrice (`.sphere-ring`) și containerele paralele de aliniere eliptică (`.macro-wrapper` / `.micro-wrapper`).
  - **Misiunea**: Reduce înălțimea totală a scenei la `340px !important` cu un `margin-top: 100px !important`. Unifică diametrul sferei și al inelelor interioare la o cotă simetrică unică de **`260px !important`**, lărgind astrolabul decorativ exterior la `width: 95% !important`. Repoziționează benzile paralele pe noul ecuator redus prin coordonatele stricte `top: 120px !important` și `top: 175px !important`, restrângând fasciculele laser (`::after`) la `width: 80% !important`.

**ZONA C: MATRICEA DE SCALARE TIPOGRAFICĂ ȘI HERO HUD**

**ZONA C (Matricea de Scalare Tipografică și Hero HUD)**: Gestionează redimensionarea elastică a textelor oțelite stencil și a antetelor prin unități dinamice calculate pe baza lățimii fizice a ecranului (`2.4vw` / `0.65rem`), protejând cockpit-ul de colaps vizual.

- **Selectorul `.stenciled-metal-text` ȘI `.stenciled-metal-text-sub` (Ierarhia Stencil)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează titlul principal oțelit H1 din secțiunea Hero, împreună cu subtitlul monospațiat tehnic situat direct dedesubt, responsabile de execuția primelor fluxuri asincrone de scriere.
  - **Misiunea**: Prăbușește dimensiunea titlului H1 la un format fix și compact de `1.15rem !important` cu o spațiere strânsă de `1px !important`, reducând grosimea cursorului clipitor la exact `border-right-width: 2px !important`. Pe subtitlu, forțează o a doua regulă defensivă strictă care îngheață fontul la o cotă minimă liliputană fixă de `0.65rem !important` cu un spațiu micro-fin între litere de `0.5px !important`.

**ZONA D: ȘASIUL BLUEPRINT SPLIT-SCREEN & REȚEAUA DE TABURI HUD**

**ZONA D (Șasiul Blueprint Split-Screen)**: Guvernează deconstrucția monitorului asimetric de cod din secțiunea recursivă. Convertește cele două panouri paralele laterale dintr-un rând orizontal într-o stivă verticală rigidă, unificând totodată butoanele elastice de tab într-o rețea tactilă fluidă.

- **Monitorul Recursiv ȘI Butoanele Pastile de Comutare (`.blueprint-container` / `.tab-btn`)**
  Arhitectura Funcțională (Rol în context & Misiune)
  - **Rolul în context**: Targetează cutia generală a ecranului recursiv (Inspectorul de Blueprint), panourile despărțite de cod (`.terminal-split`), micro-eticheta CRT (`.code-inspector-screen::before`) și rețeaua de butoane HUD active.
  - **Misiunea**: Instalează o marjă compactă de `80px auto 40px` pentru a coborî schița sub consolă și blochează lățimea la `100%` prin directiva defensivă `overflow-x: hidden !important`. Convertește panourile din linie orizontală în stivă verticală rigidă (`flex-direction: column !important`), micșorând padding-ul pe `.panel` la exact `15px !important`. Rescalează micro-eticheta CRT la `0.55rem !important` poziționată strâns în colț (`top: 6px`, `right: 10px`), deparazitează typewriter-ul interior prin tratamentul stratificat `nowrap` și unifică taburile prin regula elastică `flex: 1 1 auto !important` cu un `flex-wrap: wrap !important` pe container.

```
/* ==========================================================================
    00.2.B. GLOBAL MUTATION PROTOCOL: MOBILE VIEWPORTS (max-width: 768px)

    REZUMAT: Acest macro-bloc guvernează întreaga mutație genetică de layout
    pentru ecranele mici de telefoane și tablete. El prăbușește grilele rigide
    de desktop, eliberează scroll-ul documentului global, transformă sidebar-ul
    într-o consolă HUD orizontală glisantă prin atingere (touch swipe) și compactează
    geometric reactorul 3D poliedric, ecranele splitate recursive și casetele
    de status pentru a garanta o experiență mobilă imună la overflow lateral.
   ========================================================================== */

/* ==========================================================================
    00.2.B.1. SCUTUL ANTI-OVERFLOW & CONSOLA HUD ORIZONTALĂ (max-width: 768px)

    REZUMAT: Acest district structural execută mutația genetică a layout-ului
    central pentru ecrane mici. El instalează scutul absolut de 100vw pentru a
    tăia jocul parazit orizontal al paginii mari, comprimă turnul sidebar într-o
    consolă fixă ultra-joasă de 48px poziționată sub navbar și deblochează tunelul
    de glisare tactilă orizontală a capitolelor prin ascunderea scrollbar-urilor.
   ========================================================================== */

@media (max-width: 768px) {
  /* [PRO UX SECURITY] - Neutralizarea anomaliei de derivă orizontală */
  .log-layout {
    width: 100vw !important; /* Forțează layout-ul să aibă exact lățimea ecranului fizic */
    max-width: 100vw !important; /* Scut anti-întindere absolut */
    overflow-x: hidden !important; /* REPARAȚIA SALVATOARE: Taie instantaneu pixelii excedentari ai consolei HUD și INTERZICE total paginii mari să mai poată fi glisată sau mișcată la stânga și la dreapta! */
  }

  /* CONTAINERUL EXTERIOR AL CONSOLEI (Banda holografică perfect aliniată) */
  .log-sidebar {
    /* REPARAȚIE TOP FLUID: Scoatem !important. Acum JavaScript are permisiunea totală
       să tragă consola HUD în top: 0 când navbarul dispare, sigilând tavanul paginii! */
    /* position: sticky; */

    position: fixed !important; /* MODIFICAREA A: Trecem elementul pe fixed pentru a bloca definitiv bara pe ecran, independent de restul paginii */
    top: 60px; /* MODIFICAREA B: O lipim etanș la fix 60px sub navbar, eliminând golul inestetic de la inițializare */

    /* REPARAȚIE ENTRALĂ INDENTARE: Preluăm pachetul tău original de extindere de la pagina 1
       pentru a forța bara să anuleze padding-ul părintelui și să se lipească dintr-o margine în alta! */
    margin-left: -40px !important; /* Trage marginea stângă în exteriorul containerului pentru a anula padding-ul general */
    margin-right: -40px !important; /* Trage marginea dreaptă în mod simetric în afara barierelor native ale paginii */
    width: calc(
      100vw + 80px
    ) !important; /* Compensează matematic marginile trase în exterior, extinzând bara pe toată lățimea fizică */

    height: 40px !important; /* Profil ultra-jos original compact de bandă tehnică, forțat uniform la 40px */
    padding: 0 15px !important; /* Pernă fină de aer internă pe laterale pentru protecția vizuală a capsulelor glisate */
    box-sizing: border-box !important; /* Include padding-ul în calculul lățimii, blocând dilatările parazite de pixeli */
    z-index: 1005 !important; /* Prioritate de plutire deasupra articolelor; textul cronicilor nu mai poate trece peste ea */

    /* CORECTURA ȘI PĂSTRAREA TEXTURII HOLOGRAFICE SF */
    background: rgba(
      10,
      11,
      20,
      0.85
    ) !important; /* Negru profund stelar original cu o transparență cinematică densă de 85% */
    backdrop-filter: blur(
      20px
    ) !important; /* Intensificăm blurul: textul lung care trece pe sub ea este șters cinematic din fundal */

    /* Linia micro-fină laser roz-magenta înlocuiește definitiv bordura groasă verde din versiunea desktop */
    border-bottom: 1px solid rgba(255, 0, 127, 0.25) !important;

    /* Umbră duală de propulsie neon care oferă iluzia că ecranul plutește pe un câmp magnetic
        REPARAȚIE VIZUALĂ HOLOGRAFICĂ:
        Mărim umbra duală exterioară roz de jos și adăugăm un INSET roz în tavan (0 4px ...).
        Această directivă creează o reflexie micro-fină de lumină roz aprinsă chiar în buza
        de sus dintre consolă și navbar, transformând bara într-o hologramă perfectă! */
    box-shadow:
      0 4px 15px rgba(255, 0, 127, 0.12),
      /* Umbră exterioară inferioară fină ce oferă profunzime și relief */ inset
        0 1px 0px rgba(255, 0, 127, 0.25),
      /* Reflexia laser roz-neon injectată chirurgical în buza superioară */
        inset 0 -1px 0px rgba(167, 243, 208, 0.1) !important; /* Micro-linia fosforică verde-mentă de jos păstrată intactă */

    /* ALINIERI AXIALE ȘI FLUX DE GLISARE ORIZONTAL */
    display: flex !important; /* Activează modelul Flexbox pe orizontală pentru alinierea în linie a componentelor */
    align-items: center !important; /* Centrează perfect capsulele de zi pe axa verticală în interiorul celor 40px */
    justify-content: flex-start !important; /* Toate elementele pornesc rigid din extrema stângă (portul de inițializare) */

    /* TUNELUL INDEPENDENT DE SWIPE (Ascunde barele parazite în toate browserele mobile) */
    overflow-x: auto !important; /* Permite glisarea liberă pe orizontală a listei de capitole de la stânga la dreapta */
    overflow-y: hidden !important; /* Îngheață complet axa Y pentru a bloca orice deviație verticală parazită */
    -webkit-overflow-scrolling: touch; /* Activează impulsul cinematic nativ prin atingere pe ecranele telefoanelor iOS/Android */
    scrollbar-width: none !important; /* Ascunde complet bara de scroll nativă pe browserele din ecosistemul Firefox/Gecko */
    -ms-overflow-style: none !important; /* Purifică și ascunde scrollbar-ul pe browserele din arhitectura legacy Microsoft */
  }

  /* ASCUNDEREA BAREI DE SCROLL PENTRU CHROME, SAFARI ȘI OPERA */
  .log-sidebar::-webkit-scrollbar {
    display: none; /* Dispare complet bara roz/standard pe mobil, lăsând interfața curată */
  }

  /* ALINIEREA CENTRALĂ A NAVIGAȚIEI (Aliniem titlul și lista pe același rând) */
  .sidebar-nav {
    display: flex !important; /* Activează Flexbox pe containerul interior direct pentru aliniere orizontală */
    align-items: center !important; /* Menține elementele aliniate perfect la mijlocul benzii în mod simetric */
    height: 100% !important; /* Ocupă întreaga înălțime a consolei master de 40px */
    width: max-content !important; /* Permite containerului să se lungească liber pe orizontală cât toate butoanele */
  }

  /* TITLUL DEVENIT ETICHETĂ FIXĂ ÎN STÂNGA (Butonul tău de top curat și mini) */
  .sidebar-nav h4 {
    display: flex !important; /* Îl readucem forțat în consolă, anulând ascunderea de desktop a widgetului */
    position: static !important; /* Resetează poziționarea absolută de pe desktop pentru a nu pluti haotic */
    font-size: 0.55rem !important; /* Dimensiune liliputană originală: protejează restul link-urilor de strivire */
    padding: 0 10px !important; /* Umplutură laterală originală calculată pentru spațiul de siguranță */
    margin: 0; /* Resetează marginile parazite ale browserului */
    border-right: 1px solid var(--solar-mint); /* Linia originală verticală rigidă verde-mentă de separare */
    white-space: nowrap; /* Interzice textului să se fragmenteze pe două rânduri sau să se rupă */
    align-items: center; /* Centrează textul pe verticală în interiorul etichetei compacte */
    color: var(--solar-mint); /* Text aprins original pe verde fosforic curat */
    height: 25px; /* Înălțime fixă originală pentru o aliniere perfectă în linie */
  }

  /* LISTA PROPRIU-ZISĂ DE BUTOANE (Aliniere laser pe orizontală) */
  .sidebar-nav ul {
    display: flex !important; /* Forțează lista să devină o linie flexibilă orizontală continuă */
    align-items: center; /* Aliniază toate elementele listei la mijlocul axei verticale */
    height: 100%; /* Se întinde pe toată înălțimea nav-ului interior */
    padding: 0 10px !important; /* Aer original aplicat doar între elemente în mod controlat */
    margin: 0; /* Resetează marjele native */
    gap: 10px; /* Distanța fizică originală fixă de 10px între butoane */
    list-style: none; /* Șterge punctele implicite ale listei HTML */
    width: auto; /* Formula ta originală: permite listei să respire liber în lățime */
  }

  /* ETICHETELE DE SĂPTĂMÂNĂ // SECTOR MARKERS (Versiune Orizontală Octogonal Poligonală) */
  .sidebar-nav .week-label {
    margin: 0 4px !important; /* Pernă fină de aer în stânga și dreapta pe panglică în timpul swipe-ului */
    display: flex !important; /* Activează Flexbox pe etichetă pentru alinierea textelor în interior */
    align-items: center !important; /* Centrează perfect butonul octogonal pe axa verticală a HUD-ului de mobil */
    height: 100% !important; /* Ocupă toată înălțimea utilă a consolei de mobil de 40px */
    flex-shrink: 0 !important; /* Scut absolut anti-strivire: restul capsulelor nu au voie să deformeze polygonul */
  }

  /* REGLAJ MILIMETRIC BUTON INTERIOR SECTOR PE MOBIL */
  .sidebar-nav .week-label a {
    /* TOATĂ GEOMETRIA OCTOGONALĂ (`clip-path`) ȘI CULORILE SUNT MOȘTENITE CONFORM ACORDULUI DE SUS! */
    font-size: 0.6rem !important; /* Dimensiune tehnică liliputană, asortată la fix cu capsulele de zi */
    padding: 4px 10px !important; /* Umplutură originală compactă adaptată pentru banda de 40px */
    border-radius: 0 !important; /* REPARAȚIE: Forțăm 0 pentru ca colțurile tăiate mecanic la 45° să fie perfect ascuțite, nu rotunjite! */
    display: inline-flex !important; /* Menține alinierea pe centrul poligonului pentru o așezare impecabilă */
  }

  /* EFECT HOVER PE MARCAJUL DE SECTOR VIOLET */
  .sidebar-nav .week-label a:hover {
    background: var(
      --nebula-purple
    ) !important; /* Fundalul se aprinde complet pe violet solid din variabila de root */
    color: white !important; /* Textul devine alb curat pentru contrast maxim pe placă */
    opacity: 1; /* Luminozitate totală nominală pe parcursul interacțiunii */
  }

  /* BUTOANELE DE ZI INDIVIDUALE (Minimaliste, doar text și bordură fină) */
  .sidebar-nav li {
    flex: 0 0 auto; /* Împiedică elementele din listă să se întindă sau să se mărească haotic pe mobil */
    margin: 0 !important; /* Anulează definitiv marginile de desktop pentru a păstra alinierea strânsă */
    padding: 0 !important; /* Resetează umpluturile parazite ale browserului terestru */
  }

  /* BUTOANELE DE ZI MAI COMPACTE (Dimensiunile tale de aur) */
  .sidebar-nav a {
    background: transparent; /* Fără fundal solid în starea de repaus a elementelor */
    border: 1px solid rgba(167, 243, 208, 0.1); /* Chenar micro-fin original 10% verde-mentă fosforic */
    padding: 4px 8px !important; /* Dimensiune originală ultra-compactă adaptată pentru ecrane strâmte de mobil */
    font-size: 0.6rem !important; /* Font mic original tehnic de ecran radar pentru o scanabilitate rapidă */
    color: var(
      --solar-mint
    ); /* Culoarea stabilă verde-mentă extrasă direct din rădăcină */
    opacity: 0.6; /* Aspect desaturat, odihnitor pentru ochi în fază de repaus */
  }

  /* BUTONUL ZILEI ACTIVE CURENTE APRINS ÎN HUD MOBIL */
  .sidebar-nav a.active {
    border-color: var(
      --nebula-pink
    ); /* Chenarul comută pe roz-magenta intens de alertă de sistem */
    color: var(
      --nebula-pink
    ); /* Textul luminează complet pe aceeasi lungime de undă roz-magenta */
    opacity: 1; /* Intensitate luminoasă maximă nominală pe monitorul catodic */
    text-shadow: 0 0 5px var(--nebula-pink); /* Aura originală fină de neon împrăștiată în jurul cifrelor */
    box-shadow: 0 0 10px rgba(255, 0, 127, 0.2); /* Strălucire originală fină exterioară roz de plutire magnetică */
  }

  /* REPARAREA VIZUALĂ A LINK-ULUI DE HARTĂ PE MOBIL (Sincronizare cu stilul Desktop) */
  .map-title-link {
    /* REPARAȚIA STRUCTURALĂ UNICĂ: Doar inline-flex are voie să fie aici pe mobil! */
    display: inline-flex !important; /* Îl obligă să devină un element flexibil compact în linie orizontală */
    width: auto !important; /* Îi interzice cu sfințenie să ocupe 100% din lățimea ecranului */
    max-width: max-content !important; /* Se strânge chirurgical exact cât textul din interiorul său */
    flex-shrink: 0 !important; /* Scut anti-strivire: restul butoanelor din consolă nu pot deforma capsula */
    align-items: center !important; /* Centrează textul pe verticală în interiorul butonului mobil */
    justify-content: center !important; /* Centrează textul pe orizontală pentru o aliniere perfectă */

    /* RECONSTRUCȚIE CROMATICĂ MOBIL FIXĂ: */
    background: rgba(
      13,
      15,
      20,
      0.95
    ) !important; /* Fundal opac de sticlă neagră densă originală Solaris */
    border: 1px double var(--nebula-pink) !important; /* Chenarul original dublu roz-magenta de impact vizual! */
    box-shadow: 0 0 10px rgba(255, 0, 127, 0.2) !important; /* Aură fină de neon roz împrăștiată în jurul capsulei */
    padding: 4px 10px !important; /* Umplutură originală compactă, optimizată fin pentru banda HUD de 40px */
    border-radius: 4px !important; /* Rotunjire fină geometrică pe colțuri */
    white-space: nowrap !important; /* Interzice textului să se fragmenteze sau să se rupă vertical în consolă */
    margin: 0 !important; /* Curăță marjele exterioare pentru a rula în linie cu butoanele de zi */
    text-decoration: none !important; /* Elimină sublinierea nativă inestetică a link-urilor generată de browsere */
  }

  /* Textul interior h4 din capsula de mobil */
  .map-title-link h4 {
    position: static !important; /* Anulează poziționarea absolută de desktop pentru a-l integra în fluxul capsulei mini */
    margin: 0 !important; /* Șterge marginile parazite ale browserului terestru */
    padding: 0 !important; /* Resetează umpluturile native */
    font-size: 0.6rem !important; /* Dimensiune liliputană originală tehnică de ecran mobil */
    font-weight: bold !important; /* Îngroșat stabil original pentru o autoritate vizuală de control */
    color: var(
      --solar-mint
    ) !important; /* Aprinde textul pe verde-mentă fosforic pentru contrast maxim */
    text-transform: uppercase !important; /* Protocol militar de litere mari capitalizate obligatoriu */
    letter-spacing: 1px !important; /* Spațiere tehnică fină originală între caractere */
    border-bottom: none !important; /* Elimină orice dungă inestetică sau separator moștenit de pe desktop */
    background: transparent !important; /* Curăță fundalul parazit pentru a păstra transparența sticlei Solar */
    border: none !important; /* Siguranță maximă: elimină și eventualul chenar moștenit din cascadă */
    text-shadow: 0 0 5px rgba(167, 243, 208, 0.4) !important; /* Strălucire de ecran pornit, oglindind un radar active */
    width: auto !important; /* Resetează lățimea forțată de desktop din modulele superioare */
    white-space: nowrap !important; /* Interzice textului să se mai spargă pe verticală sau să se rupă */
  }

  /* ==========================================================================
    00.2.B.2. SEIFUL DE LECTURĂ ȘI AERISIREA TITLURILOR H3 (max-width: 768px)

    REZUMAT: Acest district izolează și decontaminează ierarhia tipografică a
    cronicilor zilnice pe ecrane înguste. El execută reparația salvatoare pentru
    titlurile metaforice ultra-lungi, comutând direcția Flexbox din linie în coloană,
    centrează axial antetele mari de secțiune pentru o simetrie perfectă și
    reconfigurează capsula de mobil a hărții pentru a preveni colapsul textului.
   ========================================================================== */

  /* REPARAREA ȘI AERISIREA TITLURILOR H3 (Suport pentru titluri metaforice ultra-lungi) */
  .log-entry h3 {
    display: flex !important; /* Păstrează sistemul Flexbox din desktop pentru aliniere structurală */

    /* REPARAȚIA SALVATOARE PENTRU MOBILE/SPLIT: Schimbăm direcția din linie în coloană!
        Asta așază automat titlul metaforic LUNG direct SUB textul roz „Day 09”,
       oferindu-i toată lățimea utilă a ecranului pentru a nu se mai sparge sau înghesui pe telefoane! */
    flex-direction: column !important;
    align-items: flex-start !important; /* Aliniază ambele blocuri de text (ID-ul de zi și denumirea) la marginea din stânga */
    gap: 8px !important; /* Lasă un spațiu fin și curat de 8px pe verticală între zi și denumire */
    flex-wrap: wrap !important; /* Permite textului să curgă liber în funcție de lățimea ecranului fizic */
    font-size: 1.1rem !important; /* Dimensiune tehnică compactă originală de ecran radar */
    border-bottom: 1px solid rgba(167, 243, 208, 0.1) !important; /* Linie fină originală de demarcație tehnică */
    padding-bottom: 10px !important; /* Mărit padding-ul pentru o barieră vizuală aerisită și elegantă */
    width: 100% !important; /* Ocupă tot ecranul util al casetei jurnal mobile */
  }

  /* Corecție estetică pentru textul metaforic din dreapta (devenit acum text de dedesubt) */
  .log-entry h3 .meta-title {
    font-size: 0.9rem !important; /* Îi mărim o idee dimensiunea originală pentru o lizibilitate perfectă pe mobil */
    color: var(
      --solar-mint
    ) !important; /* Menține aprinderea pe verde-mentă fosforic de sistem din root */
    letter-spacing: 1px !important; /* Spațiere industrială curată între caractere */
    width: 100% !important; /* Forțează elementul să își ia independența totală pe rândul lui dedesubt */
    text-align: left !important; /* Aliniere curată în stânga, direct sub ID-ul roz al zilei curente */
  }

  /* CENTRAREA SIMETRICĂ A ANTETULUI PE MOBIL */
  .category-header {
    padding-top: 140px; /* Împinge fizic antetul în jos cu 140px ca să nu fie acoperit de HUD-ul mobil sau navbar */
    padding-bottom: 30px; /* Pernă fină de air originală de 30px sub titlul mare de capitol */
    text-align: center; /* Centrare completă stabilă pe orizontală pentru o simetrie perfectă pe telefon */
  }

  /* ==========================================================================
    00.2.B.3. PROTOCOLUL DE ATERIZARE TACTICĂ ȘI SCUTURILE ANTI-REZIDUURI

    REZUMAT: Acest district guvernează amortizarea vizuală și punctele de oprire
    ale cronicilor la saltul din sidebar pe rezoluții mobile. El unifică logica
    de oprire la fix 120px sub tavan, injectează perna de aer superioară de 20px
    pentru a masca reziduurile grafice și instalează scutul mecanic cu margine
    negativă de -30px pe porțile AIRLOCK pentru a anihila golurile parazite.
   ========================================================================== */

  /*  ABSORBȚIA VIZUALĂ LA CLICK (Aterizare milimetrică sub consolă pe mobil) */
  .log-content article[id],
  .log-entry {
    /* CALIBRARE FIXĂ: Oprim scroll-ul la fix 120px sub tavan.
       Această valoare lipește marginea superioară a casetei direct de sub linia verde a consolei HUD. */
    scroll-margin-top: 120px !important;

    /* PERNA DE AER ELEGANTĂ: Împingem textul în jos cu 20px în interiorul casetei.
        Fundalul închis al articolului va acoperi acum tot spațiul de sub consolă,
        anulând dungile sau reziduurile transparente din spate! */
    padding-top: 20px !important;

    /* Păstrăm distanța de siguranță la podea pentru a asigura spațiu de manevră articolelor scurte */
    margin-bottom: 100px !important;
  }

  /* Corecție simetrică dedicată pentru Porțile AIRLOCK (Anunțurile de Sector - UNIFICARE ȘI CURĂȚARE CASCADĂ) */
  .sector-announcement {
    /* Sincronizare la fix 120px sub tavan la saltul din sidebar pentru o aliniere structurală unificată */
    scroll-margin-top: 120px !important;

    /* SCUTUL MECANIC ANTI-REZIDUURI (Absorbit din prima regulă din fabrică)
        Tragem vizual containerul în sus cu 30px prin margine negativă pentru a îngropa
        orice reziduu parazit de la butonul sau textul de deasupra. */
    margin-top: -30px !important;

    /* REGLAJ VIZUAL FINAL (Suprascris și executat de a doua regulă din fabrică) */
    padding-top: 40px !important; /* Umplutură internă echilibrată pentru ca titlul „THE HULL” să stea aerisit */
    margin-bottom: 80px !important; /* Lăsăm un margin-bottom stabil și curat, fără exagerări, sub poarta AIRLOCK */
  }

  /* ==========================================================================
    00.2.B.4. INGINERIA AVANSATĂ ȘI SCALAREA VOLUMETRICĂ (max-width: 768px)

    REZUMAT: Acest district final izolează ingineria grea adaptivă a navetei.
    El guvernează deparazitarea motorului typewriter prin scuturi anti-wrap,
    operează compresia volumetrică a Icosaedrului 3D la dimensiuni strânse de mobil,
    scalează elastic tipografia stencil prin unități dinamice "vw" și convertește
    monitorul split-screen recursiv într-o stivă verticală rigidă etanșă.
   ========================================================================== */

  /* --- REZUMAT ZONAL A: TERMINALELE MAȘINII DE SCRIS SINCRONE (.mission-status) ---
    Acest micro-district de siguranță deparazitează fluxul textelor automate de status.
    El instalează scutul absolut anti-wrap ("white-space: nowrap") pentru a proteja
    integritatea pașilor exacti ai animației typewriter ("steps") și deschide o
    trapă de glisare internă orizontală pe mobil, eliminând complet clipirile distructive. */

  /* --- 12. REPARAȚIE TEXT FLUID STATUS PE MOBIL/SPLIT --- */
  /* REGLAJ DE LĂȚIME PENTRU STATUSUL PE MOBIL:
      În loc să rupeți textul pe două rânduri, îi permitem barei de status
      sa facă un micro-scroll intern dacă textul e prea lung, protejând pașii animației! */
  .mission-status {
    overflow-x: auto !important; /* REPARAȚIA PRIN TRANSMISIE: Dezactivează blocarea orizontală și deschide un tunel local de glisare pe axa X pentru textul lung */
    scrollbar-width: none !important; /* Scut anti-poluare: șterge complet șina nativă de scrollbar pe browserele mobile din ecosistemul Firefox */
  }

  /* ELIMINAREA INTERFEȚEI VISUALE WEBKIT PENTRU MONITORUL DE STATUS */
  .mission-status::-webkit-scrollbar {
    display: none !important; /* Ordin dictatorial Webkit: anihilează și ascunde piesa mobilă pe Safari și Chrome mobile pentru un HUD curat */
  }

  /* SCUTUL DE CONFORMARE KINETICĂ PENTRU PARAGRAFELE TIP TYPEWRITER */
  .mission-status p {
    font-size: 0.75rem !important; /* Micșorăm discret textul tehnic pe mobil pentru a încăpea perfect în caseta HUD de mobil */
    white-space: nowrap !important; /* SCUTUL ANTI-WRAP SUPREM: Interzice cu sfințenie textului să se spargă pe două rânduri, salvând pașii steps(35) ai mașinii de scris */
  }

  /* --- REZUMAT ZONAL B: COMPRESIA GEODEZICĂ A REACTORULUI 3D (.armillary-reactor-core) ---
    Acest sector guvernează scalarea volumetrică a nucleului poliedric cu 20 de fețe.
    El reduce diametrul macroscopic al sferei de la 460px la parametri strânși de 240px,
    recalibrează distanțele superioare la 100px și fuzionează capsulele de aliniere
    paralelă pe noul ecuator compact (top: 120px/175px), integrând fasciculele laser. */

  /* RESPONSIVE COMPRESSION // MOBILE ALIGNMENT REACTOR (max-width: 768px) */
  .armillary-reactor-core {
    margin-top: 100px !important; /* Pernă de aer controlată sub navbar-ul fix pe mobil pentru a bloca suprapunerile */
    margin-bottom: 80px !important; /* Pernă inferioară redusă pentru ecrane scurte pentru a strânge layout-ul vertical */
    height: 340px !important; /* Compactare mecanică: reține întregul reactor în interiorul ecranului telefonului */
    scroll-margin-top: 180px !important; /* Amortizor de oprire fluidă la click pe logo legat direct de script.js */
  }

  /* COMPRESIE CORE POLIEDRIC ȘI INELE CONCENTRICE (Fuziunea salvatoare a duplicatelor) */
  /* Rezolvăm coliziunea din VS Code: forțăm o cotă unică simetrică de 260px pe ambele piese,
     eliminând riscul ca inelele interioare să se decaleze sau să se turtească sub formă de ou! */
  .quantum-plasma-sphere,
  .quantum-plasma-sphere .sphere-ring {
    width: 260px !important; /* Reducem dimensiunea miezului geodezic pentru a proteja marginile display-ului mobil */
    height: 260px !important; /* Păstrează raportul de aspect perfect 1:1, salvând adâncimea formatului preserve-3d */
  }

  /* CAPSULELE DE ALINIERE PARALELĂ (Lărgirea containerului la maximum pe mobil) */
  .armillary-band-container {
    width: 95% !important; /* Deschide inelele exterioare pe 95% din lățime pentru a folosi spațiul util */
  }

  /* Repoziționăm cele două benzi perfect paralele la mijlocul figurii reduse de 260px */
  .macro-wrapper {
    top: 120px !important; /* Cota de aur din fabrică: coboară banda macro pe noul centru geometric mobil */
    height: 45px !important; /* Înălțimea structurală fixă a inelului mare, păstrată neatinsă */
  }

  .micro-wrapper {
    top: 175px !important; /* Cota de aur din fabrică: aliniază inelul secundar fin sub ecuatorul reactorului */
    height: 35px !important; /* Înălțimea structurală fixă a inelului micro, conservată pe mobil */
  }

  /* Ajustăm pseudo-elementele laser discrete pentru cotele noi de mobil */
  .macro-wrapper::after,
  .micro-wrapper::after {
    left: 10% !important; /* Retrage originea orizontală la 10% pentru a centra perfect firul laser */
    width: 80% !important; /* Restrânge lungimea laserului la 80% pentru a nu străpunge inelele exterioare */
  }

  /* --- REZUMAT ZONAL C: MATRICEA DE SCALARE TIPOGRAFICĂ ȘI HERO HUD (max-width: 768px) ---
    Acest district controlează adaptarea elastică a tipografiei oțelite stenciled și a
    antetelor principale din secțiunea Hero. El implementează unitățile dinamice bazate
    pe lățimea fizică a viewportului (2.4vw) îmbinate cu plafoane fixe de 0.65rem,
    ajustează pernele laterale la 20px pe elementele macro și resetează marjele
    pentru a asigura o lizibilitate de înaltă rezoluție, imună la colaps vizual. */

  /* SCALARE TEXT TITLU H1 (Păstrarea identității Space Grotesk) */
  .stenciled-metal-text {
    font-size: 1.15rem !important; /* Dimensiune optimă rigidă finală executată pentru lizibilitate pe ecrane înguste */
    letter-spacing: 1px !important; /* Spațiere strânsă militară de interfață terminal */
    border-right-width: 2px !important; /* Cursor subțire adaptat ecranului mic de mobil */
  }

  /* REPARAȚIE DISCRETĂ SUBTITLU (Subordonare optică perfectă pe un singur rând) */
  .stenciled-metal-text-sub {
    font-size: 0.65rem !important; /* Plafonul rigid de siguranță original din fabrică ce oprește overflow-ul */
    letter-spacing: 0.5px !important; /* Spațiere micro-fină adaptată pentru textul monospațiat mobil */
    border-right-width: 1px !important; /* Firul laser marginal al mașinii de scris compactat */
  }

  /* --- REZUMAT ZONAL D: ȘASIUL BLUEPRINT SPLIT-SCREEN (max-width: 768px) ---
    Acest district guvernează conversia ecranului recursiv într-o stivă verticală rigidă.
    El elimină duplicatele parazite de înălțime fixă (anulând ecuațiile 100vh),
    forțează curgerea organică a panourilor prin "height: auto", deparazitează
    mecanica typewriter din interiorul panourilor de cod și fluidizează butoanele de tab. */

  /*  RESPONSIVE PROTOCOL // BLUEPRINT COMPRESSION
  Calibrarea terminalului recursiv pentru ecrane de telefon (max-width: 768px). */
  .blueprint-container {
    margin: 80px auto 40px auto !important; /* Pernă compactă de aer originală sub navbar pentru a lăsa spațiu util */
    padding: 10px !important; /* Strânge umplutura internă la 10px pentru a maximiza zona de afișare */
    width: 100% !important; /* Se întinde pe toată lățimea disponibilă în grila de mobil */
    overflow-x: hidden !important; /* Scut anti-scroll orizontal parazit pe corpul principal, oprind barca orizontală */
    box-sizing: border-box !important; /* Îngheață padding-ul în lățime pentru a opri dilatările de pixeli */
  }

  /* RECONSTRUCȚIE SPLIT: Trecem panourile în stivă verticală rigidă */
  .terminal-split {
    flex-direction: column !important; /* Forțează cele două panouri de cod (HTML/SQL) să cadă vertical unul sub celălalt */
    gap: 20px !important; /* Distanță rigidă de izolare de 20px între cele două terminale mobile */
    width: 100% !important; /* Ocupă integral spațiul orizontal de la o margine la alta a ecranului */
    box-sizing: border-box !important; /* Asigură imunitatea totală a modelului de casetă */
  }

  .panel {
    width: 100% !important; /* Panoul se mulează elastic pe display-ul telefonului în mod automat */
    padding: 15px !important; /* Padding redus militar pentru a câștiga spațiu util pentru liniile de cod */
    box-sizing: border-box !important; /* Blochează spargerea marginilor la randare */
  }

  /* Repoziționăm eticheta cinematică a monitorului CRT pentru rezoluții înguste */
  .code-inspector-screen::before {
    font-size: 0.55rem !important; /* Dimensiune liliputană a textului decorativ pentru a nu aglomera antetul */
    top: 6px !important; /* Îl lipește strâns de buza de sus a carcasei ecranului */
    right: 10px !important; /* Îl trage la fix 10px de flancul drept pentru o aliniere tehnică fină */
  }

  /* REPARAȚIE DISCRETĂ PENTRU CASETA MISSION STATUS ON MOBILE */
  .panel .mission-status {
    display: block !important; /* Trecem de la inline-block la block pentru a ocupa rândul curat în panou */
    width: 100% !important; /* Anulează forțarea 'max-content' care lăbărța containerul în dreapta în afara ecranului */
    max-width: 100% !important; /* Blocaj rigid de tavan ce securizează granițele vizuale */
    padding: 10px !important; /* Umplutură internă compactă originală de exact 10px */
    box-sizing: border-box !important; /* Păstrează modelul de casetă intact */
  }

  /* Forțăm textul din interiorul statusului să facă wrap dacă e prea lung pe mobil */
  .panel .mission-status p {
    font-size: 0.7rem !important; /* Scădere fină de font pentru a încadra telemetria pe ecrane medii */
    white-space: normal !important; /* Permite textului de status să curgă pe două rânduri pe telefoane (Starea de testare inițială) */
    line-height: 1.4 !important; /* Înălțime de rând aerisită originală pentru o citire comodă */
    letter-spacing: 1px !important; /* Spațiere tehnică adaptată stilului de terminal industrial */
  }

  /* INTERVENȚIE RECURSIVĂ DE URGENȚĂ: SCUT DE MOBIL ANTI-STIVUIRE
     Injectat direct în interiorul query-ului @media (max-width: 768px) */
  .panel .mission-status p,
  .blueprint-layout .mission-status p {
    white-space: nowrap !important; /* REPRIMARE TOTALĂ: Nimicește directiva normal/wrap pe telefoane, salvând pașii steps() ai mașinii de scris! */
    display: inline-block !important; /* Menține contextul de linie dreaptă continuă pe ecrane split/mobile */
    width: auto !important; /* Lasă textul să ruleze dincolo de marginile fizice înguste ale telefonului în interiorul overflow-ului */
    min-width: 0 !important; /* Permite animației typewriter să își facă pașii de la 0 la 100% fluid, fără blocaje */
  }

  .panel .mission-status,
  .blueprint-layout .mission-status {
    display: block !important; /* Forțează afișarea de tip bloc curat pe ambele terminale recursive */
    overflow-x: hidden !important; /* Scut defensiv: taie literele care se scriu în afara sticlei telefonului, oprind overflow-ul general */
    max-width: 100% !important; /* Împeidică bara de status să lăbărțeze sau să deformatze layout-ul de mobil */
  }

  /* FLUIDIZARE BUTOANE TAB HUD */
  .source-selector-tabs {
    flex-wrap: wrap !important; /* Permite butoanelor .html și .sql să treacă pe rândul doi dacă ecranul telefonului e de fix 320px */
    gap: 6px !important; /* Spațiu aerian strâns de exact 6px între pastilele de comutare active */
    width: 100% !important; /* Se extinde pe tot flancul orizontal interior disponibil în layout */
  }

  .tab-btn {
    flex: 1 1 auto !important; /* Butoanele devin elastice, împărțind simetric spațiul orizontal în mod egal */
    padding: 6px 10px !important; /* Dimensiune originală optimizată pentru interacțiunea tactilă cu degetul */
    font-size: 0.7rem !important; /* Font comprimat original tehnic ce garantează potrivirea perfectă a cuvintelor */
    text-align: center !important; /* Centrează geometric textele etichetelor (HTML, SQL, NOTES) în interiorul capsulei */
  }
} /* @section: Layout Mobile Layout - Închidere Media Query */
```

---

---

---

---

---

---

---

---

🧭 **LOGICA DE CURGERE A CASCADEI (De ce stă fiecare selector unde stă?)**

În CSS (Cascading Style Sheets), ordinea de scriere în fișier nu este o alegere estetică, ci o **lege cronologică a interpretării datelor** de către browser. Codul este citit de sus în jos. Elementele declarate mai sus devin fundații genetice, în timp ce elementele de mai jos le moștenesc sau le pot suprascrie selectiv.

Iată de ce structura noastră respectă această succesiune sacră, selector cu selector:

🌟 1. De ce Modulul 01 (`:root`) stă Primul?

- **Motivul Ontologic**: `:root` reprezintă geneza universului tău digital. Înainte ca browserul să deseneze prima linie sau să calculeze vreo dimensiune, el trebuie să își încarce „bateria centrală” de token-uri cromatice (culorile, gradienții, variabilele de font).
- **Logica Cascadei**: Dacă ai declara o variabilă cromatică la mijlocul sau la sfârșitul fișierului, selectorii de sus care încearcă să o apeleze prin funcția `var()` nu ar găsi-o la momentul citirii lor, generând erori de afișare și prăbușirea schemei de culori.

🌟 2. De ce Selectorul Universal (_, _::before, \*::after) deschide Modulul 02?

- **Motivul Ontologic**: Aceasta este prima lege fizică aplicată materiei. Înainte de a formata elemente specifice, trebuie să distrugi complet anomaliile și setările implicite haotice cu care vine fiecare browser de pe Pământ (marginile și padding-urile arbitrare).
- **Logica Cascadei**: Stând la începutul Modulului 02, regula `box-sizing: border-box` devine o proprietate genetică obligatorie pentru tot ce urmează. Orice element creat ulterior în fișier va fi obligat să își calculeze lățimea incluzând bordurile și spațiile interne, asigurând imunitate totală la colaps spațial.

🌟 3. De ce urmează `html` și apoi `body`?

- **Motivul Ontologic**: Reprezintă trecerea de la macro-structură (hardware) la micro-structură (interfața vizibilă). Elementul `html` încapsulează tot documentul la nivel de fereastră de browser, în timp ce `body` reprezintă puntea fizică pe care merge echipajul.
- **Logica Cascadei**: Regulile de pe `html` (cum ar fi blocarea scroll-ului orizontal prin `overflow-x: hidden`) trebuie să prindă rădăcini înaintea containerului `body`, oferind un cadru rigid exterior. `body` vine imediat sub el pentru a prelua controlul ambiental (gradientul de fundal, fontul global, line-height-ul textului).

🌟 4. De ce `body::before` stă imediat sub `body`?

- **Motivul Ontologic**: `body::before` este o mască fixă atașată direct pe geamul cockpit-ului. Deși din punct de vedere vizual stă deasupra tuturor elementelor (datorită unui `z-index` uriaș), din punct de vedere semantic și genetic el este o extensie directă a nodului părinte `body`.
- **Logica Cascadei**: Legarea lor consecutivă în cod respectă principiul proximității conceptuale. Când un programator (sau un elev de-al tău) studiază legile care guvernează puntea principală (`body`), el trebuie să vadă imediat și filtrul atmosferic care este aplicat peste aceasta (`body::before`), înțelegând instantaneu relația de subordonare structurală dintre nodul real și cel virtual.

🌟 5. De ce urmează `section`, `section[id]` și `.archive-body` în Modulul 02?

- După ce cascada a stabilit legile microscopice hardware (`*`, `html`) și învelișul ambiental planetar (`body`, `body::before`), ea coboară natural către **arhitectura macro a compartimentelor interioare**. Acești trei selectori definesc containerele gigant în care va fi injectat conținutul.

Iată logica de poziționare în cascadă pentru fiecare:

• Selectorul `section` (Comportamentul Implicit de Capitol)

- **Motivul Ontologic**: Reprezintă un element structural nativ (o etichetă HTML standard). În cascada CSS, selectorii de tip tag/element curat (`section`) trebuie să stea întotdeauna **înaintea** selectorilor mai specifici (cum sunt cei cu atribute sau clase).
- **Logica Cascadei**: Creează un șablon de bază pentru _toate_ capitolele site-ului. El impune pernele de aer masive (`padding-top: 120px` și `padding-bottom: 80px`) care eliberează textul din strânsoarea navbar-ului fix de sus și lasă o zonă de respirație vizuală în partea inferioară a modulelor.

• Selectorul `section[id]` (Sistemul de Ancorare și Targetare)

- **Motivul Ontologic**: Acest selector folosește un selector de atribut (`[id]`). În algoritmul de specificitate al CSS, selectorii de atribut au o greutate mai mare decât selectorii simpli de tag. De aceea, el stă **imediat sub `section`**.
- **Logica Cascadei**: El rafinează doar acele secțiuni care acționează ca destinații de teleportare (ancore din navbar). Impunerea regulii `min-height: 80vh` forțează macro-secțiunile să ocupe cel puțin 80% din înălțimea ecranului, garantând un aspect aerisit și monumental, în timp ce `scroll-margin-top: 0px` (sau valoarea calibrată de tine) asigură alinierea perfectă la scroll.

• Selectorul `.archive-body` (Scutul Anticolaps al Paginii Bibliografie)

- **Motivul Ontologic**: Acesta este un selector de clasă (`.`). În ierarhia CSS, clasele sunt și mai specifice decât etichetele simple. El stă la finalul acestui grup structural deoarece este o **excepție/configurare specială** aplicată unui corp de pagină specific (cum este `bibliography.html`).
- **Logica Cascadei**: Interzice lăbărțarea pe orizontală a tabelelor de date din interiorul paginii de bibliografie. Declararea regulilor `width: 100% !important` și `max-width: 100% !important` forțează acest container macro să rămână blocat în dimensiunea ecranului fizic, acționând ca o carcasă ranforsată ce nu permite datelor SQL sau tabelelor complexe să rupă grila layout-ului pe mobil.

🌟6. De ce selectorii `h2` si `h2:hover` sunt poziționați la începutul modulului 03

• Selectorul `h2` (Macro Indicators / Titluri de Volum și Capitol)

- **Motivul Ontologic**: Într-un univers SF de tip _Solaris_, titlurile de capitol sunt coordonate de sector, stâlpi de susținere ai cunoașterii. Ele trebuie să emită o prezență cromatică puternică, dar non-intruzivă structural. Rozul neon reprezintă energia activă a computerului de bord, ghidând privirea instantaneu spre începutul unei noi baze de date.
- **Logica Cascadei**: Stând la absolut începutul Modulului 03, selectorul general de tip etichetă (`h2`) definește o „stare genetică de bază” pentru toate elementele de acest tip din proiect. Orice `h2` nou creat va moșteni automat această culoare roz și umbră fosforică, lăsând modulelor ulterioare (Modulul 04 pentru Antete sau Modulul 09 pentru Porți de Sector) libertatea de a adăuga animații sau de a modifica culoarea local, prin specificitate crescută, fără a strica uniformitatea globală.

• Selectorul `h2:hover` (Suprapunerea de Energie Kinetică / Proximitate Terminal)

- **Motivul Ontologic**: Reprezintă feedback-ul vital dintre om și mașină. Interfața nu este un obiect inert, ci un organism digital reactiv. Aprinderea intensă a umbrei demonstrează că sectorul de date vizat este online, alimentat cu energie și gata pentru a fi explorat epistemic.
- **Logica Cascadei**: În ordinea de scriere a CSS-ului, stările dinamice (pseudo-clasele precum `:hover`, `:focus`, `:active`) trebuie să fie amplasate **imediat sub selectorul lor principal** (`h2`). Dacă ar fi plasate dezorganizat sau înaintea selectorului de bază, browserul ar putea ignora intensificarea luminoasă din cauza modului în care rescrie proprietățile identice în cadrul aceleiași etape de randare.

🌟 7. Selectrorul `h3` cu reguli minimaliste de culoare si `margin-top:0`

- **Motivul Ontologic**: În timp ce volumele mari sunt semnalizate masiv, sub-capitolele text au nevoie de un impuls cinetic puternic. Rozul-magenta acționează ca un indicator de tensiune ridicată în nodurile de text, avertizând cititorul că urmează o transmisie de date critică pentru continuarea expediției.
- **Logica Cascadei**: Plasarea lui `h3` cu această configurație în deschiderea Modulului 03 definește amprenta genetică a tagului. Orice sub-titlu simplu se va naște roz și lipit de marginea de sus. Când cascada va coborî spre modulele asimetrice avansate (cum sunt cardurile din Modulul 08 sau jurnalele flexbox din Modulul 11 si din query-ul de media pentru mobile/split screen), acele structuri specifice vor adăuga reguli complexe de aliniere sau vor schimba nuanțele local (pe bază de clase specifice), fără ca această directivă curată de pornire să fie alterată.

🌟 8. Regulile de pornire pentru `h4`, `h5`, `<p>`, `<p code>` si `<hr>` in Modulul 03 sunt minime

• Selectorul `h4`:

- **Motivul Ontologic**: În ierarhia semnelor de pe o navă spațială, `h4` reprezintă micro-transmisiile de diagnostic. Nu are nevoie de spectacolul vizual al rozului neon (`h2`) sau al mentei fosforice intense (`h3`), ci trebuie să ofere o citire sobră, chirurgicală, a datelor de inventar.
- **Logica Cascadei și a Media Queries**: Lăsarea definiției de bază în Modulul 03 și izolarea comportamentului `.log-sidebar h4` în modulele de layout și în Media Queries este un triumf didactic. Pe desktop, `h4` din sidebar acționează ca un antet de listă fix, dar când ecranul se restrânge sub `768px`, cascada rulează codul din Media Query, unde transformi acest titlu într-un element HUD interactiv (cum ar fi un buton central de meniu sau un indicator tactil orizontal). Acest lucru garantează că modificările de pe mobil nu vor polua niciodată listele de inventar din corpul textului narativ.

• Selectorul `h5`:

- **Motivul Ontologic**: În arhitectura CSS, un tag pur de nivel 5 nu are dreptul să impună linii punctate sau transformări structurale de tip block-to-inline întregului site. Dacă am fi lăsat codul vechi intact, orice utilizare viitoare a unui `<h5>` pe puntea SQL sau în interiorul Sondei Recursive ar fi declanșat o undă de șoc vizuală, parazitând noile ecrane cu sublinieri verzi nedorite. Curățarea sa reprezintă un act de ecologizare a cascadei.
- **Logica Cascadei**: Lăsând `h5` complet curat la început, browserul desenează o ierarhie aerisită. Cunoașterea curge lin în jos: textul se naște cu dimensiunea corectă și text natural; când cascada ajunge la Modulul 11, selectorul specific se activează și injectează culoarea albastru electric stelar (`--starlight-blue`) și linia punctată discretă strict pe componentele din anexe, salvând restul flotei de la poluare estetică.

• Selectorul `<p>` (Scutul de Neutralitate / Paragrafele Generale)

- **Motivul Ontologic**: În designul de înaltă precizie, spațiul alb este la fel de valoros ca materia codului. Un paragraf general nu trebuie să presupună că deține o marjă inferioară, deoarece poate fi integrat într-un panou HUD sau într-o celulă de date unde alinierea axială este milimetrică. Neutralitatea la nivel genetic garantează libertate totală la nivel de componentă.
- **Logica Cascadei**: Declarat ca selector de tag curat în Modulul 03, `p` stabilește că textul nu generează de la sine forțe de respingere. Cunoașterea curge controlat în jos: când paragraful face parte din textul narativ al jurnalului, Modulul 11 intervine local și injectează distanțarea de lectură prin `.log-entry p { margin-bottom: 1.5rem; }`, lăsând în același timp elementele HUD din navbar sau tabelele SQL perfect imune la colaps spațial.

• Selectorul `<p code>`

- **Motivul Ontologic**: În timpul lecturii jurnalului, mintea echipajului navighează prin două straturi de realitate: narațiunea literară și instrucțiunile tehnice de mașină. Rozul-magenta aplicat pe aceste micro-taguri inline acționează ca un indicator de înaltă tensiune, avertizând operatorul că acel cuvânt nu este literatură, ci o comandă hardware executabilă.
- **Logica Cascadei**: Acest selector folosește o relație de descendență (`p code`). El este mai specific decât un selector simplu de tag (`code`). Amplasarea sa la finalul Modulului 03 asigură că textul din interiorul paragrafelor va primi această alertă roz, în timp ce marile ecrane radar de cod (`pre code`) vor rămâne intacte, afișând textul verde fosforic pe fundal închis, fără coliziuni stilistice.

• Selector `<hr>`

- **Motivul Ontologic**: Pe o navă spațială, capitolele nu se termină pur și simplu; ele sunt separate prin porți de siguranță sau bariere de vid. Gradientul care dispare spre margini mimează o rază laser concentrică ce a străpuns structura metalică a paginii, oferind o tranziție dramatică și curată între dimensiunile cunoașterii frontend.
- **Logica Cascadei**: Fiind un tag structural curat, plasarea sa la finalul ierarhiei tipografice din Modulul 03 este perfectă. El curăță comportamentul nativ al browserului și impune această barieră laser peste tot, asigurându-se că nicio zi din jurnal sau tabel SQL nu se va lipi direct de elementele vecine, stabilizând layout-ul pe verticală.

🌟 9. De ce urmează Blocurile de Cadraj Mare în Modulul 04?

După ce cascada a stabilit regulile microscopice (:root, universal reset) și ierarhiile tipografice de bază (Modulul 03), ea trece în mod logic la **Modulul 04: Core Containers & Headers**. Această secțiune se ocupă de encapsularea fizică a volumelor de text și de comportamentul vizual al marilor antete de pagină.

• Selectorul Grupat `.category-header, .footer, .main-container > h2` (Alinierea Simetrică)

- **De ce-ul poziției**: În ordinea cascadei, regulile de aliniere și limitare a lățimii macro-containerelor trebuie declarate înainte de a stiliza elementele de detaliu din interiorul lor. Acest selector este grupat pentru a impune o lege simetrică unificată peste trei zone complet diferite ale flotei.

- **Efectul în cascadă**: Impune o armătură laterală rigidă (`padding-left: 40px`, `padding-right: 40px`) și un scut anti-lăbărțare de înaltă rezoluție (`max-width: 1200px`). Acest lucru garantează că indiferent cât de mare este monitorul hardware pe care rulează aplicația, conținutul nu se va deforma și nu se va lipi de marginile ecranului, păstrând o zonă de siguranță geometrică.

• Selectorul `.category-header` (Antetul de Secțiune Macro)

- **De ce-ul poziției**: Se așază imediat sub selectorul grupat, acționând ca o specificare locală. El izolează doar zona superioară a paginilor (Index, Jurnale).
- **Efectul în cascadă**: Definește camera de aer superioară a capitolului (`padding-top: 40px`, `padding-bottom: 20px`) și ordonă alinierea centrată a tuturor textelor din cabină (`text-transform: center`).

• Selectorul `.category-header h2` (Animația Cinematică de Antet)

- **De ce-ul poziției**: Folosește un selector combinator de descendență. El stă la finalul acestui modul deoarece aplică o corecție estetică de mare precizie unui singur element îngropat în antet.
- **Efectul în cascadă**: Moștenește culoarea roz neon stabilită global în Modulul 03, dar execută o ajustare fină: reduce spațierea literelor la `2px` pentru un aspect mai compact de monitor de bord și rulează motorul de animație recursivă `neon-pulse-pink`, făcând ca titlul să pulseze ciclic în vidul digital.

🌟 10. Sub-modulul 05.1 (Bara Superioară Fixă): `.navbar` și `.navbar--hidden`

**REZUMAT**: Acest modul proiectează puntea principală de interacțiune și navigație a flotei. El consolidează panoul de control fix superior (Cockpit-ul HUD) și consolele de orientare asimetrice (Harta din Sidebar). Modulul utilizează tranziții cinematice bazate pe fizica accelerației reale (`cubic-bezier`), măști de sticlă acrilică cu filtrare optică (`backdrop-filter`) și rețele electrice de fire laser pentru a oferi echipajului un răspuns tactil și vizual instantaneu în timpul explorării.

• Selectorul `.navbar` (Bara Superioară Fixă / Main HUD Cockpit)

- **Motivul Ontologic**: Navbar-ul este consola de comandă centrală a Nostromo-ului tău. Ea trebuie să plutească spectral deasupra textului narativ (`z-index: 1000`), oferind o prezență tehnologică constantă, dar topindu-se ambiental în vid prin blur-ul cinematic pentru a nu perturba lectura.
- **Logica Cascadei**: Fiind o componentă HUD majoră, se așază la deschiderea Modulului 05, imediat sub regulile macro de conținut. Ea moștenește resetarea universală `box-sizing: border-box` declarată în Modulul 02, ceea ce garantează că padding-ul lateral de `40px` nu va umfla sau deforma lățimea de `100%` a carcasei pe ecrane de desktop.

• Selectorul `.navbar--hidden` (Clasa Automată de Ascundere)

- **Rolul în context**: Targetează starea dinamică a barei de navigație, injectată chirurgical prin intermediul senzorilor din `script.js`.
- **Misiune**: Împinge fizic întreaga consolă pe verticală în afara spațiului vizibil al ecranului hardware (`transform: translateY(-100%)`) în momentul în care nava accelerează prin scroll descendent.
- **Motivul Ontologic**: Camuflajul structural reprezintă adaptabilitatea interfeței la nevoile umane. Când echipajul plonjează adânc în textul narativ, consola se retrage în mod discret în tavanul virtual pentru a elibera spațiul mental de explorare, revenind instantaneu la o simplă decelerare prin scroll în sus.
- **Logica Cascadei**: Stă imediat sub `.navbar`. Fiind o clasă dinamică combinată, are o specificitate precisă: nu rescrie proprietățile de fundal sau dimensiuni, ci aplică doar vectorul de deplasare pe axa Y, profitând de harta cubic-bezier configurată pe părinte pentru a executa saltul fluid.

🌟 11. Sub-modulul 05.2 (Identitatea și Portalurile): `.logo`, `.logo a`, `.logo a:hover`

• Selectorul `.logo` și `.logo a` (Identitatea Vizuală a Navei / Core Logo)

- **Motivul Ontologic**: Logo-ul este farul energetic al miniflotei tale. El nu trebuie să rămână un text inert; pulsația sa ciclică și fluidă demonstrează că inima reactorului central funcționează optim, oferind în același timp un contrast cromatic superb cu restul panoului întunecat.
- **Logica Cascadei**: Acest sub-modul izolează pilonul de brand înainte de a trece la rețeaua de butoane. Includerea liniei `font-family: var(--font-main)` pe elementul ancoră (`.logo a`) este o mișcare de siguranță chirurgicală: ea forțează browserul să spargă imunitatea nativă a link-urilor și să aplice rigiditatea geometrică a fontului Space Grotesk, asortându-se perfect cu restul consolei HUD.

• Selectorul `.logo a:hover` (Suprapunerea de Energie Kinetică pe Brand / Proximity Proximity Flash)

- **Motivul Ontologic**: Într-o interfață HUD avansată, logo-ul nu este o ștampilă statică, ci un nod vital de rețea. Reacția sa luminoasă violentă la hover servește ca o confirmare hardware absolută pentru utilizator că acea zonă reprezintă un portal activ de reîncărcare, gata să execute teleportarea înapoi pe Puntea de Comandă.
- **Logica Cascadei**: În conformitate cu legile stabilite în Modulul 03 pentru titlurile mari, pseudo-clasele de interacțiune (`:hover`) trebuie plasate imediat sub selectorul lor părinte structural (`.logo a`). Acest lucru permite browserului să calculeze instantaneu diferența de tensiune luminoasă (de la pulsația latentă la explozia de neon) fără decalaje sau rateuri de randare în interiorul cockpit-ului fix.

🌟 12. Sub-modulul 05.3 REȚEAUA TERMINALS & FIRELE LASER EXTENSIBILE

• MOTIVUL ONTOLOGIC (De ce există această rețea în vid?)

În ontologia spațiului cibernetic din universul _Solaris_, interfața nu este un simplu instrument pasiv, ci un **câmp de forțe reactive**. Rețeaua de link-uri `.nav-links` nu reprezintă simple cuvinte pe un ecran, ci **coordonate de teleportare/portaluri active** către alte straturi ale realității frontend.

- **Text-Shadow și Pulsul de Neon la Hover (`var(--nebula-pink)`)**: Atunci când cursorul (voința utilizatorului) intersectează textul, aprinderea bruscă în roz de alertă și generarea aurei difuze de `text-shadow` demonstrează o „descărcare de tensiune energetică”. Interfața confirmă că portalul a fost alimentat electric și este gata de execuție.
- **Mecanica Firului Laser Virtual (`::after`)**: Linia microscopică de `1px` situată la coordonata `bottom: 0` este materializarea vizuală a unui canal deschis. Faptul că se naște din nimic (`width: 0`) și se depliază fluid până la `100%` prin curba cinematică simulează o punte laser care securizează pasul utilizatorului.
- **Identitatea Stării Active (`.active`)**: Când nava se află fizic pe o anumită pagină, culoarea se stabilizează pe verde-mentă fosforic (`--solar-mint`), iar firul laser de dedesubt rămâne permanent extins. Această transformare cromatică reprezintă un far stabil de orientare: într-un ocean cosmic infinit, echipajul are nevoie de o ancoră vizuală permanentă pentru a ști în ce punct al matricei se află localizat.

• LOGICA CASCADEI (De ce stau aceste reguli exact în acest punct?)

Amplasarea acestor reguli (liniile 352-409) respectă cu sfințenie principiul **Specificității Progresive** și al **Cronologiei de Execuție** în CSS:

- **De la Container la Componentă (`.nav-links` -> `a`)**: Mai întâi, cascada configurează containerul structural (`.nav-links`), curățând gloanțele listei și aliniind elementele în Flexbox. Doar după ce această „cameră de control” orizontală este fixată pe desktop, cascada coboară în interiorul ei pentru a formata elementele interactive individuale (`.nav-links a`).
- **Relația de Subordonare a Pseudo-elementelor (`a::after`)**: În CSS, un pseudo-element se poate poziționa absolut doar dacă părintele său are o proprietate de poziționare declarată. Prin urmare, regula `position: relative;` de pe `.nav-links a` este fundamentul care permite liniei virtuale `::after` să stea perfect lipită la `bottom: 0`. Dacă am fi inversat ordinea sau dacă am fi plasat regulile în module dezorganizate, linia laser ar fi colapsat în tavanul ecranului (la rădăcina HTML), rupându-se de text.
- **Ordinea Interacțiunii și Suprascrierii (`:hover` înainte de `.active`)**: Regulile dinamice de hover sunt plasate deasupra stării active. Acest lucru permite browserului să ruleze animația laser pe link-urile standard, dar în momentul în care o pagină devine cu adevărat activă, clasa `.active` (situată mai jos în fișier) deține o greutate mai mare în cascadă și forțează linia să își schimbe culoarea din roz în verde-mentă solid, blocând comportamentul de hover și stabilizând elementul.
- **Scutul Defensiv Final (`.return-btn`)**: Plasarea butonului discret de întoarcere la sfârșitul rețelei este un act de izolare chirurgicală. Prin intermediul etichetei `.return-btn::after { display: none !important; }`, cascada execută o comandă de anihilare selectivă: ea găsește pseudo-elementul definit mai sus și îl șterge _doar_ pentru acest buton, lăsând restul rețelei de link-uri intactă și protejată.

🌟 13. Sub-Modulul 05.4 (The Command Console Core / Consola și Harta din Sidebar)

• MOTIVUL ONTOLOGIC (De ce există această consolă în vid?)

În topografia odiseei noastre, dacă bara superioară (`.navbar`) reprezintă parbrizul holografic exterior al cockpit-ului, consola laterală stângă (`.log-sidebar`) este **computerul intern de telemetrie și orientare axială**. Echipajul nu poate naviga eficient prin „Oceanele Mercuriale ale HTML-ului” sau prin „Void-ul SQL” fără un instrument care să îi localizeze permanent coordonatele.

- **Efectul Cinematic de Scanline la Hover (`padding-left: 15px`)**: Atunci când operatorul atinge un element inactiv din listă, glisarea fizică a textului spre dreapta nu este o simplă animație ornamentală. Ea mimează un **fascicul de scanare electronică (Scanline Beam)** care verifică și luminează în verde fosforic (`--solar-mint`) o nouă traiectorie, demonstrând că ruta este deschisă și calculată de computerul de bord.
- **Solidificarea Scutului Activ (`.sidebar-nav a.active`)**: În momentul în care nava a aterizat într-un sector (utilizatorul citește o anumită zi), interfața rulează un protocol de stabilizare. Textul abandonează frecvența verde de scanare și se aprinde în roz de alertă militară (`--nebula-pink`), în timp ce marginea invizibilă se convertește într-o **barieră solidă laser roz** (`border-left`). Această ancorare cromatică intensă acționează ca un scut de siguranță: ea fixează atenția cititorului și îi confirmă în mod absolut unde se află în interiorul flotei.
- **Ancora Supremă a Hărții (`.map-title-link h4`)**: Titlul hărții (`HTML Expedition Map`) reprezintă **Punctul Zero de Reîncărcare a Sectorului**. În repaus, el emite o pulsație verde analogică discretă peste o linie punctată, dar la atingere explodează într-o coroană plasmatică de `12px` prin proprietatea `text-shadow`. Acest răspuns violent avertizează echipajul că se află în contact cu nodul master care coordonează întreaga rețea de sub-module din stânga.

• LOGICA CASCADEI (De ce stau aceste reguli exact în acest punct?)

Amplasarea selectorilor din Sub-Modulul 05.4 este o lecție magistrală de **Specificitate Progresivă Curată**, demonstrând cum o verticalitate corectă în CSS elimină nevoia de forțări structurale:

- **De la Scutul Macro la Elementele Micro**: Cascada respectă o curgere arhitecturală firească. Mai întâi configurează structura fizică a containerului lateral (`.log-sidebar`), aplicându-i masca de sticlă și blur-ul cinematic. Abia după ce această porțiune de carcasă a fost fixată pe desktop, codul coboară în interiorul ei pentru a formata listele (`ul`, `li`) și titlurile de capitole (`.sidebar-nav h4`), stabilind o pernă stabilă de aer de `20px` dedesubt.
- **Suprascrierea Nativă fără Directive Violente**: În codul refactorizat, stările de repaus (`.sidebar-nav a`), hover (`:hover`) și activ (`.active`) sunt așezate într-o ordine strict cronologică. Deoarece au specificități matematice echivalente în browser, așezarea clasei `.active` **mai jos** în fișier decât regula de hover îi permite acesteia să execute o **suprascriere genetică totală și curată**. Când o zi devine activă, ea taie de la sine culoarea verde și padding-ul de tranzit de deasupra, blocându-le în roz de alertă, fără a mai fi nevoie să „inflamăm” codul cu directive agresive de tip `!important`.
- **Ancorarea și Protecția Elementelor Block (`.map-title-link`)**: Declararea regulilor `display: block;` și `width: 100%;` direct pe selectorul master `.map-title-link` este așezată strategic înaintea formatării textului din interior (`h4`). Această mișcare securizează layout-ul: ea forțează tagul `<a>` (care nativ este un element inline ce se strânge pe text) să se deschidă ca o membrană pe toată lățimea utilă a coloanei din nav-ul stâng. Astfel, când browserul coboară la linia următoare (`.map-title-link h4`), linia sa punctată de la bază (`border-bottom`) se va întinde perfect pe tot ecranul sidebar-ului, asigurând o demarcație industrială impecabilă și imună la colaps spațial.

🌟 14. Module06: HERO MATRIX & KINETIC PORTAL SYSTEMS (ECRANUL PRINCIPAL)

- MOTIVUL ONTOLOGIC (De ce există elementele ecranului principal în vid?)

În ontologia spațiului nostru digital, Modulul 06 nu configurează o simplă pagină web, ci materializează **Puntea de Comandă Supremă a Nostromo-ului (The Space Command Deck)**. Este primul contact vizual al echipajului cu mașina, spațiul epistemic unde se inițializează călătoria prin cod.

- **Dimensiunea Monumentală a Containerului `.hero`**: Forțarea înălțimii minime la `100vh` (înălțime completă de ecran hardware) și lărgirea carcasei la `100vw !important` (lățime planetară absolută) reprezintă imersia totală în vid. Utilizatorul este deconectat de la realitatea exterioară browserului și absorbit în totalitate de interfața tehnică a reactorului.
- **Portalul Kinetic `.cta-button`**: Butonul de acces rapid nu este un simplu element utilitar, ci o **capsulă de teleportare activă**. În starea latentă, se camuflează în sticla întunecată a navei, respirând printr-o aură verde discretă. La atingere, declanșează o explozie de energie: fundalul devine o mască fosforică verde-mentă pură, textul devine negru-militar de înalt contrast, iar colțurile sunt învăluite într-o aureolă dublă de neon de înaltă densitate prin `box-shadow`. Acest răspuns cinetic violent confirmă echipajului că portalul a fost armat și este gata pentru saltul în hyper-spațiul codului.
- **Rasterul CRT Local `.hero::before`**: Generarea mascaților de linii de scanare de `4px` și coloane de sub-pixeli de `6px` aplicată strict peste fundalul secțiunii Hero are un rol profund. Ea distilează estetica anilor '80: textul și formele geometrice tridimensionale nu mai par desenate artificial pe o pânză web modernă, ci par proiectate fizic din interiorul unui tub catodic real, prin emisie fluorescentă de fosfor.

- LOGICA CASCADEI (De ce stau aceste reguli exact în acest punct?)

Amplasarea selectorilor în Modulul 06 urmează o logică ierarhică strictă, bazată pe trecerea de la legile macro-structurale la micro-ingineria de detaliu:

- **Ruptura Controlată a Plafonului Global (`.hero` la deschidere)**: În Modulul 04, am stabilit o regulă macro rigidă: toate containerele mari de pe navă sunt blocate la o lățime maximă defensivă de `1200px` pentru a proteja textul de lăbărțare. Cu toate acestea, Modulul 06 se deschide cu selectorul `.hero` care execută o **suprascriere militară de forță** prin `width: 100vw !important` și `max-width: 100vw !important`. Plasarea sa în acest punct este crucială: fiind scris mai jos în fișier și echipat cu directivă de urgență, el sfidează bariera de 1200px a celorlalte module, permițând ecranului de întâmpinare să se deschidă cinematic pe absolut toată suprafața ecranului hardware.
- **Poziționarea ca Rădăcină de Coordonate (`position: relative`)**: Regula `position: relative` fixată pe părintele `.hero` este fundamentul pe care se sprijină pseudo-elementul `.hero::before`. În ordinea interpretării CSS, browserul trebuie să valideze mai întâi contextul spațial al containerului real înainte de a-i putea calcula și atașa membrana virtuală.
- **Stratificarea Sub-textuală a Pseudo-elementului (`.hero::before`)**: Selectorul virtual stă așezat strategic sub formatarea textelor. Proprietatea `z-index: 1;` îl plasează la milimetru deasupra fundalului brut al navei, dar sub eticheta `<h1>` sau paragrafele din cockpit. Această așezare în cascadă garantează o lizibilitate maximă: masca CRT filtrează lumina din adâncuri, dar nu poluează claritatea literelor care plutesc la suprafață. De asemenea, directiva `pointer-events: none;` dezactivează corpul fizic al măștii, permițând cursorului mouse-ului să străpungă sticla CRT și să interacționeze direct cu link-urile și butoanele active de dedesubt, fără blocaje tactile.
- **Izolarea Portalului Kinetic (`.cta-button` la final)**: Selectorul butonului CTA încheie Modulul 06 în mod natural. El moștenește fontul geometric `var(--font-main)` injectat în `:root` în Modulul 01 și aplicat global pe `body` în Modulul 02, dar folosește un sistem Flexbox integrat local pentru umplutura internă de `15px 35px`. Stările sale de repaus și hover sunt legate consecutiv în cod pentru a permite hărților termice de tranziție cubic-bezier să ruleze fluid explozia fosforică la hover, anulând simultan structura de text-shadow anterioară pentru a proteja definiția perfectă a literelor pe fundalul luminat intens.

• Selectorii `.stenciled-metal-text` și `.stenciled-metal-text-sub` (Telegraful Master / The Hero Titles)

- **Motivul Ontologic**: Titlul suprem al expediției nu este un text editat digital modern, ci o transmisiune radio brută, decupată laser direct în oțelul navei Nostromo. Faptul că subtitlul (`.stenciled-metal-text-sub`) are o amânare (delay) de exact 3 secunde permite computerului de bord să își încarce mai întâi titlul roz master, declanșând ulterior curgerea datelor secunde pe frecvența desaturată de diagnostic.
- **Logica Cascadei**: Plasarea lor la finalul Modulului 06 respectă trecerea de la macro-containerul `.hero` la elementele interioare specifice de tip block-to-inline. Deoarece folosesc o bordură din dreapta (`border-right`) ca și cursor mecanic, ele moștenesc automat animația `blink` definită în inima sistemelor de animații (Modulul 00.1), demonstrând corelația perfectă a flotei fără a aglomera fișierul.

🌟 15. MODULE 07: Panoul de capitole

- MOTIVUL ONTOLOGIC (De ce există panoul de capitole în vid?) In topografia odiseei noastre virtuale, dacă ecranul Hero (Modulul 06) este poarta de intrare pe navă, Modulul 07 reprezintă **Harta Marilor Continente ale Cunoașterii (The Category Quantum Grid)**. Este spațiul epistemic în care echipajul își alege vectorul de zbor (HTML, CSS sau SQL) pentru a explora materia întunecată a frontend-ului.
  - **Lumina Albastru-Stelar a Portalurilor (`--starlight-blue`)**: Alegerea acestei nuanțe specifice pentru stările de hover nu este una pur cosmetică. În codul cromatic al cockpit-ului, verdele-mentă indică telemetria stabilă a instrumentelor de bord, în timp ce albastrul-electric stelar reprezintă **Frecvența de Căutare și Scanare Activă**. Aprinderea bruscă a cardului și a butoanelor sub această radiație indică faptul că portalul respectiv a fost validat prin atingere și este gata de propulsie.
  - **Levitația Kinetică a Cardurilor (`translateY(-8px)`)**: În vidul cosmic din universul _Solaris_, obiectele nu sunt ancorate pe suprafețe inerte, terestre. Ridicarea bruscă a capsulei de sticlă cu 8px la trecerea cursorului simulează o eliberare din câmpul gravitațional. Cardul pare că plutește în fața ochilor utilizatorului, desprinzându-se de restul carcasei pentru a deveni un obiect tridimensional interactiv tranzitat de energie.
  - **Sinteza de Sticlă _Solaris_ (`.category-card`)**: Utilizarea panourilor de tip capsulă din sticlă fumurie semi-transparentă cu blur cinematic extins de `15px` oferă adâncime operativă cockpit-ului. Sub-modulele nu par lipite artificial pe ecran, ci par a fi panouri fizice din sticlă acrilică securizată, încastrate direct în vidul întunecat al carcasei metalice a navei Nostromo.

- LOGICA CASCADEI (De ce stau aceste reguli exact în acest punct?)
  Ordinea de curgere a selectorilor în Modulul 08 este guvernată de legea **Specificității Progresive Extrinseci**, deplasându-se de la constrângerile geometrice globale de spațiu la micro-mecanica internă a butoanelor de acces:
  - **Protecția Corectă a Anchorului Suprem (`.main-container`)**: Acest selector grupează prima linie defensivă și stă în deschiderea modulului. Rolul său în cascadă este de a impune plafonul de lățime maximă de `1200px` direct peste grila de dedesubt. Browserul trebuie să citească și să execute acest cadraj exterior rigid înainte de a-i permite motorului Grid să deseneze celulele, garantând că rețeaua de carduri nu va evada și nu se va deforma pe monitoarele ultra-wide.
  - **Auto-Responsivitatea fără Forțări de Mobil (`.category-grid`)**: Plasarea formulei `repeat(auto-fit, minmax(300px, 1fr))` pe containerul secundar este o victorie didactică majoră. În loc să aglomerăm fișierul mai jos cu interogări media complexe (`@media`) care să modifice lățimile pe telefoanele mobile, cascada stabilește o **lege genetică adaptivă** direct pe grilă. Când ecranul hardware se micșorează sub `300px` pentru o celulă, browserul execută o repliere nativă pe verticală, curățând codul de directive redundante.
  - **Ancorarea Locală a Capsulei (`position: relative` pe `.category-card`)**: Proprietatea `position: relative` este plasată strategic pe cardul individual. Ea nu modifică poziția cutiei, ci deschide o „rădăcină locală de coordonate” pentru butoanele și eventualele micro-etichete tehnice din interior, asigurându-se că elementele interioare rămân prizoniere în granițele sticlei și nu colapsează în tavanul ecranului.
  - **Mecanica de Simetrie Verticală a Subsolului (`flex-grow: 1` pe paragrafe)**: Aceasta este cea mai subtilă și spectaculoasă mișcare în cascadă din interiorul cardului. Întrucât textul narativ al descrierilor are lungimi complet diferite (HTML are trei rânduri, iar SQL poate avea un singur rând lung), butoanele de dedesubt ar fi stat decalate pe orizontală, stricând ordinea industrială a flotei. Injectarea directivei `flex-grow: 1` pe tagul `p` obligă browserul să transforme paragraful într-o membrană elastică: acesta se umflă automat și consumă tot spațiul vertical rămas liber în card, împingând fizic butonul `.btn` fix la baza capsulei, aliniind toate butoanele pe o singură linie orizontală impecabilă pe toate cele 3 coloane!
  - **Izolarea Butonului și Inversarea Cromatică la Hover (`.category-card .btn:hover`)**: Selectorul butonului încheie Modulul 08, acționând ca o componentă granulară cu specificitate înaltă. Prin regula `align-self: flex-start`, el refuză să moștenească lățimea de bloc a cardului și se strânge elegant pe textul său. Stările de hover sunt plasate imediat sub repaus pentru a permite hărților de tranziție electronică să execute fluid inversarea cromatică (fundalul devine albastru solid, iar textul se stinge în negru militar profund), anulând simultan structura de text-shadow anterioară pentru a oferi o claritate totală a literelor pe placa aprinsă.

🌟 16. MODULE 08: AIRLOCK SECTORS & CONTENT VAULTS (PROFILUL DE JURNAL)

Acest modul mută atenția de pe ecranul principal pe structura internă a paginilor de jurnal, organizând transmisiile narative și datele tehnice în compartimente securizate.

• Selectorul `.log-layout` (Matricea Macro de Jurnal)

- **Motivul Ontologic**: Înghețarea spațiului pe orizontală creează ordinea militară necesară parcurgerii datelor textuale.
- **Logica Cascadei**: Deschide Modulul 09 pentru a oferi un înveliș protector peste toate componentele interne.

• Selectorul `.sector-announcement` (Porțile Airlock Violet)

- **Motivul Ontologic**: Capitolele nu sunt simple texte, ci camere etanșe (Airlocks). Chenarul dublu violet simbolizează un scut de siguranță activat la trecerea dintr-un sector în altul.
- **Logica Cascadei**: Declarat înaintea textelor interne, oferă coordonatele relative (`position: relative`) necesare pentru alinierea micro-etichetelor din subordine.

• Selectorul `.sector-announcement span` și `h2` (Etichetele Porții)

- **Motivul Ontologic**: Chihlimbarul este nuanța alertelor latente. Anunțarea numărului de sector cu această culoare avertizează operatorul că urmează descărcarea unei noi baze de date.
- **Logica Cascadei**: Specificațiile locale de pe `h2` taie nativ moștenirea globală roz, lăsând poarta curată și adaptată cromatic contextului de capitol.

• Selectorul `.mission-status` (Panoul de Control al Stării)

- **Motivul Ontologic**: Mimează ecranul mic secundar de diagnosticare de pe bord, care confirmă permanent starea sistemelor.
- **Logica Cascadei**: Stă deasupra log-textului, izolând zona de metadate de narațiunea fluidă ce urmează dedesubt.

• Selectorul `.mission-status p` (Telegraful Fosforic Unificat)

- **Motivul Ontologic**: Reprezintă conexiunea directă om-mașină. Stingerea automată a cursorului la finalul textului indică finalizarea cu succes a transmisiunii.
- **Logica Cascadei**: Clasa folosește `width: max-content` pentru a trage cursorul lipit de ultimul caracter scris, controlând la milimetru layout-ul dinamic.

• Selectorul `.log-text` și `.log-text p:first-of-type::first-letter` (Motorul Narativ și Drop-Cap-ul)

- **Motivul Ontologic**: Îmbinarea dintre asprimea codului și eleganța literară. Drop-cap-ul roz introduce cititorul în atmosfera narativă a cronicii, amintind de manuscrisele vechi reinterpretate în cheie cyberpunk.
- **Logica Cascadei**: Fiind reguli de tag imbricate, ele guvernează fluid corpul textului fără a polua tabelele sau zonele de navigare HUD.

• Selectorul `.log-entry` și `.log-entry p` (Caseta Monitor a Zilei)

- **Motivul Ontologic**: Fiecare zi este un sub-terminal independent încapsulat în siguranță în structura metalică a navei.
- **Logica Cascadei**: Poziționarea sa centralizează regulile. Paragrafele din interior primesc automat o nuanță desaturată stardust și reguli rigide de auto-despărțire în silabe (`hyphens: auto`) pentru a împiedica link-urile lungi să spargă layout-ul.

• Selectorii Componentelor Semantice (`.semantic-module`, `.tag-name`, `.tag-meta`, `.tag-description`)

- **Motivul Ontologic**: Reprezintă glosarul tehnic al misiunii. Termenii cheie de cod sunt decupați laser din fluxul narațiunii, primind o identitate energetică superioară pentru scanarea cognitivă rapidă.
- **Logica Cascadei**: Situați la finalul Modulului 09, acești selectori acționează ca micro-suprascrieri de clasă, adăugând straturi estetice de înaltă precizie exact acolo unde textul devine pur didactic.

• SECTOR ROUTING: Decontaminarea Componentelor `.log-text`

- **Observație de Bord**: Paragrafele de jurnal `.log-text` și Letrina inițială `::first-letter` au fost extrase din granițele Modulului 09.
- **Destinația în Cascadă**: Locul lor de drept este în **Modulul 11 (The Log Chronicles)**. Mutarea și fuzionarea lor acolo anihilează duplicarea masivă de cod depistată la paginile 32 și 41 din fișierul vechi, asigurând o singură componentă curată, stabilă și reutilizabilă pe toate punțile flotei.

🌟 17. MODULE 09: Consola terminalului de notițe

• **MOTIVUL ONTOLOGIC (De ce există consola de hacking în vid?)**

În ontologia cibernetică a universului _Solaris_, interfața nu este un simplu instrument de editare textuală, ci un **seif digital de izolare (The Note Terminal Vault)**. Notițele pe care echipajul le introduce nu sunt stocate într-o aplicație clasică din cloud, ci sunt „gravate” direct în memoria volatilă a unui terminal catodic analogic, izolat în pântecul metalic al navei Nostromo.

- **Negrul Oarb al Ecranului (`#05070a`)**: Alegerea acestui fundal specific, mai întunecat decât restul paginii, simulează stingerea luminilor ambientale în cabina de pilotaj. Monitorul absoarbe lumina camerei, forțând operatorul să plonjeze într-o stare de concentrare profundă, unde singura realitate care pulsează este energia verde-mentă a caracterelor.
- **Raza Laser de Măturare Continuă (`::before`)**: Linia subțire de `3px` care rulează la infinit de sus în jos (`laser-scan`) nu este un simplu element decorativ retro-SF. Ea reprezintă **Frecvența de Refresh și Ecranare de Înaltă Tensiune (The Trawler Scan Light)**. Ea demonstrează că monitorul este online, re-calibrează constant emisia de fosfor și protejează datele de bruiajele electromagnetice din exteriorul navei.
- **Eticheta Spectrală de Diagnostic (`::after`)**: Mesajul `"SYS_STATUS: READY_TO_WRITE //"` plasat în subsol acționează ca un ecou al sistemului de operare. Faptul că are o opacitate minimă de 25% verde-mentă arată că este o interfață vie, pregătită să preia fluxul conștiinței operatorului, transformând o zonă inestetică de layout într-un detaliu tehnic militar autentic.
- **Rigiditatea Monolitică a Textarea-ului (`resize: none`)**: În designul HUD industrial, elementele sunt fixe, nituite în consola de fier a bordului. Interzicerea modificării manuale a dimensiunii casetei demonstrează că utilizatorul se supune regulilor fizice rigide ale mașinii. Textul scris cu fontul fix mecanic `Courier New` luminează direct pe frecvența verde-mentă fosforică, sugerând că fiecare caracter tastat consumă tensiune din reactorul central.
- **Inversarea Cromatică de Salvare (`.save-btn:hover`)**: Când butonul este validat prin hover, trecerea sa instantanee de la starea de alertă latentă (chenar roz) la o explozie de neon (fundal aprins, umbră dublă interioară/exterioară) reprezintă **Armarea și Transmisia Semnalului (The Save Signal Execution)**. Interfața oferă un răspuns tactil și cromatic violent pentru a asigura operatorul că transmisia a fost securizată și salvată în siguranță în arhivele sferice.

• **LOGICA CASCADEI** (De ce stau aceste reguli exact în acest punct?)

Amplasarea selectorilor în Modulul 10 urmează principiul **Specificității Progresive și al Contextualizării Componentelor**, demonstrând cum straturile virtuale conlucrează impecabil deasupra elementelor interactive reale:

- **Rădăcina Spațială Locală (`position: relative` pe `.note-terminal`)**: Acest selector macro deschide Modulul 10. Declararea proprietății `position: relative` este mutarea genetică obligatorie. Fără ea, cele două pseudo-elemente (`::before` pentru laser și `::after` pentru status text) nu ar fi putut levita prizoniere în granițele casetei metalice, ci ar fi evadat din monitor și s-ar fi ancorat haotic la nivelul general al ecranului hardware (HTML/Body).
- **Imunitatea Tactilă a Straturilor Virtuale (`pointer-events: none`)**: Atât pe linia laser de scanare (`::before`), cât și pe textul de diagnostic (`::after`), sa aplicat directiva de aur `pointer-events: none`. În ordinea randării în browser, aceste elemente au un `z-index` înalt, adică plutesc fizic _deasupra_ casetei textarea în care scrie utilizatorul. Dacă am fi omis această directivă, masca laser ar fi blocat mouse-ul: operatorul ar fi dat click pe linia laser în loc să poată da click în interiorul textarea-ului pentru a scrie, gripând întreaga consolă! Directiva le transformă în proiecții pur spectrale prin care mouse-ul trece liber.
- **Purificarea Casetelor de Focus (`outline: none` pe textarea)**: Browserul vine din fabrică cu o regulă parazită: când dai click într-o casetă, îi pune o bordură groasă albastră sau neagră (focus ring). Declararea lui `outline: none` în acest punct specific al cascadei execută un ordin de anihilare selectivă: ea șterge amprenta browserului terestru chiar în momentul interacțiunii, permițând literelor tale verzi să rămână perfect lipite de chenarul micro-fin original de 20% opacitate, păstrând unitatea cromatică a mașinii.
- **Izolarea Butonului prin Combinare de Clase (`.note-terminal button, .save-btn`)**: Acest selector este plasat spre finalul modulului, având o specificitate crescută. El folosește un padding dreptunghiular calibrat (`8px 22px`) și o marjă superioară de `10px` pentru a asigura o perne de aer stabilă sub textarea. Stările sale de hover sunt legate imediat sub repaus pentru a permite hărților de tranziție cubic-bezier să ruleze fluid inversarea cromatică și să injecteze acea umbră interioară și exterioară de neon roz (`box-shadow`), adăugând simultan un `text-shadow` care luminează textul capitalizat doar pe perioada atingerii, restabilind lizibilitatea pe placa aprinsă.
- **Subordonarea Anexelor (`.appendix-list` la final)**: Listele tehnice încheie Modulul 10 în mod natural. Ele sunt elemente satelit ale terminalului, de aceea sunt așezate la coada ierarhiei. Prin aplicarea unei indentări fixe de `20px` la stânga și a unui `margin-bottom: 8px` pe elementele `li`, cascada garantează că notele secundare se vor naște perfect aliniate și aerisite pe verticală, evitând colapsul vizual în momentul în care utilizatorul derulează jurnalul.

🌟 18. MODULE 10

**SUB-MODULE 10.1: THE JOURNAL FOUNDATIONS (NARAȚIUNEA ȘI LETTERING-UL)**

**REZUMAT / SUMMARY**: This sub-module establishes the genetic text engine for the flight logs. It normalizes paragraph text flow for high-contrast dark reading grids and implements the historical pink drop-cap on opening characters to define visual entry protocols.

• **Selectorul `.log-text` (Zona Textului Narativ General)**

- **Motivul Ontologic**: În ontologia interfeței flotei tale, textul narativ reprezintă **Memoria Vie a Expediției**. Într-un mediu dominat de rigiditatea laserelor, a metalului întunecat și a geometriei pure a codului, fluxul de cuvinte justificat simetric oferă o ancoră umană. Alinierea compactă stânga-dreapta și spațierea verticală generoasă (`1.8`) transformă lectura jurnalului tehnic dintr-o simplă rulare de date reci într-o experiență filosofică fluidă și stabilă, reflectând ordinea și disciplina de la bord.
- **Logica Cascadei**: Plasarea sa la absolut începutul Modulului 11 stabilește „Constituția Genetică” a textului din jurnale. Fiind un selector de clasă general, el nu modifică structura cutiilor (layout-ul), ci formatează strict estetica curgerii literelor. Așezarea lui în acest punct strategic asigură browserul că toate paragrafele interioare vor moșteni acest ritm de citire aerisit, permițând sub-modulelor specifice de dedesubt (cum este letrina pseudo-element `::first-letter` sau modulele semantice `.semantic-module`) să introducă excepții locale dramatice de culoare roz-neon sau dimensiuni mari, fără a destabiliza sau sparge baza de date tipografică generală a jurnalului.

• **Selectorul Pseudo-Element `.log-text > p:first-of-type::first-letter` (Ștampila Monolit Jet-Age)**

- **Motivul Ontologic**: Înlătură definitiv estetica romantică de carte de povești. Prima literă devine un bloc hardware proeminent, un comutator sau o tastă încastrată în tabloul de oțel al navei care semnalizează: „Transmisiune Online”.
- **Logica Cascadei**: Selectorul combinat de copil direct `> p` garantează că această capsulă industrială se va randa o singură dată la începutul textului, lăsând paragrafele interioare din modulele semantice perfect imune la decorări parazite.

**SUB-MODULE 10.2: THE CHRONICLE VAULTS (CAPSULELE DE JURNAL & ETICHETE)**

După izolarea elementelor macro de narațiune simplă și a glifului monolit din deschidere (Sub-Modulul 10.1), cascada avansează în profunzimea jurnalelor pentru a structura **mecanica vizuală a casetei de zi și cronicile de taguri**. Acest sector optimizează ierarhia elementelor interactive, garantând o citire fluidă și protejând layout-ul de erori de revărsare pe rezoluții strâmte.

• **Selectorul `.log-entry` (Caseta Jurnalului de Zi / The Entry Screen Vault)**

- **Motivul Ontologic**: Reprezintă un seif digital izolat. Jurnalele nu plutesc libere în vid, ci sunt reținute în capsule hardware ranforsate. Umbra interioară (`inset box-shadow`) sugerează adâncimea fizică a unui ecran vechi bombat, transmițând operatorului sentimentul de securitate și izolare ermetică a datelor stocate.
- **Logica Cascadei**: Deschide sub-modulul ca o componentă majoră de tip bloc. Ea stabilește contextul spațial local (`position: relative`) pentru a ține prizonieri toți selectorii copii interni (titlurile, paragrafele, modulele semantice) și le transmite prin moștenire regulile termice de tranziție cinematică.

• **Selectorul `.log-entry:hover` (Suprasarcina Kinetică a Casetei)**

- **Motivul Ontologic**: Mimează încărcarea cu energie a unui ecran tactil analogic la atingere. Modulul reacționează organic la proximitatea utilizatorului, desprinzându-se ușor de carcasă ca un sertar magnetic, confirmând vizual că acel sector de date este gata pentru citire activă.
- **Logica Cascadei**: Așezat imediat sub repausul clasei `.log-entry`, folosește o curbă cinematică fluidă `cubic-bezier(0.4, 0, 0.2, 1)` moștenită de sus pentru a rula accelerarea pe ecran fără salturi rigide sau rateuri de randare.

• **Selectorul `.log-entry p` (Paragrafele Interioare din Jurnal)**

- **Motivul Ontologic**: Textul tehnic secundar nu trebuie să concureze în intensibilitate cu marile titluri. Aspectul său desaturat și perfect aliniat reflectă disciplina militară de la bord.
- **Logica Cascadei**: Acest selector compus are o specificitate mai mare decât tagul global `p` definit în Modulul 03. El intervine local și rescrie dimensiunea și culoarea textului exclusiv în interiorul jurnalelor, lăsând paragrafele de pe restul paginilor complet intacte. Scutul de rupere automată a cuvintelor lungi (link-uri, comenzi) garantează că layout-ul capsulei nu se va lăbărța pe mobil.

• **Selectorul `.log-entry h3` (Alinierea Antetului de Zi / Symmetrical Header Track)**

- **Motivul Ontologic**: Întruchipează ordinea binară a aparatelor de măsură analogice. Ziua curentă (semnalul de alarmă roz) este separată fizic prin vid orizontal de datele tehnice ale misiunii, oferind o scanare vizuală instantanee operatorului.
- **Logica Cascadei**: Folosește o lățime de `100%` pentru a acoperi complet tavanul capsulei. El suprascrie proprietățile generale ale tagului `h3` din Modulul 03 (unde era doar text simplu roz) și adaugă comportamentul flexibil pe linie orizontală, acționând ca o bară tehnică rigidă.

• **Selectorul `.semantic-module` (Caseta de Definiții Tehnice / Syntax Terminal)**

- **Motivul Ontologic**: Funcționează ca o „sub-pânză” de securitate. Când textul narativ se întrerupe pentru a livra o informație pur tehnică, linia laser roz avertizează operatorul că a intrat într-un nod structural de cod.
- **Logica Cascadei**: Se așază înaintea formatării elementelor interne de text. Ea acționează ca un container părinte local: toate tagurile din interiorul ei se vor alinia automat raportat la perna sa de aer de `15px` din stânga.

**Selectorul `.tag-name` (Numele Etichetei de Cod / The Syntax Core)**

- **Motivul Ontologic**: În inima unei stații spațiale software, tagurile HTML sunt **Cărămizile Atomice ale Structurii**. Ele nu pot rămâne stinse; ele trebuie să emită lumină intensă, ca niște valve electronice active care alimentează circuitul.
- **Logica Cascadei**: Acest selector de clasă simplu țintește direct nodurile inline din interiorul modulului semantic. El rupe monotonia textului de zi și își injectează aura fosforică, dominând vizual zona de diagnostic.

• **Selectorul `.tag-meta` (Metadatele Etichetei / Diagnostic Scripts)**

- **Motivul Ontologic**: Reprezintă micro-telemetria de sistem. Atributele sunt parametri secundari ai mașinii, de aceea sunt comprimate tipografic, dar păstrate pe litere mari pentru a evoca rigoarea unui cod de eroare hardware.
- **Logica Cascadei**: Se așază în text ca un element inline imediat după

• **Selectorul `.tag-description` (Descrierea Extinsă a Tagului / Block Reset)**

- **Motivul Ontologic**: Întruchipează **Legea Separării Structurale a Cunoașterii**. În arhitectura datelor, definiția tehnică pură (antetul) nu trebuie să se amestece fizic pe aceeași linie cu exegeza narativă (descrierea). Prăbușirea forțată a blocului descriptiv dedesubt oferă minții un moment de respirație vizuală, marcând clar trecerea de la identificarea hardware a tagului la înțelegerea funcției sale filosofice în mașină.

- **Logica Cascadei**: **Aceasta este o directivă de urgență didactică critică.** Deoarece tag-name și tag-meta sunt elemente de tip inline (care tind să stea pe același rând), paragraful de descriere risca să fie deformat sau împins haotic în dreapta lor pe monitoarele mari. Injectarea lui `margin-top: 8px !important` execută un ordin dictatorial în cascadă: ea taie curgerea orizontală, prăbușește curat descrierea dedesubt și fixează o distanță geometrică perfectă, salvând simetria casetei din _Day 03_.

**SUB-MODULE 10.3: THE MATRIX REPOSITORIES (MATRICILE DE DATE CELULARE)**

După securizarea textului narativ (10.1) și a capsulelor de zi (10.2), cascada de stilizare pătrunde în infrastructura tabulară globală a flotei. Acest sector acționează ca o **Librărie Master reutilizabilă** pe toate paginile navetei spațiale, normalizând elementele de tabel și transformând listele inerte de date în radare rigide de citire de înaltă rezoluție.

• **Selectorul Grupat `table, .data-grid` (Structura Bazei de Date / The Solaris Database Grid)**

- **Motivul Ontologic**: Întruchipează **Ordinea Absolută a Informației**. În universul tău cyberpunk-industrial, datele brute nu pot pluti dezordonate în pagină; ele au nevoie de o plasă structurală rigidă de tip grid care să le clasifice, reflectând rigoarea matematică a computerului de bord.
- **Logica Cascadei**: Deschide sub-modulul ca selector principal grupat. Gruparea clasei cu tagul nativ rezolvă un conflict istoric de specificitate și previne duplicarea codului (Principiul DRY). Ea stabilește o huse metalică întunecată unică în memorie, permițând elementelor copii (`th`, `td`) să moștenească identitatea vizuală a flotei, lăsându-le doar sarcina de a randa micro-calibrările locale.

• **Selectorul `th` (Antetele de Coloană Hardware / Hardware Row Headers)**

- **Motivul Ontologic**: Funcționează ca **Plafonul de Validare al Coloanei**. Antetele de tabel indică operatorului _ce tip_ de energie sau informație curge în celulele de dedesubt. Fundalul verde-mentă de joasă tensiune și linia laser solidă separă chirurgical etichetele de datele propriu-zise, captând instantaneu atenția prin strălucirea de diagnostic a sistemului.
- **Logica Cascadei**: Are o specificitate locală ridicată. El suprascrie fundalul transparent al rândurilor și impune o linie inferioară mai groasă (`2px`) decât liniile celulelor normale, acționând ca un scut superior în cascadă pentru a bloca amestecarea vizuală a etichetelor master.

• **Selectorul `td` (Învelișul Unificat al Celulelor de Date)**

- **Motivul Ontologic**: Garantează **Amortizarea Spațială și Egalitatea Geometrică a Datelor**. Corectarea duplicării din fișierul vechi în favoarea valorii unice de `12px` restabilește o armonie vizuală deplină: textul din celule se aliniază la milimetru cu textul din antet (`th`), oferind caracterelor monospace o zonă sigură de protecție (pătrat tehnic), formula anti-overflow garantând că nicio adresă URL uriașă nu va deforma sau sparge ecranul.
- **Logica Cascadei**: Acționează ca o regulă de formatare internă de tip block-to-inline. Prin intermediul directivei `white-space: normal !important`, el suprascrie NOWRAP-ul global în cazul în care fereastra browserului devine extrem de strâmtă (pe ecrane mobile sau ecrane splitate), permițând textului să cadă curat pe rândul următor în interiorul celulei, fără să spargă marginile fizice ale monitorului.

• **Selectorul `tr:hover` (Răspunsul Kinetic pe Rând / Proximity Sweep Bar)**

- **Motivul Ontologic**: Mimează o **Rază de Scanare Proximity**. În tabelele dense cu zeci de date, ochii operatorului pot pierde rândul. Iluminarea bruscă și discretă pe spectrul verde-mentă a întregului rând atins de cursor confirmă hardware că acele date au fost izolate temporar din matrice pentru o citire sigură.
- **Logica Cascadei**: Se așază sub definițiile de repaus ale elementelor din tabel. Fiind o pseudo-clasă dinamică echipată cu directive `!important`, ea intervine ultima în ordinea de citire a proprietăților rândului și suprascrie local fundalul transparent, dezactivându-și efectul instantaneu în momentul în care cursorul părăsește coordonatele.

• **Selectorul `td::selection` (Selecția de Înaltă Tensiune / Text Highlight Map)**

- **Motivul Ontologic**: Reprezintă o **Captură de Energie (Data Extraction Protocol)**. Marcarea textului copiat pe culoarea roz de alertă militară simulează o extragere de date de înaltă frecvență, rupând monotonia verde a ecranului pentru a oferi un contrast radar maxim pe placa aprinsă.
- **Logica Cascadei**: Fiind un pseudo-element special de interfață, el rulează în fundal deasupra tuturor regulilor cromatice anterioare, intrând în acțiune doar la declanșarea evenimentului de drag-select, fără a perturba culorile de repaus.

• **Selectorii de Scrollbar Custom `.data-grid::-webkit-scrollbar` ... `-track` (Bara de Scroll Catodică)**

- **Motivul Ontologic**: Întruchipează **Minimalismul Hardware și Integrarea sub-Sistemelor**. Barele de scroll implicite ale browserelor moderne sunt groase și deformează aspectul de cockpit industrial. Subțierea barei la doar 3px o transformă într-un indicator discret, o mică șină electrică verde-mentă care păstrează tabelul compact, fluid și perfect integrat în estetica generală a monitorului CRT.
- **Logica Cascadei**: Aceste reguli Webkit sunt legate strict de rădăcina tabelului, nu de conținutul lui. Ele stau la finalul Sub-Modulului 11.3 deoarece definesc finisajul exterior al „cutiei” mari de tabel. Ele nu influențează așezarea textelor din interior, ci doar controlează modul în care containerul își gestionează overflow-ul fizic pe ecranele strâmte.

**SUB-MODULE 10.4: THE CELLULAR CYBER-LINKS (REȚELELE INTERACTIVE DE ANCORE)**

După configurarea carcasei macro și a șasiului fizic al tabelelor (Sub-Modulul 10.3), cascada se concentrează pe elementele dinamice interioare ale celulelor. Acest sector izolează și tratează **sistemele micro-cinetice de navigație și micro-accentele cromatice la hover**, separând intenționat designul structural de layout de ingineria fină a animațiilor laser.

• **Selectorul `.data-grid td a` (Ancorele Active din Tabel / Symmetrical Cellular Links)**

- **Motivul Ontologic**: Întruchipează **Frecvența de Căutare și Scanare HUD**. În estetica industrial-cyberpunk a cockpit-ului, un link nu trebuie să arate ca un text comun de internet terestru. El este un nod de telemetrie activ, o scurtătură cibernetică ce pulsează discret pe culoarea stelelor, semnalizând echipajului că acea celulă de date ascunde o rută de navigare validă.
- **Logica Cascadei**: Se plasează la deschiderea sub-modulului pentru a defini starea latentă de repaus a portalurilor. Declararea obligatorie a proprietății `position: relative` pe această clasă deschide o „rădăcină de coordonate locală”, absolut necesară pentru a bloca și reține firul laser virtual (`::after`) direct sub litere, împiedicându-l să evadeze în tavanul tabelului macro.

• **Selectorul Pseudo-Element `.data-grid td a::after` (Firul Laser de Energie Ascuns / The Invisible Underscore)**

- **Motivul Ontologic**: Reprezintă un **Circuit Latent de Înaltă Tensiune**. Firul nu este vizibil în starea de veghe a navei pentru a nu aglomera vizual tabelele dense cu zeci de date. El stă retras în vidul digital, complet comprimat, așteptând ca impulsul electric al cursorului să îi alimenteze nodurile pentru a se materializa pe ecran.
- **Logica Cascadei**: Fiind un pseudo-element dependent, el moștenește axa de coordonate deschisă de părinte. Proprietatea `transition` configurată pe `width` cu o curbă cubic-bezier specifică flotei Solaris garantează că, în momentul activării, extinderea orizontală nu va fi un salt sec, ci o glisare fluidă și elegantă de la stânga la dreapta.

• **Selectorul `.data-grid td a:hover` (Declanșarea Cromatică a Porții / Active Link State)**

- **Motivul Ontologic**: Simulează **Validarea și Cuplarea Releei**. Schimbarea violentă a culorii literelor indică faptul că portalul a fost interceptat, iar computerul de bord direcționează fluxul de energie al ecranului pe acel nod specific, pregătind transmisiunea de date.
- **Logica Cascadei**: Se așază imediat sub starea de repaus a link-ului. Ea rescrie prioritar culoarea textului exclusiv pe perioada intersecției, dezactivând efectul și readucând link-ul la frecvența albastră nativă în milisecunda în care mouse-ul părăsește zona.

• **Selectorul `.data-grid td a:hover::after` (Explozia Vectorului Laser / The Laser Width Deployment)**

- **Motivul Ontologic**: Întruchipează **Fuziunea și Materializarea Circuitului (The Laser Deployment Map)**. Extinderea fulgerătoare a firului roz-neon sub litere oferă un răspuns tactil și cinematic de înaltă rezoluție. Operatorul primește o confirmare vizuală incontestabilă: poarta este armată complet, linia laser subliniază importanța resursei, iar portalul este deschis pentru propulsie asincronă.
- **Logica Cascadei**: Este selectorul final și cel mai specific al sub-modulului. El combină o pseudo-clasă de acțiune (`:hover`) cu un pseudo-element structural (`::after`). În momentul atingerii, această linie execută prioritar rescrierea dimensiunii orizontale de la 0 la 100%, rulând fluid pașii de tranziție stocați în memorie fără a decala sau influența cu un singur pixel padding-ul simetric de `12px` al celulei gazdă `td`.

**SUB-MODULE 10.5: THE RADAR DATA STREAMS (MONITOARELE CRT VERZI)**

După configurarea structurilor de bază ale tabelelor (Sub-Modulul 11.3) și a micro-accentelor interactive (Sub-Modulul 11.4), cascada deparazitează elementele de afișare a codului sursă. Acest sector izolează și tratează **casetele de afișare preformatate și textul fosforescent**, oferind o identitate vizuală unificată și protejând layout-ul de erori de lăbărțare pe ecrane splitate.

• **Selectorul `pre` (Securizare Blocuri de Cod / The Radar Data Streams)**

- **Motivul Ontologic**: Întruchipează **Incinta Ecranului Catodic (The CRT Hardware Viewport)**. În universul _Solaris_, codul sursă nu este o simplă înșiruire inertă de litere pe o foaie albă; el reprezintă fluxul de date brute procesat în timp real de computerul de bord. Umbra interioară verde și masca întunecată transpun utilizatorul direct în fața unui monitor industrial militar dintr-o stație spațială a anilor '70.
- **Logica Cascadei**: Deschide sub-modulul ca selector macro de tip bloc. Declararea proprietății `position: relative` este obligatorie pentru a deschide o rădăcină locală de coordonate, permițând indicatorului spectral (`pre::before`) să leviteze în colțul superior al sticlei fără să evadeze în tavanul ecranului. Directiva `white-space: pre-wrap` execută o reparație istorică majoră: ea elimină comportamentul nativ distructiv al elementului `pre` care tinde să lungească rândul la infinit pe orizontală, forțând liniile de cod să se replieze curat pe rând nou în interiorul casetei pe ecrane mici sau ferestre splitate.

• **Selectorul `code` (Textul Fosforescent din Arhivă / The Fluorescent Terminal Text)**

- **Motivul Ontologic**: Reprezintă **Radiația Fotonilor de Fosfor (The Phosphor Glow Core)**. Literele de cod trebuie să aibă aspectul unui fascicul de electroni imprimat direct pe sticla tubului catodic, strălucirea difuză simulând emisia de lumină stabilă a terminalelor vechi analogice.
- **Logica Cascadei**: Acest selector de etichetă simplă moștenește fundalul întunecat de la părintele `pre`, dar intervine local și suprascrie fontul și umbra textului general. Dimensiunea compactă de `0.9rem` garantează că blocurile mari de instrucțiuni pot fi parcurse cu o scannability optimă, fără a polua vizual restul jurnalului.

• **Selectorul Pseudo-Element `pre::before` (Indicatorul Digital din Colț / Automated Telemetry Indicator)**

- **Motivul Ontologic**: Simulează un **Mesaj Automat de Status de Firmware (Firmware Ambient Script)**. El avertizează operatorul că acel ecran catodic este online, calibrat și conectat la fluxul central de telemetrie al navei, adăugând un strat profund de atmosferă industrial-SF elementului grafic de bază.
- **Logica Cascadei**: Se ancorează absolut raportat la marginile de repaus ale cutiei `pre`. Utilizarea unei opacități de 50% și a dimensiunii micro-fine blochează din start orice conflict de atenție vizuală: eticheta rămâne pitită pe fundal, devenind vizibilă doar la o scanare atentă a monitorului, fără a perturba citirea liniilor de cod active de dedesubt.

• **Selectorii de Scrollbar Custom `pre::-webkit-scrollbar` și `-thumb` (Micro-Firul de Scroll Albastru)**

- **Motivul Ontologic**: Reprezintă **Micro-Circuitul de Navigație Axială**. O bară de scroll standard grosolană ar distruge aspectul de instrument militar fin. Subțierea ei la doar 4px și aprinderea pe culoarea stelelor albastre creează o distincție cromatică superbă: ecranul emite energie verde, iar șina lui de ghidaj pulsează discret pe albastru electric.
- **Logica Cascadei**: Aceste reguli Webkit sunt legate strict de rădăcina elementului `pre`. Ele încheie Modulul 11.5 deoarece controlează finisajul exterior al cutiei. Ele nu influențează așezarea codului sursă, ci doar controlează modul în care containerul își gestionează overflow-ul fizic în cazul în care un rând de instrucțiuni refuză wrap-ul automat.

**SUB-MODULE 11.6: THE AUXILIARY ANNEXES & FUTURE AMBER VAULTS (PANOURI AUXILIARE)**

După izolarea radarelor de cod preformatat (Sub-Modulul 10.5), cascada structurală unifică ultimele componente satelit care completează paginile jurnalelor de navigație. Acest sector tratează **panourile de extensii pentru scripturi, link-urile globale, sub-logurile interne și capsulele de timp în așteptare**, demonstrând practic conceptul de specificitate contextuală prin excepții locale de ierarhie.

• **Selectorii `.js-annex` și `.js-annex h4` (Panourile de Extensii / The JavaScript Badge Framework)**

- **Motivul Ontologic**: Reprezintă un **Nod Satelit de Extensie (The Extension Pod)**. Când materia jurnalului depășește limbajele de bază (HTML/CSS) și interoghează sisteme asincrone superioare (JavaScript), interfața avertizează operatorul prin schimbarea culorii de graniță pe violetul profund al nebuloasei. Înălțarea titlului `h4` direct pe bordură sub formă de etichetă mecanică nituită elimină designul web plat, evocând carcasele rigide ale aparatelor de măsură analogice.
- **Logica Cascadei**: Declararea lui `position: relative` pe containerul părinte deschide un context local strict de coordonate care blochează elementul `h4` în flancul stâng (`left: 15px`). Directiva finală `font-style: normal` aplicată pe titlu acționează ca un scut de decontaminare: ea distruge forțat orice moștenire parazită de text italic sosită din eventualele scurgeri de cod globale ale site-ului.

• **Selectorul `.archive-link` și Starea de Hover (Butoanele Portale de Navigație / Outbound Channels)**

- **Motivul Ontologic**: Întruchipează **Cuplarea Releei de Transmisiune**. Butonul nu este o simplă legătură textuală, ci un comutator hardware activ. Trecerea instantanee de la starea de contur fin la placa solidă aprinsă și textul întunecat oferă operatorului o confirmare vizuală violentă, specifică ecranelor cu descărcări electrice, semnalizând că poarta spre arhive a fost armată.
- **Logica Cascadei**: Se plasează ca o componentă globală reutilizabilă de tip block-to-inline. Tranziția fluidă de `0.3s ease` guvernează toate proprietățile simultan (`all`), pregătind elementul pentru rescrierile de context care urmează imediat în cascadă.

• **Selectorii de Excepție Contextuală `.js-annex .archive-link` și `:hover` (Nesting Overrides)**

- **Motivul Ontologic**: Mimează **Integrarea Hardware și Adaptarea de Tensiune**. Un buton general masiv ar fi sufocat vizual interiorul casetei mici `.js-annex`. Compactarea lui și vopsirea pe spectrul violet demonstrează că piesa a fost integrată electric în sub-modulul gazdă, adaptându-și consumul și aspectul la rețeaua locală.
- **Logica Cascadei**: **Acesta este un exemplu de elită de specificitate combinată (Selector Descendent)**. Deoarece regula conține două clase înlănțuite (`.js-annex .archive-link`), ea are o greutate mai mare în cascadă decât clasa simplă `.archive-link` definită anterior. Browserul execută o suprascriere chirurgicală: lasă butoanele de pe restul paginilor mari și verzi, dar le micșorează și le transformă în violet strict pe cele din interiorul anexelor, rulând fluid noii parametri de hover fără a deforma layout-ul de bază.

• **Selectorul `.future-log` și Starea de Hover (Capsulele Timpului / The Dormant Amber Vaults)**

- **Motivul Ontologic**: Întruchipează **Starea de Hibernare și Criptare a Datelor**. Un capitol viitor este o capsulă de timp inertă. Filtru grayscale și opacitatea redusă sugerează vizual că datele sunt înghețate sub straturi de securitate. Modificarea bruscă la hover reprezintă **Trezirea și Sincronizarea Core-ului**: cardul glisează spre dreapta ca un sertar magnetic ce iese din consolă, culorile explodează înapoi online pe ecran, iar titlul interior pulsează rapid prin animația `pulse 1s infinite`, confirmând alimentarea circuitului cu tensiune chihlimbar completă.
- **Logica Cascadei**: Se plasează la absolut finalul Modulului 11 ca o componentă de suprascriere majoră. Utilizarea directivelor `!important` pe culorile de graniță este justificată didactic pentru a sparge și anula cu desăvârșire bandourile verzi standard definite pe `.log-entry` în Sub-Modulul 11.2. La hover, regula transmite energia în aval: ea forțează inclusiv insignele `.sub-log` și etichetele superioare `h4` interioare să își abandoneze nuanțele stabile de repaus pentru a se aprinde unitar în nuanța chihlimbarului de avertizare, demonstrând o coordonare perfectă a sistemelor în cascadă.

🌟 **19. MODULE 11**
**REZUMAT / SUMMARY**: Acest modul configurează blocul final de închidere structurală a machetelor standard (`.footer`). El implementează un scut protector din sticlă fumurie Solaris semi-transparentă, delimitat superior de o linie laser dublă violet-roz, și rulează un motor rigid Flexbox pe verticală pentru a alinia simetric toate metadatele de telemetrie, indicatorii de stare online și semnăturile digitale ale echipajului.

**SCALAREA DIDACTICĂ A CASCADEI (Scaffolding Architecture)**

- **Protejarea Curbei de Învățare**: Păstrarea Terminalului de Subsol ca **Modulul 11** reprezintă o decizie pedagogică strategică fundamentată pe conceptul de _scaffolding_ (eșalonarea progresivă a dificultății). Deși din punct de vedere pur vizual footer-ul se află la baza paginii, din punct de vedere al complexității tehnice, el utilizează proprietăți macro de layout tradiționale și accesibile (`display: flex`, `opacity`, `transition`, marje de centrare).
- **Zona de Respirație Cognitivă**: Amplasarea subsolului în acest punct exact oferă studenților un moment de consolidare și respirație vizuală după densitatea tabelelor din Modulul 11. Această barieră didactică separă curat layout-ul structural clasic de **„Laboratorul de Inginerie Avansată și Tehnologii Neconvenționale”** (reținut exclusiv pentru Modulele 13, 14 și 15). Astfel, studenții sunt feriți de un șoc cognitiv major, fiind pregătiți metodic înainte de a plonja în matrici geometrice mult mai complexe (decupări `clip-path` octogonale în 8 puncte, rotații tridimensionale pe 3 axe virtuale sau ecrane splitate asimetrice).

**MOTIVUL ONTOLOGIC (Filosofia de Design a Subsolului)**

În topografia odiseei noastre virtuale, dacă ecranul Hero este poarta de intrare, **Modulul 11 (Footer Terminal) reprezintă Sigiliul și Semnătura Flotei**. Este un ecran administrativ de încheiere, un „panou negru de diagnostic” amplasat la podeaua navei unde se oprește zgomotul transmisiunilor narative.

- **Sticla Translucidă Solaris (`.footer`)**: Utilizarea unei opacități de 40% combinată cu blur de `10px` nu este o simplă alegere cosmetică modernă. Ea simulează un material fizic — sticlă acrilică fumurie ecranată. Subsolul nu pare lipit artificial pe fundal, ci dă senzația unui panou hardware real, greu, încastrat direct în vidul întunecat al cockpit-ului, permițând structurilor din spatele lui să se dizolve cinematic.
- **Laserul Dublu Violet-Roz (`border-top`)**: O linie simplă de border ar fi sugerat un site web civil comun. Tăietura dublă originală la o opacitate fină de 20% simulează o **Barieră Energetică de Demarcație**. Ea avertizează operatorul că a parcurs toate cronicile zilnice și a atins puntea limită a sectorului curent.
- **Frecvența de Activare Proximity (`:hover`)**: Trecerea instantanee la opacitate maximă (`1`) și aprinderea laserului dublu în nuanța roz-magenta intens a alarmei de sistem reprezintă **Sincronizarea și Armarea Consolei**. Când omul privește sau atinge baza ecranului, subsolul „se trezește” din modul de economisire a energiei, confirmând hardware că circuitele sunt online și gata de dialog tehnic.
- **Liniile Monospace de Telemetrie (`p`, `.copyright`)**: Forțarea fontului rigid mecanic `monospace` cu majuscule militare și un letter-spacing larg de `3px` transformă textul simplu de drepturi de autor într-o **Transmisiune de Date Criptate**. Aspectul amintește de benzile de telex imprimat sau de monitoarele radar secundare ale navelor maritime, unde textul nu are rol decorativ, ci transmite coordonate rigide de zbor.
- **Martorii Luminoși de Diagnostic (`.telemetry-active`, `.vessel-sig`)**: Sunt ledurile de control de pe tabloul de bord. Într-un ecran stins, aprinderea bruscă a cuvântului „ONLINE” pe verde-mentă fosforic cu o aureolă de neon indică vizual o stare stabilă a sistemelor, în timp ce rozul neon semnează autoritatea inginerească a constructorului navetei, generând un contrast izbitor de înaltă rezoluție.

**LOGICA CASCADEI (Mecanica de Poziționare și Specificitate)**

Ordinea de scriere și structura regulilor din Modulul 12 urmează principiul **Curățării Subordonate și al Protecției Axiale**, garantând că subsolul rămâne perfect imun la deformări pe orice rezoluție hardware:

- **Ancorarea și Protecția prin Copil Direct (`.footer`)**: Acest selector macro deschide modulul și folosește proprietatea `position: relative`. Ea este directiva genetică obligatorie: deschide o rădăcină locală de coordonate, asigurându-se că micro-accentele de neon și straturile de blur rămân blocate în incinta subsolului și nu colapsează în alte module de deasupra.
- **Ordinul Dictatorial de Aliniere Flexbox (`display: flex !important`)**: În cascadă, utilizarea directivei `!important` pe Flexbox și pe direcția coloanei (`flex-direction: column !important`) execută un act de autoritate chirurgicală. Ea anulează complet orice comportament nativ de bloc extins al browserelor terestre și forțează toate paragrafele interne să se așeze tehnic sub formă de benzi paralele pe verticală, direct una sub cealaltă.
- **Scutul Anti-Decalaj Axial (`margin-left: auto !important`, `margin-right: auto !important`)**: Aceste marje forțate acționează ca niște magneți axiali egali pe monitoarele mari de desktop. Ele blochează caseta exact pe mijlocul ecranului, împiedicând-o să migreze asimetric spre stânga sau spre dreapta sub influența altor elemente de layout mari (cum este sidebar-ul general), menținând simetria perfectă a navei amiral.
- **Strângerea Casetei de Text pe Dimensiunea Reală (`width: auto !important`)**: Aplicarea acestei reguli forțate pe paragrafele `.footer p` și pe containerul `.external-comms` este o mișcare strategică de siguranță. În mod implicit, elementele de tip block încearcă să ocupe 100% din lățime, fapt care ar fi întins aureola luminoasă (`text-shadow`) a cuvintelor pe tot ecranul, creând un blur haotic. Directiva `width: auto` strânge membrana cutiei exact pe lungimea textului scris, permițându-i lui `align-items: center` de sus să execute o centrare milimetrică perfectă.
- **Suprasolicitarea Stării Dinamice la Hover (`.footer:hover`)**: Selectorul de hover este plasat imediat sub starea de repaus a corpului mare. El intervine ultimul în ordinea cascadei din acest sector și suprascrie opacitatea nativă de `0.8`, browserul recalculând instantaneu cadrele luminoase și transmițând culoarea roz-neon direct pe bordura superioară, fără a perturba înălțimea fixată de padding de `40px 20px`.

🌟 20. **MODULE 12: GEOMETRIC SYSTEM // PORTALE POLIGONALE SECTOR (OCTAGONAL STYLE)**

**REZUMAT**: Acest modul construiește nodurile de navigare octogonale compacte, profilate laser în interiorul meniului din sidebar (`.sidebar-nav`). El rulează un motor `inline-flex` pentru centrarea axială a textului liliputan de `0.6rem !important`, folosește un fundal de 15% mov stins și deblochează o matrice procentuală în 8 puncte (`clip-path`) pentru a asambla butoane tactile cu unghiuri rigide la 45 de grade.

• **Selectorul Grupat `.sidebar-nav .week-label a, .sidebar-nav .sector-link` (Tastele Hardware Octogonale)**

- **Motivul Ontologic**: Întruchipează **Tasta Hardware de Instrument de Zbor (The Tactile Flight Deck Key)**. În estetica cockpit-ului tau industrial, butoanele din sidebar-ul de navigare nu sunt simple rânduri de text; ele sunt butoane fizice decupate laser dintr-o placă acrilică de sticlă fumurie. Forma octogonală rigidă cu unghiuri la 45 de grade rezonează cu ecranele tactile de pe radarele navelor de luptă SF, adăugând un nivel uriaș de atmosferă și realism interfeței web.
- **Logica Cascadei**: Se așază la deschiderea Modulului 13, imediat după ce subsolul din Modulul 12 a închis structurile simple de layout. Selectorul deține o specificitate ridicată prin includerea clasei părinte `.sidebar-nav`, asigurându-se că regulile dictatoriale (marcate cu `!important`) se aplică chirurgical _doar_ butoanelor mici din meniul asimetric, lăsând ancorele mari de pe restul paginilor complet imune.

• **Selectorul de Stare Dinamică la Hover (Suprasarcina Cromatică și Micro-Expansiunea Kinetică)**

- **Motivul Ontologic**: Simulează **Răspunsul Mecanic al Butonului Tactil (The Micro-Kinetic Feedback Loop)**. Întrucât interfețele ecranelor de sticlă duc lipsă de butoane fizice cu resort, micro-expansiunea cinematică la hover (`scale(1.05)`) combinată cu explozia aureolei de neon violet oferă operatorului o confirmare tactilă digitală instantanee că nodul a fost selectat și portalul este gata pentru inițializarea saltului de rețea.
- **Logica Cascadei**: Așezat imediat sub repausul butoanelor, suprascrie opacitatea de veghe (`0.85`) și fundalul stins. El este guvernat de harta de tranziție `cubic-bezier(0.4, 0, 0.2, 1) !important` configurată mai sus pe toate proprietățile (`all`), forțând browserul să ruleze micro-mărirea și aprinderea neonului într-o mișcare extrem de fluidă, fină și profesionistă.

🌟 21. MODULE 13: THE HOLO-GEODESIC ENGINE (REACTORUL ARMILAR TRIDIMENSIONAL)

• Selectorul `.armillary-reactor-core` (Lentila Cubic-Virtuală Master)

- **Motivul Ontologic**: Reprezintă o ruptură în continuitatea plană a interfeței web clasice. Ecranul încetează să mai fie o simplă foaie incoloră de hârtie digitală și devine o incintă fizică adâncă, un reactor atomic transparent în care cunoașterea prinde volum și greutate spațială, provocând o stare de uimire epistemică operatorului.
- **Logica Cascadei**: Se așază la absolut începutul Modulului 07 deoarece este „fundația gravitațională 3D” a întregului sector. Toate elementele care urmează (fețe, inele, text) se nasc în interiorul acestui selector părinte și depind în mod absolut de lentila lui de perspectivă pentru a putea levita pe axa Z.

• Selectorul `.quantum-plasma-sphere` (Miezul Rotativ al Grilei Spațiale)

- **Motivul Ontologic**: Într-un univers SF analogic, mișcarea circulară constantă indică viața și funcționarea motorului central de date. Sfera nu este un obiect inert, ci un organism geometric în stare critică ce prelucrează telemetria expediției.
- **Logica Cascadei**: Vine imediat sub `.armillary-reactor-core` deoarece este primul copil real din layout-ul 3D. El moștenește axa Z deschisă de părinte și acționează ca o „sub-rădăcină” dinamică: rotația aplicată pe această clasă se va scurge în cascadă peste toate cele 20 de fețe triunghiulare din interior, făcându-le să se rotească unitar în spațiu fără a le altera unghiurile individuale.

• Selectorul `.quantum-plasma-sphere .face` (Panourile Poligoanelor Triunghiulare)

- **Motivul Ontologic**: Fețele triunghiulare din sticlă refractă lumina adâncă a vidului, simbolizând fragmentele de cunoaștere pe care filosoful-programator le asamblează într-o structură unică, coerentă și armonioasă (poliedrul platonician).
- **Logica Cascadei**: Acest selector tip etichetă compusă stabilește „codul genetic estetic” comun pentru absolut toate fețele, înainte ca acestea să fie trimise la unghiurile lor specifice. Orice triunghi se naște cu aceeași mască de sticlă și border fin verde, reducând drastic volumul fișierului CSS.

• Selectorii Grupați de Poziționare `.face-t1` ... `.face-b5` (Matricea de Coordonate Vectoriale)

- **Motivul Ontologic**: Reprezintă Aritmetica Sacră Hardware. Unghiurile nu sunt opționale sau alese estetic; ele respectă rația de aur (Golden Ratio). Intercalarea laser roz pe fețele pare sparge monotonia verde-mentă și generează pe ecran aspectul de plasă de înaltă tensiune alternantă, confirmând complexitatea tehnologică a mașinii.
- **Logica Cascadei**: Fiind selectori unici de clasă cu specificitate înaltă, plasați consecutiv, ei suprascriu coordonata zero comună a părintelui `.face`. Browserul citește aceste linii ca pe o listă de ordine militare de plasament spațial: fiecare triunghi își preia matricea unică pe axele X-Y-Z și îngheață pe poziția sa geometrică precisă, îmbinându-se perfect margine în margine cu vecinii săi, fără a lăsa goluri de aer.

• Selectorul `.armillary-reactor-core:hover .quantum-plasma-sphere` (Suprasarcina Kinetică a Miezului)

- **Motivul Ontologic**: Demonstrează reactivitatea organică a interfeței. Când omul interoghează mașina prin atingere, reactorul răspunde instantaneu trecând într-o stare de alertă critică, o rotație ultra-rapidă ce indică activarea proceselor asincrone superioare de calcul.
- **Logica Cascadei**: Folosește o pseudo-clasă aplicată pe containerul mare combinată cu un descendent. Stând sub definiția de repaus a sferei, are puterea în cascadă de a intercepta și accelera timpul animației pe loc, browserul re-calculând instantaneu cadrele de rotație pe minut fără decalaje.

• Selectorul `.armillary-reactor-core:hover .face` (Fuziunea Energetică a Panourilor)

- **Motivul Ontologic**: Accentuarea marginilor și tremurul fluorescent intens al fețelor de sticlă sugerează o acumulare masivă de tensiune electrică în nodurile rețelei poliedrice, interfața simulând o fuziune plasmatică imersivă la atingerea ecranului.
- **Logica Cascadei**: Poziționarea sa la finalul blocului de hover dezasamblează starea stabilă de repaus și impune temporar acest comportament electric dictatorial peste toate cele 20 de triunghiuri, ignorând local culorile lor de bază prin directiva `infinite alternate !important`.

• Selectorul `.armillary-band-container` (Straturile HUD Ecuatoriale / Astrolabul)

- **Rolul în context**: Targetează containerul structural care plutește pe orizontala miezului 3D, acționând ca o centură metalică ecuatorială ce încapsulează benzile de text texturate.
- **Misiune**: Centrează perfect benzile de text pe axa centrală a ecranului prin Flexbox unificat, limitează lățimea maximă la `780px` pentru a proteja lizibilitatea pe monitoare ultra-wide și impune un `z-index: 5` agresiv.
- **Motivul Ontologic**: Întruchipează inelele de citire ale unui astrolab analogic. Textul nu trebuie să se rotească haotic o dată cu Icosaedrul din fundal; el trebuie să rămână stabil pe orizontală pentru a putea fi citit chirurgical de către echipaj, plutind deasupra haosului tridimensional din miez.
- **Logica Cascadei**: Se plasează după vectorii 3D deoarece trece de la modelarea poliedrului la elementele HUD de text suprapuse. Proprietatea sa de elevare `z-index: 5` rupe ordinea nativă a straturilor și ridică benzile de text pe o platformă superioară, deasupra fețelor 3D, garantând un contrast total.

• Cooperarea Wrapperelor `.macro-wrapper` și `.micro-wrapper` (Poziționarea Axială)

- **Motivul Ontologic**: Mimează inelele concentrice ale instrumentelor de navigație astronomice vechi, ecranele fiind distanțate simetric pentru a lăsa spațiu de respirație vizuală în interiorul cockpit-ului.
- **Logica Cascadei**: Vin imediat sub containerul lor general, funcționând ca specificări locale. Ele dictează doar înălțimea, lăsând restul proprietăților grafice să fie moștenite unitar.

• Selectorul `.astrolabe-metal-arc` (Șasiul de Sticlă al Benzilor de Text)

- **Motivul Ontologic**: Reprezintă fanta fizică de sticlă fumurie a unui monitor industrial. Literele deschise la culoare au nevoie de un ecran întunecat în spatele lor pentru a asigura lizibilitatea maximă, gradientul care dispare spre margini creând impresia unui inel care se curbează în adâncimea vidului.
- **Logica Cascadei**: Se așază cu `z-index: -1` față de părintele său direct, alunecând în mod controlat în spatele textului, oferind contrastul cromatic necesar fără a polua elementele exterioare.

• Selectorii Pseudo-Element `.macro-wrapper::after` și `.micro-wrapper::after `(Tăieturile Laser de Demarcație)

- **Motivul Ontologic**: Reprezintă sudurile energetice sau circuitele active care alimentează astrolabul. Alternanța de timp (delay-ul de 2s) și de culoare (roz vs verde) creează un dialog cromatic superb, indicând că panourile HUD pulsează în parametri nominali diferiți în vid.
- **Logica Cascadei**: Fiind pseudo-elemente finale, încheie apoteotic Modulul 07. Ele folosesc `pointer-events: none` pentru a rămâne entități pur spectrale, neafectând interacțiunea tactilă a mouse-ului și lăsând structura generală curată și perfect auto-documentată.

🌟 22. **MODULE 14: BLUEPRINT OVERLAY // DESIGN SPECIFIC PENTRU INTERFAȚA RECURSIVĂ**

**REZUMAT / SUMMARY**: Acest modul finalizează ierarhia stilistică a proiectului, funcționând ca o incintă izolată dedicată exclusiv ecranului de documentație master (`recursive-blueprint.html`). El orchestrează dispunerea asimetrică de tip split-screen (panouri paralele), formatează monitorul catodic virtual din dreapta pentru inspectarea sintaxei și deblochează reținerea spațială a axei Z prin filtrul de scalare, forțând mini-Icosaedrul 3D să execute o horă luminoasă fluidă și scurtcircuite electrice de înaltă frecvență la atingere.

• **Selectorul Master `.blueprint-container` (Scutul Axial al Blueprint-ului)**

- **Motivul Ontologic**: Reprezintă **Matricea de Siguranță a Planșei Tehnice**. Pagina de documentație nu este un jurnal narativ fluid, ci o planșă tehnică de inginerie. Plafonul de 1300px forțează datele să rămână grupate compact în fața operatorului, setând o distanță vizuală ideală pentru analiză.
- **Logica Cascadei**: Se poziționează la absolut începutul Modulului 14. Rolul său în cascadă este de a stabili coordonatele spațiale master, forțând fontul rigid `monospace` prin moștenire directă în aval peste toate sub-elementele care nu au etichete specifice declarate.

• **Selectorul `.terminal-split` (Rețeaua Macro Split-Screen)**

- **Motivul Ontologic**: Întruchipează **Mecanica Monitorului Dual (The Dual-Chamber Workspace)**. Cunoașterea teoretică (stânga) și execuția practică (dreapta) sunt așezate în oglindă. Operatorul poate citi explicațiile didactice și poate inspecta simultan codul sursă în milisecunda în care scanează ecranul pe orizontală, eliminând efortul de navigare între pagini separate.
- **Logica Cascadei**: Acest selector de clasă simplă folosește directive `!important` pentru a se asigura că, pe rezoluțiile mari de desktop, panourile refuză stivuirea verticală nativă din modulele anterioare, înghețând layout-ul într-o aliniere paralelă perfectă.

• **Selectorul `.panel` și `.panel-title` (Capsulele Hermetice din Panou)**

- **Motivul Ontologic**: Întruchipează **Izolarea Compartimentată a Cunoașterii (The Sealed Knowledge Chambers)**. Într-o interfață de diagnostic avansat, datele nu pot pluti libere pe ecran fără protecție. Panourile funcționează ca două seifuri acrilice ermetice, luminate discret la margini de o micro-tensiune verde fosforic, oferind operatorului senzația că analizează componente de înaltă siguranță. Umbra exterioară densă desprinde fizic panourile de carcasă, făcându-le să leviteze ca două ecrane tactice independente. Titlul `.panel-title`, tăiat la bază de linia punctată, simulează o etichetă metalică de inventar militar, indicând rigoarea și disciplina militară de la bordul navetei.
- **Logica Cascadei**: Elementul `.panel` introduce o directivă de urgență critică: **`min-width: 0 !important`**. Aceasta acționează ca un scut anti-overflow dictatorial: ea interzice blocurilor de cod preformatate ultra-lungi din interior să lăbărțeze sau să spargă lățimea fixă de 50% a panoului, forțând browserul să rețină textul în limitele oțelului digital.

• **Selectorul `.code-inspector-screen` (Șasiul Central al Inspectorului de Cod)**

- **Motivul Ontologic**: Reprezintă **Terminalul Catodic de Diagnostic (The Core Source Code Inspector)**. Acesta nu este un simplu container text; el simulează ecranul greu din sticlă securizată al unui computer central de pe o navă militară. Textul argintiu-indigo oferă un contrast odihnitor pentru ochi, iar umbra neagră interioară bombată mută utilizatorul din spațiul web modern direct întrun terminal retro-futurist.
- **Logica Cascadei**: Utilizează directiva `position: relative !important`. Aceasta este mutarea arhitecturală obligatorie care deschide contextul de poziționare local, permițând etichetei de diagnostic (`::before`) să plutească fixată pe sticla de sus, fără să fie afectată de scroll-ul vertical al liniilor de cod din interior.

• **Selectorul Pseudo-Element `.code-inspector-screen::before` (Eticheta de Diagnostic CRT)**

- **Motivul Ontologic**: Funcționează ca un **Ecou de Firmware Ambient**. Această ștampilă cromatică confirmă operatorului că transmisiunea de date codificate este online, validată și curge în parametri nominali stabili în interiorul cockpit-ului.
- **Logica Cascadei**: Beneficiază de directiva `pointer-events: none`. Deoarece plutește fizic deasupra textului, în lipsa acestei directive, ea ar fi blocat mouse-ul operatorului, împiedicându-l să selecteze sau să copieze codul din spatele etichetei. Această linie o transformă într-o proiecție spectrală prin care cursorul trece liber.

• **Selectorul `.recursive-reactor-wrapper` (Scutul Spațial al Mini-Reactorului)**

- **Motivul Ontologic**: Reprezintă **Miniatura de Diagnostic Holografic (The Micro-Reactor Core Projection)**. Pentru a nu deforma panoul teoretic, reactorul gigant este micșorat, devenind o replică digitală la scară redusă. Integrarea lui `preserve-3d` este un act de restaurare fizică: ea re-deschide adâncimea axei Z prin filtrul de scalare, împiedicând Icosaedrul să colapseze plat și transformându-l într-o sferă geometrică volumetrice reală în vid.
- **Logica Cascadei**: Forțarea înălțimii la 400px și aplicarea marjei negative compensează în cascadă spațiul fantomă pe care proprietatea `scale` îl lasă nativ în layout. Activarea lui `preserve-3d` în acest punct strategic oferă imunitate totală fețelor copii, permițându-le să își mențină translațiile spațiale de `210px` calculate pe baza rației de aur.

• **Selectorul de Hover pe Mini-Reactor `.recursive-reactor-wrapper:hover .quantum-plasma-sphere .face` (Hora Electro-Kinetică)**

- **Motivul Ontologic**: Întruchipează **Sincronizarea Core-ului și Hora Scurtcircuitului (The High-Voltage Particle Dance)**. Spre deosebire de încercările bidimensionale eșuate care plateau structura, conservarea lui `preserve-3d` pe părinte îi permite sferei să își continue rotația master asincronă, rară și maiestuoasă din Modulul 07. Triunghiurile verzi nu se mai contopesc haotic, ci se plimbă libere pe ecran într-o horă 3D superbă, tremurând și scurtcircuitând violent sub efectul arcurilor electrice de `0.12s`, generând un feedback tactil și cinematic de excepție.
- **Logica Cascadei**: Este selectorul final și cel mai specific al modului. Folosind o stivuire descendentă strânsă combinată cu directive `!important`, el sparge cu desăvârșire opacitățile și culorile albe de repaus ale fețelor, forțând browserul să ruleze tremurul fulgerător de luminozitate direct peste matricile tridimensionale înghețate în spațiu, fără a decala layout-ul cu un singur pixel.

🌟 23. **MODULE 00.1: KINETIC PROPULSION ENGINES & CENTRAL KEYFRAMES (BANCA DE ANIMAȚII)**

**REZUMAT / SUMMARY**: Acest modul centralizează și izolează toate motoarele de mișcare asincrone (`@keyframes`) utilizate pe interfețele navetei Solaris. Poziționat strategic la finalul layout-ului structural (după Modulul 14) și fix înaintea interogărilor media adaptive (`@media`), el acționează ca o „bancă de energie kinetică”, alimentând proprietățile `animation` apelate pe tot parcursul site-ului și protejând fișierul de coliziuni de moștenire sau duplicări parazite.

- **STRUCTURA DIDACTICĂ PE GRUPĂRI CINETICE (Scaffolding Engine)**
  Pentru a asigura o curbă de învățare lină și organică, eliminând haosul din codul vechi, blocul de `@keyframes` este eșalonat pedagogic în 4 mari districte funcționale: 1. **Gruparea A (Ambient Interface Effects)**: Micro-tensiunile de fundal care dictează atmosfera analogică a cabinei (linii catodice, pulsații neon și umbre energetice). 2. **Gruparea B (Asynchronous Teletype Engines)**: Motoarele mecanice ce guvernează scrierea incrementală a textului și comportamentul dinamic al cursorului hardware. 3. **Gruparea C (Telemetry Radar Sweeps)**: Razele de scanare și expansiunile sferice ce simulează actualizarea datelor de sector în timp real. 4. **Gruparea D (Quantum 3D Geodesic Spin)**: Transformările unghiulare avansate și scurtcircuitele plasmatice dedicate reactorului poliedric 3D.

  23.1. **GRUPAREA A: ATMOSPHERIC & STRUCTURAL FLICKERS (EFECTE AMBIENTALE)**

• **Motorul Kinetic `crt-flicker` (Instabilitatea Catodică)**

- **Motivul Ontologic**: Întruchipează **Instabilitatea Fizică a Lămpii CRT**. În estetica navetei Solaris, interfața nu este un ecran digital rece și static; ea este un instrument analogic viu. Tremurul microscopic permanent amintește operatorului că datele sunt afișate prin bombardament de electroni, oferind un feedback vizual organic, cald și profund imersiv.
- **Logica Cascadei**: Fiind apelată ca o animație infinită liniară la o viteză liliputană fină, ea nu intră în coliziune cu opacitățile textelor din interior. Deoarece se execută pe un pseudo-element fixat pe tot geamul cockpit-ului cu `pointer-events: none`, masca luminoasă tremură independent de scroll, fără a încetini procesarea paginii.

• **Motorul Kinetic `pulse` (Pulsația Neon și Luminozitatea HUD)**

- **Motivul Ontologic**: Reprezintă **Respirația Energetică a Core-ului**. Variația cursivă împiedică arderea statică a pixelilor pe fosforul ecranelor vechi. Lumina care se dilată și se strânge ritmic (la fiecare 2s sau 3s conform modulelor de navigație) simulează pulsația unui generator nuclear aflat în parametri nominali stabili.
- **Logica Cascadei**: Acest motor este un exemplu superb de reutilizare globală. O singură declarare de cadre este stivuită în cascadă de selectori diferiți cu timpi diferiți (`3s infinite` pe logo-ul mare și `2s infinite ease-in-out` pe link-ul intern), demonstrând cum o regulă centrală își poate schimba frecvența în funcție de specificitatea containerului gazdă.

• **Motorul Kinetic `energy-flicker` (Pulsul Divizorilor Decorativi)**

- **Motivul Ontologic**: Întruchipează **Descărcarea de Tensiune în Rețeaua Secundară**. Firul laser nu are doar rol de barieră estetică; el pulsează ca un circuit imprimat care se încarcă cu energie în milisecunda în care datele sunt active, ghidând privirea studentului printre volume.
- **Logica Cascadei**: Se plasează sub animația `pulse` pentru că face tranziția de la text-shadow la box-shadow structural. Proprietatea acționează elastic pe elementele de tip bloc subțiri de `1px`, transformând o simplă linie nativă `<hr>` într-un indicator cyberpunk dinamic.

• **MOTORUL KINETIC `glow-flicker` (FLICKER CATODIC COROZIU)**

**REZUMAT / SUMMARY**: Acest motor kinetic universal izolează o operațiune avansată de modulare optică prin intermediul filtrelor grafice hardware (`brightness`, `blur`) și a opacităților secvențiale. El este conceput special pentru a simula un comportament defectuos/instabil al monitoarelor analogice retro-SF pe stările de avertizare (Warning Status), fiind complet imun la coliziunile cromatice parazite.

- **Motivul Ontologic**: Întruchipează **Instabilitatea Tensiunii în Tuburile Catodice Vechi (The Analog Voltage Short-Circuit)**. În designul brutalist cyberpunk, o stare de hibernare tehnică nu poate pulsa fluid și moale ca un dispozitiv modern civil. Introducerea filtrelor de `blur` și a salturilor violente de `brightness` simulează comportamentul fizic al unui releu spațial defectuos, unde fluxul de electroni se chinuie să aprindă fosforul ecranului. Amestecul dintre textul chihlimbar stabil și tremurul neregulat oferă o atmosferă industrială copleșitoare și un realism profund imersiv manualului de curs.
- **Logica Cascadei**: **Aceasta este o decizie de elită pentru obținerea unui Motor Universal Reutilizabil (Color Independence Protocol)**. Deoarece animația utilizează exclusiv proprietăți fizice vectoriale (`opacity`, `filter`), ea **nu conține nicio variabilă cromatică fixă** în interiorul cadrelor sale `@keyframes`. Acest lucru înseamnă că nu va polua sau suprascrie optic culoarea textului! Ea lasă chihlimbarul nativ `var(--amber-glow)` definit în selectorul de layout să ruleze curat, spre deosebire de animația `pulse` care vopsea forțat textul în roz-neon, eliminând definitiv scurtcircuitele de moștenire parazită în browser.

• **Motorul Kinetic `cosmic-flicker` (Protocolul Licărire Discretă)**

- **Motivul Ontologic**: Simulează un **Efect Cinematic de Instrument Analogic Defect (The Strobe Neon Flare)**. Această licărire asimetrică elimină rigiditatea computerelor moderne; ea redă imperfecțiunea fermecătoare a arcurilor electrice din vechile relee spațiale, oferind realism tabloului de bord.
- **Logica Cascadei**: Încheie perfect districtul Efectelor Ambientale (Gruparea A). Amplasarea sa în cascadă este exploatată genial în modulele superioare prin adăugarea unui delay de `2s` pe inelul micro-verde (`animation-delay: 2s`). Browserul compilează aceeași animație, dar decalează impulsurile pe ecran, creând un dialog cromatic asincron superb între laserul roz superior și cel verde inferior.

  23.2. **GROUP B: ASYNCHRONOUS TELETYPE ENGINES (MOTOARE SCRIERE)**

**REZUMAT / SUMMARY**: Acest district kinetic izolează și controlează toate mecanismele de emulare a mașinii de scris mecanice, utilizate global pe antetele de titluri și casetele de status. Prin gruparea exclusivă a celor 3 piloni activi (`typing-modular`, `blink`, `hide-cursor`), acest districit demonstrează cum se pot stivui asincron proprietăți temporale multiple pe o singură linie de cod, garantând randări imune la overflow sau deformări parazite pe Desktop split.

• **Motorul Kinetic `typing-modular` (Desfășurarea Oblonului de Lățime)**

- **Motivul Ontologic**: Întruchipează **Generarea Mecanică de Text (The Raw Teletype Data Stream)**. În estetica cockpit-ului _Solaris_, datele nu apar instantaneu și steril pe ecran; ele sunt „tipărite” caracter cu caracter, imitând fluxul brut de telemetrie al calculatoarelor industriale analogice. Acest comportament oferă interfeței un ritm respirator captivant, capturând atenția studentului în milisecunda încărcării paginii.
- **Logica Cascadei**: Funcționează mână în mână cu funcția de timp rigidă `steps()` aplicată direct în selectori (ex: `steps(35, end)` pentru titlu și `steps(55, end)` pentru subtitlu). Această funcție sparge fluiditatea nativă a CSS-ului și forțează browserul să deschidă oblonul în trepte matematice fixe, egale cu numărul exact de caractere din șirul HTML, asigurând o scriere sacadată perfectă.

• **Motorul Kinetic `blink` (Pâlpâirea Cursorului Hardware Universal)**

- **Motivul Ontologic**: Reprezintă **Martorul Digital de Sincronizare (The Command Line Cursor Tick)**. El oferă operatorului dovada vizuală că sistemul este online, procesează instrucțiunile și se află la capătul activ al rândului de cod încapsulat.
- **Logica Cascadei**: **Aceasta este o lecție magistrală de reutilizare globală și specificitate (Principiul DRY)**. Utilizarea cuvântului cheie `inherit` reprezintă o alegere inginerească de elită: cursorul nu este blocat pe o singură culoare fixă. El preia dinamic și automat nuanța textului gazdă: va clipi verde-mentă fosforic pe `.mission-status` și argintiu desaturat pe `.stenciled-metal-text-sub`, eliminând necesitatea scrierii a 4 animații separate. Targetarea strictă a proprietății `border-right-color` (în loc de un `border-color` general) protejează integritatea casetelor: dacă elementul are chenar pe toate cele 4 laturi (cum este terminalul de note), hover-ul sau scrierea nu vor face ca întreaga cutie să dispară haotic, ci doar cursorul din dreapta.

• **Motorul Kinetic `hide-cursor` (Anihilarea Definitivă a Liniei de Ghidaj)**

- **Motivul Ontologic**: Întruchipează **Deconectarea Releei după Transmisiune (The Channel Purge Protocol)**. Odată ce textul tehnic de status a fost complet afișat pe ecran, cursorul intermitent devine o poluare vizuală inutilă. Stingerea lui automată semnalizează finalizarea cu succes a scriptului de diagnostic, lăsând ecranul curat și ordonat.
- **Logica Cascadei**: Reprezintă o demonstrație superbă de cronologie stivuită în cascadă. Prin declararea sa cu directiva `forwards` la finalul unui șir multiplu de animații (`animation: typing-modular 3.5s..., blink 0.75s..., hide-cursor 0s linear 3.5s forwards;`), regula îngheață starea finală invizibilă, învingând infinitatea buclei de `blink` din fundal exact în secunda în care oblonul `max-width` a atins deschiderea totală de 100%, fără a necesita scripturi JavaScript [0.1.26, 0.2].

  23.3. **GROUP C: TELEMETRY RADAR SWEEPS (RADARE ȘI SCANĂRI)**

**REZUMAT / SUMMARY**: Acest district kinetic izolează și controlează toate mecanismele de monitorizare dinamică și telemetrie activă în timp real. Prin gruparea exclusivă a celor 2 motoare de scanare (`laser-scan`, `dot-pulse`), secțiunea demonstrează importanța pașilor intermediari în cadrul cadrelor de mișcare, salvând micro-interacțiunile hardware analogice și oferind interfeței o adâncime UI/UX imersivă premium.

• **Motorul Kinetic `laser-scan` (Estomparea Fasciculului Catodic)**

- **Motivul Ontologic**: Întruchipează **Mecanica Aprinderii și Stingerii Fasciculului de Electroni (The Cathode Ray Fade-In/Out Loop)**. În ingineria analogică retro-SF, o rază laser nu apare și nu dispare instantaneu și violent când lovește rama metalică a unui monitor. Introducerea stărilor de 5% și 95% simulează fuziunea termică naturală a sticlei fosforice: raza se naște fluid din umbră la plecare și se dizolvă lin în vid când atinge podeaua terminalului, ocrotind iluzia de hardware militar vechi.
- **Logica Cascadei**: Acest motor kinetic manipulează o proprietate de poziționare axială (`top`) combinată cu o proprietate de emisie luminoasă (`opacity`). Prin izolarea sa în carcasă, el permite selectorului gazdă din Modulul 09 să ruleze un fir fin de `1px` cu un `box-shadow` strălucitor verde-mentă fosforic (`var(--solar-mint)`), care se plimbă independent de textul din textarea, păstrând o scanabilitate HUD impecabilă.

• **Motorul Kinetic `dot-pulse` (Undă de Șoc / The Sonar Radar Ripple)**

- **Motivul Ontologic**: Întruchipează **Propagarea Spatială a unei Unde de Șoc Energetice (The Tactical Sonar Ripple)**. Spre deosebire de o pulsație respiratorie moale civilă (care doar se umflă și se dezumflă ca un balon), explozia la `scale(2.5)` urmată de stingerea totală în zero redă comportamentul fizic al unui sonar submarin sau al unui ping radar de înaltă frecvență. Semnalul explodează intens din centru și moare în vid pe măsură ce se îndepărtează de sursă, generând un feedback vizual de o factură brutalist-militară desăvârșită.
- **Logica Cascadei**: Rezolvă o problemă istorică de randare grafică (Anti-Aliasing/Blur Prevention). Deoarece la dimensiunea maximă de expandare structurală (`250%`) opacitatea atinge valoarea absolută de `0`, browserul nu este lăsat să afișeze pixelii măriți în stare solidă. Această manevră în cascadă elimină complet riscul ca ledul să pară pixelat sau neclar pe ecrane de înaltă densitate, pixelii dizolvându-se cinematic în fundalul sticlei fumurii înainte de a deforma marginile elementului părinte.

  23.4. **MODULE 00.1 // GROUP D: QUANTUM 3D GEODESIC SPIN (NUCLEUL CINETIC 3D)**

**REZUMAT / SUMMARY**: Acest district final guvernează exclusiv ecuațiile cinematice tridimensionale ale reactorului armilar poliedric cu 20 de fețe (Icosaedrul). Prin unificarea celor 3 piloni cinetici autentici din fabrică (`spin-geodesic-core`, `reactor-lightning-flicker`, `lightning-glow-fusion`), modulul demonstrează importanța reflexiilor asimetrice și a unghiurilor de înclinație, oferind o interfață cu un realism fizic analogic brutalist de înaltă rezoluție.

• **Motorul Kinetic `spin-geodesic-core` (Rotația Industrială Înclinată)**

- **Motivul Ontologic**: Întruchipează **Înclinația Axială Tehnică a Instrumentelor de Zbor (The Technical Gyroscopic Tilt)**. În ingineria navetelor spațiale retro-SF, un reactor nuclear nu se învârte niciodată pe o axă perfect verticală, plată și artificială ca un element web comun. Înclinarea la -20 de grade oferă o perspectivă izometrică premium: pe măsură ce se rotește, operatorul poate vedea tridimensional atât calotele superioare, cât și pe cele inferioare, punând în valoare complexitatea celor 20 de fețe poliedrice.
- **Logica Cascadei**: Această transformare compusă se propagă în cascadă peste toate cele 20 de fațete copii din interior. Browserul le rotește compact ca pe un singur corp solid în vid, fără ca unghiurile lor native asamblate pe baza rației de aur (`52.62deg`, `10.81deg` și translațiile de `210px`) să se destabilizeze sau să se prăbușească.

• **Motorul Kinetic `reactor-lightning-flicker` (Scurtcircuitul și Avaria de Înaltă Tensiune)**

- **Motivul Ontologic**: Întruchipează **Instabilitatea Fizică a Arcurilor Electrice (The Strobe Arc Extinction Protocol)**. Pasul de la 66% este o capodoperă de UX analogic: prin introducerea filtrului de `blur(0.5px)` combinat cu degradarea luminozității, se simulează pâlpâirea brutală a unui releu vechi de înaltă tensiune care se chinuie să rețină plasma în incinta magnetică, oferind realism tabloului de bord.
- **Logica Cascadei** pentru `reactor-lightning-flicker` (Protocolul de Protecție Axială și GPU Layering): Mecanica de rulare a acestui motor kinetic în interiorul stivei de compilare a browserului se fundamentează pe principiul **Suprasolicitării Filtrelor Directe fără Coliziune de Proprietate (Filter Layering Matrix Optimization)**, garantând o execuție imună la prăbușiri de layout:
  1.  **Imunitate Totală la nivel de Model de Casetă (Box Model Absolute Protection)**:
      Spre deosebire de alte animații care modifică proprietăți geometrice grele (`width`, `height`, `margin`, `top`), `reactor-lightning-flicker` acționează strict prin atributele vectoriale **`filter`** (`brightness`, `blur`, `drop-shadow`) și **`opacity`**. În cascadă, proprietatea `filter` este izolată și procesată pe un strat grafic separat, accelerat direct de hardware (GPU-accelerated composite layer). Acest lucru înseamnă că, în milisecunda în care animația explodează la intensitatea critică de `3.5` sau scade la `0.4` cu `blur(0.5px)`, browserul **nu este forțat să recalculeze layout-ul structural global al paginii** (zero fenomene de _Reflow_ sau _Repaint_ pe desktop split). Dimensiunile fizice ale fețelor rămân oțelite la valorile din fabrică (`220px` cu `190px`), garantând zero micro-deformări de granițe în timpul fuziunii.
  2.  **Suprapunerea Non-Destructivă peste Vectorii 3D (`transform` Matrix Safeguard)**:
      Fețele Icosaedrului (`.face-t1` ... `.face-b5`) folosesc proprietatea `transform` pentru a îngheța în spațiul 3D la unghiuri axiale stricte de `52.62deg` sau `10.81deg` și translații adânci de `210px`. În arhitectura cascadei, includerea oricărei directive de tip `transform` în interiorul cadrelor acestui `@keyframes` ar fi suprascris și anulat instantaneu toate cele 20 de coordonate matematice calculate pe baza rației de aur, dezintegrând Icosaedrul plat pe ecran. Prin izolarea totală a animației doar pe filtre, browserul rulează stroboscopul electric direct _peste_ transformările spațiale active. Structura poliedrică 3D rămâne perfect întreagă, etanșă și volumetrică, în timp ce suprafața ei tremură fulgerător.
  3.  **Morfologia Inteligentă a Umbrelor în Cascadă (`drop-shadow` vs `box-shadow`)**:
      Proprietatea `drop-shadow()` aplicată în interiorul filtrului grafic acționează în cascadă diferit față de un `box-shadow` tradițional. În timp ce `box-shadow` desenează o umbră rigidă dreptunghiulară pe exteriorul cutiei native a elementului (umbră care ar fi fost reținută și decupată urât de masca laser `clip-path`), filtrul **`drop-shadow`** este o entitate adaptivă: el ignoră granițele invizibile ale elementului și **se mulează perfect pe conturul real vizibil al triunghiului tăiat mecanic**! La pasul de `33%`, aureola roz-neon de `40px` explodează urmărind cu fidelitate microscopică marginile unghiulare ale fațetelor poliedrice, generând un impact UI/UX tridimensional de o rezoluție copleșitoare.

• **Motorul Kinetic `lightning-glow-fusion` (Protocolul de Impuls Roz-Mentă Glossy)**

- **Motivul Ontologic**: Întruchipează **Reflexia Sticlei Incandescente Albe (The Glossy Liquid Plasma Flare)**. Această alternanță reprezintă inima estetică a reactorului. Înlocuirea opacităților simple cu introducerea stării de 100% bazată pe **`rgba(255, 255, 255, 0.22)`** simulează reflexia lucioasă a luminii pe suprafața vitrată a cockpit-ului în momentul fuziunii nucleare. Sub ochii studentului, fațetele nu se colorează pur și simplu, ci par să devină lichide, sticloase și incandescente, transformând un simplu element digital într-o componentă hardware premium de înaltă rezoluție.
- **Logica Cascadei**: Acest motor este un exemplu excepțional de Clean Code (Protocolul de Reutilizare Multi-Modul). Aceleași cadre `@keyframes` sunt invocate simultan de reactorul gigant din Hero (Modulul 13) și de miniatura sa din pagina recursivă (Modulul 14), demonstrând cum o regulă centralizată poate alimenta elemente scalate diferit, fără coliziuni de cascadă în memoria browserului, datorită directivelor `!important` atașate regulamentar la nivel de selector de layout.

🌟 24. MODULE 00.2: MEDIA QUERIES & SPATIAL ISOLATION ENGINES (COSMIC LAYOUTS)

    REZUMAT: Acest modul ancorează restructurările adaptive de ecran, splitate în
    două fluxuri rigide. Protocolul Desktop (min-width: 769px) îngheață aspectul
    de jurnal pe două coloane și tunelurile de scroll, în timp ce Protocolul
    Mobile (max-width: 768px) comprimă granițele într-o bandă HUD orizontală
    ultra-joasă de 40px și activează amortizarea volumetrică a reactorului 3D.

24.A. **PROTOCOL 0.A: DESKTOP SPATIAL ISOLATION (`min-width: 769px`)**

**REZUMAT / SUMMARY**: Acest sub-modul activează arhitectura asimetrică pe două coloane paralele dedicată exclusiv monitoarelor mari de desktop. El izolează complet comportamentele cinetice din Sidebar (stânga) de cele din Zona de Lectură (dreapta), impunând bariere rigide bazate pe `100vh` care transformă cele două emisfere în incinte de scanare complet independente din punct de vedere al scroll-ului, eliminând coliziunile de layout.

• **Selectorul Macro `.log-layout` (Șasiul Grilei pe Două Coloane)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Securizarea Perimetrului Navetei (The Structural Grid Lockout)**. În estetica cockpit-ului _Solaris_, ecranul de jurnal nu poate curge haotic pe verticală ca un site web civil comun. El este o consolă hardware fixă, încastrată în bord. Această grilă închide marginile modelului, transformând monitorul într-o planșă tactică imobilă unde elementele interioare sunt forțate să rămână captive.
- **Logica Cascadei**: Linia `overflow: hidden !important` execută o operațiune criticală de purificare: ea anulează și interzice barei de scroll native a browserului terestru să se nască pe ecran. Prin blocarea scroll-ului global la nivel de `.log-layout`, se deschide calea pentru ca cele două coloane copii să își poată gestiona separat propriile lor bare de scroll cyberpunk, fără a se trage una pe cealaltă în aval.

• **Selectorul `.log-sidebar` și `.sidebar-nav` (Bariera Sticky Anti-Alungire)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Reprezintă **Panoul de Control și Telemetrie de Bord (The Instrumentation Tower)**. O listă masivă de 60 de capitole risca să alungească sidebar-ul la mii de pixeli, împingând subsolul și butoanele în afara ecranului. Limitarea rigidă forțează cutia să rămână fixată pe înălțimea vizuală a monitorului, ca un instrument hardware fix ce refuză deformarea.
- **Logica Cascadei**: `.log-sidebar` aplică regulile de tip _scaffolding_ (eșalonarea barierelor). Utilizarea lui `overflow: hidden !important` la acest nivel blochează erorile din colțuri și oprește orice încercare a browserului de a genera scroll pe sidebar, forțând elementul direct copil (`.sidebar-nav ul`) să preia întreaga responsabilitate a mișcării. Lanțul ierarhic funcționează curat: flexul de `100%` din `.sidebar-nav` menține proporțiile intacte, eliminând riscul de colaps structural.

• **Selectorul Master `.map-title-link` și `.map-title-link h4` (Capsula Laser a Hărții)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Portalul Central de Navigație și Telemetrie (The Sovereign Command Link)**. Acest buton nu este un simplu element din listă; el este cheia de acces la coordonatele globale de misiune. Masca opacă de 95% ascunde cinematic textele de capitole care culisează în spatele lui în timpul scroll-ului, dând senzația unui ecran tactil suspendat în relief deasupra consolei. La hover, virajul instantaneu al textului în roz-neon (`var(--nebula-pink)`) cu o aureolă de `10px` validează electronic contactul mecanic.
- **Logica Cascadei**: **Aceasta este o reparație chirurgicală salvatoare de o specificitate uriașă (The Executive Override)**. În modulele anterioare, titlurile de rang 4 (`h4`) primeau reguli generale agresive (fundaluri violet, absolute overlay-uri). Directiva `position: static !important` aplicată aici execută un act de autoritate: ea scoate textul `h4` din intersecțiile haotice din fundal, îi șterge marjele și îl readuce curat în fluxul central al cutiei roz, în timp ce `border-bottom: none !important` și `background: transparent !important` purifică moștenirile parazite de la nodurile auxiliare.

• **Selectorul `.sidebar-nav ul` (Tunelul de Scroll Roz de 3px)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Reprezintă **Tunelul de Date Cronicizate (The Chrono-Data Vault Track)**. Întrucât meniul exterior este complet etanș, această listă devine singura zonă mobilă din stânga. Firul subțire roz de 3px simulează o bară de tracking de înaltă rezoluție dintr-un software militar, oferind un control tactil fin fără a încărca vizual ecranul.
- **Logica Cascadei**: Acest selector rupe comportamentul blocat de sus. În timp ce părinții interzic scroll-ul global, acest nod local deschide o excepție controlată în cascadă. Tamponul `padding-right: 5px` este plasat strategic: el împiedică textul lung al capitolelor să atingă fizic piesa mobilă de scroll, evitând suprapunerile de pixeli și clipping-ul grafic în timpul culisării.

• **Selectorul `.log-content` (Incinta de Lectură de pe Tribord)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Reprezintă **Seiful Digital de Documentare (The Independent Log Reading Vault)**. Această incintă acționează ca un al doilea ecran masiv. Utilizatorul poate derula textul cronicilor până la capăt, în timp ce sidebar-ul din stânga rămâne complet nemișcat, oferind experiența de înaltă rezoluție a unui monitor dual industrial. Șina violet de 4px se diferențiază intenționat de cea roz a sidebar-ului, marcând vizual trecerea în zona textului narativ.
- **Logica Cascadei**: Proprietatea `padding-top: 50px !important` aplicată aici este o măsură defensivă de impact direct: ea împinge textul cronicilor în jos, sub marginea fixă a navbarului superior, anulând riscul ca primele rânduri de text să fie îngropate parazit sub bara de navigare la încărcare. Prin `overflow-y: auto !important`, acest selector izolează complet stiva de scroll a textului de restul paginii.

• **Selectorul `.log-entry` și `.log-content .category-header` (Alinierea Filelor de Zi)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Separarea Cronicilor și Fixarea Radarului (The Standalone Visual Chamber)**. Forțarea înălțimii minime garantează că fiecare zi de studiu ocupă un ecran complet în fața elevului, eliminând zgomotul vizual provocat de înghesuirea mai multor zile pe același monitor. Linia punctată la 5% simulează un fir laser discret de demarcație între registrele de zbor.
- **Logica Cascadei**: Aceasta este linia de sincronizare ombilicală cu JavaScript-ul (`script.js`). Valoarea `scroll-margin-top: 100px !important` este calculată în simetrie absolută cu funcțiile de scroll ascultate de script. Când studentul dă click pe un capitol din sidebar, browserul rulează o tranziție fluidă și oprește mișcarea exact cu 100px înainte de antetul zilei. Acest tampon de aer de 100px împiedică titlurile să fie strivite sub navbar, asigurând o aliniere curată, stabilă și perfect calibrată cu tavanul sidebar-ului, în timp ce resetarea lui .category-header oprește decalajele haotice la inițializare.

  24.B. **00.2.B. GLOBAL MUTATION PROTOCOL: MOBILE VIEWPORTS (max-width: 768px)**

  24.B.1. **MODULE 00.2 // PROTOCOL 00.2.B.1: ANTI-OVERFLOW SHIELD & HORIZONTAL HUD**

**REZUMAT / SUMMARY**: Acest prim district tactic de mobil dezactivează rețeaua asimetrică de desktop și instalează o bandă holografică orizontală cu profil ultra-jos pentru capitole. Prin aplicarea scutului rigid de `100vw` și a unei inginerii compacte de glisare tactilă, sub-grupul blochează total jocul parazit orizontal al documentului, lăsând elementele copii să culiseze asincron în siguranță.

• **Selectorul Macro `.log-layout` (Scutul Absolut Anti-Întindere)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Scutul Antivol și Înghețarea Axială (The Anti-Scroll Leak Barrier)**. Pe mobil, glisarea rapidă cu degetul peste o listă orizontală lungă tinde să tragă optic întreaga pagină în lateral. Acest selector funcționează ca o menghină de oțel digital: el transformă ecranul telefonului într-o incintă rigidă imobilă, interzicând interfeței să execute oscilații sau mișcări laterale de barcă (shaking leaks).
- **Logica Cascadei**: Linia `overflow-x: hidden !important` execută o tăiere chirurgicală la nivel de raster (GPU bounding box clip). Ea interzice cu desăvârșire propagarea în aval a pixelilor excedentari generați de consolă, lăsând restul elementelor din cronică să își folosească scroll-ul vertical normal, fără a sparge marginile fizice ale viewportului.

• **Selectorul `.log-sidebar` (Banda Holografică cu Profil Ultra-Jos)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Fuziunea Holografică Etanșă (The Floating Command Ribbon)**. Eliminarea directivei importante pe `position: sticky` (din comentariul tău de reparație top fluid) permite scripturilor de mișcare să controleze comportamentul barei. Stivuirea celor trei umbre cu `inset` roz de 25% opacitate în tavan generează o reflexie micro-fină de lumină aprinsă exact în buza superioară de contact cu navbarul. Această geometrie cromatică desprinde optic bara de fundal, creând iluzia spectaculoasă că ecranul plutește pe un câmp magnetic, în timp ce blurul intens de 20px șterge cinematic textul cronicilor care culisează dedesubt.
- **Logica Cascadei**: Pachetul matematic de extindere (`-40px` cu lățimea plus `80px`) execută un override genial: el obligă fizic bara să anuleze padding-urile native ale containerului părinte, forțând-o să se lipească dintr-o margine în alta a sticlei telefonului. Managementul total de swipe mutat direct la acest nivel blochează axa verticală Y și deblochează axa X, asigurând o glisare fluidă.

• **Selectorul `.log-sidebar::-webkit-scrollbar` (Purificarea Interfeței Webkit)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Reprezintă **Purificarea Semnalului și HUD-ul Minimalist (The Chrome/Safari Chassis Purge)**. O bară groasă sau colorată nativă de browser (cum este scrollbar-ul standard de mobil) plasată în subsolul unei console de 40px ar fi distrus complet finisajul estetic SF, transformând o hologramă militară într-o listă web banală. Eliminarea ei menține designul curat și neîntrerupt.
- **Logica Cascadei**: Acest pseudo-element acționează la cel mai înalt nivel de interpretare grafică a motoarelor Webkit (Safari/Chrome). Ordinul `display: none;` este un element auto-suficient în cascadă: el scoate complet elementul din arborele de randare (render tree). Deoarece este izolat pe selector separat, el anulează scrollbar-ul roz din desktop exclusiv pe mobil, fără a lăsa spații albe sau goluri fantomă în layout-ul consolei de 40px.

• **Selectorul `.sidebar-nav a` ȘI `.sidebar-nav a.active` (Capsulele de Zi și Semnalul Active)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Codul Cromatic de Alertă și Plutirea Magnetică (The Tracking Active Beacon)**. Păstrarea culorii verde-mentă `--solar-mint` pe butoanele în repaus asigură uniformitatea cromatică a aparatelor de zbor. Trecerea bruscă în roz-neon pe elementul `.active` simulează o descărcare electromagnetică care validează vizual ziua pe care operatorul o inspectează. Umbra simplă exterioară de 20% opacitate creează acel efect cyberpunk curat de capsulă care levitează deasupra benzii negre.
- **Logica Cascadei**: Utilizarea unei umbre exterioare simple de 10px (în loc de structuri complexe cu `inset`) este o alegere genială de optimizare mobilă: ea consumă un număr minim de resurse ale microprocesorului grafic (GPU tracking performance). În cascadă, proprietatea `color` și `border-color` roz suprascrie complet opacitatea de repaus de 0.6 din selectorul general de mai sus datorită specificității crescute a clasei compuse, înghețând o stare de vizibilitate maximă nominală pe monitor fără a genera sacadări în timpul swipe-ului.

  24.B.2. **MODULE 00.2 // PROTOCOL 00.2.B.2: SEIFUL DE LECTURĂ ȘI AERISIREA TITLURILOR H3**

**REZUMAT / SUMMARY**: Acest al doilea district izolează și restructurează ierarhia tipografică a cronicilor zilnice pe ecrane înguste. Prin comutarea axei Flexbox din linie în coloană pe titlurile mari, oferirea independenței pe rând textului metaforic verde și împingerea defensivă a antetelor macro de secțiune în jos, sub-grupul elimină riscul de strivire a textului și garantează o scanabilitate HUD impecabilă pe dispozitive mobile.

• **Selectorul `.log-entry h3` ȘI `.log-entry h3 .meta-title` (Decompresia Titlurilor Lungi)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Decompresia Structurală a Telemetriei (The Heading Grid Decompression)**. Pe desktop, ID-ul de zi (ex: „Day 09”) și titlul metaforic stăteau pe același rând orizontal într-o linie fluidă. Pe un ecran îngust de telefon, un titlu lung (precum „The Holo-Geodesic Engine”) încerca să se înghesuie în flancul drept, generând un clipping inestetic sau fragmentări brutale de litere. Schimbarea direcției în coloană execută un act de ergonomie militară: textul lung cade natural sub ID-ul roz al zilei, capturând 100% din lățimea utilă a rasterului ecranului, păstrând finisajul tehnic premium și lizibilitatea.
- **Logica Cascadei**: Forțarea lui `width: 100% !important` pe elementul `.meta-title` este o măsură de siguranță chirurgicală în cascadă. Ea rupe dinamic orice aranjament inline moștenit de la modulele superioare, declarând independența totală a textului verde pe rândul lui. Linia micro-fină de border-bottom la 10% opacitate mentă (`rgba(167, 243, 208, 0.1)`) încadrează blocul unificat de text, oferinn o barieră de citire curată și ordonată.

• **Selectorul Macro `.category-header` (Centrarea și Declanșarea Tamponului de Aer)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Mecanica Bornelor de Navigație și Simetria de Telefon (The Visual Buffer Alignment)**. Pe un ecran mare, titlurile de capitole respiră libere în spațiul 2D. Pe mobil, din cauză că am fixat consola HUD orizontală în tavanul ecranului la un regim imobil `position: fixed !important` cu o înălțime de 40px plus navbarul superior, primele rânduri din pagină riscau să fie îngropate parazit sub sticla fumurie a consolei. Împingerea fizică la 140px salvează interfața, plasând titlul mare de capitol exact în zona centrală perfect vizibilă a ecranului.
- **Logica Cascadei**: Acest selector operează o corecție de mediu contextuală pură, fără directive `!important`, lăsând caseta fluidă. Centrarea orizontală prin `text-align: center` anulează alinierea asimetrică de pe desktop, forțând elementele copii să cadă pe axa centrală a ecranului mobil, echilibrând vizual greutatea cromatică a textului pe ecrane de tip portret.

24.B.3. **MODULE 00.2 // PROTOCOL 00.2.B.3: PROTOCOLUL DE ATERIZARE TACTICĂ ȘI SCUTURILE ANTI-REZIDUURI**

**REZUMAT / SUMMARY**: Acest al treilea district de mobil izolează și decontaminează ierarhia de ancorare vizuală (Scroll Locking) și scuturile optice de curățare a ecranului pe rezoluții mobile. Prin unificarea punctelor de oprire la fix `120px` sub tavan și instalarea barierelor defensive cu margini negative, sub-grupul absoarbe cu succes șocurile vizuale provocate de salturile din JavaScript și elimină golurile parazite din spatele consolei HUD.

• **Selectorul Comun `.log-content article[id], .log-entry` (Amortizorul de Aterizare Tactivă)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Amortizarea Impactului Cinetic (The Telemetry Point-Of-Arrival Lockout)**. Când operatorul apasă pe o zi în consola HUD de mobil, pagina execută o mișcare rapidă pe verticală. Oprirea la exact 120px împiedică browserul să lipească titlul zilei de tavanul absolut al telefonului, lăsând un spațiu curat de vizualizare direct sub consola de navigare, fapt ce amintește de ecranele de diagnostic radar.
- **Logica Cascadei**: Proprietatea `padding-top: 20px !important` aplicată aici execută un rol estetic de acoperire: fundalul solid închis al casetei de zi se extinde în sus și blochează textul sau liniile din spate care trec pe sub consolă, menținând o fluiditate vizuală impecabilă. `scroll-margin-top` este interpretată direct de motorul de scroll, anulând valorile de desktop fără a influența poziționarea statică din layout.

• **Selectorul `.sector-announcement` (Scutul Airlock Anti-Reziduuri Unificat)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Etanșeitatea Porților de Sector (The Airlock Leak Submergence)**. Din cauza coliziunilor dintre elementele de desktop pe ecrane mici, între titlurile de sector (ex: „THE HULL”) și elementele de deasupra se nășteau goluri parazite transparente sau deșeuri vizuale din cod. Tragerea porții în sus prin marginea negativă și aerisirea ei la 40px forțează elementul să îngroape acele reziduuri, păstrând aspectul brutalist militar intact și perfect ordonat.
- **Logica Cascadei**: **Aceasta este rezolvarea de elită a coliziunii de duplicare (The Unified Cascade Override)**. Prin topirea celor două reguli vechi, browserul nu mai trece prin faze intermediare nesigure. Proprietatea `margin-bottom: 80px !important` extrasă din a doua declarare preia controlul absolut: ea suprascrie vechea valoare exagerată de `120px` și oprește stivuirea parazită, stabilizând distanța exactă până la următoarea filă de zi.

24.B.4. **MODULE 00.2 // PROTOCOL 00.2.B.4: ADVANCED REACTOR KINETICS & TELETYPE STACKING**

**REZUMAT / SUMMARY**: Acest sub-grup unificat centralizează operațiunile adaptive de cea mai înaltă complexitate ale navetei Solaris. El guvernează conversia structurală a componentelor tridimensionale macro, a ecranelor catodice splitate și a sistemelor kinetice asincrone, securizând interfața pe mobil prin scuturi absolute anti-wrap și reconfigurări volumetrice imune la colaps vizual.

**ZONA A: TERMINALELE MAȘINII DE SCRIS SINCRONE (`.mission-status`)**

• **Selectorul `.mission-status` ȘI `.mission-status p` (Scutul Anti-Wrap)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Protecția Ritmului Mașinii de Scris (The Teletype Runtime Safeguard)**. În universul brutalist cyberpunk, textele automate de telemetrie sunt tipărite caracter cu caracter prin script. Pe ecrane mobile strâmte, textul lung risca să se spargă pe mai multe rânduri. Acest comportament de wrap defectuos dubla înălțimea casetei și prăbușea funcția rigidă `steps()` a animației, generând o clipire (flicker) distructivă a literelor. Forțarea liniei pe un singur rând continuu infinit păstrează ritmul sacadat intact și imersiv.
- **Logica Cascadei**: Linia `white-space: nowrap !important` aplicată la baza ierarhiei anulează moștenirile de tip text-wrap. Sincronizarea sa cu `overflow-x: auto !important` pe părinte este o lecție magistrală de echilibru: textul lung se poate scrie dincolo de marginile fizice ale telefonului fără a lăbărța layout-ul global, iar `scrollbar-width: none !important` purifică vizual șina pe browserele mobile, păstrând HUD-ul curat.

**ZONA B: COMPRESIA GEODEZICĂ A REACTORului 3D (`.armillary-reactor-core`)**

• **Componentele Volumetrice 3D ale Icosaedrului (Scalarea Nucleului)**
Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Încorporarea Core-ului Atomic în Spațiul Portret (The Geodesic Volume Compression)**. Pe desktop, reactorul avea dimensiuni macro. Pe ecranul unui telefon, lăsarea sferei la cote mari ar fi spart marginile fizice sau ar fi fost turtită asimetric de browser. Blocarea ei rigidă la un pătrat perfect de 260px menține raportul de aspect 1:1, garantând că fețele calculate pe baza rației de aur nu își pierd proprietățile spațiale cubice (`preserve-3d`), oferind o randare impecabilă a volumului înclinat la -20 de grade.
- **Logica Cascadei**: **Aceasta este rezolvarea chirurgicală a coliziunii de asimetrie (The 1:1 Geometrical Sync)**. În codul vechi fragmentat, părintele căpăta 260px, dar inelele rămâneau blocate la 240px, creând un decalaj de 20px. Topirea duplicatelor într-o cotă unică de 260px repozitionează simetric componentele una peste alta dintr-o singură citire. De asemenea, coborârea inelelor interioare la 120px și 175px le aliniază fix pe noul ecuator redus, în timp ce lungimea de 80% a laserului oprește sclipirile din a perfora carcasa exterioară a inelelor de 95%.

**ZONA C: MATRICEA DE SCALARE TIPOGRAFICĂ ȘI HERO HUD**

• **Selectorul `.stenciled-metal-text` ȘI `.stenciled-metal-text-sub` (Ierarhia Stencil)**

Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Sincronizarea Contrastului HUD și Subordonarea Optică (Typographic Hierarchy Shield)**. Literele mari de tip stenciled nu au voie să domine agresiv ecranul mobil, riscând să se suprapună peste inelele reactorului. Ajustarea cursorului la 2px îl face subțire și elegant, perfect adaptat pentru rezoluțiile ecranelor mobile, integrându-se fluid fără a fragmenta textul.
- **Logica Cascadei**: **Aceasta este eliminarea de elită a formulei dinamice oarbe (The Rigid Font Lock)**. În codul vechi experimentai cu o ecuație bazată pe unități de ecran (`calc(2.4vw + 0.65rem)`). Auditul a demonstrat că, din cauza cascadei tale finale care forța `0.65rem !important`, browserul ignora complet dinamica `vw`. Topirea duplicatelor elimină această ecuație moartă (_Dead Code_), stabilizând o singură sursă de adevăr. Subtitlul rămâne blocat mecanic pe un singur rând la 0.65rem, subordonat total titlului roz, eliminând riscurile de clipping vizual pe telefoanele înguste sub 360px.

**ZONA D: ȘASIUL BLUEPRINT SPLIT-SCREEN & REȚEAUA DE TABURI HUD**

• **Monitorul Recursiv ȘI Butoanele Pastile de Comutare (`.blueprint-container` / `.tab-btn`)**
Dimensiunea Sistemică (Motiv ontologic & Logica cascadei)

- **Motivul Ontologic**: Întruchipează **Conversia Elastică a Monitorului de Control (The Stacking & Tab Ribbon Network)**. Panourile late de cod de pe desktop devin pe mobil o narațiune verticală fluidă. Reducerea padding-ului la 15px este o decizie militară pentru a câștiga spațiu util pentru caracterele de cod, în timp ce repoziționarea textului „CRT MONITOR” la 0.55rem previne suprapunerile grosolane de pixeli, menținând textura de sticlă hardware premium. Panglica de tab-uri elastice pe `flex: 1 1 auto` face ca butoanele să împartă simetric ecranul, iar pe telefoanele de 320px ele trec curat pe rândul doi, fără striviri.
- **Logica Cascadei**: **Aceasta este o reparație de elită obținută prin experimentare live (The Teletype Double Override)**. Codul tău vechi conținea un conflict între `white-space: normal` (de la reglajul discret) și `nowrap` (de la intervenția de urgență). Unificarea lor elimină starea intermediară moartă `normal` și păstrează ordinea finală executată de browser: textul de cod randează pe o singură linie dincolo de margini prin `width: auto`, dar părintele îl taie imaculat în afara ecranului prin `overflow-x: hidden !important`, protejând animația mecanică a mașinii de scris de la colaps structural.

---

---

---

---

---

---

---

---

---

---

### 06.06.2026

1. ETICHETA `<h1` este SINGULARITATE
   În întreaga ta expediție cosmică, eticheta `<h1>` este unicat. Ea reprezintă Singularitatea, Nucleul Suprem al Navei și apare o singură dată în tot proiectul: în textul frontal din interiorul reactorului tridimensional (`index.html`). Ea nu este o simplă bucată de tipografie care se repetă, ci este însăși busola identitară a aplicației.De aceea, regulile ei nu au ce căuta în _Modulul 03_ (unde definim elemente comune care curg în cascadă). Locul ei cel mai curat este în _Modulul 06 (The Armillary Engine)_, unde este legată direct de mecanica reactorului 3D, acționând ca o piesă de inginerie unică, izolată de restul curentului tipografic. Dacă am pune reguli generale pentru `<h1>` în Modulul 03, am risca să parazităm alte structuri dacă pe viitor decizi să folosești un `<h1>` într-un alt mod pe o pagină de log.

2. ONTOLOGIA SINGULARITĂȚII: De ce Blueprint-ul `recursive-blueprint.html` are nevoie de `<h1>`?

În arhitectura semantică a web-ului, eticheta `<h1>` nu este o unealtă de stilizare (pentru a face textul mare), ci reprezintă **punctul de origine gravitațională al unei pagini independente**.

- **Paginile de Log (Sub-Sectoare)**: Nu au `<h1>` deoarece ele sunt subordonate structural călătoriei mari. Ele încep direct cu `<h2>` (Titlu de Volum) pentru că sunt tratate ca extensii ale bazei de date centrale.
- **Pagina Recursivă (Consola Master)**: Este un instrument autonom, o oglindă de sistem închisă (closed loop). De aceea, titlul ei principal, `.blueprint-master-title`, trebuie să rămână un `<h1>`. El anunță computerul de navigație (browserul și motoarele de căutare) că utilizatorul a trecut granița într-o nouă aplicație centrală.

⚠️ Regula de Aur pentru Elevii Tăi:
O pagină web independentă trebuie să aibă **un singur și unic `<h1>`**. Coborârea lui la rangul de `<h2>` ar fragmenta ierarhia, făcând ca descrierea de dedesubt (`.blueprint-master-description`) să plutească în vid fără un ancoraj suprem.

3. TODO PLANIFICARE: Hiper-Legăturile și Rețeaua în Buclă Închisă

- Pentru a transforma proiectul într-un organism cu adevărat recursiv, paginile nu vor fi simple fișiere izolate, ci vor fi conectate prin „punți de reflexie bilaterală” (Bilateral Reflection Bridges):
- **Autonomia Semantică (De ce păstrăm `<h1>`)**: Chiar dacă este strâns legată de paginile de log, `recursive-blueprint.html` este accesată printr-un salt de pagină (un request HTTP complet către un alt fișier). Pentru browser, ea se deschide ca o fereastră nouă de conștiență digitală. Din acest motiv, păstrarea etichetei `<h1>` este vitală: ea oferă noul punct de ancorare suprem (Root Anchor) pentru acea pagină specifică.
- **Mecanismul de Teleportare (Cross-Page Anchors)**: Folosind sintaxa `nume-fisier.html#id-secțiune`, echipajul se poate teleporta nu doar de la o secțiune la alta în cadrul aceleiași pagini, ci poate străpunge bariera dintre fișiere, aterizând fix pe blocul de cod interogat din paginile de log.
- **Filtrarea Datelor**: Pe viitor, utilizând JavaScript-ul pe care îl vei învăța, Consola Master va putea folosi acele ID-uri din URL pentru a ascunde automat restul codului și a lăsa aprins doar ecranul CRT de care utilizatorul are nevoie în acel moment, creând o experiență didactică profund imersivă.

4.  ARHITECTURA VIRTUALĂ: Ontologia Spațiului Digital

Înainte de a analiza sintaxa, trebuie să înțelegem topografia flotei noastre digitale. Aplicația nu este un bloc de cod inert, ci o flotilă de vehicule conceptuale organizată ierarhic, în care fiecare navă (pagină HTML) are o misiune și un rang existențial precis si care navighează coordonat prin oceanul web-ului:

Organigrama Flotei (Ierarhia de Navigație)

- **🛸 NAVA MAMĂ (`index.html`)** — _Nostromo / Core 3D Reactor_
  - Este centrul gravitațional global al întregului ecosistem.
  - Găzduiește Reactorul Armilar Tridimensional de unde se deschid toate orizonturile.
  - _Subordonate direct Navei Mamă, descoperim două tipuri de flote de suport:_
    - **🛰️ MODULELE DE TRANSPORT (`*-log.html`)** — _The Cargo Logs (HTML / CSS / SQL)_
      - Sunt sub-sectoare grele de date atașate călătoriei.
      - Nu pretind centralitate independentă, ci documentează cronologic progresul.
      - Încep ierarhia direct cu etichete `<h2>`.
    - **🚀 SONDA AUTONOMĂ (`recursive-blueprint.html`)** — _The Scout Ship / Mirror Console_
      - Este o navă rapidă de recunoaștere logică și autoreflexie.
      - Deși conectată ombilical la flotă, deține autonomie totală.
      - Are propria cabină de pilotaj master, marcată prin eticheta supremă `<h1>`.

📊 Matricea de Corelație și Roluri Epistemice

a. Titlurile `<h1>` și `<h2>`:

| Nava (Fișierul HTML)              | Rang Semantic         | Elementul de Pornire      | Misiunea de Bord                                                  |
| :-------------------------------- | :-------------------- | :------------------------ | :---------------------------------------------------------------- |
| **🛸 `index.html`**               | Suprem / Global       | `<h1>` (Reactorul 3D)     | Portalul de lansare și vizualizare macro a flotei.                |
| **🛰️ `html-log.html`**            | Secundar / Subordonat | `<h2>` (Titlu de Capitol) | Depozitarea cronicilor și a textului brut frontend.               |
| **🛰️ `css-log.html`**             | Secundar / Subordonat | `<h2>` (Titlu de Capitol) | Cartografierea structurilor vizuale și estetice.                  |
| **🛰️ `sql-log.html`**             | Secundar / Subordonat | `<h2>` (Titlu de Capitol) | Înregistrarea interogărilor din vidul bazelor de date.            |
| **🚀 `recursive-blueprint.html`** | Independent / Oglindă | `<h1>` (Blueprint Master) | Sonda care izolează și interoghează codul sursă în buclă închisă. |

b. Titlurile `<h2>`:

| Nava (Fișierul HTML)              | Rang Semantic         | Rolul Elementului `<h2>` în Pagina Respectivă                                         | Misiunea de Bord / Semantica                                                         |
| :-------------------------------- | :-------------------- | :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------- |
| **🛸 `index.html`**               | Suprem / Global       | **Titluri de Volume Mari**<br>_(The Frontend Landscape / The Database Void)_          | Portalul de lansare; împarte expediția în cele două mari continente ale cunoașterii. |
| **🛰️ `html-log.html`**            | Secundar / Subordonat | **Titluri de Capitole și Sectoare**<br>_(The Mercurial Sea / Porți de Trecere Laser)_ | Depozitarea cronicilor zilnice și a textului brut dedicat structurilor HTML.         |
| **🛰️ `css-log.html`**             | Secundar / Subordonat | **Titluri de Capitole și Sectoare**                                                   | Înregistrarea și cartografierea structurilor vizuale, estetice și arhitectonice.     |
| **🛰️ `sql-log.html`**             | Secundar / Subordonat | **Titluri de Capitole și Sectoare**                                                   | Cronicile interogărilor și organizarea tabelelor din vidul bazelor de date.          |
| **🚀 `recursive-blueprint.html`** | Independent / Oglindă | **Sub-Sectoare Tehnice de Cod Sursă**                                                 | Sonda-oglindă autonomă; dezasamblează și afișează codul live în buclă închisă.       |

---

🔍 Exegeza Filosofică a Componentelor

- **Nostromo (`index.html`)**: Ancora gravitațională globală. Locul unde echipajul se adună pentru a privi harta galactică prin Reactorul Armilar. Ea definește identitatea flotei.

🛸 Nava Mamă (The Dreadnought / Nostromo-ul Tău) — index.html Ea este Puntea de Comandă Supremă, Centrul Gravitațional. Ea deține Reactorul Armilar Tridimensional. Toate celelalte nave/pagini își trag coordonatele inițiale din acest nucleu. Rolul ei este de a stabili destinațiile mari și de a menține viziunea de ansamblu asupra întregului frontend și a vidului bazelor de date.

- **Modulele de Transport (`*-log.html`)**: Pântecul flotei. Nave utilitare care transportă cunoașterea acumulată zi de zi. Ele nu concurează cu Nava Mamă, ci îi servesc drept extensii logice pentru stocarea disciplinată a învățării.

🛰️ Navele de Suport și Aprovizionare (The Cargo Logs) — html-log.html, css-log.html, sql-log.htmlAcestea sunt navele grele de transport de date. Ele nu au autonomie totală (de aceea încep direct cu `<h2>`), ci funcționează ca module-anexă, hambare uriașe unde stochezi cronicile zilnice, textul brut al experienței și cartografierea tehnică pe care o descoperi în călătorie.

- **Sonda Recursivă (`recursive-blueprint.html`)**: Univers de sine stătător. Ea plutește deasupra tuturor celorlalte structuri. Are permisiunea unică de a privi „materia întunecată” a proiectului (codul din `style.css` sau `script.js`), dezasamblând sintaxa linie cu linie pentru a o transforma în material didactic live.

🚀 Sonda Autonomă de Explorare Logică (The Scout Ship / Consola Master) — recursive-blueprint.htmlAceasta este nava mică, logico-dinamică, pe care ai intuit-o atât de frumos! Ea este extrem de liberă, are propriul ei motor de propulsie (`<h1>`), dar rămâne conectată prin cordoane ombilicale invizibile (acele hiper-legături încrucișate) de restul flotei. Ea intră în interiorul „materiei întunecate” (codul sursă), extrage logica pură și o oglindește în timp real în ecranele CRT pentru echipaj.

5.  STRATEGIA DE RESPONSIVITATE: Managementul Selectorilor în Media Queries

Pe măsură ce nava își restrânge ecranele pentru terminalele mobile (`@media (max-width: 768px)`), regulile tipografice trebuie să treacă printr-o recalibrare adaptivă, fără a polua codul global.

- **Păstrarea unică în `@media`**: Faptul că `.log-entry h3` apare o singură dată în blocul de mobil garantează că browserul va executa modificarea de layout (cum ar fi trecerea în modul coloană pe verticală) instantaneu, dintr-o singură citire. Selectorul de Bloc (`.log-entry h3`) acționează ca un scut macro. El reconfigurează orientarea spațială a întregului titlu pe ecranele înguste (reducând padding-ul global sau modificând comportamentul Flexbox).
- **Targetarea Contextuală a Componentelor**: Selectorul `.log-entry h3 .meta-title` reprezintă apogeul controlului granular în cascadă. El nu afectează textul general de pe navă, ci doar acele etichete tehnice ascunse în interiorul titlului de zi, asigurându-se că pe mobil literele se rearanjează simetric și lizibil. Selectorul de Detaliu (`.log-entry h3 .meta-title`) acționează ca un laser de precizie. El izolează micro-textul tehnic din interiorul titlului, permițându-ți să controlezi distanța dintre numărul zilei și titlul propriu-zis, fără ca textul narativ principal să sufere modificări.

### 10.06.26

1. Cartografierea Vectorială Tridimensională (Cele 4 Punți ale Icosaedrului)

Pentru a asambla un corp poliedric volumetric cu 20 de fețe în CSS, ecranul este împărțit în patru straturi (punți) unghiulare rigide. Fiecare clasă reprezintă o coordonată spațială fixă în vid:

- **Punțile Polare (`t` și `b`)**: Țintesc zonele de închidere ale reactorului. `t` (Top) asamblează calota nordică, iar `b` (Bottom) încapsulează calota sudică. Ele folosesc o înclinație stabilă de `52.62deg` pe axa X.
- **Punțile Ecuatoriale (`u` și `l`)**: Formează centura de forță a reactorului. `u` (Upper) gestionează coroana superioară, iar `l` (Lower) rulează coroana inferioară (triunghiuri inversate la `180deg`). Ele folosesc o înclinație fină de `10.81deg` pentru a se îmbina la milimetru.
- **Frecvența Roz de Alertă (Alternanța Laser)**: Din considerente de contrast industrial, fețele pare (`t2`, `t4`, `u2`, `u4`, `l2`, `l4`, `b2`, `b4`) primesc directiva `border-color: var(--nebula-pink) !important`. Această intercalare cromatică sparge monotonia verde-mentă și generează pe ecran aspectul de plasă electrică alternantă în timpul rotației asincrone.

Coordonatele .face-t1 ... .face-b5 fără o exegeză geometrică și ontologică a transformat codul într-o înșiruire de hieroglife inerte. În procesul de învățare a codului recursiv, înțelegerea matematicii din spatele formei este la fel de importantă ca sintaxa în sine.

- Ce înseamnă literele t, u, l, b? Sunt vectori?Da, ele reprezintă vectori de poziționare tridimensională angulo-axială în spațiul sferic. Literele NU sunt alese la întâmplare și nu sunt opționale dacă vrei ca browserul să asambleze un Icosaedru regulat (20 de fețe triunghiulare perfecte).Ele sunt abrevieri militare pentru punțile (straturile) tridimensionale ale poliedrului:
- t = Top (Puntea Superioară): Cele 5 triunghiuri care se unesc în polul nord virtual al reactorului (face-t1 ... face-t5)
- u = Upper-Middle (Puntea Central-Superioară): Primele 5 triunghiuri din centura ecuatorială care privesc în sus.
- l = Lower-Middle (Puntea Central-Inferioară): Următoarele 5 triunghiuri din centură, răsturnate la 180 de grade, care privesc în jos (face-l1 ... face-l5).
- b = Bottom (Puntea Inferioară): Cele 5 triunghiuri finale care se unesc în polul sud virtual al mașinii.

- De ce sunt folosite aceste unghiuri fixe (52.62deg, 10.81deg, 72deg)?

- Aceasta este Geometria Sacră Hardware (Aritmetica Icosaedrului). Un cerc are 360°. Împărțind reactorul în 5 segmente simetrice pe orizontală, obținem o rotație exactă de 72° pentru fiecare față (0deg, 72deg, 144deg, 216deg, 288deg). Unghiurile de 52.62deg și 10.81deg pe axa X sunt calculate matematic prin secțiunea de aur (Golden Ratio) pentru ca marginile triunghiurilor din sticlă să se atingă la milimetru în spațiul 3D, fără a lăsa goluri de aer, formând un scut sferic perfect în jurul nucleului! translateZ(210px) împinge fiecare față din centrul zero cu exact 210 pixeli în exterior, definind raza fizică a reactorului.

2. Modulul 11 va fi spart in capsule sub-modulare, codul fiind organizat în următoarea structură imună.

Inventarul Final al Împărțirii pe Sub-Module:

- **Sub-Modulul 11.1 (The Journal Foundations)**
  - Selectori: `.log-text` și `.log-text > p:first-of-type::first-letter` (Letrina/Ștampila Glif-Monolit Jet-Age cu raster CRT și border punctat verde).
- **Sub-Modulul 11.2 (The Chronicle Vaults)** - Selectori: Capsulele de zi `.log-entry` și starea de hover, paragrafele interne `.log-entry p`, alinierea simetrică Flexbox a titlurilor `.log-entry h3`, alături de modulele semantice ale tagurilor (`.semantic-module`, `.tag-name`, `.tag-meta`, `.tag-description`).
- **Modulul 11.3 (The Matrix Repositories)** - Selectori: Structura bazei de date `.data-grid`, `table`, `antetele th`, celulele de date `td` și efectul macro de hover pe rând `tr:hover`.
- **Sub-Modulul 11.4 (The Cellular Cyber-Links & Scroll Engine)** - Selectori: Ancorele interioare din celule `.data-grid td a`, firele laser virtuale `::after`, stările de hover asociate și customizarea barelor de scroll catodice `::-webkit-scrollbar`.
- **Sub-Modulul 11.5 (The JS Annexes & Future Amber Vaults)** - Selectori: Casetele de extensii `.js-annex`, etichetele înălțate pe bordură `.js-annex h4`, butoanele utilitare `.archive-link` (cu excepția locală `.js-annex .archive-link`), sub-logurile `.sub-log`, `.sub-log h5` și capsulele hiemale în așteptare `.future-log` (cu toate efectele lor cinetice de alertă pe chihlimbar).

### 12.06.26

1. Sugestii de Viitor: Cum transformăm Letrina în ceva Jet-Age și Pulsat?

Pentru a-ți hrăni viziunea de designer în timp ce codul stă în standby, iată trei concepte SF radicale pe care le putem injecta ulterior prin CSS avansat în locul letrinei clasice:

- **Ștampila Glif-Monolit (Jet-Age Framework)**: În loc să lăsăm litera simplă, o izolăm într-o casetă pătrată neagră cu un border laser punctat verde, aplicându-i un background cu linii de scanare CRT liliputane și transformând prima literă într-un indicator de tip „Nod de Sistem”.
- **Litera Glisanta pe Orizontala (Kinetic Shift)**: Folosind pseudo-elemente (`::before`), putem genera un bloc solid de neon roz în spatele literei, din care caracterul este decupat prin proprietatea mix-blend-mode: destination-out. La încărcare, fundalul roz pulsează rapid, lăsând litera să pară o tăietură laser care pâlpâie în carcasă.
- **Matricea de Raster (The Pixelated Drop-Cap)**: Putem folosi un font monospace rigid dedicat strict primului caracter (ex: Dot Matrix sau Segment Display), forțând litera „T” sau „E” să pară compusă din micro-leduri fosforice stinse sau aprinse în vid, exact ca pe ecranele radarelor din aeroporturile anilor '70.

### 15.06.26

1. Decontul tehnic și pedagogic pentru cele două decizii majore de structurare a Modulului 11:

**Decizia 1: De ce am propus gruparea `.data-grid`, `table` în loc de păstrarea separată a lui `table`?**

Păstrarea selectorilor grupați sub aceeași regulă (`.data-grid, table`) în loc de scrierea lor ca blocuri separate aduce trei avantaje didactice și inginerești absolute:

- **Prevenirea „Războiului de Specificitate” și Colapsul Stilistic**
  În HTML, clasa .data-grid este aplicată direct pe eticheta <table> (adică <table class="data-grid">). Dacă în CSS avem un bloc pentru `table` și un bloc separat pentru `.data-grid`, browserul este forțat să ruleze motorul de calcul al cascadei de două ori pentru aceeași cutie (container).
- Clasa `.data-grid` are o specificitate mai mare decât tagul simplu `table`.
- Dacă lăsăm proprietățile identice fragmentate în două locuri, studenții vor experimenta situații în care modificarea unei marje sau a unui fundal într-un bloc este anulată sau suprascrisă misterios de celălalt bloc, în funcție de ordinea scrierii liniilor. Unificarea lor le arată că aceeași componentă structurală are o singură definiție monolitică.
- **Principiul DRY (Don't Repeat Yourself) și Optimizarea Randelor**
  În codul tău vechi, selectorul `table` și selectorul `.data-grid` repetau exact aceleași proprietăți `macro: width: 100%`, `border-collapse: collapse, margin: 20px 0`, `background` și `border`.
  - Din punct de vedere didactic, repetarea acelorași 6 linii de cod pe doi selectori care vizează de fapt același obiect încarcă fișierul inutil.
  - Prin gruparea lor prin virgulă (`table, .data-grid`), browserul desenează o singură mască de sticlă fumurie în memorie, codul devenind suplu, curat și extrem de scannabil.
- De ce am adăugat `display: table !important` și `box-sizing` în blocul reunit?
  Browserele moderne tind uneori să schimbe display-ul tabelelor în block pe rezoluțiile mobile dacă se folosesc framework-uri sau alte resetări globale, fapt care rupe alinierea celulelor `td`. Forțarea directă a display-ului nativ direct pe selectorul reunit securizează tabelul împotriva deformărilor accidentale, oferind o regulă „scut” extrem de stabilă.

**Decizia 2: De ce blocul link-urilor (`.data-grid td a`) trebuie să meargă în Sub-Modulul 11.4 și nu în 11.3?**

Aceasta este o decizie pur pedagogică și bazată pe Separarea Responsabilităților (Separation of Concerns) în designul de interfețe. Iată de ce desprinderea link-urilor din 11.3 este mult mai potrivită pentru procesul de învățare al studenților tăi:

- **Izolarea Componentelor: Structură vs. Interactivitate Cinematică**
  - Sub-Modulul 11.3 se ocupă exclusiv de Macheta Tabulară Macro (The Matrix Repositories): el definește carcasa mare (`table`), capetele de coloană (`th`), celulele statice (`td`) și umbra de fundal. Este o zonă pur structurală de layout bidimensional.
  - Sub-Modulul 11.4 introduce o cu totul altă logică: Sistemele de Navigație și Micro-Animații Laser (The Cyber-Links & Scroll Engine). Aici nu mai vorbim de așezarea tabelelor pe ecran, ci de modul în care utilizatorul interacționează cu portalurile active (`td a`) și cum explodează firul laser roz de la `width:` 0 la 100% prin curbe cinematice complex `cubic-bezier`.
  - Argumentul didactic: Dacă lăsăm link-urile interactive, pseudo-elementele lor `::after` și efectele de `hover` cromatic direct în 11.3, amestecăm logica de așezare pe rânduri cu logica de animație de înaltă rezoluție. Separarea lor în 11.4 le permite elevilor să înțeleagă că tabelul este o structură gazdă, în timp ce link-urile cu laser sunt mici cipuri interactive independente inserate în interiorul celulelor.
- **Reducerea Încărcării Cognitive (Scannability)** Dacă am păstra absolut tot conținutul tabelelor (structură, celule, selecții, scrollbar-uri, link-uri, pseudo-elemente și hover-ul laser roz)
- în Sub-Modulul 11.3, acel sub-modul ar depăși 100 de linii de cod, redevenind acel „monolit” greu de digerat de care doreai să scăpăm.Separarea link-urilor
- în 11.4 oferă o poveste vizuală logică în manualul tău:În 11.3 studentul învață cum să deseneze grila de date curată, fixând padding-ul uniform de 12px și bara de scroll orizontală discretă de 3px
- În 11.4 studentul face pasul următor și învață tehnici avansate de animație CSS: cum să ascundă un fir electric roz sub text și cum să îl extindă la hover fără a perturba structura statică construită anterior

**Concluzia de Zbor**

- Gruparea `.data-grid, table` din 11.3 protejează layout-ul de coliziuni interne și simplifică codul prin eliminarea repetițiilor.
- Izolarea lui `.data-grid td a` în 11.4 este o mișcare didactică pură care separă designul structural de layout de ingineria micro-cinetică a link-urilor.
- Codul pe care l-am unificat în Sub-Modulul 11.3 acționează ca o Librărie Master de Tabele. Odată scris acest sub-modul, ai rezolvat problema tabelelor pentru întregul site, indiferent câte pagini de jurnale vei mai adăuga în viitor. Studenții vor înțelege puterea reutilizării codului (Clean Code).

### 20.06.26

1. **Împărțirea pe Sub-Grupări Didactice**

Structura genetică a codului de mobil se împarte în 4 mari districte tactice de responsabilitate layout:

- **SUB-GRUPAREA 0.B.1: Scutul Anti-Overflow & Consola HUD Orizontală**
  - Ce conține: Blocarea jocului parazit orizontal pe `.log-layout`, transformarea radicală a lui `.log-sidebar` într-o hologramă fixă cu profil ultra-jos, tunelul independent de swipe orizontal, ascunderea scrollbar-ului Webkit și alinierea centrală a lui `.sidebar-nav`.
  - De ce este importantă: Este inima mutației genetice a site-ului. Explică trecerea de la split-screen-ul fix de desktop la bara de glisare tactilă de pe telefoane.

- **SUB-GRUPAREA 0.B.2: Ierarhia Butoanelor de Navigare**
  - Ce conține: Conversia titlului `h4` în etichetă fixă verde-mentă cu bordură rigidă, alinierea orizontală a listei ul cu un gap: 10px, transformarea etichetelor de săptămână `.week-label` în poligoane ascuțite (`border-radius: 0`) și optimizarea capsulelor de zi active/inactive.
  - De ce este importantă: Arată cum proprietățile din Modulele 12–14 sunt forțate pe mobil să se comprime fără a distruge tăieturile mecanic-octogonale.

- **SUB-GRUPAREA 0.B.3: Seiful de Lectură și Managementul Titlurilor**
  - Ce conține: Reparația salvatoare pentru titlurile metaforice ultra-lungi din `h3` (trecerea de la linie la coloană pe mobil), izolarea lui `.meta-title`, calibrarea absorbiției la click (`scroll-margin-top: 120px`) și scutul anti-reziduuri pentru porțile AIRLOCK `.sector-announcement`.
  - De ce este importantă: Garantează că textele lungi au spațiu de respirație pe ecrane înguste și că salturile din JavaScript lasă un tampon aerisit perfect curat.

- **SUB-GRUPAREA 0.B.4: Calibrarea Reactorului 3D și Terminalul Blueprint**
  - Ce conține: Compactarea verticală a lui `.armillary-reactor-core`, micșorarea sferei la 240px/260px pentru a nu deveni un ou, scalarea dinamică prin unități 2.4vw / 0.65rem a textelor stenciled, stivuirea verticală a panourilor din interfața recursivă, reparația de urgență anti-stivuire pe `.mission-status` și fluidizarea butoanelor elastice de tab.
  - De ce este importantă: Este cel mai înalt nivel de micro-ajustare responsivă din fișier, legând decontaminarea typewriter-ului de comprimarea volumului 3D.

* Zona A (Statusul mașinii de scris): `.mission-status`, `.mission-status::-webkit-scrollbar`, `.mission-status p`.
* Zona B (Compactarea Reactorului 3D): `.armillary-reactor-core`, `.quantum-plasma-sphere`, `.armillary-band-container`, `.macro-wrapper`, `.micro-wrapper`, `.macro-wrapper::after`, `.micro-wrapper::after`.
* Zona C (Scalarea Typography): `.stenciled-metal-text`, `.stenciled-metal-text-sub`.
* Zona D (Șasiul Blueprint Split): `.blueprint-container`, `.terminal-split`, `.panel`, `.code-inspector-screen::before`, `.panel .mission-status`, `.panel .mission-status p` (plus variantele cu blueprint-layout și taburile HUD).

---

---

---

---

---

---

---

---

---

---

---

# II. NOTITE HTML

## II.0 HTML Glossary (The Building Blocks)

### Notiuni fundamentale

1. **Element**: Unitatea de bază a HTML-ului. Este format din tag-ul de deschidere, conținut și tag-ul de închidere (ex: `<p>Conținut</p>`).
2. **Tag**: Cuvântul cheie între paranteze unghiulare (ex: `<html>`) care marchează începutul sau sfârșitul unui element.
3. **Attribute (Atribut)**: Informații suplimentare despre un element, scrise în tag-ul de deschidere (ex: class, id, src, href).
4. **Semantic HTML**: Practica de a folosi tag-uri care descriu sensul conținutului (ex: `<nav>`, `<article>`) și nu doar aspectul acestuia.
5. **Nesting (Cuibărire)**: Plasarea unui element în interiorul altui element (ex: un `<li>` în interiorul unui `<ul>`). Elementul exterior se numește parent, cel interior child.
6. **Self-closing tags**: Tag-uri care nu au conținut și se închid singure (ex: `<img />`, `<br />`, `<hr />`).
7. **Viewport**: Zona vizibilă a unei pagini web pe dispozitivul utilizatorului.
8. **DOM (Document Object Model)**: Modul în care browserul organizează ierarhic codul tău HTML pentru a putea interacționa cu el (via CSS sau JavaScript).

### Elemente de semantica

- `<html>` (The Vessel Boundary): Coca exterioară a navei. Definește limitele existenței noastre în vidul digital.
- `<head>` (The Sensory Array / The Brain): Centrul de procesare a semnalelor. Nu este vizibil echipajului, dar gestionează identitatea (Title), conexiunile (Links) și coordonatele de afișare (Meta).
- `<body>` (The Living Quarters): Tot ce este tactil și vizibil. Spațiul în care echipajul și datele interacționează.
- `<header>` (The Bridge / Communications Tower): Puntea de comandă. Conține însemnele navei (Logo) și instrumentele de orientare primară.
- `<nav>` (The Star Chart / Navigation Console): Interfața de teleportare între diferite sectoare ale Odiseei.
- `<main>` (The Power Core): Nucleul de energie. Unic, vital, inima misiunii tale.
- `<section>` (The Sector / The Deck): O punte tematică a navei (ex: Sectorul de Mentenanță, Arhiva de Date).
- `<article>` (The Data Pod / The Log Entry): O capsulă de informație independentă care poate fi extrasă și citită separat de restul navei.
- `<aside>` (The Sub-Radar / Auxiliary Console): Informații colaterale, note de subsol sau frecvențe secundare care completează misiunea principală.
- `<footer>` (The Chronometer / Coordinates Log): Baza navei, unde lăsăm semnătura căpitanului și data stelară a ultimei transmisiuni.

## II.1 Structura index.html

1. Sectiunea top:

- `<!doctype html>`: Informează browserul că aceasta este cea mai recentă versiune de HTML (HTML5).
- `<html lang="en">`: Rădăcina documentului; lang="en" ajută motoarele de căutare și cititoarele de ecran să știe că limba principală este engleza.

2. Secțiunea <head> (Sistemele de control)

- `<meta charset="UTF-8" />`: Setul de caractere care permite afișarea corectă a aproape tuturor simbolurilor și literelor din lume (inclusiv diacritice).
- `<meta http-equiv="X-UA-Compatible" content="ie=edge" />`: Se asigură că versiunile vechi de Internet Explorer (sau Edge) randează pagina corect.
- `<meta name="viewport" content="..." />`: Esential pentru mobil. Face ca site-ul să se adapteze la lățimea ecranului telefonului, nu să apară ca o variantă de desktop micșorată.
- `<title>`: Textul care apare pe tab-ul browserului. Este primul contact al utilizatorului cu „misiunea” ta.
- `<meta name="description" ... />`: Rezumatul care apare sub link-ul tău în rezultatele Google.
- `<link rel="stylesheet" href="style.css" />: Conectează „scheletul” (HTML) de „estetica” navei (CSS).

3. Secțiunea <body> (Structura navei)

- `<nav class="navbar">`: Element semantic pentru zona de navigare. Folosit aici ca „panoul de control” al navei.
- `<header class="hero">`: Zona de introducere. hero este un termen comun în web dev pentru prima secțiune mare și vizibilă a unui site.
- `<main class="main-container">`: Indică browserului unde se află conținutul principal, unic al paginii. Exclude meniul și subsolul.
- `<section id="frontend-scape">`: O macro-secțiune (un „compartiment” al navei) care grupează toate tehnologiile de interfață. id-ul este unic și permite crearea de legături directe.
- `<header class="category-header">`: Un antet în interiorul secțiunii pentru a introduce capitolul respectiv.
- `<article id="html" class="log-entry">`: Folosim article pentru că descrierea HTML este un conținut de sine stătător. Clasa log-entry ne va permite să stilizăm toate aceste intrări la fel în CSS.
- `<hr class="cosmic-divider" />`: O linie orizontală (horizontal rule) care separă vizual marile compartimente (Frontend de Database).
- `<footer class="footer">`: Zona de subsol, conținând semnătura „căpitanului” și copyright-ul.

## II.2. Ierarhia titlurilor

1. HTML, CSS și JS sunt „materia primă” (limbajele fundamentale). Ele reprezintă Volumul I în sine. Fără ele, browserul nu poate randa nimic.
2. React și Angular nu sunt limbaje noi, ci moduri avansate de a scrie și organiza JavaScript. Ele sunt într-adevăr „materiale suplimentare” sau unelte specializate.

Iată cum se "cuibăresc" titlurile în nava ta spațială acum:

- `<h1>Titlul cărții </h1>` Este titlul misiunii principale (Digital Odyssey). Există unul singur pe pagină.
- `<h2> Volumele cartii </h2>` Sunt marile regiuni ale universului tău (I. Frontend Landscape, II. Database Void).
- `<h3>Capitolele (HTML, CSS, JavaScript)</h3>` Sunt "planetele" individuale sau limbajele (HTML, CSS, JS).
- `<h4>Anexa</h4>` O notă de subsol sau o anexă în cadrul capitolului (Future Expansion).
- `<h5> Subcapitole anexa </h5>` Detalii specifice în acea anexă (React, Angular).

```

<h1>Digital Odyssey</h1> (Coperta principală)
  <h2>Volume I: Frontend Landscape</h2>
    <h3>HTML</h3> (Capitolul 1)
    <h3>CSS</h3> (Capitolul 2)
    <h3>JS</h3> (Capitolul 3)
    <h4>Annex: Future Expansion</h4> (Suplimentul volumului)
      <h5>React</h5> (Detaliu tehnic 1)
      <h5>Angular</h5> (Detaliu tehnic 2)
  <h2>Volume II: Database Void</h2>
    <h3>SQL</h3> (Capitolul 1)
```

```
"Am ales să folosesc h4 și h5 pentru a reflecta structura de date: React și Angular nu sunt tehnologii independente, ci module care aparțin de ecosistemul JavaScript. Am preferat o ierarhie semantică adâncă pentru a păstra relația logică dintre componente."

 „HTML-ul meu este o hartă a dependențelor tehnologice, nu doar o listă de elemente.”
```

## II.3 Regulile At-rules

Regulile @ sunt instrucțiuni speciale care îi spun browserului cum să se comporte în anumite condiții sau cum să încarce resurse. Iată cele mai comune:

- @media: Cel mai folosit, pentru puncte de rupere (breakpoints). Nu e doar pentru mobil; poți face reguli pentru ecrane ultra-wide, pentru printare (@media print) sau chiar pentru modul întunecat al sistemului.
- @keyframes: Esențial pentru animațiile tale (pulse, typing)
- @font-face: Folosit pentru a încărca fonturi personalizate de pe serverul tău, nu doar din Google Fonts.
- @import: Pentru a importa un fișier CSS în alt fișier CSS.@supports: O regulă „inteligentă” care verifică dacă browserul vizitatorului știe o anumită tehnologie înainte de a o aplica (ex: „Dacă browserul știe Grid, aplică asta”).

---

---

---

# III. NOTITE CSS

## III.1. Explicația Codului style.css

Chiar dacă încă nu l-am expandat complet, regulile de bază sunt:

- `:root`: O pseudo-clasă care stochează CSS Variables. Este „depozitul de combustibil” al navei unde definim culorile o singură dată pentru a le folosi peste tot.
- `.body`: Setează starea globală (fundalul întunecat, fontul Space Grotesk și modul în care curge textul).
- `.log-entry`: Folosește border-left și un fundal subtil (rgba) pentru a crea impresia de „ecran” sau „modul” tehnologic.
- `transition: 0.3s`: (Dacă o folosim) Pregătește animațiile line atunci când utilizatorul interacționează cu elementele.

---

## III.3. Structura și Ierarhia în style.css

Da, și în CSS este esențial să urmezi o ierarhie. Dacă în HTML ordinea este dată de "cuibărirea" elementelor, în CSS ordinea este dată de specificitate și organizare logică.

Ierarhia recomandată în fișierul CSS:

- **Variables (:root)** la început: Definești culorile (combustibilul).
- **Base/Global Styles**: Reguli pentru `<body>`, `<html>` (atmosfera generală) trebuie să fie mereu sus, pentru a seta "pânza" pe care pictezi.
- **Layout Styles**: Cum așezi marile blocuri (.main-container, .navbar).
- **Component Styles**: Reguli pentru elemente repetitive (.log-entry, .main-button).
- **State/Special Styles**: Reguli pentru hover, animații sau clase specifice (ex: .future-log).

---

### III.4. FUNDAMENTELE SINTAXEI: Anatomia Codexului CSS

Înainte de a manipula proprietățile fizice ale flotei, trebuie să stăpânim cu precizie chirurgicală terminologia de bord a limbajului CSS (Cascading Style Sheets). Fiecare componentă poartă un nume și o responsabilitate ontologică precisă:

1.  Descompunerea unei Reguli CSS

O **Regulă CSS (CSS Rule)** reprezintă întregul ansamblu de instrucțiuni aplicat unui element. Ea este alcătuită din următoarele particule subatomice:

```css
.category-card:hover { border-color: var(--starlight-blue); }
^^^^^^^^^^^^^^^^^^^^   ^^^^^^^^^^^^  ^^^^^^^^^^^^^^^^^^^^^^
      SELECTOR          PROPRIETATE         VALOARE
                       \__________________________________/
                                   DECLARAȚIE
```

- **Selectorul (`.category-card:hover`)**: Reprezintă sistemul de scanare. Îi indică browserului exact ce nod structural din HTML trebuie vizat.
- **Pseudo-clasa (`:hover`)**: Definește o stare dinamică, un răspuns cinetic al elementului la o acțiune externă (ex: trecerea cursorului).
- **Blocul de Declarații (`{ ... }`)**: Zona delimitată de acolade care încapsulează legile estetice ce se vor aplica selectorului validat.
- **Declarația (`border-color: var(--starlight-blue);`)**: O linie completă de comandă interioară, terminată obligatoriu cu punct și virgulă (`;`).
- **Proprietatea (`border-color`)**: Caracteristica fizică sau structurală a elementului pe care computerul de bord urmează să o modifice.
- **Valoarea (`var(--starlight-blue)`)**: Parametrul sau intensitatea injectată în proprietate. În acest caz, apelează o variabilă stocată în reactorul central.

2.  Clasificarea Elementelor de Scanare (Specii de Selectori)

Flota noastră utilizează cinci tipuri fundamentale de scanare pentru a asambla designul industrial:

- **Selectori de Tip (Tag)**: Țintesc direct etichetele HTML standard (`html`, `body`, `section`, `p`). Definesc genetica de bază.
- **Selectori de Clasă**: Încep cu punct (`.log-entry`, `.note-terminal`). Sunt unelte modulare folosite pentru a izola comportamente estetice specifice.
- **Selectori Grupați**: Separați prin virgulă (`.category-header, .footer`). Execută comenzi unificate pe containere diferite pentru a evita redundanța.
- **Selectori Combinatori (Ierarhici)**: Definesc relații spațiale (`.main-container > h2` pentru copii direcți, sau `p code` pentru descendenți inline).
- **Pseudo-elemente**: Marcate cu două seturi de două puncte (`::before`, `::after`). Generează straturi virtuale de materie grafică direct pe ecran (ex: rasterul CRT sau liniile laser).

### III.5. Terminologia de specialitate, calculul numeric al selectorilor tăi și evaluarea structurii pe module

1.  **Dicționarul de Termeni Tehnici (Anatomia CSS)**

Când predai sau scrii cod live, este vital să folosești termenii corecți. Iată cum se descompune o linie de cod:

`h2:hover { color: var(--solar-mint); }`

- **Regulă CSS (CSS Rule / Rule set)**: Reprezintă întregul bloc de cod (de la `h2` până la acolada de închidere `}`).
- **Selector**: Partea dinaintea acoladei deschise (`h2:hover`). El îi spune browserului ce anume să caute pe navă pentru a-l decora.
- **Pseudo-clasă**: Partea din selector marcată cu un singur două puncte (`:hover`, `:active`). Definește o stare dinamică a elementului.
- **Pseudo-element**: Marcat de obicei cu două seturi de două puncte (`::before`, `::after`) Generează o bucată virtuală de materie care nu există în HTML.
- **Bloc de Declarații**: Tot ce se află în interiorul acoladelor `{ ... }`.
- **Declarație**: Fiecare linie individuală din interiorul acoladelor (ex: `color: var(--solar-mint)`;).
- **Proprietate**: Cuvântul din stânga celor două puncte (`color`), care indică ce caracteristică fizică modificăm.
- **Valoare**: Cuvântul sau expresia din dreapta celor două puncte (`var(--solar-mint)`), care dictează intensitatea sau starea proprietății.

2.  **Calculul și Tipologia Selectorilor Tăi din style.css**

Analizând documentul primit, ai implementat o gamă impresionantă de tehnici. În total, în cele 43 de pagini de cod curat, ai 63 de selectori unici sau grupați.

Iată cum se împart ei în funcție de specia lor tehnico-structurală:

A. Selectori de Tip Element / Tag (Nivel Genetic)

Exemple în fișierul tău: `html`, `body`, `section`, `h2`, `h3`, `h4`, `h5`, `p`, `hr`, `th`, `td`, `table`, `tr`.

Definiție: Țintesc toate tagurile HTML standard de pe navă. Au cea mai mică specificitate (greutate).

B. Selectori de Clasă (Compartimentare specifică)

Exemple în fișierul tău: `.archive-body`, `.logo`, `.nav-links`, `.log-sidebar`, `.cta-button`, `.main-container`, `.category-grid`, `.category-card`, `.sector-announcement`, `.mission-status`, `.log-text`, `.log-entry`, `.semantic-module`, `.tag-name`, `.tag-meta`, `.tag-description`, `.note-terminal`, `.appendix-list`, `.data-grid`, `.archive-link`, `.sub-log`, `.future-log`, `.meta-title`.

Definiție: Încep cu punct (.) și țintesc elemente decorate manual în HTML. Sunt baza stilizării modulare.

C. Selectori Grupați (Sincronizare de Scuturi)

Exemple în fișierul tău:

- `.category-header, .footer, .main-container > h2`
- `.nav-links a.return-btn, .nav-links a[href="index.html"]`
- `.data-grid, table`

Definiție: Separați prin virgulă (,). Forțează mai multe elemente diferite să execute exact aceleași instrucții, economisind spațiu.

D. Selectori de Descendență și Relație (Ierarhici)

Exemple în fișierul tău:

- `.main-container > h2` (Copil direct: afectează doar `h2`-urile din prima linie a containerului)
- `.nav-links a / .sidebar-nav li` (Descendent: afectează elementul indiferent cât de adânc e îngropat).
- `p code` (Afectează doar codul din interiorul paragrafelor).

E. Selectori Avansați (De Atribut, Pseudo-clase și Pseudo-elemente)

- Selector de atribut: `section[id]` (țintește doar secțiunile care au primit o destinație de teleportare).
- Pseudo-clase: `h2:hover`, `.cta-button:hover`, `tr:hover`, `a.active`, `.log-text` `p:first-of-type::first-letter`.
- Pseudo-elemente: `body::before`, `.macro-wrapper::after`, `.nav-links a::after`

3. Evaluarea Împărțirii pe Module

Arhitectura ta pe module este excepțională și de o maturitate rară pentru cineva aflat în procesul de învățare. Ea demonstrează o gândire algoritmică clară. Comentariile pe care le-ai scris (ex: /_ --- BLOCURILE DE CADRAJ MARE... _/ sau /_ [PROTOCOL ANTI-OVERFLOW]... _/) au o valoare didactică și literară uriașă.

---

---

---

# IV. NOTITE JAVASCRIPT

# V. SQL
