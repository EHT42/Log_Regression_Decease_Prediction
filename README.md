# Klassifikation von Patienten mit Logistischer Regression

Dieses Projekt implementiert eine logistische Regression zur Klassifikation von Patienten als gesund oder krank basierend auf medizinischen Merkmalen wie Alter, BMI, Blutdruck und Cholesterinwert. Die scikit-learn-Bibliothek wird für das Training und die Bewertung des Modells verwendet, und die matplotlib- und seaborn-Bibliotheken werden zur Visualisierung der Ergebnisse genutzt.

Funktionsweise des Programms:
- Daten einlesen:
Der Datensatz wird aus einer CSV-Datei geladen, die medizinische Daten der Patienten enthält. Dieser wird in Merkmale (Features) und Zielvariable (Label) unterteilt.
- Datenaufbereitung:
Die Merkmale, die für die Klassifikation verwendet werden, sind: Alter, BMI, Blutdruck und Cholesterin. Die Zielvariable ist, ob der Patient gesund (0) oder krank (1) ist.
- Trainings- und Testdatensatz aufteilen:
Der Datensatz wird in Trainings- und Testdaten unterteilt, um das Modell zu trainieren und zu validieren.
- Logistische Regression:
Ein Logistisches Regressionsmodell wird mit den Trainingsdaten erstellt und trainiert. Das Modell wird anschließend auf den Testdaten bewertet.
- Modellbewertung:
Die Genauigkeit des Modells sowie ein Klassifikationsbericht werden ausgegeben, um die Modellleistung zu bewerten.
Eine Verwirrungsmatrix wird erzeugt und mit seaborn visualisiert.
- Vorhersage einer neuen Patientendiagnose:
Das Modell kann für einen neuen Patienten verwendet werden, um basierend auf den eingegebenen Merkmalen vorherzusagen, ob der Patient krank oder gesund ist.
- Modellparameter:
Es werden die wichtigsten Modellparameter ausgegeben, um die Konfiguration der logistischen Regression zu überprüfen.
