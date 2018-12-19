Beachten:
- Jede Folie in eine Markdown-Datei
- Dateien (Folien) werden ihrer Nummerierung nach angezeigt
- Ordner werden ihrer Nummerierung nach durchlaufen
- In jedem Ordner startet die Nummerierung neu bei 1
- Fehlt eine Nummer, werden nachfolgende Dateien (in dem Ordner) ignoriert

Die erste Folie in jedem Unterordner existiert als Dummy und kann einfach überschrieben werden.

Dateibenennung:
- ``1.md``
- ``2.md``
- ...
- ``n.md``

Nicht funktioniert:
- führenden Nullen
- andere Dateinamen (auch nicht ``3_irgendwas.md``)

Wenn ihr die Präsentation selbst sehen wollt, müsst ihr das Repo auf einen Webserver (z.B. [Apache über XAMPP](https://www.apachefriends.org/de/index.html)) legen.
