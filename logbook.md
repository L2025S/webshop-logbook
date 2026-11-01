

# Sprint 1 - vecka 39
### Vad jag arbetade med
- `1. Skapa frontendrepo`
- `2. Lägg till CI för frontend`
- `3. Skydda huvudbranchen `
- `4. Alla kan köra frontend lokalt`

### Eventuella problem och hur jag löste dem
- Inga problem.
### Samarbete  och agilt arbete
- Vi valde Scrum Master, bestämde alla mötestider coh sätta oss in i Planning Poker. 
- Vi planerade inte att göra mycket i första veckan.




# Sprint 2 - vecka 40
### Vad jag arbetade med
- `9. Tillåt frontend mot product-service api `
- `10. Visa produkter från backend` 
- `15. Grundläggande kundvagn`
- Uppdaterat productService.ts för att hämta accessToken från localStorage

### Eventuella problem och hur jag löste dem
- Ingen problem.

### Samarbete  och agilt arbete
- Vi har satt upp en rutin för att sätta poäng på stories med online planning poker.
- Vi har en fast tid varje dag för Daily Scrum. 
- Retrospektiv: 
    + Vi bestämde oss för att planera mer, och vi kan lägga till fler uppgifter senare om vi hinner.
    + Om någon har problem eller sitter fast med någonting, måste ta det upp på Daily Scrum.




#  Sprint 3- Vecka 41
### Vad jag arbetade med
- `16. Utöka kundvagnen med quality och prisberäkning`
- `21. Kundvagn del-3`
- `23. Produkter ska få två nya attribute: category och imageUrl i backend`
- `25. Frontend ska kunna visa imageUrl för produkter`
 
### Eventuella problem och hur jag löste dem
- Problem: Knappen "Place Order" fungerar inte. Det står " You are not logged in." 
- Lösning: 
    + Order behöver använda Cookies för att "Place Order" funkar. 
    + Jag har informerat den personen som är ansvarig för Order Service att ändra metoden att hämta users, eftersom vi använder Cookies nu.

### Samarbete  och agilt arbete
- Mål: Vi jobbar på både frontend och backend, skapar en adminfunktionalitet och förbättra UX (User Experience) för kunden.
- Vad vi har uppnått:
    + Vi har förbättrat UX  med kundvagn, product search field, category filter, 
    + E-mail funkar lokalt och 404-template och an admin-sida.
- Retrospektiv: 
    + Vi tyckte att vi hade gjort väldigt bra jobb.






# Sprint 4 - vecka 42
### Vad jag arbetade med 
- Färdigt: `24. Uppdatera så att formuläret som skapar nya produkter inkluderar category och imageUrl`
- Inte färdigt: Lägg till stock i ProductForm

### Eventuella problem och hur jag löste dem
- Lite om ev problem och lösningar på dem

### Samarbete  och agilt arbete
- Mål: Vi ska göra klart resten av arbete och börja med gateway. 
- Vi var färdig med:
    + Mail-funktion funkar på frontend. 
    + Hela flödet funkar: login- product- order- skickar mejl
    + Logintest
    + Deleteknappen på adminPage.
    + Order använder Cookies.
    + Skapade en repo till Gateway.
- Retrospektiv:
    + Vi uppdaterar allting i tid på Trello men också behöver uppdatera uppgifterna på Google Sheets så att lärare kan se allting.
    + Mer aktiva att godkänna Pull Request så att alla kan få uppdaterings i tid. 


# Sprint 5 - vecka 43
### Vad jag arbetade med
- Färdigt: 
    + `32. Gateway-applikcation i backend`
    + `33. Driftsättning av gateway`
    + `Fix: add stock to ProductForm`

- Inte färdigt: 
    + 

### Eventuella problem och hur jag löste dem
- Problem: AdminPage syns inte när man loggar in som ADMIN.
- Lösning: Tillfälligt: 1. VITE_ENABLE_MSW=false; Permanent: Ändra "admin" till "ADMIN"

### Samarbete  och agilt arbete
- Mål: Gör klart gateway och testning. 
- Vi var färdig med:
  + `32. Gateway-applikation i backend.`
  + `33. Driftsättning av gateway`
  + `34. Cookie för jwttoken i gateway`
  + `35. Cookie för jwttoken i frontend`
  + `36. Återställ inloggad användare om användare laddar om sidan.`
  + `38. Undersök integrationstestning.`
  + `39.Konfigurera MSW`
  + `40. Testa produkthämtning`
  + `AdminPage: kappen-Edit Stock`
-Inte färdigt med:
  + `41. Test återställning av användare`
- Retrospektiv:
  + Bra kommunikation med Pull Request.




# Sprint 6 - vecka 44
### Vad jag arbetade med
- Färdigt:
  + `- README- gateway `
  + `- README- product`
  + `- Javadoc - product `
  + `- Undersök E2E-test `
  

- Inte färdigt:
  +

### Eventuella problem och hur jag löste dem
- 

### Samarbete  och agilt arbete
- Mål: .
- Vi var färdig med:
  + `- 41. Testa återställning av användare `
  + `- 42. Undersök en-to-end-testning`
  + `- 44. Informera om nödvändiga cookies`
  + `- 46. Documentera backend med Javadoc`

-Inte färdigt med:
  + `- 43. Skapa README-filer `
  + `- 45. Finputsning av frontend design `

            