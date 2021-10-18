# Követelmény specifikáció 
#### (Az első elkészítendő dokumentum)

## A jelenlegi helyzet
####  (Kifejtésre kell kerülni az aktuális helyzetnek)
- (mielőtt még a szoftver elkészül)
- (tartalma 3-7 mondat)

Az országban az emberek természete általában nem vidám, sok gond és viszontakság éri őket. 
Ezért születik meg számukra ez a weboldal, hogy szórakoztassa őket.
Felrázza őket a mélabúságból és jókedvet vigyen a mindennapok közé.

## Kívánt rendszer
#### (A megrendelő álltal vágyott program leírása)
- (funkcióit nem kell teljes mértékben kifejteni, de nagyvonalakban le kell írni mit tartalmazzon)
- (tartalma szintén 3-7 mondat)

A megrendelő vágyik egy weblapra, ami elképzelései szerint egy Viccportál.
Ez az oldal tetszés szerint bővíthető, középen egy üzenőfal szerűen legördülő lista,
ahol kommentszerűen különböző hosszúságú vicceket lehet feltölteni és olvasni.
Felül a menüsorban ki lehet választani milyen stílusú vicceket szeretne olvasni a felhasználó,
így a középpen lévő üzenőfal megváltozva kiszűri ezeket a vicceket és ezeket jeleníti meg.
Mivel a megrendelő nem vágyik a bonyolultságra, ezért elég egy adott kategóriának megfelelni.

## Elvárt működés
#### (A program működésével kapcsolatos információk)
- (Ki kell fejteni hogy maga a szoftver, amit elkészítünk milyen funkciókat tartalmaz és azok hogyan működnek)
- (tartalma a fentiek alapján)

A felhasználó bejelentkezés nélkül megtekintheti a vicceket, tud szűrést végrehajtani,
de nem tud újabb vicceket hozzáírni, ehhez be kell regisztrálnia és belépnie.
A regisztráció ingyenes és automatikus, de az Admin elveheti a jogukat, hogy tudjanak vicceket felvinni, 
ha azok nem felelnek meg az elvárt követelményeknek. 

## A rendszer futtatása
#### (Opcionális, de jó ha van növeli, a dokumentum méretét és hitelességét)
- (Ha asztali alkalmazás, írd le hogyan indítod el, mi kell a használatához)
- (Ha webes, akkor az adatbázist és a szervert írd)

A futtatáshoz szükség van Internetre, ugyanis böngészőböl futtatható weboldalról van szó.
A megrendelőnek rendelkeznie kell egy szervergéppel/vagy bérelt tárhellyel és egy Domain címmel.
A szervergépnek mindig futnia kell, ahhoz hogy el tudják érni az oldalt a kliensek.

## Szükséges funkciók listája
#### (Ebbe a fejezetbe kerülnek azok a funkciók, amiket meg akarunk valósítani)
- (Ajánlott táblázatszerűen elrendezni)
- (tartalma mindig több funkció annál több)

| Modul | ID |Név | Leírás |
|---|---|---|---|
| Backend | F1 | Adatbázis | Az adatbázis tárolja az alkalmazás által használt adatokat |
| Backend | F2 | Funkciók | A felhasználó által használt parancsok végrehajtása |
| Frontend | F3 | Felhasználó beléptető oldal | A felhasználó beléptetésére használt oldal |
| Frontend | F4 | Regisztrációs oldal | A felhasználó regisztrációjára használt oldal |
| Frontend | F5 | Main oldal | Beléptetés után megjelenő felület |

## További lehetséges funkciók listája
#### (Ebbe a fejezetbe kerülnek azok a funkciók, amiket a !!jövőben még!! meg akarunk valósítani)
- (Lehetséges bővítések, amiket úgy gondolunk, vagy a vevő gondol úgy, hogy hasznos kiegészítései lehetnek a programnak)
 
| Modul | ID |Név | Leírás |
|---|---|---|---|
| Frontend | F6 | Side oldal | A fő oldal mellett csinálhatunk, kiegészíthetjük akár hírekkel, vagy melléktörténetekkel egy külön menüpont alatt. |

## Adatbázis

- (Az adatbázis megtervezett váza, lehet akár kép is)


- Tábla a felhasználók kezelésére:
   - userid: a felhasználóhoz tartozó azonosító
   - username: felhasználónév
   - password: jelszó
   - email: a felhasználó email címe
   - registerdate: regisztráció dátuma
- Külön tábla az adatok tárolására (viccek):
  - userid (kulcs)
  - Data: viccek tartalma

## A rendszerre vonatkozó törvények, rendeletek, szabványok és ajánlások felsorolása
  - (jogszabályok ami a rendszerünkre vonatkoznak)


  - AZ EURÓPAI PARLAMENT ÉS A TANÁCS (EU) 2016/679 RENDELETE (2016. április 27.) a természetes személyeknek a személyes
adatok kezelése tekintetében történő védelméről és az ilyen adatok szabad áramlásáról, valamint a 95/46/EK irányelv 
hatályon kívül helyezéséről (általános adatvédelmi rendelet


  - 2011.évi CXII. törvény az információs önrendelkezési jogról és az információszabadságról


  - 1.§2 E törvény célja a hatálya alá tartozó tárgykörökben az adatok kezelésére vonatkozó alapvető szabályok 
meghatározása annak érdekében, hogy a természetes személyek magánszféráját az adatkezelők tiszteletben tartsák,
valamint a közügyek átláthatósága a közérdekű és a közérdekből nyilvános adatok megismeréséhez és terjesztéséhez
fűződő jog érvényesítésével megvalósuljon.
