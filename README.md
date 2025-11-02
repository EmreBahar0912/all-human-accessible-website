# Accessible Website

Ontwerp en maak voor een opdrachtgever een component/pagina/site toegankelijk volgens WCAG richtlijnen.

De instructie van deze leertaak staat in [INSTRUCTIONS](https://github.com/fdnd-task/all-human-accessible-website/blob/main/docs/INSTRUCTIONS.md)

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

### Live URL
Mijn Live URL: https://emrebahar0912.github.io/all-human-accessible-website/

In deze sprint heb ik aan de contactpagina gewerkt van AdConnect. Ook heb ik feedback van de oprachtgever werkt van de vorige sprint review. Mijn doel was om de contactpagina simpel, kort en krachtig te houden voor toekomstige gebruikers. De originele contacpagina van AdConnect ziet er zo uit:

<img width="1354" height="563" alt="image" src="https://github.com/user-attachments/assets/1ebb837a-91d5-49fb-af4e-7f172b3c5355" />
<img width="1344" height="560" alt="image" src="https://github.com/user-attachments/assets/7caa8d21-697d-4321-a510-c00045ce4589" />

Ikzelf vond dat er te veel informatie opstaat voor een contactpagina. Als gebruiker wil ik het liefst een korte informatie over een persoon waarmee ik contact wil opnemen en hem/haar kunnen bereiken. Dus als oplossing voor dit probleem heb ik de contactpagina opnieuw ingericht door middel van visitekaartjes te maken voor elk bestuurslid waarmee je contact kunt opnemen.
Zo ziet het eruit op mobiel:
<img width="385" height="594" alt="image" src="https://github.com/user-attachments/assets/6b4ec017-a1dd-483f-8d71-4c433b2aa708" />

- Op tablet krijg je twee kolommen:

<img width="425" height="602" alt="image" src="https://github.com/user-attachments/assets/f448be52-3bdc-48b6-865c-558d3237e52b" />

- En op laptop krijg je drie kolommen:

<img width="652" height="504" alt="image" src="https://github.com/user-attachments/assets/072e9cff-5425-41f0-9ea3-bf02fbbb2022" />

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

### Toegankelijkheid
Ook heb ik me deze sprint gefocust op toegankelijkheid. Het is enorm belangrijk dat een website toegankelijk is voor iedereen. Dit heb ik gedaan door middel van een kleurcontrast test en een WCAG Audit uit te voeren.

Ik heb met kleuren getest of de voorgrondkleuren en achtergrondkleuren goed met elkaar in balans staan. Dit heb ik gedaan met een app genaam Colour Contrast Analyser. Hierin heb ik gecheckt of het contrast voldoende is bij kleine en grote teksten, icons en borders.
- Check hier mijn kleurcontrast testen: https://github.com/EmreBahar0912/all-human-accessible-website/issues/13

Ook heb ik een WCAG Audit uitgevoerd op mijn gemaakte werkt. Dit heb ik gedaan met Lighthouse test, keyboard navigatie test, screenreader test, interactive elements test en headings & landmarks test. Al deze testresultaten heb ik in Github issues gedocumenteerd en de problemen verholpen.
Voor de keyboard navigatie heb ik gebruikgemaakt van JavaScript om ervoor te zorgen dat tabben niet mogelijk is wanneer er een hamburger-menu aanwezig en gesloten is.

<img width="686" height="619" alt="image" src="https://github.com/user-attachments/assets/0f7b37ff-bd8d-4d26-9c62-05ad144aaf14" />

- Check hier mijn WCAG Audit: https://github.com/EmreBahar0912/all-human-accessible-website/issues/12

### Grid-template-areas
Tijdens deze sprint heb ik gebruikgemaakt van wat voor mij een nieuwe methode is, namelijk grid-template-areas. Dit heb ik geïmplementeerd bij de visitekaartjes van de contactpagina. Ik vond hetzelf een handige functie voor responsive layout.

<img width="468" height="605" alt="image" src="https://github.com/user-attachments/assets/7ea63b9e-cc3b-4e54-a7c7-1819c5fff4ba" />

## Bronnen
- Coding2GO YouTube kanaal (grid-template-areas): https://youtu.be/v0o1kV-qfVI?si=QsRY2XUuwdoXd1UZ
- WCAG Audit richtlijnen: https://web.dev/articles/how-to-review
- Kleurcontrast test: Colour Contrast Analyser & a11y checklist https://www.a11yproject.com/checklist/

## Licentie
This project is licensed under the terms of the [MIT license](./LICENSE).
