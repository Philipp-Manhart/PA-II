Du bist ein Experte für Statistik und Big Data. Ich bin dualer Student der BMW Bank und fertige eine wissenschaftliche Arbeit mit dem titel "Chancen und Herausforderungen der Big Data Integration in Business Intelligence Systeme im Finanzsektor: eine konzeptionelle Analyse am Beispiel der des Controllings der BMW Bank". Im Theorieteil (ca. 2500 Wörter) habe ich bereits die Begriffe definiert und exemplarisch 3 Chancen und 2 Herausforderungen betrachtet. Jetzt bin ich dabei meinen Praxisteil zu schreiben und habe mit Absprache mit meinem Wissenschaftlichen Betreuer der Hochschule definiert, dass ich die versuche die Prognose der wöchentlichen Absatzzahlen der BMW Bank zu verbessern, indem ich ihren Zusammenhang mit anderen externen Größen z.B. Verbraucherpreisindex überprüfe. Ich habe folgendes Vorgehen gewählt:

- Datenbeschaffung
- Datenvereinheitlichung(Einheitliches Datumsformat etc.)
- Logarithmieren von gewissen Daten (Google Trends Daten, Gebrauchtwagenpreisindex, Verbraucherpreisindex); Andere Daten wie z.B. der Euribor, oder die Arbeitslosenquote wurden nicht logarithmiert

- Mergen der Daten
- Interpolieren der Daten
- Auf Wochenbasis bringen
- Saisonale Bereinigung der Daten mittel STL
- Stationarität der Daten überprüfen mittels ADF
- Nicht Stationäre Daten differenzieren
- Für differenzierte Daten Stationärität erneut mittels ADF prüfen
- Feature Engineering: Lagging der Zielvariable (BMW Absatzzahlen) nach vorne, also wie hänge die Absatzzahlen in 4,8,.. Wochen von den heutigen externen Variablen ab?
- Pearson & Spearman Korrelation, der Zielvariablen bzw. gelaggten Zielvariable und der externen Variable



So möchte ich weiter machen: 
- Externe Variablen die eine Hohe Korrelation haben zu meiner Zielvariable identifizieren
- Die Identifizierten Variablen für multibler linearer Regression nutzen 



Bitte bewerte mein Vorgehen: Mache ich irgendwas falsch? Fehlt etwas Relevantes? 