# 📅 Schema vecka 6

**Next.js, vecka 2 av ?**

Vi lämnar statisk data och börjar arbeta med riktiga API:er. Fokus ligger på att hämta, visa och styra data via URL:en.

---

## 📅 Måndag

Vi introducerar konceptet API:er och börjar hämta extern data till vår applikation.

### Mål för dagen

* Förstå skillnaden och teorin bakom olika API-typer (REST vs GraphQL)
* Introduktion till "The Shop" (eller Futurama) – vi skapar ett projekt för att visa produkter/karaktärer
* Kunna hämta data (fetch) och visa upp det i komponenter
* Förstå hur data flödar från en extern källa till vårt gränssnitt

### Läsning

* **Viktigt** - Data Fetching fundamentals - [https://nextjs.org/docs/app/building-your-application/data-fetching/fetching-caching-and-revalidating](https://nextjs.org/docs/app/building-your-application/data-fetching/fetching-caching-and-revalidating)
* Om REST (översiktligt) - [https://aws.amazon.com/what-is/restful-api/](https://aws.amazon.com/what-is/restful-api/)
* Om GraphQL (översiktligt) - [https://graphql.org/learn/](https://graphql.org/learn/)

### Slides

* [API:er](https://docs.google.com/presentation/d/1xHPIuuKB4ehC8Jdzpvm3PeaD2NWPmGQI1pvHfEzxdsQ/edit?usp=sharing)

### Bra att ha-länkar från föreläsningen

* [PokéAPI (REST)](https://pokeapi.co/)
* [PokéAPI (GraphQL)](https://beta.pokeapi.co/graphql/console)
* [Hoppscotch](https://hoppscotch.io/)
* [Swagger](https://api.escuelajs.co/docs#/products/ProductsController_getProduct)
* [Exempel på olika API:er](https://developer.mozilla.org/en-US/docs/Web/API)

### Repo från föreläsningen

* [Lektion 2 feb]() 

### Övningar

* Bygg upp grunden för API-projektet "Shop" (eller Futurama).
* Skapa en komponent som hämtar en lista med data från ett öppet API och renderar ut det på sidan.

---

## 📅 Tisdag

Vi byter källa för våra karaktärer från json till API

### Mål för dagen

* Server Fetch: Hämta data med fetch
* Lite om felhantering (try/catch och state)
* Hur man kan tänka kring logig och lager när det gäller fetch
* Om vi hinner: Dynamisk metadata (t.ex. att sidans titel blir produktens namn) och/eller streaming med suspense

### Läsning

* Data Fetching Patterns - [https://nextjs.org/docs/app/building-your-application/data-fetching/patterns](https://nextjs.org/docs/app/building-your-application/data-fetching/patterns)
* Generating Metadata - [https://nextjs.org/docs/app/api-reference/functions/generate-metadata](https://nextjs.org/docs/app/api-reference/functions/generate-metadata)
* Hantera Not Found programmatiskt - [https://nextjs.org/docs/app/api-reference/functions/not-found](https://nextjs.org/docs/app/api-reference/functions/not-found)

### Övningar
* Byt ut hårdkodade kort mot data från API:et.
* Implementera en kontroll: Om en produkt/karaktär inte finns i API:et ska användaren skickas till en 404-sida.
* (Valfritt) Lägg till `generateMetadata` för detaljsidorna.

---

## 📅 Onsdag

Vi lär oss styra sidans innehåll via URL:en med hjälp av `searchParams`.

### Mål för dagen

* Förstå URL State Management: Varför vi vill ha filter och sökningar i URL:en
* Kunna använda `searchParams` i server components (page props)
* Göra en ny `fetch` baserat på vad som står i `searchParams`

### Läsning

* `searchParams` prop - [https://nextjs.org/docs/app/api-reference/file-conventions/page#searchparams](https://www.google.com/search?q=https://nextjs.org/docs/app/api-reference/file-conventions/page%23searchparams)
* URL Search Params (MDN) - [https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams)

### Övningar

* Implementera sök/filtrering i din shop/futurama-app.
* När användaren söker/filtrerar ska URL:en uppdateras (t.ex. `?category=electronics`).
* Sidan ska ladda om datan baserat på parametern.

---

## 📅 Torsdag

APL-DAG (Arbetsplatsförlagt lärande)

---

## 📅 Fredag

APL-uppföljning och kod-reflektion.

### Mål för dagen


**Frågor för Code Review:**

### Övningar

* **Final Polish:** Se till att din sökfunktion fungerar felfritt och att URL:en ser snygg ut.
* Fortsätt söka APL-platser.

---

## Extra material för hela kursen i next.js

Samma länkar som tidigare för den som vill fördjupa sig eller repetera.

### e-learning

* [Jan Marshal - Master Next.js 15 in Just 3 Hours (With Authentication)](https://www.youtube.com/watch?v=PqxHnMfyCUY)
* [ByteGrad - Next.js Tutorial 2026 - Start Your Next.js Journey Here](https://www.youtube.com/watch?v=KAQCHfu_3jw)
* [Jan Marshal - Next.js 16 Full Stack Course (8+ Hours) | Auth, Caching, Server Actions & Much More](https://www.youtube.com/watch?v=MZbwu3-uz3Y)

### Övningar

* Next.js Dashboard-app (Kapitel om Data Fetching) - [https://nextjs.org/learn/dashboard-app/fetching-data](https://nextjs.org/learn/dashboard-app/fetching-data)
