**Spark Machine Learning (MLlib)** ist ein leistungsstarkes Werkzeug innerhalb des Apache Spark-Ökosystems, das speziell für maschinelles Lernen auf großen Datensätzen entwickelt wurde. Es nutzt verteiltes Rechnen, um Daten effizient zu verarbeiten und Modelle zu trainieren. MLlib bietet eine umfassende Auswahl an Algorithmen für Klassifikation, Regression und Clustering sowie Unterstützung für Feature Engineering und Pipelines. Durch die enge Integration mit Spark SQL und anderen Spark-Komponenten ermöglicht es eine nahtlose Datenverarbeitung und -analyse.

Im Projekt **"Regression_House_Price"** wird Spark Machine Learning eingesetzt, um ein Modell zur Vorhersage von Immobilienpreisen zu entwickeln. Die wesentlichen Schritte sind:

1. **Datenvorbereitung:** Der Datensatz wird in HDFS überprüft und hochgeladen. Anschließend wird eine Spark-Umgebung eingerichtet, um die Daten zu laden und zu analysieren.
2. **Datenverarbeitung:** Kategorische und numerische Attribute werden identifiziert und vorbereitet. Spark MLlib wird verwendet, um die Daten mit StringIndexer und OneHotEncoder für das Modell vorzubereiten.
3. **Modelltraining:** Ein Gradient-Boosted Tree Regressor wird innerhalb einer Spark-Pipeline trainiert, um präzise Vorhersagen der Immobilienpreise auf Basis der verarbeiteten Daten zu ermöglichen.
4. **Evaluation:** Die Modellleistung wird mit der R²-Metrik auf einem Testdatensatz bewertet.

Dieses Projekt demonstriert, wie Spark MLlib für umfassende Datenverarbeitung und Modellierung genutzt wird, um effiziente und skalierbare Vorhersagen zu ermöglichen.
