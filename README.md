# Modeliranje metabolizma in integracija transkriptomskih podatkov
Repozitorij za predavanje o modeliranju bioloških procesov na modulu Funkcijska genomika (doktorski študij Biomedicina).

Izvedli smo analizo podatkov iz diferenčne analize RNA sekvenc, primerjajoč tumor WILMS z kontrolnimi vzorci. Podatki so bili predhodno obdelani s trimerjem Cutadapt, psevdo-prilegani in kvantificirani s SALMON ter analizirani z R-knjižnico DEseq2. Identificirali smo genetske razlike med skupinama, kar nam je omogočilo razumevanje bioloških procesov in poti povezanih s tumorjem WILMS, na ravni genov.

Za razumevanje na nivoju metabolnih pretokov smo kvantificirane poravnave sekvenc RNA in gene rangirali od -1 do 3, glede na intenziteto signala. Na podlagi RECON3D smo testirali spremembe v metabolnih pretokih, vključno z biomaso. Ustvarjenemu modelu smo vzorčili metabolni pretok, in sicer 1000 vzorcev po algoritmu ACHR. Tisoč vzorcev za model tumorja smo primerjali z vzorci normalnega modela. Na značilno različnih reakcijah smo izvedli obogatitveno analizo. Rezultat, je devet značilno različnih poti. Ojačani so bili: ekstracelularni transport, sfingolipidni metabolizem, oksidacija maščobnih kislin, keratan sulfatna sinteza, hondroitin sinteza in glikosfingolipidna presnova. Reducirane poti so: mitohondrijski transport, ekstracelularna izmenjava in presnova škroba ter saharoze.

Ob uporabi modela Human-GEM, smo naleteli na računske težave. Analiza seta podatkov z uporabo Human-GEM in orodjem CORDA je v povprečju znašala štiri ure.
