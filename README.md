# BAxxxOS

**Ein universelles Entwicklungs-OS für Geräte, Maschinen und Anlagen.**

BAxxxOS bringt Entwicklung, Inbetriebnahme und Betrieb an einem Ort zusammen. Eine Werkstatt soll damit Geräte einrichten und aktualisieren können. Ein Veranstaltungsort soll seine Schaltstellen und Messwerte gemeinsam bedienen können. Ein Boot soll Instrumente und Energiedaten auf einer Oberfläche zusammenführen. Der gemeinsame Kern ist ein Host, der weiß, welche Geräte zur Anlage gehören und welche Aufgabe jedes Gerät hat.

## OneButtonFlash

Ein Host soll per Knopfdruck **alle erreichbaren, unterstützten ESP-Geräte** einer Anlage flashen können. Er ordnet jedem Gerät die Firmware zu, die zu seiner Hardware und Aufgabe passt. Fehlt eine passende Firmware, entwickelt eine **lokal laufende KI** sie aus dem Geräteprofil und der Aufgabenbeschreibung. Der Host baut und prüft das Ergebnis und spielt es nach erfolgreicher Prüfung auf die Zielgeräte.

Im Alltag heißt das etwa: Eine zusätzliche Schaltstelle kommt ins Gelände, ein Ersatzgerät übernimmt die Rolle eines ausgefallenen Knotens, oder eine ganze Gruppe erhält ein gemeinsames Update. Die Anlage kann je nach Einsatz lokal bedient oder von einer gemeinsamen Zentrale koordiniert werden. **OneButtonFlash mit lokaler KI ist das Zielbild der Plattform. Einzelne Anwendungen liegen bereits als Entwürfe oder Prototypen vor.**

## Projektfamilie

| Projekt | Anwendung |
| --- | --- |
| **BAxpiOS** | Host und Leitstelle. Von einem Ort aus Geräte einrichten, aktualisieren, gruppieren und ihren Status überblicken. |
| **BAipsOS** | Verteilte Anlagen im Veranstaltungsbetrieb. Licht, Schaltstellen, Szenen und Zustände eines Geländes lassen sich lokal an den Stationen und zentral in der Leitstelle bedienen. |
| **BAfsiOS** | Standortanwendung für Gastronomie und Veranstaltungsbetrieb am Wasser. Teams sollen Bereiche, Geräte und Betriebszustände eines Geländes im Blick behalten. |
| **BAbarOS** | Lokales Bedienpanel für die Bar. Licht und Schaltstellen für Gastraum, Wege und Eingänge lassen sich von einer Oberfläche aus überblicken und bedienen. |
| **BAmapOS / BAxMAP** | Kartenansicht für Geräte, Standorte und Zonen. Betreiber sehen, wo ein Gerät sitzt und welcher Bereich zu einem Status oder einer Meldung gehört. |
| **BAhidOS** | Gemeinsame Bedienoberflächen für kompakte Touchpanels und größere Leitstellen. Geeignet für lokale Schaltfunktionen, Szenen und Anlagenübersichten. |
| **BAledOS** | Lichtsteuerung und visuelles Feedback für Räume, Installationen und Veranstaltungen. Pegel, Zustände oder Szenen können über Licht sichtbar werden. |
| **BAenvOS** | Schallpegel und Umgebungsdaten für Veranstaltungsorte sichtbar machen. |
| **Besucherströme / RuView** | Forschungsanwendung für die Geländeübersicht. Sie soll zeigen, wo sich Besucherströme verdichten, damit das Betriebsteam Wege und Einlässe besser einschätzen kann. |
| **Restless Booth Controller** | Bedien- und Anzeigeprojekt für den DJ-Arbeitsplatz. Pegel und Betriebszustände sollen dort sichtbar sein, wo das Team sie braucht. |
| **BAmarOS** | Bootscockpit für Fahrtwerte, Position und Track, Motordaten und Bordfunktionen. |
| **FS-BAxOS** | Energieanzeige für mehrere Batterien. Ladezustand, Verbrauch und geschätzte Restlaufzeit lassen sich gemeinsam überblicken. |
| **[BAtruOS](https://github.com/bastelalex/BAtruOS)** | Diagnose und Retrofit für ältere Heizungssteuerungen. RetroControl beginnt mit der Trumatic E1800 und einem nachvollziehbaren Prüfablauf für Werkstätten. |

Weitere Anwendungen aus den Projektarbeiten sind eine **Werkstattzentrale** zur Gerätediagnose und ein **Gateway-Kit**, das vorhandene Router als lokale Stationen zum Einrichten und Aktualisieren von Geräten weiterverwendet. **Mobile Terminals** ergänzen die Plattform um Barcode- und Inventarerfassung, Check-ins und Statusmeldungen. **BAcarOS** lässt sich als Fahrzeugvariante für Instrumente und Diagnose ableiten, **BAgasOS** als breiterer Anwendungszweig für Service und Diagnose an Bestandsgeräten. **BAminOS, BAmidOS und BAmaxOS** sind bisher vor allem Namen im Baukasten. Eine mögliche Einteilung reicht vom einzelnen Bediengerät über eine kleine Anlage bis zur Leitstelle für mehrere Bereiche.

## Pilotpartner und Investoren

Ein erster Pilot kann an einem konkreten Gerätebestand zeigen, wie viel Aufwand beim Einrichten, Tauschen und Aktualisieren entsteht und wie viel davon ein gemeinsamer Host übernehmen kann. Dafür ist BAxxxOS offen für Gespräche mit Veranstaltungsbetrieben, Werkstätten, Gerätepartnern und Hardware-Investoren.

[Bastelalex auf GitHub](https://github.com/bastelalex) · [Über GitHub Kontakt aufnehmen](https://github.com/bastelalex/BAxxxOS/issues/new)

## English summary

BAxxxOS is a universal development OS for physical devices. A single host is intended to deploy firmware to supported ESP devices through OneButtonFlash. If suitable firmware is missing, a local AI is intended to create it, and the host builds, validates and deploys it. Applications include venue operations, marine dashboards, energy monitoring, workshop diagnostics and mobile field terminals.
