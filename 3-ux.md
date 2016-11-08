---
layout: page
title: Principii de UX
permalink: /ux/
---

## Ce este _User Experience_
**UX ("User Experience")** este **prima etapă** din dezvoltarea oricărui proiect web. Scopul ei este de a construi
un prototip (pentru o aplicație/website) care să reflecte atât nevoile utilizatorilor finali, cât și cerințele clientului.

**User Experience Designer-ul** este dator să strângă (prin _UX Research_) atât date despre nevoile și profilul utilizatorilor finali ai unei aplicații web,
cât și cerințele clientului (informații de ordin tehnic, legal sau business, care vor defini mulțimea posibilă de funcționalități dintr-o aplicație).

Acei **User Experience Designeri care sar peste etapa de _UX Research_ și trec direct la proiectarea interfeței** încalcă una din regulile de bază ale domeniul "UX",
care spune că [_You are not your user_](http://uxmyths.com/post/715988395/myth-you-are-like-your-users).

**User Experience Designer-ul** va folosi aceste date strânse și _experiența sa profesională (cunoștințe de arhitectura informației,
psihologie, interaction design, ergonomie, human-computer interaction etc)_ pentru a crea interfețe "usable"
(ușor de folosit, intuitive, care să servească scopurilor utilizatorilor finali în timpi rezonabili) [1].

**User Experience Designer-ul** va testa pe utilizatori reali dacă prototipul construit de el reprezintă într-adevăr o interfață "usable",
și va integra feedback-ul strâns de la acei utilizatori în noua versiune de prototip.

**După ce etapa de "UX" este încheiată, proiectul web poate trece în următoarea fază de dezvoltare: _visual design_ (UI)**, în care prototipul capătă forma vizuală finală ce va defini acel proiect (fonturi, culori, forme, imagini etc).

Deoarece **User Experience Design-ul include elemente din mai multe discipline (arhitectura informației, _interaction design_, _user research_, psihologie etc)**, este imposibil să acoperi toate principiile într-un singur ghid.

Această pagină trece în revistă doar cele mai importante principii de UX, după care să te ghidezi pentru a proiecta o pagină "usable".

## Cum definim o pagină "usable"?
O pagină web se poate numi "usable" dacă ea răspunde simultan la următoarele 3 întrebări:

1. Cum ajung pe această pagină?
2. Ce pot face pe această pagină? (acțiuni posibile)
3. Unde pot să ajung pornind de la această pagină?

Răspunsul la aceste 3 întrebări îl aflăm (în primă etapă) dacă definim mai întâi **arhitectura informației** (_Information Architecture - IA_) pentru acel website (aplicație).

## 1. Arhitectura Informației (IA)
Este arta și știința de a organiza informația pe un website, un intranet, o comunitate online sau un produs software, cu scopul de a asigura partea de [usability](https://en.wikipedia.org/wiki/Usability) și [findability](https://en.wikipedia.org/wiki/Findability) [2].

O bună Arhitectură a Informației ajută oamenii să înțeleagă mediul înconjurător și să găsească rapid ceea ce căutau, fie că este vorba de lumea reală (orientarea într-un supermarket sau într-o gară) sau de lumea online (un website, o aplicație software). [3]

Arhitectura Informației are 5 mari componente [4]:
* Sisteme organizaționale
* Sisteme de etichetare (_labels_)
* Sisteme de navigare
* Sisteme de căutare
* Tezaure, vocabulare controlate, metadata

### 1.1 Sisteme organizaționale
Reprezintă modul în care organizăm informația pe un website:
* alfabetic
* cronologic
* geografic
* după subiect (_topic_)
* după activitate (_task_)
* după auditoriu (tipuri de utilizatori)
* după formatul informației (audio, video, documente text etc)
* după clasificări sociale (generate de utilizatori): de exemplu, _free tag-urile_ de pe Flickr
* o combinație între două sau mai multe moduri de mai sus. [4]

### 1.2 Sisteme de etichetare (_labels_)
Reprezintă modul în care reprezentăm informația:
* link-uri contextuale (_hyperlinks_)
* titluri de paragrafe (_headings_)
* opțiuni de navigare (exemple de etichete standard: _Site map_, Contact, FAQ, _Help_ etc)
* termeni de index (_keywords_, _tags_ etc)
* iconițe (etichete vizuale).

Cum putem crea etichete eficiente?
* analizând conținutul website-ului
* cerând autorilor de conținut de pe website să propună etichete
* cerând sugestii de la utilizatorii avansați ai website-ului (aplicației) sau de la experții în acel domeniu
* folosind exerciții de _[card sorting](https://en.wikipedia.org/wiki/Card_sorting)_
* analizând _search log-urile_ de pe website (din aplicație)
* analizând _tag-urile_ generate de utilizatori. [4]

### 1.3 Sisteme de navigare
Reprezintă modul în care putem naviga într-un website (aplicație):
* navigare globală (meniu global): unde mă aflu în cadrul website-ului
* navigare locală: ce conținut pot găsi în vecinătatea paginii curente?
* navigare contextuală: ce conținut pot citi mai departe, pornind de la pagina curentă?
* navigări suplimentare: _site map-uri_, indecși de website, tutoriale pentru o activitate anume de pe website etc
* navigare socială: "Cele mai populare articole", "Ultimele articole accesate" etc. [4]

Navigarea globală poate fi:
* _broad and shallow_ (meniul global conține multe secțiuni, dar fiecare secțiune are un submeniu mic, de exemplu website-urile de știri de genul nytimes.com)
* _narrow and deep_ (meniul global conține puține secțiuni, dar fiecare secțiune are un submeniu vast, de exemplu website-urile de comerț online de genul Amazon.com).

Ambele tipuri de navigare globală vin cu [avantaje și dezavantaje](https://www.nngroup.com/articles/flat-vs-deep-hierarchy/), prin urmare natura website-ului va determina tipul de navigare globală.

### 1.4 Sisteme de căutare
Reprezintă modul în care căutăm informația pe un website (aplicație).

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
Reprezintă componente de arhitectura informației deseori _invizibile_ pentru utilizatorul unui website (aplicații). Au rol în a sprijini alte componente de arhitectura informației, cum ar fi navigarea și căutarea.

_Tag-urile metadata_ sunt folosite pentru a descrie documente, pagini, imagini, software, fișiere audio/video și alte obiecte de conținut, cu scopul de a îmbunătăți navigarea și extragerea de informații.

Vocabularele controlate sunt liste de termeni echivalenți ([synonym rings](https://en.wikipedia.org/wiki/Synonym_ring)) sau liste de termeni preferați (_[authority file](https://en.wikipedia.org/wiki/Authority_control)_).

Tezaurele sunt un tip de vocabulare controlate în care [relațiile de echivalență](http://eurovoc.europa.eu/drupal/?q=node/322), [de ierarhie](http://eurovoc.europa.eu/drupal/?q=node/323) și [de asociere](http://eurovoc.europa.eu/drupal/?q=node/325) sunt identificate cu scopul de a îmbunătăți extragerea informației. De exemplu, un tezaur despre vin pornește de la termenul "vin" și conține sub-termenii "vin roșu", "vin alb", care la rândul lor conțin sub-termenii "vin dulce", "vin sec", "vin demi-sec", care la rândul lor conțin sub-termenii specifici unui soi anume de vin ("Chardonnay", "Cabernet Sauvignon" etc). [4]



## Bibliografie

1. [User Experience Design, Wikipedia](https://en.wikipedia.org/wiki/User_experience_design)
2. [Information Architecture, Wikipedia](https://en.wikipedia.org/wiki/Information_architecture)
3. [What is Information Architcture?](http://www.iainstitute.org/what-is-ia)
4. [Information Architecture: For the Web and Beyond](https://www.amazon.com/Information-Architecture-For-Web-Beyond/dp/1491911689)
