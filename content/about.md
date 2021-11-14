---
Title: About
Description: About this webpage.
---
Om den här webbplatsen
=======================

Den här webbplatsen är uppbyggd på ett flat-file CMS som heter [Pico](https://picocms.org/). Att systemet är flat-file betyder att man inte behöver använda någon databas eller liknande för att uppdatera innehållet. Det räcker med att uppdatera textfiler - i Picos fall jobbar man med markdown-formatet. Det gör det väldigt smidigt att skapa en ny sida (som den här!) eller ändra i en redan befintlig sida på webbplatsen. När sidorna kompileras blir markdown-filerna till PHP, det är alltså ett så kallat PHP-ramverk.
<br><br>
För att skapa själva HTML-strukturen i dokumenten använder sig Pico av [Twig](https://twig.symfony.com/). Man skriver mallar med hjälp av Twig, vilket gör att webbplatsen blir modulär och det finns en enighet mellan sidorna på webbplatsen.
<br><br>
Temat på webbplatsen, alltså själva stylingen, är skrivet i SASS vilket är en vidareutveckling av CSS. SASS kompileras ned till ren CSS innan det körs på webbplatsen.