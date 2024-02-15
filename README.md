# Általanos információk

## Csapatok összeállítása

A félév elején a kurzus hallgatóiból 2-3 fős csapatokat állítunk össze. Ennek megszervezése alapvetően a hallgatók feladata. Ezt
[Ennek a táblázatnak](https://docs.google.com/spreadsheets/d/1BPvd-QJT9Fd2HLqn0v-txxHA3oMNaa7M44eLx-d2CMs/edit#gid=0)
a segítségével lehet megtenni. Értelemszerűen a "csapat sorszáma" oszlopba kell beírni
a csapat sorszámát. A táblázatot később letisztázom és a kimaradó emberekből (ha
lesznek) véletlenszerűen állítok össze csapatokat.

## Verziókövetés

A kurzus egyik célja a Git használatának elsajátítása. Ez azt jelenti, hogy ahelyett,
hogy a csapattagok a kódrészleteket például e-mailben, Messengeren stb. osztanák meg
egymással, a változásokat Git használatával követik. Ez egyben azt is jelenti, hogy
a Git repositoryban nem csak a kész, működő verziónak kell szerepelnie, hanem látszani
kell annak is, hogy a félév során mi történik.

A csapatoknak a készülő kód és az egyéb fájlok mellett a dokumentációt is ugyanebben a
GitHub repositoryban kell (verziókövetve) tárolniuk.

Ehhez mindenkinek regisztrálnia kell a GitHubra és a felhasználónevét be kell írnia a
feljebb már említett [táblázatba](https://docs.google.com/spreadsheets/d/1BPvd-QJT9Fd2HLqn0v-txxHA3oMNaa7M44eLx-d2CMs/edit#gid=0). Ha ez megtörtént, a csapattagokat meghívom a megfelelő repositoryba.
A meghívás után a csapattag nevét **sárgára** színezem a táblázatban.

A meghívóról a GitHub e-mail értesítést küld, ahol egy linkre kattintva el is kell azt fogadni.
Ezt rendszeresen ellenőrzöm. Ha minden rendben van, akkor a táblázatban az adott személyt
**zöldre** állítom. Erre a folyamatra egy hét áll rendelkezésre. Aki ennek nem tesz határidőre eleget,
azt szankcionálni fogom.

A repository linkje a következőhöz hasonló lesz:
[https://github.com/OE-AMK-Projektmunka1-2023/PL2023A_20](https://github.com/OE-AMK-Projektmunka1-2023/PL2023A_20)

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

### Könyvtárstruktúra

A repositoryban külön könyvtárban kell elhelyezni a projekt forráskódját (és a
kapcsolódó egyéb fájlokat), a dokumentációt, illetve az egyéb állományokat.
Néhány példa:

 * **src**: A projekthez tartozó forráskódok
 * **firmware**: Az esetleges mikrovezérlős forráskódok
 * **docs**: Dokumentációk
 * **schematics**: Kapcsolási rajzok
 * **screenshots**: Képernyőképek

**A kurzus során elvárás a tiszta könyvtárszerkezet használata.**

### Commitok

A változásokat commitok formájában lehet a verziókövetőbe feltölteni. Minden
commithoz szükséges kitölteni a "commit message"-et is. A feltöltéshez
csak **NE** használjuk a "file upload" funkciót!

A csapatok a félév során **rendszeresen** kell, hogy commitokat készítsenek.
Mivel a "rendszeresen" szónak való megfelelést nehéz utólag elbírálni,
így a következő konkrét mérőszámok az irányadóak. Egy valós fejlesztés
során persze ennél minimum egy nagyságrenddel több commit szokott születni.

**A kurzus során elvárás, hogy legyen legalább 10 olyan hét, amikor ÉRDEMI
változás történik a repositoryban és ezt a commitok dátuma is tükrözi.**

**Szintén elvárás, hogy minden csapattag esetében legyen legalább 3-3 olyan hét,
amikor az adott csapattagnak ÉRDEMI commitja van.**

Érdemi commit lehet akár egy egyeztetésről szóló bejegyzés az előrehaladási
naplóban, vagy akár valamilyen, a projekthez kapcsolódó ötlet, vagy kísérlet nyoma
(fotó, rövid leírás stb) is.

# Témák

A következőkben néhány témajavaslat kerül felsorolásra. Ezek nagyrészt nem
konkrét, minden tekintetben kidolgozott feladatok, hanem inkább ötletek.
A pontos részleteket pontosan emiatt minden esetben egyeztessük.

[Képfeldolgozási algoritmusokon alapuló projekt Webkamerával, vagy Raspberry Pi kamerával](kepfeldolgozas.md)

[Tangram társasjáték számítógépes megvalósítása](tangram.md)

[Játék Arduinoval és OLED kijelzővel](arduino-jatek.md)

[Okos otthon megvalósítása NodeRed segítséglvel](okos-otthon.md)

[WiFi aktivitás mérése Raspberry Pi segítségével](wifi-aktivitas.md)

[Beszélő óra, beszélő konyhai időzítő, beszélő műszer](beszelo.md)

## Tranziens jelek vizsgálata Arduinoval

Egy kontaktus átváltása (például egy kapcsoló, vagy relé ki- vagy bekapcsolása) soha nem
az áramkör egyszeri nyitása, vagy zárása, hanem ezek gyors ismétlése során létrejövő
tranziens folyamat (prellezés). Az egyik lehetséges feladat ennek a jelenségnek a
vizsgálata Arduino segítségével, lehetőleg automatizáltan.

Egy másik tranziens jelenség az izzólámpa be- és kikapcsolása, ahol számunkra
az izzószál áramának / ellenállásának változása az érdekes.

## Numpad-flyer játék



## Accele-pong játék

Az Accele-Pong játék a közismert Ponghoz hasonló, de itt az ütőket a játékosok egy-egy
gyorsulásérzékelő elforgatásával egy kör mentén tudják elhelyezni. A játékhoz egy
irányító már készen van. A játék például PyGame, vagy Unity alatt valósítható meg.
