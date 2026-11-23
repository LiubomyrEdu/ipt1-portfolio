```
int auswahl;

do
{
    Console.Write("Eine Anzahl Bücher zwischen 1 und 5: ");
    auswahl = Convert.ToInt32(Console.ReadLine());
} while (auswahl >= 1 || auswahl <= 5);

for (int i = 1; i <= auswahl; i++)
{
    Console.WriteLine($"Buch {i} registriert");
}

while (auswahl > 0)
{
    Console.WriteLine($"Noch {auswahl} offen");
    auswahl--;
}

Console.WriteLine("Alle Bücher verarbeitet.");
```
