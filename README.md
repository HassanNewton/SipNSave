# Dryckeshantering

Detta projekt är en enkel webbaserad applikation för att hantera drycker. Applikationen använder `json-server` som en mock-server för att simulera en REST API och lagra drycker i en lokal JSON-fil.

## Funktioner
- **Visa drycker**: Applikationen hämtar en lista av drycker från servern och visar dem på sidan.
- **Lägg till dryck**: Användaren kan lägga till en ny dryck genom att fylla i ett formulär.
- **Ta bort dryck**: Varje dryck har en "ta bort"-knapp som gör det möjligt att ta bort drycken från listan.
- **Visa beskrivning**: När användaren hovrar över en dryck, visas en beskrivning av drycken.

## Förutsättningar

För att kunna köra projektet lokalt behöver du ha följande installerat:

- [Node.js](https://nodejs.org/en/) (för att kunna köra JavaScript på servern)

### Installera beroenden

1. Klona projektet till din lokala dator:
   ```bash
   git clone <repository-url>
   cd <project-directory>

## Kör applikationen

För att kunna köra applikationen, behöver du starta en lokal mock-server med hjälp av `json-server`. Gör så här:

1. Se till att du är i projektets rotmapp.

2. Kör följande kommando för att starta servern:

   ```bash
   npx json-server --watch db.json --port 3001
   
Detta kommando startar en lokal server som lyssnar på port 3001 och simulerar en REST API med hjälp av filen db.json.

Öppna en ny terminal och starta applikationen genom att öppna index.html-filen i din webbläsare.
