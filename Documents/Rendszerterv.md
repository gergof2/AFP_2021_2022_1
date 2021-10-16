# Rendszerterv

## A rendszer célja

- A rendszer célja egy olyan viccportál létrehozása, ahol a felhasználók kommentszerűen tudnak vicceket olvasni, illetve feltölteni.
- A vicceket kategóriákra bontva tudják elolvasni a látogatók.

## Projektterv
**Projekt szerepkörök, felelősségek**
-   szerepkörök
    - product owner: Tajti Tibor
    - scrum master: Szalóki Dávid, Ungi Keve, Seres Péter, Kerepesi Gergő
	- junior, medior, senior fejlesztők: (ha van)
-   felelősségek:
    - scrum master: A Scrum master felügyeli és megkönnyíti a folyamat fenntartását, segíti a csapatot, ha problémába ütközik, illetve felügyeli, hogy mindenki betartja-e a Scrum alapvető szabályait.
    - fejlesztők: A projekt elkészítése.

**Projekt munkások és felelősségeik**

-   Frontend: (ha készül)
-   Backend: (ha készül)
-   Adatbázis: (ha készül)
## Rendszerterv 

## Üzleti folyamatok modellje
- Üzleti szereplők:
  - Felhasználók, viccportál olvasói
  
- Üzleti folyamatok:
  - Viccek felvitele az adatbázisba
  - Esetleges helyesírási hibák javítása
  - Korrekciós feladatok

## Követelmények
 - Funkcionális
	- Böngészőben való működés
	- Az eltárolt viccek kategóriánkénti tökéletes megjelenítése
 - Nem funkcionális
	- Gyors működés, könnyen átlátható legyen
	- Egyszerű, egyértelmű kezelés
 - Törvényi előírások, szabványok
	- GDPR követelményeinek való megfelelés
	- Felnőtt tartalmú viccek szűrése

## Funkcionális terv
- Rendszerszereplők
  - Felhasználók
  
- Rendszerhasználati esetek és lefutásaik:
  - Felhasználó
    * Viccek felvitele, módosítása, törlése
  - Látogató
	* Viccek olvasása

- Menü hierarchiák
  - Kezdőlap
    * Kategóriák
    * Bejelentkezés

## Fizikai környezet
Kliens:
	- Eszköz: Asztali számítógép
	-  Operációs rendszer: Windows 7 vagy nagyobb
	- Szükséges applikációk: Chrome, Firefox, Edge, Safari böngésző
	- Konfiguráció: Nem specifikus.

Szerver:
	- Eszköz: Kliens
	- Specifikáció: Klienssel ekvivalens
	- Operációs rendszer: Windows 7 vagy nagyobb

## Absztrakt domain modell
A program működése során a felhasználók többféle szerepkörben is tudnak tevékenykedni. Egyszerre tudnak vicceket felvinni az adatbázisba, azokat módosítani, esetlegesen törölni is.
A látogatók csak olvasni tudják a weboldalon megtalálható vicceket.

## Architekturális terv
 - Backend
	A rendszerhez szükség van egy adatbázis szerverre, ebben az esetben MySql-t használunk.
	A kliensekkel JSON objektumokkal kommunikál.
 - Frontend
	A frontend elkészítéséhez HTML-t, CSS-t, JavaScript-et használunk.

## Adatbázis terv



## Implementációs terv
A Webes felület főként HTML, CSS, és Javascript nyelven fog készülni. Ezeket a technológiákat amennyire csak lehet külön fájlokba írva készítjük, és úgy fogjuk egymáshoz csatolni a jobb átláthatóság, könnyebb változtathatóság, és könnyebb bővítés érdekében.

## Tesztterv
Frontend:
	A frontend komponenseket real timeban teszteljük, WebStorm környezetben.

A user teszteket a fejlesztés végén végezzük el a funkciók kipróbálásával és dokumentálásával.

## Telepítési terv
- A rendszer beüzemelésekor ajánlott egy hozzá szakértő emberre bízni a beüzemelést mivel a szerver elindításához szükség van némi hozzáértéshez, így elkerülve az esetleges nem kívánatos hibák létrejöttét.

## Karbantartási terv
- Az alkalmazás folyamatos üzemeltetése és karbantartása, mely magában foglalja a programhibák elhárítását, a belső igények változása miatti módosításokat, valamint a környezeti feltételek változása miatt megfogalmazott program-, illetve állomány módosítási igényeket.

**Karbantartás:**
- Corrective Maintenance: A felhasználók által felfedezett és "user reportban" elküldött hibák kijavítása.
- Adaptive Maintenance: A program naprakészen tartása és finomhangolása.
- Perfective Maintenance: A szoftver hosszútávú használata érdekében végzett módosítások, új funkciók, a szoftver teljesítményének és működési megbízhatóságának javítása.
- Preventive Maintenance: Olyan problémák elhárítása, amelyek még nem tűnnek fontosnak, de később komoly problémákat okozhatnak.