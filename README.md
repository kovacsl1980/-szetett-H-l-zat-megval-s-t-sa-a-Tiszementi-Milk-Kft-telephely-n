#Öszetett Hálózat megvalósítása a Tiszementi Milk Kft telephelyén
Projektmunka-Hálózati infrastruktúra
Ez a projekt egy összetett, vezetékes és vezeték nélküli hálózati infrastruktúra tervezését és bemutatását ismerteti a Tiszamenti Milk Kft. telephelyére.

A rendszer célja egy stabil, jól áttekinthető és felügyelhető hálózat kialakítása, amely biztosítja a helyi és távoli hálózati területek közötti kommunikációt, az internetkapcsolatot, a hálózati végpontok csatlakozását és az IP-alapú szolgáltatások működését.

---

## 🎯 A projekt célja

- stabil hálózati infrastruktúra kialakítása
- helyi és távoli hálózati területek összekapcsolása
- vezetékes és vezeték nélküli hálózat kialakítása
- központi útválasztás és hálózati forgalom kezelése
- hálózati eszközök és kapcsolatok felügyelete
- IP-kamerarendszer kialakításának lehetősége
- hálózati működés szimulációja és ellenőrzése

---

## 🏗️ A rendszer fő elemei

| Technológia | Feladat |
|---|---|
| **MikroTik RouterOS** | Központi útválasztás és hálózati forgalom kezelése |
| **Ubiquiti PowerBeam M5 400** | 5 GHz-es pont–pont rádiós gerinchálózat |
| **Ubiquiti Rocket M5** | Szektoros vezeték nélküli hálózat |
| **TP-Link Gigabit Switch** | Vezetékes hálózati kapcsolatok |
| **NetXMS** | Monitoring és hibafelügyelet |
| **PoE** | Adat- és tápellátás Ethernet-kábelen |
| **IP-kamerák** | Hálózati videómegfigyelés |
| **Cisco Packet Tracer** | Hálózati szimuláció és működésellenőrzés |

---

## 📡 Hálózati felépítés

A hálózat központi eleme egy MikroTik alapú útválasztás, amelyhez Etherneten keresztül kapcsolódnak a hálózati eszközök.

A távoli hálózati terület összekapcsolását két Ubiquiti PowerBeam M5 400 biztosítja 5 GHz-es pont–pont rádiós kapcsolaton keresztül.

A távoli oldalon további hálózati eszközök és vezeték nélküli kliensek csatlakozhatnak.

Egyszerűsített adatút:

**Internet → MikroTik → Switch → PowerBeam M5 400 → PowerBeam M5 400 → távoli hálózat**

---

## 🧪 Hálózati szimuláció

A projektben Cisco Packet Tracer segítségével készült hálózati szimuláció is.

A szimuláció célja:

- IP-címzés ellenőrzése
- hálózati kapcsolatok vizsgálata
- útválasztás ellenőrzése
- végpontok elérhetőségének tesztelése
- a logikai hálózati topológia szemléltetése

A Packet Tracer a fizikai Ubiquiti rádiós eszközöket nem közvetlenül modellezi, ezért azok funkciói megfelelő hálózati elemekkel kerülnek szemléltetésre.

---

## 📹 PoE és IP-kamerarendszer

A projekt része egy PoE-alapú IP-kamerarendszer lehetőségének bemutatása.

A PoE segítségével az adatkapcsolat és a tápellátás kompatibilis eszközök esetén ugyanazon Ethernet-kábelen keresztül biztosítható.

Előnyei:

- kevesebb kábelezés
- egyszerűbb telepítés
- áttekinthetőbb infrastruktúra
- központi hálózati csatlakozás

---

## 🖥️ Monitoring és üzemeltetés

A hálózat felügyeletére NetXMS monitoring rendszer alkalmazható.

A monitoring segítségével ellenőrizhető többek között:

- hálózati eszközök elérhetősége
- hálózati kapcsolatok állapota
- hibák és kapcsolatkimaradások
- rádiós kapcsolatok működése
- üzemeltetési állapot

---

## 🔧 Hibakeresés

A hibakeresés során célszerű a hálózat felépítését követve, fokozatosan haladni:

**Fizikai kapcsolat → tápellátás → IP-konfiguráció → átjáró → útválasztás → rádiós kapcsolat → távoli végpont**

Ez lehetővé teszi a hiba helyének gyorsabb meghatározását.

---

## 📁 Projektfájlok

### 📄 Dokumentáció
**Hálózati infrastruktúra.pdf**

A projekt részletes műszaki dokumentációja.

### 📊 Projektbemutató
**Projektbemutato_Halozati_infrastruktura_LATVANYOS.pptx**

A projekt prezentációs bemutatója.

---

## 📝 Összegzés

A projekt során egy összetett, vezetékes és vezeték nélküli elemekből felépülő hálózati infrastruktúra került megtervezésre és bemutatásra.

A MikroTik útválasztás, az Ethernet-hálózat, az Ubiquiti PowerBeam és Rocket M5 eszközök, valamint a monitoring rendszer együtt egy olyan infrastruktúrát alkotnak, amely alkalmas a helyi és távoli hálózati területek összekapcsolására és felügyeletére.

A kialakítás lehetőséget biztosít a későbbi bővítésre és további hálózati szolgáltatások bevezetésére is.
