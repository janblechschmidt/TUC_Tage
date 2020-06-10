# Anleitung zum Mitmachen

## Jupyter Notebook herunterladen

Um direkt loszulegen müsst ihr als erstes das Jupyter Notebook, erkennbar an der Endung `*.ipynb`, <a href="https://raw.githubusercontent.com/janblechschmidt/TUC_Tage/master/TUC_Tage_2020_Mathe_und_KI.ipynb" download>hier</a> herunterladen.
Die Version mit Lösung erhaltet ihr <a href="https://raw.githubusercontent.com/janblechschmidt/TUC_Tage/master/TUC_Tage_2020_Mathe_und_KI_complete.ipynb" download>hier</a>.

**Hinweis**: Falls euer Browser jetzt nur eine merkwürdige Textdatei mit vielen unbekannten Dingen öffnet statt den Download zu starten, rechtsklickt ihr einfach auf den Link und wählt `Ziel speichern unter` aus, um die Datei zu speichern.

Alternativ könnt ihr auch einfach das ganze Verzeichnis als `zip`-Ordner über einen Klick auf den Button `Clone` herunterladen.

## 1. Möglichkeit: Cloud-Computing

Unter https://colab.research.google.com/ kann jeder mit einem Google-Konto in der Cloud das Jupyter Notebook ausprobieren, ohne irgendetwas zu installieren. Nach dem Download des Jupyter Notebooks (siehe oben) müsst ihr dieses bei Google Colab hochladen und könnt starten.

## 2. Möglichkeit: Installation einer eigenen Python-Umgebung mittels Conda
- aktuelle Version von miniconda [hier](https://docs.conda.io/en/latest/miniconda.html) herunterladen und installieren
- conda-Umgebung anlegen
  
      conda create --name tuc

- conda-Umgebung <code>tuc</code> aktivieren

      conda activate tuc

- notwendige Pakete installieren

      conda install -c conda-forge numpy tensorflow matplotlib jupyter

Anschließend könnte ihr mit dem Befehl

    jupyter notebook 

eine Jupyter-Session starten. Dort könnt ihr dann auch das jeweilige Notebook öffnen und ausführen.
Wichtig ist immer sicherzustellen, dass die richtige Conda-Umgebung geladen ist, sichtbar an dem `(tuc)` am Anfang einer Befehlszeile. Wenn das nicht dort steht, kann das Environment mittels `conda activate tuc` (in seltenen Fällen auch `source activate tuc`) geladen werden.
