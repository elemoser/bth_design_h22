
Utvärdera webbplatsers laddningstid och användbarhet
=======================

I den här rapporten analyserar jag tre olika webbsidor från tre olika webbplatser med fokus på hur snabbt de laddas och hur dem presterar på PageSpeed testet.

I nästa avsnittet går jag djupare in på webbplatserna och webbsidorna som jag valde ut för denna uppgift.
I de efterföljande avsnitten diskuterar jag metoderna som jag använder för att samla in data och resultaten av min utredning.
Slutligen föreslår jag en analys av resultaten och diskuterar om webbsidorna innehåller saker som kan förbättras med tanke på laddningstid och användbarhet.

<h2 id="load-sample">Urval</h2>

För denna uppgift valde jag att mäta presterande av webbplatserna från tre olika miljö- och naturvårdsorganisationer: Greenpeace, WWF och Naturskyddsföreningen.
För varje webbplats valde jag tre sidor att utvärdera som är hemsidan, en sida som uppmanar till handling med antingen donation eller underskrift samt en sida som handlar om haven.
Sidorna och länkarna till dem listas nedan.
Observera att förkortningarna inom parentesen används för att referera till webbsidorna i resultat avsnittet.

- Greenpeace
    - https://www.greenpeace.org/sweden/ (GP_1)
    - https://www.greenpeace.org/sweden/agera/ (GP_2)
    - https://www.greenpeace.org/sweden/tag/havsreservat/ (GP_3)

<figure>
<figcaption>Greenpeace hemsida</figcaption>
<img class="img-website" alt="Greenpeace Landing Page Fold" src="/dbwebb/design/me/portfolio/image/greenpeace.png?w=700&save-as=jpg">
</figure>

- WWF
    - https://www.wwf.se/ (WWF_1)
    - https://www.wwf.se/engagera-dig/ (WWF_2)
    - https://www.wwf.se/hav-och-fiske/hjalp-haven/ (WWF_3)

<figure>
<figcaption>WWF hemsida</figcaption>
<img class="img-website" alt="WWF Landing Page Fold" src="/dbwebb/design/me/portfolio/image/wwf.png?w=700&save-as=jpg">
</figure>

- Naturskyddsföreningen
    - https://www.naturskyddsforeningen.se/ (NSF_1)
    - https://www.naturskyddsforeningen.se/engagera-dig/ (NSF_2)
    - https://www.naturskyddsforeningen.se/lar-dig-mer/hav-och-vatten/ (NSF_3)

<figure>
<figcaption>Naturskyddsföreningens hemsida</figcaption>
<img class="img-website" alt="Naturskyddsföreningen Landing Page Fold" src="/dbwebb/design/me/portfolio/image/naturskyddsforeningen.png?w=700&save-as=jpg">
</figure>

När jag bläddrade igenom dessa webbsidor märkte jag att vissa laddades snabbare än andra.
Särskilt bilder verkar ta längre tid att ladda än resten av sidan.
I allmänhet skulle jag säga att alla nio webbsidor laddas inom en acceptabel tidsram på både mobil och dator.
Jag känner vanligtvis att en webbsida är långsam när laddningstiden är längre än 3 sekunder.
Det är därför jag definierar min gränsnitt vid 3 sekunder.
Allt kortare än så är en snabb laddningstid, och allt längre än så är en långsam laddningstid.
I resultaten och analysen diskuterar jag hur de valda webbsidorna presterar med tanke på detta 3 sekunder gränsvärde.


Metod
-----------------------

I det här avsnittet förklarar jag metoderna jag använder för att samla in data för den här undersökningen.

Jag använder PageSpeed[^1] för att utvärdera användarupplevelsen av en sida på både mobil och dator.
PageSpeed ​​ger fyra betyg som ligger mellan 100 (bäst) och 0 (sämst) och baseras på flera mätningar:[^2]
* Performance
* Accessibility
* Best Practices
* SEO


För att analysera webbsidornas prestanda samlade jag också in tre mätningar med hjälp av inspektionsverktyget som finns i webbläsaren (i mitt fall Google Chrome).
De här mätningarna är:
* Sidans laddningstid i sekunder
* Antalet resurser som laddas i MB
* Sidans totala storlek i MB

För varje sida gjorde jag mätningen tre gånger och räknade snittet av mätvärdena.
Alla resultat från undersökningen presenteras i nästa avsnittet.

Resultat
-----------------------

