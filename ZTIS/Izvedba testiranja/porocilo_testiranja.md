# Poročilo testiranja
## Vsebina

- [Podatki o testiranju](#podatki-o-testiranju)
- [T1 - Dodajanje projekta](#t1---dodajanje-projekta)
- [T2 - Dodajanje WP](#t2---dodajanje-wp)
- [T3 - Dodajanje Task-a](#t3---dodajanje-task-a)
- [T4 - Dodajanje osebe na projekt](#t4---dodajanje-osebe-na-projekt)
- [T5 - Nalaganje datoteke](#t5---nalaganje-datoteke)

## Podatki o testiranju

**Projekt**: Steer Project Manager

**Verzija**: Frontend commit 563758e ; backend commit d140376

**Tester**: Tibor Vito Šušnjara (tibor.susnjara@student.um.si)

**Brskalnik**: Firefox 144.0

**Operacijski sistem**: Windows 11 Home 24H2

V posameznem testnem primeru je izvedba predstavljena s tabelo oblike:
|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|...|...|...|...|

kjer je stanje lahko:
- "/" (zaradi odsotnosti pričakovanega rezultata ni mogoče določiti ujemanja med pričakovanim in dejanskim rezultatom)
- "OK" (ujemanje med pričakovanim rezultatom in dejanskim rezultatom)
- "FAIL" (neujemanje med pričakovanim rezultatom in dejanskim rezultatom)

Po koncu opisa izvedbe je podana odločitev o uspešnosti testnega primera, ki je lahko "uspešen", "neuspešen" ali "nedoločljiv".

[Nazaj na vrh](#vsebina)

## Povzetek testiranja
|Test|Naziv testa|Odločitev|
|---|---|---|
|T1|Dodajanje projekta|Uspešen|
|T2|Dodajanje WP|Uspešen|
|T3|Dodajanje Task-a|Uspešen|
|T4|Dodajanje osebe na projekt|Uspešen|
|T5|Nalaganje datoteke|Uspešen|

[Nazaj na vrh](#vsebina)

## T1 - Dodajanje projekta

**Izvedba**:

|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|Uporabnik stisne na gumb zgoraj desno za dodajanje projekta.|Ni specificiran.|Odprlo se je pojavno okno za vnos podatkov.|/|
|2|Izpolni vse potrebne podatke.|Ni specificiran.|Vsa polja prikazujejo vnešene vrednosti.|/|
|3|Stisne gumb "create" spodaj desno na modal-u.|Prikaz notification-a o uspešni kreaciji. Projekt se prikaže na listi vseh projektov.|Prikazala se je notifikacija o uspešni kreaciji projekta. Projekt je viden na seznamu vseh projektov.|OK

**Odločitev**: Uspešen

[Nazaj na vrh](#vsebina)

## T2 - Dodajanje WP

**Izvedba**:

|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|Uporabnik stisne gumb zgoraj desno za dodajanje WP.|Ni specificiran.|Odprlo se je pojavno okno za vnos podatkov.|/|
|2|Uporabnik izpolni vsa potrebna vnosna polja.|Ni specificiran.|Vsa polja prikazujejo vnešene vrednosti.|/|
|3|Uporabnik stisne gumb za oddajo form-e.|Prikaz notification-a o uspešemu vnosu novega WP. Nov WP je viden v listi vseh WP-jev.|Prikazala se je notifikacija o uspešni kreaciji "work package". "Work package" je viden na seznamu "Work packages" v sklopu projekta.|OK|

**Odločitev**: Uspešen

[Nazaj na vrh](#vsebina)

## T3 - Dodajanje Task-a

**Izvedba**:

|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|Uporabnik stisne gumb zgoraj desno na kartici WP za dodajanje taska.|Ni specificiran.|Odprlo se je pojavno okno za vnos podatkov o opravilu.|/|
|2|Uporabnik izpolni vsa potrebna vnosna polja.|Ni specificiran.|Vsa polja prikazujejo vnešene vrednosti.|/|
|3|Uporabnik stisne gumb za oddajo form-e.|Prikaz notification-a o uspešemu vnosu novega task-a. Nov task je viden pod WP-jem, kjer je uporabnik dodal task.|Prikazala se je notifikacija o uspešni kreaciji novega opravila. Novo opravilo je vidno znotraj kartice "work package", kateremu je opravilo bilo dodano.|OK|

**Odločitev**: Uspešen

[Nazaj na vrh](#vsebina)

## T4 - Dodajanje osebe na projekt

**Izvedba**:

|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|Uporabnik stisne na gumb za dodajanje oseb zgoraj desno.|Ni specificiran.|Odprlo se je pojavno okno za vnos podatkov o opravilu.|/|
|2|Poišče osebo v modalnem oknu in ga izbere.|Ni specificiran.|Pojavno okno se razširi z dodatnimi vnosnimi polji in podatki o izbrani osebi.|/|
|3|Izpolni vse ostale potrebne podatke v formi.|Ni specificiran.|Vsa polja vsebujejo vnesene podatke.|/|
|4|Pritisne gumb "assign".|Prikaz notificationa o uspešni dodaji osebe. Nova oseba se prikaže na listi oseb na projektu|Prikazala se je notifikacija o uspešnem dodajanju osebe v projekt. Dodana osebna je vidna na seznamu oseb v projektu.|OK|

**Odločitev**: Uspešen

[Nazaj na vrh](#vsebina)

## T5 - Nalaganje datoteke

**Izvedba**:

|Korak #|Postopek|Pričakovan rezultat|Rezultat|Stanje|
|---|---|---|---|--|
|1|Uporabnik stisne na gumb zgoraj desno za nalaganje datotek.|Ni specificiran.|Odprlo se je pojavno okno za nalaganje datoteke.|/|
|2|Uporabnik izbere datoteko za nalagat.|Ni specificiran.|Ime in velikost izbrane datoteke se pojavi na pojavnem oknu, nad gumbom "Upload".|/|
|3|Uporabnik stisne na gumb za potrditev nalaganja v modal-u.|Prikaže se notification o uspešnem nalaganju datoteke. Nova datoteka je vidna v datotekah projekta.|Prikazala se je notifikacija o uspešnem nalaganju datoteke. Naložena datoteka je vidna v seznamu datotek projekta.|OK|

**Odločitev**: Uspešen

[Nazaj na vrh](#vsebina)
