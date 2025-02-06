EdgeBeat Manifest (Alpha-Phase)

*EdgeBeat ist eine offene, serverlose SaaS-Plattform, die sich derzeit in der Alpha-Phase befindet. Dieses Manifest fasst die Schlüsselprinzipien, geplanten Schritte und Selbstverpflichtungen der EdgeBeat-Initiative zusammen, um der Community einen transparenten Überblick zu bieten.* 

## Bereitstellung und SaaS-Modelle

EdgeBeat wird als Cloud-Service (*Software as a Service*, SaaS) in verschiedenen Stufen angeboten. Eine **Community-Stufe**, ein **Enterprise-Angebot**:

- **Community-Stufe**: Eine offene, kostenfreie SaaS-Variante, die von der EdgeBeat-Community (bzw. Foundation) betrieben wird. Sie richtet sich an Community-Mitglieder, Einzelentwickler und Organisationen, die EdgeBeat ausprobieren oder gemeinschaftlich weiterentwickeln möchten. Dieses Modell bietet grundlegende Funktionen und geteilte Ressourcen ohne direkte Kosten, ermöglicht aber durch seine Offenheit wertvolles Feedback und Beiträge der Benutzer.  
- **Enterprise-Stufe**: Eine kommerzielle SaaS-Variante für Unternehmen und Institutionen mit höheren Ansprüchen. Enterprise-Tenants erhalten dedizierte Ressourcen, erweiterten Support und können EdgeBeat in großem Umfang produktiv einsetzen. Im Gegenzug sind sie über das EdgeBeat-Gebührenmodell verpflichtet, einen anteiligen Beitrag an die EdgeBeat Foundation zu leisten (siehe **Enterprise-Gebühr** unten), der sich aus ihrer Nutzung der Plattform ergibt.

## Lizenzierung

EdgeBeat steht unter der **Apache 2.0-Lizenz** und ist damit vollständig quelloffen (Open Source). Diese Lizenz gewährleistet, dass jeder die Software frei nutzen, ändern und verbreiten darf, solange die Lizenzbedingungen eingehalten werden. Durch die Wahl von Apache 2.0 unterstreichen wir unseren Anspruch, eine offene Community aufzubauen und breite Mitwirkung zu ermöglichen – ohne Einschränkungen beim Einsatz in unternehmerischen oder privaten Kontexten.

## Smart Contracts

Im EdgeBeat-Ökosystem kommen **Smart Contracts** zum Einsatz, um zentrale Komponenten und Abläufe in Code zu gießen und automatisiert durchzusetzen. Für die Hauptbereiche von EdgeBeat wurden folgende Smart Contracts definiert:

### EdgeBeat Core Smart Contract
Der Smart Contract für *EdgeBeat Core* legt die grundlegenden Regeln und Mechanismen der Plattform fest. Er definiert die Basisrichtlinien für Sicherheit, Ressourcennutzung und Orchestrierung von Funktionen im Kernsystem. Dieser Vertrag gewährleistet, dass alle Kern-Services von EdgeBeat die vorgesehenen Sicherheitsstandards einhalten und korrekt miteinander interagieren.

### EdgeBeat Agentic Smart Contract
Der *EdgeBeat Agentic* Smart Contract regelt das Verhalten intelligenter Agenten innerhalb der Plattform. Er stellt sicher, dass agentenbasierte Automatisierungen (z.B. autonome Workflows oder Entscheidungen, die von KI-Agenten getroffen werden) den vorgegebenen Richtlinien folgen. Gleichzeitig macht er diese Prozesse auditierbar, damit die Community nachvollziehen kann, welche Aktionen die Agenten durchführen und ob diese den Richtlinien entsprechen.

