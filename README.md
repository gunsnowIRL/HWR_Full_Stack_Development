# 01: PraFi - Praktikumsfinder
Projekt im Fach "Full-Stack Web Development" Wi-Inf-M09-F02-WiSe-2026-70027 WiSe 2026/27
| Key | Value |
|---|---|
|*Status*| work in progress
|*Updated*:| 27.10.2026

### Target User

| Gruppe | Problem |
|---|---|
| **Studierende der HWR Berlin** | Keine effiziente Übersicht über ansprechende und gleichzeitig von der Hochschule anerkannte Praktikumsangebote |
| **Unternehmen** | Geringe Sichtbarkeit bei Studierenden, viele unqualifizierte Bewerbungen, aufwendige Vorauswahl |

Die **Praktikumsstelle der HWR** ist als Stakeholder beteiligt, nutzt die Anwendung aber  nicht selbst.

### Problemstellung

**Wie können wir die Praktikumssuche und -vermittlung durch eine Web-App Lösung sowohl für die Studierende, als auch für die Unternhmen möglichst trnasparent und weffizient gestalten, damit passende Bewerber und qualifizierte Praktikumsplätze besser zusammenfinden?**

Die Suche nach einem passenden Praktikumsplatz ist heutzutage für viele Studierende schwierig. Die Gründe sind hierbei unterschiedlich:

- attraktive Stellen bei bekannten Unternehmen werden in der Regel schnell besetzt
- Studierende wissen oft nicht genau, welche Richtung sie einschlagen wollen
- Angaben zu Gehalt, Ort und Aufgaben sind über viele Portale verstreut und schwer vergleichbar
- Es ist unklar, ob die Hochschule eine Stelle als Pflichtpraktikum überhaupt anerkennt

Diese Gründe können die Praktikumssuche für Studierende unnötig erschweren und überfordern. Außerdem ist die "GO Praktikum" Plattform der HWR nicht übersichtlich genug, um das Interesse der Studierenden zu wecken. Daraus ergibt sich, dass die Praktikumssuche für viele Studierende sehr chaotisch abläuft und sich sogar über mehrere Monate hinzieht, manchmal erfolglos.

Auf der anderen Seite stehen jedoch die Unternehmen, die oft das Problem haben, die Praktikumsplätze zu besetzen. Obwohl sich viele Kandidaten auf eine Praktikumsstelle bewerben, können die Unternehmen nur schwer qualifizierte Kandidierende finden. Dadurch empfinden die Unternehmen regelmäßig das Problem der geringen Sichtabrkeit bei den Studierenden und eine aufwendige Vorauswahl.

Die Studierende und die Unternehmen benötigen also eine zentralisierte Plattform, wellche sie zusammenbringt. Das Ziel soll es sein, den Studierenden eine Möglichkeit einer einfacheren und effizienteren Praktikumssuche zu geben und den Unternehmen zu helfen, die Praktikumsstellen schnellstmöglich mit qualifizierten Kräften zu besetzen.

### Unser Ziel

Unser Ziel ist es eine **Praktikumsplattform für die HWR Berlin** zu entwickeln, die Unternehmen und Studierende zusammenbringt und die obengenannte Probleme löst. Die Plattform selbst bietet keine Praktika an. Ihr Wert entsteht durch die Vermittlung zwischen den Gruppen: Je mehr geprüfte Unternehmen Stellen anbieten, desto attraktiver ist sie für Studierende, und je mehr Studierende sie nutzen, desto interessanter ist sie für Unternehmen.

## Entscheidungen
Durch den Vorschag von [Hannes] (https://github.com/gunsnowIRL) haben wir uns kollektiv dazu entschieden, dass die Prozesse des Praktikumsbüros der HWR, wie z. B. die Genehmigung von Praktika,  nicht in der Plattform abgebildet werden.
### Funktionen

- **Stellenbörse:** Unternehmen veröffentlichen Praktikumsstellen mit Position, Gehalt, Ort, Aufgabenbeschreibung, Anforderungen und ggf. weiteren Angaben.
- **Such- und Filterfunktion:** Studierende selektieren selbstständig nach eigenen Präferenzen passende Stellen zentral an einem Ort.
- **Geprüfte Praktikumsstellen:** Die Praktikumsstelle der HWR prüft die Angebote. Studierende sehen dadurch direkt, welche Stellen von der Hochschule anerkannt sind.
- **Zugang nur für Hochschulangehörige:** Studierende registrieren sich ausschließlich mit ihrer Uni-Mail und geben ihren Studiengang als Pflichtangabe an. 
- **Bewertung durch Studierende:** Nach Abschluss eines Praktikums können Studierende das Unternehmen bewerten. Gut bewertete Unternehmen erhalten die Auszeichnung „Von Studierenden empfohlen“.
- **Schwarzes Brett (optional):** Studierende können eigene Gesuche veröffentlichen, auf die Unternehmen reagieren können.

### UI-Skizze:

### Happy-Path