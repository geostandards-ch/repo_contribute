# inoffizielle Zusatzmodelle

## Zweck
INTERLIS Model Repository für Datenmodelle, welche für die Nutzung in einem Software-Werkzeug verwendet werden können und allgemeingültig sind.
Das aktive Model Repository ist unter http://models.ilitools.ch verfügbar.

## Anwendung

```shell
# Indexdatei erstellen
java -jar ilimanager.jar --createIliModels --repos . --out ilimodels.xml
```

```shell
# Model Repository lokal prüfen
java -jar ili2c.jar --check-repo-ilis .
```

```shell
# Model Repository online prüfen
java -jar ili2c.jar --check-repo-ilis http://models.ilitools.ch
```