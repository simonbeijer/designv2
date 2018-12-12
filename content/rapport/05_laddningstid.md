---
---
Laddningstid
=======================
Denna redovisning handlar om att mäta tre sidor och se hur snabbt dom laddas, samt om det finns något som kan förbättras på laddningstiden.

Urval
-----------------------

Jag valde tre olika museum efter som att jag tänkte att samtliga har mycket bilder och innehåll för att locka besökare. Jag valde t.e.x fotografiska då jag tänkte att dom skulle ha mycket bilder i sin start sida och hur det påverkar deras prestandard. Sedan Universum som borde ha mycket bilder på djur. Samt Tekniska museet som har mycket bilder på uppfinningar maskiner osv.

Metod
-----------------------

Jag använde mig av Google Page Speed samt att kolla på laddat innehåll i nätverk delan av DevTools där resurser, storlek och tid mäts.

Resultat
-----------------------

[FIGURE src="http://localhost:8080/design/me/redovisa/htdocs/image/fotografiska.png?width=432&height=288&crop-to-fit" class="rapportbild" caption="Fotografiska"]

<table>
<tr>
  <td>Mobil score</td>
  <td>19</td>
</tr>
<tr>
  <td>Desktop score</td>
  <td>84</td>
</tr>
<tr>
  <td>Loadtime Avg.</td>
  <td>3,24 s</td>
</tr>
<tr>
  <td>Resources Avg.</td>
  <td>120 pcs</td>
</tr>
<tr>
  <td>Page size Avg.</td>
  <td>6,7 mb</td>
</tr>
</table>

[FIGURE src="http://localhost:8080/design/me/redovisa/htdocs/image/tekniska.png?width=432&height=288&crop-to-fit" class="rapportbild" caption="Tekniska"]

<table>
<tr>
  <td>Mobil score</td>
  <td>40</td>
</tr>
<tr>
  <td>Desktop score</td>
  <td>99</td>
</tr>
<tr>
  <td>Loadtime Avg.</td>
  <td>1,8 s</td>
</tr>
<tr>
  <td>Resources Avg.</td>
  <td>62 pcs</td>
</tr>
<tr>
  <td>Page size Avg.</td>
  <td>1,85 mb</td>
</tr>
</table>  

[FIGURE src="http://localhost:8080/design/me/redovisa/htdocs/image/universeum.png?width=432&height=288&crop-to-fit" class="rapportbild" caption="Universeum"]

<table>
<tr>
  <td>Mobil score</td>
  <td>34</td>
</tr>
<tr>
  <td>Desktop score</td>
  <td>93</td>
</tr>
<tr>
  <td>Loadtime Avg.</td>
  <td>3,44 s</td>
</tr>
<tr>
  <td>Resources Avg.</td>
  <td>153 pcs</td>
</tr>
<tr>
  <td>Page size Avg.</td>
  <td>4,32 mb</td>
</tr>
</table>

###[Resutlat Analys ](https://docs.google.com/spreadsheets/d/1S5lsQuYh2kzDitVK3wc5fl_KpLntlIVTLigGxz1Ak0E/edit?usp=sharing)



Analys
-----------------------

Jag tänkte att det skulle vara intressant att se hur fotografiska musset skulle fungera efter som att man direkt tänker att det kommer vara en sida med mycket bilder, det var det också.
Samtliga sidor var uppbyggda ganska liknade men det fanns tydlig skillnad mellan dom.

Tekniska var det museum som helt klart av snabbas av dom, dom har mycket bilder men bara två stycken över 100 kB.

Enligt page speed kan man ta bort css kod för att spara tid men det är så gott som tomt på förbättrings möjligheter. Dom använder sig av flera svg och gif filer.
Dock skulle den kunnas göra mer mobil vänlig.

Universum har fem bilder över 100kB, var av två av dom är över 200kB. Page speed säger att man ska fokusera på modernare bild format vilket kan spara över en sec i laddningstider.

På deras mobil så finns det över 16 sec på att använda rätt bild storlek och 14 sec på bildformaten, vilket förstås är mycket.

Dom använder nästa bara jpg och png.

Fotografiska ligger inte så bra till jämfört med dom andra sidorna och blir därmed lägst på  page speed.

Bilderna är väldigt stora på deras hemsida vilket var det jag tänkte skulle vara intressant att se, men tyvärr vet jag inte om dom har lyckat så bra med detta.

Det tar väldigt låg tid att ladda sidan jag märker t.o.m detta när jag går in på sidan första gången den hoppar runt ganska mycket innan det är färdig laddad. Även om jag inte kunnat nått om prestandard på hemsidor så skulle jag nog reagera.

Dom har förstås väldigt mycket bilder, men det är förstora för webben skulle jag säga dom har en bild på 910kb sedan en på 683kB och fem stycken över 400kB.

Enligt page speed så kan dom lösa dessa problem med modernare bildformat och koda bilderna effektivare.
Bilden på 910kB skulle kunna bli 328kB detta skulle dom kunna spara väldigt mycket tid.

Det är väldigt mycket jpg bilder på sidan svg för loggan men inte så mycket annat. Jag trodde nog att en foto hemsida borde ha bättre koll på fil format osv.

Den genom gående linjen i alla dessa museum hemsidor är att dom behöver bli bättre på mobila enheter.

Samtliga ligger lägre än vad jag trodde att dom skulle.

Jag tror att dom kan tjäna mycket på att vara mer tillgängliga där då man ofta använder mobilen om man är på tex resa i Stockholm där alla museum är belägna.

Det skulle underlätta för att hitta information och köpa biljetter osv.

Sedan har dom flesta människorna begränsning på hur mycket mobilt bredband man har att tillgå och man vill inte lägga det på att ladda onödigt stora bilder som ändå inte kan användas fullt ut i mobilen.

Även sökmotorer svarar bättre på snabba sidor och om det finns konkurrens om vilket museum man kan besöka i en viss stad så vill man så klart vara mest tillgänglig.

Referenser
-----------------------

https://developers.google.com/speed/pagespeed/insights/

https://www.fotografiska.com/sto

https://www.tekniskamuseet.se

https://www.universeum.se/sv/

Övrigt
-----------------------

Denna rapport är författad av Simon Beijer.
