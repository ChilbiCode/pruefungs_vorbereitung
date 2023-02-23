[zurück](../README.md)

# IT-Systeme

## Inhaltsangabe

1. [Begriffe](#1-begriffe)
    1. [Datensicherungskonzepte](#datensicherungskonzepte)
    2. [Servicemodelle](#servicemodelle)
    3. [Boolesche Algebra & logische Schaltugnen](#boolesche-algebra--logische-schaltugnen)
2. [DIN VDE 100-410](#2-din-vde-100-410)
3. [Industrie 4.0](#3-industrie-40)


## 1. Begriffe

Begriff IT-System: <input type="text">
<details><summary>Lösung</summary>Funktionseinheit, die Daten verarbeiten kann.</details>  
<br>

### Datensicherungskonzepte
Abkürzung | Sicherungskonzept | Lösung | Wirkweise | Lösung
-|-|-|-|-
V S | <input type="text"> | <details><summary></summary>Vollsicherung</details>| <input type="text"> | <details><summary></summary>Vollsicherung: Bei einer Vollsicherung werden alle Daten eines Systems oder einer Anwendung gesichert. Es handelt sich also um eine vollständige Sicherung aller relevanten Daten. Vollsicherungen sind zeitaufwendig, da sie alle Daten sichern, aber sie stellen auch sicher, dass alle Daten wiederhergestellt werden können, falls das System oder die Anwendung ausfällt oder beschädigt wird.</details>
D S | <input type="text"> | <details><summary></summary>Differenzielle Sicherung</details>| <input type="text"> | <details><summary></summary>Bei der differenziellen Sicherung werden ebenfalls nur die Änderungen seit der letzten Vollsicherung gesichert. Im Gegensatz zur inkrementellen Sicherung werden jedoch alle Änderungen seit der letzten Vollsicherung in einer einzigen Sicherung gespeichert. Dies bedeutet, dass nur die Vollsicherung und die letzte differenzielle Sicherung zur Wiederherstellung benötigt werden.</details>
I S | <input type="text"> | <details><summary></summary>Inkrementelle Sicherung</details>| <input type="text"> | <details><summary></summary>Inkrementelle Sicherung: Bei der inkrementellen Sicherung werden nur die Änderungen seit der letzten Sicherung gesichert. Dies bedeutet, dass bei der Wiederherstellung alle inkrementellen Sicherungen seit der letzten Vollsicherung wiederhergestellt werden müssen, um alle benötigten Daten zu erhalten.</details>

Begriff Revisionssicherheit: <input type="text">
<details><summary>Lösung</summary>bezieht sich auf die Eigenschaft von Dokumenten oder Daten, die bei einer Revision oder Überprüfung in ihrer ursprünglichen Form erhalten bleiben und unveränderlich sind. Es bedeutet, dass die betreffenden Dokumente oder Daten zu einem späteren Zeitpunkt genau so wiederhergestellt und nachvollzogen werden können, wie sie ursprünglich erstellt wurden. Eine "revisionssichere" Aufbewahrung ist also eine sichere und unveränderliche Speicherung von Informationen, bei der keine Daten verloren gehen oder manipuliert werden können. Dies kann beispielsweise in den Bereichen Buchhaltung, Archivierung oder Dokumentenmanagement wichtig sein, um die Nachvollziehbarkeit und die rechtliche Verbindlichkeit von Dokumenten zu gewährleisten.</details>  
<br>


### Servicemodelle

Abkürzung | Sicherungskonzept | Lösung | Wirkweise | Lösung
-|-|-|-|-
I a a S | <input type="text"> | <details><summary></summary>Infrastructure as a Service</details>| <input type="text"> | <details><summary></summary>Mit IaaS können Unternehmen und Benutzer auf virtuelle Ressourcen wie Server, Speicher, Netzwerke und Betriebssysteme zugreifen, die von Cloud-Providern wie Amazon Web Services (AWS), Microsoft Azure und Google Cloud bereitgestellt werden. IaaS bietet eine flexible und skalierbare Infrastruktur, die Unternehmen nutzen können, um ihre Anwendungen und Workloads zu hosten, ohne in physische Hardware investieren zu müssen.</details>
S a a S | <input type="text"> | <details><summary></summary>Software as a Service</details>| <input type="text"> | <details><summary></summary> Bei SaaS-Modellen nutzen Unternehmen und Benutzer Software-Anwendungen, die von Cloud-Providern bereitgestellt werden, anstatt diese selbst zu hosten und zu warten. Diese Anwendungen können von E-Mail-Diensten wie Gmail und Microsoft Outlook bis hin zu CRM-Systemen wie Salesforce und Projektmanagement-Tools wie Trello reichen. Die Benutzer zahlen in der Regel eine monatliche oder jährliche Abonnementgebühr, um auf die Anwendung zuzugreifen.</details>
P a a S | <input type="text"> | <details><summary></summary>Platform as a Service</details>| <input type="text"> | <details><summary></summary>PaaS ermöglicht Entwicklern, Anwendungen zu erstellen und bereitzustellen, ohne sich um die zugrunde liegende Infrastruktur kümmern zu müssen. PaaS-Provider stellen Entwicklern eine Plattform zur Verfügung, auf der sie ihre Anwendungen erstellen und ausführen können. Die Plattform umfasst in der Regel Entwicklungstools, Datenbanken, Betriebssysteme und Middleware, die für die Bereitstellung von Anwendungen benötigt werden. PaaS kann Entwicklungsprozesse beschleunigen und es Entwicklern ermöglichen, sich auf die Anwendungslogik zu konzentrieren, anstatt sich um die zugrunde liegende Infrastruktur kümmern zu müssen.</details>

Infrastructure as a Service: todo  
Software as a Service: todo  
Platform as a Service: todo




### Boolesche Algebra & logische Schaltugnen

Bedingung | Symbol | A | B | Ergebnis
-|-|-:|-:|-:
Und | & ,$\wedge$ | 0 | 0 | 0
|||0|1|0
|||1|0|0
|||1|1|0
||
Oder | $ \geq1 $, $\vee$| 0 | 0 | 0
|||0|1|1
|||1|0|1
|||1|1|1
||
Nicht | $ 1 $ , $\neg$ | 1||0 
||| 0||1
||
Entweder Oder | $ =1 $ | 0 | 0 | 0
|||0|1|1
|||1|0|1
|||1|1|0




[zum Anfang](#it-systeme)

---

## 2. DIN VDE 100-410

Die DIN VDE 100-410 ist eine Norm des Deutschen Instituts für Normung (DIN) und der Verband der Elektrotechnik, Elektronik und Informationstechnik (VDE), die sich mit der Prüfung von elektrischen Anlagen und Geräten befasst. Die Norm beschreibt die Anforderungen und Verfahren für die elektrische Sicherheitsprüfung von elektrischen Geräten, Maschinen und Anlagen.

Die DIN VDE 100-410 gibt Anweisungen zur Messung von elektrischen Größen wie Spannung, Strom, Leistung und Widerstand sowie zur Beurteilung der Ergebnisse. Die Norm ist relevant für Elektrofachkräfte, die für die Sicherheitsprüfung von elektrischen Anlagen und Geräten verantwortlich sind.

Die DIN VDE 100-410 ist Teil einer Reihe von Normen, die sich mit der elektrischen Sicherheit befassen, und wird in Deutschland für die Einhaltung der geltenden Gesetze und Vorschriften für die elektrische Sicherheit verwendet.

Schutzart | Schutzmaßnahmen
-|-
Basisschutz | Der Basisschutz umfasst grundlegende Schutzmaßnahmen wie Schutzerdung und Schutzisolierung, die einen grundlegenden Schutz gegen elektrischen Schlag bieten.
Fehlerschutz |  Der Fehlerschutz bezieht sich auf Schutzmaßnahmen, die zum Schutz vor gefährlichen Fehlern in elektrischen Anlagen und Geräten dienen, wie zum Beispiel einem Fehlerstrom-Schutzschalter (FI-Schutzschalter). Dieser schaltet bei einem Fehlerstrom innerhalb von Millisekunden ab, um das Risiko eines elektrischen Schlags zu reduzieren.
Zusatzschutz | Der Zusatzschutz beinhaltet weitere Schutzmaßnahmen, die je nach Art der elektrischen Anlage oder des Geräts notwendig sein können, um einen ausreichenden Schutz gegen elektrischen Schlag zu gewährleisten. Beispiele für Zusatzschutzmaßnahmen sind der Schutz durch Schutzkleinspannung, die Verwendung von Abdeckungen und Abschirmungen oder die Verwendung von Schutzeinrichtungen wie Überspannungsschutzgeräten.


[zum Anfang](#it-systeme)
 
---

## 3. Industrie 4.0

Industrie 4.0 bezeichnet die vierte industrielle Revolution, die durch die fortschreitende Digitalisierung und Vernetzung von Produktions- und Fertigungsprozessen geprägt ist. Im Kern geht es darum, die klassische industrielle Produktion durch die Integration von IT-Technologien, Automatisierung und intelligenten Systemen zu transformieren, um eine höhere Flexibilität, Effizienz und Produktivität zu erreichen.

Die Industrie 4.0 beinhaltet die Verbindung von Maschinen, Systemen und Prozessen über digitale Technologien, wie zum Beispiel Cloud-Computing, Big Data-Analyse, künstliche Intelligenz, Cyber-Physische-Systeme und Internet der Dinge (IoT). Dadurch können Produktions- und Fertigungsprozesse effizienter und flexibler gestaltet werden, da diese digital vernetzten Systeme und Prozesse selbstorganisiert miteinander kommunizieren und kooperieren können.

Die Industrie 4.0 hat das Potenzial, die gesamte Wertschöpfungskette von der Produktentwicklung bis hin zur Auslieferung von Produkten zu revolutionieren. Durch die Einbindung von Kunden und Lieferanten in die digital vernetzten Systeme können auch neue Geschäftsmodelle und Produkte entstehen, die auf individuelle Kundenbedürfnisse und eine hohe Produktqualität ausgerichtet sind.

Die Industrie 4.0 wird als zukunftsweisender Ansatz angesehen, um wirtschaftliche Herausforderungen wie hohe Arbeitskosten, Fachkräftemangel und zunehmende Kundenanforderungen zu bewältigen und die Wettbewerbsfähigkeit von Unternehmen zu stärken.

[zum Anfang](#it-systeme)
 
---
