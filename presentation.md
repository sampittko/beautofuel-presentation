footer: Určenie optimálnej jazdy automobilu
slidenumbers: true
autoscale: true

[.footer: # ![inline 60%](assets/fei-tuke.png) ` ` ` ` ` ` ` ` ` ` ![inline 28%](assets/kpi.png)]
[.slidenumbers: false]

# Určenie optimálnej jazdy automobilu

![right](assets/titulka.jpeg)

#### Bc. Samuel Pitoňák

#### <br><br><br><br><br><br><br><br><br>

#### Vedúci práce: <br>

#### Ing. Miroslav Biňas, PhD.

---

![](assets/bill-gates.png)

> We need to transofrm the way we do almost everything[^1]
> -- Bill Gates

[^1]: Breakthrough Energy. [Helping the world get to net-zero](https://breakthroughenergy.org).

---

## Motivácia

![](assets/les.jpg)

- ročne vyprodukujeme **51 miliárd ton** skleníkových plynov[^1]
- negatívne následky _zvýšených emisií_:
  - **globálne otepľovanie**
  - **znečistenie vzduchu**

---

## Motivácia

![](assets/kvalita-vzduchu.jpg)

- negatívne následky _nízkej kvality ovzdušia_:
  - **7 miliónov úmrtí ročne** po celom svete[^2]
  - **91% svetovej populácie** žije na miestach s nedostačujúcou kvalitou ovzdušia[^2]

[^2]: Svetová zdravotnícka organizácia. [Health topics - Air pollution](https://who.int/westernpacific/health-topics/air-pollution).

---

Obr. 1: Hlavné zdroje väčšiny dnešných globálnych emisií skleníkových plynov[^1]

![inline](assets/emisie.png)

---

## Motivácia

- cestná preprava založená z veľkej časti **na obnoviteľných zdrojoch energie do roku 2050** (výskumné agendy ERTRAC[^3]<sup>, </sup>[^4]<sup>, </sup>[^5])
- elektromobily dnes:
  - nedostačujúca infraštruktúra, nízky dojazd, nejednota poskytovateľov v cenách, osobitné mobilné aplikácie[^6]...

<!-- prettier-ignore-start -->

[^3]: ERTRAC. [Strategic Research Agenda 2004](https://ertrac.org/uploads/documentsearch/id29/ertrac_sra_dec2004_11.pdf).

[^4]: ERTRAC. [Strategic Research Agenda 2010](https://ertrac.org/uploads/documentsearch/id21/ERTRAC_SRA_2010.pdf).

[^5]: ERTRAC. [Strategic Research Agenda 2018](https://ertrac.org/uploads/documentsearch/id52/ERTRAC-Strategic-Research-Agenda-SRA-2018.pdf).

[^6]: Tim Burton. [I’m NOT Selling My Porsche Taycan Turbo S and HERE’S WHY!](https://ertrac.org/uploads/documentsearch/id52/ERTRAC-Strategic-Research-Agenda-SRA-2018.pdf).

<!-- prettier-ignore-end -->

---

## [fit] Čo vieme spraviť už dnes?

- **motivácia šoféra** jazdiť ekologicky
- _zlé rozhodnutia_ môžu mať za následok až **48% zhoršenie účinnosti paliva**[^7]
- úrovne rozhodnutí[^8]:
  - _strategické_ (výber vozidla, ...)
  - _taktické_ (výber trasy, zaťaženie vozidla, ...)
  - _operačné_ (štýl jazdy, ...)

<!-- prettier-ignore-start -->

[^7]: Angela Sanguinetti a spol. _The many reasons your mileage may vary: Toward a unifying typology of eco-driving behaviors_. 2017. DOI: [10.1016/j.trd.2017.02.005](https://doi.org/10.1016/j.trd.2017.02.005).

[^8]: Atiyeh Vaezipour a spol. _Reviewing In-vehicle Systems to Improve Fuel Efficiency and Road Safety_. 2015. DOI: [10.1016/j.promfg.2015.07.869](https://doi.org/10.1016/j.promfg.2015.07.869).

<!-- prettier-ignore-end -->

---

## Motivácia

- _zlepšenie správania šoféra za volantom_ má stále **významný potenciál** pre[^9]<sup>, </sup>[^10]:
  - **zlepšenie bezpečnosti jazdy**
  - **zlepšenie účinnosti paliva**
  - **zníženie emisií**

<!-- prettier-ignore-start -->

[^9]: Rana Massoud a spol. _A Fuzzy Logic Module to Estimate a Driver’s Fuel Consumption for Reality-Enhanced Serious Games_. 2018. DOI: [10.17083/ijsg.v5i4.266](https://doi.org/10.17083/ijsg.v5i4.266).

[^10]: Rana Massoud a spol. _Exploring Fuzzy Logic and Random Forest for Car Drivers’ Fuel Consumption Estimation in IoT-Enabled Serious Games_. 2019. DOI: [10.1109/ISADS45777.2019.9155706](https://doi.org/10.1109/ISADS45777.2019.9155706).

<!-- prettier-ignore-end -->

---

## Motivácia

- _stratégia gamifikácie_:
  - motivuje **pozitívne zapojenie**[^11]
- _stratégia odmien_:
  - pomocou **systému odmien** je možné dosiahnúť až **10% zlepšenie** účinnosti paliva[^13]

<!-- prettier-ignore-start -->

[^11]: Gautam Dange a spol. _Deployment of serious gaming approach for safe and sustainable mobility_. 2017. DOI: [10.1109/IVS.2017.7995879](https://doi.org/10.1109/IVS.2017.7995879).

[^12]: Wen-Tai Lai. _Deployment of serious gaming approach for safe and sustainable mobility_. 2015. DOI: [10.1016/j.trd.2014.10.003](https://doi.org/10.1016/j.trd.2014.10.003).

<!-- prettier-ignore-end -->

---

## Motivácia

- Madlen Günther a spol. vo svojom výskume **potvrdili užitočnosť motivačných stratégií** _gamifikácie_ v spojitosti s _finančnými odmenami_[^13]
- tiež navrhujú, aby sa ďalší výskum zaoberal **vzájomným vplyvom** týchto stratégií

[^13]: Madlen Günther a spol. _A field study of feedback, gamification and financial rewards in Germany._. 2020. DOI: [10.1016/j.erss.2019.101407](https://doi.org/10.1016/j.erss.2019.101407).

---

## Ciele práce

<!-- prettier-ignore-start -->

1. analýza:
  - __typov spätnej väzby__ k jazde automobilom
  - __metód zberu dát__ z jazdy automobilom
2. návrh
  - riadeného __experimentu__
  - __systému__ pre experiment
3. __implementácia systému__ pre experiment
4. __realizácia experimentu__ v záujme zozbierať dostatočné množstvo dát
5. __vyhodnotenie experimentu__ a __zodpovedanie výskumnej otázky__

<!-- prettier-ignore-end -->

---

## Ciele práce

_Výskumná otázka_

- **Redukuje** _motivačná stratégia_ **odmien** (vonkajšia motivácia) _mieru motivácie šoféra, ktorá je spôsobená motivačnou stratégiou_ **gamifikácie** (vnútorná motivácia)_?_

---

## Návrh riešenia

![right 50%](assets/kiwi.jpg)

_Typy spätnej väzby_

- **v reálnom čase** (obr. 2[^14])
  - možné reagovať v danom momente
  - zvýšená kognitívna záťaž
  - priamy vplyv na bezpečnosť jazdy

[^14]: [www.plxdevices.com/ProductDetails.asp?ProductCode=kiwi-app](https://www.plxdevices.com/Kiwi-OBD-OBDII-Interface-Gauges-Scan-tool-Diagnostics-s/195.htm)

---

[.slidenumber-style: #fff]

## Návrh riešenia

![right](assets/hud-widgets.jpg)

_Typy spätnej väzby_

- v reálnom čase
- **akumulovaná spätná väzba** (obr. 3[^15])
  - agregácia dát za nejaký časový interval
  - reprezentovaná často v podobe rozrastajúceho sa lista
  - jednoduchšie vnímanie počas jazdy

[^15]: [www.hudway.co/apps/widgets](https://hudway.co/apps/widgets)

---

[.slidenumber-style: #fff]

## Návrh riešenia

![right](assets/jerrycan.jpeg)

_Typy spätnej väzby_

- v reálnom čase
- akumulovaná spätná väzba
- **offline spätná väzba** (obr. 4[^16])
  - najskôr monitorovanie správania šoféra
  - analýza dát neskôr po dokončenej jazde
  - detailný pohľad na výkon

[^16]: [www.jerrycan.io](https://jerrycan.io/)

---

## Návrh riešenia

![right](assets/google-maps.jpeg)

_Typy spätnej väzby_

- v reálnom čase
- akumulovaná spätná väzba
- offline spätná väzba
- **rada pred jazdou** (obr. 5[^17])
  - alternatívne trasy
  - vzdialenosť, čas, spotreba

[^17]: [www.maps.google.com](https://maps.google.com)

---

## Návrh riešenia

![right 175%](assets/obd.jpeg)

_Zber dát z jazdy automobilom_

- použitie protokolu pre _palubnú diagnostiku_ (OBD[^18]):
  - v EÚ štandard **v každom automobile od roku 2004**[^18]
- dáta priamo z kontrolnej riadiacej jednotky (ECU) automobilu
- zariadenie ELM327 (obr. 6) umožňuje komunikáciu cez Bluetooth s diagnostickým zariadením
- spotrebu paliva treba **dodatočne vypočítať** z poskytnutých dát

[^18]: [www.wikipedia.org/wiki/On-board_diagnostics](https://en.wikipedia.org/wiki/On-board_diagnostics).

---

![right 80%](assets/envirocar.png)

## Návrh riešenia

_Platforma enviroCar_[^19]

- zber, zdieľanie a analýza dát
- webová a mobilná aplikácia
- OBD a GPS modely pre výpočet spotreby paliva[^20]
- open-source
- API
- knižnice pre prácu s ich dátami (Python)
  - formát GeoJSON

<!-- prettier-ignore-start -->

[^19]: [www.envirocar.org](https://envirocar.org).

[^20]: [www.blog.52north.org/2020/07/02/fuel-consumption-models-in-envirocar/](https://blog.52north.org/2020/07/02/fuel-consumption-models-in-envirocar/).

<!-- prettier-ignore-end -->

---

## Návrh riešenia

[.column]

_Typ spätnej väzby_

- **offline spätná väzba**
- prístup bez negatívnych implikácií na bezpečnosť jazdy

[.column]

_Metóda zberu dát_

- použitie platformy _enviroCar_
- pri overení metódy som zaznamenal **technické komplikácie** v komunikácii medzi zariadeniami
- **GPS model ako kompromis**
- získané dáta stratia na presnosti

---

## Návrh riešenia

_Experimentálny dizajn_

[.column]

- **2 experimentálne skupiny**
- **between-subject dizajn**
- **3 fázy** (trvanie spolu 6 týždňov):
  1. zozbieranie baseline dát
  2. poskytnutie jednej motivačnej stratégie
  3. poskytnutie oboch motivačných stratégií

[.column]

- **závislá premenná**:
  - spotreba paliva
- **nezávislé premenné**:
  - stratégia gamifikácie
  - stratégia odmien

---

## Návrh riešenia

_Základný prípad použitia_

1. **Zber dát** z jazdy automobilom

---

## Návrh riešenia

_Základný prípad použitia_

1. **Zber dát** z jazdy automobilom
2. **Nahratie dát** na server _enviroCar_

---

## Návrh riešenia

_Základný prípad použitia_

1. **Zber dát** z jazdy automobilom
2. **Nahratie dát** na server _enviroCar_
3. Použitie systému pre experiment pre **synchronizáciu zozbieraných dát**

---

## Návrh riešenia

_Základný prípad použitia_

1. **Zber dát** z jazdy automobilom
2. **Nahratie dát** na server _enviroCar_
3. Použitie systému pre experiment pre **synchronizáciu zozbieraných dát**
4. **Zobrazenie motivačnej spätnej väzby** v používateľskom rozhraní

---

## Návrh riešenia

![right 100%](assets/architektura.jpg)

_Architektúra systému_ (obr. 7)

- separácia zámerov
- kontajnerizácia (_Docker_)
- **4 hlavné komponenty**:
  - webový klient (_NextJS_)
  - CMS (_Strapi_)
  - komponent pre synchronizáciu a spracovanie dát (_FastAPI_)
  - monitorovací nástroj (_Grafana_)
- 2 databázy (_Mongo_ a _Influx_)
- JWT pre autentifikáciu a autorizáciu
- komunikácia medzi komponentmi cez GraphQL a REST APIs

---

[.footer: __Prvá fáza__]

![78%](assets/ui1.png)

---

[.footer: __Druhá fáza__]
[.slidenumbers: false]

![55%](assets/ui21.png) ![55%](assets/ui22.png)

---

[.hide-footer]

![78%](assets/top10.png)

---

[.footer: __Tretia fáza__]

![58%](assets/ui3.png)

---

[.hide-footer]
[.slidenumbers: false]

![51%](assets/grafana.png)

---

## Vyhodnotenie riešenia

_Dataset_

|                | počet   | počet na účastníka  |
| -------------- | ------- | ------------------- |
| vzdialenosť    | 5211 km | 473 km (_11 / deň_) |
| merania        | 393     | 35 (_1 / deň_)      |
| synchronizácie | 246     | 22 (_1 / dva dni_)  |

---

## Vyhodnotenie riešenia

_Identifikované hrozby validity výsledkov_

<!-- prettier-ignore-start -->

1. **malá vzorka**:
  - obmedzenia v dôsledku pandémie
  - nízka šanca preukázania sledovanej zmeny napriek jej potenciálnej existencii

<!-- prettier-ignore-end -->

---

## Vyhodnotenie riešenia

_Identifikované hrozby validity výsledkov_

<!-- prettier-ignore-start -->

2. **malá vzorka**:
  - obmedzenia v dôsledku pandémie
  - nízka šanca preukázania sledovanej zmeny napriek jej potenciálnej existencii
3. **viacero mätúcich faktorov**:
  - neúspech pri implementácii filtrovacieho algoritmu
  - _kompromis_: zavedenie pravidiel

<!-- prettier-ignore-end -->

---

## Vyhodnotenie riešenia

_Identifikované hrozby validity výsledkov_

<!-- prettier-ignore-start -->

1. **malá vzorka**:
  - obmedzenia v dôsledku pandémie
  - nízka šanca preukázania sledovanej zmeny napriek jej potenciálnej existencii
2. **viacero mätúcich faktorov**:
  - neúspech pri implementácii filtrovacieho algoritmu
  - _kompromis_: zavedenie pravidiel
3. **nepresná metóda zberu dát**:
  - technické komplikácie bránili použitiu _enviroCar_ OBD modelu
  - _kompromis_: _enviroCar_ GPS model

<!-- prettier-ignore-end -->

---

## Vyhodnotenie riešenia

| fáza | skupina     | priemerná spotreba | oproti predošlej fáze |
| ---- | ----------- | ------------------ | --------------------- |
| č. 1 | odmeny      | 6,01               | -                     |
| č. 2 | odmeny      | 6,25               | +4,0%                 |
| č. 3 | odmeny      | 6,38               | +2,1%                 |
| č. 1 | gamifikácia | 6,06               | -                     |
| č. 2 | gamifikácia | 6,17               | +1,8%                 |
| č. 3 | gamifikácia | 6,21               | +0,7%                 |

---

## Vyhodnotenie riešenia

- **študentov t-test** pre overenie H<sub>0</sub>:
  - normálna distribúcia dát => _parametrický_
  - t = 0,6126, p = 0,5404
  - **nebol zistený štatisticky významný vplyv nezávislej premennej na závislú premennú**

<!---

![45%](assets/korelacie.png)







--->

---

[.slidenumbers: false]

## Vyhodnotenie riešenia

![right](assets/ui3.png)

_Použiteľnosť systému pre experiment_

- priemerné SUS z mnohých štúdií je rovné hodnote 68[^21]
- hodnotenie účastníkov experimentu:
  - SUS **79,25**
  - dobrá implementácia z pohľadu používateľa
  - vysoká spoľahlivosť systému
- potvrdenie, že responzívny dizajn dnes je nevyhnutnosť:
  - 8 z 10 používateľov pristupovalo na systém pre experiment zo smartfónu

[^21]: [www.usability.gov/how-to-and-tools/methods/system-usability-scale.html](https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html)

---

## Vyhodnotenie riešenia

_Vedomosti ohľadom ekologickej jazdy_

| kvíz po fáze | priemer (b) | medián (b) | rozsah (b) |
| ------------ | ----------- | ---------- | ---------- |
| č. 1         | 1,27        | 1          | 0 - 2      |
| č. 2         | 1,43        | 1          | 1 - 2      |
| č. 3         | 1,89        | 2          | 1 - 3      |

---

## [fit]<br>+49%

---

![](assets/zelena.png) ![](assets/zlta.png)

## Zhrnutie

[.column]

_Prínosy_

- **rámec pre realizáciu experimentu**
- **systém pre experiment**
- integrácia s platformou _enviroCar_
- vzorec pre výpočet ekologického výkonu
- **zlepšenie vedomostí ohľadom ekologickej jazdy**

[.column]

_Návrhy_

- _opätovná realizácia experimentu_ po odstránení nedostatkov
  - viac účastníkov
  - eliminácia mätúcich faktorov
  - použitie OBD modelu
- _realizácia v simulácii_

---

[.slidenumbers: false]

## Otázky zo strany oponenta

![](assets/otazniky.jpg)

_Ako by bolo možné do budúcnosti lepšie rozlíšiť skupiny účastníkov a tak viac zamerať spôsob motivácie?_

[.column]

_gamifikácia_

- vytvorenie viacerých príležitostí súťaženia
- nové kategórie s rebríčkami podľa:
  - štýlu jazdy
  - prevýšenia
  - množstvo CO2 emisií
  - a iných...

[.column]

_odmeny_

- nahradiť odmenenie krovkami finančnými odmenami
- implementovať pôvodne zamýšľaný obchod:
  - ekologické skóre ostáva ako kredit
  - možnosť utratiť kredity na to, na čo šofér chce z aktuálnej ponuky obchodu

---

[.slidenumbers: false]

## Otázky zo strany oponenta

![](assets/otazniky.jpg)

_Aké nové atribúty by bolo potrebné doplniť do datového modelu?_

[.column]

_gamifikácia_

- použitie existujúcich atribútov z dátového modelu _enviroCar_ pre navrhované rozšírenia:
  - prevýšenie
  - CO2 emisie
  - otáčky motora

[.column]

_odmeny_

- navrhované rozšírenia si nevyžadujú doplnenie atribútov

---

[.slidenumbers: false]

![inline 100%](assets/beautofuel.png)
