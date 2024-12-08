---
Title: Analys av laddningstid
Description: Load times analysis page
Template: technologies
---


<div class="menu">
<div class="menu-item">
<a href="../analysis/01_colors">Colors</a>
</div>

<div class="menu-item">
<a href="../analysis/03_design_principles">Design principles</a>
</div>
</div>



<div class="content" markdown="1">

# Analys av laddningstid
Uppgiften handlar om att utvärdera laddningstiden på tre webbplatser.

<br>
Urval
-----------------------

Jag har valt att analysera följande tre webbplatser: Bornolmslinjen, Dagens Industri och Elgiganten. Dessa har jag valt för att få lite spridning i typ av webbplats.

<br>
Metod
-----------------------

Jag använde verktyget PageSpeed Insights för att få fram betyget på respektive sida både på desktop och mobil.

Jag använde DevTools för att analysera laddningstiden, antal resurser och totala storleken på sidan.

Datan sparades i en <a href="https://docs.google.com/spreadsheets/d/1T1-A0zBmADSTkvCdvVeu-DvBChw2D-1A-Ic4GoEEfGs/edit?usp=sharing" target="_blank">Google Sheet</a> för att kunna presenteras i tabellform.

<br>
Resultat
-----------------------

<div class="embed-container">
    <iframe class="table" width="100%" height="500px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRAh2eNMpmhS9bn8HSd0FNFEQEcRgHA94F3q5BB0WUGtBPknDiOMZxQyu2L0LNhSffXG_qF9oD6LrcN/pubhtml?widget=true&amp;headers=false" frameborder="0" allowfullscreen></iframe>
</div>

<br>
1. Bornholmslinjen
<div class="image2">
    <img src="../assets/img/bornholmslinjen.png" alt="Bornholmslinjen">
</div>

<br>
Bornholmslinjens sidor får medelmåttiga poäng i PageSpeed Insights men är ok både på datamängd och laddningstid. Däremot används extremt många resurser, nästan 700. Mobilt får sämre betyg än desktop vilket verkar vara vanligt.

Rekommendationer är att minska körningstiden för JavaScript och minska antalet resurser, minifiera och reducera CSS. 

För mobilvy är det viktigt att minska storleken på bilderna. 


<br>
<br>
2. Dagens Industri
<div class="image2">
    <img src="../assets/img/DI.png" alt="Dagens Industri">
</div>

<br>
Dagens Industri får bättre poäng än Bornholmslinjen på PageSpeed Insights men inte heller här några superbetyg, framför allt på mobil. DI är dock riktigt snabb att ladda och använder inte så många resurser. Datamängden däremot är lite högre än Bornholmslinjen.

Rekommendationer är att minska påverkan från tredjepartskod (annonser mestadels) som gör att sidan inte laddas snabbare.
Även här rekommenderas att minska överflödig JavaScript och CSS samt att bilderna optimeras.

<br>
<br>
3. Elgiganten
<div class="image2">
    <img src="../assets/img/elgiganten.png" alt="Elgiganten">
</div>

<br>
Elgiganten får sämre poäng än Bornholmslinjen och Dagens Industri på PageSpeed Insights. Datamängden är hög framför allt på gamingsidan och laddningstiden är förhållandevis lång.

Rekommendationer är att minska mängden JavaScript och CSS. Använda ett modernare bildformat och minska ner DOM-trädet.


<br>
<br>
Analys
-----------------------

Sammantaget är Dagens Industri vinnaren i denna analys dock inte med lysande resultat. De andra två hamnar på delad andraplats med liknande brister.

Generellt verkar webbplatserna prestera sämre på mobil än på desktop vilket utvecklarna borde tänka på idag när de flesta använder mobilen till det mesta.

Alla tre webbplatserna behöver se över mängden JavaScript och CSS och rensa upp koden från sådant som inte behövs för att förbättra laddningstiden.

Bilder behöver generellt optimeras för att snabba upp sidorna, framförallt på mobilen. Modernare bildformat är att föredra.

Tredjepartskod som annonser är ett stort problem för laddningstiden och bör se till att undvikas i största möjliga utsträckning.

Ingen av de tre sidorna upplever jag som långsam att ladda, de känns helt ok.
Runt 3 sekunder är rimligt för att ladda en sida utan att man känner att man behöver vänta in sidans innehåll. Detta kan ju såklart variera beroende på vilken mobiltäckning man har och hur snabbt internet man har hemma.


<br>
<br>
<br>
Övrigt
-----------------------
Analysen utförd av:

Johnnie Eliasson

</div>
