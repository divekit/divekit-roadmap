---
type: review
acronym: reviewBrandingUseCase
responsible:
    - ngi
reviewers:
    - fgr
    - ama
referencedType: useCase
referencedAcronym: branding
referencedCommit: bedb3775be4b5c65030268fa00ef43d63de30367
title: Review zum Use Case Branding
history:
    v1:
        date: 2021-07-28
        comment: initially created
todo:
---

## Review-Protokoll

| Referenz | Reviewer-Kommentar | Autor-Kommentar |
|------------|------------------|-----------------|
| Hauptszenario, Satz 1 und Trigger| “Der externe Anwender möchte das Design des Systems an seine Hochschule anpassen“ – ist eher Trigger als Teil des Szenarios | Stimmt, andersrum würde es besser passen, wird ausgetauscht |
| Precondition | der externe Anwender muss als Verwalter im System eingeloggt sein” – ist das nicht Teil des Szenarios, dass er sich einloggt? | Nein, der Loginprozess ist ein eigenständiger Usecase, dieser hier baut nur darauf auf und beinhaltet den Login daher nicht |
| Überschrift für Ausnahmeszenario | rausnehmen, da es keins gibt | na klar |
| Alternativszenario 3d | müsste Icons statt barrierearme Ansicht heißen | Oops, Copy+Paste Fehler. Wird gefixt. |
| Durchgängig in der Beschreibung der Szenarien (4, 5, 4a, 4b) | Stylesheets können nicht von jedem bedient werden und eine Anpassungsmöglichkeit mit implementierter Oberfläche wäre ja vielleicht eine sinnvolle Alternative. | Stimmt, daher wird das Wort Stylesheet durch Einstellungsmöglichkeiten ersetzt und die technische Umsetzung aus dem Use Case rauszuhalten |