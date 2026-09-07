<p align="center">
  <a href="https://pize.ai/de">
    <img src="assets/pize-logo.svg" width="96" height="96" alt="Pize logo" />
  </a>
</p>

<h1 align="center">pize.ai</h1>

<p align="center"><strong>KI-gestützte Programmierung für wissenschaftliches Rechnen und statistische Analysen.</strong></p>
<p align="center">Daten verstehen. Analysen entwickeln. Ergebnisse prüfen.</p>

<p align="center">
  <a href="https://pize.ai/de">Website</a> &middot;
  <a href="https://pize.ai/docs">Dokumentation</a> &middot;
  <a href="https://pize.ai/download">Download</a>
</p>

<p align="center" dir="ltr">
  <a href="README.md">English</a> &middot;
  <a href="README.zh-CN.md">简体中文</a> &middot;
  <a href="README.de.md">Deutsch</a> &middot;
  <a href="README.ja.md">日本語</a> &middot;
  <a href="README.fr.md">Français</a><br />
  <a href="README.ar.md">العربية</a> &middot;
  <a href="README.es.md">Español</a> &middot;
  <a href="README.hi.md">हिन्दी</a> &middot;
  <a href="README.id.md">Bahasa Indonesia</a> &middot;
  <a href="README.ru.md">Русский</a>
</p>

---

## Für Forschung entwickelt, nicht nur für Codevervollständigung

**Pize ist ein KI-Programmierassistent für Forschende, die mit wissenschaftlichem Code und statistischen Daten arbeiten.** Er unterstützt dabei, Projekte zu verstehen, Analysen vorzubereiten, Code zu schreiben und auszuführen, Ausgaben und Diagramme zu betrachten und den nächsten Schritt anzupassen. Pize lässt sich in Pize Code, Positron, über die CLI oder das SDK nutzen.

Fehler entstehen oft schon vor der Modellierung: durch falsch erkannte Trennzeichen, fehlende Werte, die als Zahlen interpretiert werden, oder eine Beobachtung, die als Kopfzeile gilt. Deshalb beginnt Pize beim Verständnis der Datenstruktur statt bei Annahmen über den Dateiinhalt.

