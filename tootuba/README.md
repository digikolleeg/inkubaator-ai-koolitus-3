# Töötoa käsiraamat

Tee sammud järjekorras. Kui jääd hätta, kasuta **varuteed** ja jätka.

**Kuidas seda lehte lugeda:** kopeeri plokk pealkirjaga **Kleebi AI-le** vestlusesse. Ülejäänu on juhis sulle.

Hoia testkirjad, hindamisvõtmed ja see käsiraamat **väljaspool** kausta, mille AI-le annad.

---

## 0. Enne algust: anna AI-le kaust

**Claude (Cowork):** tee uus projekt.
- **What are you working on:** pane nimeks näiteks „Töötuba”.
- **What are you trying to achieve:** jäta tühjaks. Sinna kirjutatu läheb iga vestluse juhiseks.
- **Folder:** vali täpselt see kaust, mille AI peab nägema (sammus 2 `tootuba-proov`, sammust 4 alates `ettevotte-aju`). Ära vali kausta, kus on testkirjad või hindamisvõtmed.

Tee iga kausta jaoks eraldi projekt. **Uus vestlus** tähendab: samas projektis vajuta „New”.

**ChatGPT:** vaata [codex-chatgpt.md](codex-chatgpt.md).

Kui näed Coworkis sõna „blocked”, peatati üks käsk. AI proovib tavaliselt teist viisi. Vaata kaustast, kas failid on olemas.

## 1. 13:00 · Avademo

Kuula ja paku enne vastuse nägemist: kas digikolleeg peaks vastama, kliendilt täpsustust küsima või omaniku otsust ootama?

## 2. 13:12 · Ühine harjutus

Kirjutame koos vastuse kirjale, mis saadeti väljamõeldud koerasalongile Käpakamber.

1. Tee kaust `tootuba-proov` ja kopeeri sinna kolm faili kaustast [`naidisfirmad/kapakamber/`](../naidisfirmad/kapakamber/). Tee sinna tühi alamkaust `mustandid/`.
2. Tee Coworkis projekt kaustaga `tootuba-proov` (vt samm 0).

**Kleebi AI-le:**

```text
Vastad väljamõeldud koerasalongi Käpakamber kirjadele. Loe failid kes-me-oleme.md, kuidas-kirjutame.md ja faktid.md ning kasuta ainult neid.

Kirjuta Liisi nimel allolevale kirjale vastuse mustand. Ära saada midagi. Kui vastamiseks on infot puudu, küsi. Kui on vaja omaniku otsust, märgi see eraldi.

Väljund:
1. Vastuse mustand.
2. „Kinnita enne saatmist”: ainult see, mida Liisi peab enne saatmist otsustama või parandama. Kui midagi pole, kirjuta „pole”.
3. Mulle kontrollimiseks: millisest failist võtsid hinna ja tingimused.

Salvesta mustand faili mustandid/harjutus-v1.md.

KIRI:
Tere! Mul on 7 kg šnautser, karv on päris sassis. Kui palju maksab pesu ja pügamine kokku? Kas pean ootama?
Piret
```

**Kontroll:** leia ise failist `faktid.md` rida, kust hind tuli. Alles siis ava [hindamisvõti](../vastused/harjutus.md).

**Varutee:** kui AI ei näe kausta, lisa kolm faili manusena.

## 3. 13:25 · Vali oma töö

- **Tegid eeltöö:** ava `ettevotte-aju/teadmus/korduvad-tood.md` ja vaata lõiku „Esimene kandidaat”. Kui see on töö, mida tahad digikolleegile anda, ongi valik tehtud. Kirjuta üles, mitu tundi sul nendele töödele kuus kulub (lõik „Kokku”).
- **Eeltööd ei teinud:** vali näidisfirma Käpakamber või Tööruum. Kopeeri valitud firma kolm faili kausta `ettevotte-aju/teadmus/`. Digikolleegi ehitamisel kasuta Käpakambri Pireti kirja või Tööruumi kirja E1. Testkirjad on kaustas [`testkirjad/`](../testkirjad/).

