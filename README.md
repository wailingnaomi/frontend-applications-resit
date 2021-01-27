# frontend-applications-resit
Voor dit vak moest ik gebruik maken van een framework om een client-side applicatie te maken die data dynamisch rendert. Helaas is het mij niet gelukt om het met D3 te doen, dus heb ik zoveel mogelijk gekeken naar components en heb ik wel een klein stukje waar data veranderd. **De grafieken zijn door Naomi zelf gemaakt met de data van RDW**

![Schermafbeelding 2021-01-27 om 23 03 41](https://user-images.githubusercontent.com/55541888/106060108-f180c680-60f3-11eb-9e01-bccbe605be48.png)


## Concept
De auto in de stad - het thema dat we hebben gekregen van de Volkskrant. Ik heb voor het vorig vak Functional Programming en Frontend Data met de data gewerkt over [gekentekende voertuigen](https://opendata.rdw.nl/Voertuigen/Open-Data-RDW-Gekentekende_voertuigen/m9d7-ebf2). Deze heb ik toen gefilterd naar alleen personenauto's. Van de personenauto's heb ik gekeken naar kleuren en automerken. Mijn onderzoeksvraag is: **Wat voor personenauto zien we het meest in Nederland?**

Eerst laat ik zien hoeveel kleuren en automerken er zijn en vervolgens combineer ik deze twee data in een stacked barchart. 

![Schermafbeelding 2021-01-27 om 23 04 39](https://user-images.githubusercontent.com/55541888/106060247-0eb59500-60f4-11eb-981c-caaffc3ab2b0.png)
![Schermafbeelding 2021-01-27 om 23 05 20](https://user-images.githubusercontent.com/55541888/106060312-255bec00-60f4-11eb-81ef-fccdad73280b.png)



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
