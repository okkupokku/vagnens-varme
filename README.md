# Vagnens värme

Prototyp för att hålla en vagn eller stuga frostfri och värma när elen är billig.

- Hämtar riktiga finska elpriser per kvart från [spot-hinta.fi](https://spot-hinta.fi).
- Räknar totalpris: börspris + elbolagets marginal + överföring + elskatt.
- Hämtar väderprognos från [Open-Meteo](https://open-meteo.com).
- Planerar uppvärmningen så att vagnen hålls över nödgränsen till lägsta möjliga kostnad.

Vagnen är än så länge **simulerad**. Nästa steg är att koppla in en Shelly-stickpropp och en temperaturgivare.

Hela sidan finns i `index.html` och behöver ingen server. Öppna den i webbläsaren eller lägg ut den med GitHub Pages.
