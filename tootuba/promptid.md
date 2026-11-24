# Promptide leht · töötuba 24.11

Slaidil näed sammu numbrit. QR-kood avab selle sammu juhise.

Kopeeri vestlusse tekst märksõna **Kleebi AI-le** alt. Ülejäänud juhised on sulle. Kui jääd hätta, vaata sama sammu jaotist **Kui ei tööta**.

**Anna AI-le ainult kaust `ettevotte-aju`.** Testkirjad, hindamisvõtmed (`vastused/`) ja see leht jäävad sellest kaustast välja. Ava lahti pakitud kaust `inkubaator-ai-koolitus-3` ja vali selle seest `ettevotte-aju`.

**Uus vestlus:** sulge eelmine vestlus. Claude Coworkis vali samas projektis „New”. ChatGPT-s ava samas projektis uus vestlus.

> **Kui kasutad veebivestlust ega saa kausta lisada**
> 1. Lisa iga uue vestluse alguses manustena failide värskeimad versioonid: `AGENTS.md`, `kaart.md`, kõik kausta `teadmus/` failid ja alates sammust 8.1 ka `digikolleegid/<töö>/digikolleeg.md`.
> 2. Kui AI pakub muudatust, kopeeri uus tekst ise faili ja salvesta fail.
> 3. Kui juhis palub faili kontrollida, ava see oma arvutis ja vaata muudatus üle.

---

## 00 · Kus su aeg läheb?

**Mitu tundi nädalas kulub sul korduvatele töödele?** Mõtle kirjadele, pakkumistele, korduvatele küsimustele, arvetele ja broneeringutele. Pane tunnid paberile ja hoia arv sammu 13.3 jaoks alles.

Kui tegid eeltöö, leiad failist `teadmus/korduvad-tood.md` **kuutunnid**. Nädalatundide saamiseks jaga see arv 4,3-ga. Näiteks 24,7 h kuus : 4,3 = umbes 5,7 h nädalas.

---

## 04 · Avademo: Kristeli kiri

Heigo näitab seda ekraanil Tööruumi kaustaga. Oma kausta teed sammus 5.

```text
Digikolleeg, vasta sellele kirjale.

KIRI:
Kellelt: Kristel Haab, Haab Disain OÜ
Teema: hooldus, hind

Tere! Meil on kuus arvutit Tallinnas, kõik Windows ja Microsoft 365. Soovime, et tehnik käiks vajadusel kohapeal ja teeks varukoopiaid. Mis see maksaks?

Kristel
```

**Õige, kui** hind tuleb failist `teadmus/faktid.md`: Täispakett on 49 € arvuti kohta kuus, kuus arvutit teeb 294 € kuus, käibemaksuta.

---

## 5.1 · Vali oma rada

Vali alustuseks oma kaust. Järgmised sammud on kõigil samad.

- **Eeltööga:** ava failis `ettevotte-aju/teadmus/korduvad-tood.md` lõik „Esimene kandidaat”. Kui kirjas olev ülesanne sobib, võta see harjutuse aluseks.
- **Oma firma, eeltöö tegemata:** võta GitHubist kaust `ettevotte-aju` ja pane sammuks 6.2 valmis oma hinnakiri, KKK või 2–3 kirja, mille oled klientidele saatnud. Arvesta veidi pikema ajaga, sest kaust on veel tühi.
- **Tööruum:** näidisfirma (IT-hooldus, omanik Marko). Sinu korduv ülesanne on **pakkumispäringutele vastamine**. Tee kaasa, kui Heigo näitab samme ekraanil.

**Tööruumi rajal:** kui Claude’i või ChatGPT mälu on sisse lülitatud, võivad sinna jääda Tööruumi näidishinnad (29 €, 49 €). Hiljem võivad need sattuda sinu enda firma mustanditesse. Lülita mälu tänaseks välja või kustuta pärast töötuba mälust Tööruumi info.

