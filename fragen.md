# Fragen für die IPA

- Was ist REST?
     - Representational State Transfer (REST) ist ein Architekturstil für APIs. Es wird verwendet, für die Bereitstellung von Standards zwischen Computersystemen im Internet, wodurch die Kommunikation zwischen Systemen erleichtert wird. Dabei werden bereits vorhandene Technologien und Protokolle des Internets benutzt, z. B. HTTP und JSON.

- Welche Verbs gibt es in REST?
    - GET - holt eine Ressource vom Server (sozusagen 'read')
    - POST - erstellt eine neue Ressource auf dem Server ('create')
    - PUT und PATCH - werden zum Updaten einer Ressource auf dem Server genutzt ('update')
    - DELETE - löscht eine Ressource vom Server ('delete')

- Wann soll welcher Verb genutzt werden?
    - siehe obere Frage

- Was ist node? Wieso gibt es node?
    - Node.js wird zur Entwicklung von Netzwerkanwendungen, insbesondere Webserver, genutzt. Mittels node ist es möglich, JavaScript auch im Backend einzusetzen -> nicht nötig andere Sprachen wie PHP zu lernen, asynchrones Programmieren möglich

- Was ist Typescript?
     - TypeScript ist ein typisiertes Superset von JavaScript, das zu reinem JavaScript kompiliert wird. Somit kann der Code von Node verwendet werden.

- Welches Protokoll nutzt ihr in eurem Node Applikationen?
     - http

- Was ist tsconf.json?
     - Das Konfigurationsfile von tsc (TypeScript Compiler). Dort werden Details zur Kompilation z. B. Zielordner, Version oder Regeln definiert.

- Was ist npm?
     -  Es ist das weltweit größte Softwareregister. Man brauch npm zum Teilen und Ausleihen von Paketen. Viele Organisationen nutzen npm auch, um private Entwicklungen zu verwalten.

- Wie kann ich sehen welche Pakete instaliert worden sind?
     - npm ls --depth=0

- Wie kann ich ein Paket für die Entwicklung installieren?
     - npm install ... (mit --save oder --save-dev wird das Package zudem in die Dependencies im package.json geschrieben. Wird in einem Projekt npm install ausgeführt, werden automatisch alle Packages aus diesem File installiert)

- Was ist Gulp?
     - Gulp ist ein Javascript Task Runner, mit dem man Aufgaben automatisieren kann.

- Welche andere Alternativen gibt es zu Gulp?
     - Grunt, Broccoli

- Wann wird Gulp eingesetzt?
     - Gulp kann verwendet werden, um HTML, JavaScript und CSS zu verkleinern, SCSS in CSS umzuwandeln, Bilder zu optimieren und Dateien in einen „dist“-Ordner zu kopieren. Außerdem kann Gulp dazu genutzt werden, um den Webbrowser automatisch zu aktualisieren oder ihn automatisch zu starten.

- Was ist Babel?
     - Babel ist ein JavaScript Compiler.

- Was mache Babel, wieso ist Babel wichtig?
     - Babel unterstützt die neueste Version von JavaScript über Syntaxtransformatoren. Mit diesen Plugins kann man die neue Syntax verwenden, ohne auf die Browserunterstützung zu warten.

- Was versteht man unter einem Entwicklungsworkflow?
     - Ein strukturierter Ablauf eines Projektes, damit Zeit und Mühe gespart werden. Ein Beispiel eines Entwicklungsworkflow ist:
          1. Scaffold
          2. Develop
          3. Test
          4. Integrate
          5. Optimize
          6. Deploy

- Was ist Ecmascript?
     - ECMAScript ist ein Subset von JavaScript. JavaScript ist im Kern ECMAScript, es baut darauf auf. Sprachen wie ActionScript, JavaScript, JScript verwenden alle ECMAScript als Kern.

- Welche Versionen davon gibt es?
     - 1: erste Version
     - 2: Redaktionelle Änderungen, damit die Spezifikation vollständig dem internationalen Standard ISO / IEC 16262 entspricht
     - 3: Regex hinzugefügt, bessere Handhabung von Zeichenfolgen, neue Steueranweisungen, Ausnahmebehandlung / -abfangen, genauere Definition von Fehlern, Formatierung für numerische Ausgaben und andere Verbesserungen
     - 4: Die vierte Ausgabe wurde aufgrund politischer Differenzen in Bezug auf die sprachliche Komplexität aufgegeben.
     - 5: Fügt "strict mode" hinzu. Eine Untergruppe, die eine gründlichere Fehlerprüfung ermöglicht und fehleranfällige Konstrukte vermeidet.
     - 6: Fügt eine bedeutende neue Syntax zum Schreiben komplexer Anwendungen hinzu, einschließlich Klassen und Modulen, definiert sie jedoch semantisch in den gleichen Begriffen wie ECMAScript 5 strict Modus. Weitere neue Features sind Iteratoren und for / of Schleifen, Python-artige Generatoren und Generator-Ausdrücke, Arrow-Functions, binäre Daten, typisierte Arrays, Sammlungen (maps, Mengen und schwache maps), promises und mathematische Verbesserungen.
     - 7: Die siebte Ausgabe, auch bekannt als ECMAScript 2016, wurde releast mit dem Ziel, die Themen Sprachenreform, Code-Isolation, Kontrolle von Effekten und Bibliotheks- / Tool-Aktivierung von ES2015 fortzusetzen, enthält zwei neue Funktionen: den Potenzierungsoperator (**) und Array .prototype.includes.
     - 8: Zu den vorgeschlagenen neuen Funktionen gehören concurrency und Atomics, binäre Datenübertragungen ohne Kopieren, mehr Zahlen und mathematische Erweiterungen, syntaktische Integration mit promises (await/async)

