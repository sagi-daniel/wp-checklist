# WordPress Egyedi Block Fejlesztési Checklist ACF-fel

## 1. Kezdeti Elemzés
- [ ] Design áttekintése (Desktop/Mobile)
- [ ] Ellenőrizni, hogy a szekció megjelenik-e más oldalakon
- [ ] Hasonló, újrafelhasználható komponensek azonosítása

## 2. Komponens Követelmények Elemzése
- [ ] Szükséges UI komponensek meghatározása (szekció, kártyák, stb.)
- [ ] Egyedi Post Type szükségességének meghatározása
- [ ] Eldönteni: csak adatmegjelenítés vagy entitáskezelés is szükséges
- [ ] Szükséges ACF mezők listázása

## 3. Adatstruktúra Beállítása
- [ ] Custom Post Type létrehozása (ha szükséges)
- [ ] ACF mezőcsoportok beállítása
- [ ] Mezők közötti kapcsolatok definiálása
- [ ] Adatstruktúra tesztelése wp-adminban

## 4. Kezdeti Fejlesztés
- [ ] PHP sablon fájl létrehozása, SCSS fájl létrehozása
- [ ] Helykitöltő dobozok hozzáadása a tartalmi területekhez
- [ ] Reszponzív struktúra implementálása
- [ ] Alapvető reszponzív viselkedés tesztelése

## 5. Adatintegráció
- [ ] Tesztadatok feltöltése wp-adminba
- [ ] ACF mezők bekötése 
- [ ] Adatkimenet tesztelése var_dump-pal
- [ ] Minden szükséges adat elérhetőségének ellenőrzése

## 6. Frontend Fejlesztés
- [ ] HTML struktúra felépítése
- [ ] Alap stílusok implementálása
- [ ] Desktop specifikus stílusok
- [ ] Mobil specifikus stílusok
