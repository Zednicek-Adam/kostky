# Kostky - Počítadlo Bodů (Kingdom Come / Farkle)

Stylové počítadlo bodů pro oblíbenou kostkovou hru **Kostky (Farkle)** se středověkým motivem inspirovaným hrami jako Kingdom Come: Deliverance.

🌐 **Živá verze (GitHub Pages):** [https://zednicek-adam.github.io/kostky/](https://zednicek-adam.github.io/kostky/)

## 🎲 O aplikaci

Tato webová aplikace usnadňuje počítání bodů při hraní kostek s přáteli. Nabízí přehledné ovládací rozhraní pro zadávání kombinací kostek, automatický přepočet skóre, živý žebříček hráčů a kroniku jednotlivých tahů.

## ✨ Hlavní funkce

- **Správa hráčů**: Přidávání a odebírání hráčů, nastavení pořadí a přepínání aktuálního hráče.
- **Rychlé zadávání bodů**:
  - Samostatné bodované kostky (1 a 5)
  - Skupiny stejných kostek (3× až 6× pro čísla 1–6)
  - Speciální kombinace celého hodu (Malá, Velká a Plná postupka, Tři páry)
  - Ruční zadání libovolného počtu bodů
- **Funkce Zpět & Smazat**: Možnost opravení překlepu v probíhajícím tahu před zapsáním.
- **Nula (Bust)**: Zaznamenání neúspěšného tahu, ve kterém nepadly žádné body.
- **Žebříček & Kronika hospody**: Živý žebříček s ukazatelem postupu k cílovému skóre a historie nedávných tahů.
- **Nastavení cílového skóre**: Výběr přednastavených hodnot (1 500, 2 000, 4 000 b.) nebo zadání vlastní hodnoty.
- **Ukládání stavu**: Stav hry se automaticky ukládá do lokálního úložiště prohlížeče (`localStorage`).
- **Responzivní středověký design**: Přizpůsobeno pro mobilní zařízení i stolní počítače s vizuálními motivy pergamenu, dřeva a pečetí.

## 📜 Pravidla a bodování

| Kombinace | Body |
| --- | --- |
| **Jedna 1** | 100 b. |
| **Jedna 5** | 50 b. |
| **3× Jednička** | 1 000 b. *(4× = 2 000 b., 5× = 4 000 b., 6× = 8 000 b.)* |
| **3× Dvojka** | 200 b. *(4× = 400 b., 5× = 800 b., 6× = 1 600 b.)* |
| **3× Trojka** | 300 b. *(4× = 600 b., 5× = 1 200 b., 6× = 2 400 b.)* |
| **3× Čtyřka** | 400 b. *(4× = 800 b., 5× = 1 600 b., 6× = 3 200 b.)* |
| **3× Pětka** | 500 b. *(4× = 1 000 b., 5× = 2 000 b., 6× = 4 000 b.)* |
| **3× Šestka** | 600 b. *(4× = 1 200 b., 5× = 2 400 b., 6× = 4 800 b.)* |
| **Postupka 1–5** | 500 b. |
| **Postupka 2–6** | 750 b. |
| **Postupka 1–6** | 1 500 b. |
| **Tři páry (2+2+2)** | 750 b. |

## 🚀 Jak spustit aplikaci

Aplikaci můžete vyzkoušet přímo online na [GitHub Pages](https://zednicek-adam.github.io/kostky/) nebo ji spustit lokálně:

1. Stáhněte nebo klonujte tento repozitář.
2. Otevřete soubor `index.html` v libovolném moderním webovém prohlížeči (Chrome, Firefox, Safari, Edge).

Není vyžadován žádný lokální server ani instalace balíčků.

## 🛠 Použité technologie

- **HTML5 & JavaScript (ES6+)**
- **Tailwind CSS** (načítané z CDN)
- **Google Fonts** (Cinzel, MedievalSharp)
- **FontAwesome 6** (ikony)
