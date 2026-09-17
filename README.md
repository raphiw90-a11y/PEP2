# Fleetly – Personalbedarfsplanung

Lokale, responsive Webapp zur kurz- und langfristigen Planung von Fahrern und Fahrzeugen pro Filiale.

## Start

```bash
python3 -m http.server 8000
```

Danach `http://localhost:8000` öffnen. Es werden keine Build-Schritte oder Backend-Dienste benötigt.

## Modell

Der Fahrerbedarf wird aus Forecast, Paketen pro Stunde, Tourstunden sowie Ferien- und Absenzquote berechnet. Der Fahrzeugbedarf basiert auf Paketen pro Fahrzeug. Werte können in der Tagesplanung direkt verändert werden; sämtliche Ergebnisse werden sofort neu berechnet. Der CSV-Export stellt die aktuelle Planung zur weiteren Bearbeitung bereit.
