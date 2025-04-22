# Übung Erklärbare KI und Visualisierung
Dieses Repositorium enthält den Code und Daten für die Übungen in der Veranstaltung Erklärbare KI und Visualisierung bei Kai Moltzen und Prof. Dr. Ricardo Usbeck an der Leuphana Universität Lüneburg. 

## Voraussetzungen
1. Installation von [Python 3.12+](https://www.python.org/downloads/release/python-31210/)
2. Installation einer vollumfassenden Entwicklungsumgebung (IDE), z.B. [PyCharm](https://www.jetbrains.com/pycharm/) (als Student erhalten Sie eine [kostenlose Vollversion](https://docs.python.org/3/library/venv.html), oder [VS Code](https://code.visualstudio.com/) (generell kostenlos).
3. Programmierkenntnisse in Python. Ressourcen sind z.B. [The Python Tutorial](https://docs.python.org/3/tutorial/index.html), [W3 Python Tutorial](https://www.w3schools.com/python/), ...
4. Nutzen Sie für diesen Kurs eine eigene virtuelle Umgebung (venv), in der Sie Packete installieren und nutzen:[venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html); IDEs wie PyCharm oder VSCode bieten auch grafische Oberflächen zur Verwaltung von venvs. Wenn nötig, aktivieren Sie Ihre venv für diesen Kurs und verifizieren Sie, dass die venv aktiviert ist. Das ist der Fall, wenn die Eingabe `sys.prefix != sys.base_prefix` in der Python Konsole true ausgibt.
5. Stellen Sie sicher, dass Sie den Package Installer pip installiert haben. Machen Sie sich mit dessen Nutzung vertraut: [PIP User Guide](https://pip.pypa.io/en/stable/getting-started/)
6. Installieren Sie alle für dieses Repositorium erforderlichen Packete: `pip install -r requirements.txt`

## Aufbau
Für jede Übung (donnerstags) wird ein eigenes [Jupyter Notebook](https://jupyter.org/) zur Verfügung gestellt (Week_x..ipynb). Das Notebook enthält alle Aufgabenstellungen sowie Code, den wir in der Übung besprechen. Im `data` Ordner werden exemplarische Datensätze bereitgestellt. Sofern weitere Datensätze selbstständig heruntergeladen werden müssen (z.B. wegen Speicheranforderungen), ist dies in den Notebooks vermerkt. 

## Ablauf
In der Vorlesung (dienstags) besprechen wir Konzepte und Theorien zu Erklärbarer KI und Visualisierung. In der Übung (donnerstags) wenden wir diese Konzepte praktisch an, indem a) wir gemeinsam Code erörtern, b) Sie Aufgaben in der ÜBung bearbeiten und wir diese besprechen, c) indem Sie die Hausaufgaben lösen und wir diese in der darauffolgenden Woche besprechen.
Hausaufgaben sind als solche gekennzeichnet. Sollten Sie Fragen zu den Hausaufgaben oder Inhalten der vorherigen Übungen haben, können Sie diese per Mail bis zur Vorlesung am Dienstag stellen und wir besprechen sie in der darauffolgenden Übung. Wir setzen für die jeweils nächste Übung voraus, dass die vorherige Übung verstanden wurde und der Code in den zugehörigen Notebooks bei Ihnen läuft.

## Prüfungsleistung / Abgaben
Die Prüfungsleistung besteht aus der **Abgabe Ihres Portfolios** (Upload in MyStudy bis 11.07.2025 EOD) sowie der **Präsentation Ihres Miniprojektes**. 
Das **Portfolio** besteht aus einem Archiv (zip) aus:
1. Notebooks mit den **gelösten Aufgaben** der Übungen.
2. Ihrer **Implementierung des Miniprojekts** (z.B. als Notebook, Webseite, ...) inklusive allem Code, Erklärungen sowie der Beschreibung und Interpretation Ihres Projektes. Denken Sie daran: Sie sollen die in der Vorlesung kennengelernten Konzepte nutzen, um mit Daten eine Geschichte zu erzählen!
3. Falls Sie das Miniprojekt in Kleingruppen (max. 3 Studis) bearbeiten, geben Sie zusätzlich einen detaillierten **Arbeitsbericht** ab, indem Sie darlegen, wer was und in welchem Umfang bearbeitet hat.