### EdgeBeat LLM Smart Contract
Der Smart Contract für *EdgeBeat LLM* (Large Language Model) bestimmt den Rahmen für den Einsatz von KI-Sprachmodellen innerhalb von EdgeBeat. Er sorgt dafür, dass die Integration von LLM-Funktionen verantwortungsbewusst erfolgt – z.B. indem die Nutzung von KI-Modellen protokolliert, Ausgaben überprüft und Richtlinien zur Vermeidung von Fehlentscheidungen oder Bias eingehalten werden. Dieser Vertrag schafft Vertrauen darin, dass KI-gestützte Komponenten sicher und nachvollziehbar eingebunden sind.

### EdgeBeat Tenant Smart Contract
Der *EdgeBeat Tenant* Smart Contract definiert die Bedingungen für die Nutzung der Plattform durch verschiedene Mandanten (**Tenants**). Er legt fest, wie Ressourcen in der Multi-Tenant-Umgebung isoliert und fair zugeteilt werden. Zudem enthält er Regelungen zu den Rechten und Pflichten von Enterprise-Tenants, inklusive der Verpflichtung zur Beitragszahlung an die Foundation gemäß Nutzungsumfang. Durch diesen Smart Contract wird sichergestellt, dass alle Tenants die Plattform gerecht und sicher gemeinsam nutzen.

## Offener Algorithmus für Enterprise-Gebühr

Für Enterprise-Nutzer (Tenants) gilt ein **offener, community-beschlossener Algorithmus** zur Berechnung einer Gebühr an die EdgeBeat Foundation. Dieses **Gebührenmodell** stellt sicher, dass die Nutzung der Plattform durch Unternehmen fair vergütet wird und zur Weiterentwicklung des Ökosystems beiträgt. Die Höhe der Gebühr für einen Enterprise-Tenant hängt von mehreren Faktoren ab:

- **Anzahl der genutzten Smart Contracts** – Je mehr EdgeBeat-Smart-Contracts ein Enterprise-Tenant einsetzt, desto größer sein Anteil an der Systemnutzung.
- **Nutzungszeitraum** – Die Dauer, über die ein Tenant die Plattform und Ressourcen in Anspruch nimmt (z.B. kontinuierlicher Betrieb von Funktionen über Monate hinweg).
- **Systemlast (Load)** – Die tatsächliche Last bzw. Ressourcenbeanspruchung, die durch den Tenant entsteht (etwa Umfang der verarbeiteten Daten oder Häufigkeit der Funktionsaufrufe).

Aus diesen Parametern ermittelt der Algorithmus eine anteilige Gebühr, die der Enterprise-Tenant an die Foundation entrichten muss. Der Algorithmus selbst ist **offen einsehbar** und wird von der Community mitgestaltet. Dadurch ist sichergestellt, dass das Modell transparent, fair und an aktuelle Gegebenheiten angepasst ist. Die Einnahmen aus diesen Gebühren fließen in die Finanzierung der gemeinsamen Infrastruktur und Weiterentwicklung von EdgeBeat zurück.

## Roadmap: Rollout in der Alpha-Phase

In der laufenden **Alpha-Phase** wird EdgeBeat schrittweise ausgebaut. Geplant sind mehrere Rollout-Stufen, um nach und nach alle Aspekte *als Code* umzusetzen und die verschiedenen EdgeBeat-Editionen sowie Entwicklerwerkzeuge bereitzustellen:

