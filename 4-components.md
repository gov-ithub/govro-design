---
layout: page
title: Componente
permalink: /componente/
---

În această pagină vor fi listate componentele disponibile și modul de utilizare a acestora.

## Așezarea în pagină
Așezarea în pagina include containerele de bază și un sistem de așezare bazat pe linii și coloane.

### Containerul
Centrează conținutul paginii cu un container.

``` html
<div class="container-fluid">
  ...
</div>
```

### Grila
Grila este una standard prin care adaugi rânduri cu coloane, fiecare coloană având o clasă care stabilește raportul de lățime al acesteia.

<div class="example example-guide">
  <div class="row">
    <div class="col-md-8"><span>coloană două treimi</span></div>
    <div class="col-md-4"><span>coloană o treime</span></div>
  </div>
</div>
``` html
<div class="row-fluid">
  <div class="col-md-8">...</div>
  <div class="col-md-4">...</div>
</div>
```

## Tipografia

### Titluri
<div class="example">
  <h1>h1. Titlu design.gov.ro</h1>
  <h2>h2. Titlu design.gov.ro</h2>
  <h3>h3. Titlu design.gov.ro</h3>
  <h4>h4. Titlu design.gov.ro</h4>
  <h5>h5. Titlu design.gov.ro</h5>
  <h6>h6. Titlu design.gov.ro</h6>
</div>
``` html
<h1>h1. Titlu design.gov.ro</h1>
<h2>h2. Titlu design.gov.ro</h2>
<h3>h3. Titlu design.gov.ro</h3>
<h4>h4. Titlu design.gov.ro</h4>
<h5>h5. Titlu design.gov.ro</h5>
<h6>h6. Titlu design.gov.ro</h6>
```

### Paragrafe
<div class="example">
<p class="lead">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.</p>
<p>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec ullamcorper nulla non metus auctor fringilla. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Donec ullamcorper nulla non metus auctor fringilla.</p>
<p>Maecenas sed diam eget risus varius blandit sit amet non magna. Donec id elit non mi porta gravida at eget metus. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit.</p>
</div>
``` html
<p class="lead">...</p>
<p>...</p>
```

### Citate
<div class="example">
<blockquote>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
</div>
``` html
<blockquote>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
  <footer>Someone famous in <cite title="Source Title">Source Title</cite></footer>
</blockquote>
```

### Liste
#### Liste neordonate
<div class="example">
<ul>
  <li>Lorem ipsum dolor sit amet</li>
  <li>Nulla volutpat aliquam velit
    <ul>
      <li>Phasellus iaculis neque</li>
      <li>Purus sodales ultricies</li>
      <li>Vestibulum laoreet porttitor sem</li>
      <li>Ac tristique libero volutpat at</li>
    </ul>
  </li>
  <li>Faucibus porta lacus fringilla vel</li>
  <li>Aenean sit amet erat nunc</li>
  <li>Eget porttitor lorem</li>
</ul>
</div>
``` html
<ul>
  <li>...</li>
</ul>
```

#### Liste ordonate
<div class="example">
<ol>
  <li>Lorem ipsum dolor sit amet</li>
  <li>Nulla volutpat aliquam velit
    <ol>
      <li>Phasellus iaculis neque</li>
      <li>Purus sodales ultricies</li>
      <li>Vestibulum laoreet porttitor sem</li>
      <li>Ac tristique libero volutpat at</li>
    </ol>
  </li>
  <li>Faucibus porta lacus fringilla vel</li>
  <li>Aenean sit amet erat nunc</li>
  <li>Eget porttitor lorem</li>
</ol>
</div>
``` html
<ol>
  <li>...</li>
</ol>
```

## Butoanele
Butoanele sunt folosite pentru **acțiuni** în formulare și acțiuni primare în pagină, iar legăturile din text sunt folosite pentru **destinații** sau pentru a ajunge de la o pagină la alta.

<div class="example">
  <button class="btn btn-default" type="button">Buton button</button>
  <a class="btn btn-default" href="#" role="button">Buton link</a>
</div>
``` html
<button class="btn btn-default" type="button">Buton button</button>
<a class="btn btn-default" href="#" role="button">Buton link</a>
```

### Dimensiunea butoanelor
<div class="example">
  <button class="btn btn-default" type="button">Buton</button>
  <button class="btn btn-default btn-sm" type="button">Buton mic</button>
</div>
``` html
<button class="btn btn-default" type="button">Buton</button>
<button class="btn btn-sm" type="button">Buton mic</button>
```

### Tipuri de butoane
Butoanele primare sunt folosite pentru a indica acțiunea principală dintr-o pagină.

Butoanele periculoase aduc aminte utilizatorului că acțiunea respectivă are un potențial periculos (ex: ștergerea unei resurse).
<div class="example">
  <p>
  <button class="btn btn-primary" type="button">Buton principal</button>
  <button class="btn btn-primary btn-sm" type="button">Buton principal mic</button>
  </p>

  <p>
  <button class="btn btn-danger" type="button">Buton periculos</button>
  <button class="btn btn-sm btn-danger" type="button">Buton periculos mic</button>
  </p>

