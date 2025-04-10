# 🌍 Way Out West – Tillgänglig & Responsiv Redesign

Detta projekt är en omarbetning av **Way Out Wests officiella hemsida**, med syfte att förbättra **tillgänglighet**, **användarvänlighet** och **responsiv design**. Vi har fokuserat på att anpassa sidan för flera olika skärmstorlekar och säkerställa att alla användare, oavsett förmåga eller enhet, får en positiv upplevelse.

---

## ✨ Vad vi gjort

- Förbättrat semantiken i HTML-strukturen  
- Justerat färgkontraster enligt WCAG-riktlinjer  
- Lagt till alternativa texter på samtliga bilder  
- Infört tydliga fokusmarkeringar för tangentbordsnavigering  
- Implementerat en responsiv layout med tydliga brytpunkter  
- Använt SASS för mer strukturerad och återanvändbar CSS  
- Infört animationer och övergångar för förbättrad interaktivitet  
- Integrerat ett tillgängligt formulär i footern med hjälp av Bootstrap

---

## 📱 Breakpoints & Responsiv design

Vi använder två huvudsakliga **breakpoints** för att stödja tre enhetstyper:

- **Mobil:** upp till 767px (t.ex. iPhone XR)  
- **Tablet:** 768px – 1199px (t.ex. iPad Air)  
- **Desktop:** 1200px och uppåt

Responsiviteten hanteras med media queries för att säkerställa att layout, text och bilder anpassas smidigt över olika enheter.

---

## 🎨 Dynamiska effekter & funktionalitet

Vi har använt **CSS-animationer och övergångar** för att förbättra den visuella upplevelsen:

- **Headerbanderoll:** Animeras och visas konsekvent på alla skärmstorlekar  
- **Knappövergångar:** Färgskiftning med `transition: 0.4s` vid hover  
- **Bilder:** Smidig inzoomningseffekt vid hover

---

## 🧩 Ramverk

Vi har integrerat **Bootstrap** i formulärsektionen (footern).  
Själva inmatningsfältet är omstylat, men knappen från Bootstrap används i modifierad form.

---

## 🧪 Tillgänglighetstester

För att säkerställa tillgänglighet har vi använt:

- **Wave** (webbtillgänglighetsverktyg)  
- **W3C HTML Validator**  
- **Skärmläsartest (VoiceOver)**  
- **Tangentbordsnavigeringstest**

Vi upptäckte flera tillgänglighetsbrister på originalhemsidan, såsom felaktig rubrikstruktur, svaga kontraster och avsaknad av `alt`-texter på bilder. Dessa åtgärdades i vår version.

---

## 💅 Användning av SASS

Vi doppade tårna i SASS, framför allt för:

- **Nestad styling av typsnitt** för konsekvent typografi  
- Styling av **bilder, knappar och komponenter**  
- Förbättrad struktur i vår CSS-kodbas

