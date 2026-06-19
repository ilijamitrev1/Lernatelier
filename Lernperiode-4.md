# Lern-Periode 4

- Name: Ilija Mitrev
- Zeitraum: 24.04.2026 bis 26.06.2026

## Grob-Planung

### Noten
Ich besonders gut mit dem Datenbanken. Diese Module habe ich mit 6-er abgeschlossen und eines von den 3 war mit 5.5.

### Veränderungen
verschiedene Plattformen ausprobieren als nur Viusal Studio/ Visual Studio Code

### Projekte / neue Technologien
Ich möchte Unreal Engine ausprobieren

### Planung
Ich möchte eine neue Programmiersprache anfangen und ich habe mich für C++ entschieden. Ich will ein kleines Spiel programmieren. Vielleicht werde ich es auch mit Unreal Engine versuchen aber ich bin mir noch nicht sicher

### Generelle Ziele
Mein Ziel ist es, die Sprache kennenzulernen und ein Spiel haben

### Planung 24.04.2026 
- [x] Sprache herausfinden, mit der man überhaupt programmiert
- [x] Welche Tools brauche ich?
- [x] Wie werden Spiele programmiert? Wie sieht der Code aus? Was für Elemente gibt es?
### Planung 08.05.2026
- [x] anfangen
- [x] informieren und kleiner Input 
- [x] vielleicht anfangen zu programmieren
### Reflexion
Heute habe ich das Entwicklerpaket für C++ heruntergeladen auf Visual Studio und die ersten Zeilen geschrieben. Ich werde mich aber mehr informieren und recherchieren 
das nächste Mal, um mehr zu programmieren. Vielleicht werde ich noch Unreal Engine herunterladen, um zu schauen, wie die Engine funktioniert.
### 22.05.2026 
- [x] weiter programmieren
- [x] recherichieren und mehr Wissen bekommen
- [x] Planung für das nächste Mal
### Reflexion
Heute habe ich mich mehr über die Sprache selbst informiert und habe gut verstanden, wie sie aufgebaut ist. Ich habe sie mit C sharp verglichen, da der Aufbau 
ähnlich ist und ich auch gut ableiten kann, was welches Element macht. Ich konnte nicht zu viel programmieren aber habe ein kleines Programm zusammenstellen 
können und es funktioniert. Das war mir am wichtigsten. Man sieht am Aufbau vom Code das es sehr an c sharp ähnelt. Man muss auch als erstes die variablen op,
x und y definieren, und dann wieder mit While, if und so weiter weitermachen. 
Code:
#include <iostream>
using namespace std;

int main() {
    char op;
    double x, y;

    while (true) {
        cout << "Welche Operation moechtest du ausfuehren? (+, -, *, /): ";
        cin >> op;

        if (op == '+' || op == '-' || op == '*' || op == '/') {
            break;
        }

        cout << "Ungueltige Eingabe! Bitte nur +, -, * oder / eingeben." << endl;
    }

    cout << "Erste Zahl eingeben: ";
    cin >> x;

    cout << "Zweite Zahl eingeben: ";
    cin >> y;

    double result;

    switch (op) {
    case '+':
        result = x + y;
        break;

    case '-':
        result = x - y;
        break;

    case '*':
        result = x * y;
        break;

    case '/':
        if (y == 0) {
            cout << "Fehler: Division durch 0 ist nicht erlaubt!" << endl;
            return 0;
        }
        result = x / y;
        break;
    }

    cout << "Ergebnis: " << result << endl;

    return 0;
}
### Planung 29.05.2026
- [x] Etwas richtiges programmieren vllt. schon mit Viusalisierung
- [x] Schauen, ob es mit Visual Studio geht oder doch die Engine nötig ist
- [x] Mehr Elemente lernen (Bsp. wie programmiert man Bewegung mit WASD?)
- [x] Planung für das nächste Mal
### Reflexion 
Heute habe ich an dem Modul 122 weitergearbeitet, weil wir nächste Woche eine Prüfung
haben und ich noch etwas fertigmachen musste.
### Planung 05.06.2026
- [x] Planung für das nächste Mal
- [x] programmieren
- [x] Unreal Engine
### Reflexion
Heute habe ich den ganzen Tag mit der Unreal Engine verbracht und sie nicht wirklich eingerichtet. Es ist sehr kompliziert und mich noch besser informieren, um sie korrekt einzurichten
### Planung 12.06.2026
- [x] Unreal Engine
- [x] programmieren
- [x] Tutorials schauen
### Reflexion 
Das mit Unreal Engine wird leider nicht funktionieren ich werde nur mit Visual Studio programmieren müssen. Die Tutorials sind zu alt für die akutellen Versionen von Unreal Engine. Ich es versucht aber geht nicht. 
### 19.06.2026
- [ ] Programmieren nur auf VS
- [ ] Tutorial suche nur für VS
- [ ] Erstes Spiel in 2d und mit Fenster-Anzeige
