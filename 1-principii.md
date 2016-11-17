---
layout: page
title: Principii generale
permalink: /
---

În această pagină sunt prezentate principiile care stau la baza ghidului de proiectare a serviciilor gov.ro

## Proiectează servicii accesibile

Serviciile disponibile prin gov.ro sunt în beneficiul tuturor cetățenilor români. Acest lucru înseamnă că trebuie să construiești servicii cât mai cuprinzătoare.

Excluderea unei persoane de la utilizarea serviciului din cauza dizabilității poate fi o încălcare a legii nr. 448/2006 privind protecţia drepturilor persoanelor cu handicap.

### Îndeplinește standardul de accesibilitate
Ca un minim, serviciul trebuie să îndeplinească nivelul AA al ghidului privind accesibilitatea conținutului web [(WCAG) 2.0](https://www.w3.org/WAI/intro/wcag.php){:target="_blank"}.


### Testează accesibiltatea
Poți găsi unele probleme de accesibilitate prin utilizarea unui instrument automat sau prin verificări manuale.

Poți să utilizezi un instrument automat pentru a testa în mod regulat accesibilitatea serviciului în timpul dezvoltării și după lansare, ca de exemplu: [WAVE](http://wave.webaim.org/){:target="_blank"}, [Tenon](https://tenon.io/){:target="_blank"} sau [HTML_Sniffer](https://www.squizlabs.com/general/html-codesniffer){:target="_blank"}.

Nu trebuie să te bazezi exclusiv pe utilizarea de instrumente automate pentru verificarea accesibilității - ele pot găsi doar 20%-30% din probleme.

Pentru alte instrumente automate sau manuale vezi [lista W3C](https://www.w3.org/WAI/ER/tools/?q=wcag-20-w3c-web-content-accessibility-guidelines-20){:target="_blank"}.


## Înțelege nevoile utilizatorului

Documentează-te pentru a înțelege cine sunt utilizatorii serviciului și cum influențează ei proiectarea serviciului.

Înțelege nevoile utilizatorilor astfel încât să poți construi un serviciu care:
- ajută utilizatorii să facă lucrul pe care îl doresc din prima încercare, fără a fi nevoiți să înțeleagă cum funcționează instituțiile guvernamentale
- este construit după nevoile reale ale utilizatorilor, nu după presupuneri


## Proiectează pentru diverse navigatoare și dispozitive

Tehnologia este mereu în schimbare, astfel încât experiența utilizatorilor serviciului variază în funcție de capacitățile tehnice ale navigatoarelor și dispozitivelor pe care ei le folosesc.

Nu toate navigatoarele vor afișa paginile web în același mod. Deseori există diferențe vizibile în modul în care diferite navigatoare interprezează CSS, HTML și JavaScript.

Serviciul nu trebuie să arate identic în toate navigatoarele, dar utilizatorii trebuie să poată să acceseze și să utilizeze toate informațiile și caracteristicile de care au nevoie, indiferent de navigatorul pe care îl folosesc.

Folosește tehnica [progresiv enhancement](https://en.wikipedia.org/wiki/Progressive_enhancement){:target="_blank"} pentru a oferi serviciului cele mai mari șanse de a fi funcțional pentru majoritatea utilizatorilor.

### Testează compatibilitatea
Dacă proiectezi un serviciu pentru publicul larg, nu doar pentru a fi utilizat în guvern, trebuie să-l testezi în navigatoarele din tabelul următor:

| Sistem de operare |	Navigator |
|:--------|:-------|
| Windows |	Internet Explorer 8+ |
| Windows | Edge (ultima versiune) |
| Windows | Google Chrome (ultima versiune) |
| Windows |	Mozilla Firefox (ultima versiune) |
| Mac OS X | Safari 9+ |
| Mac OS X | Google Chrome (ultima versiune) |
| Mac OS X | Mozilla Firefox (ultima versiune) |

Dacă serviciul este destinat utilizatorilor interni folosește navigatoarele din tabel ca referință, apoi extinde testele cu navigatoarele persoanelor care folosesc serviciul în mod curent.
