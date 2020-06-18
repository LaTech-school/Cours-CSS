# Definition CSS

## Syntaxe

```
sélecteur {
    propiété à définir: valeur;
}
```

Exemple pour `<body>`

```css
body {
    background-color: #FF0000;
}
```


## Cibler des éléments HTML

### Sélecteur de TYPE

```
body {...}
cible la balise : <body>
```
```
div {...}
cible la balise : <div>
```
```
a {...}
cible la balise : <a hre="#">
```
```
p {...}
cible la balise : <p>
```

### Sélecteur de CLASSE

Le sélecteur de classe prend le dessus sur le sélecteur de type.

```
.banane {....}
cible la balise : <div class="banane">
cible la balise : <p class="banane">
cible la balise : <body class="banane">
```
```
.poire {....}
cible la balise : <div class="poire">
cible la balise : <p class="poire">
cible la balise : <body class="poire">
```
```
.pomme {....}
cible la balise : <div class="pomme">
cible la balise : <p class="pomme">
cible la balise : <body class="pomme">
```

### Sélecteur d'ID

Le sélecteur d'ID prend le dessus sur le sélecteur de classe.

```
#main-form {....}
cible la balise : <div id="main-form">
```
```
#copyright {....}
cible la balise : <div id="copyright">
```


### Sélecteur Multiple

```
.pomme, .poire {....}
cible la balise : <div class="poire">
cible la balise : <div class="pomme">
```
```
#main-form, #copyright {....}
cible la balise : <div id="main-form">
cible la balise : <div id="copyright">
```

```
.pomme, .poire, #main-form, #copyright {....}
cible la balise : <div class="poire">
cible la balise : <div class="pomme">
cible la balise : <div id="main-form">
cible la balise : <div id="copyright">
```