> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Performance audit on Lidl – Shop

## ContentAudit
<img width="488" alt="image" src="https://user-images.githubusercontent.com/90447045/165923594-204b782f-523d-4c7a-9655-956abad62056.png">
Hier vind je een performance audit op een bestaande website, namelijk de Lidl shop. Met behulp van een lighthouse test en het documenteren van de bevindingen. Ook meteen wat er verbeterd zou kunnen worden. 

De lidl webshop: https://www.lidl.nl/c/lidl-shop/s10008767

<img width="454" alt="image" src="https://user-images.githubusercontent.com/90447045/165924977-8194ab99-160f-43d4-816c-8836ef0e16e4.png">
<img width="454" alt="image" src="https://user-images.githubusercontent.com/90447045/165924999-19228746-308a-4828-b799-df292d858316.png">


### First Contentful Paint (FCP)
Markeert het moment waarop de eerste tekst of afbeelding werd geschilderd.
De FCP test heeft een positief resultaat. 
<img width="197" alt="image" src="https://user-images.githubusercontent.com/90447045/165925261-a96e8cf0-390b-4748-a7d2-72a98d2529ca.png">

### Time to Interactive (TTI)
De hoeveelheid tijd die nodig is om de pagina volledig interactief te maken.
De TTI test heeft een positief resultaat.
<img width="301" alt="image" src="https://user-images.githubusercontent.com/90447045/165925402-0a00b1d9-58ca-4fb2-9cee-36c46e9a3c81.png">

### Speed Index
Laat zien hoe snel de inhoud van een pagina zichtbaar wordt gevuld.

<img width="230" alt="image" src="https://user-images.githubusercontent.com/90447045/165925589-37efdf36-a43b-476f-a257-ecefe766b4b1.png">
<img width="454" alt="image" src="https://user-images.githubusercontent.com/90447045/165925608-1925e9be-4cf7-40ec-a309-687ad61cf106.png">

### Total Blocking Time (TBT)
De TBT test heeft een positief resultaat. 
Som van alle tijdsperioden tussen FCP en Time to Interactive, wanneer de taakduur meer dan 50 ms bedroeg, uitgedrukt in milliseconden.

<img width="260" alt="image" src="https://user-images.githubusercontent.com/90447045/165925767-b38ccec6-20df-4288-8f63-29edcac5d3c0.png">


### Largest Contentful Paint (LCP)
Het markeert het tijdstip waarop de grootste tekst of afbeelding is geschilderd.

<img width="278" alt="image" src="https://user-images.githubusercontent.com/90447045/165925789-c4679986-9c82-4dff-b104-129865c600d5.png">

### Cumulative Layout Shift (CLS)
Het meet de beweging van zichtbare elementen binnen de viewport.

<img width="274" alt="image" src="https://user-images.githubusercontent.com/90447045/165925854-4ea3c7eb-0ecb-4a6a-b00d-00b2d530dafd.png">


## Bronnen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
