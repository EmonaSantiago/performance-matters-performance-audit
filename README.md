> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Performance audit on H&M – Shop
10-05-2022

https://www2.hm.com/nl_nl/index.html

Hier vind je een performance audit op een bestaande website, namelijk de H&M . Met behulp van een light house test en het documenteren van de bevindingen. Ook meteen wat er verbeterd zou kunnen worden.

## Content Audit
<img width="222" alt="image" src="https://user-images.githubusercontent.com/90447045/168787143-cd4d05f1-507b-46f1-a371-8be78279f031.png"><img width="221" alt="image" src="https://user-images.githubusercontent.com/90447045/168787183-662927ea-f49d-489b-a12f-3826ece9a3c2.png">

De Performance score van de H&M is 76. De score kan veel hoger met bepaalde verbeter punten. 




### First Contentful Paint (FCP)
Ook al heeft het geen directe invloed op de prestatiescore. Het verwijderen van bronnen die de weergave blokkeren zou al een kleine verbetering zijn. De bronnen blokkeren namelijk de eerste (FP) voor de pagina. Dus het overwegen van kritieke JS/CSS inline te leveren en alle niet-kritieke JS/Stijlen uit te stellen. 

<img width="222" alt="image" src="https://user-images.githubusercontent.com/90447045/168787367-cfa34f3e-0133-40ed-90ed-5ecc46c5f830.png">


### Time to Interactive (TTI)

De resultaten voor de TTI zijn best positief. Het is van belang dat de zichtbaarheid van inhouden optimaliseren ten koste van interactiviteit. Ook wel duurt de TTI van de H&M 0,8 sec. Dat duurt het voordat de pagina volledig interactief wordt.

<img width="168" alt="image" src="https://user-images.githubusercontent.com/90447045/168787487-540a17b5-35e9-4e71-8353-023390709458.png">

Om dit toch nog te verbeteren is het uitstellen of verwijderen van onnodige Javascript werk. 


### Speed Index
<img width="159" alt="image" src="https://user-images.githubusercontent.com/90447045/168787604-04ae0c3a-a813-4672-a3b1-5c091d7c2254.png">

Dit te verbeter door:
- het Minimaliseren van het hoofddraadwerk.

- Verkort de uitvoeringstijd van Javascript.
 
- Zorg ervoor dat tekst zichtbaar blijft tijden het laden van Webfonts.



### Total Blocking Time (TBT)
<img width="176" alt="image" src="https://user-images.githubusercontent.com/90447045/168787735-e4b19e2c-4f69-4144-9e9e-71b8d91956e3.png">

De resultaten van de TBT vallen positief. Om toch nog wat te werken is het uitschakelijken van onnodig laden, passeren of uitvoeren van Javascript. 


### Largest Contentful Paint (LCP)
De largest Contenful Paint resultaten vallen erg tegen. Wat suggesties voor verbeteringen: 
Het vermijden van enorme netwerkpayloads. Zoals de totale grootte van de h&m was 4.018 KIB. Dit te verbeteren door doorlinken van kritieke verzoeken te voorkomen. En LCP-element, dus de grootste weergave met content te vermijden. 


<img width="182" alt="image" src="https://user-images.githubusercontent.com/90447045/168787855-2a43d3e8-9ab2-491e-bb80-9512ddf860cd.png">

### Cumulative Layout Shift (CLS)
De Cumulatieve Lay-out Shift meet ook wel de beweging van zichtbare elementen binnen het kijkvenster. 
Een verbeter suggestie dat aangegeven is is dat de afbeelding elementen geen alt kenmerken hebben. Ook wel om de semantiek van de opties in de app te verbeteren. Zo kun je de functionaliteit verbeteren voor gebruikers van hulptechnologie, zoals een schermlezer. 
<img width="187" alt="image" src="https://user-images.githubusercontent.com/90447045/168787933-b3260536-3344-4db5-9e15-9459af66fb9a.png">

## Bronnen
https://www2.hm.com/nl_nl/index.html
## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
