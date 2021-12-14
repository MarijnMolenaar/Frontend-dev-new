# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details>
<summary>uitwerken voor kick-off werkgroep - DONE</summary>

### Auteur:
Marijn Molenaar

#### Je startniveau:
Zwart

#### Je focus:
Responsiveness
 
</details>





## Je website

<details>
<summary>uitwerken voor kick-off werkgroep</summary>

### Je opdracht:
https://www.sneakerjagers.com/

Voor mijn opdracht ga ik de website van Sneakerjagers namaken, met de focus op responsiveness. 
Ik vind het interessant om hier meer over te weten en hoe responsiveness in zijn werking gaat. 

#### Screenshot(s) van de eerste pagina (small screen): 
hier de naam van de pagina  
<img src="images/ss1.PNG" width="375px" alt="Homepagina van de site">

#### Screenshot(s) van de tweede pagina (small screen):
hier de naam van de pagina  
<img src="images/ss2.PNG" width="375px" alt="Sneaker-scroll pagina">
 
</details>



## Breakdownschets (week 1) - DONE

<details>
<summary>uitwerken na afloop 2e werkgroep</summary>

### de hele pagina: 
<img src="images/schets1.png" width="375px" alt="breakdown van de hele pagina">

### dynamisch deel (bijv menu): 
<img src="images/screenshot2.png" width="375px" alt="breakdown van een dynamisch deel">

### wellicht nog een dynamisch deel (bijv filter): 
<img src="images/screeshot3.png" width="375px" alt="breakdown van nog een dynamisch deel">

</details>





## Voortgang 1 (week 2)

<details open>
<summary>uitwerken voor 1e voortgang</summary>

### Stand van zaken
Ik ben begonnen aan het bouwen van de homepagina. Dit is de basis van mijn project, en ook een beginsel voor de 2e pagina. 
Op het moment van schrijven ben ik alle standaard elementen in de pagina aan het zetten, en ze aan het stijlen en positioneren
met css en flexbox. Voor beiden pagina's ga ik grote blokken met content gebruiken waar doorheen gescrolled kan worden.

Web development kan soms erg lastig zijn. Zelf heb ik al flink wat ervaring met frondedn development, maar soms loop ik ook even vast. 
De opdrachten helpen hier goed bij, omdat je de code ook in actie ziet, en niet alleen maar op een slide waar
het niet zoveel betekend. 


### Agenda voor meeting
samen met je groepje opstellen

| Marijn         | Tessa              | Dana         | Sadie            |
| ---            | ---                | ---          | ---              |
| HTML video     | en dit             | Meerdere     | en dan ik dat    |
| achtergrond img| dit als er tijd is |button styling| dit wil ik zeker |
| ...            | ...                | ...          | ...              |
 

### Verslag van meeting
hier na afloop snel de uitkomsten van de meeting vastleggen

- HTML video: Opgelost
- Achtergrond omg: Nog niet opgelost, ga hier zelf nog achteraan

</details>





## Voortgang 2 (week 3)

<details>
<summary>uitwerken voor 2e voortgang</summary>

### Stand van zaken
Het gaat de goede kant op met mijn site. De basis staat nu voor beiden pagina's. Ik ben nu bezig om alle elementen precies goed te positioneren,
en de content aan de site toe te voegen. Maar in principe heb ik nu een solide basis waar ik mee door kan gaan.

Er zijn nog wel wat aandachtspuntjes. Ik ben nu bezig om m.b.v. selectoren alle elementen aan te spreken en de juiste positie te geven. 
Sommige tekstblokjes staan nog niet helemaal recht onder de afbeeldingen, en die wil ik nog goed zien te krijgen. Ook ga ik de kopjes nog
een klein beetje aanpassen, die lijken ook nog niet helemaal op de echte website.

Over het algemeen gaat het goed. Ik heb nog wat to-do's, maar ik ben ervan overtuigd dat ik die allemaal kan aankaarten.

