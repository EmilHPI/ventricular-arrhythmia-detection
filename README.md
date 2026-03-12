# Segmentbasierte Klassifikation von ventrikulären Arrhythmien durch ML
Dieses Repository enthält den entwickelten Code im Rahmen der Bachelorarbeit:
Maschinelles Lernen zur segmentbasierten Klassifikation maligner ventrikulärer Arrhythmien im Kontext implantierbarer Kardioverter-Defibrillatoren.

In diesem Projekt wird untersucht, wie ML auf EKG-Daten angewendet werden kann, um lebensbedrohliche Herzrhythmusstörungen zuverlässig zu erkennen. Es enthält den Code für Preprocessing, Feature-Exraktion, Modell Training und Evaluation.

## Projektstruktur

`notebooks/`
- Enthält den vollständigen Code zur Analyse.

`data/`
- Platzhalter für die Datensätze und Zwischenergebnisse.

## Datensätze

Das Projekt basiert auf zwei öffentlich verfügabaren EKG-Datensätzem:
- MIT-BIH Arrhythmia Database (https://doi.org/10.13026/C2F305)
- MIT-BIH Malignant Ventricular Ectopy Database (https://doi.org/10.13026/C22P44)

Beide Datensätze sind über Physionet verfügbar und wegen der Lizenzen nicht in diesem Repository hochgeladen.

## Wie führt man den Code aus?

1. Repository klonen und eine Python-Umgebung erstellen.
2. Abhängigkeiten installieren ```bash pip install -r requirements.txt ```
3. Die beiden Datensätze manuell von Physionet in `data/raw/` herunterladen.
4. Die Notebooks im Ordner `notebooks/` der Reihe nach ausführen.
5. Die erzeugten Modelle und Abbildungen werden automatisch gespeichert.

## Lizenz

MIT

## Autor

Emil Kobel (Bachelorarbeit - Hasso-Plattner-Institut)
