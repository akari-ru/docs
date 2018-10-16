# Aykosh

Aufgaben für C#  ~D \\(^o^)/ __/

## Hausaufgabe 1

### 1. Erstellen von neuen Projekten in Visual Studio
Öffne dein Visual Studio und erstelle eine neue C# Konsolen Applikation (Console Application mit den Namen 'AykoshRulesThemAll'.

Zu den verschiedenen Projekten die erstellbar sind, es sind Templates, was im Grunde genommen bedeutet
Visual Studio erstellt eine Ordnerstruktur mit entsprechenden Dateien und Einstellung für ein bestimmte
Anwendung, welche man erstellen will. Beispiele wären, unsere Konsolen Anwendung, ein Spiel oder eine
Klassen Bibliothek (aber dazu später ^^).

### 2. Datentypen
In dein erstelltes Konsolen Programm in der Main Funktion:
```C#
	 static void Main(string[] args)
     {
     	 // Hier kommt dein Code rein ;)
     }
```
Deklariere für jeden Datentyp eine Variable mit beliebigen Wert und gebe diese auf der Kommandozeile aus.
```C#
Console.WriteLine("NameDerVariable ist " + variable);
```

Ignorier dat mal : /
Etwas schwerer - Testen der Wertebereiche:
Teste die möglichen Werte die eine Variable vom Typ uint annehmen kann.
uint steht für unsigned integer bzw. vorzeichenlose Ganzzahll.
uint ist im Grunde genommen ein int jedoch ohne Vorzeichen.
Es werden alle 32 Bit für die interne Abspeicherung der Zahl verwendet,
wobei bei normalen int das erste Bit für + oder - verwendet wird und die restlichen 31 für die Zahl.
Die Größe eines Datentyps in Bytes kann mit dem sizeof() Operator. Merke: 1 Byte = 8 Bit
Beispiel:
```C#
Console.WriteLine("int ist " + sizeof(int) + " Bytes  (" + sizeof(int)*8 + " Bit) groß.");
```

### 3. if und else
Schreibe eine if else Verzweigung die Testet ob eine Zahl größer oder kleiner als 10 ist,
und das entsprechende Ergebnis auf der Kommandozeile ausgibt.
Code Template:
```C#
int zahl;
if ( /* Hier kommt dein Code rein */ ) 
{
	Console.WriteLine("" + zahl + " ist größer oder gleich 10.");
}
else 
{
	Console.WriteLine("" + zahl + " ist kleiner als 10.");
}
```

Das wars ;)
