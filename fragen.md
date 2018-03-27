# Fragen für die IPA

- Was ist REST?
     - = REpresentational State Transfer ist ein Architekturstil, für die Bereitstellung von Standards zwischen Computersystemen im Internet, wodurch die Kommunikation zwischen Systemen erleichtert wird. REST-konforme Systeme, oft als RESTful-System bezeichnet, zeichnen sich dadurch aus, dass sie zustandslos sind und die Anliegen von Client und Server voneinander trennen.
- Welche Verbs gibt es in REST?
     - GET
          - Abrufen von Informationen. Ein GET-Request muss sicher und idempotent sein.
     - POST
          - Oft wird POST verwendet, um eine neue Entität zu erstellen, aber es kann auch verwendet werden, um eine Entität zu aktualisieren.
     - PUT
          - Speichert eine Entität in einem URI. PUT kann eine neue Entität erstellen oder eine vorhandene aktualisieren. Eine PUT-Anfrage ist             idempotent. Idempotenz ist der Hauptunterschied zwischen PUT und POST.
     - PATCH
          - Aktualisieren Sie nur die angegebenen Felder einer Entität an einem URI. Eine PATCH-Anfrage auch ist idempotent.
     - DELETE  
          - Fordern Sie an, dass eine Ressource entfernt wird. Die Ressource muss jedoch nicht sofort entfernt werden. Es könnte eine asynchrone oder lang     andauernde Anfrage sein.
     *  --> In der Informatik wird ein Stück Programmcode, das mehrfach hintereinander ausgeführt wird und das gleiche Ergebnis wie bei einer einzigen              Ausführung liefert, als idempotent bezeichnet.
- Wann soll welcher Verb genutzt werden?
     - siehe obere Frage
- Was ist node? Wieso gibt es node?
     - Node.js ist eine JavaScript-Laufzeitumgebung, die auf der V8-JavaScript-Engine von Chrome basiert. Node.js verwendet ein ereignisgesteuertes, nicht blockierendes E / A-Modell, das es leicht und effizient macht.
     - Wenn der Andwenndungsfall keine rechenintensiven Vorgänge enthält oder auf blockierende Ressourcen zugreift, kann man die Vorteile von Node.js nutzen und schnelle und skalierbare Netzwerkanwendungen schreiben.
- Was ist Typescript?
     - TypeScript ist ein typisiertes Superset von JavaScript, das zu reinem JavaScript kompiliert wird.
- Welches Protokoll nutzt ihr in eurem Node Applikationen?
     - http
- Was ist tsconf.json?
     - Die Datei tsconfig.json gibt die Stammdateien und die Kompileroptionen an, die zum Kompilieren des Projekts erforderlich sind.
- Was ist npm?
     -  Es ist das weltweit größte Softwareregister. Man brauch npm zum Teilen und Ausleihen von Paketen. Viele Organisationen nutzen npm auch, um private Entwicklungen zu verwalten.
- Wie kann ich sehen welche Pakete instaliert worden sind?
     - npm ls
- Wie kann ich ein Paket für die Entwicklung installieren?
     - npm install
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
     - Die siebte
- Was ist Bootstrap?
     - Es ist ein HTML-, CSS-, JavaScript-Framework, das man als Grundlage für die Erstellung von Websites oder Webanwendungen verwenden können.
- Wieso gibt es Bootstrap?
     - Es wurde entwikelt, um responsive, mobile-first Projekte im Internet zu erstellen.
- Welche Version von Bootstrap gibt es?
     - Version 1, 2, 3 und 4
- Was sind die Prinzipien von Bootstrap 4?
     - Ein stabiles und gut laufendes Framework zu sein.
- Was ist ein Linter?
     - Ein Linter oder Lint bezieht sich auf Tools, die Quellcode analysieren, um Programmierfehler, stilistische Fehler und verdächtige Konstrukte zu         kennzeichnen.
- Wieso wird es eingesetzt, was bringt es?
     - Man erkennt die Fehler und kann sie beheben, auch wenn die Syntx stimmt. Ein Beispiel ist "nicht erreichbarer Code". Er ist zwar korrekt geschrieben, aber der Linter erkennt, dass da etwas nicht stimmt.
- Was ist JSON?
     - Die JavaScript Object Notation, kurz JSON, ist ein kompaktes Datenformat in einer einfach lesbaren Textform zum Zweck des Datenaustauschs zwischen Anwendungen.
- Wieso wurde JSON erstellt?
     - Es ist einfach für Menschen zu lesen und zu schreiben. Rechner können leichter parsen und generieren.
- Was sind die stärke und schwäche von JSON?
     - JSON ist sehr nützlich beim Entwickeln einer Webanwendung, bei der eine schnelle, kompakte und bequeme Serialisierung von Daten erforderlich ist,       jedoch ist es aufgrund seiner Flexibilität weniger geeignet als beispielsweise XML zum Übertragen von Daten zwischen getrennten Systemen oder zum       Speichern von Daten, die gelesen werden von Dritten.