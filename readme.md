Hier ist der Code für die Übung der KSS-Vorlesung 2020 zu finden. 
Die Web App die mit dem hier erzeugten Modell funktioniert lässt sich unter folgendem Link aufrufen und funktioniert auf Android-Geräten:
https://pi2gm.csb.app/
Aufgezeichnet wurden die Daten mit folgender Web App:
https://mbli7.csb.app/

Ziel der Applikation ist es zu erkennen, ob das Gerät fällt oder in normaler Benutzung ist. Sobald das Gerät fällt wird dies als farbliches Signal auf dem Bildschirm angezeigt.
Um das Modell zu trainieren wurden eigene Aufzeichnungen erstellt und mit *falling* bzw *other* gelabeled. Diese Daten wurde verwendet um verschiedene Modelle zu trainieren und zu evaluieren.
Das fertige Modell wurde mit der Hilfe des sklearn-porters für Java-Script exportiert und in die Web App eingebunden.

-  `/Notebooks`: Notebook welches alle Verarbeitungsschritte enthält.
- `/Model`: Das exportierte js Model.
- `/Plots`: Interaktive Plots zur Datenexploration.
