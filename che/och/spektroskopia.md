# Spektroskopia
Metódy na *charakterizáciu zloženie zlúčenín* pomocou **interakcie EM žiarenia s hmotou**

**Spektrálne metódy**:
- $\textbf{hmotnostná spektroskopia}$ (MS)
- $\textbf{infračervená spektroskopia}$ (IČ)
- $\textbf{nukleárna magnetická rezonancia/spektroskopia}$ (NMR)
- *chiroptické metódy* - rozoznávanie chirality

Potreba nastáva v príkladových situáciach:
- objavil si neočakávaný produkt reakcie
- objavil si neznámu látku v rastlinnom extrakte
- detekoval si kontaminant v jedle
- kontroluješ čistotu lieku

![](metódy_spektroskopie.png)

## Interakcia EM vĺn s hmotou
![](emspektrum.png)

X-Ray -> *vnútorné elektróny*
UV -> *valenčné elektróny*
IČ -> *molekulové vibrácie*
Rádio -> *jadrové spiny*

## Delenie
### Infračervená spektroskopia
-> Interakcia hmoty s infračerveným žiarením (transmitancia)

Nevie určiť štruktúru, ale vie *potvrdiť funkčné skupiny*
Nevieme priradiť všetky peaky
--> Rozdelenie molekúl na fragmenty

os x: `vlnočet (wavenumber)` $f = 1/\lambda$
os y: `transmitancia` $T=l/l_0$

Sila peaku záleží na *dipólovom momente* väzby -> čím polárnejšia, tým **silnejší**``

Opisuje molekulu ako *harmonický oscilátor* - $\text{Hookov zákon}$ - $F=-kx$
![Vibračné módy molekúl|400](vibračné-módy.png)
**Väčšie molekuly** - osciluju pomalšie (low wavenumber), **menšie molekuly** - oscilujú rýchlejšie (high wavenumber)
**Jednoduché väzby** - oscilujú pomalšie (low wavenumber), **násobné väzby** - oscilujú rýchlejšie (high wavenumber)

#### Regióny IČ spektra
![](ic_spektrum.png)


**X-H región**:

| Bond | Reduced mass | IR freq   | Bond strength |
| ---- | ------------ | --------- | ------------- |
| C-H  | 12/13 = 0.92 | 2900-3200 | 440           |
| N-H  | 14/15 = 0.93 | 3300-3400 | 450           |
| O-H  | 15/16 = 0.94 | 3500-3600 | 500           |

Nie je to *vôbec perfektné*, napr. vodíkové väzby dokážu rozšíriť O-H peak
![](peakshapes_ic.png)

**Triple bond región**:
Väčšinou je prázdny, takže sa trojité väzby identifikujú ľahko
![](triple_bond_region.png)

**Double bond región**:
*Najdôležitejší región* -> C=C (ény a arény), C=O, -NO2
Väčšinou veľmi ostré peaky
![](double-bond_region_ic.png)

**Fingerprint región**:
**Zle čítateľná** (veľmi blízke pomery hmotností) a používa sa iba ako *otlačok prsta molekuly*



---

### Hmotnostná spektroskopia
Dokáže určiť *mólovú hmotnosť molekúl* - $m/z$ -> hmotnosť/náboj

![400](hmotnostna_spektroskopia.png)

**Princíp**:
- Jónizácia látky
- Vystrelenie látky do magnetického poľa
- Ohýbanie dráhy magnetickým poľom
- Vrazenie jónu do detektoru

![Electron impact spektrum|500](Pasted%20image%2020220719111138.png)

*Metódy zahŕňajú*: electron impact (hard), chemická jonizácia (soft), elektrosprej (soft)
`Hard metódy` vedú často ku **fragmentácii**, pričom `soft` sa im snažia zabrániť
![Pri metóde electron impact často látky fragmentujú](electron_impact_ms.png)

`Elektrospray` - jonizuje aeorosol substrátu spolu so *sodíkom* -> m/z = M+1, M+23, M-1
`Chemická jonizácia` - *bombardované NH4+* reáguje so substrátom -> m/z = M+1, M+18

![Elektrosprej je o dosť presnejší](elektrosprej_ms.png)

#### Izotópy
Prvky C, Cl a Br majú *abundanciu vyšších izotópov*, ktorá môže ovplyvniť výsledok MS
Pre Cl -> $\ce{^35Cl, ^37Cl}$ v pomere 3:1 -> M = 35.5
Pre Br -> $\ce{^79Br, ^81Br}$ v pomere 1:1 -> M = 80
Ale hmotnostná spektroskopia **nemeria priemernú hmotnosť**!

**Bróm a chlór**:
Uvidíme 2 peaky oddelené o 2u v rôznych pomeroch (1:1, 3:1)
![Pre bróm máme dva peaky oddelené o 2u|600](bróm_ms.png)

**Uhlík**:
Každý atóm uhlíka má 1.1% šancu byť $\ce{^13C}$
Takže pomer 
$$\frac{[M]^+}{[M+1]^+} = \frac{1}{0.011*n} \implies n = \frac{[M+1]^+}{0.011*[M]^+}$$
![600](ms_uhlík_radioaktívny.png)

--- 

### Nukleárna magnetická rezonancia
-> *Jadrá atómov* v silnom magnetickom poli pohlcujú (excitujú sa) a vyžarujú (vrátia sa do ground state) elektromagnetické žiarenie, pričom menia spin

**NMR aktívne izotopy**:
Všetky izotopy, ktoré majú *nepárny počet protónov a/alebo neutrónov*
Najbežnejšie sú $\ce{^1H, ^13C}$ ale aj $\ce{^2H, ^6Li ^11B}$

**Ako sa meria**:
Frekvencie: 60-1000 MHz
Najčastejšie sa meria v roztoku. $\ce{^1H, ^13C}$ sa merajú v *deuterovaných rozpúšťadlách* (CDCl2, D2O, DMSO, ...)

#### Informácie zo spektra
1. *Počet signálov* -> koľko rôznych typov vodíkov je v molekule
2. *Pozícia signálov* (`chemický posun`) -> aké typy vodíkov to sú
3. *Relatívna plocha pod signálmi* (integráica) -> koľko vodíkov nejakého typu je v molekule
4. *Štiepenie signálov* -> ovplyvňovanie susedných vodíkov

**Chemický posun**:
Chemický posun $\delta$ -> rezonančná frekvencia jadra relatívne voči štandardu
Je *rozdielny pre jadrá v rôznych podmienkach*, lebo majú rôznu distribúciu elektrónov, ktoré chránia jadro.
![](shielding_nmr.png)
Pre NMR s $\ce{^1H, ^13C, ^29Si}$ - $\textbf{tetrametylsilán}$
![200](tetrametylsilan.png)
Ďalšie: H3PO4 ($\ce{^13P}$), CFCl3 ($\ce{^19F}$), ...

---

### X-ray kryštalografia
Spočíva v *difrackcii xray vĺn* z **krýštálu látky**
Dokáže presne určiť *tvar molekuly*, ale iba pre kryštalické látky

Oproti NMR sa používa menej (dĺžka, kryštalizácia, cena,...)
**Nie je bezchybná**: nevie rozoznať H, niekedy ani O, či N