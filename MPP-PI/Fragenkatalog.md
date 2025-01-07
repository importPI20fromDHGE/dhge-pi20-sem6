# Fragenkatalog MPP2

Sammlung von in der MPP 2 gestellten Fragen unseres Kurses (PI20). Zusätzlich einige statistische Informationen.

Ermittelt aus [Google Forms Umfrage](https://docs.google.com/forms/d/10i2sxWrXhH-zEt9lYSmu3H_ZBvT09PPUQZmUiER4t8Y/viewanalytics).

- [Fragenkatalog MPP2](#fragenkatalog-mpp2)
  - [Allgemeine Fragen](#allgemeine-fragen)
  - [Fragen der Praxispartner](#fragen-der-praxispartner)
  - [Prof. Günther \& Hr. Grimm](#prof-günther--hr-grimm)
    - [Statistiken](#statistiken)
    - [Fragen](#fragen)
    - [Anmerkungen](#anmerkungen)
  - [Prof. Kusche \& Hr. Grimm](#prof-kusche--hr-grimm)
    - [Statistiken](#statistiken-1)
    - [Fragen](#fragen-1)
    - [Anmerkungen](#anmerkungen-1)
  - [Prof. Kusche \& Prof. Matschinske](#prof-kusche--prof-matschinske)
    - [Statistiken](#statistiken-2)
    - [Fragen](#fragen-2)
    - [Anmerkungen](#anmerkungen-2)
  - [Prof. Kusche \& Prof. Günther](#prof-kusche--prof-günther)
    - [Statistiken](#statistiken-3)
    - [Fragen](#fragen-3)
    - [Anmerkungen](#anmerkungen-3)
  - [Anmerkungen zu Nachprüfungen](#anmerkungen-zu-nachprüfungen)

## Allgemeine Fragen

*Nichts zu vermelden: Wurden alle zugeordnet*

## Fragen der Praxispartner

- Was macht die LED, wenn man eine Rechteckspannung anlegt -> blinkt
  - Zusatzpunkt gab es dafür zu erwähnen, dass p-dotierte Schicht bei LED dünner ist als bei normalen Silizium Dioden
- In einer Lichterkette, wie sind LEDs angeordnet? Reihe oder Parallel -> beides (scheinbar?) wollte parallel hören, aber Reihe war mit richtiger Erklärung auch richtig
- UML-Klassendiagramm
- Altes Mainboard erklären
- Programmieren (Klassendiagramm, allgemeine Fragen zu OOP, Member)
- Klassendiagramme für einen Vogel aufmalen. -> Was wenn ich einen speziellen Vogel will (Vererbung). Was ist wenn ich ein spezielles Aussehen von Vogel erzeugen will (er wollte auf Fabrikmuster hinaus)
- Spezialisierte Fabriken zur Objekterzeugung
- Die Stromleitung im Haus hat wie viel Ampere? - 16A
- Wie kann die CPU 100A nutzen, ohne dass die Sicherung rausfliegt? -> Stromleitung hat 3680W und 230V, wenn man die Spannung am PC verringert, bekommt man mehr Ampere.
- Behauptung: "Ich behaupte ein Monitor Flackert". -> Stimmt -> Wie oft -> Hertz Anzahl
- Wie ist eine LED aufgebaut?
- Kopfrechenaufgabe wie viele LEDs in einem 4k Monitor vorhanden sind (Einfache Werte).
- Wie werden die einzelnen LEDs effektiv angesprochen -> Multiplexer
- Zeichne ein ERM für Autovermietung mit Auto, Kunden und Rechnungen. + weitere Fragen zu DB-Planung
- Unterschied TCP UDP
  - Klassendiagramm und Beziehung zwischen beiden
  - Was für Techniken und Co für Implementierung (BA bezogen)
- Datenbankindex
- 16 Bit Text/Hash in DB speichern -> char[16]  (wegen BA)
- OOP-Paradigmen
- MVC
- Client Server
- REST
- DNS (inkl. MX Record)
- Was ist der Unterschied zwischen symmetrischer und asymmetrischer Verschlüsselung?
- Wozu braucht man Service-Level Agreements?
- Vor- und Nachteile Micro Services
- Klassendiagramm
- 3-Schichten Architektur
- OOP
- UML
- API vs. ABI
- Agile Entwicklung
- Was macht die DevOps Abteilung
- Stakeholder bei einem Projekt
- UML-Diagramm: Wann wird der Destruktor aufgerufen? -> Nach der Beendung des Scopes "{}"
- Call by Reference und Call by Value
- Unterschied Liste und Array
- Funktionsweise Docker
- Server-Side-/Client-Side-Rendering
- Vorteil UUIDs zu Integer bei DB-Indexierung
- 3 Säulen Cloud -> IaaS PaaS SaaS
- Vogel Programm erstellen, Klassendiagramm gewünscht ->
  - Wie alt ist ein Vogel? -> mit double angefangen, damit genauer, Prüfer wollte dann aber auf Geburtsdatum hinaus ("ich möchte es so genau wissen, wann immer ich möchte") -> Geburtsdatum mit genauer Sekunde (z. B. unix-Timestamp, long)
  - Vererbung: Erklären, was dadurch passiert

## Prof. Günther & Hr. Grimm

### Statistiken

*Vorzustellende Projektarbeit*  
60% PA4 (aber nur, weil die Note der BA noch nicht vorlag)  
40% BA

*Fragen zu Projektarbeiten*  
Bei 80% hatten weniger als 2/3 der Fragen Bezug zur Projektarbeit. Beim Rest war es ungefähr Hälfte-Hälfte.

*Welche Module wurden abgefragt (bei % der Studierenden)*  
80% Programmieren & OOP (Semester 1 & 2 - Prof. Kusche)  
60% Systementwicklung (Semester 3 & 4 - Prof. Kasche)
80% Einführung in die Informatik / Digitaltechnik (Semester 1 - Prof. Dorendorf/ Prof. Barié)  
20% Algorithmen und Datenstrukturen (Semester 2 - Prof. Dorendorf)  
40% Datenbanken (Semester 3 & 4 - Prof. Dorendorf & Hr. Grimm)  
40% Betriebssysteme und Rechnernetze (Semester 2 & 3 - Prof. Günther / Hr. Feldmann (ext.))  
60% Verteilte Systeme / Netzwerkadministration (Semester 5 & 6 - Hr. Feldmann (ext.) / Prof. Barié)  
60% Elektrotechnik / Elektronik (Semester 1 & 2 - Prof. Barié)  
20% Webentwicklung (Semester 5 - Hr. Grimm)  
20% IT-Trends (Semester 3 - Prof. Kasche)

### Fragen

*Prof. Günther*

- Funktionsweise CD
- Funktionsweise Analog-Digital-Wandler
- Netzwerk mit Teilnehmern anzeichnen -> wie viele IP-Adressen sind in dem Netz?
- IP-Adressen allgemein
- Ping an google.com beschreiben
- NAT und DNS erklären
- CD hat kleine Plättchen -> Reinigungs-CD für Laser
- Wie sind da Daten gespeichert -> haben kleine Rillen, die durch Laser ausgelesen werden, wie wird da ein Lautsprecher angesteckt/wie kommt der Ton raus
- TCP -> wie erkennt es, dass ein Datenpaket verloren gegangen ist -> Sequenznummer für jedes Paket.

*Hr. Grimm*

- Welche Datenstrukturen gibt es in C
- Schreiben Sie eine Schleife in einer beliebigen Sprache, welche alle geraden Zahlen zwischen 12 und 25 ausgibt. Modulo-Operator in C bspw. gewünscht

*unklar*

- Was gibt es für Elemente in der Digitaltechnik?
- Wertetabelle UND-Gatter
- Was benötigt man, um 3+1 bitweise zu addieren?
- Halbaddierer/Volladdierer Funktionsweise
- Ohm'sches-Gesetzt berechnen (mit Falle: absichtlich falsches Ergebnis vorgesagt -> Wollten sehen, ob man die realistischen Wertbereiche für Widerstände kennt)
- Schaltkreis zeichnen
- Vorwiderstand erklären
- Datenbanken/Relationen
- Besonderheit n-zu-m Beziehung?
- Welche Komponente eines Betriebssystems kümmert sich um die Ausführung von Programmen und die gleichzeitige Ausführung mehrerer Prozesse? -> Scheduler
- C-Programmierung (Schleifen und Pointer)
- ICMP -> Ping
- Rechennetz skizzieren
- Subnetze

### Anmerkungen

- Es lagen 4 Hardware-Komponenten da... (CD, RAM, Ethernet-Anschluss, Kassette) -> sich eins aussuchen & erklären
- Fragen können von sehr leicht bis unlösbar reichen -> ist alles durcheinander gemischt, ohne klare Richtung.
- Scheinbar wurde die Schwierigkeit der Fragen gegenüber dem Vorjahr etwas erhöht, was in viel Digital- bzw. Elektrotechnik endete.
- Atmosphäre war eher professionell - besonders von Prof. Günther. Nicken auch, wenn man bei was falsch liegt...
- Interessieren sich eigentlich nur für richtige Antworten. Ausschweifen, wenn man sich bei etwas unsicher ist, um trotzdem Wissen zu zeigen, ist unerwünscht/gibt wenig bis keine Punkte
- Bewertung war moderat bis streng, wenn man das hohe Anforderungslevel beachtet.
- Fürs Lernen daher:
  - Alles gründlich anschauen und immer wieder Dinge hinterfragen.
  - Themen und Konzepte tiefgreifend verstehen.
  - Dieses Formular NICHT als end all be all ansehen. Es können und werden ganz andere Fragen kommen.

## Prof. Kusche & Hr. Grimm

### Statistiken

*Vorzustellende Projektarbeit*  
100% BA

*Fragen zu Projektarbeiten*  
Bei 80% hatten weniger als 2/3 der Fragen Bezug zur Projektarbeit. Beim Rest war es ungefähr Hälfte-Hälfte.

*Welche Module wurden abgefragt (bei % der Studierenden)*  
80% Programmieren & OOP (Semester 1 & 2 - Prof. Kusche)  
60% Systementwicklung (Semester 3 & 4 - Prof. Kasche)
20% Einführung in die Informatik / Digitaltechnik (Semester 1 - Prof. Dorendorf/ Prof. Barié)  
20% Algorithmen und Datenstrukturen (Semester 2 - Prof. Dorendorf)  
60% Datenbanken (Semester 3 & 4 - Prof. Dorendorf & Hr. Grimm)  
60% Betriebssysteme und Rechnernetze (Semester 2 & 3 - Prof. Günther / Hr. Feldmann (ext.))  
40% Verteilte Systeme / Netzwerkadministration (Semester 5 & 6 - Hr. Feldmann (ext.) / Prof. Barié)  
80% Elektrotechnik / Elektronik (Semester 1 & 2 - Prof. Barié)  
60% Technische Informatik/ Rechnerarchitektur (Semester 4 - Prof. Günther)  
20% E-Commerece (Semester 5 - Prof. Müller)  
20% ITM: ITIL (Semester 6 - Prof. Müller)

### Fragen

*Prof. Kusche*

- Datenbanken (Grund für künstliche Schlüssel, Joins, Indizes)
- Baumstruktur (Binärer Sortierbaum, Problem bei sortiertem Array zu Baum -> hängt schief)
- Umwandlung Wechselstrom zu Gleichstrom und welche Aufgabe hat ein Kondensator dabei
- ACID, Locking-Konzepte, Logging, read und write - erklären reichte nicht, man musste den gesuchten Begriff erraten.
- Wie viel Watt hat eine CPU
- Aus Watt Ampere ermitteln
- Was passiert bei einer hohen Stromstärke in der Leitung
- Wie viel Ampere hat der Hausstrom
- Modolo-Operator in C. Wissen, dass Bitoperationen performanter sind als Modolo-OPs
- Was passiert, wenn eine Pipeline einen if-operator ausführt?
- Haushaltsstrom, einfacher Gleichrichter, Brückengleichrichter, Diode, Spannung und Strom
- Netzwerke, Router, Verteilte Systeme, IP-Adressen, Subnetze
- Ganz viele Hardwarefragen zu einem alten Servermainboard (i486)
- Register
- ISO/OSI (erschreckend gründlich: Protokolle und Geräte zuordnen, Schichten benennen, etc.)
- Verschlüsselung (oberflächlich - async/sync²)
- IP-Adressen
- WAN/LAN
- Viele Fragen nach smart Pointers, weil er das in meinem Code gesehen hat.
  - Was ist make_unique - make_shared.
- RAM und Bussysteme -> Parallel oder seriell - Daten und Adressen
- Wann weist eine Netzwerkkarte, dass ein Packet ist gerade gekommen? -> Interrupt

*Hr. Grimm*

- Was sind relationale DBMS - Indexes - Join - Select - Logs - Transactions

² ggf. ist auch asymmetrisch/ symmetrisch gemeint

### Anmerkungen

- Waren alle sehr entspannt und nett.
- Helfen, wenn man nicht mehr weiterkommt.
- Prof. Kusche hat sehr viel geredet. Von ihm kann alles kommen. Elektrotechnik und Elektronik mit einfachen Rechnungen sind sehr gern gesehen
- Wenn du in der Arbeit Code hast, dann kannst du erwarten, dass Prof. Kusche dazu was fragt und das ist nicht schlecht, weil 30 Minuten gingen bei mir um den Code.

## Prof. Kusche & Prof. Matschinske

### Statistiken

*Vorzustellende Projektarbeit*  
100% BA

*Fragen zu Projektarbeiten*  
Bei allen hatten weniger als 2/3 der Fragen Bezug zur Projektarbeit.

*Welche Module wurden abgefragt (bei % der Studierenden)*  
57% Programmieren & OOP (Semester 1 & 2 - Prof. Kusche)  
86% Systementwicklung (Semester 3 & 4 - Prof. Kasche)
29% Einführung in die Informatik / Digitaltechnik (Semester 1 - Prof. Dorendorf/ Prof. Barié)  
29% Algorithmen und Datenstrukturen (Semester 2 - Prof. Dorendorf)  
29% Datenbanken (Semester 3 & 4 - Prof. Dorendorf & Hr. Grimm)  
86% Betriebssysteme und Rechnernetze (Semester 2 & 3 - Prof. Günther / Hr. Feldmann (ext.))  
43% Verteilte Systeme / Netzwerkadministration (Semester 5 & 6 - Hr. Feldmann (ext.) / Prof. Barié)  
14% Systemprogrammierung (Semester 6 & 6 - Prof. Günther)  
43% Elektrotechnik / Elektronik (Semester 1 & 2 - Prof. Barié)  
58% Technische Informatik/ Rechnerarchitektur (Semester 4 - Prof. Günther)

### Fragen

*Prof. Kusche*

- LAN-Kabel
  - Wie viele Adern darunter?
  - Wie werden hier Daten übertragen? (Wollte hier symmetrische Signalübertragung wissen)
- Was ist passiert, wenn es zu einen unknown host, access denied, too many hops kommt? Wie kommt sowas an? (ICMP)
- V-Modell und warum werden dazwischen immer Parallelen gezeichnet.
- Kennst du Modelle mit 'Kreisen' -> Spiralen Modell und SCRUM
- Hardware-Teile, die vom Prüfer benannt wurden, auf Platine zeigen
- Was speichert -> ROM
- Programm Management Arten (Wasserfallmodell und Co)
- Was ist ein Member, wenn er für die gesamte Klasse gilt (static)
- NTP
- Public, private, protected
- Konstruktoren
- Hausstrom: Kann man 20 Rechner an eine Steckdose stecken? (nein), wieviel Watt braucht ein Rechner (ungefähr 250W), wer reguliert den Strom in der Steckdose (Sicherungen)
- Bei OOP konkretes zu Klassen, Methoden, abstrakten Klassen usw.
- Wie verschicken Rechner im lokalen Netzwerk IP-Pakete, hier auch ARP kurz angeschnitten (Ethernet Frames)
- Wie verschicken Rechner global Pakete, über welches Protokoll (IP)
- Redundanz in Rechenzentren und Redundanz bei Netzwerkkabeln global
- Viel zu IP-Adressen
  - Wie die aufgebaut sind (Host-Anteil usw.)
  - Private IP-Adressen
  - Welche IP-Adressen nicht vergeben werden können (Broadcast, ...)
  - Subnetze (allgemein)
- Mainboard erklären (Uhr, BIOS, BIOS SRAM, externer L2 Cache, 2. BIOS Sockel)
- Binärbaum (Operationen: durchlaufen -> Rekursive Aufrufe)
- Was landet im Stack bei Funktionsaufruf
- Was passiert bei Endlosrekursion (Speicherzugriffsfehler weil Stack voll) -> welche Einheit löst Fehler aus (MMU via Interrupt)
- Unterschied Prozess und Thread?
- Welchen Speicher Teilen sich Thread und Prozess -> Heap
- Semaphoren -> Was machen die?
- Woher weiß ein Prozess, welcher Thread zu ihm gehört?
- Computer Leitung berechnen
  - Wie viel Watt zieht ein Prozessor unter Last? -> Er wollte 130 W
  - Wie viel Volt braucht der Prozessor auf dem Mainboard? -> 1.3 Volt
  - Dann wollte er wissen, was man daraus berechnen kann.-> Stromstärke-> I=P/V=130W/1.3 =100A
  - Diese 100A werden ja auf viele Anschlüsse am Prozessor verteilt. Was passiert, wenn man alles über einen schickt?
- Netzwerke und Firewalls
  - Was gibt es für Firewalls und wo sind Unterschiede?
  - Nach was kann die Firewall filtern?
  - Wie setzt man eine Firewall sinnvoll in einem Netzwerk ein?
- Was steht am Anfang eines Pakets und was steht am Ende?
- TCP/UDP
- Datenstrukturen
- Algorithmen
- Hardware (Motherboard) mit Datenleitungen
- Interrupt - im Detail

*Prof. Matschinske*

- Wie wird eine Nutzwertanalyse aufgestellt (wegen BA)
- Agile Softwareentwicklung allgemein: Was ist der Unterschied wenn man ein fertiges Produkt aus einer agilen Entwicklung hat zu einem aus einer nicht agilen -> mehr auf die Bedürfnisse der Nutzer:innen angepasst usw.
- Was ist PDCA?
- SCRUM Artefakte und Rollen
- SCRUM im Detail

### Anmerkungen

- Prof. Kusche hat ziemlich versucht einen die Antwort hinterherzutragen, wenn man nicht gleich drauf kommt. Liegt größtenteils daran, dass er komisch umformulierte Fragen stellen muss, damit wir nicht gleich auf die Antwort kommen.
- War viel angenehmer als ich gedacht habe. Prof. Kusche greift mit einigen Fragen mehr in die Tiefe und will da auch eine Antwort von dir haben - da wird nicht locker gelassen. Aber es ist oft nichts Unmögliches.
- 8,9/10: Würde gerne wieder mit Prof. Kusche Prüfung haben
- Prof. Kusche ist gut drauf und hilft gern, verrennt sich aber auch total in eine Richtung, wenn er einmal dabei ist
- Sie sind echt sehr lieb und lenken einem auch zu den richtigen Antworten, wenn man mal etwas nicht sofort weiß. Prof. Kusche hat auch sehr viel einfach so erzählt, ohne dabei konkrete Fragen zu stellen.

## Prof. Kusche & Prof. Günther

### Statistiken

*Vorzustellende Projektarbeit*  
100% BA

*Fragen zu Projektarbeiten*  
Bei allen hatten weniger als 2/3 der Fragen Bezug zur Projektarbeit.

*Welche Module wurden abgefragt (bei % der Studierenden)*  
67% Programmieren & OOP (Semester 1 & 2 - Prof. Kusche)  
67% Systementwicklung (Semester 3 & 4 - Prof. Kasche)
50% Einführung in die Informatik / Digitaltechnik (Semester 1 - Prof. Dorendorf/ Prof. Barié)  
34% Algorithmen und Datenstrukturen (Semester 2 - Prof. Dorendorf)  
50% Datenbanken (Semester 3 & 4 - Prof. Dorendorf & Hr. Grimm)  
50% Verteilte Systeme / Netzwerkadministration (Semester 5 & 6 - Hr. Feldmann (ext.) / Prof. Barié)  
67% Systemprogrammierung (Semester 6 & 6 - Prof. Günther)  
67% Elektrotechnik / Elektronik (Semester 1 & 2 - Prof. Barié)  
34% Technische Informatik/ Rechnerarchitektur (Semester 4 - Prof. Günther)

### Fragen

*Prof. Kusche*

- Viel zur Arbeit, auch im Vortrag bereits
- Automaten/Sprachen/Grammatik: Wie kann Code Syntax noch dargestellt werden? Backus-Naur-Form
- Ich habe 5V Eingangsspannung. Was ist, wenn ich eine LED anschließen will? -> LED-Spannung zwischen 1,8V und 3,3V -> Vorwiderstand berechnen -> 20mA Strom -> 100 Ohm
- Was hat bei gleichen Bauteilen die höhere Leistung? Parallel oder Reihe
- Einwurf zu Günther: Code verbessern -> int i = 25 statt int i = 0 etc.
- Zu Datenbanken
  - Primary Keys (ID) vs. zusammengesetzte IDs (aus mehreren Spalten)
  - Warum Daten nicht nach einem Commit oder Rollback direkt auf der Datenbank geupdated werden und WO diese dann stehen (Transaction-log)
  - Seltene Eigenschafften aufzählen, wann der Server ein Rollback machen will, obwohl der Client einen Commit möchte (Wenn 2 Clients gleichzeitig ein Datensatz editieren und dann committen wollen).
  - Backups (wie werden daten wiederhergestellt > Backups, Transaction-Logs für DB)
- Wie wandelt man analoge Sensor-Daten (Helligkeitssensor) in digitale Daten um (AD Wandler) -> zwei spezielle Werte kennen
- Wie sehr kann ein Prozess verbessert werden, der 50% der Zeit im kritischen Abschnitt verbringt, wenn die Menge an Prozessoren und Prozessen irrelevant ist?
  - Menge an Prozessoren war nicht irrelevant - wenn alles parallel läuft, kann er auf die maximal Leistung eines Prozessors verbessert werden -> wollte darauf hinaus, dass ein Prozess scheinbar nicht Parallel abgearbeitet werden kann sondern nur verschiedene Prozesse.
- Welche Arten von Deadlocks gibt es? - ohne Interprozesskommunikation, Prozess basiert auf anderem Prozess, Sperrung der Datenbank von 2 Transaktionen gleichzeitig
- Wie viele Watt hat eine CPU? - 45-300W -> er wollte 130W
- Wie viel Spannung hat eine CPU? - 1,3V
- Wie kann ich aus Watt und Spannung Strom berechnen? - W/V = A
- Wie viel Ampere hat die CPU dann? - 130W / 1,3V = 100A
- Wie viele Pins hat eine CPU? - 200 (ist zwar nicht zeitgemäß aber was solls)
- Eine CPU hat etwa 200 Pins. Wie bekommt die CPU diese mit dem Strom versorgt? - Parallelschaltung
- Kennen Sie den Kirchhoff'schen Satz? - Ja, Knotenregel, dass an jedem Knoten I=0 -> an jedem Pin 0,5A
- Die Stromleitung im Haus hat wie viel Ampere? - 16A
- Wie kann die CPU 100A nutzen ohne dass die Sicherung rausfliegt? - Stromleitung hat 3680W, wenn man die Spannung verringert bekommt man mehr Ampere.
- Wie viel Spannung für einen ganzen Rechner von 230W für 100A? - 230W/100A = 2,3V
- Mit welchem SQL-Befehl werden Daten abgefragt? - SELECT
- Welche Arten von Beziehungen gibt es? - 1:1, 1:n, n:1, n:m
- Was ist die Besonderheit bei n:m? - Beziehungstabelle
- Wie werden Tabellen verbunden? - Primär- und Fremdschlüssel
- Mit welcher SQL Operation werden die Daten aus zwei Tabellen verknüpft? - JOIN
- Wie kann die Performance verbessert werden, wenn von der Tabelle mit dem Fremdschlüssel aus, die Daten aus der "Haupttabelle" verbunden werden sollen? - Indizes
- Was unterscheidet UDP von TCP?
- Was passiert bei TCP wenn zu viele Pakete auf der Leitung sind (neusenden von Paketen) -> Was passiert in dem Fall bei UDP?
- NAT
- ISO/OSI
- ICMP
- Firewall stateless und statefull)
- Elektrotechnik (Kondensator, Wechselstrom zu Gleichstrom, zugehörige Spannungsverläufe)
- Password-Hashing
- Dependency Injection
- TTL IP-Pakete
- Signaturen
- DNS
- DHCP
- L2-Cache -> die Anordnung zwischen RAM und CPU, wie groß die L2 Caches und was machen die, er ist dann noch auf Bus-typen gekommen und wollte auf die Harvard-Architektur hinaus
- Unterschied des Lesens zwischen CD und Festplatte

*Prof. Günther*

- Was ist das (die von mir angezeichnete Schaltung mit LED) -> Reihe -> Parallel auch noch ein Beispiel gegeben
- kurz Kirchhoffsche Gesetze erklärt
- Programmierung: for-Schleife, alle ungeraden Zahlen zwischen 25 und 100 ausgeben -> Modolo Operator (%)
- Kritische Abschnitt, Deadlock/Race Condition (wie beheben -> Semaphoren. Tritt erst bei 2 Ressourcen und 2 Zugriffen auf diese 2 Ressourcen auf)
- 5 Philosophenproblem Erklären und Lösung nennen -> Deadlock -> Interprozesskommunikation: Semaphoren, Pipes, Sockets
- Welche Arten von Semaphoren gibt es?
- Wie funktioniert eine Semaphore?
- Wie funktioniert Pipes und Sockets + Vergleich dieser - lokal, nicht lokal; verwandt, ohne Verwandtschaft; ...
- Was bedeutet Reproduzierbarkeit und wenden sie es auf ihre Arbeit an
- Zwischen Kassette, CD, LAN-Port und RAM wählen -> Bei RAM ECC ja/nein, warum, wieviel Musik in CD Qualität passen in 4 GB
- Volladierer
- Diode Vorwiederstand
- Sockets
- CD (Reinigungs-CD)
- Analog-Digitalumwandler in der Digitaltechnik
- Umrechnen Binär in Hexadezimal

### Anmerkungen

- Prof. Günther war sehr bemüht, dass man besteht.
- Es war mehr wie ein Gespräch und sie lassen keinen aus Absicht durchfallen.
- Externer Prüfer hat Protokoll geschrieben, Prof. Günther und Prof. Kusche haben primär die Fragen gestellt.
- Prof. Kusche ist egal in welche Richtung du versucht das Gespräch zu lenken.

## Anmerkungen zu Nachprüfungen

- Die jeweils andere Projekt-/Bachelorarbeit wird vorgestellt (wenn beim Erstversuch die BA, wird beim Zweitversuch die PA4 gefordert)
- Wenn man das erste Mal durchfällt, ruhig bleiben, sie wollen einen wirklich durchbringen
- Auch abgewandelte Fragen vom ersten Versuch drangenommen. Sich diesen nochmal genau durch den Kopf gehen zu lassen ist von Vorteil
