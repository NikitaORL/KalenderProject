# ProjectLibre – Kasutusjuhend

## Sisukord

1. [Projektist](#projektist)
2. [Funktsionaalsus](#funktsionaalsus)
3. [Disain ja paigutus](#disain-ja-paigutus)
4. [Ekraanipildid](#ekraanipildid)
5. [Kasutatud tehnoloogiad](#kasutatud-tehnoloogiad)
6. [Navigatsioon](#navigatsioon)
7. [Autor](#autor)

---

## Projektist

Käesolev projekt on veebisait, mis sisaldab samm-sammulisi juhiseid **ProjectLibre** tarkvara kasutamiseks.  
ProjectLibre on tasuta avatud lähtekoodiga projektijuhtimise tarkvara, mis on alternatiiv Microsoft Projectile.

Projekti eesmärk on pakkuda kasutajale visuaalseid materjale kahe põhiteema kohta:
- kalendrite loomine ja seadistamine
- diagrammide (Gantt, Network Diagram) kasutamine ja ressursside jälgimine

Iga samm on varustatud ekraanipildiga ja selge struktuuriga, mis muudab õppimise lihtsaks ja arusaadavaks.

---

## Funktsionaalsus

Projekt koosneb kahest iseseisvast veebilehest:

### 1. Kalender (`index.html`)
- Uue töökalendri loomine ProjectLibres
- Tööpäevade ja töötundide seadistamine
- Tööaja kestuse (Duration) muutmine
- Kalendri rakendamine ülesannetele
- Kalendri mõju ajakavale

### 2. Diagrammid (`diagram.html`)
- Gantti diagrammi loomine ülesannete visualiseerimiseks
- Network Diagram (võrgustiku diagrammi) loomine sõltuvuste jälgimiseks
- Ressursside tabelite (Resource Sheet, Resource Usage) kasutamine
- Diagrammitüüpide võrdlus ja nende otstarve

---

## Disain ja paigutus

Visuaalne kujundus on loodud rõhuasetusega puhtusele ja loetavusele:

| Element | Kirjeldus |
|---------|----------|
| **Päis** | Gradienttaust küllastunud sinisest tumesiniseni, suur pealkiri ja alapealkiri |
| **Navigatsioonimenüü** | Kaks nuppu sujuva värvi muutumisega hiire kohal viibimisel |
| **Sisuala** | Valge taust, ümarad nurgad, vari visuaalseks eraldamiseks taustast |
| **Pildid** | Kõigil ekraanipiltidel on vari, ümarad nurgad ja peenike raam |
| **Jalus** | Tume taust, teave autori kohta, kinnitatud lehe alumisse ossa |
| **Kohanduvus** | Korrektne kuvamine erineva suurusega ekraanidel (lauaarvutid, tahvelarvutid, mobiilseadmed) |

---

## Ekraanipildid

Allpool on toodud näited lehtede kujundusest:

| Leht | Pilt |
|------|------|
| Kalender | <img width="1859" height="946" alt="{A7798BAF-5102-40BB-A234-33C7BFE24E90}" src="https://github.com/user-attachments/assets/b985b7c9-f3da-420e-a2e4-f9f82ab5ed4c" /> |
| Diagrammid | <img width="1773" height="943" alt="{3A016461-5C92-405E-9B6F-0FDF5377511F}" src="https://github.com/user-attachments/assets/e9b4d876-30a4-4b7b-82cb-1f906c2b4759" /> |

*Projektis kasutatakse 10 ekraanipilti ProjectLibre liidesest, millest igaüks vastab konkreetsele juhiste sammule.*

Ekraanipildid asuvad kaustas `Image2/`:

| Failinimi | Kirjeldus |
|-----------|-----------|
| `createK.png` | Uue kalendri loomine |
| `editK.png` | Tööaja muutmine |
| `Ktime.png` | Tööaja kestuse seadistamine |
| `vali.png` | Kalendri valimine |
| `advanced.png` | Kalendri seadistamine Advanced menüüs |
| `checkK.png` | Tulemuse kontroll |
| `table.png` | Ülesannete lisamine tabelisse |
| `gant.png` | Gantti diagramm |
| `network.png` | Network Diagram |
| `resourse.png` | Resource Usage vaade |

---

## Kasutatud tehnoloogiad

- **HTML5** – veebilehtede struktuuri loomine
- **CSS3** – kujundus, gradientide varjundid, üleminekuefektid
- **Flexbox** – paindlike paigutuste loomine
- **Media Queries** – kohanduva disaini rakendamine
- **PNG** – kõigi graafiliste materjalide vorming

---

## Navigatsioon

Lehtede vahel liikumine toimub navigatsioonimenüü abil, mis asub iga lehe ülaosas.  
Menüü nupud:

- **Kalender** – üleminek kalendri loomise juhendile
- **Diagrammid** – üleminek diagrammide loomise juhendile

Aktiivne leht on menüüs esile tõstetud tumedama taustavärviga.

---

## Autor

**Nikita Orlenko**  
2026. aasta