I det här avsnittet presenterar jag resultaten från datainsamlingen.
Tabellen nedan visar betygen från PageSpeed ​​och mätningar som erhållits med inspektionsverktyget.[^3]
Observera att rådata finns i det sista arket ("<a href="https://docs.google.com/spreadsheets/d/1Ysb2wtklOT2idD7C6kgdQ-Hz2SVeS-Ws4DcKSfe6fXk/edit?usp=sharing">all_data</a>").

<div class="embed-container">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRnfYXjhLj3C0EkNvfHRQhF28QOX27y7PGnLGcvxQ27zQoPIvI0gtiAtHpU4NBercEghh9kGqs4e1Pm/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

## Betyg från PageSpeed

Tabellen ovan visar betygen från PageSpeed på det första arket ("PageSpeed_results").
Efter PageSpeeds notation är alla värden över 90 markerade i grönt och alla värden under 50 är markerade i rött.
Ett betyg över 90 anses vara bra och ett betyg under 50 anses vara dåligt.

### Greenpeace

Greenpeace visar de bästa resultaten i sitt *SEO* betyg.
Alla tre utvalda sidor får mellan 92 och 100 poäng på både mobil och dator.
Sammantaget får sidorna acceptabla betyg i kategorierna *Accessibility* och *Best Practices*.
De tre utvalda Greenpeace sidorna presterar dock suboptimalt i *Performance* på mobil.
I den kategorin, når webbsidorna inte mer än 30 poäng.

### WWF

WFF presterar bäst i kategorin *Performance*, men bara på dator.
Prestanda på mobila enheter är ganska dålig.
Den högsta poängen bland de tre webbsidorna är inte mer än 43 på mobil i *Performance*.
Betyget för *SEO*, *Accessibility* och *Best Practices* är acceptabelt både på mobil och dator.

### Naturskyddsföreningen

Naturskyddsföreningen presterar bäst i kategorin *Best Practices*.
Alla tre utvalda sidor får mellan 91 och 92 poäng på både mobil och dator.
I kategorierna *Accessibility*, *Best Practices* och *SEO* visar Naturskyddsföreningens webbsidor acceptabla betyg.
Däremot presterar sidorna dåligt i kategorin *Performance* på mobila enheter.

## Mått från inspektionsverktyget i webbläsaren

Tabellen ovan visar genomsnittet av alla tre mätningar, d.v.s sidans laddningstid, antalet resurser som laddas samt sidans totala storlek, som erhållits med inspektionsverktyget på det andra arket ("Inspect_results").

I det följande diskuterar jag laddningstidsresultaten för varje webbplats med tanke på laddningsgränsen som definieras i avsnittet <a href="#load-sample">urval</a>.
Som en påminnelse, en laddningstid under 3 sekunder räknas som snabb och en laddningstid över den tidsramen räknas som långsam.

### Greenpeace

I genomsnitt laddas Greenpeaces hemsida (GP_1) på 3,29 sekunder, vilket enligt den definierade gränsen räknas som ganska långsamt.
Sidan med den kortaste laddningstiden bland de tre utvalda webbsidorna är Greenpaces Agera-sidan (GP_2) som tar 2,86 sekunder att ladda i genomsnitt.
Sidan med den längsta laddningstiden bland alla tre är webbsidan som handlar om havreservat (GP_3) som tar 3,64 sekunder att ladda i genomsnitt.
Den totala genomsnittliga laddningstiden för alla tre Greenpeace sidor är 3,26 sekunder, vilket är över gränsen på 3 sekunder och därför kategoriseras Greenpeace som en långsam webbplats.

### WWF

I genomsnitt laddas WFFs hemsida (WWF_1) på 2,86 sekunder, vilket enligt den definierade gränsen räknas som snabbt.
Sidan med den kortaste laddningstiden bland de tre utvalda webbsidorna är Engagera-dig-sidan (WWF_2) på WWFs webbplats.
Denna tar 2,65 sekunder att ladda i genomsnitt.
Sidan med den längsta laddningstiden bland alla tre är webbsidan som handlar om haven (WWF_3) som tar 3,01 sekunder att ladda i genomsnitt.
Den totala genomsnittliga laddningstiden för alla tre WFF sidor tillsammans är 2.84 sekunder.
WFF kategoriseras alltså som en snabb webbplats.

### Naturskyddsföreningen

Naturskyddsföreningens hemsida (NSF_1) laddas i genomsnitt på 3.06 sekunder, vilket är något över 3 sekunders-gränsen men förmodligen ändå upplevs som relativt snabbt.
Sidan med den kortaste laddningstiden är Engagera-dig-sidan (NSF_2) på Naturskyddsföreningens webbplats, vilken laddas i genomsnitt på 2.86 sekunder.
Sidan med den längsta laddningstiden bland alla tre är webbsidan som handlar om haven (NSF_3) som tar 3,08 sekunder att ladda i genomsnitt.
Den totala genomsnittliga laddningstiden för alla tre Naturskyddsföreningen sidor tillsammans är exakt 3 sekunder.
Webbplatsen ligger precis på den definierade gränsen som räknas som snabb laddningstid.


Analys
-----------------------

Alla nio webbsidor på alla tre webbplatser presterar olika, men ändå finns det vissa mönster som framträder.


## Låga betyg för *Performance* på mobila enheter

I resultat avsnittet visas att alla nio sidorna presterar sämst i kategorin *Performance* på mobila enheter.
Det finns en tydlig kontrast till prestationen i de andra kategorierna.
Den högsta poängen i denna kategori bland alla nio webbsidor får WWFs hemsida med betyget 43.

För att kolla om andra typer av webbplatser presterar bättre utvärderade jag [dbwebb.se](dbwebb.se/) och [bth.se](https://bth.se/) i PageSpeed.[^4]
Den förra uppnår ett betyg på 92 i *Performance* på mobila enheter.
Den senare å andra sidan får 32 för samma kategori.
Det finns ingen tydlig slutsats att dra här förutom att få ett bra resultat på *Performance* verkar utmanande för de flesta webbsidor.

PageSpeed ​​erbjuder ett antal förslag till förbättringar i denna kategori.
Ett förbättringsförslag som visas för nästan alla utvärderade sidor är att minska oanvänd CSS- eller JavaScript-kod (d.v.s "reduce unused CSS","reduce unused JavaScript").
Därefter verkar det som att alla webbsidor kan förbättras när det gäller bildhantering.
PageSpeed ​​nämner att använda lämpligare storlekar ("properly size images"), koda bilderna mer effektivt ("efficiently encode images") och skjuta upp bilder utanför skärmen ("defer offscreen images").
I detta kursmoment har vi också diskuterat detta under lektionen: Bilder kan i hög grad påverka laddningstiden men också den allmänna prestandan för en webbsida.

<!-- 
- PageSpeed suggestions for improvement:
    - serve images in next-gen formats
    - eliminate render-blocking resources
    - enable text compression
    - avoid serving legacy JavaScript to modern browser -->


## Längre laddningstid för havet

För den här utredningen tittade jag på laddningstiden för tre sidor på webbplatserna för Greenpeace, WWF och Naturskyddsföreningen.
För var och en av dessa webbplatser valde jag liknande "typer" av webbsidor att undersöka, det vill säga hemsidan, sidan som uppmanar till handling och en sida som informerar om något havsrelaterade problem.
Intressant nog visar de olika typerna av webbsidor liknande mönster i laddningstid.
Den webbsidan som laddas snabbast jämfört med de andra för alla tre webbplatserna är sidan som uppmanar till handling.
Det kan bara vara en slump, men i allmänhet betyder en kort laddningstid för en sida att användarna kommer att få en bättre användarupplevelse och stanna kvar på den längre i genomsnitt.[^5]
Så en kort laddningstid för en sida, där besökare uppmanas att engagera sig och donera till en sak, verkar särskilt viktig.

För alla webbplatser var hemsidans laddningstid längre än sidan där organisationerna uppmanar till handling.
Dock webbsidor som visar längst laddningstid för alla tre webbplatser är sidorna som informerar om något havsrelaterade problem.
Jag har inte lyckats hitta en bra förklaring till detta mönster.
Jag misstänker dock att antalet havsrelaterade problem inte har någon effekt på laddningstiden, utan snarare antalet klick som behövs för att nå dessa sidor.
Webbsidorna som är dedikerade till havsfrågorna ligger flera steg bort från hemsidan och sidan för donationer.
Detta kan ses i webbadresserna till dessa sidor (se avsnittet <a href="#load-sample">Urval</a>).
Prestanda för dessa sidor är inte lika avgörande som en användarvänlig hemsida eller donationssida.
<!-- Kanske finns det en bättre förklaring till detta, men det ligger utanför detta projekts ram.-->

## Rangordning

Sammantaget presterar WWF bäst, men det är inte den klara vinnaren i alla kategorier.
Greenpeace får högst poäng i PageSpeed-utvärderingen.
Den uppnår mycket poäng med sin prestanda i SEO-kategorin.
Men Greenpeace presterar sämst jämfört med WWF och Naturskyddsföreningen i kategorin *Prestanda* på mobila enheter.
Dessutom, även om Greenpeace presterar bäst i PageSpeed-utvärderingen, presterar den sämst i laddningstidsutvärderingen.
Båda WWF och Naturskyddsföreningen göt mycket bättre än Greenpeace med tanke på den genomsnittliga laddningstiden för webbsidor.
WFF får bara något lägre poäng än Greenpeace i PageSpeed-utvärderingen, men det är den klara vinnaren i utvärderingen av laddningstid.
Som nämnts i resultatavsnittet överträffar Naturskyddsföreningen Greenpeace och WWF i kategorin *Best Practices*, annars presterar den dock inte bättre än konkurrensen.
Det verkar därför som att WWF totalt sett rankas högre än Greenpeace och Naturskyddsföreningen.


Övrigt
-----------------------

Denna rapport skrevs inom kmom05 av kursen *Teknisk webbdesign och användbarhet*.

Författare: Elena Moser (elmo22)


Referenser
-----------------------

[^1]: <a href="https://pagespeed.web.dev/" target="_blank">PageSpeed (visited 2022-12-04)</a>

[^2]: <a href="https://developer.chrome.com/docs/lighthouse/performance/performance-scoring/?utm_source=lighthouse&utm_medium=lr">PageSpeed Insights Documentation (last visited 2022-12-04)</a>

[^3]: Utvärderad 2022-12-04

[^4]: Utvärderad 2022-12-05

[^5]: <a href="https://web.dev/why-speed-matters/">Why does speed matter?</a> (last visited 2022-12-6)
