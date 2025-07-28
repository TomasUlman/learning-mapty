# learning-mapty

> ⚠️ This is a study project based on a Udemy course. It is not intended for production use.  
> The README continues in Czech, as this project is part of my personal learning archive.

---

## 🗺️ Mapty – sportovní aktivity na mapě

Tato aplikace slouží ke sledování sportovních aktivit (běhu a jízdy na kole) přímo na mapě pomocí knihovny Leaflet.js. Uživatel si může zaznamenat aktivitu kliknutím na mapu, vyplnit údaje a uložit je – data se ukládají do Local Storage a zůstávají dostupná i po obnovení stránky.

---

## 💡 Funkce aplikace

- **Zobrazení aktuální polohy uživatele** pomocí geolokace
- **Záznam sportovních aktivit** kliknutím na mapu
  - *Běh*: zadání vzdálenosti, trvání, kadence
  - *Cyklistika*: zadání vzdálenosti, trvání, převýšení
- **Vykreslení aktivity na mapě** jako marker s popiskem
- **Seznam aktivit v postranním panelu**
- **Mazání aktivit** kliknutím na křížek
- **Uložení dat do Local Storage**

---

## 🛠 Použité technologie

- **HTML / CSS** – struktura a stylování rozhraní
- **JavaScript (ES6+)**
  - OOP (třídy `Workout`, `Running`, `Cycling`, `App`)
  - Práce s DOM a událostmi
  - Geolokace API
  - Local Storage
- **Leaflet.js** – zobrazení mapy a práce s markery

---

## 🧠 Co jsem si na projektu vyzkoušel

- Organizaci kódu pomocí objektově orientovaného přístupu
- Práci s mapou a událostmi kliknutí (Leaflet)
- Validaci vstupních dat a uživatelské interakce
- Implementaci markerů s popupy
- Ukládání a obnovu dat přes Local Storage
- Dynamické skrývání / zobrazování vstupních polí podle typu aktivity

---

## 🧼 Poznámka

Tento projekt je studijní ukázkou práce s mapovými knihovnami a JavaScriptem bez použití backendu. Data jsou ukládána lokálně a nejsou trvale synchronizována se serverem.
