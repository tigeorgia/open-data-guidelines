Zehn Open Data Leitfäden - Transparency International Georgien
============

Dieses Dokument dient als Leitfaden um Leitern von Regierungsstellen, IT Managern und Webentwicklern bei der Erstellung von Open Data Webseiten zu helfen. Er soll jedoch nicht alle Situationen abdecken, da &#8212;&#8220;Daten&#8221; ein weites Feld sind, und einige Arten möglicherweise Methoden erfordern, die hier nicht erläutert sind, um vollständig offen zu sein. Ausserdem gibt es Themen, die hier nicht diskutiert werden, die aber Schlüsselkomponenten in der Entwicklung guter Webseiten sind, wie z.B. Barrierefreiheit.

Öffentliche Daten sind Daten, deren Veröffentlichung nicht aufgrund von Bedenken bzgl. Privatsphäre, Sicherheit oder anderen stichhaltigen Gründen beschränkt ist. Dieser Leitfaden geht nicht im Detail darauf ein, welche Informationen als öffentlich anzusehen sind. Generell gilt aber, dass Regierungsdaten als öffentlich angenommen werden können, solange es nicht einen durch internationales Gesetz legitimierten, spezifischen Grund gibt dessen Veröffentlichung zurückzuhalten und diese Entscheidung dem Öffentlichen Interesse dient. Wenn Daten legitimerweise zurückgehalten werden, sollten sie redaktionell bearbeitet und klar ausgezeichnet sein und die Restmenge zusammen mit einer Erklärung der Gründe für diese Bearbeitung veröffentlicht werden.

Open Data ist:


1. ##Vollständig
    Alle Daten bzgl. eines bestimmten öffentlichen Datensatzes sollten veröffentlicht werden, inklusive nicht-digitaler Archivdaten und Daten, die verwendet wurden, um Aggregate oder abgleitete Abbildildungen zu erzeugen.
    - Für langjährige Datensätze ist die Digitalisierung von papier-basierten Archiven oftmals eine schwierige Aufgabe. Idealerweise würden diese Daten verfügbar gemacht weden, aber angesichts limitierter Ressourcen sollte der Fokus darauf liegen, dass Systeme erstellt werden, die die Sammlung und Veröffentlichung von öffentlichen Daten in einem digitalen Format effizient ermöglicht. Falls möglich sollten neue digitale Systeme so entworfen werden, dass nicht-digitale Archivdaten während der Digitalisierung hinzugefügt werden können.
    - Aggregate und abgeleitete Abbildungen sollten zusammen mit den Quelldaten, die zu ihrer Erstellung geführt haben, angeboten werden, inklusive Erklärungen welche Methoden dazu genutzt wurden. Beispielsweise sollte eine Abbildung der Inflationsrate zusammen mit den Preisen für Warenkörbe, die zur Messung der Inflationsrate beigetragen haben, angeboten werden.

2. ##Primär
    Daten sollten an der Quelle gesammelt und mit dem Granularitätsniveau dieser Sammlung veröffentlicht werden.
    - Daten liegen bei der Sammlung möglicherweise nicht immer in einer nutzbaren Form vor (z.B. Sensordaten). In diesen Fällen ist die Verarbeitung nach der Sammlung zulässig. Diese Verarbeitung sollte aber in einem Datenformat resultieren, welches alle Möglichkeiten und die volle Granularität der originalen Datensammlung widerspiegelt. Daten sollten niemals verloren gehen.

3. ##Zeitnah
    Daten sind so schnell wie möglich zugänglich zu machen, um ihren Wert für die Öffentlichkeit zu maximieren.
    - Es gibt keinen Zeitraum, der für alle Datentypen gilt, aber in vielen Fällen wird ein gut entworfenes System die Daten in Echtzeit, oder beinahe, veröffentlichen. Deshalb sollten Informationen so bald wie möglich zugänglich gemacht werden.
    - Aktualisierungen sollten leicht aus dem grösseren Datensatz heraus zu identifizieren sein, durch Mechanismen wie RSS feeds, Suchfunktionen, die nach Datum filtern können und Archive, die Schnappschüsse der Datensätze in regelmässig gemachten Abständen enthalten. Eine erfolgreiche Webseite wird vermutlich eine Kombination dieser Techniken verwenden.

4. ##Verfügbarkeit
    Die Daten sind für soviele Nutzer wie möglich zugänglich und für die grösstmögliche Menge an Verwendungszwecken.
    - Es sollte einfach sein, die Daten miteinander digital zu teilen. Jede veröffentlichte Seite und jedes veröffentlichte Dokument sollte einen einzigartigen und einfach zu erhaltenen URI (URL) zugewiesen bekommen, der per eMail oder sozialen Netzwerken verteilt werden kann. Webentwicklungswerkzeuge wie Cookies, Flash und AJAX/AHAH sollten nicht benutzt werden, um den Ort der Daten zu verschleiern oder das Teilen direkter Links zu erschweren.
    - URIs sollten in einem für Menschen freundliches Format vorliegen, z.B. &quot;www.domain.gov.ge/data/ministry/justice/complaints/2009/10/11/complaint.html&quot; nicht &quot;www.domain.gov.ge/data.php?lang=GEO&search_code=15&search_str=10,11,2009&type=4&min=01A&quot; .
    - Vollständiger Zugang zu den Daten sollte niemals eine Registrierung oder Bezahlung voraussetzen.
    - Das Herunterladen grosser Datenmengen sollte via Protokolle wie FTP oder rsync ermöglicht werden.
    - Idealerweise ermögicht eine gut dokumentierte Programmierschnittstelle (API) den automatisierten Zugang zu den Daten.

