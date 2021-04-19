## Ressource:

---

**Start af node-server, til udvikling**

Start en terminal på din computer. Hvis du ikke står i projektets folder, kan du navigere dertil med <code>ls</code> ("list". Viser filerne i den mappe du står i), og <code>cd</code> ("change directory". Skifter til den mappe du skriver navnet på&mdash;eksempelvis "cd Documents").

Når terminalen er i projektets egen mappe, kør følgende kommando for at starte node-serveren.

<code>npm run start</code>  

Derefter kan du se det lokale site i browseren ved at gå til http://localhost:8080/

---

**Upload sitet til internettet**

Start endnu en terminal i projektets mappe, og skriv

<code>npm run deploy</code>

Denne kommando tager alle filer i _site-mappen og uploader dem til fjernserveren. Dermed er sitet på nettet.

---

**Øvrige terminal-kommandoer:**

<code>clear</code> (Rydder skærmen i terminalen)  
<code>node -v</code> (Viser din node-version (og at du har node installeret korrekt))  
<code>npm -v</code> (Viser din version af *node package manager*)


---



_  



---

**Ressourcer:**

Let’s Learn Eleventy!  
https://www.learnwithjason.dev/lets-learn-eleventy

Google webfont helper tool (til at embedde webfonte med, uden at skulle trække dem fra Googles servere = self hosted):
https://google-webfonts-helper.herokuapp.com/fonts











