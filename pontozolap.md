# Pontozólap

Név: Nádudvari Boglárka
Neptun kód: CQRUIW


# Projekt rövid leírása
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/solution.png?raw=true)
A solution-ben két projekt található. Egy webapplikáció (ASP.NET Core Web API) és egy Windows Forms App. Mindkettő projekt egy adatbázist használ. Funkciója, hogy rendezvényeket lehet vele kezelni. Lehet törölni, szűrni, hozzáadni, módosítani.

(Valamiért az órán elkészített Cherry solution-t nem tudom az otthoni számítógépemről futtatni, ezért az otthon elkészített másolatából rakom be a képernyőfelvételek nagy részét)

## Hozott anyagok

**Saját adatbázis**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/ab_constraint1.png?raw=true)

![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/ab_constraint2.png?raw=true)
3x1p Az alkalmazásban használt táblánként pont
1x1p Az adatbázis tartalmaz Constraint-eket (min 2)
1x1p Az adatbázis adatainak forrásmegjelölése értsd: miből készült és hogyan
1x2p Az adatbázis saját Azure SQL szerveren van

Az Azure Portalon létrehoztam az SQL adatbázist, majd Azure Data Studio-ban létrehoztam a három táblát. Az Events-et, ez a tábla tartalmazza a rendezvényeket, a nevet, a dátumot és a helyszínt. Az Attendees-t, ez tartalmazza a résztvevők adatait, teljes név, email cím és telefonszám. Az utolsó, pedig a Locations tábla, amiben a helyszínek adatai vannak, a neve, címe, város, férőhely és, hogy beltéri-e.

Részösszeg: 7p

**Weboldal**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/style.png?raw=true)
1x1p A weboldalnak van egy értelmezhető struktúrája
1x1p A weboldal dinamikus tartalommal tölthető fel adatbázison keresztül
1x1p A weboldal használ legalább 20 sor értelmes css-t
1x1p A weboldal javascriptet használ API végpont által szolgáltatott adatok betöltésére, hozott anyagként
1x1p A weboldal javascriptje más funkciót is ellát, mint az adatok betöltése

Részösszeg: 5p Eddig: 12p

## Egyéb, extra

1p Scaffold-DbContext használata

Részösszeg: 1p Eddig: 13p

## Windows Forms Application
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/form1.png?raw=true)

**User Interface**
1x2p Az alkalmazásból a kilépés csak megerősítő kérdés után lehetséges.

Részösszeg: 2p Eddig: 15p

**Tábla adatainak megjelenítése ListBox-ban.**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/listszur.png?raw=true)
1x2p Adatok megjelenítése
1x2p Ha az adatok tetszőleges módszerrel, pl. TextBox-on keresztül szűrhetőek.

Részösszeg: 4p Eddig: 19p

**Tábla adatainak megjelenítése DataGridView-ban**
1x2p Adatok megjelenítése

Részösszeg: 2p Eddig: 21p

 **Adatkötés  BindingSource-on keresztül**
 1x2p Működő BindingSource

Részösszeg: 2p Eddig: 23p

**Új rekord rögzítése**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/ujesemeny.png?raw=true)
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/hibakez.png?raw=true)
1x2p Ha csak az idegen kulcsok vannak felvéve
1x1p Ha legalább egy nem kulcs mező, pl. Mennyiség is fel van véve
1x2p Ellenőrzéshez kötött adatfelvitel (egyszerű validáció pl: String.IsNullOrEmpty())
1x2p Felugró ablakon keresztül történik Ok és Mégse gombbal

Részösszeg:  7p Eddig: 30p

**Rekord törlése**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/torles.png?raw=true)
1x2p Sikeres törlés
1x2p Megerősítéshez kötött törlés

Részösszeg: 4p Eddig: 34p

## ASP .NET
1x2p program.cs beállítása wwwroot mappában tárolt statikus tartalmak megosztására

Részösszeg: 2p Eddig: 36p

**API végpontok**
![enter image description here](https://github.com/boginadudvari/projektzhmedia/blob/main/api_vegpont.png?raw=true)
1x3p Teljes SQL tábla adatainak szolgáltatása API végponton keresztül
1x2p SQL tábla egy választható rekordjának szolgáltatása API végponton keresztül
1x3p SQL tábla egy választható rekordjának törlése
1x5p Új rekord felvétele HttpPost metóduson keresztül SQL táblába
1x3p Rekord módosítása HttpPut metóduson keresztül SQL táblában

Részösszeg: 16p Eddig: 52p
