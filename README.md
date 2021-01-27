# frontend-applications-resit
Voor dit vak moest ik gebruik maken van een framework om een client-side applicatie te maken die data dynamisch rendert. Helaas is het mij niet gelukt om het met D3 te doen, dus heb ik zoveel mogelijk gekeken naar components en heb ik wel een klein stukje waar data veranderd. **De grafieken zijn door Naomi zelf gemaakt met de data van RDW**

## Concept
De auto in de stad - het thema dat we hebben gekregen van de Volkskrant. Ik heb voor het vorig vak Functional Programming en Frontend Data met de data gewerkt over gekentekende voertuigen. Deze heb ik toen gefilterd naar alleen personenauto's. Van de personenauto's heb ik gekeken naar kleuren en automerken. Mijn onderzoeksvraag is: **Wat voor personenauto zien we het meest in Nederland?**

Eerst laat ik zien hoeveel kleuren en automerken er zijn en vervolgens combineer ik deze twee data in een stacked barchart. 

FOTO

## Data
Omdat ik niet meer met D3 heb gewerkt voor dit vak, heb ik de data in een excel bestand gezet zodat ik de waardes goed kon overnemen om de grafieken te plotten. Automerken die een waarde hebben minder dan 5 heb ik in een soort gezet; overig. Dit heb ik ook bij de grafieken neergezet.

## Features
Over de verschillende componenten kun je die hier lezen: [in de wiki](https://github.com/wailingnaomi/frontend-applications-resit/wiki).

Het grootste component is [ChangeChart](https://github.com/wailingnaomi/frontend-applications-resit/wiki/ChangeChart.vue-%7C-state---component) omdat ik hier twee knoppen heb waarbij de data veranderd naar de goeie afbeelding. Om het makkelijk te zeggen; knop A geeft afbeelding A en knop B geeft afbeelding B.

## Credits en bronnen
- Anthony (uit support groep 3)
- Sjors (dmv team project Eenwoud met svelte (veel geleerd!!))
- [To do app](https://github.com/wailingnaomi/frontend-applications) die ik heb gemaakt om met vue te leren kennen

- https://stackoverflow.com/questions/48847644/how-to-bind-img-src-to-data-in-vue
- https://dev.to/rolanddoda/deploy-to-github-pages-like-a-pro-with-github-actions-4hdg
- https://stackoverflow.com/questions/52794839/how-to-change-a-button-class-on-click-in-vue
- https://codeburst.io/creating-reusable-components-with-vue-js-button-component-503167facfde
- https://stackoverflow.com/questions/61728016/vue-js-change-image-src-with-a-click
- https://dev.to/rolanddoda/deploy-to-github-pages-like-a-pro-with-github-actions-4hdg
- https://cli.vuejs.org/guide/creating-a-project.html#vue-create
- https://masteringjs.io/tutorials/vue/bind
- https://learnvue.co/2020/12/how-to-use-lifecycle-hooks-in-vue3/#mounting

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
