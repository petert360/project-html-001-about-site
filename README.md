# Feladatmegoldások

Kedves Mentorok!

Mindenekelőtt elnézéseteket kérem, hogy a feladatban a tartalom és a stílus kialakításig nem jutottam el.
Igyekeztem a formai követelményeket tudásom szerint teljesíteni.

* Minden oldalon elkészítettem a header, nav, main, section, footer elemeket a szemantikus weblap tervezésnek megfelelően.
* A helyileg mentett file-okat rendszeresen szinkronizáltam a github "petert360/project-html-001-about-site" repository-val. Az oldal tetejére címet helyeztem, ez alá a navigációs sort, a HOME-WORKS-GALLERY-ABOUT linkekkel.
* A navigációs sor kialakítását a https://www.w3schools.com/css/css_navbar.asp oldal segítségével valósítottam meg.
* A láblécnek a navigációs sornak megfelelő stílust adtam, a keretes szerkezet érdekében.

1. Home:
    * A rövid bemutatkozást "lorem ipsum" helyettesíti.
    * Két képnek alakítottam ki helyet a bemutatkozás alatt, a galériában alkalmazott módszerrel tettem reszponzívvá.
    * A három boxot egy "containerben" elhelyezett 3 "box" divvel alkítottam ki. A container flex, a benne lévő diveket egymás mellé a __justify-content: space-evenly;__ segítségével helyeztem el.
    * A footerben lévő link az oldal tetején lévő elemre mutat, így valósítva meg az oldal tetejére ugrást.

2. Works: 
    * A 3 projekt bemutatására vonatkozó helyeket divek segítségével alakítottam ki.
    * A container divben egy div a képnek, egy pedig a mellette lévő szövegnek készült. Azért bontottam a képet és a szöveget két divre, mert így a képet és a szöveg egymás mellé vagy alá tudom helyezni a képszélességtől függően a szöveg függőleges tagolása mellett.

3. Gallery: 
    * A https://www.w3schools.com/css/css_image_gallery.asp alapján építettem fel a galéria oldalt.
    * A css-ben az ide vonatkozó __.clearfix:after{}__ és a __*{}__ megoldásokat nem látom át teljesen, de nélkülük az oldal nem őrizné meg a formát, és saját megoldást egyelőre nem találtam.
    * A képek körül halvány árnyék van: __box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);__
    * Mobil nézet esetén egymás alá kerülnek a képek, 600px felett 3 van egy sorban.

4. About
    * A nav alatt egy kép helyét alakítottam ki.
    * A tulajdonságok felsorolásában OL és UL elemeket is használtam.
    * Az űrlap validálásokat csak HTML szinten oldaottam meg:
        * név min. 5 karakter: __minlength="5" required__
        * email @-et taralmató szöveg: __type="email" required__
        * üzenet min. 20 karakter: __minlength="5" required__

Üdvözlettel,

Benke Péter