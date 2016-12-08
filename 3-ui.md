---
layout: page
title: Principii de UI
permalink: /principii/ui/
---

## Ce este _UI_
"UI" ("User Interface") este același lucru cu termenul "visual design", _în contextul dezvoltării web a unui proiect_. Etapa de "UI" din cadrul unui proiect web se referă la transformarea wireframe-urilor sau prototipului (construite în etapa anterioară de "UX") într-o interfață care să fie atractivă din punct de vedere vizual pentru utilizatori (fonturi, culori, forme, imagini etc). Această etapă va crea înfățișarea finală a paginilor și a aplicației în sine.

**Multă lume confundă UI-ul cu UX-ul**. "UX" (User Experience) este etapa care proiectează o interfață "usable", este "sistemul osos" al oricărui proiect web. "UI" este etapa care îmbracă "sistemul osos" cu "mușchi și piele", astfel încât acesta să arate atractiv și convingător.

**A trece la partea de "culoare" (UI) fără a avea definită în prealabil partea de "structură" (UX)** înseamnă să încalci una din regulile de bază ale _User Experience Design-ului_, care spune că [_Forma urmează funcției_](https://en.wikipedia.org/wiki/Form_follows_function).

**Visual designer-ul nu este un simplu utilizator de Photoshop** (sau Sketch, Illustrator etc). El este capabil atât _să creeze interfețe frumoase_, cât și _să explice concepte de design și să argumenteze deciziile din spatele muncii sale_. [1]

**Visual designer-ul este mai mult decât un _graphic designer_** (care se ocupă de tipografie, culoare, imagini, utilizarea spațiului, iconițe), el este un om capabil să **asigure o experiență vizuală consecventă pe toate tipurile de ecrane** necesare unei aplicații (desktop, tablete, _smartphones_). [1]

Această pagină descrie principiile de bază ale _visual design-ului_.

## 1. Așezarea în pagină
Folosește spațiul liber pentru a crea o ierarhie vizuală în pagină.

### Lățimea paginii
Lațimea maximă implicită a unei pagini este de 1020px, dar o poți extinde în cazul în care conținutul cere acest lucru.

Folosește o grilă pentru a așeza conținutul. Pentru a preveni apariția unor linii lungi de text conținutul trebuie să stea într-o coloană care este de maximum două treimi din lățimea paginii.

Liniile lungi de text reduc lizibilitatea, prin urmare toate liniile de text trebuie să nu fie mai lungi de 75 de caractere.

### Mărimea ecranului
Proiectează pentru ecrane mici mai întâi, folosind o singură coloană.

Optimizează apoi pentru diferite dimensiuni de ecran fără a face presupuneri cu privire la modelul dispozitivelor pe care le folosesc utilizatorii.

### Spațierea
- distanța dintre elemente este de obicei 5px, 10px, 15px sau multiplu de 15px
- distanța față de marginile ecranului este de 15px pentru ecranele mici și 30px pentru ecranele mari

### Proporțiile
- separă pagina în coloane în funcție de conținut
- folosește ca proporții jumătăți, treimi sau sferturi din lățimea paginii

## 2. Tipografia

### Fontul
- folosește fontul **Trebuchet MS** cu caractere normale, cursive și aldine pentru domeniile .gov.ro
- pentru a acoperi cât mai multe dispozitive folosește stiva de fonturi: "Trebuchet MS", "Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", Tahoma, sans-serif

### Titlurile și subtitlurile
- folosește caractere aldine pentru titluri
- folosește titluri și subtitluri în mod consecvent pentru a crea o ierarhie clară în pagină

### Corpul de text
- folosește caractere normale
- evita să folosești caractere cursive sau aldine dacă nu este necesar
- folosește dimensiunea 16px pentru corpul de text (14px pentru ecrane mici)
- asigură-te că liniile de text nu depășesc 75 de caractere deoarece acestea devin greu de citit dincolo de acest prag

### Legăturile
- legăturile din corpul de text trebuie să fie subliniate
- legăturile care nu fac parte dintr-un text trebuie să nu fie urmate de punct
- culorile legăturilor se regăsesc în [paleta de culori](#paleta-de-culori)

### Listele
- elementele unei liste încep cu literă mică

### Extrasele
- folosește o margine pentru a atrage atenția asupra conținutului important din pagină

## 3. Culorile

### Contrastul de culoare
Raportul de contrast de culoare pentru text și elemente interactive trebuie să fie de cel puțin 4,5:1 așa cum este [recomandat de W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html){:target="_blank"}.

### Paleta de culori

#### Culorile principale

- Pantone 480C; RGB(0,73,144); CMYK(100,72,0,18)
- Negru 80%; RGB(88,89,91); CMYK(0,0,0,80)
- Negru 100%; RGB(0,0,0); CMYK(0,0,0,100)

#### Culorile secundare

- Pantone 300C; RGB(0,121,193); CMYK(100,44,0,0)
- Negru 20%; RGB(209,211,212); CMYK(0,0,0,20)
- Negru 100%; RGB(255,255,255); CMYK(0,0,0,0)

#### Culorile componentelor
[text, legături, fundal, butoane, focus, nuanțe de gri]

## 4. Pictograme și imagini
Evita decorarea inutilă - folosește doar pictograme și imagini dacă este o nevoie reală pentru utilizator.

### Pictogramele
- dacă sunt necesare pictograme asigură-te că sunt clare, simple și însoțite de un text relevant
- nu ascunde funcționalități sub pictograme

### Imaginile
- în cazul în care sunt necesare imagini acestea trebuie să aibă raport 3:2

## 5. Datele
Folosește tabele pentru a face conținutul mai ușor de parcurs.

### Datele numerice tabelare
- atunci când se compară șiruri de numere, aliniază numerele la dreapta în celulele de tabel

### Vizualizarea datelor
- datele vizualizate sunt recomandate ca alternativă la utilizarea imaginilor
- asigură-te că valoarea numerică apare înaintea descrierii pentru a fi ușor de citit

## 6. Butoanele
- folosește butoanele pentru navigarea în site și afișează un singur buton principal pe pagină.

### Textul butonului
- textul unui buton trebuie să fie scurt și să descrie acțiunea pe care o realizează butonul

### Alinierea butonului
- butonul principal se aliniaza la stânga, în linie cu celelalte elemente din formular

### Butoanele dezactivate
- nu dezactiva butoane decât dacă există un motiv bun pentru asta
- dacă trebuie să dezactivezi un buton, asigura-te că arată că nu poate fi selectat (opacitate 50%)
- daca butonul principal este dezactivat, furnizează un alt mod prin care utilizatorul poate să continue sau adaugă un mesaj de eroare și un text pentru a explica de ce butonul este dezactivat

## 7. Formularele
Păstrează formularele cât mai simple - cere doar informațiile necesare.

### Câmpurile opționale și obligatorii
- solicită doar informațiile de care ai absolută nevoie
- dacă ceri informații opționale marchează etichetele câmpurilor opționale cu '(opțional)'
- câmpurile obligatorii nu trebuie marcate cu asterisc

### Etichetele
- toate câmpurile din formular trebuie să aibă etichetă
- nu ascunde etichete, cu excepția cazului în care contextul le face inutile
- etichetele trebuie să fie aliniate deasupra câmpurilor aferente
- textul etichetei trebuie să fie scurt și direct
- evită să folosești punct la sfârșitul etichetelor
- fiecare etichetă trebuie să fie asociată cu un câmp din formular

### Câmpurile
- câmpurile trebuie să aibă o dimensiune proporțională cu informația care trebuie introdusă
- asigură-te că utilizatorii pot introduce informațiile și la dimensiuni mici de ecran
- dimensionează lățimea câmpurilor la 100% pe ecrane mici

### Starea de focalizare
- orice elementele din formular trebuie să fie evidențiat când se află în starea de focalizare
- starea de focalizare se activează la click pe eticheta sau în interiorul câmpului

### Spațierea între elemente
- asigură-te că există suficient spațiu între elementele unui formular

## 8. Erorile și validarea
- încearcă să reduci numărul de erori dintr-o pagină
- validează și evidențiază erorile și alte mesaje
- grupează erorile în partea de sus a paginii
- include un titlu pentru grupul de erori
- leagă fiecare eroare de câmpul care a generat problema

### Evidențiază erorile în formular
Pentru fiecare eroare:
- scrie un mesaj care ajută utilizatorul să înțeleagă de ce a apărut eroarea și ce să facă cu privire la aceasta
- pune mesajul de eroare în etichetă, după textul respectiv, cu roșu
- folosește un chenar roșu pentru câmp pentru a-l conecta vizual cu eroarea

## 9. Antetul și subsolul
Când și cum se utilizează antetul gov.ro, subsolul și logo-ul.

### Când se utilizează antetul și subsolul gov.ro
Dacă serviciul este disponibil la www.gov.ro sau la o adresa de forma serviciu.gov.ro, atunci trebuie să folosească antetul și subsolul gov.ro. Aceasta include logo-ul Guvernului României și paleta de culori.

În cazul în care serviciul nu este disponibil la unul dintre aceste domenii, atunci nu trebuie să folosească antetul și subsolul gov.ro.

### Implementarea antetului și subsolului gov.ro
Codul și resursele pentru a implementa antetul și subsol gov.ro sunt disponibile în pagina de [componente](/componente).


## Bibliografie

1. [What is visual design](https://skillcrush.com/2016/05/31/what-is-visual-design/)
