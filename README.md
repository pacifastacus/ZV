# A kidolgozott záróvizsga tételsor
Záróvizsga tételsor a Debreceni Egyetem mérnökinformatikus hallgatói számára

# Hogy Szerkeszd ezt a doksit
Ha csak a dokumentum kinézetén szeretnél állítani, akkor módosítsd a `kidolgozott_tételsor.tex` fájlt. Ebben a főállományban módosíthatod:
  * Papírméret `\def\PAPER{<TYPE>}`
  * betűméret `\def\FONTSIZE{<SIZE>}`, pt-ben megadva
  * globális térköz `\setlength{\parskip}{<X>pt plus <Y>pt minus <Z>pt}`, `X` a térköz mérete, `Y,Z` a térközölés rugalmassága
  * Tárgymutató mélysége `\setcounter{tocdepth}{<SZÁM>}`, `SZÁM` minél nagyobb, annál részletesebb tárgymutatót kapsz
  * Fejezeteket törölhetsz és adhatsz hozzá (Hogy kezelhető legyen, célszerű, az új fejezetet külön fájlban szerkeszteni)
  
Az egyes Egyes fejezetek az *altalanos*, *halozatok*, *meres* és *vir* almappákban vannak, a különböző szak-specializácók szerint. a *tex* mappában speciális tex fájlok vannak. Az almappákban van egy-egy `pelda.tex` sablon fájl, ami alapján el lehet kezdeni szerkeszteni a fejezeteket.

A preambulumot a `tex/preamble.tex` fájlban találod. Nincs kommentelve, így nem hozzáértő embernek a szerkesztését nem ajánlom. Direkt ezért lett elszeparálva a főfájltól.

Mindenki aki módosítani akarja a repó fájljait kezdjen új branchbe
