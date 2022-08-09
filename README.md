# CowRumpIdentification

Dieses Repository ist eine Implementation einer Pipeline zum Trainieren eines Modells für die Identifikation von Kühen. Der Struktur der Hausarbeit folgend, ist die Pipeline in zwei haupsächliche Schritte aufgeteilt:

1. Die Vorbereitung der Bilder mithilfe eines Object Detectors 
2. Das Training eines Classifiers für die Identifikation

Die Notebooks mit dem relevanten Code ([prepare_images.ipynb](./prepare_images.ipynb), [train_identification.ipynb](./train_identification.ipynb)) sind auf einer lokalen Maschnine geschrieben worden und setzen voraus, das mithilfe des os Modules von Python Ordner angelegt und Bilder auf der Festplatte gespeichert werden können. 

## Benötigte Module

Es werden mindestens die folgenden Module benötigt:

- numpy 
- Pillow (Python Image Library)
- imageio
- torch
- torchvision
- keras 
- scikitplot
- matplotlib

## How to Run

Zunächst muss das [prepare_images.ipynb](./prepare_images.ipynb) Notebook ausgeführt werden. Dazu muss der Pfad zu dem originalen und vorsortierten Datensatz im ersten Code Block richtig gesetzt werden. Ein Archiv mit den Bildern ist hier (TODO: LINK) zu finden. Danach kann das Notebook vollständig ausgeführt werden.

Für das [train_identification.ipynb](./train_identification.ipynb) Notebook müssen keine weiteren Einstellungen vorgenommen werden. Das vom ersten Notebook erstellte Ordnerstruktur wird einfach ausgelesen. 