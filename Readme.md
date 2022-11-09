# Readme

## Anaconda Env

Zur Ausführung des Python Codes, benutze ich ein Anaconda Environment. Die Requirements für das Environment sind in der Datei requirements.txt hinterlegt. Wenn anaconda installiert ist, lässt sich mit dem Befehl <code>conda create --name 'myenv' --file requirements.txt</code>, das Environment starten.

Wenn ein commit gemacht wird, sollte vorher die Requirements file geupdated werden, falls neue Bibliotheken o.ä. installiert wurden. Um die requirements.txt Datei zu aktualisieren kann man einfach den Befehl <code>conda list -e > requirements.txt</code> ausführen.

Wenn wir das Environment aktuell halten, macht es uns das am Ende auch einfacher, den Code auf der VM auszuführen.

## Daten

Die Daten liegen als .zip im Repo. Da sie zu groß sind, können sie nicht unkomprimiert auf dem Repo liegen. Der entzippte Ordner "data", wird nicht versioniert. Bitte den Name nicht ändern, sonst kann man das Repo nicht mehr auf Github hochladen. 
Die Daten sind roh in 2016 und 2017 aufgeteilt und bilden die beiden Jahre komplett ab (mit fehlenden Werten). Die log-Daten sind in dem Papier[1] nicht berücksichtigt, stehen hier aber trotzdem zur Verfügung für zukünftige Implementierungen.

## Datenvorbereitung

Wie im Papier[1], müssen die Daten erstmal grundsätzlich vorbereitet werden. Also bspw. fehlerhafte Sensordaten entfernen und die verschiedenen Datensätze (Sensor- und Mast-Daten) Zeitsynchronisiert zusammenbringen.

in <code>Initial Data Preparation.ipynb</code> wird das umgesetzt werden. Das ist aktuell noch in Arbeit

## Datengetriebene Datenvorbereitung

Notebook noch nicht begonnen.


## Datengetrieben Feature Selection

Notebook noch nicht begonnen.

# Referenzen

[1] <a>https://www.mdpi.com/1996-1073/15/3/826</a>