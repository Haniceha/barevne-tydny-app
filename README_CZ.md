# Barevné týdny – webová aplikace pro iPhone

## Funkce
- Pravidlo pro liché týdny a samostatné pravidlo pro sudé týdny.
- Černá, hnědá, modrá a žlutá; lze vybrat jednu až čtyři barvy.
- Výjimky pro konkrétní týdny 1–53, které mají přednost před sudým/lichým pravidlem.
- Přehled aktuálního týdne a uložených výjimek.
- Nastavení se ukládá lokálně v zařízení; soubory podporují přidání na plochu a offline cache.

## Jak ji zprovoznit pouze z iPhonu pomocí GitHub Pages
1. Safari: otevři https://github.com/ a přihlas se nebo si vytvoř účet.
2. Vytvoř nové úložiště (repository) s názvem `barevne-tydny`, nastav ho jako **Public** a potvrď Create repository.
3. V úložišti stiskni **Add file → Upload files**. Nahraj všechny soubory z tohoto ZIPu: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`. Na iPhonu je nejprve ulož do aplikace Soubory a ZIP rozbal přes Soubory.
4. Dole potvrď **Commit changes**.
5. V repozitáři otevři **Settings → Pages**. V části Build and deployment vyber **Deploy from a branch**, branch `main`, folder `/(root)`, potom **Save**.
6. Počkej, až GitHub Pages zveřejní web. Adresa bude obvykle `https://TVUJ-UCET.github.io/barevne-tydny/`. Přesnou adresu uvidíš v Settings → Pages. Než ji otevřeš, ověř, že stránka je zveřejněná.
7. Na iPhonu otevři tuto adresu v Safari. Klepni na Sdílet → **Přidat na plochu**. Pokud je dostupná volba **Otevřít jako webovou aplikaci**, nech ji zapnutou a klepni na Přidat.

## Poznámka
Jde o webovou aplikaci na ploše, ne o nativní iOS widget, který se přidává přes tlačítko + v galerii widgetů. Uložené nastavení je lokální pro danou instalaci/prohlížeč; při smazání dat webové aplikace se může vymazat.
