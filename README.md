# PECH-MIS — sajt za ALU i PVC stolariju

Static one-page site for PECH-MIS (Pečenjevce / Leskovac), built on the same system as the Moj Prozor V2 page. Serbian (latinica) only.

Sections: hero, highlights rail, product lineup, window configurator, savings calculator + subsidies (do 50%), profile cross-section and profile systems (Gealan S8000 / S9000 / Linear, Rehau, Teraplast), our work gallery, process, contact (phones, two Leskovac locations, quote form), footer.

No build step: open `index.html`, or import the folder into Vercel (`vercel.json` enables clean URLs).

## Notes

- Prices, Uw/Rw values, profile multipliers and the savings/payback model are placeholders. Confirm them with PECH-MIS before going live (`TYPES`, `PROFILES`, `COLORS`, `GLASS` and `renderSav` in the script).
- Profile depths/chambers (S8000 74 mm, S9000 82,5 mm, Rehau/Teraplast 70 mm) are typical values; confirm which exact Rehau and Teraplast series they sell.
- The configurator lead form and the contact form have no backend: they open the visitor's e-mail app with a prefilled message to pechmis77@gmail.com.
- All photos are PECH-MIS's own project photos from their Instagram (`img/`, 480×640). Higher-resolution originals from the client would make the hero sharper.
