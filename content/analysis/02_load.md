---
Title: Load  
Template: analys  
---

# Utvärdering av webbplatsers laddningstid och användbarhet  

## Introduktion  
Denna rapport analyserar och mäter laddningstid och användbarhet av tre olika webbplatser.  

---

## Urval  
De valda webbplatserna är:  
1. [Sean Halpin](https://seanhalpin.design) – En UI/UX-designer som specialiserar sig på användarfokuserad design.  
2. [Elaine Eksvärd](https://elaineeksvard.se/) – En svensk föreläsare, författare och expert på retorik.  
3. [Redeye](https://redeye.se) – En svensk plattform för investeringar och finansiell rådgivning.  

Urvalet baseras på personer som inspirerar mig i mitt dagliga arbete eller i livet utanför jobbet, samt Redeye.se som är webbplatsen för min nuvarande arbetsgivare.  

---

## Metod  
1. **Verktyg som användes**:  
    **Chrome DevTools**: För att mäta laddningstid, antal resurser och sidstorlek.  
    **Google PageSpeed Insights**: För att få Mobile och Desktop-resultat.  
    **Google Sheets**: För att lagra och analysera mätvärden.  

---   

2. **Tillvägagångssätt**:  
    Jag mätte laddningstid med hjälp av Chrome DevTools under fliken "Network" med avaktiverad cache.   
    Dokumenterade snittvärden i ett Google Kalkylark.  
    Mätningar utfördes för både Mobile och Desktop via Google PageSpeed Insights.  

---

## Resultat och analys  

### **1. Sean Halpin**  
**Skärmdump**: ![https://seanhalpin.design](%base_url%/image/sean.png?w=50%)  

**Testade sidor**:  
[Startsidan](https://www.seanhalpin.xyz)  
[Om](https://www.seanhalpin.xyz/about)  
[Notes](https://www.seanhalpin.xyz/notes)  

---

**Mätvärden från Google PageSpeed Insights**:  

**Mobile**: 91  
**Desktop**: 99  

---   

**Snittvärden från DevTools**:  
   Laddningstid: 361 ms  
   Resurser: 48st  
   Total sidstorlek: 1.3 MB  

---   

**Förbättringsförslag**:  
 Optimera bilder och använd moderna format som WebP, format på sidan (png).  
 Minimera CSS och JavaScript för snabbare rendering.  

---

### **2. Elaine Eksvärd**  
**Skärmdump**:  ![https://elaineeksvard.se/](%base_url%/image/elain.png?w=50%)  

**Testade sidor**:  
 [Startsidan](https://elaineeksvard.se)  
 [Om Elaine](https://elaineeksvard.se/om-elaine)  
 [Kontakt](https://elaineeksvard.se/kontakt)  

 ---   


**Mätvärden från Google PageSpeed Insights**:  

 **Mobile**: 100  
 **Desktop**: 100  

---   

**Snittvärden från DevTools**:  
 Laddningstid: 1337 ms  
 Resurser: 66  
 Total sidstorlek: 1.7 MB   

---   

**Förbättringsförslag**:  
 Reducera JavaScript som inte används.  
 Begränsa datainhämtning till sid-specifikt innehåll.  
 Korrigera bildstorlekar som levereras av Gatsby-plugin.  

---

### **3. Redeye**  
**Skärmdump**: ![https://redeye.se/](%base_url%/image/redeye.png?w=50%)  

**Testade sidor**:  
[Startsidan](https://redeye.se)  
[Events](https://redeye.se/events)  
[Tools](https://redeye.se/tools)  

---   

**Mätvärden från Google PageSpeed Insights**:  

**Mobile**: 37   
**Desktop**: 30   

---   

**Snittvärden från DevTools**:  
Laddningstid: 1320 ms  
Resurser: 158  
Total sidstorlek: 10.5 MB  

---   

**Förbättringsförslag**:  
Implementera lazy-loading för JavaScript och använd SSR för att minska laddningstider.  
Optimera bilder genom att använda moderna format som WebP via Cloudinary.  

---

## Data och mätningar  
**Google Sheet-länk**: [Klicka här](https://docs.google.com/spreadsheets/d/1CLrQaNvHPAIM54P0IOh1CWz1b-EZVYYl2Ttuh02IZqI)  

**Inbäddat data**:  
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS8iz1kjrgyvfTyIlhwT6ok5G9Hoxva9s4SwoLUCs1C2bqG28iZ7niwku_-uz1AYD44lUyN4pTWl3dO/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;range=A01:J12&amp;headers=false"  width="100%" height="500" title="Data och mätningar"></iframe>  

---

## Sammanfattning och analys  
Webbplatserna varierade i prestanda och användbarhet.  

---   

**Gemensamma förbättringsåtgärder**:  
 **Bildoptimering**: Genom att använda moderna format som WebP.  
 **Minifiering**: Minska storleken på CSS och JavaScript.  
 **Laddningsoptimering**: Implementera lazy-loading och begränsa mängden data som laddas inledningsvis.  

---   

**Rangordning av webbplatser (bäst till sämst)**:  
1. [Sean Halpin](https://seanhalpin.design)  
2. [Elaine Eksvärd](https://elaineeksvard.se)  
3. [Redeye](https://redeye.se)  

---   

**Gränsvärde för snabb laddningstid**: Under 2 sekunder.  
 Sean Halpin: Klarar gränsvärdet.  
 Elaine Eksvärd: Klarar gränsvärdet.  
 Redeye: Klarar inte gränsvärdet.  

Webbplatsen för Sean Halpin är bäst optimerad för snabba laddningstider och användarvänlighet, medan Redeye behöver betydande förbättringar för att konkurrera i dessa avseenden.  

---

## Referenser  
Analyserade webbplatser:  
1. [Sean Halpin](https://seanhalpin.design)  
2. [Elaine Eksvärd](https://elaineeksvard.se/)  
3. [Redeye.se](https://redeye.se)  

Verktyg: [Google PageSpeed Insights](https://pagespeed.web.dev/), [Chrome DevTools](https://developer.chrome.com/docs/devtools).  

---

## Övrigt  
Namn: Rawa Aref  