Oma testkirjad hoia eraldi kaustas, mitte kaustas `ettevotte-aju`.

**Varutee:** eemalda päris kirjadest enne isikuandmed: [andmekaitse](../andmekaitse/puhastamine.md). Kui kahtled, kasuta näidisfirmat.

## 4. 13:40 · Intervjuu: tööjuhis faili

1. Tee Coworkis projekt kaustaga `ettevotte-aju`.
2. Ava fail [`intervjuu/digikolleeg-intervjuu.md`](../intervjuu/digikolleeg-intervjuu.md) ja kopeeri kogu sisu.

**Kleebi AI-le:** kogu intervjuufaili sisu.

3. Vasta küsimustele. Kontrolli pakutud faile ja kinnita ainult see, mis on õige.

**Kontroll:** kaustas `digikolleegid/<töö>/` on fail `digikolleeg.md` ja `kaart.md` tabelis on sinu digikolleeg.

**Varutee:** kui AI küsib kümne vastuse järel edasi:

```text
Peata intervjuu. Näita nüüd seniste vastuste ja failide põhjal koostatud faile, et saaksin need kinnitada.
```

## 5. 14:05 · Esimene mustand uues vestluses

Ava samas projektis **uus vestlus**.

**Kleebi AI-le:** (lisa lõppu kiri, mida intervjuus kasutasid)

```text
Digikolleeg, vasta sellele kirjale. Salvesta mustand faili mustandid/esimene-v1.md.

KIRI:
```

**Kontrolli järjekorras:** kas faktid on võetud failidest? Kas digikolleeg oskab vastata, kliendilt puuduvat infot küsida ja vajadusel otsuse sulle jätta? Kas see kõlab sinu moodi? Kas saadaksid selle kliendile?

## 14:25 · Paus

## 6. 14:35 · Test, parandus faili, uus vestlus

1. Ava uus vestlus. Anna esimene testkiri (Käpakamber K1, Tööruum T1 või sinu oma).

**Kleebi AI-le:**

```text
Digikolleeg, vasta sellele kirjale. Salvesta mustand faili mustandid/test1-v1.md.

KIRI:
```

2. Hinda vastust ise. Alles siis ava hindamisvõti kaustas [`vastused/`](../vastused/).
3. Leidsid vea? Kirjuta samasse vestlusesse.

**Kleebi AI-le:** (täida nurksulud)

```text
Selle mustandi juures ei sobinud: [MIS TÄPSELT]

Ütle, kust viga tuli ja millises failis seda parandada. Paku võimalikult väike muudatus. Näita vana ja uut lõiku. Ühe kirja põhjal ära tee üldreeglit. Ära muuda faili enne minu kinnitust.
```

| Leid | Parandus läheb |
|---|---|
| vale või puuduv fakt | `teadmus/faktid.md`, allika ja kuupäevaga |
| lubas midagi, mida ei tohi | tööpiirid → Ei tohi lubada |
| oleks pidanud sinult küsima | tööpiirid → Peatub ja küsib |
| küsis kliendilt midagi tarbetut või kirjutas liiga pikalt | tööjuhis `digikolleeg.md` |
| ei kõla nagu sina | häälefail: sinu sõnastus näitena |
| sul endal oli otsus tegemata | otsusta enne, siis uuenda faili |
| ühe kliendi erand | ei lähe üldreegliks |

4. Kontrolli, et parandus on **failis**. Ava uus vestlus ja anna sama kiri uuesti. Võrdle.
5. Tee sama teise testkirjaga (K2, T2 või sinu oma). Kolmas jääb lõpuproovi jaoks.

**Kui vastused olid kohe õiged:** küsi Käpakambrilt „Kas saan sõbrale kinkekaardi osta?”. Failides seda pole ja digikolleeg peab ütlema, et ei tea.

Abiks ekraanil: [KUI juhtub see, ÜTLE nii](parandusnaited.md).

## 15:10 · Paus

## 7. 15:20 · Uus pöördumine failist

