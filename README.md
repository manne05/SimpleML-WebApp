# SimpleML-WebApp
Einfache Machine Learning Web Applikation

Vorhersage / Erkennen von Irisblüten.

Im Frontend akzeptiert die Seitenleiste auf der linken Seite Eingabeparameter,
 die sich auf Merkmale (d.h. Blütenblattlänge, Blütenblattbreite, Kelchblattlänge und Kelchblattbreite) von Irisblüten beziehen. Diese Merkmale werden an das Backend weitergeleitet, wo das trainierte Modell die Klassenbezeichnungen in Abhängigkeit von den Eingabeparametern vorhersagen wird. Die Vorhersageergebnisse werden zur Anzeige an das Front-End zurückgesendet.

Im Back-End werden die Benutzereingabeparameter in einem Datenrahmen gespeichert, der als Testdaten verwendet wird. In der Zwischenzeit wird ein Klassifizierungsmodell unter Verwendung des Random-Forest-Algorithmus aus der Scikit-Lernbibliothek erstellt. SchlieÃŸlich wird das Modell angewandt, um Vorhersagen Ã?ber die Benutzereingabedaten zu machen und die vorhergesagten Klassenbezeichnungen als eine von drei BlÃ?tentypen zurÃ?ckzugeben: Setosa, Versicolor oder Virginica. Zusätzlich wird auch die Vorhersagewahrscheinlichkeit angegeben, die es uns ermöglicht, die relative Zuverlässigkeit der vorhergesagten Klassenbezeichnungen zu erkennen.
