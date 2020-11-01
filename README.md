Kedves Mentorok!

Mindenekelőtt elnézéseteket kérem, hogy a feladatban a tartalom és a stílus kialakításig nem jutottam el.
Igyekeztem a formai követelményeket tudásom szerint teljesíteni.

# Feladatmegoldások:
Minden oldalon elkészítettem a header, nav, main, section, footer elemeket a szemantikus weblap tervezésnek megfelelően.
A helyileg mentett file-okat rendszeresen szinkronizáltam a github "petert360/project-html-001-about-site" repository-val.
Az oldal tetejére címet helyeztem, ez alá a navigációs sort, a HOME-WORKS-GALLERY-ABOUT linkekkel.
A navigációs sor kialakítását a https://www.w3schools.com/css/css_navbar.asp oldal segítségével készítettem el.
A láblécnek a navigációs sornak megfelelő stílust adtam, a keretes szerkezet érdekében.

1. Home:
    1. A rövid bemutatkozást Lorem ipsum helyettesíti
    2. A két képnek alakítottam ki helyet a bemutatkozás alatt, a galériában alkalmazott módszerrel tettem reszponzívvá.
    3. A három boxot egy "containerben" elhelyezett 3 "box" divvel alkítottam ki. A container flex, a benne lévő diveket agymás mellé a "justify-content: space-evenly;" segítségével helyeztem
    4. A footerben lévő link az oldal tetején lévő elemre mutat, így valósítva meg az oldal tetejére ugrást.

2. Works: 
    1. A 3 projek bemutatására vonatkozó helyket divek segítségeével oldottam meg:
    a container divben egy div a képnek egy pedig a mellette lévő szövegnek készült. Azért bontottam a képet és a szöveget két divre, mert így a képet és a szöveg egymás mellé vagy alá tudom helyezni a képszélességtől függően a szöveg pedig mindig függölegesen tagolódik.

3. Gallery: 
    1. A https://www.w3schools.com/css/css_image_gallery.asp alapján építettem fel a galéria oldalt.
    A css-ben az ide vonatkozó ".clearfix:after" és a "*" megoldásokat nem látom át teljesen, de nélkülük az oldal nem őrizné meg a formát, és saját megoldást egyelőre nem találtam.
    2. A képek körül halvány árnyék van: box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
    3. Mobil nézet esetén egymás alá kerülnek a képek, 600px felett 3 van egy sorban.

4. About
    1. A nav alatt egy kép helye van a bemutatandó személyről.
    2. A tulajdonságok felsorolásában rendezett és rendezetlen listák is vannak
    3. Az űrlap validálásokat csak HTML szinten oldaottam meg
        név min. 5 karakter: minlength="5" required
        email @-et taralmató szöveg: type="email" required
        üzenet min. 20 karakter: minlength="5" required

Üdvözlettel,

Benke Péter