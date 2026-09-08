# Általanos információk

## Időbeosztás, mérföldkövek

A félév során csapatban **KELL** dolgozni. Egy csapat 2-3 főből állhat, amitől indokolt esetben felfelé igen, lefelé
semmilyen esetben sem tudunk eltérni. Egy fős csapat nem megengedett. A csapatok összeállítását a második konzultációig lezárjuk.

A csapatok összeállításával párhuzamosan folyik a téma kiválasztása (lásd lentebb).

A csapatoknak 4 konzultáción kell részt venniük a félév során. Ezek az órarend szerinti időpontok közül kerülnek kiválasztásra, a félév során egyenletesen elosztva.

A félév során **dokumentáció** készítése szükséges (lásd lejjebb).

A féléves munkát egy közös, **személyes beszámoló zárja** (úgyszintén lásd lejjebb).

### Csapatok összeállítása

A csapatok összeállítása alapvetően a hallgatók feladata. Ezt egy online táblázat segítségével lehet megtenni,
aminek a linkjét Neptun üzenetben elküldöm.
Értelemszerűen a "csapat sorszáma" oszlopba kell beírni
a csapat sorszámát. A táblázatot később letisztázom és a kimaradó emberekből (ha
lesznek) véletlenszerűen állítok össze csapatokat.

A csapatok összeállítását a **második konzultációig** le fogjuk zárni.
Ezt követően a kimaradó embereket önkényesen fogom csapatokba rendezni.

### GitHub regisztráció és meghívó

A féléves munkához szükség van a GitHub-ra történő regisztrációra is. Az ottani **felhasználónevet** úgyszintén be kell
írni ebbe a táblázatba. A csapatok véglegesítése után mindenkit meghívok az előre elkészített GitHub repositoryba (ehhez
kell tudnom a felhasználónevet). A meghívás után az illető nevét sárgára állítom. A meghívó elfogadását rendszeresen
ellenőrizni fogom és ennek alapán állítom az adott embert zöldre. Ennek a folyamatnak a második konzultációig kell megtörténnie.

### Konzultációk

A kurzushoz az órarendben heti rendszerességű konzultáció van rendelve, azonban csak ebből csak 4 alkalmat tartunk meg.
Ezeket közösen, személyesen tartjuk. A konzultációk helye: C211, ideje 8:00-9:45.

A konzultációk időpontja:
  * 1. konzultáció: **Szeptember 11. 8:00-9:45** (1. hét)
  * 2. konzultáció: **Szeptember 25. 8:00:9:45** (3. hét)
  * 3. konzultáció: **Október 29. 8:00-9:45** (8 hét)
  * 4. konzultáció: **November 26 8:00-9:45** (12. hét)

Az 1. konzultációt főképp az általános tudnivalók ismertetésével és a csapatbeosztással fogjuk tölteni.


A 2. konzultációra a csapatoknak és a választott témáknak véglegesnek
kell lenniük. A témák választható részeit (például hogy a csapat milyen nyelvet, fejlesztőkörnyezetet stb. fog használni) eddigre véglegesíteni kell. A választott fejlesztőeszköz
használatával el kell készíteni egy skeleton projektet, ami az adott eszközökkel egy minimális demó. Ennek a GitHub repositoryban is meg kell jelennie és minden csapattagnak
a kódot (akár minimálisan) érintő változást kell eszközölnie. Ezzel igazolható, hogy a csapat valóban beállította a fejlesztőeszközben a verziókövetést és képes annak alapvető használatára.

A 3. konzultáció célja az évközi időarányos haladás további kontrollja. Ekkorra minden csapatnak be kell mutatnia egy olyan verziót, ami a funkciók egy része meg van valósítva.

A 4. konzultáción az elkészült munkákat mutatják be a csapatok.

### Írásbeli beszámoló

Az írásbeli beszámolót a [szakdolgozat sablonban](https://amk.uni-obuda.hu/wp-content/uploads/2024/09/Szakdolgozat_sablon_2024.docx) kell elkészíteni. Minimális terjedelme 25 oldal. A beadási határidő december 3-a (utolsó előtti oktatási hét csütörtök).

## Témák

Ebben a repositoryban a többi MarkDown fájl a lehetséges választható témák leírását tartalmazza.
Ezek többé-kevésbé
konkrét, kidolgozott feladatok, választható elemekkel. A legtöbb feladat többféle verzióban
(például webalkalmazás, mobil app, vagy PC program) is megvalósítható, de nagyvonalakban specifikálva van.
Saját projekt nem készíthető, illetve az egyszer már lefixált projekttől sem lehet eltérni.

## Verziókövetés

A kurzus egyik célja a Git használatának elsajátítása. Ez azt jelenti, hogy ahelyett,
hogy a csapattagok a kódrészleteket például e-mailben, Messengeren, Discordon stb. osztanák meg
egymással, a változásokat Git használatával követik. Ez egyben azt is jelenti, hogy
a Git repositoryban nem csak a kész, működő verziónak kell szerepelnie, hanem látszani
kell annak is, hogy a félév során mi történik.

A csapatoknak a készülő kód és az egyéb fájlok mellett a dokumentációt is ugyanebben a
GitHub repositoryban kell (verziókövetve) tárolniuk.

### A fejlesztői környezet beállítása a Githez

A fejlesztés első (vagy inkább nulladik) lépése a fejlesztőrendszer beállítása a Githez. A legtöbb
IDE képes a Gittel együttműködni, azonban mindegyiket egy kicsit máshogy kell beállítani. Egy
további lehetőség akár egy grafikus, akár az alap parancssoros Git kliens használata.

Addig senki ne kezdjen hozzá a fejlesztéshez, amíg a Git használata nem megy rutinszerűen.

### README.md

A repositoryban levő README.md fájl a projekt rövid összefoglalója.
Itt szerepelhet például:

 * A csapattagok névsora, Neptun kódja, esetleg elérhetősége
 * A projekt neve, elnevezése
 * A projektről néhány mondat, amiből képet kapunk arról, hogy mit csinál a csapat
 * A felhasznált technológiák, programnyelvek
 * Az előrehaladási napló (nagyobb mérföldkövek; mit csinált a csapat)

A README.md formátuma MarkDown, ami egy egyszerű szövegformázó (markup) nyelv.
Rövid leírás például [itt](https://www.markdownguide.org/basic-syntax/).

**A README.md naprakészen tartása elvárás a kurzus teljesítéséhez.**

### .gitignore

A .gitignore fájl arra való, hogy bizonyos fájlokat automatikusan figyelmen kívül
hagyjunk a verziókövetés során. Ezek például a projekt fordítása során létrejövő,
a forráskódból generált fájlok. Interneten számos példa lelhető fel ezzel kapcsolatban.
Egy kiindulási alap lehet például
[ez a gyűjtemény](https://github.com/github/gitignore).

**A .gitignore fájlnak az adott fejlesztőeszközhöz passzoló kitöltése elvárás
a kurzus teljesítéséhez.**

### Commitok

A változásokat commitok formájában lehet a verziókövetőbe feltölteni. Minden
commithoz szükséges kitölteni a "commit message"-et is. A feltöltéshez
**NE** használjuk a "file upload" funkciót!

A csapatok a félév során **rendszeresen** kell, hogy commitokat készítsenek.
Mivel a "rendszeresen" szónak való megfelelést nehéz definiálni, így
erre nem teszek próbálkozást. Ez a szöveges leírás a projekt specifikációkkal együtt
most 50 feletti kommentnél jár. Egy két hónapos szoftverfejlesztés
ennél kevesebb kommenttel nem tükröz hihető Git-használatot.