</div>
``` html
<button class="btn btn-primary" type="button">Buton principal</button>
<button class="btn btn-sm btn-primary" type="button">Buton principal mic</button>

<button class="btn btn-danger" type="button">Buton periculos</button>
<button class="btn btn-sm btn-danger" type="button">Buton periculos mic</button>
```

### Butoane dezactivate
<div class="example">
<p>
<button class="btn btn-default" type="button" disabled>Buton dezactivat</button>
<a class="btn btn-default disabled" href="#" role="button">Buton dezactivat</a>
</p>
<p>
<button class="btn btn-primary" type="button" disabled>Buton dezactivat</button>
<a class="btn btn-primary disabled" href="#" role="button">Buton dezactivat</a>
</p>
<p>
<button class="btn btn-danger" type="button" disabled>Buton dezactivat</button>
<a class="btn btn-danger disabled" href="#" role="button">Buton dezactivat</a>
</p>
</div>
``` html
<button class="btn btn-default" type="button" disabled>Buton dezactivat</button>
<a class="btn disabled" href="#" role="button">Buton dezactivat</a>
```

### Grupuri de butoane
<div class="example">
  <div class="btn-group">
    <button class="btn btn-default" type="button">Buton</button>
    <button class="btn btn-default" type="button">Buton</button>
    <button class="btn btn-default" type="button">Buton</button>
  </div>
</div>
``` html
<div class="btn-group">
  <button class="btn btn-default" type="button">Buton</button>
  <button class="btn btn-default" type="button">Buton</button>
  <button class="btn btn-default" type="button">Buton</button>
</div>
```

## Formularele

### Input
<div class="example">
<form>
  <p><input class="form-control input" type="text" placeholder="Input normal"></p>
  <p><input class="form-control input-sm" type="text" placeholder="Input mic"></p>
  <p><input class="form-control" type="text" placeholder="Input dezactivat" disabled></p>
  <p><input class="form-control input-sm" type="text" placeholder="Input mic dezactivat" disabled></p>
</form>
</div>
``` html
<input class="form-control" type="text" placeholder="Input normal">
<input class="form-control input-sm" type="text" placeholder="Input mic">

<input class="form-control" type="text" placeholder="Input dezactivat" disabled>
<input class="form-control input-sm" type="text" placeholder="Input mic dezactivat" disabled>
```

### Select
<div class="example">
<form>
<p>
  <select class="form-control">
    <option>Select normal</option>
    <option>1</option>
    <option>2</option>
    <option>3</option>
  </select>
</p>
<p>
  <select class="form-control input-sm">
    <option>Select mic</option>
    <option>1</option>
    <option>2</option>
    <option>3</option>
  </select>
</p>
<p>
  <select class="form-control" disabled>
    <option>Select normal</option>
    <option>1</option>
    <option>2</option>
    <option>3</option>
  </select>
</p>
<p>
  <select class="form-control input-sm" disabled>
    <option>Select mic</option>
    <option>1</option>
    <option>2</option>
    <option>3</option>
  </select>
</p>
</form>
</div>
``` html
<select class="form-control">
  <option>Select normal</option>
</select>
<select class="form-control input-sm">
  <option>Select mic</option>
</select>
```

### Textarea
<div class="example">
  <textarea class="form-control" rows="3"></textarea>
</div>
``` html
<textarea class="form-control" rows="3"></textarea>
```

### Checkbox și radio
<div class="example">
<div class="checkbox">
  <label>
    <input type="checkbox" value="">
    Aceasta este prima opțiune
  </label>
</div>
<div class="checkbox disabled">
  <label>
    <input type="checkbox" value="" disabled>
    A doua opțiupe este dezactivată
  </label>
</div>

<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" checked>
    Aceasta este prima opțiune și este implicită
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="optionsRadios">
    Aceasta este a doua opțiune
  </label>
</div>
<div class="radio disabled">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3" disabled>
    A treia opțiune este dezactivată
  </label>
</div>
</div>
``` html
<div class="checkbox">
  <label>
    <input type="checkbox" value="">
    Aceasta este prima opțiune
  </label>
</div>
<div class="checkbox disabled">
  <label>
    <input type="checkbox" value="" disabled>
    A doua opțiupe este dezactivată
  </label>
</div>

<div class="radio">
  <label>
    <input type="radio" name="optionsRadios" checked>
    Aceasta este prima opțiune și este implicită
  </label>
</div>
<div class="radio">
  <label>
    <input type="radio" name="optionsRadios">
    Aceasta este a doua opțiune
  </label>
</div>
<div class="radio disabled">
  <label>
    <input type="radio" name="optionsRadios" id="optionsRadios3" value="option3" disabled>
    A treia opțiune este dezactivată
  </label>
</div>
```

### Grupuri de input
<div class="example">
<p>
<div class="input-group">
  <span class="input-group-addon" id="basic-addon1">RO</span>
  <input type="text" class="form-control" placeholder="12345678" aria-describedby="basic-addon1">