5. ##Maschinenlesbarkeit
    Die Daten sind in Format und Struktur gespeichert, die das automatische Verarbeiten zulassen.
    - Maschinenlesbarkeit sollte nicht die Lesbarkeit für Menschen ersetzen; beide Formate sollten vorhanden sein (z.B. eine Transkription einer Rede sollte zusammen mit dessen Aufzeichnung ausgeliefert werden).
    - Daten sollten niemals nur in Form von gescannten Bildern zugänglich gemacht werden. Gescannte Bilder können der beste Weg sein, bestimmte Dokumente zu präsentieren, z.B. Dokumente, die ein Siegel oder eine Signatur tragen, aber sie sollten immer von einer maschinenlesbaren Repräsentation des restlichen Dokumenteninhalts begleitet werden.
    - Daten sollten niemals in nicht-Unicode Schriftarten wie AcadNusx oder LitNusx gespeichert werden.
    - Daten sollten in einem einfach zu verarbeitenden Format präsentiert werden, wie z.B. CSV, JSON oder XML.
    - In jedem Fall sollte die Bedeutung der Datenfelder gut dokumentiert und diese Dokumentation zusammen mit den Daten ausgeliefert werden.

6. ##Nicht-proprietär
    Die Daten sind in einem offenen Format verfügbar, welches nicht von nur einer Entität kontrolliert wird. Damit kann sichergestellt werden, dass Computerprogramme, die diese Daten verarbeiten können, immer verfügbar sein werden.
    - Ein offenes Format ist eines, welches in keinem Land unter der Verwertung geistigen Eigentums steht und für welches Dokumente, die die Struktur des Formats erklären, frei verfügbar sind. HTML und XML sind Beispiele für offene Formate.
    - Einfache Formate und Formate, die von zahlreichen Programmen unterstützt werden, sind vorzuziehen. Formate wie z.B. XML und JSON sollten gegenüber Formaten wie PDF oder OOXML bevorzugt werden (OOXML sind üblicherweise MS Office-Formate wie .docx, .pptx und .xlsx).

7. ##Frei verwendbar
    Der Schutz durch geistige Eigentumsrechte, wie Urheberrecht oder Warenzeichen, wird nicht benutzt, um potentielle Nutzer oder Nutzungen der Daten einzuschränken.
    - Daten sollten frei für jegliche Verwendung sein, inklusive kommerzieller Nutzung ohne Einschränkungen.
    - Auch wenn das Gesetz klarstellt, dass öffentlichte Regierungsdaten frei verwendet werden können, sollte eine Notiz diesbezüglich in jedem veröffentlichten Datensatz enthalten sein.

8. ##Nachprüfbar
    Jede öffentliche oder private Körperschaft sollte eine Person abstellen, die auf Fragen und Beschwerden über die Daten eingeht, und die Kontaktdaten dieser Person sollten in den Daten enthalten sein.

9. ##Auffindbar
    Die Daten müssen von denen gefunden werden können, die nach ihnen suchen; sie müssen in den entsprechenden Katalogen enthalten sein und Webseiten sollten für Suchmaschinen zugänglich sein.
    - Idealerweise sollten alle Regierungsstellen einen einheitlichen Weg finden ihre Daten online zu stellen, so dass Nutzer die Daten jeglicher Stelle auf deren Webseite schnell auffinden können.
    - Die Stellen sollten sicherstellen, dass die Auflistungen auf Portalwebseiten der Regierung korrekt und aktuell sind.
    - Die Stellen sollten umfangreiche Sitemaps erzeugen und bei allen grossen Suchmaschinen eintragen.

10. ##Permanenz
    Da Daten altern, sollten sie auf eine Art und Weise archiviert werden, die obige Kriterien erfüllt.

Dieser Leitfaden wurde auf Basis von Leitfäden der Sunlight Foundation, Access-Info Europe, OpenGovData.org und anderen erstellt und angepasst. Dieses Dokument und dessen Inhalt sind nach Creative-Commons lizensiert und darf frei wiederverwendet, verändert und weiter verteilt werden. Jegliches Entfernen vom oder Hinzufügen zum Text dieses Leitfadens sollte dem Autor dieser Änderungen zugeschrieben werden und nicht Transparency International Georgien oder Transparency International.


<div>
<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.de"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Zehn Open Data Leitfäden</span> von <a xmlns:cc="http://creativecommons.org/ns#" href="http://transparency.ge" property="cc:attributionName" rel="cc:attributionURL">Transparency International Georgien</a> ist lizensiert unter einer <a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.de">Creative Commons Namensnennung 3.0 Unported Lizenz</a>.<br />Basierend auf Arbeit von <a xmlns:dct="http://purl.org/dc/terms/" href="http://transparency.ge/en/ten-open-data-guidelines" rel="dct:source">transparency.ge</a>.<br />Genehmigungen ausserhalb dieser Lizenz möglich auf <a xmlns:cc="http://creativecommons.org/ns#" href="http://transparency.ge/en/ten-open-data-guidelines" rel="cc:morePermissions">http://transparency.ge/en/ten-open-data-guidelines</a>.</div>

Die Kontaktperson für dieses Dokument ist [Sebastian Henschel](mailto:sebastian@transparency.ge)

Letzte Änderung: 20. März 2012
