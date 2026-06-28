# Balkezes tradi és saját mérések

## Teszt íj paraméterei
* **Típus:** Végh Turul 28# (ez valószínűleg AMO 29.75")
* **Húzáshossz:** nettó 649 mm (25.5" / AMO 27.25")
* **Íjerő ezen a hosszon:** 25.75#

*Korábban mért értékek:* AMO 26.75" 25#, ez AMO 28"-on kb 27#, AMO 27.25"-on ~25.7#

### 4. Vessző mérése (723 mm / 28.5"):
* $47.45 - 26.15 = 21.3 \text{ mm}$ (0.84" 26"-on 1 kg súllyal)
* 0.76" 2#-tal --> **C** jelű kategória

> 🎯 A táblázat szerint a 26# erejű, 27" íjhoz **A** jelű vessző kell.

---

## Spine-Instruction2.pdf kritikája és hibái

Az alábbi szakirodalmi idézetet vettem alapul:
> *"A félreértések elkerülése végett ne feledjük, hogy az „500”-as spine valójában 0.500 hüvelykes lehajlást jelent a „modern” ASTM spine mérési módszer szerint. Egy 500-as nyíl, amelyet az ATA módszerrel mérnek, 0.413 hüvelykes lehajlást eredményezne az ATA ASTM módszerrel, ami egy 63 fontos spine. Azt se feledjük, hogy az ATA ASTM spine 26 / lehajlás hüvelykben. Az ATA ASTM lehajlást úgy lehet kiszámítani, hogy az ASTM ATA lehajlást megszorozzuk 0.825-tel."*

**Sok a hiba ebben a leírásban.** A valóságban az irány pont fordított:
$$\text{ASTM lehajlás} < \text{ATA lehajlás}$$
$$\text{ASTM} = \text{ATA} \times 0.825$$

### Kiszámolva egyből fontban:
* $26 / 0.76 \approx 34\#$
* 25.7#-hoz a lehajlás: $26 / 25.7 = 1.01"$

---

## Összehasonlítás: 1" ASTM lehajlás vs. ATA lehajlás

* 1" ASTM lehajlás (26" támaszköz, 2# súly) = $1 / 0.825 = 1.212"$ ATA lehajlás (28" támaszköz, 1.94# súly). Ez **26# ATA spine** értéknek felel meg.
* **Példa:** 1000-es Skylon vessző esetén: $1.000 \times 0.825 = 0.825"$. 
  Kiszámolva íjerőre: $26 / 0.825 = 31.5\#$. Vagyis a számítás szerint ez egy 31.5 fontos íjhoz jó vessző.

### Gyakorlati korrekciók és tapasztalatok
A fenti elméleti számításoknál két fontos tényezőt kell figyelembe venni:
1. Nincs megadva a hegy súlya, ami szabványosan 125 gn volt abban az időben (bár lehet, hogy 100-as).
2. A mai modern karok gyorsabbak, a hegyek ennek megfelelően könnyebbek.

**Saját tapasztalatom:** Ez a vessző 50-es heggyel kiválóan működik a 30#-os és a 32#-os íjhoz is. Valójában $\approx 1050$-es, így kerekítve pontosan a 30# jön ki.

### Vesszőhossz vs. Húzáshossz
A vesszőm hossza 25.96", ami kisebb, mint az AMO 27" húzáshosszam, de hosszabb a nettó húzáshossznál (ami 25.25"). A különbség 0.71" (18 mm) + a hegy. 

Az ASTM-ben a vesszőhosszt azonosnak veszik az AMO húzáshosszal. Az én esetemben az ennél valamivel rövidebb vessző valóban kicsit keménynek mutatkozik, de ez nyilván véletlen egybeesés – mindenesetre a módszer használhatónak látszik.

* 900-as vesszőnél 35# jön ki, ekkor valószínűleg a 70-es hegy és a +2-3" lesz a jó hossz.

> ❓ **Nyitott kérdés:** Vajon a hosszabb (vagy rövidebb) húzáshosszhoz tartozó nagyobb (vagy kisebb) font erő teljesen azonos-e a vessző ASTM font spine értékével?