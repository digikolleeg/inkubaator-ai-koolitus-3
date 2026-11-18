# Ettevõtte aju: algpakk

Siia paned kirja, mida AI peab sinu ettevõtte kohta teadma: mida müüd, kellele ja kuidas kliendiga räägid. Uues vestluses annad talle need failid ega pea kõike otsast peale seletama.

Kaustas on tavalised tekstifailid sinu arvutis. Neid saad kasutada Claude'i ja ChatGPT-ga (ka Codexi äpis). Uut kontot ega programmi pole vaja.

## Seitse osa

Seitse osa on kaustas `teadmus/`, iga osa üks fail.

| Fail | Mis seal on | Enne töötuba |
|---|---|---|
| `mina.md` | sinu roll, mida otsustad ainult sina | hiljem |
| `kes-me-oleme.md` | mida ettevõte teeb, kellele, mida ei tee, tööpiirid AI-le | **jah** |
| `faktid.md` | mida müüd, hinnad, tingimused | **jah** |
| `kliendid.md` | kes ostab, mida küsib, miks loobub | hiljem |
| `kuidas-kirjutame.md` | kuidas kirjutad, sinu enda saadetud vastused | **jah** |
| `susteemid.md` | mis tööriistad sul on ja mida kopeerid käsitsi ühest teise | hiljem |
| `korduvad-tood.md` | iga nädal korduvad tööd ja nende ajakulu | **jah** |

Failist `kaart.md` näed, millised osad on täidetud ja mis viimati muutus. Kausta `sisend/` pane hinnakiri, märkmed ja vanad pakkumised. Töötoas valmiv tööjuhis läheb kausta `digikolleegid/` ning AI kirjutatud mustandid kausta `mustandid/`.

## Kuidas see on üles ehitatud

Kaust järgib Andrej Karpathy „LLM wiki” ülesehitust:

| Kiht | Siin | Mis see on |
|---|---|---|
| toormaterjal | `sisend/` | sinu lisatud materjal; AI loeb, aga ei muuda |
| teadmus | `teadmus/` | kontrollitud tekst, mille oled kinnitanud |
| sisukord ja logi | `kaart.md` | mis on täidetud, mis muutus |
| reeglid | `AGENTS.md` (`CLAUDE.md` suunab sinna) | kuidas AI kausta kasutab |

Iga osa faili alguses on lühike kirjeldus, seis ja kuupäev. Seda plokki nimetatakse frontmatteriks. AI loeb kõigepealt kaardi ja kirjeldused ning avab selle töö jaoks vajalikud failid.

## Kuidas alustada (30 minutit)

1. Laadi kaust alla ja pane see kohta, kust selle üles leiad.
2. Ava Claude või ChatGPT ja anna talle ligipääs sellele kaustale. Juhend: [Claude](../tootuba/claude.md) · [ChatGPT](../tootuba/codex-chatgpt.md).
3. Kirjuta: `Loe AGENTS.md ja alusta eeltööd.`

AI küsib ühe küsimuse korraga ja täidab neli osa: ettevõte, pakkumine, hääl ja korduvad tööd. Iga osa lõpus näitab ta faili ja küsib kinnitust. Lõpus näed, mitu tundi kuus su korduvad tööd võtavad. Kui tahad pooleli jätta, kirjuta `paus`. Järgmine kord kirjuta `jätka`.

Kui AI ei näe kausta (näiteks ChatGPT veebis), lisa vestlusele manusena kuus faili: `INTERVJUU.md`, `kaart.md`, `teadmus/kes-me-oleme.md`, `teadmus/faktid.md`, `teadmus/kuidas-kirjutame.md` ja `teadmus/korduvad-tood.md`. Kirjuta: `Loe INTERVJUU.md ja alusta eeltööd.` Salvesta failid, mida AI näitab, ise õigesse kohta: osad kausta `teadmus/`, `kaart.md` kausta juurde.

## Kolm reeglit

1. **Kliendi andmed välja.** Enne päris kirja kopeerimist eemalda nimed, telefonid, e-posti aadressid, aadressid ja tellimusnumbrid. Juhend: [puhastamine](../andmekaitse/puhastamine.md).
2. **Puuduv info jääb nähtavaks.** Kui sa pole infot andnud, jääb koht tühjaks ja saab märke „katmata”. AI ei tohi sinna ise hinda ega muud fakti välja mõelda.
3. **Testkirjad hoia väljaspool seda kausta.** Vali 3 kliendikirja, tee need puhtaks ja salvesta eraldi kausta. Nendega kontrollid töötoas, kas digikolleeg vastab õigesti. Kui AI on neid juba näinud, test ei loe.

## Pärast töötuba

Täida ülejäänud osad omas tempos. Failis `teadmus/korduvad-tood.md` kirja pandud tööde seast saad valida järgmise töö, mida digikolleegile anda.
