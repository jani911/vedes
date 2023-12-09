A Tervezési minták: az újrahasználható objektumorientált szoftver elemei (eredeti címén angolul Design Patterns: Elements of Reusable Object-Oriented Software) egy 1994-es szoftverfejlesztési könyv, amelyben programtervezési minták vannak részletesen leírva. A könyvet Erich Gamma, Richard Helm, Ralph Johnson, és John Vlissides írta, a hozzátartozó előszót pedig Grady Booch. A szerzőket szokás Gang of Four (GoF), azaz Négyek bandája néven együtt említeni. 

A Létrehozási minták objektumok létrehozását valósítják meg, miközben javítják abban a rugalmasságot, hogy ki, hol, hogyan és mikor hozzon létre objektumokat.

    Absztrakt gyár programtervezési minta egységbe zárja a közös témához kapcsolódó egyedi gyártó metódusok egy csoportját.
    Építő programtervezési minta minden egyes inicializációs paramétert lépésről lépésre kap meg, majd egyben adja vissza az elkészült objektumot.
    Gyártó metódus programtervezési minta úgy hoz létre objektumot, hogy nem specifikálja a konkrét osztályát.
    Prototípus programtervezési minta úgy hoz létre objektumot, hogy egy már létező másik objektumot klónoz le.
    Egyke programtervezési minta egy objektumra korlátozza egy osztály létrehozható példányainak számát.

Szerkezeti

Ezek az osztályok és objektumok elrendezésével kapcsolatosak, Öröklődést használnak, hogy összeállítsák az interfészeket és, hogy meghatározzanak különböző módokat az objektumok összetételére, hogy hogy adhatunk hozzájuk új funkcionalitást.

    Illesztő programtervezési minta lehetővé teszi olyan osztályok együttműködését, amelyek az inkompatibilis interfészeik miatt normálisan nem tudnának együttműködni.
    Híd programtervezési minta külön választjuk az absztrakciót az implementációjától, azért hogy a kettőt függetlenül lehessen variálni.
    Összetétel programtervezési minta lehetővé teszi, hogy a kliensek az önálló objektumokat és összetételeket egységes módon kezeljék.
    Díszítő programtervezési minta lehetővé teszi adott objektumokhoz más viselkedések hozzáadását akár statikusan, akár dinamikusan anélkül, hogy hatással lenne az azonos osztályból származó többi objektumra.
    Homlokzat programtervezési minta egy leegyszerűsített interfészt biztosít nagyobb kódrészekhez.
    Pehelysúlyú programtervezési minta lecsökkenti a nagyobb mennyiségű, hasonló objektum létrehozásának és módosításának költségét.
    Helyettes programtervezési minta helyettesítőt biztosít egy másik objektumhoz, a költség csökkentésére, a komplexitás csökkentésére stb.
