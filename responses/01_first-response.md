# Willkommen

In diesem Kurs könnt ihr die Inhalte meiner mySession "Actions for Continuous Integration" noch einmal selber ausprobieren. **Continuous Integration**, oder **CI**,kann dein Projekt auf ein neues Level heben und verändert die Art Software zu entwickeln und Live zu stellen.
Aber was genau ist dieses ``Continuous Integration``und brauche ich das wirklich in meinem Projekt?

### Was ist CI und wass geht mich das jetzt an?

<p align="center">
  <img alt="a gear and a loop, representing continuous integration" src="https://github.com/christianherweg0807/lab-starter/blob/map-events/img/pngkey.com-cycle-icon-png-4532037.png">
</p>

Das Ziel von [CI](https://en.wikipedia.org/wiki/Continuous_integration) ist die Steigerung der Softwarequalität. Spätestens seit das Konzept der permanenten Integration von Kent Beck im Rahmen von Extreme Programming populär gemacht wurde, ist der Begriff der kontinuierlichen Integration an sich bekannt, für die erfolgreiche Einführung müssen allerdings einige Grundsätze [vgl. ["Continuous Integration"](http://www.martinfowler.com/articles/continuousIntegration.html) FOWLER, Martin] befolgt werden:

Gemeinsame Codebasis
Automatisierter Build
Häufige Integration in den Hauptbranch
Kurze Testzyklen
Automatisiertes Reporting
Automatisiertes Deployment in die Produktion
[...]
    
CI Tools wie [Github Actions](https://docs.github.com/en/actions) helfen uns dabei viele der daraus resultierenden Aufgaben zu automatisieren. Actions kann Builds und Tests laufen lassen. Die Ergebnisse werden wiederum in dem betreffenden Pull Request angezeigt. Es ist sehr sinnvoll alle Interaktionen Rund die Software an einm Ort sattfinden zu lassen und die Ergebnisse aucch dort zu speichern. Dadurch verringert sich die Kontextwechsel für die Entwickler und wir erhöhen die Nachvollziehbarkeit unsere Tests. Das Ziel sind weniger Bugs in Produktion und schnelles Feedback wärend der Entwicklung.

Let´s go: 

## Kapitel 1: starter-workflows ... Ein guter Anfang

<img alt="icon of a bug in a browser window" align="left" width="120" height="120" src="https://github.com/christianherweg0807/lab-starter/blob/map-events/img/Bug.png">
In diesem Reepository ist ein Bug versteckt.
Ziel dieses Schrittes ist Continuous Integration (CI) zu benutzen um automatisiertes Testen zu ermöglichen. Dies erleichtert die Suche und hilft Scenarien wie diese zu vermeiden.

Zu allererst müssen wir CI grundlegend in diesem Repository einrichten. Am einfachsten geht dies über die vorgefertigten Templates, die github uns bereitstellt. Diese sind nach Programmiersprache oder Framework gegliedert. Die Codebasis dieses Projektes ist in Node.js geschrieben. Also los:

### :keyboard: Aufgabe: Erzeuge einen Pull Request mit einem Workflow Template

1. Navigiere zum [Actions tab]({{ actionsUrl }}).
2. Wähle das Template Node.js Workflow aus.
3. Commite den Workflow in einen neuen Branch.
4. Erzeuge einen Pull Request mit dem Titel **CI for Node**.

Ich werde an den Pull Reequest kommentieren, sobald er angelegt worden ist.

---
