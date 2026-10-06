# Doprinos hrvatskomu prijevodu Selaha

Čitatelji, oni koji uče hebrejski, prevoditelji i svi koji su odrasli na
hrvatskom — dobro došli. Ti poznaješ ovaj jezik bolje od stroja. Ovaj
dokument kaže kako možeš pomoći.

Tekst je izradio stroj i čeka uho izvornoga govornika. Ali **neke stvari
koje ovdje izgledaju kao pogreške učinjene su namjerno.** Pročitaj prvi
dio prije nego što ispraviš i jednu riječ.

## Prijava pogreške, prijedlog

- Otvori **Issue** u repozitoriju:
  <https://github.com/selah-project/selah-hr>
- Ili, ako znaš i sam ispraviti, otvori **Pull request**.
- Ili nam piši: <support@selahproject.com>

## Što treba u prijavi

- Mjesto: knjiga, glava, stih (na primjer: `genesis 1:1`).
- Što sada ondje stoji i zašto je pogrešno.
- Što bi trebalo stajati, ako znaš.

## Što se NE ispravlja — izbori, ne pogreške

- **Jahve.** יהוה se piše *Jahve* i sklanja se na osnovi (*Jahvin*,
  *Jahvi*, *Jahvu*, *Jahvom*). Ne *Gospodin*, ne *GOSPODIN*, ne *Gospod*,
  ne *Jehova*, ne *Bog* na mjestu Imena. *gospodaru moj* za čovjeka je
  ispravno.
- **Elohim** ostaje *Elohim*. *bog* i *bogovi* malim slovom ispravni su
  samo za bogove naroda i kumire (Izlazak 32,8).
- **⟨את⟩ nije tiskarska pogreška.** Hebrejski označava određeni objekt
  riječju את; hrvatski ga ne označava. Znak ostaje vidljiv. Ne briši ga.
- **Riječi po hebrejskom zvuku**: *ruah*, *hesed*, *cedek*, *Tora*,
  *Šabat*, *Miškan*, *Šeol*. To nisu hrvatske riječi koje nedostaju — to
  su hebrejske riječi zadržane jer ih nijedna hrvatska riječ ne pokriva.
  *Šeol* nije *pakao*.
- **Imena po hebrejskom zvuku**: *Avraham*, *Jicak*, *Jaakov*, *Moše*,
  *Aharon*, *Jisrael*, *Micrajim*, *Jerušalajim* — ne *Abraham*, *Izak*,
  *Jakov*, *Mojsije*, *Aron*, *Izrael*, *Egipat*, *Jeruzalem*.
- **Nema predznanja.** Postanak 22,1 ne zna Postanak 22,13. Gdje čitatelj
  Biblije očekuje poznatu riječ, ponekad će vidjeti jednostavan hebrejski.
  To je namjerno.
- **Množina ostaje množina** (Postanak 1,26: *Načinimo*).

## Što se ispravlja — i gdje nam trebaš

- **Nespretan hrvatski.** Ako rečenica ne zvuči kao čovjek koji govori,
  ispravi je. To je najveća potreba.
- **Ekavica i srpske riječi.** Standard je **ijekavica** (*rijeka*,
  *dijete*, *vrijeme*, *mlijeko*) i hrvatske riječi (*kruh*, *zrak*,
  *tisuća*, *jučer*, *uopće*). *reka*, *dete*, *hleb*, *vazduh*,
  *hiljada*, *juče* — ispravi.
- **Ćirilično slovo u latiničnoj riječi.** Neka ćirilična slova izgledaju
  kao latinična (*а* i **a**, *е* i **e**). Cijeli tekst je latinicom.
- **Engleske riječi** — engleski je jezik stroja. *the*, *of*, *and* nisu
  hrvatski, ni u tekstu ni u ⟨⟩.
- **Jedno slovo mijenja smisao.** *vraćanje* (vraćanje duše, Ruta 4,15)
  nije *vračanje* (čaranje). Provjeri č i ć, đ i dž.
- **Prorok nije vrač.** נביא je *prorok*. *vrač* i *gatar* ispravni su
  samo gdje hebrejski govori o gatanju i čaranju.
- **Redak i tok koji se ne slažu.** Ako glosa nosi broj, Ime ili znak
  koji tok stiha ne nosi — ili obratno — prijavi.

## Pravila ispravka datoteka

- Jedna datoteka = jedan stih: `<knjiga>/<glava>/<stih>.json`.
- **Broj jedinica jednak je broju glosa**: svaka hebrejska riječna
  jedinica dobiva točno jednu glosu; ne oduzimaj, ne dodaj.
- Hebrejska riječ (`surface`) piše se kako stoji u izvoru. Ne mijenja se.
- Oznake **⟨את⟩** ostaju — nikada ih ne briši, nikada ih ne dodaj.
- Imena stoje po D1 (vidi
  `docs/methodology/translation-discipline/hr.md` u glavnom
  repozitoriju): **Jahve**, **Jah**, **Elohim**, **El**, **Eloah**,
  **Adonaj**, **Šadaj**, **Jahve Cebaot**. Naslov nikada ne stoji na
  mjestu Imena.
- Dodana riječ samo u ⟨⟩, samo hrvatska, i samo ako je hrvatska rečenica
  traži. Zagrade su `⟨` i `⟩` — ne `<` i `>`.

## Otvorena pitanja — prijavi, ne ispravljaj

Ovo još nije odlučeno. Ako imaš mišljenje, napiši ga i ostavi tekst:

1. **Sklonidba Imena** — *Jahvin*, *Jahvi*: je li to prirodan hrvatski?
2. **Imena ljudi** — hebrejski izgovor (*Avraham*, *Jicak*, *Jaakov*,
   *Moše*) ili predajno ime?
3. **Pravopis** — *ruah*, *hesed*, *cedek*, *Šabat*, *Miškan*.

## Mjerilo

Vjernost slovu prethodi čitljivosti. Ako ispravak čini rečenicu ljepšom,
ali je odvodi dalje od hebrejskoga slova, ne ulazi. Ako je čini
točnijom, molimo te za nj.

---

**English.** Contributions welcome: open an Issue or Pull request at
<https://github.com/selah-project/selah-hr>, or write to
<support@selahproject.com>. The text is machine-made and awaits a native
ear. One file = one verse; unit count equals gloss count; ⟨את⟩ markers
are never deleted or added; the D1 Names (Jahve, Elohim…) never yield to
titles; supplied words only in ⟨⟩, and only in Croatian. Ijekavian
standard; Serbian forms, Cyrillic letters and English words are faults.
Letter-faithfulness outranks readability.

## Conduct

Be honest, be kind, show your evidence. Distinguish certainty from
suggestion. The maintainers weigh and decide.
