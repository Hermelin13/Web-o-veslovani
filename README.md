# Web o veslování

Tento malý web je informační stránka o veslování vytvořená jako školní projekt na střední škole (gymnázium).

Web obsahuje základní přehled o veslování, kategorie lodí a slovníček používaných pojmů. Stránky byly vytvořeny pomocí statických HTML souborů a jednoduchého CSS.

## Co je v repozitáři

- `index.html` — hlavní stránka
- `kategorie.html` — přehled kategorií lodí
- `slovnicek.html` — slovníček pojmů souvisejících s veslováním
- `style.css` — společné styly webu
- `IMAGES/` — složka s použitými obrázky (fotografie, ilustrace)

## Jak spustit web lokálně

Nejjednodušší způsob je otevřít `index.html` přímo v prohlížeči (dvojklik). Pokud chcete spustit jednoduchý lokální server (doporučené při testování), můžete použít Python nebo rozšíření Live Server ve VS Code.

Příklad (PowerShell / Windows):

```powershell
# Pokud máte Python 3 dostupný jako 'python'
python -m http.server 8000

# Nebo použijte py launcher, pokud je nainstalovaný
py -3 -m http.server 8000
```

Pak otevřete v prohlížeči adresu http://localhost:8000/ a přejděte na `index.html`.

## Poznámky

- Projekt vznikl během výuky na střední škole jako jednoduchý statický web. Je určen především pro demonstraci základů webového vývoje a prezentaci informací o veslování.
- Pokud chcete aktualizovat obsah nebo přidat vlastní jméno autora, upravte tento soubor nebo historii commitu.
