# Ettevõtte aju: algpakk

See kaust on koht, kuhu paned kirja selle, mida AI sinu ettevõtte kohta teadma peab. Üks kord kirja, iga kord kasutusel. Ilma selleta seletad igas vestluses otsast peale, mida müüd ja kuidas kliendiga räägid.

Kaust on tavalised tekstifailid sinu arvutis. Töötab Claude'i, ChatGPT ja Codexiga. Ühtegi kontot ega programmi juurde vaja ei ole.

## Seitse osa

| Kaust | Mis seal on | Enne töötuba |
|---|---|---|
| `1-mina/` | sinu roll, mida otsustad ainult sina | hiljem |
| `2-ettevote/` | mida ettevõte teeb, kellele, mida ei tee, tööpiirid AI-le | **jah** |
| `3-pakkumine/` | mida müüd, hinnad, tingimused | **jah** |
| `4-kliendid/` | kes ostab, mida küsib, miks loobub | hiljem |
| `5-haal/` | kuidas kirjutad, sinu enda saadetud vastused | **jah** |
| `6-susteemid/` | mis tööriistad sul on ja mida kopeerid käsitsi ühest teise | hiljem |
| `7-tood/` | iga nädal korduvad tööd ja palju need aega võtavad | **jah** |

Fail `kaart.md` näitab, mis osad on täidetud ja mis viimati muutus. Kaust `sisend/` on toormaterjalile (hinnakiri, märkmed, vanad pakkumised). Kaust `digikolleegid/` on töötoas valmivale tööjuhisele. Kaust `mustandid/` on AI kirjutatud mustanditele.

## Kuidas see on üles ehitatud

Sama muster, mida kasutab Andrej Karpathy „LLM wiki”:

| Kiht | Siin | Mis see on |
|---|---|---|
| toormaterjal | `sisend/` | mida iganes sinna paned; AI loeb, aga ei muuda |
| teadmus | seitse osa | kontrollitud tekst, mille oled kinnitanud |
| sisukord ja logi | `kaart.md` | mis on täidetud, mis muutus |
| reeglid | `AGENTS.md` (`CLAUDE.md` suunab sinna) | kuidas AI kausta kasutab |

Iga osa faili alguses on frontmatter: lühike kirjeldus, seis ja kuupäev. AI loeb esmalt kaardi ja kirjeldused ning avab ainult selle faili, mida töö vajab. Kõike korraga ta ei laadi.

## Kuidas alustada (30 minutit)

1. Laadi kaust alla ja pane see kohta, kust selle üles leiad.
2. Ava Claude, ChatGPT või Codex ja anna talle ligipääs sellele kaustale. Juhend: [Claude](../tootuba/claude.md) · [Codex või ChatGPT](../tootuba/codex-chatgpt.md).
3. Kirjuta: `Loe AGENTS.md ja alusta eeltööd.`

AI küsib ühe küsimuse korraga ja täidab neli osa: ettevõte, pakkumine, hääl ja korduvad tööd. Iga osa lõpus näitab ta faili ja küsib kinnitust. Lõpus saad teada, mitu tundi kuus su korduvad tööd võtavad. Kui tahad pooleli jätta, kirjuta `paus`. Järgmine kord kirjuta `jätka`.

Kui AI ei näe kausta (näiteks ChatGPT veebis), lisa vestlusele manusena kuus faili: `INTERVJUU.md`, `kaart.md`, `2-ettevote/kes-me-oleme.md`, `3-pakkumine/faktid.md`, `5-haal/kuidas-kirjutame.md` ja `7-tood/korduvad-tood.md`. Kirjuta: `Loe INTERVJUU.md ja alusta eeltööd.` Salvesta failid, mida AI näitab, ise õigesse kausta.

## Kolm reeglit

1. **Kliendi andmed välja.** Enne kui kleebid päris kirja, võta välja nimed, telefonid, e-postid, aadressid ja tellimusnumbrid. Juhend: [puhastamine](../andmekaitse/puhastamine.md).
2. **Mida pole kirjas, seda AI ei tea.** Tühi koht jääb tühjaks ja saab märke „katmata”. Väljamõeldud hind on hullem kui puuduv hind.
3. **Testkirjad hoia väljaspool seda kausta.** Vali 3 kliendikirja, tee puhtaks ja pane kõrvale eraldi kausta. Nendega kontrollid töötoas, kas digikolleeg vastab õigesti. Kui AI on neid juba näinud, test ei loe.

## Pärast töötuba

Täida ülejäänud osad omas tempos. Iga uus korduv töö failis `7-tood/korduvad-tood.md` on järgmise digikolleegi kandidaat.
