# Jitsi Test (Angular)

![US](https://www.stevenskelton.ca/flag-icon/png/36/country-4x3/us.png)

**A web application written in Angular framework that implements the basic functionality of the open source video conferencing API called Jitsi**

Starting project
-

Set the repository's root directory as the base.
Before starting the project for the first time, the following command must be run:

`npm install`

The project can be started from Visual Studio Code, under the Run and Debug menu item, or from the terminal with the following command:

`npm run start`

It can then be opened manually from `http://localhost:4200`.

In order for the microphone and camera to be detected in the browser, their use must be enabled on the given page at first launch.

Other information
-

I was done with the project in 3 hours. I dragged the API into the project from an external script and started it in the `app.component.ts` file. I didn't log in in any way, I just wanted to create the basic functionality in the start window of the meeting. Below the meeting interface, I have written some data in tables (at startup or by pressing buttons), which can already be requested via the API in this state.

---

![HU](https://www.stevenskelton.ca/flag-icon/png/36/country-4x3/hu.png)

**Angular frameworkben írt webalkalmazás, amely a Jitsi nevű, nyílt forráskódú videókonferencia API alapvető működését implementálja**

Projekt elindítása
-

A repo gyökérmappája legyen a projekt alapja.
A projekt első indítása előtt futtatni kell az alábbi parancsot:

`npm install`

A projekt indítható Visual Studio Code-ból, Run and Debug menüpont alól, vagy terminálból az alábbi paranccsal:

`npm run start`

Utána megnyitható manuálisan a `http://localhost:4200` címről.

A böngészőben a mikrofon és kamera észleléséhez első indításkor engedélyezni kell azok használatát az adott lapon.

Egyéb tudnivalók
-

A projekttel kb. 3 óra alatt készültem el. External scriptről behúztam a projektbe az API-t, és elindítottam az `app.component.ts` fájlban. Nem jelentkeztem be semmilyen módon, csak a meeting indulási ablakában lévő működést szerettem volna elérni. A meeting felület alá táblázatokba kiírtam néhány adatot (indításkor vagy gombok megnyomásával), amik már ebben az állapotban lekérhetőek az API-n keresztül.
