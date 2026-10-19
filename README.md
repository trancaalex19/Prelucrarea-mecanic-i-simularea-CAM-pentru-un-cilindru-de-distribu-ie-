# CNC Distribution Cylinder CAM

Proiectarea procesului de fabricare, simularea CAM și generarea codului NC pentru reperul Cilindru de Distribuție cu Flanșă.

## Despre Proiect

Acest depozit conține documentația tehnică completă, modelele 3D, simulările CAM și programele CNC necesare fabricării reperului **Cilindru de Distribuție cu Flanșă**. Proiectul tratează întregul ciclu de pregătire a fabricației pentru un volum de producție de 1.250 bucăți/an, încadrându-se în categoria producției de serie mijlocie.

Semifabricatul ales este obținut prin matrițare la cald pe ciocan din oțel de calitate C45 (OLC 45). Această metodă asigură o orientare favorabilă a fibrelor de material, o rezistență mecanică sporită și un adaos minim de prelucrare față de forma finală a piesei.

Procesul tehnologic este conceput pentru a garanta respectarea cerințelor constructive și funcționale critice, precum ajustajele de precizie (treapta IT7 pentru alezajul Ø12 H7 și găurile de ghidare Ø4 P7) și calitatea suprafețelor (rugozități Ra = 0.4 µm pentru alezajele funcționale și Ra = 0.8 µm pentru suprafața frontală de sprijin).

## Specificații Tehnice

| Parametru | Detaliu |
| :--- | :--- |
| Denumire Reper | Cilindru de Distribuție cu Flanșă |
| Material | Oțel C45 / OLC 45 (SR EN 10083) |
| Semifabricat | Matrițat la cald pe ciocan (adaos mare) |
| Volum Producție | 1.250 bucăți/an (Serie mijlocie) |
| Masa / Volum | 0.172 kg / 45.04 cm³ |
| Utilaj CNC | Centru de strunjire-frezare Mazak Quick Turn 250MY |
| Precizie Dimensională | Trepte IT7, IT8, IT9 (ISO 2768-m) |
| Rugozități Critice | Ra = 0.4 µm (alezaj finisat), Ra = 0.8 µm (față frontală) |

## Software și Echipamente

* **CAD / Modeling:** CATIA V5 (construcția modelului 3D și determinarea proprietăților masei), SolidWorks (reprezentarea spațială a ansamblului piesa-semifabricat).
* **CAM & Simulare:** SolidWorks CAM (definirea originilor tehnologice, generarea traseelor de sculă, optimizarea vitezelor și verificarea coliziunilor).
* **Mașină-Unealtă:** Strung CNC Mazak Quick Turn 250MY dotat cu scule antrenate, axă C și axă Y, permițând realizarea operațiilor combinate de strunjire, frezare și găurire dintr-un număr minim de prinderi.
* **Scule & Echipamente:** Scule așchietoare de înaltă performanță din gama Sandvik Coromant (burghie din carbură CoroDrill 860.1/460.1, freze CoroMill Plura 1P220, bare de canelat MB-E12 și cuțite de strunjire/retezare cu plăcuțe DCMT/DNMG).

## Flux Tehnologic și Poziționări CNC

Procesul este structurat pe principiul concentrării operațiilor pe mașini-unelte CNC, fiind împărțit în două poziționări tehnologice principale:

### Setup 1 (Prima Poziționare)
* **Orientare și Fixare:** Orientare pe suprafața exterioară brută a semifabricatului și strângere în universalul cu 3 bacuri al mașinii CNC.
* **Operații Executate:**
  * Strunjire de degroșare și finisare pe fața frontală și profilul exterior.
  * Frezare 2.5D profil lateral superior utilizând axa Y și scula antrenată CoroMill Plura.
  * Centruire și găurire frontală pentru cele 4 orificii Ø6.5 dispuse pe cercul de divizare, orificiile Ø12 și găurile Ø4.
  * Găurire centrală din plin în trepte (Ø8, Ø10.5, Ø12).
  * Canelare interioară pentru profilul Ø13 cu bară MB-E12.
  * Retezare completă a piesei din bara de material.

### Setup 2 (A doua Poziționare)
* **Orientare și Fixare:** Repoziționarea piesei debitate (rotită la 180°) prin prindere pe suprafața cilindrică deja prelucrată, utilizând bacuri moi uzinate special la diametrul piesei pentru a proteja calitatea suprafeței.
* **Operații Executate:**
  * Strunjire frontală de semifinisare și finisare pentru aducerea piesei la cota de lungime finală și realizarea rugozității de Ra 0.4 µm.
  * Executarea teșiturilor exterioare de protecție.
  * Centruire și găurire centrală pe fața din spate (Ø8, Ø12, Ø16).

## Autor

* **Student:** Trancă Alexandru-Constantin
* **Specializarea:** Informatică Aplicată, Facultatea de Inginerie Industrială și Robotică, UNSTPB
* **Coordonatori:** Prof. dr. ing. Sergiu TONOIU / Şl. dr. ing. Marius LAZĂR
