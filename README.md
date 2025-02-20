Användarroller

Admin: Full kontroll över användare, projekt och uppgifter.

Användare: Hanterar sina egna projekt och uppgifter.

Autentisering

JWT (JSON Web Tokens) används för säker användarautentisering och åtkomstkontroll.

Databasval: MongoDB

MongoDB valdes för dess flexibilitet och skalbarhet:

Schemalös natur gör det enkelt att justera datamodellen.

Dokumentbaserad modell för enkel koppling mellan User, Task och Project.

JSON-struktur passar JavaScript/TypeScript-applikationer.

Tekniker och Verktyg

Node.js & Express.js: Servermiljö och API-ramverk.

TypeScript: Statisk typning för bättre kodstruktur.

Mongoose: ODM för att hantera MongoDB.

GraphQL: Flexibelt API för datahämtning.

JWT & Bcrypt: Autentisering och säker lagring av lösenord.

Crypto & Nodemailer: Säkra återställningstokens och e-posthantering.

Nodemon & Dotenv: Utvecklingsverktyg och miljövariabelhantering.

Applikationens funktionalitet

Struktur: Modeller för User, Task och Project.

Uppgiftshantering: Tasks kan ha status (Todo, In Progress, Completed) och tilldelas användare.

Projekthantering: Uppgifter organiseras inom projekt.

Autentisering & Rollhantering: JWT och användarroller styr åtkomst.

Lösenordsåterställning: Gamla lösenord verifieras innan uppdatering.

Mailtrap-integration: Simulerad e-posthantering under utveckling.

Felhantering & Validering: Användaruppgifter kontrolleras med tydliga felmeddelanden.

Trullo erbjuder en robust och skalbar lösning för projekt- och uppgiftshantering med modern teknologi och säkerhetsfunktioner.

## Installation

För att installera beroenden:

```bash

npm install
```

För att köra applikationen:

```bash
nodemon index.ts
```
