# Generátor plánů jízd – v1

První testovací prototyp generátoru Story grafik pro plánované tramvajové směny a TXT vozové jízdní řády.

## Funkce

- Výhled směn s datem, L/P, časem a označením ZMĚNA.
- Podpora složeného zápisu L/P.
- Import TXT vozáku přímo v prohlížeči.
- Parser ignoruje číslo spoje a pro jednotlivé jízdy používá linku, první a poslední zastávku a jejich časy.
- Interní bloky Depo ↔ Vrata se ve veřejném náhledu filtrují.
- Story náhled 9:16.

## Spuštění

Jde o čisté HTML/CSS/JS bez buildu. Otevři `index.html` nebo složku publikuj jako statický web.

## Stav

V1 prototyp. Zatím chybí export PNG, vícestránkové Story, ruční editace rozpoznaného vozáku a robustnější parser pro další varianty VJR.
