<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/MathJax.js?config=TeX-mml-chtml"></script>
# Klasszikus vesszőméretezés, részletek fordítása

Forrásdokumentum: [AMO Standard (PDF)](http://www.outlab.it/doc/amostd.pdf)

## AMO Hagyományosan Íjhossz Standard
Az AMO íjhossz-standard három hüvelykkel hosszabb, mint az AMO mester-ideg, amely a megfelelő ideg- vagy aljzásmagasságot állítja be az íjon. A mester-ideg csak az íjhossz megjelölését viseli. 

> **Példa:** Egy AMO 66" (íjhossz) jelölésű mester-ideg tényleges hossza felajzva 63"-nak felel meg.

Annak érdekében, hogy az ideg hossza pontos legyen, a mérést 1/4" (6.35 mm) átmérőjű acélcsapokon végzik, 100 fontos terhelés alatt, a csapok külső szélét mérve. (Tűréshatár: $\pm 1/16"$ / $\pm 1.6	ext{ mm}$).

## AMO Hagyományos Íjerő Jelölési Szabvány
A gyártók jelezhetik a tényleges húzóerőt 28" húzásra vonatkoztatva (26 1/4" DLPP /Draw Length from Pivot Point/), vagy az alábbi kerekített szabványt:

| Tényleges erő | Jelölés az íjon |
| :--- | :--- |
| 19-20-21 font | **20#** |
| 22-23 font | **20X#** |
| 24-25-26 font | **25#** |
| 27-28 font | **25X#** |

## Húzóerő korrekció 28" hossztól való eltérésnél
Ha a húzáshossz eltér a szabványos 28 hüvelyktől, az alábbi képlettel számolhatjuk ki a valós erőt:

$$\Delta F = rac{	ext{Íj ereje 28"-nál}}{20} 	imes 	ext{Eltérés hüvelykben}$$

### Példák a számításra:
1. **Íjerő 28"-on = 42#**, húzáshossz = 25.5" (eltérés: $28 - 25.5 = 2.5"$)
   $$rac{42}{20} = 2.1 \quad 
ightarrow \quad 2.1 	imes 2.5 = 5.25\#$$
   Valós erő: $42 - 5.25 =$ **36.75#**

2. **Íjerő 28"-on = 38#**, húzáshossz = 30" (eltérés: $30 - 28 = 2"$)
   $$rac{38}{20} = 1.9 \quad 
ightarrow \quad 1.9 	imes 2 = 3.8\#$$
   Valós erő: $38 + 3.8 =$ **41.8#**

---
*Megjegyzés: Gyakorlati szempontból a nyílvessző hossza és a húzáshossz azonosnak tekinthető.*