Dieses Repository ist die öffentliche Produkt- und Community-Seite von Pize. Es wird vom Gründer [@guopengnaivoc](https://github.com/guopengnaivoc) gepflegt.

## Was Pize bietet

| Funktion | Nutzen im Arbeitsablauf |
| --- | --- |
| **Datenbewusstes Einlesen** | Trennzeichen, Kopfzeilen, fehlende Werte und Spaltentypen anhand des Inhalts erkennen; Kommentare, Metadaten und komprimierte Tabellen berücksichtigen. |
| **Kontext für große Datensätze** | Bei überschrittenem Kontextbudget eine kompakte Datenkarte mit Schema, kleiner Vorschau und ausdrücklich geschätzter Zeilenzahl bereitstellen. |
| **Aktuelle R-/Python-Sitzung** | In Positron die fokussierte Sitzung untersuchen und Dataframes zusammenfassen. Nach Freigabe Code ausführen, Diagramme abrufen und anhand echter Ausgaben weiterarbeiten. |
| **Prüfbare Codeänderungen** | Änderungen über mehrere Dateien koordinieren, Diffs prüfen, Änderungen rückgängig machen und zu einem früheren Aufgabenprüfpunkt zurückkehren. |
| **Planung und Ausführung** | Zuerst das Projekt im Planungsmodus erkunden und ein Vorgehen abstimmen, dann mit Freigabe Code schreiben und Terminalbefehle ausführen. |
| **Projekt- und Browserkontext** | Dateien, Ordner, Probleme und URLs referenzieren; beim Debugging Browseraktionen, Screenshots und Protokolle nutzen. |
| **Wiederverwendbare Konventionen** | Projektregeln und Skills für statistische Definitionen, Diagrammkonventionen und Verzeichnisstrukturen anwenden. |

Bei Forschungsformaten wie Parquet, Arrow, RDS, HDF5, h5ad, NumPy, SPSS und Stata erkennt Pize das Format und unterstützt beim passenden Ladecode. Das bedeutet nicht, dass jedes Binärformat direkt in den Gesprächskontext dekodiert wird. Verhalten und Grenzen beschreibt die [Dokumentation zum Einlesen und zur Laufzeit](https://pize.ai/docs).

## In der gewohnten Umgebung arbeiten

| Oberfläche | Einsatz |
| --- | --- |
| **Pize Code** | Unterstützung im Editor, Projektkontext, prüfbare Änderungen und Terminalabläufe. |
| **Positron** | Derselbe Agent mit Zugriff auf die bereits fokussierte R- oder Python-Sitzung. |
| **CLI** | Pize über die Kommandozeile nutzen. |
| **SDK** | Den Agenten und seine datenorientierten Funktionen in eigene Programme und interne Werkzeuge einbetten. |

Die Verbindung zur laufenden Sitzung ist Positron-spezifisch. Nicht jede Oberfläche hat denselben Laufzeitzugriff. Installation und Einzelheiten stehen in der [offiziellen Dokumentation](https://pize.ai/docs).

## Modelle und angebundene Werkzeuge

Pize unterstützt Cloud- und lokale Modelle, darunter Anthropic, OpenAI, Google Gemini, DeepSeek, AWS Bedrock und OpenRouter sowie OpenAI-kompatible Endpunkte. Wähle Anbieter und Konfiguration passend zu deiner Forschungsumgebung.

**Das SDK bettet Pize ein; MCP verbindet Pize mit externen Werkzeugen.** Als MCP-Client kann Pize kompatible Server für Datenbanken, interne Systeme und Laborwerkzeuge anbinden. Die verfügbaren Aktionen hängen vom Server und den erteilten Berechtigungen ab.

## Erste Schritte

1. **Oberfläche auswählen.** Beginne auf der [offiziellen Downloadseite](https://pize.ai/download) und folge den Installationshinweisen für deine Umgebung.
2. **Modell konfigurieren.** Verbinde einen unterstützten Anbieter oder lokalen Endpunkt gemäß der Dokumentation.
3. **Forschungskontext bereitstellen.** Öffne das Projekt und füge relevante Skripte oder Daten hinzu. Fokussiere in Positron die Sitzung mit den zu analysierenden Daten.
4. **Planen, freigeben und iterieren.** Stimme das Vorgehen ab, prüfe vorgeschlagene Aktionen und betrachte Code, Ausgaben und Diagramme, bevor du fortfährst.

<details>
<summary><strong>Beispiele für Forschungsanfragen</strong></summary>

Diese Formulierungen sind Einstiegshilfen, keine unabhängig validierten Analyseergebnisse.

- „Untersuche Spalten, Datentypen und fehlende Werte dieses Datensatzes, bevor du eine Analyse vorschlägst.“
- „Erkläre diese R- oder Python-Pipeline und nenne die Annahmen, die ich prüfen sollte.“
- „Hilf mir, dieses Analyseskript zu überarbeiten, führe es nach Freigabe aus und erläutere die Diagnosegrafiken.“

</details>

Pize unterstützt den Arbeitsablauf, ersetzt aber kein wissenschaftliches Urteil. Prüfe Methodenannahmen und Ausgaben, bevor du dich auf Ergebnisse verlässt. Die Datenverarbeitung hängt von den konfigurierten Werkzeugen und Modelldiensten ab; beachte die [Datenschutzhinweise](https://pize.ai/privacy) und die Richtlinien deines Anbieters.

## Was hier öffentlich ist

Dieses Repository enthält Produktinformationen, Community-Hinweise und die eigenständige [interaktive Proteindarstellung](https://guopengnaivoc.github.io/pize.ai/). Die Darstellung ist eine visuelle Demonstration, kein Proteinvorhersagedienst und kein Beleg für validierte wissenschaftliche Ergebnisse. Die Datenquellen sind in den [Protein-Quellenangaben](assets/protein-CREDITS.md) dokumentiert.

**Der Quellcode der Pize-Kernanwendung wird in diesem Repository nicht veröffentlicht.** Die öffentliche Darstellung macht nicht das gesamte Produkt zu Open Source. Ausgewählte Werkzeuge, Beispiele und technische Notizen können später separat mit eigenen Angaben zu Umfang und Lizenz erscheinen. Aktuelle Software und Verfügbarkeit findest du auf der offiziellen Website.

## Gründer, Feedback und Zusammenarbeit

Pize wurde von [@guopengnaivoc](https://github.com/guopengnaivoc) gegründet und wird unter dem Namen **pize.ai** gepflegt. Die Website ist der Produkteinstieg; dieses Repository bündelt öffentliche Projektinformationen und Community-Feedback.

- **Produktfragen und Funktionswünsche:** Erstelle ein [GitHub Issue](https://github.com/guopengnaivoc/pize.ai/issues).
- **Hilfreiche Fehlerberichte:** Beschreibe Umgebung, Aufgabe, erwartetes und tatsächliches Verhalten sowie ein minimales Beispiel. Siehe die [Mitwirkungshinweise](CONTRIBUTING.md).
- **Zusammenarbeit, Laboreinsatz oder private Anliegen:** Wähle die passende E-Mail-Adresse unten.

Veröffentliche keine API-Schlüssel, Zugangsdaten, privaten Datensätze oder vertraulichen Forschungsergebnisse in öffentlichen Issues. Aktuelle Funktionen und Einrichtungshinweise stehen auf [pize.ai](https://pize.ai/de) und in der [Dokumentation](https://pize.ai/docs).

## Pize kontaktieren

Klicke auf eine Adresse, um dein E-Mail-Programm mit einem vorgeschlagenen Betreff zu öffnen. Die Adressen stammen von der [offiziellen Kontaktseite](https://pize.ai/contact).

| Kontakt | Anliegen | E-Mail |
| --- | --- | --- |
| **Allgemeine Anfragen** | Produktfragen, Medienanfragen und Informationen zu Veröffentlichungen. | [hello@pize.ai](mailto:hello@pize.ai?subject=Pize%20general%20inquiry) |
| **Produktkontakt** | Produktdemos, Fragen zur Einführung und Zusammenarbeit. | [contact@pize.ai](mailto:contact@pize.ai?subject=Pize%20product%20inquiry) |
| **Technischer Support** | Konto, Dokumentation, Datenschutz und Datenlöschungsanfragen. | [support@pize.ai](mailto:support@pize.ai?subject=Pize%20support%20request) |
| **Geschäftliche Partnerschaften** | Einkauf, Forschungskooperationen und geschäftliche Anfragen. | [business@pize.ai](mailto:business@pize.ai?subject=Pize%20business%20inquiry) |

