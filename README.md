<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internetes Kommunikációs Protokollok</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background-color: #004466;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        section {
            padding: 1rem 2rem;
        }
        h2 {
            color: #004466;
        }
        .protocol {
            margin: 1rem 0;
            padding: 1rem;
            background-color: #f2f2f2;
            border-radius: 5px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <h1>Internetes Kommunikációs Protokollok</h1>
    <p>Az internet működéséhez szükséges alapvető kommunikációs protokollok és azok szerepe</p>
</header>

<section>
    <h2>Protokollok és Szerepük</h2>
    <p>Az internetes kommunikáció a különböző rétegeken keresztül valósul meg, ahol minden réteg saját szabályrendszerrel (protokollal) rendelkezik. Itt megvizsgáljuk az egyes protokollokat, és hogy mely rétegben működnek.</p>

    <!-- OSI modell ábra -->
    <div class="protocol">
        <h3>Az OSI Modell</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/OSI_mod_2.png/300px-OSI_mod_2.png" alt="OSI Modell Ábra">
        <p>Az OSI (Open Systems Interconnection) modell hét rétegre osztja a hálózati kommunikációt, amely segíti a különböző hálózati elemek közötti kommunikációt.</p>
    </div>

    <!-- TCP/IP modell ábra -->
    <div class="protocol">
        <h3>A TCP/IP Modell</h3>
        <img src="https://www.szabilinux.hu/konya/konyv/8fejezet/Image281.gif" alt="TCP/IP Modell Ábra">
        <p>A TCP/IP modell egyszerűbb megközelítést alkalmaz, ahol négy réteget különböztetünk meg. Ez a modell az internet működésének alapja.</p>
    </div>

    <!-- Protokollok -->
    <div class="protocol">
        <h3>HTTP (Hypertext Transfer Protocol)</h3>
        <p><strong>Száma:</strong> N/A</p>
        <p><strong>Feladata:</strong> A weboldalak letöltéséért felelős protokoll. A kliens-szerver kommunikáció során a kliens kérésére a szerver válaszol.</p>
        <p><strong>Réteg:</strong> Alkalmazási réteg</p>
    </div>

    <div class="protocol">
        <h3>FTP (File Transfer Protocol)</h3>
        <p><strong>Száma:</strong> N/A</p>
        <p><strong>Feladata:</strong> Fájlok átvitele szerver és kliens között. Gyakran használják nagy méretű fájlok átvitelére.</p>
        <p><strong>Réteg:</strong> Alkalmazási réteg</p>
    </div>

    <div class="protocol">
        <h3>TCP (Transmission Control Protocol)</h3>
        <p><strong>Száma:</strong> N/A</p>
        <p><strong>Feladata:</strong> Megbízható, kapcsolat-orientált adatátvitel biztosítása. Az adatok csomagokra bontása és sorrendbe állítása.</p>
        <p><strong>Réteg:</strong> Szállítási réteg</p>
    </div>

    <div class="protocol">
        <h3>UDP (User Datagram Protocol)</h3>
        <p><strong>Száma:</strong> N/A</p>
        <p><strong>Feladata:</strong> Gyors, de nem megbízható adatátvitel. Nincs kapcsolat, a csomagok nem biztos, hogy sorrendben érkeznek.</p>
        <p><strong>Réteg:</strong> Szállítási réteg</p>
    </div>

    <div class="protocol">
        <h3>IP (Internet Protocol)</h3>
        <p><strong>Száma:</strong> IPv4 (RFC 791), IPv6 (RFC 8200)</p>
        <p><strong>Feladata:</strong> Az adatok címzése és útválasztása a hálózaton keresztül. Az IP címek segítségével biztosítja az eszközök azonosítását.</p>
        <p><strong>Réteg:</strong> Hálózati réteg</p>
    </div>

    <div class="protocol">
        <h3>IEEE 802.11 (Wi-Fi)</h3>
        <p><strong>Száma:</strong> IEEE 802.11a/b/g/n/ac</p>
        <p><strong>Feladata:</strong> Vezeték nélküli hálózatok (Wi-Fi) adatátviteli szabványa, amely biztosítja az eszközök közötti kommunikációt a fizikai és adatkapcsolati rétegen.</p>
        <p><strong>Réteg:</strong> Fizikai és Adatkapcsolati réteg</p>
    </div>

    <div class="protocol">
        <h3>RIP (Routing Information Protocol)</h3>
        <p><strong>Száma:</strong> RFC 1058</p>
        <p><strong>Feladata:</strong> Egy egyszerű útválasztási protokoll, amely az útvonalak távolságát és a hálózat elérhetőségét kommunikálja más útválasztók között.</p>
        <p><strong>Réteg:</strong> Hálózati réteg</p>
    </div>

    <div class="protocol">
        <h3>DNS (Domain Name System)</h3>
        <p><strong>Száma:</strong> N/A</p>
        <p><strong>Feladata:</strong> A domain nevek IP címekké való átalakítása, hogy a felhasználók könnyebben elérhessék az internetes erőforrásokat.</p>
        <p><strong>Réteg:</strong> Alkalmazási réteg</p>
    </div>

</section>

</body>
</html>
