# master_thesis
Master thesis - Predictive Identification of Android Malware through Hybrid Analysis

**Abstract**
With a still increasing amount of mobile devices running the mobile operating system *Android*,
their extensive usage and various application possibilities, those 
devices have become valuable targets for malicious apps. <br>
With advanced static and dynamic analyses researchers gain valuable insights into the mechanics of malware,
where machine learning is often utilized to detect unknown malicious apps.
The Android operating system and related malware are continuously evolving.
So training a machine learning model using outdated malware could negatively affect the performance of the predictive identification of
more recent malware. 
Though several scientific publications used outdated malware collections. <br>
This thesis focuses on the central research question:
*How precise is the predictive identification of recent Android malware by comparing two hybrid approaches?*
In this thesis recent malicious and benign Android apps from suitable repositories were collected.
Two hybrid analyses were implemented to extract static and dynamic information from Android apps.
Both approaches attempt to increase the code coverage of the dynamic analysis, which was executed on physical devices.  <br>
A *random forest* ensemble approach was utilized to perform 
a binary classification on malicious and benign Android apps using a total of 163559 features of the hybrid analyses.
An antivirus aggregator service was applied to reduce the teacher noise.
To provide a categorization of the analyzed malware an unsupervised clustering approach with *k-means* was utilized.  <br>
The classification of both hybrid approaches and the clustering were applied to over 9000 Android apps.
The prediction of unknown malware results in an accuracy of approximately 90%. 
The clustering approach reveals 30 clusters with different malware labels.

**Kurzfassung**
Die Verbreitung und Einsatzmöglichkeiten mobiler Endgeräte, die das mobile Betriebssystem *Android* nutzen, nimmt stetig zu. 
Die Geräte erweisen sich als wertvolle Ziele für Malware, die in Form von Apps auf das Gerät gelangen. <br>
Wissenschaftler haben ausgereifte statische und dynamische Analyseverfahren entwickelt, um Einblicke 
in die Funktionsweise von Malware-Apps zu erhalten. Oftmals werden maschinelle Lernverfahren
verwendet, um unbekannte bösartige Apps zu erkennen.
Software wie das Android-Betriebssystem oder Android-Malware entwickeln sich kontinuierlich weiter.
Das Training eines maschinellen Lernmodells mit veralteten Malwaredaten, kann zu
negativen Auswirkungen auf die Leistungsfähigkeit der Vorhersage von aktueller Malware führen.
Mehrere Publikationen nutzen veraltete Malware-Apps als Grundlage.  <br>
Diese Masterarbeit behandelt die folgende zentrale Forschungsfrage: 
*Wie genau ist die Erkennung von unbekannter aktueller Malware im Vergleich von zwei hybriden Analyseverfahren?*
In dieser Arbeit wurden aktuelle bösartige sowie harmlose Android-Apps von geeigneten Quellen erfasst.
Es wurden zwei hybride Analysen implementiert, die in der Lage sind statische und dynamische Informationen 
aus Android-Apps zu extrahieren. 
Beide hybride Ansätze verfolgen das Ziel die Programmcodeerfassung zu maximieren. Die dynamische Analyse 
wurde auf physikalischen Geräten durchgeführt. <br>
Ein *random forest*-Ansatz wurde verwendet, um eine binäre Klassifikation von bösartigen und normalen Apps durchzuführen.
Dazu wurden insgesamt 163559 Features der hybriden Analysen verwendet.
Ein Antivirus-Aggregator-Dienst wurde genutzt, um Störungen der Daten für das Modelltraining zu minimieren. 
Um eine Kategorisierung der verwendeten Malware zu erhalten wurde ein Clustering-Ansatz mit Hilfe von *k-means* umgesetzt.
Für die Klassifizierung und das Clustering wurden über 9000 Apps verwendet.  <br>
Unbekannte Malware wurde mit einer Genauigkeit von etwa 90% erkannt. 
Der Clustering-Ansatz deckt 30 Cluster mit verschiedenen Malware-Bezeichnungen auf.