# TDWI 2021: Text Mining mit Python und PowerBI

Workshop von **Jens Albrecht und Roland Zimmermann** auf [TDWI-Konferenz 2021](https://www.tdwi-konferenz.de/tdwi-2021/programm/konferenzprogramm.html#item-2976)

[Link zum Programm-Eintrag](https://www.tdwi-konferenz.de/tdwi-2021/startpage/program/conference-program/track/workshop-6.html)

[Link zum Video-Mitschnitt](https://youtu.be/fp95Ao-cs20)

In diesem Ordner werden die Arbeitsmaterialien für den Workshop abgelegt sowie eine Installationsanleitung.

Für das aktive Mitmachen wird benötigt:

  - Am besten ein Google-Account mit Zugang zu [Google Colab](http://colab.research.google.com/) **oder** eine Anaconda/Miniconda-Installation auf dem lokalen Rechner (siehe unten)
  - PowerBI Desktop ([Link zum Download](https://powerbi.microsoft.com/de-de/downloads/))

## Inhalt

[Präsentation](TDWI2021_Text_Mining.pdf)

### PowerBI-Dateien

[Im Verzeichnis `powerbi`](powerbi). (Die Daten können auf Anfrage erhalten werden.)

### Notebooks für den Python-Teil

  * **Data Preprocessing** 
  [[View here in git](notebooks/Data_Preprocessing.ipynb)] 
  [[View in nbviewer](https://nbviewer.ipython.org/github/jsalbr/tdwi-2021-text-mining/blob/main/notebooks/Data_Preprocessing.ipynb)] 
  [[Execute on Google Colab](https://colab.research.google.com/github/jsalbr/tdwi-2021-text-mining/blob/master/notebooks/Data_Preprocessing.ipynb)]

  * **Classification** 
  [[View here in git](notebooks/Classification.ipynb)] 
  [[View in nbviewer](https://nbviewer.ipython.org/github/jsalbr/tdwi-2021-text-mining/blob/main/notebooks/Classification.ipynb)] 
  [[Execute on Google Colab](https://colab.research.google.com/github/jsalbr/tdwi-2021-text-mining/blob/master/notebooks/Classification.ipynb)]

  * **Advanced Models** 
  [[View here in git](notebooks/Advanced.ipynb)] 
  [[View in nbviewer](https://nbviewer.ipython.org/github/jsalbr/tdwi-2021-text-mining/blob/main/notebooks/Advanced.ipynb)] 
  [[Execute on Google Colab](https://colab.research.google.com/github/jsalbr/tdwi-2021-text-mining/blob/master/notebooks/Advanced.ipynb)]


Darüber hinaus bereitgestellt, aber im Workshop nicht verwendet, die Notebooks zur Datenextraktion und Bereinigung:

  * **Data Extraction**
  [[View here in git](notebooks/Data_Extraction_Reddit.ipynb)] 
  [[View in nbviewer](https://nbviewer.ipython.org/github/jsalbr/tdwi-2021-text-mining/blob/main/notebooks/Data_Extraction_Reddit.ipynb)] 

  * **Data Cleaning**
  [[View here in git](notebooks/Data_Cleaning_Reddit.ipynb)] 
  [[View in nbviewer](https://nbviewer.ipython.org/github/jsalbr/tdwi-2021-text-mining/blob/main/notebooks/Data_Cleaning.ipynb)] 



## Ananconda-Installation

```sh
# Anlegen eines virtuellen Environments
conda create --name tdwi
# Aktivieren des Environments
conda activate tdwi
# Python-Pakete installieren
conda env update --file conda_requirements.yml
# Spacy Modell laden
python -m spacy download en_core_web_sm
# Jupyter Notebook starten
jupyter notebook
```

