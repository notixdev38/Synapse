# Synapse Framework

Synapse ist ein modulares Automatisierungs- und Integrationsframework zur
Orchestrierung von Authentifizierung, Netzwerkkommunikation, Konfigurations-
management und geplanten Hintergrundprozessen.

Die Anwendung wurde für stabile und reproduzierbare Ausführung in produktiven
Umgebungen entwickelt und wird als eigenständige Windows-Applikation
bereitgestellt.

Synapse kombiniert mehrere interne Module wie OAuth-Handling, Task-Scheduling,
Netzwerkzugriffe und Logging in einer einzigen Laufzeitumgebung.

Dadurch können komplexe Prozesse automatisiert, überwacht und zentral gesteuert
werden.

---

## ⚠ WICHTIG – START DER ANWENDUNG

## **DIE ANWENDUNG MUSS ÜBER „Synapse.exe“ GESTARTET WERDEN**
## **NICHT ÜBER PYTHON ODER .PY DATEIEN**

Die bereitgestellte EXE-Datei ist der offizielle und unterstützte Startweg.

Start:



Die Python-Dateien sind interne Framework-Komponenten und **nicht**
zur direkten Ausführung vorgesehen.

Ein direkter Start von `.py` Dateien kann zu Fehlern oder unvollständiger
Initialisierung führen.

---

## Warum Synapse.exe verwenden?

Die EXE enthält:

- integrierte Python Runtime
- alle Abhängigkeiten
- vorkompilierte Module
- feste Versionsstände
- optimierte Startkonfiguration

Vorteile:

- keine Python Installation erforderlich
- keine pip Abhängigkeiten nötig
- keine Versionskonflikte
- sofort einsatzbereit
- identisches Verhalten auf jedem System
- geeignet für Deployment und Produktivbetrieb

Die Nutzung der EXE stellt sicher, dass alle Komponenten korrekt geladen werden.

---

## Schnellstart

### 1. Dateien entpacken
Projektordner entpacken oder kopieren.

### 2. Konfiguration prüfen
Folgende Dateien anpassen:

- config.json
- OAuth.json
- .env (optional)



Fertig.  
Synapse initialisiert automatisch alle Module und startet die Dienste.

---

## Konfiguration

### config.json

Beinhaltet allgemeine Systemeinstellungen:

Beispiele:

- Betriebsmodus (development / production)
- Logging Optionen
- Retry Limits
- Zeitüberschreitungen
- Thread Limits

Beispiel:

```json
{
  "mode": "production",
  "logging": true,
  "retry_limit": 5



### 3. Anwendung starten


![image alt](https://github.com/notixdev38/Synapse/blob/5f327a3c7376acf8537bde56b57c0316578e97e9/Bild_2026-02-09_131048484.png)

