# Factory Rally Lastenheft

Lastenheft der Projektidee samt organisatorischer Anmerkungen


## Latex übersetzen

Das Template (siehe Quellen) verwendet `biber` für die Literaturangaben und `makeindex` für die Indizierung. Zum Übersetzen sollten die folgenden Befehle verwendet werden:

1. `pdflatex main`
2. `makeindex main.idx -s StyleInd.ist`
3. `biber main`
4. `pdflatex main`
5. `pdflatex main`


# Quellen und weiterführende Links

* Latex Layout basiert auf dem [modified Legrand Orange Book Template](https://www.latextemplates.com/template/the-legrand-orange-book).


# Lizenz

![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png)
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/)



