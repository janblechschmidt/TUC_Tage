# Anleitung zum Mitmachen
## 1. Möglichkeit: Cloud-Computing

Unter https://colab.research.google.com/ kann jeder mit einem Google-Konto in der Cloud das Jupyter Notebook ausprobieren, ohne irgendetwas zu installieren. Dafür einfach das gewünschte Notebook (erkennbar an der Endung `*.ipynb`)  runterladen und bei Google Colab hochladen und starten.

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

eine Jupyter-Session starten. Dort könnt ihr dann auch das jeweilige Notebook (erkennbar an der Endung `*.ipynb`) öffnen und ausführen. Wichtig ist immer sicherzustellen, dass die richtige Conda-Umgebung geladen ist, sichtbar an dem `(tuc)` am Anfang einer Befehlszeile. Wenn das nicht dort steht, kann das Environment mittels `conda activate tuc` (in seltenen Fällen auch `source activate tuc`) geladen werden.
