# Colors of Finance 2025 - Správce programu

Aplikace pro zpřehlednění a organizaci programu konference Colors of Finance 2025.

## Funkce

- 📋 **Načtení programu** - Vložte program ve formátu `ČAS | NÁZEV | ŘEČNÍK | POPIS`
- 🎨 **Barevné označování** - Označte si položky podle vašeho zájmu:
  - 🟢 Zelená - Zajímá mě (priorita)
  - 🟠 Oranžová - Možná (sekundární zájem)
  - 🔴 Červená - Nezajímá mě
  - ⚪ Šedá - Neoznačeno
- 🤖 **Automatické označování** - Automaticky označí položky podle klíčových slov (IT, AI, LinkedIn, Úvodní seminář)
- 🔍 **Filtrování** - Zobrazte pouze položky podle kategorií
- 📊 **Statistiky** - Přehled označených položek
- 📥 **Export** - Stáhněte si označený program do textového souboru
- 💾 **Uložení** - Automatické ukládání do prohlížeče (localStorage)

## Jak použít

1. Otevřete soubor `colors-of-finance-program.html` v prohlížeči
2. Vložte program konference nebo klikněte na "Načíst ukázkový program"
3. Klikněte na "Načíst program"
4. Klikněte na "Automaticky označit podle preferencí" pro automatické označení
5. Klikněte na jednotlivé položky pro změnu jejich označení
6. Použijte filtry pro zobrazení konkrétních kategorií
7. Exportujte si finální program pomocí tlačítka "Exportovat program"

## Formát vstupu

Každý řádek = jedna položka programu:
```
ČAS | NÁZEV | ŘEČNÍK | POPIS
```

Minimálně potřebujete: `ČAS | NÁZEV`

## Automatické rozpoznávání témat

Aplikace automaticky rozpoznává a označuje tagy pro témata jako:
- IT, AI, LinkedIn
- Investice, Kryptoměny
- Marketing, Finance
- Bezpečnost, Cloud, Data

## Technologie

- HTML5
- CSS3
- JavaScript (ES6+)
- LocalStorage pro ukládání dat

## Autor

Vytvořeno pro Colors of Finance 2025

