---
title: "Üürikuulutused Tartu linnas"
subtitle: "Projekt aines \"Statistiline andmeteadus ja visualiseerimine\""
author: "Mats Ploompuu"
date: "15. mai 2016"
output: html_document
---

Töö aluseks on Taivo Pungas'e poolt kinnisvaraportaalist kv.ee (http://kinnisvaraportaal-kv-ee.postimees.ee/) vahemikus 22.06.2009 kuni 14.08.2015 kraabitud kuulutused, mis on kättesaadavad leheküljel http://pungas.ee/andmestikud/kv-ee-kinnisvarakuulutused/.

Töö eesmärk on uurida, kuidas Tartu korterite üürid sõltuvad linnaosast ning kuidas need ajas muutunud on. Samuti pakub huvi, kas peab paika levinud uskumus, et kevadel ja varasuvel, kui tudengid ülikooli lõpetavad, on paremad võimalused leida soodsaid pakkumisi kui suve lõpus, mil värsked tudengid endale aktiivselt elamispinda otsivad, ehk kuidas üürihinnad sõltuvad aastaajast.

###Üürihind linnaosade kaupa

Kui vaadata pelgalt üürihindasid, osutub, et keskmiselt kõige kallim on korterit üürida Tähtvere linnaosas ja Kesklinnas, mis eristuvad ülejäänutest üpris tuntavalt. Kõige odavamalt üüritakse kortereid välja Maarjamõisas ja Ropkas.

![](p1.png)
Loomulikult pole kõik välja üüritavad korterid sama suurusega. Korterite suurused erinevad ka linnaositi, näiteks üpriski ootuspäraselt on 30-ndatel uue linnaosana rajatud Tähtveres suhteliselt suured korterid.
Ajaloolises natuke vaesemas puitmajade piirkonnas Karlovas on aga väiksemad korterid.

Annelinnas on selgesti eristatavad korterid vastavalt tubade arvule: 1-toalised korterid, mille pindala jääb 30 ruutmeetri ümber, 2-toalised pindalaga peaaegu 50 ruutmeetrit, 3-toalised pindalaga 65 ruutmeetrit ja 4-toalised, mille pindala on peaaegu 80 ruutmeetrit. Võib eeldada, et selle tingib tüüpprojekti järgi ehitatud majade rohkus.

![](px.png)
Võttes arvesse korterite pindala, ehk leides keskmised üürihinna korteri ruutmeetri kohta, on ootuspäraselt kõige kallim korterit üürida kesklinnas. Järgnevad Vaksali piirkond ja Supilinn. Kõige odavama ruutmeetriüüriga korterid on Jaamamõisas, Annelinnas ja Ränilinnas.


![](p2.png)
Korteri üür ei ole lineaarselt seotud korteri suurusega - väiksemate korterite puhul on ruutmeetri üürihind märksa kõrgem. Vaadates korterite pindala ja ruutmeetri üürihinda kajastavad joonist, torkab silma, et juba mainitud kahe- ja kolmetoalised Annelinna tüüpkorterite mõju on ka siin nähtav. Seega ei näita ka eeltoodud ruutmeetripõhine üürihind otseselt piirkonna üürihinna taset, vaid võib olla osaliselt mõjutatud piirkonna korterite suuruste jaotusest.

![](pc.png)

###Üürihind kuude lõikes

Kõige soodsamalt antakse kortereid üürile varakevadel ja sügiskuudel. Suveperioodi kõrgemad hinnad on oodatavad, kuna värsked tudengid otsivad elamispindu. Seevastu jaanuari kõrgema hinna põhjus on selgusetu. 

Kõigis linnaosades toimub septembris üürihindades suur langus. Karlovas lisaks ka Oktoobris. Ühelt poolt võivad selleks ajaks soovijad juba elamispinna leidnud olla, teisalt aga on võimalik, et turule on jäänud proportsionaalselt enam kehvemaid ja odavamaid kortereid.

Joonisel on kajastatud need linnaosad, kus on üüripakkumisi kõige enam.

![](p3.png)

Ruutmeetri üürihinnad järgivad üpris sama trendi: kõrgemad hinnad suvekuudel ja jaanuaris, madalamad sügisel. Varakevadine natuke madalam hind siinkohal nii tugevalt esile ei tule.
![](p4.png)

Kui eeldada, et suvise hinnatõusu põhjuseks võivad olla tudengid, siis peaks see hinnatõus mõjutama vaid nende huvisfääris olevaid kortereid. Alloleval vasakpoolsel joonisel on kujutatud kortereid pindalaga 15-45 ruutmeetrid, parempoolselt suuremaid kui 45 ruutmeetrit. Osutub, et väiksemate korterite puhul ongi sesoonne kõikumine märksa tugevam.
![](p5_6.png)

###Üürihinna muutus läbi aastate

Nagu näha, on Tartu korterite üürihinnad aastast aastasse tõusnud. Kesklinnas on läbivalt kõige kallimad üürikorterid ning Annelinnas kõige odavamad.

Kahjuks puuduvad andmed varasemate aastate kohta, seega ei ole teada, kuidas majanduskriis üüriturgu mõjutas. 
![](p7.png)

Kui vaadata korterite üürihindu tubade arvu lõikes, jääb silma kahetoaliste korterite hinnatõusu pidurdumine või langemine 2015. aastal. Sellele oli eelnenud varasematel aastatel suhteliselt kiire tõus.

![](p8.png)

Kokkuvõttes midagi väga üllatavat Tartu üürituru kohta ei selgunud. Leidis kinnitust asjaolu, et suve lõpus küsitakse korterite eest natukene kõrgemat üüri. Samuti leidis kinnitust, et Annelinnas on korterite üürid kõige odavamad ja seda aastast-aastasse ja kõikide tubade arvuga korterite puhul ning Kesklinnas kõige kallimad (kui vaadata suuremaid linnaosi). Anomaalia, mis vajab veel uurimist, on jaanuarikuised kõrged üürihinnad.