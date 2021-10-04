# Követelmény specifikáció 
#### (Az első elkészítendő dokumentum)

## A jelenlegi helyzet
####  (Kifejtésre kell kerülni az aktuális helyzetnek)
- (mielőtt még a szoftver elkészül)
- (tartalma 3-7 mondat)

Az országban az emberek természete álltalában nem vidám, sok gond és viszontakság éri őket. 
Ezért születik meg számukra ez a weboldal, hogy szórakoztassa őket.
Felrázza őket a mélabúságból és jókedvet vigyen a mindennapok közé.

## Kívánt rendszer
#### (A megrendelő állatal vágyott program leírása)
- (fungcióit nem kell teljes mértékben kifejteni, de nagyvonalakban le kell írni mit tartalmazzon)
- (tartalma szintén 3-7 mondat)

A megrendelő vágyik egy weblapra, ami elképzelései szerint egy Viccportál,
Ez az oldal tetszés szerint bővíthető, középen egy üzenőfal szerűen legördülő lista,
ahol kommentszerűen különböző hosszúságú vicceket lehet feltölteni és olvasni.
Felül a menüsorban ki lehet választani milyen stílusú vicceket szeretne olvasni a felhasználó,
így a középen lévő üzenőfal megváltozva kiszűri ezeket a vicceket és ezeket jeleníti meg. 
Mivel a megrendelő nem vágyik a bonyolultságra, ezért elég egy adott kategóriának megfeleni.

## Elvárt működés
#### (A program működésével kapcsolatos információk)
- (Ki kell fejteni hogy maga a szoftver amit elkészítünk milyen fugciókat tartalmaz és hogyan működnek)
- (tartalma a fentiek alapján)

A felhasználó bejelentkezés nélkül megtekintheti a vicceket, tud szűrést végrehajtani,
de nem tud ujabb vicceket hozzáírni, ehez be kell regisztrálnia és belépnie.
A regisztráció ingyenes és autómatikus, de az Admin elveheti a jogukat hogy tudjanak vicceket felvinni
ha azok nem felelnek meg az elvárt követelményeknek. 

## A rendszer futtatása
#### (Opcionális, de jó ha van növeli a dokumentum méretét és hitelességét)
- (Ha asztali alkalmazás, Ird le hogyan indítod el, mi kell a használatához)
- (Ha webes, akkor az adatbázist és a szervert írd)

A futtatáshoz szükség van Internetre , böngészőböl futatható ugyanis weboldalról van szó
A megrendelőnek rendelkeznie kell egy szervergéppel/vagy bérelt tárhelyel és egy Domain címmel
A szervergépnek mindig futnia kell, ahoz hogy el tudják érni az oldalt a kiensek

## Szükséges funkciók listája
#### (Ebbe a fejezetbe kerülnek azok a fungciók amiket meg akarunk valósítani)
- (Ajánlott táblázat szerűen elrendezni)
- (tartalma mindig több fungció annál több)

| Modul | ID |Név | Leírás |
|---|---|---|---|
| Backend | F1 | Adatbázis | Az adatbázis tárolja az alkalmazás által használt adatokat |
| Backend | F2 | Funkciók | A felhasználó által használt parancsok végrehajtása |
| Frontend | F3 | Felhasználó beléptető oldal | A felhasználó beléptetésére használt oldal. |
| Frontend | F4 | Regisztrációs oldal | A felhasználó regisztrációjára használt oldal. |
| Frontend | F5 | Main oldal | Beléptetés után megjelenő felület. |

## További lehetséges funkciók listája
#### (Ebbe a fejezetbe kerülnek azok a fungciók amiket amiket a !!jövőben még!! meg akarunk valósítani)
- (Lehetséges bővítések amiket úgy gondolunk, vagy a vevő úgy gondol hogy hasznos kiegészítései
 lehetnek a programnak)
 
| Modul | ID |Név | Leírás |
|---|---|---|---|
| Frontend | F6 | Side oldal | A fő oldal melett csinálhatunk, kiegészíthetjük akár hírekkel, vagy melléktörténetekkel egy külön menüpont alatt. |
