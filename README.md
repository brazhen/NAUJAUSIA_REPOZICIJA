# STUDENTŲ DUOMENŲ ANALIZĖS PROGRAMA

TURINYS:
1. Apie programą
2. Funkcionalumas
3. Parsisiuntimo ir paleidimo instrukcija
4. Naudojimo instrukcija
5. Autorius

## APIE PROGRAMĄ

Ši programa sukurta siekiant supaprastinti studentų duomenų tvarkymą ir analizę. Ji suteikia vartotojui galimybę lengvai valdyti studentų informaciją, apdoroti ją įvairiais būdais ir gauti rezultatus pagal individualius poreikius. Programa yra universali ir tinka tiek rankiniam naudojimui, tiek automatizuotoms operacijoms.

## FUNKCIONALUMAS

Duomenų įvedimas: vartotojas gali pasirinkti vieną iš trijų būdų įvesti studentų duomenis: o Duomenis įvesti rankiniu būdu. o Nuskaityti iš išorinio failo (pvz., txt formato). o Generuoti atsitiktinius studentų duomenis, nurodant reikiamą skaičių įrašų.

#### PASIRINKUS RANKINĮ DUOMENŲ ĮVEDIMĄ:

• Galimybė pasirinkti kelių studentų duomenis norima įvesti.

• Galimybė sugeneruoti studentų namų darbų ir egzaminų rezultatus arba juos suvesti rankiniu būdu.

• Galutinio balo skaičiavimas: vartotojas gali pasirinkti, kaip skaičiuoti galutinį balą: o Pagal vidurkį (tradicinis metodas). o Pagal medianą (tiksliau atspindi nevienodai pasiskirsčiusius pažymius).

• Rezultatai pateikiami konsolėje lentelės pavidalu

#### PASIRINKUS DUOMENŲ NUSKAITYMĄ IŠ FAILO: 

• Programa gali nuskaityti bet kokio dydžio failus • Galutinio balo skaičiavimas: vartotojas gali pasirinkti, kaip skaičiuoti galutinį balą: o Pagal vidurkį (tradicinis metodas). o Pagal medianą (tiksliau atspindi nevienodai pasiskirsčiusius pažymius).

• Galutinis rezultatas pateikiamas konsoleje lentelės pavidalu 

PASIRINKUS FAILO GENERAVIMĄ: • Konteinerio pasirinkimas: programa suteikia galimybę generuojant duomenis pasirinkti tarp dviejų konteinerio tipų – vector ir list

• Suteikiama galimybė pasirinkti kiek studentų turi būti generuojamame faile (1 000, 10 000, 100 000, 1 000 0000, 10 000 000)

• Rūšiavimo strategijos: programa siūlo tris skirtingas rūšiavimo strategijas, skirtas studentų sąrašų valdymui: o Vieno konteinerio metodas: visi studentų duomenys laikomi viename konteineryje (pvz., std::vector), o sąrašai rūšiuojami pagal galutinius balus. o Dviejų konteinerių metodas: studentai, priklausomai nuo jų rezultatų (ar jų galutinis balas viršija nustatytą ribą), iš karto paskirstomi į du skirtingus konteinerius. o Optimizuotas metodas: derina efektyvumą ir mažina nereikalingų duomenų kopijavimą, kad būtų sutaupoma laiko ir išteklių apdorojant didelius duomenų kiekius.

• Galutiniai rezultatai pateikiami dviejuose atskiruose failuose, programos aplanke. Tinginukai – vidurkis mažesnis nei 5, Moksliukai – vidurkis yra 5 arba daugiau.



• Taip pat veiksmams atliekamiems pasirinkus failo generavimą daroma ir spartos analizė.

## PARSISIUNTIMO IR PALEIDIMO INSTRUKCIJA

1. Parsisiųskite "Source Code (ZIP)" iš github repozitorijos
2. Išskleiskite parsisiųstą ZIP aplanką darbalaukyje
3. Atsidarykite išskleistą aplanką ir paspauskite ant "Product" failo
4. Yra tikimybė, jog gausite pranešimą dėl nežinomo šaltinio, tad spauskite "vistiek vykdyti" ar panašiai..
5. Ant darbalaukio turi atsirasti programa pavadinimu "STUDENTŲ DUOMENŲ ANALIZĖ"

## NAUDOJIMO INSTRUKCIJA

Programa yra sukurta taip, kad būtų lengva ja naudotis – tereikia vadovautis ekrane matomomis instrukcijomis ir viskas bus gerai. Taip pat suklydę nesijaudinkite, nes programoje yra klaidų „medžiojimas“.

## AUTORIUS

Naglis Bražėnas

Vilniaus Universitetas, Duomenų Mokslas, 2 kursas.

El. paštas - naglis.brazenas@mif.stud.vu.lt, tel. nr. +37062196211

