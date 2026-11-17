# Digikolleegi töötuba

Tallinna Ettevõtlusinkubaator, 24. november 2026, kell 13–17.

## Alusta siit

1. **Enne töötuba:** [tee eeltöö](EELTOO.md). Arvesta 30 minutiga.
2. **Töötoa ajal:** [töötoa käsiraamat](tootuba/README.md). Kõik sammud ja kleebitavad tekstid on seal järjekorras.

Giti pole vaja. Vajuta GitHubis **Code → Download ZIP** ja paki lahti.

## Mida töötoas ehitame

Digikolleegi: AI-abilise, kes kirjutab mustandi vastuseks ühele korduvale pöördumisele sinu ettevõttes. Saatmise otsustad sina.

```text
pöördumine -> digikolleeg loeb sinu faile -> mustand või küsimus sulle
                                              |
                          vale vastus -> parandus õigesse faili -> uus vestlus
```

Kell 17 oskad ilma juhendajata:

- avada uue vestluse ja anda digikolleegile õiged failid;
- anda ette seni kasutamata pöördumise;
- saada sobiva mustandi või põhjendatud küsimuse endale;
- märgata väljamõeldud fakti või lubadust ja panna parandus õigesse faili.

## Mis kus on

| Kaust | Mis seal on | Kas AI-le anda |
|---|---|---|
| [`tootuba/`](tootuba/) | käsiraamat; eraldi juhend Claude'ile ja Codexile/ChatGPT-le | ei, see on sinu jaoks |
| [`intervjuu/`](intervjuu/) | kleebitav intervjuu, mis teeb sinu tööjuhise `digikolleeg.md` | jah, kleebi vestlusesse |
| [`naidisfirmad/`](naidisfirmad/) | kaks väljamõeldud ettevõtet: Käpakamber (koerasalong) ja Tööruum (IT-hooldus) | jah, ühe firma kaust korraga |
| [`testkirjad/`](testkirjad/) | näidisfirmade testpöördumised | ainult kirja tekst, ükshaaval |
| [`vastused/`](vastused/) | testide hindamisvõtmed | **ei**; ava alles pärast vastust |
| [`ettevotte-aju/`](ettevotte-aju/) | sinu ettevõtte aju: seitse osa ja intervjuu, mis need täidab | jah, see on sinu kaust |
| [`andmekaitse/`](andmekaitse/) | kuidas päris kirjad enne AI-le andmist puhtaks teha | ei |
| [`logi/`](logi/) | proovi logi, kuhu paned kirja, mis töötas ja mis mitte | ei |

Näidisfirmad on täielikult välja mõeldud. Nende hindu ega tingimusi ei kanta sinu ettevõtte faktidesse.

## Kontakt

Heigo Tolppa, Digikolleeg
