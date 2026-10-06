# PROVENANCE — kako je ovaj prijevod nastao

*Hrvatski (hrvatski standard, latinica, ijekavica). 23.213 stihova.*

Ovo je zapis o tome kako je tekst u ovom repozitoriju izrađen i što je u
njemu trebalo ispraviti. Prijevod koji je izradio stroj nema težine ako
ne možeš vidjeti kako je nastao, pa ova datoteka kaže oboje — **i
pogreške, i one koje su provjere pogrešno pripisale stroju.**

---

## Pristup

Svaki je stih preveden iz hebrejskoga toga stiha, prema pisanim pravilima
— `docs/methodology/translation-discipline/hr.md` u projektu Selah,
napisanima na hrvatskom. Pravila: hebrejska riječ je jedinica; Ime ostaje
Ime (*Jahve*); dvostruka vjernost Ponovljenoga zakona 6,4 — ne dodaj, ne
oduzmi; nema predznanja, pa Postanak 22,1 ne zna Postanak 22,13; samo
Tanah, bez ijedne riječi Novoga zavjeta; nema prevoditeljskih bilješki.

Izvorni tekst je hebrejski suglasnički tekst s punktacijom, riječ po
riječ (OpenScriptures Hebrew Bible, WLC). Svaki stih daje dvije
površine: **glosu za svaku hebrejsku riječ** i **tok** — stih kao
hrvatsku rečenicu. Čuvaju se obje, jer se mogu razilaziti, a gdje se
razilaze, nešto nije u redu.

Prijevod je izradio jezični model (glm-5.3) 4. listopada 2026., od podneva
do predvečerja. Tijekom rada tekst je u više navrata pregledan
automatskim provjerama i čitanjem stihova; nekoliko je stihova ispravljeno
rukom.

## Što je hrvatski tražio

- **Hrvatski nije srpski.** Jezici su bliski, a standard je drukčiji:
  ijekavica (*rijeka*, *dijete*, *vrijeme*) i hrvatske riječi (*kruh*,
  *zrak*, *tisuća*, *jučer*). Pravila to kažu izrijekom, jer se stroj u
  bliskom jeziku najlakše oklizne prema susjedu.
- **Isto Ime kao srpski prijevod, drugim pismom.** Srpski prijevod piše
  *Јахве* ćirilicom; hrvatski *Jahve* latinicom, i sklanja ga na osnovi:
  *Jahvin*, *Jahvi*, *Jahvu*, *Jahvom*.
- **Hrvatski nema člana**, pa u ⟨⟩ ne smije stajati ni ⟨the⟩ ni ⟨ה⟩.

## Ime

Na završnoj provjeri 4. listopada sva 6.008 mjesta Imena nosila su
*Jahve*; *Gospodin*, *Jehova* i *Bog* na mjestu Imena nisu se pojavili
nijednom — od prve provjere do posljednje. Jedno mjesto koje se činilo
pogrešnim (Brojevi 10,14) nije bilo pogreška prijevoda: hebrejska riječ
*Jehuda* imala je oštećenu površinu koja je glasila יהוה. Površina je
vraćena iz izvora.

## Pogreške pronađene i ispravljene

- **Ćirilična slova u latiničnim riječima.** Neka ćirilična slova izgledaju
  jednako kao latinična (*а*/a, *е*/e), pa je stroj pisao *zlatа* i
  *bubregе* s ćiriličnim slovom. Pokušaj da se to spriječi pravilom nije
  uspio — udio je ostao isti prije i poslije. Zato je ispravljeno
  mehanički: 221 ćirilično slovo zamijenjeno je latiničnim blizancem u
  155 datoteka, svaka zamjena provjerena; riječi su ostale iste.
- **Oštećene hebrejske površine.** Hebrejska riječ stiha je doslovna kopija
  izvora, ali u 91 površini (86 datoteka) jedno je hebrejsko slovo bilo
  zamijenjeno latiničnim, ćiriličnim, arapskim ili kineskim znakom
  (ש → *š*, ו → *u*). Sve su vraćene iz izvora.
- **Engleski.** Nekoliko kratkih nizova stihova vraćeno je na engleskom
  (Hagaj 2,21–23; Psalam 40,5–8; 2 Ljetopisa 29,6). Ponovno su prevedeni.
- **Jedno slovo, drugi smisao.** U Ruti 4,15 *za vraćanje duše* (משיב נפש)
  postalo je *vračanje* — čaranje — zamjenom č za ć. Stroj je istu
  pogrešku ponovio i pri ponovnom prevođenju; ispravljena je rukom.
- **Vidioci nisu vrači.** U Izaiji 30,10 חזים (vidioci) bili su prevedeni
  *gatari*; ispravljeno.
- **Razmišljanje ostavljeno u tekstu.** U Ezekielu 1,21 stroj je u tok
  stiha upisao dva pokušaja spojena riječju *ispravljeno:*. Zadržano je
  njegovo ispravljeno čitanje, a ostatak uklonjen.
- **Prazni i slomljeni retci.** Nekoliko stihova bilo je prazno ili je
  imalo slomljen redak riječi; prevedeni su ponovno.

## Što je pogrešno izmjereno

Provjere koje su našle gornje pogreške optužile su i ispravan hrvatski:

- Provjera srpskih oblika optužila je *vremena* (ijekavski genitiv), *Bela*
  (Postanak 36,32, kralj Edoma) i *idete* (jer u sebi sadrži *dete*).
  Uklonjene su iz provjere.
- Provjera riječi *vrač* i *gatar* pročitala je svaki stih koji ih nosi:
  gotovo svi su ispravni — faraonovi čarobnjaci, Endor, zabrane u
  Levitskom zakoniku i Ponovljenom zakonu, Bileam, babilonski mudraci u
  Danijelu. Izaija 30,10 bio je jedina prava pogreška te vrste, a Ruta
  4,15 nađena je slučajno, istom provjerom.

Sve je to isti zakon: **riječ koja je ispravna u jeziku ne može je
osuditi provjera koja ne zna jezik.**

## Pogreške još neizliječene

Navodimo ih da čitatelj zna što može očekivati:

- **⟨את⟩ u toku i u retku riječi.** Kod nekih stihova (24 pri završetku
  prijevoda) tok i redak riječi ne slažu se oko znaka ⟨את⟩ — na primjer
  Ruta 4,15, gdje redak nosi ⟨את⟩, a tok ne.
- **Broj redaka i broj hebrejskih riječi.** Kod nekih stihova redak riječi
  imao je redak više ili manje od hebrejskoga teksta. Dana 6. listopada
  2026. provjera je izdvojila 83 stiha (broj redaka različit od broja
  hebrejskih riječi, prazni retci, engleski u ⟨⟩). Ti su stihovi uklonjeni
  i upravo se ponovno prevode; korpus se u isto vrijeme ponovno
  provjerava.
- **Nespretni oblici** koje stroj nije mogao čuti: *Osuvojene* (Jeremija
  48,41), *blagožen* (Psalam 40,5), arhaični naglasni znak u *gatarâ*
  (Suci 9,37; Mihej 5,11). Popis je u `NOTES.md`.

## Stanje ovoga teksta

**Nije ga pregledao izvorni govornik.** Objavljen je otvoreno jer se
skriveni tekst ne može ispraviti. `CONTRIBUTING.md` kaže što je namjeran
izbor, što je pogreška, a što otvoreno pitanje — na hrvatskom, za
čitatelja koji to može prosuditi.