To do:
-Navigatiebalk goed krijgen
-Tekstblok onder sneakerstories sectie rechttrekken aan afbeelding
-Microinteractie toevoegen (zoekbalk of hamburgermenu)
-Site beter responsive maken


### Agenda voor meeting
samen met je groepje opstellen

| student 1      | student 2          | student 3    | student 4        |
| ---            | ---                | ---          | ---              |
| dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
| en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
| ...            | ...                | ...          | ...              |


### Verslag van meeting
hier na afloop snel de uitkomsten van de meeting vastleggen

- punt 1
- punt 2
- nog een punt
- ...

</details>





## Toegankelijkheidstest (week 4)

<details>
<summary>uitwerken na test in 8e voortgang</summary>

### Bevindingen
Lijst met je bevindingen die in de test naar voren kwamen:

- Toetsenbord: Tab werkt nog niet op afbeeldingen/sneakerblokken, omdat deze elementen nog niet kilkbaar zijn d.m.v. een button of ander klikbaar element
- Parkingson: Mijn website is enigsinds goed te gebruiken omdat de buttons groot zijn. 

- Zichtbeperking: De tekst en afbeeldingen zijn goed zichtbaar met zichtbeperkingen

- Concentratieproblemen: De site is te gebruiken terwijl ik een ballon hooghoud

- Screenreader: De screenreader kan alle elementen op de pagina voorlezen, behalve de footer            

#### TAB toets werkt niet overal
SOmmige delen van de site waren niet toegankelijk met de tab toets, omdat die items niet als detecteerbaar element waren gecodeerd, zoals een button of een link. Dit heb ik opgelost door deze elementen waar nodig binnen een <a></a> tag te zetten, zodat ze detecteerbaar werden.




#### Motorische handicap 
Ik heb de website getest met de schokband om, die de gevolgen van parkingson moeten simuleren. Uit deze test is gebleken dat de website nog goed te gebruiken is, omdat mijn site veel gebruikt maakt van grote, klikbare vlakken die makkelijk aangeklikt kunnen worden. 


#### Zichtsbeperking
Ik heb de website getest met een aantal zichtbeperkende brillen. Uit deze test is gebleken dat de tekst nog goed leesbaar is, omdat de tekst op een witte achtergrond staat die veel licht afgeeft.


#### Screenreader
Ik heb een screenreader door de website heen laten lezen. Alle klikbare elementen en tekst kan worden afgelezen, behalve die in de footer. Waar dit aan ligt wil ik nog uitzoeken. Het liefst zou ik wel willen dat dit afgelezen kan worden omdat mijn naam hierin staat en ook de bronvermelding van de afbeeldingen.

</details>





## Voortgang 3 (week 4)

<details>
<summary>uitwerken voor 3e voortgang</summary>

### Stand van zaken
De basis staat nu, alleen moet ik nog de HTML volgens de standaard indelen. Hiervoor kan ik de w3c validator gebruiken om te testen of alles correct staat. Ook kan ik nog wat onnodige css en HTML code weghalen. Dot optimaliseert mijn site en maakt het bestand kleiner. 


### Agenda voor meeting
samen met je groepje opstellen

| student 1      | student 2          | student 3    | student 4        |
| ---            | ---                | ---          | ---              |
| dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
| en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
| ...            | ...                | ...          | ...              |


### Verslag van meeting
hier na afloop snel de uitkomsten van de meeting vastleggen

- punt 1
- punt 2
- nog een punt
- ...

</details>





## Eindgesprek (week 5)

<details>
<summary>uitwerken voor eindgesprek</summary>

### Stand van zaken
hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)

### Screenshot(s)

hier screenshot(s) van je eindresultaat

</details>





## Bronnenlijst

<details open>
<summary>continu bijhouden terwijl je werkt</summary>

Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg).

1. bron 1
2. bron 2
3. ...

</details>