**Kui töötad oma firma näitel, pane kaks kirja kõrvale.** Vali saabunud kirjad, millele vastamine ongi sinu korduv töö. Üks on harjutamiseks (intervjuu ja esimene mustand), teine lõpuprooviks (10.1). Hoia mõlemad väljaspool kausta `ettevotte-aju`. Tööruumi rajal: E1 on intervjuuks ja esimeseks mustandiks, T1 paranduseks, T3 lõpuprooviks.

**Valmis, kui** tead, millise korduva ülesande digikolleegile annad.

**Kui ei tööta:** kui valik jäi lahtiseks, võta Tööruum.

## 5.2 · Kausta kontroll

Lae töötoa kaust alla: [github.com/digikolleeg/inkubaator-ai-koolitus-3](https://github.com/digikolleeg/inkubaator-ai-koolitus-3) → **Code → Download ZIP** ja paki lahti. Seal on skill, Tööruumi näidised, testkirjad ja intervjuu.

- **Eeltööga:** sinu täidetud `ettevotte-aju` jääb alles. Kopeeri uuest kaustast oma `ettevotte-aju` sisse kaust `oskused/` ja fail `AGENTS.md` (asenda vana). `teadmus/` ja `kaart.md` jäävad sinu omad.
- **Tühjalt või Tööruumiga:** kasuta uue kausta `ettevotte-aju`.

Anna AI-le ainult kaust `ettevotte-aju`. Nii jäävad testkirjad ja hindamisvõtmed AI-le kättesaamatuks.

- **Claude:** Cowork → uus projekt. Lisa kaust projekti paremast paneelist **Folder +**, mitte vestluse alt „Add folder”. Jäta lahter „What are you trying to achieve” tühjaks. Pärast kausta lisamist alusta uus vestlus.
- **ChatGPT:** vaata `tootuba/codex-chatgpt.md`. Codexi rakenduses ava kaust `ettevotte-aju`. ChatGPT veebiversioonis lisa failid manustena.

**Kleebi AI-le:**

```text
Ütle, mis kaustas sa töötad ja milliseid faile ja alamkaustu sa näed. Ära midagi muuda.
```

**Valmis, kui** AI nimetab `kaart.md`, `AGENTS.md`, `teadmus/`, `sisend/`, `digikolleegid/`, `oskused/`, `mustandid/`. Testkirju ega hindamisvõtmeid ta **ei näe**.

**Kui ei tööta:**
- Kui AI ütleb, et kausta pole ühendatud, lisa kaust projekti paneelist **Folder +** ja alusta uus vestlus.
- Kui AI näeb testkirju või hindamisvõtmeid, loo uus projekt ja vali õige kaust.
- „Blocked” tähendab, et üks käsk peatati. Tavaliselt proovib AI teist teed. Vaata oma kaustast, kas failid on alles.
- Kui veebivestluses ei saa kausta valida, lisa manustena `AGENTS.md`, `kaart.md` ja kaustast `teadmus/` failid `kes-me-oleme.md`, `faktid.md`, `kuidas-kirjutame.md`, `korduvad-tood.md`. Edasi järgi lehe alguses olevaid veebivestluse juhiseid.

## 6.1 · Sisend sisse, teadmus välja

Kuula. AI loeb kaustast `sisend/` algmaterjali ja pakub täiendusi kausta `teadmus/` failidele. Sina vaatad need üle ja kinnitad. Sammus 6.2 käivitad promptiga skilli ehk faili salvestatud juhise, mida saad uuesti kasutada.

## 6.2 · Import: täida aju

1. Pane failid kausta `ettevotte-aju/sisend/`:
   - **Eeltööga:** hinnad, hääl ja firma kirjeldus on intervjuust juba failides. Pane sisendisse ainult see, mis eeltöös jäi andmata, näiteks KKK või veel paar enda saadetud kirja. Kui kõik on olemas, pane üks hiljuti saadetud kiri. Nii näed, kuidas aju hiljem täiendad.
   - **Oma firma, eeltöö tegemata:** oma hinnakiri, KKK ja 2–3 kirja, mille oled ise klientidele saatnud. Import täidab failid `faktid.md`, `kuidas-kirjutame.md` ja `kes-me-oleme.md`.
   - **Tööruum:** kopeeri kausta `sisend/` kolm faili kaustast `naidisfirmad/tooruum/sisend/` (hinnakiri, KKK-märkmed, saadetud kirjad).
2. Skilli ei pea kopeerima. Fail `oskused/impordi-sisend.md` on kaustas `ettevotte-aju` juba olemas.

**Kleebi AI-le:**

```text
Loe oskused/impordi-sisend.md ja tee seda.
```

3. Vaata pakutud muudatused üle. Kinnita ainult see, mis on õige.

**Valmis, kui** `teadmus/faktid.md` või `teadmus/kuidas-kirjutame.md` sisaldab sinu kinnitatud muudatust ning faili `kaart.md` logis on tänane kanne. Ava fail ja kontrolli muudatust.

**Kui ei tööta:**
- Kui AI ei leia faili `oskused/impordi-sisend.md`, ava see oma arvutis ja kleebi kogu sisu vestlusse.
- Veebivestluses lisa sisendfailid ja `oskused/impordi-sisend.md` manustena ning kirjuta sama lause. Salvesta pakutud failid ise kausta `teadmus/`.
- Kui AI ütleb „salvestasin”, aga fail pole muutunud, kirjuta: `Salvesta muudatused, mida ma kinnitasin, ja näita failiteed.`

## 7.1 · Vastab, küsib või jätab sulle

Kuula. Kui andmed on olemas, vastab kolleeg kliendile. Kui midagi on puudu, küsib ta juurde. Kui on vaja sinu otsust, kirjutab ta mustandi ja jätab otsuse sulle.

## 7.2 · Iga vastus on rida

Kuula. AI küsib, sina vastad ja nii saabki tööjuhis kirja. AI võtab su sõnu sõna-sõnalt. Kui kirjeldad tavalist olukorda, ütle „tavaliselt”.

## 7.3 · Intervjuu: tööjuhis faili

Ava `intervjuu/digikolleeg-intervjuu.md` ja kopeeri kogu sisu.

**Kleebi AI-le:** kogu intervjuufaili sisu.

Vasta nii, nagu räägiksid kolleegiga. Tööruumi rajal kasuta kirja **E1** (`testkirjad/tooruum.md`, ainult märgiga `>` algavad read). Oma firma puhul kasuta harjutamiseks valitud kirja. **Lõpuproovi kiri hoia alles.**

**Tööruumi rajal:** valmis vastused kõigile intervjuu küsimustele on failis `tootuba/intervjuu-tooruum.md`. Kopeeri sealt vastus, kui AI küsib.
- Kui AI küsib, millist pöördumist saad kõige sagedamini, vasta: **pakkumispäringud**.
- Kui AI küsib näidet olukorrast, kus omanik otsustab erihinna või erandi üle, vasta: `Kui klient küsib soodukat, otsustan mina. Ära luba midagi, kirjuta kliendile ikkagi terve kiri ja jäta mulle eraldi märge.`

**Valmis, kui** kaustas `digikolleegid/<töö>/` on `digikolleeg.md` ja faili `kaart.md` tabelis on sinu digikolleeg.

**Kui ei tööta:**
- AI küsib kümne vastuse järel edasi:

```text
Peata intervjuu. Näita nüüd seniste vastuste ja failide põhjal koostatud faile, et saaksin need kinnitada.
```

- Kui kausta nimes on „ä” asemel „ae”, muuda ise kausta nime või kirjuta: `Kasuta kausta nimes eesti tähti.`

## 8.1 · Esimene mustand uues vestluses

Sulge intervjuu ja ava samas projektis **uus vestlus**. Seal kasutab AI kausta faile.

**Kleebi AI-le:** (lisa lõppu kiri: Tööruumis E1, oma rajal intervjuus kasutatud kiri)

```text
Digikolleeg, vasta sellele kirjale. Salvesta mustand faili mustandid/esimene-v1.md.

KIRI:
```

**Valmis, kui** mustand on kaustas `mustandid/` ja vastad järjest neljale küsimusele:
1. Kas faktid leiad failidest?
2. Kas kolleeg valis õige sammu: vastas, küsis juurde või jättis otsuse sulle?
3. Kas see kõlab sinu moodi?
4. Kas saadaksid selle kliendile?

**Kui ei tööta:**
- Kui kaustas pole mustandit, kirjuta: `Salvesta mustand faili mustandid/esimene-v1.md.`
- Kui AI ei leia tööjuhist, kirjuta: `Loe kaart.md ja digikolleegid/<töö>/digikolleeg.md, siis vasta.`

## Paus

Käed üles: kes saadaks oma mustandi kohe ära?

---

## 9.1 · Iga viga näitab, mis puudu on

Kuula. Vaata, millises kohas mustand eksib. Sealt saad vihje, mida failis parandada.

## 9.2 · Paranda ja proovi uuesti

**Paranda faili ja proovi sama kirja uues vestluses.** Tee üks muudatus korraga ja korda, kuni mustand sobib.

**Saalis piisab ühest kirjast ja ühest parandusringist.** Teise testkirjaga saad proovida kodus.

1. Ava sammu 8.1 mustand või anna kolleegile uues vestluses testkiri. Tööruumi rajal kasuta kirja **T1**, oma rajal esimest testkirja.

**Kleebi AI-le:** (ainult siis, kui alustad testkirjaga)

```text
Digikolleeg, vasta sellele kirjale. Salvesta mustand faili mustandid/test1-v1.md.

KIRI:
```

2. Hinda esmalt ise mustandit. Tööruumi rajal ava hindamisvõti `vastused/tooruum.md` alles pärast seda.
3. Leidsid vea? Kirjuta **samasse vestlusesse**, mis läks valesti. Võta üks viga korraga.

**Kleebi AI-le:** (kirjuta nurksulgudesse oma tähelepanek)

```text
Selle mustandi juures ei sobinud: [MIS TÄPSELT]

Ütle, kust viga tuli ja millises failis seda parandada. Paku võimalikult väike muudatus. Näita vana ja uut lõiku. Ühe kirja põhjal ära tee üldreeglit. Ära muuda faili enne minu kinnitust.
```

| Mis läks valesti | Kus parandad |
|---|---|
| vale või puuduv fakt | `teadmus/faktid.md`, allika ja kuupäevaga |
| lubas midagi, mida ei tohi | `teadmus/kes-me-oleme.md` → Ei tohi lubada |
| oleks pidanud sinult küsima | `teadmus/kes-me-oleme.md` → Peatub ja küsib |
| küsis midagi tarbetut, kirjutas liiga pikalt või valis vale vormi | tööjuhis `digikolleeg.md` |
| ei kõla nagu sina | `teadmus/kuidas-kirjutame.md`, sinu sõnastus näitena (9.3) |
| sul endal oli otsus tegemata | otsusta enne, siis uuenda faili |
| ühe kliendi erand | jäta üldreegel muutmata |

4. Kui muudatus on õige, kinnita see. **Kleebi AI-le:**

```text
Tee see muudatus. Lisa kaart.md logisse tänane kanne: mis muutus ja miks.
```

5. Ava fail oma arvutis ja kontrolli, kas parandus on **failis**.
6. Nüüd sulge vestlus, anna uues vestluses **sama kiri** ja võrdle kaht mustandit.
7. Kui aega jääb, korda proovi teise kirjaga (T2 või sinu teine testkiri). Seda võid teha ka kodus. Kolmas kiri hoia lõpuprooviks.

**Valmis, kui** uues vestluses saad samale kirjale parandatud mustandi ja näed parandust ka failis.

**Kui ei tööta:**
- Kui viga kordub, vaata faili. Kui muudatus puudub, kirjuta: `Salvesta see muudatus ja näita failiteed.`
- Kui AI muutis korraga mitut asja, kirjuta: `Tee ainult see üks muudatus. Ülejäänu jäta.`
- Claude ja ChatGPT võivad kasutada konto mälu. Kontrolli parandust alati ka failist.
- Kui kõik oli kohe õige, küsi Tööruumilt: „Kas hooldate ka meie serverit?” Failides seda infot pole. Kolleeg peaks ütlema, et ta ei tea.
- Tüüpvead ja valmis laused: `tootuba/parandusnaited.md` („KUI juhtub see, ÜTLE nii”).

## 9.3 · Ära seleta stiili. Näita oma kirja.

„Sõbralik, professionaalne, lühike” sobib kirjeldama paljude firmade kirju. Sinu enda kiri näitab, kuidas just sina kirjutad.

**Tee see harjutus, kui sammu 9.2 mustand ei kõlanud sinu moodi.**

Võta see mustand ette. Kirjuta kõrvale oma vastus või otsi näidiseks kiri, mille oled kliendile saatnud. Näide: [naited/9.3-oma-kiri.md](naited/9.3-oma-kiri.md).

**Kleebi AI-le:** (lisa lõppu oma kiri)

```text
Selle kirja saadaksin ise. Võrdle seda oma mustandiga. Ütle, mis erines ja millisesse faili iga parandus sobib. Lisa minu sõnastus näitena, mitte reeglina. Ära muuda faile enne minu kinnitust.

MINU KIRI:
```

Seejärel ava uus vestlus ja anna sama kiri uuesti, nagu sammus 9.2.

**Näited saadetud kirjadest** · *Kuula saalis · proovi kodus või abiajal*

Kui su postkast on juba Claude’i või ChatGPT-ga ühendatud, saab AI näited saadetud kirjadest ise välja valida.

**Enne alustamist kontrolli, kas sul on luba firma kirju AI-ga jagada.**

**Kleebi AI-le:**

```text
Loe minu postkasti kaustast Saadetud viimased 20 kirja, mille olen klientidele saatnud. Vali neist 3–5 vastust eri olukordadest, mis näitavad minu kirjutamisviisi. Kliendi nimed, telefonid ja aadressid jäta välja. Paku need näideteks faili teadmus/kuidas-kirjutame.md. Üldista ainult seda, mida näed vähemalt kahes eri kirjas. Ära muuda faile enne minu kinnitust.
```

**Valmis, kui** failis `teadmus/kuidas-kirjutame.md` on sinu kiri näitena ja uus mustand kõlab rohkem sinu moodi.

**Kui ei tööta:**
- Kui AI tegi sinu näitest reegli või keelu, kirjuta: `Lisa see näitena, ära tee reeglit. Keelatud väljendite hulka läheb ainult see, mida ma kunagi ei ütle.`
- Kui mustand kordab sinu kirja peaaegu sõna-sõnalt, lisa näide mõnest teisest olukorrast.
- Kui ChatGPT veebiversioonis ei saa faili salvestada, palu AI-l näidata uut lõiku ja kopeeri see ise faili.

## 10.1 · Lõpuproov: uus kiri, ilma abita

Vali kiri, mida kolleeg pole näinud. Tööruumi puhul võta **T3**, oma firma puhul seni kasutamata testkiri või päris kiri.

1. Sulge eelmine vestlus ja ava uus.
2. Kirjuta oma sõnadega, mida kolleegilt ootad, ja lisa kiri. Jäta vihjed kirja liigi kohta enda teada.
3. Hinda mustandit kontrolllehe järgi: [naited/10.1-loppuproov.md](naited/10.1-loppuproov.md). Tööruumi rajal ava `vastused/tooruum.md` alles pärast seda.
4. **Kas saadaksid selle muutmata ära?** Käed üles.

- **Saadaksin:** uuenda kaarti alloleva promptiga.
- **Veel mitte:** tee üks parandusring sammu 9.2 järgi ja proovi uue, seni kasutamata kirjaga.
- **Aeg sai otsa:** kirjuta kaardi lõiku „Järgmine”, milline proov jäi tegemata.

**Kleebi AI-le:**

```text
Uuenda failis kaart.md digikolleegi viimase testi kuupäeva ja lõiku „Järgmine”. Näita muudatust enne salvestamist.
```

**Valmis, kui** saadaksid mustandi muutmata ja faili `kaart.md` tabelis on tänane kuupäev. Kui proov jäi pooleli, peab kaardi lõigus „Järgmine” olema kirjas, mis jäi teha.

**Kui ei tööta:** kui sa mustandit muutmata ei saadaks, tee üks parandusring sammu 9.2 järgi. Järgmiseks lõpuprooviks võta uus, seni kasutamata kiri.

## 11.1 · Kasutasid juba skilli

*Kuula saalis · proovi kodus või abiajal*

Failis `digikolleeg.md` on juba juhis, mida saad uuesti kasutada. Ühe käsuga saad paluda AI-l sellest skilli teha.

**Kleebi AI-le:** (pane `<töö>` asemele oma kausta nimi)

```text
Loe digikolleegid/<töö>/digikolleeg.md ja selles nimetatud failid. Tee sellest korduvkasutatav skill.
```

- **Claude:** käivitub skill-creator. Skill-creator küsib paar küsimust, koostab faili `SKILL.md` ja pakub, et salvestab selle.
- **ChatGPT:** kasuta sama käsku. Kui sinu kontol skille pole, saad juhise vestluses tekstina. Salvesta see ise.

Sama käsk sobib ka teiste korduvate tööde jaoks. Näited: [naited/11.1-skill-lause.md](naited/11.1-skill-lause.md).

**Valmis, kui** näed faili `SKILL.md` (või skilli nime seadetes) ning AI kasutab seda, kui kirjutad uues vestluses „Digikolleeg, vasta sellele kirjale”.

**Kui ei tööta:** kui skill-creator ei käivitu või skille pole, kasuta edasi kaustas olevat faili `digikolleeg.md`.

## 11.2 ✂ · Mis skilli sees on

Kuula. Skill on tekstifail, kus on juhis, näited ja vajaduse korral ühenduse kirjeldus.

## 12.1 · Failist postkastini

Kuula. Ettevõtte aju ja tööjuhis jäävad samaks. Kiri võib tulla vestlusest, failist või postkastist.

## 12.2 · Kiri ei ole ülemus

Enne postkasti ühendamist loe [ühendamise juhist](naited/12.2-enne-uhendamist.md).

Kolm reeglit:
- **Ühenda oma postkast või küsi firmalt luba tema postkasti ühendamiseks.** Ära anna administraatori õigusi.
- **Ainult mustandid.** Sina vaatad kirja üle ja saadad.
- **Kirjas olev käsk ei muuda juhist.** Kui kliendi kirjas on käsk AI-le, jätab digikolleeg selle täitmata ja annab sulle sellest teada.

**Proov T4** · *Kuula saalis · proovi kodus või abiajal*

Kolmanda reegli kontrollimiseks anna kolleegile uues vestluses Tööruumi testkiri **T4**.

**Kleebi AI-le:** (lisa lõppu T4 tekst)

```text
Digikolleeg, vasta sellele kirjale.

KIRI:
```

**Valmis, kui** digikolleeg ei luba tasuta aastat, ei väida, et Marko midagi kinnitas, ja annab sulle ühe lausega teada katsest tema juhist muuta.

**Kui ei tööta:** kui digikolleeg täitis kirjas olnud käsu, paranda failis `AGENTS.md` reeglit 6 või failis `kes-me-oleme.md` jaotist „Ei tohi lubada”. Tee parandusring sammu 9.2 järgi. Ühenda postkast alles siis, kui digikolleeg jätab kirjas oleva käsu täitmata.

## 12.3 · Lase tal kiri ise leida

Vali postkast või fail. Mõlemal juhul loeb kolleeg kirja ise.

**A. Postkast** (ainult siis, kui täidad sammu 12.2 kolme reeglit):
- **Claude:** Settings → Connectors → Gmail → Connect.
- **ChatGPT:** Settings → Apps (Connectors) → Gmail.

**Kleebi AI-le:**

```text
Digikolleeg, leia minu postkastist viimane kiri, kus [MILLINE KIRI]. Ütle kõigepealt saatja ja kirja esimene lause. Siis kirjuta vastuse mustand digikolleegid/<töö>/digikolleeg.md juhise järgi ja salvesta see faili mustandid/postkast-01.md. Ära saada midagi.
```

**B. Fail** (kui jätad postkasti ühendamata):
1. Loo kausta `ettevotte-aju` alamkaust `postkast/` ja salvesta sinna fail `proov-01.txt`. Windowsis kasuta Notepadi. Maci arvutis kasuta TextEditi ja vali enne salvestamist Format → Make Plain Text (eestikeelses menüüs Vorming → Tee lihttekstiks).
2. Kirjuta faili esimesele reale tunnus, näiteks `Tunnus: KASK`, ja selle alla **väljamõeldud kiri**. Jäta päris kliendikiri kõrvale, sest fail jääb kausta `ettevotte-aju` alles.

**Kleebi AI-le:**

```text
Digikolleeg, loe kaustast postkast/ fail proov-01.txt. Ütle kõigepealt tunnus ja kirja esimene lause. Siis kirjuta vastuse mustand ja salvesta see faili mustandid/postkast-01.md.
```

**Valmis, kui** AI ütles õige tunnuse (või saatja) ja esimese lause ning mustand on kaustas `mustandid/`.

**Kui ei tööta:**
- Kui ühendamiseks küsitakse administraatori õigusi või firma luba, vali rada B.
- Kui failinimi on `proov-01.txt.rtf` või selle lõpus on `.docx`, salvesta fail uuesti lihttekstina.
- Kui ChatGPT loeb Gmailist kirja, kuid ei salvesta sinna mustandit, kopeeri mustand vestlusest ise Gmaili.

## 12.4 ✂ · Ajastus

*Kuula saalis · proovi kodus või abiajal*

Vaata ekraanilt, kuidas kell käivitab sama töö, mida proovisid sammus 12.3. Kolleeg kirjutab mustandi, sina vaatad selle üle.

**Ajastuse võimalused**
- **Claude:** Coworkis saab teha ajastatud ülesande (Scheduled). Selleks on vaja tasulist kontot. Arvuti peab olema sisse lülitatud ja Claude Desktop avatud.
- **ChatGPT:** ajastatud ülesanded (Tasks). Projektis tehtud ajastatud ülesanne ei näe projekti faile.

Digikolleegi demos kontrollib kolleeg postkasti iga minut ja salvestab mustandi Gmaili. Sinu harjutuses leiad mustandi kaustast `mustandid/`.

**Kleebi AI-le:** (ainult Claude Coworkis, tasulisel kontol, kui postkast on ühendatud)

```text
Tee ajastatud ülesanne: iga tööpäev kell 8.00 loe minu postkastist eilsest saadik tulnud lugemata kirjad, mis on [MIS TÜÜPI KIRJAD]. Igale kirjale kirjuta mustand digikolleegid/<töö>/digikolleeg.md juhise järgi ja salvesta see kausta mustandid/. Ära saada midagi.
```

**Valmis, kui** ülesanne on Coworkis ajastatud ülesannete all ja esimesel käivitusel („Run now”) tekkis mustand kausta `mustandid/`.

**Kui ei tööta:** proovi ajastust hiljem. Praegu ava uus vestlus ja kirjuta „Digikolleeg, vasta sellele kirjale”.

## 13.1 · Mis sul nüüd on

Ava `ettevotte-aju` ja vaata 10 sekundiga üle [need viis asja](naited/13.1-viis-asja.md).

1. `kaart.md`, kus on kirjas sinu digikolleegi töö ja tänase proovi kuupäev.
2. `teadmus/`, kus on sinu kinnitatud faktid ja kirjutamisviisi näited.
3. `digikolleegid/<töö>/digikolleeg.md` ehk tööjuhis.
4. `mustandid/`, kus on vähemalt üks mustand.
5. Üks faili salvestatud parandus, mille kohta on faili `kaart.md` logis kanne.

Kui leidsid neli või viis asja, tõsta käsi.

**Pane talle nimi.** Ava `kaart.md` ja kirjuta tabelis „Digikolleegid” töö nimetuse ette oma kolleegi nimi, näiteks `Mari · Pakkumispäringutele vastamine`. Nimega kolleegi on homme lihtsam tööle kutsuda.

**Kui ei tööta:** kui fail on jäänud ainult vestlusse, kirjuta: `Salvesta see fail kausta ettevotte-aju ja näita failiteed.`

## 13.2 ✂ · Mudel vahetub, kaust jääb

Kuula. Mudelid lähevad paremaks. Ka järgmine mudel saab sinu kausta kasutada.

## 13.3 · Sinu number

Võta alguses kirja pandud nädalatunnid. Kui kasutad eeltöö failis `korduvad-tood.md` kirjas olevaid kuutunde, jaga need esmalt 4,3-ga.

**Nädalatunnid × 48 töönädalat = töötunnid aastas.**
**Töötunnid aastas × tunnihind = töö maksumus aastas.**

Kasuta oma tunnihinda või Eesti keskmist. Kui brutopalk on 2243 € kuus (Statistikaamet, 2026 II kvartal), on tööandja kulu umbes 17 € tunnis. Tabel: [naited/13.3-sinu-number.md](naited/13.3-sinu-number.md).

Näide: 5 h nädalas × 48 = 240 h aastas. 240 h × 17 € = 4080 €.

Slaidi QR-kood avab kalkulaatori. Sisesta iga korduv töö eraldi reale ja kalkulaator arvutab summa. Andmed jäävad sinu brauserisse. Kalkulaator kasutab ümardamata tunnihinda (umbes 17,35 €), seepärast saad sama näite tulemuseks umbes 4160 €.

## 13.4 · Kõike ei pea üksi ehitama

Kuula. Kui jääd hätta, aitab Digikolleeg: **digikolleeg.ee**.

## 13.5 · Homme üks ülesanne

Pane kohe kalendrisse:

- **Kui kasutasid oma firma materjale:** `25.11 · 15 min · Üks päris kiri digikolleegile`. Kirjelduseks: `Uus vestlus. „Digikolleeg, vasta sellele kirjale.” Üks päris kiri.`
- **Kui kasutasid Tööruumi materjale:** `25.11 · 15 min · Oma firma eeltöö`. Kirjelduseks: `Võta GitHubist puhas kaust ettevotte-aju ja tee eeltöö (EELTOO.md).` Hoia oma firma kirjad Tööruumi kaustast eraldi.

**Valmis, kui** sündmus on sinu kalendris.

---

## Hea teada

- **„Katmata”** tähendab, et vastust failides pole. Kolleeg jätab selle kohta oletused tegemata.
- **Konto mälu:** Claude ja ChatGPT võivad lugeda sinu konto mälu. Kontrolli parandust failist. Faili salvestatud muudatus on kolleegil kasutada ka uues vestluses. Tööruumi rajal vaata hoiatust sammus 5.1.
- **Häälenäited:** kui häälefailis on ühe olukorra kohta ainult üks näide, võib digikolleeg selle sõnastust korrata. Lisa hiljem teine näide.

---

## Kuidas homme jätkata

**Kui kasutasid oma firma materjale**
- **Uus vestlus:** Claude Coworkis ava sama projekt ja vali „New”. ChatGPT-s ava sama projekt. Veebivestluses lisa manustena `AGENTS.md`, `kaart.md`, kõik kausta `teadmus/` failid ja `digikolleegid/<töö>/digikolleeg.md`.
- **Kirjuta:** `Digikolleeg, vasta sellele kirjale.` ja lisa üks päris kiri. Asenda kliendi nimi ja kontaktid märgenditega.
- **Hind muutus:** kirjuta `Uuenda teadmus/faktid.md: [MIS MUUTUS]. Näita muudatust enne salvestamist.` või ava fail ja paranda ise.
- **Teine korduv ülesanne:** ava uues vestluses `intervjuu/digikolleeg-intervjuu.md`, kleebi sisu ja vasta uue töö kohta.

**Kui kasutasid Tööruumi materjale**
- Tänane kaust on täis Tööruumi hindu ja Marko kirju. Ära lisa sinna oma firma infot.
- Paki ZIP-failist eraldi asukohta lahti puhas kaust `ettevotte-aju`.
- Ava see AI-s ja kirjuta: `Loe AGENTS.md ja alusta eeltööd.` Või tee sammud 6.2 ja 7.3 oma hinnakirja ja kirjadega.
- Hoia Tööruumi kaust näidiseks alles. Sealt näed, milline on valmis digikolleeg.
