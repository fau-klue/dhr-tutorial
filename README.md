# Statistik für (digitale) GeisteswissenschaftlR

Dieses Tutorial gibt eine Einführung in die Verwendung von R und RStudio. Anhand von Beispieldaten aus den Digital Humanities beschäftigen wir uns mit statistischen Standardmethoden, Visualisierung, Anwendungen aus der Korpuslinguistik (Keywords & Kollokate) sowie mit (verallgemeinerten) linearen Modellen.

Dieses Tutorial ist das richtige für Sie, wenn Sie …
- … bereits wissen, wie arithmetisches Mittel, Median und Standardabweichung berechnet werden, aber solche Berechnungen gerne in R vornehmen würden.
- … hübsche Visualisierungen in R erstellen wollen.
- … gerne Regressionsmodelle (oder kompliziertere Modelle) in R anpassen würden.
- … Interesse an einem Einblick in automatische Textverarbeitung haben.
- … endlich von SPSS loskommen möchten.

## Vorbereitung
- [Vorbereitung.pdf](sessions/Vorbereitung.pdf) für Literaturempfehlungen, Installationsanleitungen für R und RStudio, Orientierung in RStudio und allererste Schritte mit R
- [Erste Schritte mit R.Rmd](sessions/Erste%20Schritte%20mit%20R.Rmd)

## Daten
- ltwby2018_news_parties.csv: Tokenhäufigkeiten von drei Parteien in 10 Zeitungen [Kontingenz]
- *.lemma.tsv.gz: zwei Lemma-Häufigkeitslisten [Keywords]
- winter-elp*: Ergebnisse eines Lexical Decision Task [lineare Regression]
- smspam.tsv: SMS (ham vs. spam) [logistische Regression]

## Sitzungen
- linear-model.[Rmd|html]: Lineare Regression (LDT, Response ist Reaktionszeit)
- logistic-regression.[Rmd|html]: Logistische Regression (Gesten, Response ist binomial)
