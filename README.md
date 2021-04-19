## Ressource:

---

**Start og lukning af node-server**

Start en terminal på din computer. Hvis du ikke står i projektets folder, kan du navigere dertil med <code>ls</code> ("list". Oplister filer i den mappe du står i), og <code>cd</code> ("change directory". Skifter til den mappe du angiver, eksempelvis "cd Documents").

Når terminalen er i projektets egen mappe, kør følgende kommando for at starte node-serveren.

<code>
  npm run start
</code>

Derefter kan du se det lokale site i browseren ved at gå til http://localhost:8080/

---

**Upload sitet til fjernserver**

Start endnu en terminal i projektets mappe, og skriv

<code>npm run deploy</code>

Denne kommando tager alle filer i _site-mappen og uploader dem til fjernserveren. Dermed er sitet på nettet.

---










---

## Cantina workshop

### 14.-15. April 2021

_  
Workshoppens fokus er design og kodning af et nyt website for Cantina. Workshoppen præsenterer en enkel kodebase, der giver deltagerne adgang til at administrere indhold på Cantinas kommende website -og giver dem samtidig tilstrækkelig kode-kendskab til, at de selv kan oprette, designe og redigere websites -eksempelvis til eget brug.

Denne side er workshoppens videns- og kodebase. Siden opdateres løbende med indhold, der kan hjælpe deltagerne i arbejdet. websites kode kan også downloades herfra, når workshoppen begynder.

***Det er vigtigt at nævne, at ressourcen her ikke er lektier! ;-) .. Workshoppen gennemgår nedenstående teknologier på workshoppens første dag, da det er vigtigt at gennemgå sammen*** ... D. 14. April starter jeg (Anders) med at introducere de nødvendige teknologier &mdash; i en slags "set-it-and-forget-it"-mode &mdash; og derefter koncentrerer vi os om design og indhold. Hvis man gerne selv vil studere teknologierne inden workshoppen, giver denne ressource mulighed for det.  
*

**Intro. Præsentation af teknologi og frameworks:** 
1. Static Site Generators 
2. Eleventy
3. Node.js
4. Markdown
5. Visual Studio Code
<br/><br/>

---

**1)**

**Static Site Generators**

Først - Hvad er en ***static site generator***?... Hjemmesider kan generelt opdeles i to kategorier - statiske og dynamiske. Et statisk websted er meget som det lyder - statisk, fast, konstant. Det vil sige, at sitet er designet, gemt på en server og leveret til brugerens webbrowser som den er. Det skifter ikke mellem det punkt, hvor udvikleren rammer knappen "Gem", og når slutbrugeren klikker på den. Udviklere opretter indholdet ved hjælp af HTML, formaterer det med CSS og uploader den statiske side til en server, hvor det forbliver uændret og klar til adgang via en browseranmodning.

Modsat er dynamiske websteder i en næsten konstant forandringstilstand og drives typisk af et CMS. CMS bygger bogstaveligt talt hver side efter behov hver gang en bruger klikker på den. Udviklere opretter indhold, der er gemt i en back-end-database. Når en bruger anmoder om en URL, henter det CMS-drevne websted det relevante indhold fra databasen, indlæser en HTML-skabelon, gengiver indholdet i skabelonen og returnerer en formateret HTML-side til den besøgendes browser - en proces kendt som *server-side processing*.

Læs (engelsk): https://www.netlify.com/blog/2020/04/14/what-is-a-static-site-generator-and-3-ways-to-find-the-best-one/

Video-intro: https://www.youtube.com/watch?v=3INXQ_4W42g
<br/><br/>

---

**2)**

**Eleventy (11ty)**

Eleventy (eller 11ty) er en Node.js-baseret static site generator (SSG). SSG'er renderer et sæt statiske HTML-, CSS- og JavaScript-filer, der derefter uploades til nettet. Sitet er derfor mindre afhængigt af server-teknologier.

Dette giver flere vigtige fordele:  
_ Hosting er enkelt: du viser næsten udelukkende HTML.  
_ Systemet er sikkert: der er ikke noget at hacke.  
_ Performance er optimal, da alt er renderet på forhånd.  

11ty wesbite: https://www.11ty.dev/
<br/><br/>

---

**3)**

**Node.js**

Node.js er en server-side-splatform bygget på Google Chrome's JavaScript Engine (V8 Engine). Node.js blev udviklet af Ryan Dahl i 2009.

Node.js er en open source-platform, og et runtime-miljø til udvikling af servere og netværksapplikationer. Node.js-applikationer er skrevet i JavaScript og kan køres inden for Node.js-runtime på OS X, Microsoft Windows og Linux.

Node.js tilbyder også et rigt bibliotek med forskellige JavaScript-moduler, som forenkler udviklingen af webapplikationer ved hjælp af Node.js i høj grad.

Intro til node.js (video, Dan Shiffman): https://www.youtube.com/watch?v=RF5_MPSNAtU
<br/><br/> 

---

**4)**

**Markdown**

Markdown er et let *markup-sprog*, som du kan bruge til at tilføje formatering til almindelige tekstdokumenter. Markdown blev oprettet af John Gruber i 2004 og er nu et af verdens mest populære markup-sprog.

Brug af Markdown er anderledes end at bruge en WYSIWYG-editor. I et program som Microsoft Word klikker du på knapper for at formatere ord og sætninger, og ændringerne er synlige med det samme. Markdown er anderledes: Når du opretter en Markdown-formateret fil, tilføjer du Markdown-syntaks til teksten for at angive, hvilke ord og sætninger der skal se anderledes ud.

Link til intro: https://www.markdownguide.org/

video intro: https://www.youtube.com/watch?v=f49LJV1i-_w&t=197s
<br/><br/>

---

**5)**

**Visual Studio Code**

Visual Studio Code er en freeware kode-editor lavet af Microsoft til Windows, Linux og macOS. Funktionerne inkluderer understøttelse af fejlretning, syntaksfremhævning, intelligent kodefærdiggørelse, uddrag, kodeomdannelse og integreret Git. Brugere kan ændre temaet, tastaturgenveje, præferencer og installere udvidelser, der tilføjer yderligere funktionalitet.

Intro (video, engelsk): https://www.youtube.com/watch?v=S320N3sxinE
<br/><br/>

---

**Ressourcer:**

Let’s Learn Eleventy!  
https://www.learnwithjason.dev/lets-learn-eleventy

Google webfont helper tool (til at embedde webfonte med, uden at skulle trække dem fra Googles servere = self hosted):
https://google-webfonts-helper.herokuapp.com/fonts











