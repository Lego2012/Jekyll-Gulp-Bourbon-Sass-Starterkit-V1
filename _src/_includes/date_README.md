Deutsches Datum / Monatsnamen mit Jekyll
========================================
Quelle: [Jekyll Blog](http://jekyllblog.de/2015/02/09/deutsches-datum-monatsnamen-mit-jekyll/)

## Für Hauptseite `index.html und Archiv:

Im `_includes` Ordner gibt es zwei neue HTML-Dateien: `date.html` und `date_post.html`.
Nun einfach an den Stellen wo z.B. in `ìndex.html` ein Datum auftaucht, den Schnipsel `{{ post.date | date_to_string }}` mit `{% include date.html %}` ersetzen.

Jetzt wird an der gleichen Stelle stets ein deutsches Datumsformat (Tag. Monat Jahr) angezeigt.
