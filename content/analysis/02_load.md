---
Title: Bilder
Template: analysis
---

<h1>Utvärdering av webbplatsers laddningstid och användbarhet</h1>

<p>I denna rapport ska jag välja samt analysera 3 olika hemsidor baserat på deras laddningstid och användbarhet.</p>

<h2>Urval</h2>
<p>Jag valde att analysera sidorna twitter.com, instagram.com samt linkedin.com och jag valde dessa eftersom sociala medier är så pass stora idag så ville se hur just dessa hanterar så mycket information. Jag ville helt enkelt undersöka hur just dessa  hanterar så stort dagligt flöde av information/bilder och samtidigt hur det påverkar dess laddningstid.</p>

<h2>Metod</h2>
<p>För att få fram samt jämföra de olika webbsidornas laddningstid använde jag mig av verktyget "Google PageSpeed Insights". Detta verktyg gav mig ett specifikt betyg mellan 0 och 100 på vad som gjorde att sidan laddades snabbare/långsammare. Sen använde jag mig också av verktyget Devtools som är inbyggt i de flesta av dagens moderna webbläsare. Med det verktyget fick jag fram all sorts information som t.ex: sidornas laddningstid, antal resurser samt storlek av hemsidan.</p>

<div class = "iframe">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQLvWfsfdYLJ4GVS7BsEDS7EsAqAkpV01-UErC6tblwwBRZHiFcq1Iz80kyIaZZmo2bLl7f3rVnAFBm/pubhtml?widget=true&amp;headers=false" style= "height: 300px; width: 650px;"></iframe>
</div>

<h2>Resultat</h2>

<p>Förbättringar</p>


<h1>LinkedIn</h1>
![linkedin](%assets_url%/img/linkedin.png){.webbplats}

<p>LinkedIn kunde har laddats in en aning snabbare om sidan skulle tagit bort onödig Javascript-kod som inte alls används. Då hade både sidan för mobile och desktop sparat ett antal viktiga sekunder på att reducera hela tiden upprepande omdirigeringar samt ta bort vissa resurser som blockerar sidans rendering. </p>

<h1>Twitter</h1>
![twitter](%assets_url%/img/twitter.png){.webbplats}

<p>Twitter skulle också kunnat ladda in snabbare genom att ta bort onödig Javascript-kod som inte används för varken desktop eller mobile-versionen.</p>

<h1>Instagram</h1>
![instagram](%assets_url%/img/instagram.png){.webbplats}

<p>Instagram hade kunnat spara lite laddningstid genom att bli av med Javascript-kod så som på de andra hemsidorna. Samt så kunde sidan använda sig av lite mer modernt bildformattering än vad som används för att ladda in snabbare. Mobilvarianten skulle också kunna ta bort onödig CSS-kod som jag insåg inte användes alls.
 </p>

 <h2>Analys</h2>

 <p>Det jag har kommit fram till efter undersökningen av sidorna var att alla dessa sidor presterar mycket bättre på deras desktop- variant jämfört med mobile-varianten. Dom sidorna skulle kunnat förbättra dess laddningstid för mobila enheter genom att t.ex tänka mer på dess responsivitet samt försöka anpassa innehållet mot just mobila enheter. </p>

 <p>Om man kollar på Instagram först och främst, så hade hemidan presterat en aning bättre om t.ex bilderna hade optimerats för rätt bildformat än vad det används just nu. Eftersom bildernas format, kvalite samt storlek spelar rätt så stor roll på hur länge en sida laddas in så skulle t.ex JPEG formatet av bilder vara ett bra alternativ för Instagram. JPEG-format har både rimligt kvalite och tar relativt liten filstorlek. </p>

 <p>Instagram skulle också kunnat spara lite av sidans laddningstid genom att analysera igenom sin CSS-kod och välja ut den CSS som verkligen måste användas och sedan ta bort den resterande "onödiga" koden som inte alls används. Sedan skulle Instagram också kunna använda sig av SCSS-baserad kod som vi gör i denna kursen. Att importera flera filer in i CSS kan göra sidan lite snabbare eftersom det finns mindre tecken man använder sig av innuti filerna. </p>

 <p>Samtliga sidor hade kunnat förbättra sin laddningstid genom t.ex borttagning av onödig Javascript-kod som aldrig användes och som förekom på varje hemsida och där gäller samma princip av tänkande som för CSS. </p>

 <p>En annan sak jag insåg var att LinkedIn använde sig av flera renderingsblockerande resurser och det påverkar laddningstiden på hemsidan rätt negativt. Detta problem kan dock åtgärdas genom att flytta på all onödig Javascript samt jquery resurser från renderingbanan. Vanligtvis använder man sig av t.ex async innuti HTML-skriptet som kallar på Javascript-resurserna.</p>

 <h2>Rankning av hemsidorna</h2>

 <p>Enligt min undersökning så klarade Twitter sig bäst av alla testade sidor när det gäller laddningstid per antal resurser. Twitter laddades in på medelvärdet av 571ms samt hämtade 137 resurser. Samtidigt fick Twitter också högst genomsnittligt betyg av Google Page Insights för både mobile och desktop-varianterna. Även om LinkedIn hämtade fler resurser än vad Twitter gjorde i snittbetyg (ca 163 resurser) så laddades sidan in mycket långsammare jämfört med Twitter (2.39 sekunder).
 När det gäller Instagram så tog det nästan lika lång tid att ladda in sidan som för LinkedIn (2.36 sekunder) även om Instagram använde mindre än hälften så många resurser som LinkedIn (ca 68 resurser). Därför ger jag det sämsta rankningen för just Instagram.</p>

 <h2>Upplevelsen av Laddningstiden för hemsidorna</h2>

 <p>Enligt mig så borde en hemsida inte överstiga 10 sekunder när det gäller dess laddningstid. Den typen av gräns gör att användaren inte ska tappa fokus av det en ska göra eller få ett negativt första intryck/uppfattning av hemsidan.</p>

 <p>I min rapport så klarade alla samtliga hemsidor just den gränsen. Twitter laddades in för mig som snabbast i undersökningen eftersom det låg på under 1 sekunds tid och just den snabba responsen gav mig ett väldigt positivt första intryck av själva webbsidan. Men även Instagram och LinkedIn som laddades in på runt 2 sekunder kändes väldigt snabba när det gällde responsen.</p>

 <h2>Övrigt</h2>

 <p>Marceli Lagodziuk, malz20, har skrivit denna rapport.</p>