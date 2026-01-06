# Project decomposition


Dit top-level diagram geeft een overzicht van het volledige inline kwaliteitscontrolesysteem. Het laat zien hoe verschillende inputs, zoals fles­types, vision-modellen en ISO-normen, samenkomen in het centrale proces. Het systeem levert goedgekeurde en afgekeurde flessen als output, waarbij alle beslissingen worden vastgelegd in een database of ERP-systeem.

![IDEF0 Top Level](./img/A0-IQC.png)


Dit diagram toont de instelfase waarin de vision-modellen worden gekalibreerd op basis van productspecificaties en testinputs. Hierbij wordt gebruikgemaakt van gegevens uit flesmonsters, datasheets en test richtlijnen, met input van de operator en het testlaboratorium. Het resultaat is een geconfigureerd profiel en kalibratiegegevens die in latere fases van het proces worden gebruikt.

![IDEF0 Setting Up](./img/A1-IQC.png)


Dit diagram beschrijft het inline inspectieproces met behulp van vision-technologie.<br>
A2 (Beeldacquisitie): Het vastleggen van afbeeldingen van de flessen met behulp van een camera-opstelling, waarbij belichting en omgevingsfactoren invloed hebben op de beeldkwaliteit.<br>
A3 (Beeldverwerking): Het analyseren van de beelden met getrainde modellen en software om te bepalen of de flessen voldoen aan de kwaliteitscriteria.<br>
A4 (Sorteren): Het scheiden van goede en afgekeurde flessen op basis van de resultaten van de beeldanalyse, waarbij actuatoren en sensoren worden aangestuurd en alle resultaten worden gelogd.<br>

![IDEF0 Process](./img/A234-IQC.png)