</div>
</p>
<p>
<div class="input-group">
  <input type="text" class="form-control text-right" placeholder="1.324,54" aria-describedby="basic-addon2">
  <span class="input-group-addon" id="basic-addon2">lei</span>
</div>
</p>
</div>
``` html
<div class="input-group">
  <span class="input-group-addon" id="basic-addon1">RO</span>
  <input type="text" class="form-control" placeholder="12345678" aria-describedby="basic-addon1">
</div>

<div class="input-group">
  <input type="text" class="form-control text-right" placeholder="1.324,54" aria-describedby="basic-addon2">
  <span class="input-group-addon" id="basic-addon2">lei</span>
</div>
```

### Acțiuni formular

<div class="example">
<div class="form-actions">
<button type="button" class="btn btn-primary">Salvează</button>
<button type="button" class="btn btn-default">Renunță</button>
</div>
</div>
``` html
<div class="form-actions">
  <button type="button" class="btn btn-primary">Salvează</button>
  <button type="button" class="btn btn-default">Renunță</button>
</div>
```

## Navigația

### Navigația principală
<div class="example">
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Acțiune</a></li>
            <li><a href="#">Altă acțiune</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Acțiune separată</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left pull-right">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Caută">
        </div>
        <button type="submit" class="btn btn-default">Trimite</button>
      </form>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
</div>
``` html
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#">Brand</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
        <li><a href="#">Link</a></li>
        <li class="dropdown">
          <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Acțiune</a></li>
            <li><a href="#">Altă acțiune</a></li>
            <li role="separator" class="divider"></li>
            <li><a href="#">Acțiune separată</a></li>
          </ul>
        </li>
      </ul>
      <form class="navbar-form navbar-left pull-right">
        <div class="form-group">
          <input type="text" class="form-control" placeholder="Caută">
        </div>
        <button type="submit" class="btn btn-default">Trimite</button>
      </form>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>
```
### Navigația secundară
<div class="example">
<ul class="nav nav-side">
  <li class="active"><a href="#">Cont</a></li>
  <li><a href="#">Profil</a></li>
  <li><a href="#">Mesaje</a></li>
</ul>
</div>
``` html
<ul class="nav nav-side">
  <li class="active"><a href="#">Cont</a></li>
  <li><a href="#">Profil</a></li>
  <li><a href="#">Mesaje</a></li>
</ul>
```

### Navigația prin tabs
<div class="example">
<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Cont</a></li>
  <li role="presentation"><a href="#">Profil</a></li>
  <li role="presentation"><a href="#">Mesaje</a></li>
</ul>
</div>
``` html
<ul class="nav nav-tabs">
  <li role="presentation" class="active"><a href="#">Cont</a></li>
  <li role="presentation"><a href="#">Profil</a></li>
  <li role="presentation"><a href="#">Mesaje</a></li>
</ul>
```

### Navigația prin breadcrumbs
<div class="example">
<ol class="breadcrumb">
  <li><a href="#">Acasa</a></li>
  <li><a href="#">Nivelul 1</a></li>
  <li class="active">Nivelul 2</li>
</ol>
</div>
``` html
<ol class="breadcrumb">
  <li><a href="#">Acasa</a></li>
  <li><a href="#">Nivelul 1</a></li>
  <li class="active">Nivelul 2</li>
</ol>
```

## Alertele și notificările
<div class="example">
<div class="alert alert-success" role="alert">Mesaj de tip succes</div>
<div class="alert alert-info" role="alert">Mesaj de tip informare</div>
<div class="alert alert-warning" role="alert">Mesaj de tip avertisment</div>
<div class="alert alert-danger" role="alert">Mesaj de tip eroare</div>
</div>
``` html
<div class="alert alert-success" role="alert">Mesaj de tip succes</div>
<div class="alert alert-info" role="alert">Mesaj de tip informare</div>
<div class="alert alert-warning" role="alert">Mesaj de tip avertisment</div>
<div class="alert alert-danger" role="alert">Mesaj de tip eroare</div>
```

## Starea implicită
<div class="example">
<div class="well blankslate">
  <h4>Aceasta este o secțiune implicită</h4>
  <p>Folosește-o pentru a informa utilizatorul atunci când nu există conținut dinamic.</p>
</div>
</div>
``` html
<div class="well blankslate">
  <h4>Aceasta este o secțiune implicită</h4>
  <p>Folosește-o pentru a informa utilizatorul atunci când nu există conținut dinamic.</p>
</div>
```

## Utilitare
<div class="example">
[în curs de actualizare]
</div>
``` html
```

## Șabloane
<div class="example">
[în curs de actualizare]
</div>
``` html
```

### Șabloane formular
<div class="example">
[în curs de actualizare]
</div>
``` html
```

### Șabloane antet
<div class="example">
[în curs de actualizare]
</div>
``` html
```

### Șabloane subsol
<div class="example">
[în curs de actualizare]
</div>
``` html
```
