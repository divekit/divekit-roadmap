---
type: goal
acronym: fehlerFalscheKonfig
responsible:
    - jsp
title: Fehlerhafte Konfiguration von Umgebungseinstellungen
source:
    - [Workshop, Workshop 6-3-5-No.2, Schwerpunkt Technik No.1]
belongsTo: fehler
history:
    v1:
        date: 2021-07-05
        comment: initially created
    v2:
        date: 2021-07-24
        comment: fix todo
todo:
---

## Beschreibung

Bei einer Änderung der Umgebungseinstellungen (pom.xml) soll eine aussagekräftige Fehlermeldung seitens des Servers erscheinen. Ebenfalls soll es ein Tutorial zum Zurücksetzen geben.

## Begründung

Durch eine versehentliche Änderung der Umgebungseinstellungen (pom.xml) wird die Testseite nicht mehr dargestellt. Es wird aber auch keine brauchbare Fehlermeldung angezeigt. Somit weiß der Nutzer nicht, was der Fehler sein kann.
