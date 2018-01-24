# Apple Human Interface Guidelines für iOS
Human Interface Guidelines (HIG) dienen Entwicklern und Designern als **Leitfaden zur Erstellung einer benutzerfreudlichen und intuitiven Applikation**. Die meisten dieser Guidelines haben zudem die Funktion den Apps einer Anwendungsumgebung einen einheitlichen "Look and Feel" zu geben. Dies bedeutet, dass sowohl das visuelle Design als auch das Verhalten der Anwendungenen konsistent sein sollte.  Die Nutzung dieser Guidelines ist keine Pflicht, jedoch behält Apple es sich vor Apps ,die schwer gegen die Design-Philosophie verstoßen und grundlegende Elemente entgegen ihres Sinnes nutzen, nicht für den Store freizugeben.

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
## Systemfähigkeiten
**Multitasking** ([Link](https://developer.apple.com/ios/human-interface-guidelines/system-capabilities/multitasking/)) bietet den Nutzen die Möglichkeit schnell und bequem zwischen mehreren Apps hin- und herzuwechseln. Um dieses grundlegende Feature von iOS zu unterstützen sollte darauf geachtet werden, dass die App nur so viele Systemressourcen beansprucht, wie wirklich benötigt. Des weiteren ist sollte die App ihren aktuellen Zustand beim Schließen schnell speichern und beim erneuten Öffen schnell wiederherstellen. Initierte Tasks, die keine weitere Benutzereingabe erfordern, sollten auch beim Schließen der App durchgeführt werden. 

**Mitteilungen**

**Siri**
## Visuelles Design
### Icons
### Leisten
### Ansichten
## Technologien
## Ressourcen
Apple stellt [hier](https://developer.apple.com/design/resources/#ios-apps) UI Design Templates für Photoshop, Sketch und Adobe XD zur Verfügung. Dies ermöglich es ein realistisches und den Guidelines bereits angepasstes Design zu entwerfen.
