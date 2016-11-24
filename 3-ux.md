---
layout: page
title: Principii de UX
permalink: /ux/
---

## Ce este _User Experience_
_**User Experience (UX)** reprezintă totalitatea emoțiilor, crezurilor, preferințelor, percepțiilor, răspunsurilor fizice și psihologice, precum și comportamentele și realizările utilizatorului, generate în timpul folosirii și după folosirea unui produs sau serviciu web._

_User Experience Design-ul_ (UXD) îmbunătățește experiența utilizatorului vizavi de acel produs sau serviciu web. O bună experiență a utilizatorului va crește automat gradul de adopție al acelui produs sau serviciu web.

_User Experience Designer-ul_ este acea persoană care înțelege scopurile și contextul de folosire al potențialilor utilizatori ai unui produs sau serviciu web. El folosește această înțelegere pentru a proiecta un produs sau serviciu web în limita constrângerilor tehnice, legale sau de business specifice acelui produs sau serviciu web.

Un _User Experience Designer_ folosește următoarele metode și discipline:
* _user (experience) research_
* _product design_
* _interaction design_
* arhitectura informației (_information architecture_)
* _usability_
* _prototyping_
* _interface design_
* _content strategy_
* psihologie

**Una din regulile de bază ale _User Experience Design-ului_ spune că [_You are not your user_](http://uxmyths.com/post/715988395/myth-you-are-like-your-users)**. Cu alte cuvinte, dacă într-un proiect web sărim peste etapa de _user experience research_ și pornim de la presupunerile pe care noi le avem despre utilizatori, atunci riscăm să construim un produs sau serviciu web pe placul și nevoile noastre (ale echipei de dezvoltare), nu pe placul și nevoile utilizatorilor finali ai acelui produs sau serviciu web.

_User Experience Designer-ul_ este dator să testeze pe utilizatori reali dacă produsul sau serviciul web proiectat de el este ușor de folosit și intuitiv pentru utilizatori. Acest lucru se face prin teste cu utilizatorii, folosind metode:
* cantitative: _task success rate_, _time on task_, _error rate_, proporția de folosire a navigării versus căutării pe website etc
* calitative: măsurarea nivelului de satisfacție a utilizatorilor, așteptările și performanțele raportate etc

_User Experience Designer-ul_ este dator să livreze (în primul rând, dar nu numai) un prototip al produsului sau serviciului web. Odată prototipul validat de client (beneficiarul indirect al proiectului) și testat pe utilizatori, proiectul poate trece în următoarea fază de dezvoltare: _visual design_, în care prototipul capătă forma vizuală finală ce va defini acel proiect (_branding_, fonturi, culori, forme, imagini etc).

Această pagină trece în revistă doar cele mai importante principii de UXD.

## Cum definim o pagină "usable"?
O pagină web se poate numi "usable" dacă ea răspunde simultan la următoarele 3 întrebări:

1. Cum ajung pe această pagină?
2. Ce pot face pe această pagină? (acțiuni posibile)
3. Unde pot să ajung pornind de la această pagină?

Răspunsul la aceste 3 întrebări îl aflăm (în primă etapă) dacă definim mai întâi **arhitectura informației** (_Information Architecture - IA_) pentru acel website (aplicație).

## 1. Arhitectura Informației (IA)
Este arta și știința de a organiza informația pe un website, un intranet, o comunitate online sau un produs software, cu scopul de a asigura partea de [usability](https://en.wikipedia.org/wiki/Usability) și [findability](https://en.wikipedia.org/wiki/Findability) [2].

O bună Arhitectură a Informației ajută oamenii să înțeleagă mediul înconjurător și să găsească rapid ceea ce căutau, fie că este vorba de _orientarea în lumea reală_ (într-un supermarket, o gară, un spital etc) sau de _orientarea în lumea digitală_ (un website, o aplicație software). [3]

Arhitectura Informației are 5 mari componente [4]:
* Sisteme organizaționale: modul în care organizăm informația pe un website
* Sisteme de etichetare (_labels_): modul în care reprezentăm informația
* Sisteme de navigare: modul în care putem naviga într-un website
* Sisteme de căutare: modul în care căutăm informația pe un website
* Tezaure, vocabulare controlate, metadata: componente-suport pentru navigare și căutare, _invizibile_ utilizatorului.

### 1.1 Tipuri de sisteme organizaționale
* alfabetic (de evitat în [majoritatea cazurilor](https://www.nngroup.com/articles/alphabetical-sorting-must-mostly-die/), în favoarea celor de mai jos)
* cronologic
* geografic
* după subiect (_topic_)
* după activitate (_task_)
* după auditoriu (tipuri de utilizatori)
* după formatul informației (audio, video, documente text etc)
* după clasificări sociale (generate de utilizatori): de exemplu, _free tag-urile_ de pe Flickr
* o combinație între două sau mai multe moduri de mai sus. [4]

### 1.2 Tipuri de etichetare (_labels_)
* link-uri contextuale (_hyperlinks_)
* titluri de paragrafe (_headings_)
* opțiuni de navigare (exemple de etichete standard: _Site map_, Contact, FAQ, _Help_ etc)
* termeni de index (_keywords_, _tags_ etc)
* iconițe (etichete vizuale).

**Cum putem crea etichete eficiente?**
* analizând conținutul website-ului
* cerând autorilor de conținut de pe website să propună etichete
* cerând sugestii de la utilizatorii avansați ai website-ului (aplicației) sau de la experții în acel domeniu
* folosind exerciții de _[card sorting](https://en.wikipedia.org/wiki/Card_sorting)_
* analizând _search log-urile_ de pe website (din aplicație)
* analizând _tag-urile_ generate de utilizatori. [4]

### 1.3 Tipuri de sisteme de navigare
* navigare globală (meniu global): unde mă aflu în cadrul website-ului?
* navigare locală: ce conținut pot găsi în vecinătatea paginii curente?
* navigare contextuală: ce conținut pot citi mai departe, pornind de la pagina curentă?
* navigări suplimentare: _site map-uri_, indecși de website, tutoriale pentru o activitate anume de pe website etc
* navigare socială: "Cele mai populare articole", "Ultimele articole accesate" etc. [4]

Navigarea globală poate fi:
* _broad and shallow_ (meniul global conține multe secțiuni, dar fiecare secțiune are un submeniu mic, de exemplu website-urile de știri de genul [nytimes.com](http://www.nytimes.com/)) 
* _narrow and deep_ (meniul global conține puține secțiuni, dar fiecare secțiune are un submeniu vast, de exemplu website-urile de comerț online de genul [amazon.com](https://www.amazon.com/)).

Ambele tipuri de navigare globală vin cu [avantaje și dezavantaje](https://www.nngroup.com/articles/flat-vs-deep-hierarchy/), prin urmare natura website-ului va determina tipul de navigare globală.

### 1.4 Sisteme de căutare
Este recomandat să oferi o funcție de _căutare în website_ dacă:
* website-ul conține foarte multe pagini (de ordinul zecilor)
* poți (și ai resursele necesare) să optimizezi sistemul de căutare în website (adăugarea de filtre pentru căutare avansată, afișarea rezultatelor căutării în funcție de relevanță/alte criterii, afișarea de sugestii pentru căutările care nu au generat niciun rezultat, indexarea rezultatelor de căutare pentru anumiți etc)
* website-ul este foarte fragmentat (de exemplu Amazon.com, Wikipedia.com)
* căutarea este un mod de a învăța nevoile utilizatorilor de pe website (vezi analiza _search log-urilor_ din paragraful anterior)
* utilizatorii se așteaptă să găsească o astfel de funcție pe website, prin natura website-ului 
* utilizatorii nu sunt dispuși să folosească navigarea pe website, deoarece nu se potrivește nevoilor lor.

**Pentru a proiecta o interfață de căutare bună, este necesar să:**
* iei în calcul nivelul de expertiză și motivare al utilizatorilor care caută pe website (de exemplu, "utilizator începător" versus "utilizator avansat")
* iei în calcul tipul de nevoie de informare (căutare avansată sau căutare simplă?)
* iei în calcul tipul de informație căutat (căutare de pagini, căutare pe texte, căutare pe anumite formate etc)
* iei în calcul cantitatea de informație căutată (câte rezultate de căutare să afișăm și în ce ordine, cum filtrăm rezultatele căutării pentru a restrânge căutarea la ceva mai specific etc).
* afișezi în pagina de _rezultate pentru căutare_ care au fost cuvintele care au definit căutarea (_search query_)
* explici de unde au venit rezultatele căutării (de pe ce pagină, din ce categorie de produse, etc)
* explici utilizatorului ce căutare a făcut și cum o poate reface (utilizând filtre, reformulând căutarea, folosind [operatori booleeni](http://libguides.mit.edu/c.php?g=175963&p=1158594), afișând numărul de rezultate întoarse de căutare etc)
* integrezi căutarea cu navigarea în website (de exemplu, prin afișarea categoriilor de produse sau a altui tip de ierarhie pe pagina cu rezultatele căutării)
* marchezi căutările care nu au generat niciun rezultat prin metodele standard (de exemplu, folosirea 
[paginii 404](https://en.wikipedia.org/wiki/HTTP_404) pentru paginile căutate care nu există pe website). [4]


### 1.5 Tezaure, vocabulare controlate, metadata
_Tag-urile metadata_ sunt folosite pentru a descrie documente, pagini, imagini, software, fișiere audio/video și alte obiecte de conținut, cu scopul de a îmbunătăți navigarea și extragerea de informații.

Vocabularele controlate sunt liste de termeni echivalenți ([synonym rings](https://en.wikipedia.org/wiki/Synonym_ring)) sau liste de termeni preferați (_[authority file](https://en.wikipedia.org/wiki/Authority_control)_).

Tezaurele sunt un tip de vocabulare controlate în care [relațiile de echivalență](http://eurovoc.europa.eu/drupal/?q=node/322), [de ierarhie](http://eurovoc.europa.eu/drupal/?q=node/323) și [de asociere](http://eurovoc.europa.eu/drupal/?q=node/325) sunt identificate cu scopul de a îmbunătăți extragerea informației. De exemplu, un tezaur despre vin pornește de la termenul "vin" și conține sub-termenii "vin roșu", "vin alb", care la rândul lor conțin sub-termenii "vin dulce", "vin sec", "vin demi-sec", care la rândul lor conțin sub-termenii specifici unui soi anume de vin ("Chardonnay", "Cabernet Sauvignon" etc). [4]

Aceste componente de IA sunt folosite de obicei când proiectăm baza de date a website-ului (aplicației).



## Bibliografie

1. [User Experience Design, Wikipedia](https://en.wikipedia.org/wiki/User_experience_design)
2. [Information Architecture, Wikipedia](https://en.wikipedia.org/wiki/Information_architecture)
3. [What is Information Architecture?](http://www.iainstitute.org/what-is-ia)
4. [Information Architecture: For the Web and Beyond](https://www.amazon.com/Information-Architecture-For-Web-Beyond/dp/1491911689)

