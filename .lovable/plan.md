# Hotell Hjortronet med Hildur 4.0

## Mål
Bygg en varm, fjällinspirerad hotellapp där gäster kan prata med Hildur 4.0, se aktuell hotellstatus och använda hotellets tjänster utan backend.

## Upplevelse
- Skapa ett gemensamt sidhuvud med hotellidentitet, språkval på svenska/engelska/samiska, ljust/mörkt läge och en knapp för Kjell Katten.
- Använd fyra tydliga vyer: Välkommen, Gästtjänster, Trygghet & Säkerhet samt Drift & Infrastruktur.
- Ge alla val direkt återkoppling genom små bekräftelser, dialogrutor och statusändringar.
- Anpassa hela gränssnittet för både mobil och dator.

## Funktioner
- **Välkommen:** vänlig Hildur-hälsning, väderkort, Norrskenslarm och Kjells status.
- **Gästtjänster:** bokning av bastutid med kapacitetsgräns på åtta personer, frukost på rummet och felanmälan med formulär och bekräftelser.
- **Trygghet & Säkerhet:** visuell översikt över tre åtgärdade problem från Hildur 3000.
- **Drift & Infrastruktur:** interaktiv illustration av flytten från bastun till molndrift, inklusive Raspberry Pi-reserv vid strömavbrott.
- **Språk:** allt centralt innehåll växlar mellan svenska, engelska och samiska.
- **Kjell:** en lekfull överraskning som öppnas från sidhuvudet.

## Visuell riktning
- Mörk skogsgrön bas, varm guld/amber, ljusa naturtoner och tydlig modern typografi.
- Fjällhotellskänsla med diskreta topografiska former, träliknande detaljer och mjuka rörelser.
- Konsekventa designvariabler för färg, typografi, skuggor och båda färglägena.

## Teknisk inriktning
- Behåll befintlig TanStack-struktur och bygg upplevelsen på startsidan.
- Hantera alla val, formulär, språk, dialoger och notifieringar lokalt i webbläsaren.
- Använd återanvändbara React-delar och semantiska designvariabler i Tailwind CSS.
- Lägg till unik sidmetadata och kontrollera funktion, visning på mobil/dator samt felstatus efter implementation.
