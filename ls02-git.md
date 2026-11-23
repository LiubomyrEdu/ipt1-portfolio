# Die wichtigsten Befehle

## Git – jeden Tag

| Befehl | Was passiert? |
|--------|---------------|
| `git status` | Wo stehe ich? Was ist geändert? |
| `git add .` | Alle Änderungen vormerken (Staging) |
| `git commit -m "Was und warum"` | Version speichern |
| `git push` | Auf GitHub hochladen |
| `git pull` | Neueste Version von GitHub holen |
| `git log --oneline` | Verlauf anzeigen |

## Git – einmalig oder ab und zu

| Befehl | Was passiert? |
|--------|---------------|
| `git clone <url>` | Repo von GitHub auf den PC holen |
| `git switch -c <name>` | Neuen Branch erstellen und wechseln |

## Der Weg einer Änderung

```
Arbeitsverzeichnis --add--> Staging --commit--> Repository --push--> GitHub
```

**Gute Commit-Nachricht:** `LS5: Ticketpreis-Rechner mit 3 Testfällen`
**Schlechte Commit-Nachricht:** `update`, `fix`, `asdf`

## C# – Konsole

| Befehl | Was passiert? |
|--------|---------------|
| `dotnet new console -o ls05-csharp` | Neues Projekt im Ordner erstellen |
| `dotnet new gitignore` | `bin/` und `obj/` nicht auf GitHub laden |
| `dotnet run` | Programm starten |
| `Console.WriteLine("...");` | **Ausgabe** |
| `Console.ReadLine()` | **Eingabe** – liefert **immer Text** |
| `int.Parse(...)` | Text → ganze Zahl |
| `double.Parse(...)` | Text → Kommazahl |

## Datentypen

| Typ | Für | Beispiel |
|-----|-----|----------|
| `int` | ganze Zahl | `3`, `42`, `-7` |
| `double` | Kommazahl | `12.50`, `0.1` |
| `string` | Text | `"Mensa"`, `"Max"` |
| `bool` | wahr / falsch | `true`, `false` |

## Markdown (README)

```
# Titel
## Untertitel
- Listenpunkt
[Linktext](https://...)
`code`
```
