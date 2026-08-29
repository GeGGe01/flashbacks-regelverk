# Flashback regler – gillaprototyp

Statisk Vercel-vänlig prototyp som bygger på den uppladdade Flashback-regelsidan (sparad 2026-08-20).

## Funktion
- Responsiv mobil-/desktopvy med Flashback-inspirerad presentation.
- Gilla-knapp vid varje regel.
- Interaktionen är avsiktligt oförutsägbar: ibland flyttar sig knappen, ibland ger ett klick två gilla-markeringar och mycket sällsynt minskar antalet.
- Varje positiv gilla-händelse tilldelar samtidigt 1–3 gilla-markeringar till regel 0.06, "Moderatorsåtgärder".
- Separata vyer för Regler, Regel 0.06 och Aktivitet.
- Ingen beständig lagring; all data ligger endast i aktuell webbläsarsession.

## Vercel
Ingen build step krävs. Lägg filerna i repo och deploya som statisk site. `index.html` är entry point.

## Filer
- `index.html` – hela prototypen, inklusive CSS, regeldata och JavaScript.
