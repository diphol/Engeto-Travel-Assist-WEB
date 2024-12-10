# Engeto-Travel-Assist-WEB
Projekt : Responzivní webová stránka
# 1. Vytvoření animace pomocí relativního pozicování v CSS

Relativní pozicování umožňuje posunout prvek relativně k jeho původní pozici. Tento přístup může být využit k vytvoření plynulých animací při interakci s uživateli.

Vaším úkolem je přidat relativní pozicování k obrázkům v rámci třídy .image-item a vytvořit animaci pro stav hover.

## Postup:

1. V souboru `styles.css` najděte třídu `.image-item img`.
2. Této třídě nastavte `position: relative;` aby jsme umožnili relativní pozicování pro obrázky.
3. Přidejte nový blok pro stav hover obrázků: `.image-item img:hover {}`.
4. V rámci bloku `:hover` přidejte vlastnost `top` a nastavte hodnotu na `-12px`.

Tímto krokem vytvoříte animaci posunu obrázku nahoru o 12 pixelů při najetí myši.

Po dokončení těchto kroků byste měli mít funkční animaci, která se spustí při najetí myši na obrázek.
