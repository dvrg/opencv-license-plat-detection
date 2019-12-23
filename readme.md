## Requiremnts
+ Linux/Windows
+ python3
+ Internet

## Instalasi
1. Clone/Download repository ini
2. cd OpenCV_3_License_Plate_Recognition_Python/
3. pip3 install opencv-python==3.4.8.29

## Cara Pakai
Seluruh penjelasan kode ada di DocsAndPresentation folder.

### Training
> python3 GenData.py

### Test & Train
> python3 TraintAndTes.py

### Menjalankan
Sebelum menjalankan program cek terlebih dulu file mana yang ingin di deteksi, caranya ubah fiel Main.py pada bagian :
```
15 | def main():
16 |    imgTrainingNumbers = cv2.imread("Train/train1.png")            # read in training numbers image
```
Python3 Main.py