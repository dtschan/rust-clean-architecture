# Präsentationen gestalten
## Titel - Workshop
#### Martin Gafner
#### gafner@puzzle.ch
<!-- .slide: class="master-cover" -->

-*-*-

## 18.02.2020
# Agenda
- Vorstellungsrunde
- Wer ist Puzzle und was tut Puzzle?
- Referenzen/Kundenprojekte (Success Stories)
- Mögliche Dienstleistungen fürs KSGR
- Fragerunde
<!-- .slide: class="master-agenda" -->

-*-*-
<div class="nr"></div>

### Puzzle
## Wer ist Puzzle?
## Was tut Puzzle?
<!-- .slide: class="master-title" -->

***
## Nice to meet you
<div class="people">
  <div>

  <div class="img" style="background-image: url(https://www.puzzle.ch/wp-content/uploads/2019/06/Gafner_Martin-1-400x300.jpg)" /></div>

  ### Martin Gafner
  Chief Communications,
  Marketing & Sales

  gafner@puzzle.ch

  </div><div>

  <div class="img" style="background-image: url(https://www.puzzle.ch/wp-content/uploads/2015/07/Fankhauser-Simon-400x300.jpg)" /></div>

  ### Simon Fankhauser
  Head of Business
  Division Zürich

  fankhauser@puzzle.ch

  </div><div>

  <div class="img" style="background-image: url(https://www.puzzle.ch/wp-content/uploads/2019/06/Pfeifhofer_Anna-400x300.jpg)" /></div>

  ### Anna Pfeifhofer
  IT Project Manager
  &nbsp;

  pfeifhofer@puzzle.ch

  </div><div>

  <div class="img" style="background-image: url(https://www.puzzle.ch/wp-content/uploads/2016/07/Shulthess_Juerg-400x300.jpg)" /></div>

  ### Jürg Schulthess
  System Architect
  &nbsp;

  schulthess@puzzle.ch

  </div>
</div>

### ALLE PUZZLER

https://www.puzzle.ch/de/team


<!-- .slide: class="master-content people" -->

***

<div>

  #### Unsere Mission

  ## Was ist uns *wichtig?*
</div>

<div>

- Open Source Technologien und offene Standards
- Transparenz und Offenheit
- Agile und collaborativeSoftware Development
- Ein angenehmes Arbeitsklima und eine gesunde
  *Life Domain Balance*
</div>
<!-- .slide: class="master-left-right" -->

***
### One Team
Wir wachsen kontinuierlich, qualitativ wie quantitativ.

<!-- .slide: class="master-team"> -->

***

### One Team

<!-- .slide: class="master-team-2"> -->

-*-*-
<div class="nr"></div>

### Unsere Mission

## Was ist uns
## wichtig?
<!-- .slide: class="master-title" -->

***
<div>

### One Mission
</div><div>

# Changing IT
# for the *better*
</div>
<!-- .slide: class="master-top-head" -->

***
### Hallo zusammen. Ich bin ein kleiner Blindtext.

<div class="narrow">

Und zwar schon so lange ich denken kann. Es war nicht leicht zu verstehen, was es bedeutet, ein blinder Text zu sein: Man ergibt keinen Sinn.

Wirklich keinen Sinn. Man wird zusammenhangslos eingeschoben und rumgedreht.

*Oftmals gar nicht erst gelesen.*

</div>

***
### Aufbau Linux Basis und Automatisierung
<div class="narrow">

- Automatisierung für Linux-Basis-Infrastruktur aufbauen
- ~ 35 virtuelle Linux Server migrieren

#### Warum?
- Automatisierung > Qualität
- Dokumentation im Code
- Änderungen sind im Version Control System nachvollziehbar (und umkehrbar)
</div>

***
<div>

### Unsere Prinzipien

</div>

<div>

![demo_principles](example-presentation/imgs/demo_principles.png)

</div>

<!-- .slide: class="master-top-head" -->
***
<div>

### Standorte und ein paar Zahlen

</div>

<div>

![demo_principles](example-presentation/imgs/demo_numbers.png)

</div>

<!-- .slide: class="master-top-head" -->

-*-*-

<div class="nr"></div>

### Code Beispiele
## Präsentation von
## Code Snippets
<!-- .slide: class="master-title" -->

***

### Normaler Code

Der Code könnte ungefähr so aussehen:

```
const babelConfig = {
    babelHelpers: 'bundled',
    ignore: ['node_modules'],
    compact: false,
    extensions: ['.js', '.html'],
    plugins: [
        'transform-html-import-to-string'
    ],
    presets: [[
        '@babel/preset-env',
        {
            corejs: 3,
            useBuiltIns: 'usage',
            modules: false
        }
    ]]
};

// Our ES module bundle only targets newer browsers with
// module support. Browsers are targeted explicitly instead
// of using the "esmodule: true" target since that leads to
// polyfilling older browsers and a larger bundle.
const babelConfigESM = JSON.parse( JSON.stringify( babelConfig ) );
babelConfigESM.presets[0][1].targets = { browsers: [
    'last 2 Chrome versions', 'not Chrome < 60',
    'last 2 Safari versions', 'not Safari < 10.1',
    'last 2 iOS versions', 'not iOS < 10.3',
    'last 2 Firefox versions', 'not Firefox < 60',
    'last 2 Edge versions', 'not Edge < 16',
] };

let cache = {};
```

***
### Grösserer Code
Man hat auch die Möglichkeit den Code etwas grösser anzuzeigen.

```
# Standard
console.log("¯\_ (ツ)_/¯");
```

<div class="big">

```
# mit <div class="big">
console.log("¯\_ (ツ)_/¯");
```

</div>

<div class="very-big">

```
# mit <div class="very-big">
console.log("¯\_ (ツ)_/¯");
```

</div>
-*-*-
# Merci!
### Mehr Informationen zu Puzzle:
### www.puzzle.ch

<!-- .slide: class="master-thanks"> -->