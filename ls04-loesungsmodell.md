# LS4 – Vom Problem zur Lösung

| Phase | Deutsch +Original          | Bedeutung in der IT                                                                          | Beispiel (Login-Formular)                                                        |
| :---- | :------------------------- | :------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| **E** | **E**ingabe (Input)        | **Eingabedaten / Problem**. Zu verarbeitende Informationen.                                  | Der Benutzer gibt seinen Login-Namen und sein Passwort ein.                      |
| **V** | **V**erarbeitung (Process) | **Verarbeitung / Lösungsalgorithmus**. Das Programm analysiert die Daten nach klaren Regeln. | Der Server überprüft, ob das Passwort in der Datenbank vorhanden ist.            |
| **A** | **A**usgabe (Output)       | **Ausgabedaten / Lösung**. Das Endergebnis der Arbeit des Algorithmus.                       | Der Bildschirm für den erfolgreichen Login ODER die Meldung „Falsches Passwort“. |

| Konzept     | Beschreibung                                                                 |
| :---------- | :--------------------------------------------------------------------------- |
| **Problem** | Die Person möchte nicht jedes Mal manuell Passwörter für Accounts erstellen. |
| **Idee**    | Die Person möchte diesen Prozess automatisieren.                             |
| **Lösung**  | Ein Skript erstellen, das den Prozess selbstständig ausführt.                |

 ### Entwicklungs-Workflow (Code-Schema)

```
┌── [1] ⚠️**Marktanalyse & Recherche**
│      ├── Falls JA  ─────────────► ⚠️Nach offizieller Anleitung installieren und nutzen
│      └── Falls NEIN ───────────► 🤖Mit Schritt 2 fortfahren
│
├── [2] 🤖**Vorbereitung der Umgebung**
│      └── Die integrierte Entwicklungsumgebung *(IDE)* öffnen
│
├── [3] **Implementierung (Code schreiben)**
│      ├── 3.1 ⚠️Abhängigkeiten definieren
│      │   ├── Vorhanden ────────► 🤖Im Code importieren *(einbinden*)
│      │   └── Nicht vorhanden ───► 🤖Schritt überspringen
│      ├── 3.2 ⚠️Zeichensatz festlegen *(Sonderzeichen, Zahlen, Buchstaben)*
│      ├── 3.3 🤖Logik entwickeln *(Funktion zur Zufallsauswahl schreiben)*
│      └── 3.4 🤖Funktion aufrufen *(Main-Logik implementieren)*
│
├── [4] 🤖**Deployment & Speichern**
│      └── Den geschriebenen Quellcode sichern und die Datei speichern
│
└── [5] **Testing & Qualitätssicherung**
    ├── ⚠️Fehler vorhanden ──► Probleme beheben ──► Zurück zu [4]
	└──  Alles läuft ───────────► Projekt abschließen und nutzen
```
(⚠️) ungenauen Schritte
(🤖) logische Befehle
