---
layout: page
title: Principii de UI
permalink: /ui/
---

## Ce este “User Interface”?
_**User Interface (UI)**_ este același lucru cu _visual design_, în contextul dezvoltării web a unui proiect. Etapa de "UI" din cadrul unui proiect web se referă la transformarea wireframe-urilor sau prototipului (construite în etapa anterioară de "UX") într-o interfață care să fie atractivă din punct de vedere vizual pentru utilizatori (fonturi, culori, forme, imagini etc). Această etapă va crea înfățișarea finală a paginilor și a aplicației în sine.

**Multă lume confundă UI-ul cu UX-ul**. "UX" (User Experience) este etapa care proiectează o interfață "usable", este "sistemul osos" al oricărui proiect web. "UI" este etapa care îmbracă "sistemul osos" cu "mușchi și piele", astfel încât acesta să arate atractiv și convingător.

**A trece la partea de "culoare" (UI) fără a avea definită în prealabil partea de "structură" (UX)** înseamnă să încalci una din regulile de bază ale _User Experience Design-ului_, care spune că [Forma urmează funcției](https://en.wikipedia.org/wiki/Form_follows_function).

**Visual designer-ul nu este un simplu utilizator de Photoshop** (sau Sketch, Illustrator etc). El este capabil atât să creeze interfețe frumoase, cât și să explice concepte de design și să argumenteze deciziile din spatele muncii sale. <sup>[[1]](#bibliografie)</sup>

**Visual designer-ul este mai mult decât un _graphic designer_** (care se ocupă de tipografie, culoare, imagini, utilizarea spațiului, iconițe), el este un om capabil să **asigure o experiență vizuală consecventă pe toate tipurile de ecrane** necesare unei aplicații (desktop, tablete, smartphones). <sup>[[1]](#bibliografie)</sup>

Această pagină descrie principiile de bază ale _visual design-ului_.

## 1. Așezare în pagină
Folosește spațiul liber pentru a crea o ierarhie vizuală în pagină.

### Lățime pagină
Lațimea maximă implicită a unei pagini este de 1170px, dar o poți extinde în cazul în care conținutul cere acest lucru.

Folosește o grilă pentru a așeza conținutul. Pentru a preveni apariția unor linii lungi de text conținutul trebuie să stea într-o coloană care este de maximum două treimi din lățimea paginii.

Liniile lungi de text reduc lizibilitatea, prin urmare toate liniile de text trebuie să nu fie mai lungi de 75 de caractere.

### Mărime ecran
Proiectează pentru ecrane mici mai întâi, folosind o singură coloană.

Optimizează apoi pentru diferite dimensiuni de ecran fără a face presupuneri cu privire la modelul dispozitivelor pe care le folosesc utilizatorii.

### Spațiere
- distanța dintre elemente este de obicei 5px, 10px, 15px sau multiplu de 15px
- distanța față de marginile ecranului este de 15px pentru ecranele mici și 30px pentru ecranele mari

### Proporții
- separă pagina în coloane în funcție de conținut
- folosește ca proporții jumătăți, treimi sau sferturi din lățimea paginii

## 2. Tipografie

### Font
- folosește fontul [Work Sans](https://fonts.google.com/specimen/Work+Sans) cu caractere normale, cursive și aldine
- pentru a acoperi cât mai multe dispozitive folosește stiva de fonturi: "Work Sans", sans-serif
- pentru a 

### Titluri și subtitluri
- folosește fontul [Noto Serif])(https://fonts.google.com/specimen/Noto+Serif) cu caractere normale pentru titluri
- folosește titluri și subtitluri în mod consecvent pentru a crea o ierarhie clară în pagină

### Corp de text
- folosește caractere normale
- evita să folosești caractere cursive sau aldine dacă nu este necesar
- folosește dimensiunea 16px pentru corpul de text (14px pentru ecrane mici)
- asigură-te că liniile de text nu depășesc 75 de caractere deoarece acestea devin greu de citit dincolo de acest prag

### Legături
- legăturile din corpul de text trebuie să fie subliniate
- legăturile care nu fac parte dintr-un text trebuie să nu fie urmate de punct

### Liste
- elementele unei liste încep cu literă mică

### Extrase
- folosește o margine pentru a atrage atenția asupra conținutului important din pagină

## 3. Culori

### Contrast de culoare
Raportul de contrast de culoare pentru text și elemente interactive trebuie să fie de cel puțin 4,5:1 așa cum este [recomandat de W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html){:target="_blank"}.

### Paleta de culori

#### Culori principale
<div class="color-swatches">
	<div class="color-swatch brand-primary"></div>
	<div class="color-swatch brand-success"></div>
	<div class="color-swatch brand-info"></div>
	<div class="color-swatch brand-warning"></div>
	<div class="color-swatch brand-danger"></div>
</div>

#### Culori secundare
Culorile secundare sunt derivate de nunață ale culorilor principale

#### Nuanțe de gri
<div class="color-swatches">
	<div class="color-swatch gray-darker"></div>
	<div class="color-swatch gray-dark"></div>
	<div class="color-swatch gray"></div>
	<div class="color-swatch gray-light"></div>
</div>

## 4. Pictograme și imagini
Evită decorarea inutilă - folosește doar pictograme și imagini dacă este o nevoie reală pentru utilizare.

### Pictograme
- dacă sunt necesare pictograme asigură-te că sunt clare, simple și însoțite de un text relevant
- nu ascunde funcționalități sub pictograme

### Imagini
- în cazul în care sunt necesare imagini acestea trebuie să aibă raport 3:2

## 5. Date
Folosește tabele pentru a face conținutul mai ușor de parcurs.

### Date numerice tabelare
- atunci când se compară șiruri de numere, aliniază numerele la dreapta în celulele de tabel

### Vizualizare date
- reprezentarea vizuală a datelor este recomandată ca alternativă la utilizarea imaginilor
- asigură-te că, într-o reprezentare vizuală, valoarea numerică apare înaintea descrierii pentru a fi ușor de citit

## 6. Butoane
- folosește butoanele pentru navigarea în site și afișează un singur buton principal pe pagină.

### Text buton
- textul unui buton trebuie să fie scurt și să descrie acțiunea pe care o realizează butonul

### Aliniere buton
- butonul principal se aliniaza la stânga, în linie cu celelalte elemente din formular

### Butoane dezactivate
- nu dezactiva butoane decât dacă există un motiv bun pentru asta
- dacă trebuie să dezactivezi un buton, asigura-te că arată că nu poate fi selectat (opacitate 50%)
- daca butonul principal este dezactivat, furnizează un alt mod prin care utilizatorul poate să continue sau adaugă un mesaj de eroare și un text pentru a explica de ce butonul este dezactivat

## 7. Formulare
Păstrează formularele cât mai simple - cere doar informațiile necesare.

### Câmpuri opționale și obligatorii
- solicită doar informațiile de care ai absolută nevoie
- dacă ceri informații opționale marchează etichetele câmpurilor opționale cu '(opțional)'
- câmpurile obligatorii nu trebuie marcate cu asterisc

### Etichete
- toate câmpurile din formular trebuie să aibă etichetă
- nu ascunde etichete, cu excepția cazului în care contextul le face inutile
- etichetele trebuie să fie aliniate deasupra câmpurilor aferente
- textul etichetei trebuie să fie scurt și direct
- evită să folosești punct la sfârșitul etichetelor
- fiecare etichetă trebuie să fie asociată cu un câmp din formular

### Câmpuri
- câmpurile trebuie să aibă o dimensiune proporțională cu informația care trebuie introdusă
- asigură-te că utilizatorii pot introduce informațiile și la dimensiuni mici de ecran
- dimensionează lățimea câmpurilor la 100% pe ecrane mici

### Stare de focalizare
- orice elementele din formular trebuie să fie evidențiat când se află în starea de focalizare
- starea de focalizare se activează la click pe eticheta sau în interiorul câmpului

### Spațiere între elemente
- asigură-te că există suficient spațiu între elementele unui formular

## 8. Erori și validare
- încearcă să reduci numărul de erori dintr-o pagină
- validează și evidențiază erorile și alte mesaje
- grupează erorile în partea de sus a paginii
- include un titlu pentru grupul de erori
- leagă fiecare eroare de câmpul care a generat problema

### Evidențiere erori în formular
Pentru fiecare eroare:
- scrie un mesaj care ajută utilizatorul să înțeleagă de ce a apărut eroarea și ce să facă cu privire la aceasta
- pune mesajul de eroare în etichetă, după textul respectiv, cu roșu
- folosește un chenar roșu pentru câmp pentru a-l conecta vizual cu eroarea

## 9. Antet și subsol
Când și cum se utilizează antetul gov.ro, subsolul și logo-ul.

### Utilizare antet și subsol
Dacă serviciul este disponibil la www.gov.ro sau la o adresa de forma serviciu.gov.ro, atunci trebuie să folosească antetul și subsolul gov.ro. Aceasta include logo-ul Guvernului României și paleta de culori.

În cazul în care serviciul nu este disponibil la unul dintre aceste domenii, atunci nu trebuie să folosească antetul și subsolul gov.ro.

### Implementare antet și subsol gov.ro
Codul și resursele pentru a implementa antetul și subsol gov.ro sunt disponibile în pagina de [componente](/componente).


## Bibliografie

1. [What is visual design](https://skillcrush.com/2016/05/31/what-is-visual-design/)
