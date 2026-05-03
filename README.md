# Programmering för UX-Produktion 2026

## Projekt-Start Mapp

Denna mapp kan ni utgå från som grund för er portfolio/inlämning.

Den innehåller en [index.html](index.html) fil med Tailwind redan länkat samt en mapp för tillgångar så som styling elelr bilder

[Här hittar ni uppgiftsbeskrivningen](https://biggerpixel.notion.site/ux25-programmering-portfolio)

# Saras reflektion kring layout-tekniker och styling

I min portfolio har jag använt flera olika layout-tekniker för att skapa en websida som fungerar både i desktop- och mobilvy. Den huvudsakliga layouten i hero-sektionen är byggd med CSS Grid, eftersom Grid passar bra när man vill styra både kolumner och rader. I desktopvyn placerade jag introtext och availability card i vänster kolumn, medan bilden placerades i höger kolumn. Genom att använda grid-template-areas blir det tydligt vilka delar som ska ligga var, och layouten blir lättare att justera än om den hade byggts med många marginaler eller positionering.

För att göra min layout responsiv, använde jag mig av en media query. På så sätt tar availability card upp hela sidans bredd, vilket gör innehållet mer läsbart på mindre skärmar. Jag har även använt responsiva mått som minmax(), clamp() och CSS-variabler för att sidan ska anpassa sig på olika skärmstorlekar utan att kännas för stel.

Navigationen är byggd med Flexbox, eftersom den består av länkar som ska ligga på rad och centreras. Flexbox passar bra för sådana endimensionella layouter. Jag använder även Flexbox i tagline-texten, där flex-direction: column gör det enkelt att stapla texten och skapa jämna mellanrum med gap.

Availability-kortet använder också CSS Grid för att skapa en tabell-liknande struktur. Jag valde Grid istället för en vanlig HTML-tabell eftersom innehållet främst är en visuell informationsyta, och Grid ger bättre kontroll över kolumner, spacing och responsivitet.

Jag har använt en kombination av Tailwind-klasser, egna CSS-klasser samt id. Jag använde Tailwind för snabb styling av exempelvis spacing och textstorlekar. Jag använde min CSS-fil (main.css) för färger, typsnitt, gradients och grid layout. Jag hade svårt att få till dessa stylings i Tailwind.



# Länk till Figma:

https://www.figma.com/design/9hZGhHZM1qdb1vJRWudCaR/Sara-Inkap%C3%B6%C3%B6l-Portfolio?node-id=0-1&t=nwXQreF4Q6417Tpl-1

