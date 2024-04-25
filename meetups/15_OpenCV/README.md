# OpenCV

## Face recognition

Se vuoi provare a riprodurre l'esempio descritto nelle [slide](PyDataVenice15.Alessandra.Bilardi.pdf), puoi usare i comandi che seguono.

```sh
git clone https://github.com/bilardi/real-time-face-recognition.git
cd real-time-face-recognition
git checkout -t origin/improvements
pip3 install -r requirements.txt
python3 face_taker.py
python3 face_train.py
python3 face_recognizer.py
```

## Object detection

Che sia un viso od un oggetto, la questione primaria è, come creare i propri embedding ?
Gli applicativi che permettono di creare i propri embedding per OpenCV **risiedono solo nelle versioni precedenti alla 4.x** ([issues](https://github.com/opencv/opencv/issues/13231)): ecco una piccola guida per l'[installazione](https://github.com/bilardi/how-to-train-cascade) degli applicativi necessari, alla creazione dei propri embedding e al loro utilizzo.

## AstroPi - ESA Competition

Il progetto presentato nelle [slide](PyDataVenice15.Elia.Ernesto.Stellin.pdf) è scaricabile da [GitHub](https://github.com/pandle/astro-pi-2022-23).