1. **Infrastruktur als Code (IaC)** – Bereitstellung der Basis-Infrastruktur von EdgeBeat als Code. Sowohl die Community- als auch die Enterprise-Stufe lassen sich dadurch reproduzierbar und automatisiert einrichten (z.B. mittels Terraform-Templates oder Ansible-Playbooks für die EdgeBeat-Kernkomponenten). Dieser Schritt legt das Fundament für konsistente Deployments der Plattform.
2. **Daten als Code (DaC)** – Einführung von *Data as Code*-Konzepten. Wichtige System- und Konfigurationsdaten werden versionierbar und deklarativ verwaltbar gemacht. Dies erlaubt es, Änderungen an Datenflüssen, Konfigurationen und Policies nachvollziehbar zu gestalten und zwischen Umgebungen (Community ↔ Enterprise) konsistent zu halten.
3. **Plattform als Code (PaC)** – Weiterentwicklung der Plattform-Definition als Code. Betriebsabläufe, Sicherheitsrichtlinien und Komponenten-Konfigurationen (z.B. für EdgeBeat-Tenant-Isolierung oder die LLM-Integration) werden in Code gegossen. Damit wird die gesamte EdgeBeat-Plattform – inklusive aller Module – mit wenigen Klicks oder Befehlen deploy- und updatebar. Dieses *Policy/Plattform as Code*-Paradigma erleichtert das Skalieren und die Wartung in beiden Editionen gleichermaßen.
4. **Alles als Code (EaC)** – Abschluss der Alpha-Phase unter dem Leitgedanken *"Everything as Code"*. Alle Aspekte – von Infrastruktur über Daten bis hin zu Betriebsprozessen – sind nun als Code formalisiert. Dies ermöglicht umfassende Automatisierung, Continuous Integration/Continuous Deployment (CI/CD) und einfache Reproduzierbarkeit für EdgeBeat. Parallel dazu werden die ersten **EdgeBeat SDKs** für gängige Programmiersprachen (z.B. Python, JavaScript, Go) veröffentlicht, um Entwicklern die Anbindung an EdgeBeat zu erleichtern und echten Multi-Language-Support sicherzustellen.

Jeder dieser Schritte wird der Community transparent kommuniziert, sodass Feedback frühzeitig einfließen kann. Nach Abschluss der Alpha-Phase wird EdgeBeat über einen vollständig als Code gesteuerten Stack verfügen, was den Weg für die Beta-Phase und darüber hinaus ebnet.

## Bekanntgabe über die OWASP German Chapter Mailingliste

Die offizielle Ankündigung von EdgeBeat erfolgte über die Mailingliste des OWASP German Chapter. Durch diese Bekanntgabe in der deutschsprachigen OWASP-Community möchten wir besonders Sicherheitsinteressierte und -experten ansprechen. OWASP-Mitglieder werden eingeladen, an der EdgeBeat-Community teilzunehmen, um gemeinsam an einer offenen und sicheren Plattform zu arbeiten. Wir erhoffen uns durch den direkten Draht zur OWASP-Community wertvolles Feedback, Beiträge und eine aktive Beteiligung – um EdgeBeat von Beginn an sicher und robust zu gestalten.

## Zeitplan & Finanzierung

Die bisherigen Fortschritte von EdgeBeat wurden wesentlich durch private Vorinvestitionen ermöglicht. Bisher sind rund **150.000 €** an privaten Mitteln in das Projekt geflossen, um die Entwicklung der Kernplattform überhaupt zu starten. 

Für die nächsten Phasen strebt das EdgeBeat-Team nun öffentliche Unterstützung an. Geplant ist die Einreichung von Förderanträgen sowohl beim Bund (deutsche Förderprogramme) als auch auf EU-Ebene. Ziel dieser Anträge ist es, Mittel für einen EU- und DACH-konformen, quelloffenen Proof-of-Concept zu erhalten. Konkret soll ein offenes Projekt unter Apache-2.0-Lizenz gefördert werden, das eine sichere *serverlose* SaaS-Architektur demonstriert. Mit einer erfolgreichen Förderung durch Bund und EU kann EdgeBeat seine Entwicklung beschleunigen und sicherstellen, dass die Plattform den hohen Datenschutz- und Sicherheitsstandards in Europa gerecht wird.

## Zukunft von SaaS

