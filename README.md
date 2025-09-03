# bioimagesegmentator
The program allows you to segment biomedical images. It allows you to load DICOM and NRRD files as input.

E' un'applicazione Python basata su **Tkinter** e **SimpleITK** per la visualizzazione, l'analisi e la segmentazione di immagini mediche in formato **NRRD** e **DICOM**.

## Funzionalità principali

- **Caricamento file**: supporto per file `.nrrd` e `.dcm`.
- **Selezione del piano**: per i file `.nrrd`, possibilità di scegliere tra tre piani (Piano 1, Piano 2, Piano 3).
- **Selezione della fetta**: selezione manuale della slice da visualizzare.
- **Visualizzazione immagini**: rendering con **matplotlib** direttamente nell'interfaccia Tkinter.
- **Istogramma**: visualizzazione della distribuzione dei valori di intensità.
- **Calcolo della media**: calcolo iterativo della media per la sogliatura.
- **Segmentazione**: creazione di una maschera binaria basata sulla soglia della media.

## Requisiti

Assicurati di avere installato:

- Python 3.8+
- Tkinter (incluso nella maggior parte delle distribuzioni Python)
- [SimpleITK](https://simpleitk.readthedocs.io/)
- matplotlib
- numpy

Installa i pacchetti mancanti con:

```bash
pip install SimpleITK matplotlib numpy
