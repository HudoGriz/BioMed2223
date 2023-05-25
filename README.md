# Modeliranje metabolizma in integracija transkriptomskih podatkov
Repozitorij za predavanje o modeliranju bioloških procesov na modulu Funkcijska genomika (doktorski študij Biomedicina).

Izvedli smo analizo podatkov iz diferenčne analize RNA sekvenc, primerjajoč tumor WILMS z kontrolnimi vzorci. 
Podatki so bili predhodno obdelani s trimerjem Cutadapt, psevdo-prilegani in kvantificirani s SALMON 
in analizirani z R-knjižnico DEseq2. Identificirali smo genetske razlike med skupinama, 
kar nam je omogočilo razumevanje bioloških procesov in poti povezanih s tumorjem WILMS, na ravni genov.

Za razumevanje na nivoju metabolnih pretokov smo kvantificirane poravnave sekvenc RNA,
rangirali od -1 do 3. Na podlagi RECON3D smo testirali spremembe v metabolnih pretokih,
vključno z biomaso.

Ob uporabi modela Human-GEM, smo naleteli na koputacijske težave.