**SaaS ist tot – zumindest in der bisherigen Form.** EdgeBeat vertritt die Haltung, dass traditionelle monolithische SaaS-Lösungen an ihre Grenzen stoßen. Geschlossene, proprietäre Dienste bringen oftmals Nachteile wie Anbieter-Lock-in, mangelnde Transparenz und eingeschränkte Anpassbarkeit mit sich. Die Zukunft der Cloud-Dienste liegt unserer Ansicht nach in offenen, sicheren und widerstandsfähigen Architekturen.

Eine solche zukunftsfähige Architektur ist **serverlos**, verteilt und von Grund auf auf Sicherheit ausgelegt. Sie ermöglicht es, Dienste ohne fest zugewiesene Server dynamisch bereitzustellen, was Skalierbarkeit und Ausfallsicherheit erheblich verbessert. Zudem sollte sie **mehrere Programmiersprachen** und technologische Umgebungen nahtlos unterstützen, um ein breites Spektrum von Entwicklern und Anbietern einzubinden. Nur mit einer polyglotten, offenen Architektur können wir ein Ökosystem schaffen, das nicht von einzelnen Herstellern abhängig ist und sich agil an neue Anforderungen anpasst.

EdgeBeat sieht sich als Wegbereiter dieser nächsten Generation von Cloud-Diensten. Durch Offenheit, Community-Orientierung und technische Vielfalt wollen wir zeigen, dass eine *"SaaS ohne SaaS"*-Lösung möglich ist – eine Plattform, die die Vorteile von SaaS (kein Wartungsaufwand für Nutzer, schnelle Bereitstellung) bietet, dabei jedoch kein geschlossenes System eines einzelnen Anbieters ist, sondern gemeinschaftlich betrieben und weiterentwickelt wird.

## Offengelegte EdgeBeat Compute-Kapazitäten & Skalierungsplan

Transparenz bedeutet für uns auch, die aktuellen **Compute-Kapazitäten** offenzulegen, die der Community bereits jetzt zur Verfügung gestellt werden. Im Rahmen der Alpha-Phase stellt EdgeBeat folgende Ressourcen bereit:

- **CPU-Kerne**: 1000 (verteilt über mehrere Serverknoten für parallele Ausführung)  
- **Arbeitsspeicher**: 10 TB RAM (gesamter zugewiesener Speicher für die Ausführung von EdgeBeat-Funktionen)  
- **Datenspeicher**: 100 TB persistenter Speicher (für Daten, Logs und Smart-Contract-State)  
- **GPU**: 908GB VRAM (8x ada 48GB, 7x ada 20GB, 8x ampere 48GB)

Diese Ressourcen können von der Community für erste Tests, Proof-of-Concepts und zum Ausführen eigener EdgeBeat-Funktionen genutzt werden. 

Bis **Mitte April** planen wir eine **Verdoppelung** der vorhandenen Kapazitäten. Konkret sollen die Anzahl der CPU-Kerne und der verfügbare Arbeitsspeicher verdoppelt sowie der Speicherplatz entsprechend erweitert werden. Dieser Skalierungsplan stellt sicher, dass wachsende Nutzungsanforderungen auch während der laufenden Alpha-Phase erfüllt werden können. Wir werden die Community über den Fortschritt dieser Ausbau-Schritte auf dem Laufenden halten.

## Proof-of-Work-Algorithmus für Community Compute

EdgeBeat implementiert einen community-gesteuerten **Proof-of-Work-Algorithmus** für die gemeinsam genutzten Rechenressourcen (*Community Compute*). Dieser Algorithmus unterscheidet sich grundlegend von klassischen Proof-of-Work-Mechanismen, bei denen anonyme Rechenleistung der einzige Maßstab ist. Statt sinnloser Hash-Berechnungen setzt EdgeBeat auf **wertvolle Beiträge aus der Community als "Arbeitsnachweis"**.