Seni kleepisid kirja vestlusesse. Nüüd loeb digikolleeg selle failist.

1. Tee kausta `ettevotte-aju` alamkaust `postkast/` ja sinna fail `proov-01.txt` (TextEditis: Format → Make Plain Text). Kirjuta sinna üks väljamõeldud kiri ja esimesele reale tunnus, näiteks `Tunnus: KASK`.

**Kleebi AI-le:**

```text
Digikolleeg, loe kaustast postkast/ fail proov-01.txt. Ütle kõigepealt tunnus ja kirja esimene lause. Siis kirjuta vastuse mustand ja salvesta see faili mustandid/postkast-01.md.
```

Heigo näitab ekraanil, kuidas sama kiri tuleb otse postkastist ja digikolleeg käivitub ise.

## 8. 15:40 · Aju kasvatamine

Digikolleeg õpib sinu kirjutamisviisi sinu enda kirjadest. Vali üks või proovi mõlemat.

**A. Õpeta oma paranduse kaudu.** Võta mustand, mis ei kõlanud nagu sina. Kirjuta ise, kuidas sa kliendile vastaksid.

**Kleebi AI-le:** (lisa lõppu oma kiri)

```text
Selle kirja saadaksin ise. Võrdle seda oma mustandiga. Ütle, mis erines ja millisesse faili iga parandus sobib. Lisa minu sõnastus näitena, mitte reeglina. Ära muuda faile enne minu kinnitust.

MINU KIRI:
```

**B. Lisa oma saadetud kirjad.** Pane 3–5 kirja, mille oled ise klientidele saatnud, kausta `ettevotte-aju/sisend/`. Isikuandmed võid enne asendada märgenditega.

**Kleebi AI-le:**

```text
Loe kaustast sisend/ minu saadetud kirju. Vali neist eri olukordade vastused, mis näitavad minu kirjutamisviisi, ja paku need näideteks faili teadmus/kuidas-kirjutame.md. Üldista ainult seda, mida näed vähemalt kahes eri kirjas. Ära muuda faile enne minu kinnitust.
```

**Lisaproov:** anna testkiri, mis püüab digikolleegi juhiseid muuta (Tööruum T4). Digikolleeg ei tohi kirjas olevaid käske täita ja peab sulle neist märku andma.

## 9. 16:15 · Iseseisev lõpuproov

Ava uus vestlus. Kirjuta ise, mida digikolleegilt tahad, ja anna seni kasutamata kiri: K3, T3 või sinu kolmas testkiri. Ära lisa vihjet.

Hinda vastust enne hindamisvõtme vaatamist. Märgi endale: iseseisvalt / abiga / osaliselt / ei saanud.

## 10. 16:35 · Failid endale ja sinu number

**Kleebi AI-le:**

```text
Uuenda failis kaart.md digikolleegi viimase testi kuupäeva ja lõiku „Järgmine”. Näita muudatust enne salvestamist.
```

Kontrolli:
- failid on sinu arvutis, mitte ainult vestluses;
- parandused on failides;
- tead, kuidas järgmisel korral alustada: uus vestlus, „Digikolleeg, vasta sellele kirjale” ja kiri.

Ütle oma number: mitu tundi kuus võtavad sinu korduvad tööd (`teadmus/korduvad-tood.md`, lõik „Kokku”).

## 11. 16:50 · Tagasiside

Millisele kirjale lased digikolleegil järgmisena vastata? Milles sa teda veel ei usalda? Pane vastused [logisse](../logi/proovi-logi.md).

---

## Hea teada

- **„Katmata”** failis tähendab: selle kohta digikolleeg oletusi ei tee. See ei ole viga.
- **Konto mälu:** Claude ja ChatGPT võivad lugeda sinu konto mälu. Kontrolli faili: kui parandus on failis, töötab see ka uues vestluses.
- **Näide ei ole mall:** kui häälefailis on vaid üks näide, võib digikolleeg hakata seda igal pool kordama. Töötoas piisab iga olukorra kohta ühest sinu vastusest. Hiljem lisa teine.
