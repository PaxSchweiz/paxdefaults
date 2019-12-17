# Pax Softwareentwicklung

## Vorlagen für die Software Entwicklung
Dies beinhaltet Lizenz, Header, Copyright

### Lizenz
Dies ist abhängig von der Nutzung und der Vereinbarung mit Pax. Grundsätzlich ist sämtlicher Quelltext bestandteil von einer Pax Lizenz. Als Open Source wird eine gängige Open Source Lizenz verwendet wie Apache License. Jedes "public" Repository hat eine Lizenz.

### Header
Ein Header kommt ganz an Anfang jeder Quelltextdatei und die Vorlagen umfassen verschiedene Programmiersprachen. Der Header soll kurz eine Aussage machen über den Zweck, Inhalt, Funktionsumfang.

### Code Standard
Falls nichts anderes vorgegeben, halten wir uns an gängige Code Conventions:
* camelCase für sämtliche Namen
* Abkürzungen zu vermeiden und aussagekräftige Namen verwenden
* Kommentare mit "markup" versehen und sinnvoll die Funktionalität zu beschreiben (wie zB. Java Doc)
* Keine "Tab" intends, sondern mit white space, idealerweise 2 white spaces intends
* Unix LF, keine Windows CRLF! Gerade bei Unix kann dies zu Fehlern führen da gewisse Intepreter (wie eine shell) Fehler auswerfen
* UTF-8 - es muss sichergestellt sein, dass der charset UTF-8 ist, java und zum Teil andere compiler werfen sonst Fehler aus
* Generell ist "Clean Code" zu befolgen

## Dokumentation
Grundsätzlich so viel Dokumentation innerhalb des Repository mit den Möglichkeiten von Markdown oder HTML.

Ein Teil der Dokumentation kann auch im internen Netz gehalten werden in unserem Wiki.

## Docker
Die Docker Container basieren auf alpine (Alpine Linux) oder Debian Slim. Centos dient als open source Ersatz für rhel.

Weitergehende Container wie python oder nodejs müssen diesem Grundsatz entsprechen.

Die Quelle sind offizielle Images im Docker Hub.