So funktioniert es konkret:  
- **Community-Beitrag**: Community-Mitglieder leisten Arbeit, indem sie Code und Konfigurationen zu EdgeBeat beitragen – etwa Infrastruktur-als-Code-Skripte, Verbesserungen an Daten-Pipelines oder neue Policies als Code. Diese Beiträge werden als potenzieller "Arbeitsnachweis" gewertet.  
- **Review durch die Gemeinschaft**: Alle eingereichten Beiträge werden von der Community und den Maintainern (Projektbetreuern) überprüft. Nur qualitativ hochwertige und sichere Beiträge werden ins Projekt übernommen.  
- **Belohnung für Akzeptanz**: Wird ein Beitrag akzeptiert und ins Projekt übernommen, gilt er als **gültiger Arbeitsnachweis** für den Beitragenden und steigert dessen "Trust Score" (Reputation) innerhalb des Netzwerks.

Dieser Ansatz stellt sicher, dass diejenigen, die zum Erfolg von EdgeBeat aktiv beitragen, bevorzugt von den Community-Ressourcen profitieren. In Zukunft kann dieses Konzept genutzt werden, um z.B. Ressourcen-Allokationen zu priorisieren oder die Teilnahme an Governance-Entscheidungen zu gewichten. Der genaue Mechanismus wird gemeinsam mit der Community ausgearbeitet, bleibt aber stets transparent und für jeden nachvollziehbar.

## Vorträge & AMA-Sessions

Um den Wissensaustausch zu fördern und Interessierten einen tieferen Einblick in EdgeBeat zu geben, bieten wir an, **Vorträge** und **AMA-Sessions** (*Ask Me Anything*) zu veranstalten. Mitglieder des EdgeBeat-Teams stehen für Vortrags-Termine in der Region zur Verfügung – sei es bei lokalen Treffen oder Konferenzen in **Karlsruhe**, **Stuttgart** oder **Birkenfeld** – um das Projekt vorzustellen. 

Ebenso planen wir virtuelle AMA-Sessions, bei denen wir online Frage und Antwort stehen. Diese offenen Fragerunden erlauben es Community-Mitgliedern weltweit, direkt mit dem Team in Kontakt zu treten und mehr über EdgeBeat, seine Architektur und die Mitwirkungsmöglichkeiten zu erfahren. Wir ermutigen Interessierte, uns für die Organisation solcher Vorträge oder AMA-Termine anzusprechen.

## Transparenzverpflichtung

Als Community-Projekt legt EdgeBeat größten Wert auf **Transparenz** in allen Belangen. Wir verpflichten uns, die Entwicklung und den Betrieb der Plattform vollständig nachvollziehbar zu gestalten. Konkret bedeutet dies:

- **Offener Quellcode**: Sämtlicher Code von EdgeBeat ist frei zugänglich (z.B. auf GitHub) und steht unter Apache-2.0-Lizenz.  
- **Offene Entwicklung**: Entwicklungsfortschritt (Pläne, Meilensteine und Aufgaben) wird transparent kommuniziert und dokumentiert. Die Community kann den Status einsehen und Feedback geben.  
- **Offene Entscheidungsfindung**: Wichtige Entscheidungen über neue Features, Architektur und Richtlinien werden unter Einbindung der Community getroffen und protokolliert. Vorschläge und Diskussionen hierzu sind für alle offen nachvollziehbar (z.B. über öffentliche Diskussionen und Abstimmungen im Projekt-Repository).  
- **Transparente Finanzen**: Finanzielle Mittel, Ausgaben und Fördergelder werden offengelegt. Die Community erfährt, wofür Gelder eingesetzt werden und wie sich die Finanzierung des Projekts gestaltet.

Durch diese Maßnahmen wollen wir Vertrauen schaffen und sicherstellen, dass EdgeBeat **"von der Gemeinschaft, für die Gemeinschaft"** entwickelt wird. Jeder Interessierte soll sich zu jedem Zeitpunkt ein genaues Bild vom Projekt machen können, Fragen stellen und sich einbringen dürfen.

Wir freuen uns auf Feedback und darauf, EdgeBeat gemeinsam mit der Community voranzubringen.