- Welche ist Version die du heute für deine Entwicklung nutzt?
     - Die siebte (ECMAScript 2016)

- Was ist Bootstrap?
     - Es ist ein HTML-, CSS-, JavaScript-Framework, das man als Grundlage für die Erstellung von Websites oder Webanwendungen verwenden können.

- Wieso gibt es Bootstrap?
     - Es wurde von Twitter entwikelt, um responsive, mobile-first Projekte im Internet zu erstellen.

- Welche Version von Bootstrap gibt es?
     - Version 1, 2, 3 und 4

- Was sind die Prinzipien von Bootstrap 4?
     - Ein stabiles und gut laufendes Framework zu sein.

- Wie funktioniert das Bootstrap-grid-System?

- Was ist ein Linter?
     - Ein Linter oder Lint bezieht sich auf Tools, die Quellcode analysieren, um Programmierfehler, stilistische Fehler und verdächtige Konstrukte zu kennzeichnen.

- Wieso wird es eingesetzt, was bringt es?
     - Man erkennt die Fehler und kann sie beheben, auch wenn die Syntx stimmt. Ein Beispiel ist "nicht erreichbarer Code". Er ist zwar korrekt geschrieben, aber der Linter erkennt, dass da etwas nicht stimmt.

- Was ist JSON?
     - Die JavaScript Object Notation, kurz JSON, ist ein kompaktes Datenformat in einer einfach lesbaren Textform zum Zweck des Datenaustauschs zwischen Anwendungen.

- Wieso wurde JSON erstellt?
     - Es ist einfach für Menschen zu lesen und zu schreiben. Rechner können leichter parsen und generieren.

- Was sind die stärke und schwäche von JSON?
    - Stärken: weitverbreitet und unterstützt, es wird auf der Serverseite geparst -> schnell, 
    - Schwächen: Sicherheit, kein Error Handling
- Was ist CDN?
    - Content Delivery Network, sind über das Internet verbundene Server, mit dem man regional meist grosse Daten verteilen kann. Das macht man, weil eine Verbindung zu einem beispielsweie in Amerika stehender Server viel länger geht, als zu einem Regionalen in der Schweiz.
- Was ist SASS?
    - Syntactically Awesome Stylesheets, ist eine Stylesheet-Sprache, mit der man mehr erreichen kann mit wenniger Code. Es beinhaltet beispielsweise Schleifen, Variabeln etc. Es ist in JSON geschrieben
- Was ist Web Packet?
    - Mit Web Packet kann man Code-Dateien schlanker und kleiner machen. Somit können die Daten schneller übermittelt werden
- Was ist Babel, für was kann man das brauchen?
    - Mit Babel kann man Code umkompilieren. Wenn man z.B. Code für eine spezielle IE Version bruacht, kann man den Code mit Babel kompilieren
- Was genau ist http?
    - Hypertext Tranfer Protocol, es ist ein zustandloses Protokoll, sprich es "vergisst" den Client wieder. Es wird hauptsächlich eingesetzt, um Webseiten aus dem Internet in einen Browser zu laden.
- Was für wichtige Informationen gibt es über IP-Adressen zu wissen?
    - Das Internet Protocol ist in verschiedenen Klassen aufgeteilt. Die Klassen A, B, C und D befinden sich im Gebrauch, die klasse E ist für zukünfige Zwecke reserviert. Der Aufbau der Adresse ist für jede Klasse anders.
    - Eine IP Adresse ist technisch gesehen ein Binär Code, der aus 32 Bits und 4 Bytes besteht (ipv4)
- Was ist das OSI Model? Welche Schichten hat es?
    - Zweck des OSI-Modells ist, Kommunikation über unterschiedlichste technische Systeme hinweg zu ermöglichen.
    - Schicht 1 – Bitübertragungsschicht (Physical Layer) 
    - Schicht 2 – Sicherungsschicht (Data Link Layer)
    - Schicht 3 – Vermittlungsschicht (Network Layer)
    - Schicht 4 – Transportschicht (Transport Layer)
    - Schicht 5 – Sitzungsschicht (Session Layer)
    - Schicht 6 – Darstellungsschicht (Presentation Layer)
    - Schicht 7 – Anwendungsschicht (Application Layer)
    
    