# Apple Human Interface Guidelines für iOS
Human Interface Guidelines dienen Entwicklern und Designern als **Leitfaden zur Erstellung einer benutzerfreudlichen und intuitiven Applikation**. Die meisten dieser Guidelines haben zudem die Funktion den Apps einer Anwendungsumgebung einen einheitlichen "Look and Feel" zu geben. Dies bedeutet, dass sowohl das visuelle Design als auch das Verhalten der Anwendungenen konsistent sein sollte.  Die Nutzung dieser Guidelines ist keine Pflicht, jedoch behält Apple es sich vor Apps ,die schwer gegen die Design-Philosophie verstoßen und grundlegende Elemente entgegen ihres Sinnes nutzen, nicht für den Store freizugeben.

Dieses Dokument gibt ihnen einen **Überblick** der wichtigsten Inhalte.

Die gesamten Guidelines für iOS-Applikationen können Sie [hier](https://developer.apple.com/ios/human-interface-guidelines/overview/themes/) in Englisch finden. Zu jedem Thema wird ein Link zum zuhörigen Kapitel der Guidelines, welche weitere Informationen enthalten, bereitgestellt. 
## Grundlagen
Apple definiert drei Design-Philosophien, die den Guidelines als Grundlage dienen:
* **Klarheit.** Das Design sollte die Funktionalität der App unterstützen. Es ist subtil und vermittelt Interaktivität. 
* **Achtung.** Der Inhalt der App steht im Vordergrund, nicht das Design. Es hilft beim Verstehen und Interagieren.
* **Tiefe.** Das Navigieren durch die App vermittelt ein Gefühl von Tiefe. Der Nutzer "endeckt" die Anwendung.

[Weiterführende Informationen](https://developer.apple.com/ios/human-interface-guidelines/overview/themes/)
## Aufbau der App
Der Nutzer sollte beim **Starten der App** ([Link](https://developer.apple.com/ios/human-interface-guidelines/app-architecture/onboarding/)) schnellstmöglich mit dieser interagieren können. Tutorials sollten minimal sein und nur einmal angezeigt werden. Die App sollte immer in dem Zustand starten, in dem der Nutzer sie zuletzt beendet hat.  

Um eine intuitive **Navigation** ([Link](https://developer.apple.com/ios/human-interface-guidelines/app-architecture/navigation/)) zu ermöglichen muss dem Nutzer jederzeit klar sein, wo innerhalb der App er sich befindet und wie er sein nächstes Ziel erreicht. Apple empfiehlt die Nutzung seiner Standardnavigationselemente, da diese den meisten Nutzern bereits bekannt sind.

**Berechtigungen** ([Link](https://developer.apple.com/ios/human-interface-guidelines/app-architecture/requesting-permission/)), wie den Zugriff auf Kontakte oder die Kamera, sollten zu dem Zeitpukt erfragt werden, in dem sie benötigt werden. Dem Nutzer sollte innerhalb der Berechtigungsanfrage präzise erklärt werden, warum eine Berechtigung benötigt wird.


**Einstellungen** ([Link](https://developer.apple.com/ios/human-interface-guidelines/app-architecture/settings/)) sollten nach Möglichkeit so gewählt werden, dass die meisten Nutzer die App direkt benutzen können. Werden Informationen benötigt, sollte zunächst versucht werden, diese über das System zu erlangen. Einstellungen, die häufig geändert werden müssen, sollten für den Nutzer schnell erreichbar sein.

Beim **Laden von Daten** ([Link](https://developer.apple.com/ios/human-interface-guidelines/app-architecture/loading/)) sollte dem Benutzer mittels eines Spinners verdeutlicht werden, dass die App noch aktiv ist, wenn möglich 
sollte der Fortschritt angezeigt werden. Ladezeiten eigenen sich zum Anzeigen von Tipps oder Informationen. 

## Benutzerinteraktion
Ist eine **Authentisierung** ([Link](https://developer.apple.com/ios/human-interface-guidelines/user-interaction/authentication/)) notwendig, sollte diese so spät wie möglich gefordert werden. So gibt man dem Nutzer Zeit gefallen an der App zu finden. Die Nutzung von FaceID oder TouchID vereinfacht hierbei die Anmeldung.

Bei einer **Dateneingabe** ([Link](https://developer.apple.com/ios/human-interface-guidelines/user-interaction/data-entry/)) sollte der Nutzer durch die Bereitstellung von Auswahlmöglichkeiten und Standardwerten unterstützt werden. Eingaben sollten direkt geprüft und der Nutzer sollte nur fortfahren können, wenn alle Pflichteingaben erfolgt und validiert sind.

**Drag and Drop** ([Link](https://developer.apple.com/ios/human-interface-guidelines/user-interaction/drag-and-drop/)) ist ein intuitiver Weg Inhalte einer App zu verschieben und zu kopieren. Beim Umherziehen sollte das gewählte Element als transparente Version von sich selbst dargestellt werden. Der Nutzer sollte eine dynamische Vorschau des Ergebnis eines Drops erhalten. Eine einfache Implementierung erreicht man durch die Nutzung der Standardelemente `Text View` und `Text Field`.  

Elemente sollten **Feedback** ([Link](https://developer.apple.com/ios/human-interface-guidelines/user-interaction/feedback/)) in Form von Statusinformationen bereitstellen. Ein Nutzer, der mit der App interagiert, sollte haptisches Feedback zu seinen Aktionen erhalten. Apple stellt hierfür standardisiertes Feedback für unterschiedliche Situationen zur Verfügung.

**Gesten** ([Link](https://developer.apple.com/ios/human-interface-guidelines/user-interaction/gestures/)) sind die primäre Art mit einer App zu interagieren. Die Standardgesten (Tap, Swipe, usw.) sollten nur für ihre vordefinierten Zwecke eingesetzt werden. 
### Steuerelemente
Apple stellt mehrere Designs für **Buttons** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/buttons/)) bereit, System Buttons bieten die meisten Anwendungsmöglichkeiten. Kurze Verben im Titel machen es Nutzern hierbei leicht verständlich, welche Folgen das Drücken eines solchen Buttons hat. 

**Labels** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/labels/))sind die einfachste Form statischen Text auszugeben. Dieser sollte möglichst kurz und gut lesbar sein und sich dynamisch an die Textgröße des Systems anpassen. Auch sollten Aspekte der erleichterten Bedinung in Betracht gezogen werden.

**Textfelder** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/text-fields/)) ermöglichen dem Benutzer eine Dateneingabe. Mittels eines Platzhalters und/oder eines Bildes am linken Feldrand kann ein Benutzer erkennen, welche Art Daten erforderlich sind. Für sensible Daten sollte immer ein gesichertes Textfeld bereitgestellt werden. 

Ein **Picker** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/pickers/)) ermöglicht es Nutzern schnell aus einer Menge an bereitgestellten Werten den gewünschten auszuwählen. Die Daten sollten hierbei vorhersehbar und logisch angeordnet werden. Apple stellte standardmäßig einen Date Picker zur Verfügung.

Weitere Elemente, die es Nutzern ermöglichen aus vorgegebenen Werten auszuwählen sind **Slider** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/sliders/)) über die Werte zwischen einem Minimal- und einem Maximalwert ausgewählt werden können, **Stepper** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/steppers/)), die es ermöglichen Werte inkrementell anzupassen und **Switches** ([Link](https://developer.apple.com/ios/human-interface-guidelines/controls/switches/)), bei denen zwischen an und aus gewählt werden kann. Bei allen diesen Elementen ist es wichtig, dem Nutzer bewusst zu machen, welche Änderungen er vornimmt.   
## Systemfeatures
**Multitasking** ([Link](https://developer.apple.com/ios/human-interface-guidelines/system-capabilities/multitasking/)) bietet den Nutzen die Möglichkeit schnell und bequem zwischen mehreren Apps hin- und herzuwechseln. Um dieses grundlegende Feature von iOS zu unterstützen sollte darauf geachtet werden, dass die App nur so viele Systemressourcen beansprucht, wie wirklich benötigt. Des weiteren ist sollte die App ihren aktuellen Zustand beim Schließen schnell speichern und beim erneuten Öffen schnell wiederherstellen. Initierte Tasks, die keine weitere Benutzereingabe erfordern, sollten auch beim Schließen der App durchgeführt werden. 

Das Anzeigen von **Mitteilungen** ([Link](https://developer.apple.com/ios/human-interface-guidelines/system-capabilities/notifications/)) geben einer App die Möglichkeit Nutzer zu informieren, wenn sich die Daten oder der Status der App geändert hat. Die angezeigte Nachricht sollte sich auf das Übermitteln nützlicher Informationen beschränken. Name und Icon der App werden hierbei automatisch angezeigt. Es sollte vermieden werden, zu viele und besonders mehrere gleiche Mitteilungen an den Nutzer zu senden.  

Die Integration von **Siri** ([Link](https://developer.apple.com/ios/human-interface-guidelines/system-capabilities/siri/)) ermöglicht es Nutzern Sprachsteuerung für spezifische Aktionen der App zu verwenden. Aktionen, die mittels Siri ausgeführt werden können sollten vollständig über die Sprachsteuerung durchführbar sein und nur wenige Spracheingaben des Nutzers erfordern. Es besteht die Möglichkeit das von Apple bereitgestellte Vokabular um app-spezifisches Vokabular zu erweitern. 
## Visuelles Design
Das **Layout** ([Link](https://developer.apple.com/ios/human-interface-guidelines/visual-design/adaptivity-and-layout/)) der App sollte so gewählt werden, dass der primäre Inhalt im Fokus steht und Nutzer mit einzelnen Elementen problemlos interagieren können. Die Nutzung von Auto Layout ermöglicht es den Abstand von Elementen einer Ansicht untereinander festzulegen. Bei der Rotathttps://developer.apple.com/ios/human-interface-guidelines/visual-design/adaptivity-and-layout/ion des Bildschirms wird das Layout dann dynamisch an die Ausrichtung angepasst, der Aufbau der Ansicht bleibt aber erhalten. 

Richtig eingesetzt können **Animationen** ([Link](https://developer.apple.com/ios/human-interface-guidelines/visual-design/animation/)) das Nutzererlebnis deutlich berbessern. Es sollte darauf geachtet werden, dass Animationen sich realistisch anfüllen und sozusagen den Gesetzten der Physik folgen. Man sollte darauf achten nicht zu viele und zu umfangreiche Animationen zu verwenden, da die App ansonsten überfrachtet wirkt. Ein guter Anhaltspunkt sind die standardmäßigen Animationen des iOS-Betriebssystems.

**Farben** ([Link](https://developer.apple.com/ios/human-interface-guidelines/visual-design/color/)) sind ein einfacher Weg mit dem Nutzer zu kommunizieren. Die innerhalb einer App genutzten Farbpalette sollte konsisten und nicht zu umfangreich sein. Hierbei sollte eine Farbe als Indikator für Interaktivität gewählt werden. Sehschwächen und kulturelle Unterschiede sollten bei der Farbwahl beachtet und 

Die Beachtung der **Terminologie** ([Link](https://developer.apple.com/ios/human-interface-guidelines/visual-design/terminology/)) und der **Typografie** ([Link]()) https://developer.apple.com/ios/human-interface-guidelines/visual-design/typography/)) ermöglicht es dem Benutzer ein angenehmes Leseerlebnis zu schaffen. Wörter und Sätze sollten der Zielgruppe entsprechend gewählt werden und Informationen kurz und prägnant bereitstellen. Die Beschreibung von Interaktionen sollte konsistent sein. Die gewählte Schriftart sollte über die gesamte App hinweg einheitlich sein und nur zum Anzeigen wichtiger Informationen verändert werden. Apple empfiehlt die Benutzung der bereitgestellten Text Styles.
### Icons und Bilder
Es ist zu beachten, dass **verschiedene Auflösungen** bereitgestellt werden müssen, um eine Vielzahl an Geräten zu unterstützen. Das App Icon als Einstiegspunkt in die App sollte einprägsam sein und die Funktion dieser so simple wie möglich verdeutlichen. Innerhalb der App sollten die standardiserten **System Icons** genutzt werden, wo immer dies möglich ist. Appspezifische Icons sollten simple und konsistent sein. Der Startbildschirm sollte der ersten Ansicht, mit der Nutzer nach dem Laden interagieren können, ähneln und keinen Text beinhalten, da dieser nicht lokalisierbar ist.

[Weiterführende Informationen](https://developer.apple.com/ios/human-interface-guidelines/icons-and-images/image-size-and-resolution/)
### Leisten
Die **Navigationsleiste** ([Link](https://developer.apple.com/ios/human-interface-guidelines/bars/navigation-bars/)) am oberen Bildschirmrand sollte den Nutzer links zur vorherigen Ansicht zurückkehren und rechts, die gesamte Ansicht betreffende, Aktionen ausführen lassen. In der Mitte wird wird in der Regel der Titel der aktuellen Ansicht angezeigt. 

Die **Suchleiste** ([Link](https://developer.apple.com/ios/human-interface-guidelines/bars/search-bars/)) sollte immer zur Implementierung einer Suchfunktion genutzt werden. 

Eine **Tab Bar** ([Link](https://developer.apple.com/ios/human-interface-guidelines/bars/tab-bars/)) am unteren Bildschirmrand ermöglicht es Nutzern schnell zwischen verschiedenen Sectionen innerhalb einer App zu wechseln. Sie sollte mit aussagekräftigen Icons und Wörtern versehen werden und sich auf wenige Tabs beschränken.

Mittels einer **Toolbar** ([Link](https://developer.apple.com/ios/human-interface-guidelines/bars/toolbars/)) können dem Nutzer am unteren Bildschirmrand Aktionen ausführen, die die aktuelle Ansicht oder deren Inhalt betreffen. Es sollte sich auf häufig durchzuführende Aktionen beschränkt werden, die sich bestenfalls ausschließlich durch Icons darstellen lassen.  
### Ansichten
Die **Tabelle** ([Link](https://developer.apple.com/ios/human-interface-guidelines/views/tables/)) ist eine Ansicht mit einer Spalte und vieler Zeilen, welche in Sektionen und Gruppen unterteilt werden können. Der Aufbau einer Tabelle beim Laden von Daten sollte modular erfolgen um den Nutzer schnell mit Informationen zu versorgen. Die Tabelle sollte sich automatisch und manuel aktualisieren lassen.

Eine **Scroll View** ([Link](https://developer.apple.com/ios/human-interface-guidelines/views/scroll-views/)) kann genutzt werden, um Inhalte anzuzeigen, die größer sind als der eigentliche Bildschirm des Gerätes. Es sollte immer nur eine Scroll View gleichzeitig angezeigt werden und eine Scroll View sollte niemals eine anderen beinhalten.

Ein **Popover** ([Link](https://developer.apple.com/ios/human-interface-guidelines/views/popovers/)) ist eine Detailansicht, die über die aufrufende Ansicht gelegt wird und diese in Teilen verdeckt. Diese Ansicht sollte ausschließlich bei Ipad-Apps verwendet werden. Das Popover sollte einen Button zum Abschließen und einen Button zum Abbrechen beinhalten. 

Ein **Action Sheet** ([Link](https://developer.apple.com/ios/human-interface-guidelines/views/action-sheets/)) ist eine Meldung die dem zwei oder mehr, auf den aktuellen Kontext bezogen, Entscheidungsmöglichkeiten bietet. Die unterste Entscheidung sollte dem Nutzer die Möglichkeit geben die aktuellen Aktion abzubrechen. Entscheidungen, die einen destruktiven oder unumkehrbaren Effekt haben sollten rot sein und am oberen Ende der Entscheidungen stehen. 

Eine **Meldung** ([Link](https://developer.apple.com/ios/human-interface-guidelines/views/alerts/)) ist eine Möglichkeit die Aufmerksamkeit des Nutzers auf eine bestimmen Umstand zu lenken und im optional zwei Entscheidungsalternativen zu bieten. Titel und Inhalt der Meldung sollten kurz und präzise sein. Die Entscheidungsalternativen sollten mit ein bis zwei Wörtern erklärt werden. "Ja" und "Nein" sollten nicht genutzt werden. Entscheidungen mit destruktiven Folgen sind in rot darzustellen.
## Technologien
Apple stellt eine Vielzahl an Technologien (z.B. Apple Pay, iCloud oder verschieden sogenannte Kits) bereit. Durch die Implementierung dieser kann die App ohne großen Entwicklungsaufwand um Features erweitert werden, die iOS-Benutzer kennen und schätzen. Hierbei sollte jedoch darauf geachtet werden, dass die genutzen Technologien sich für den jeweiligen Anwendungsfall der App eignen und ihre Implementierung für den Nutzer einen Mehrwert schafft.

[Weiterführende Informationen](https://developer.apple.com/ios/human-interface-guidelines/technologies/apple-pay/)
## Ressourcen
Apple stellt [hier](https://developer.apple.com/design/resources/#ios-apps) UI Design Templates für Photoshop, Sketch und Adobe XD zur Verfügung. Dies ermöglich es ein realistisches und den Guidelines bereits angepasstes Design zu entwerfen.
