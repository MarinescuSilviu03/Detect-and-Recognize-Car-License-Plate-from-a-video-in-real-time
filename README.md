# Detect and Recognize Car License Plate from a Video in Real-Time

## Descriere
Acest proiect este o aplicație Python care detectează și recunoaște numerele de înmatriculare ale autovehiculelor dintr-un videoclip în timp real. Programul folosește tehnici de procesare a imaginilor și recunoaștere optică a caracterelor (OCR) pentru a extrage și interpreta informațiile de pe plăcuțele de înmatriculare.

## Tehnologii Utilizate
- **Python** – Limbaj principal de programare
- **OpenCV (cv2)** – Pentru procesarea imaginilor și detectarea plăcuțelor
- **Tesseract OCR** – Pentru recunoașterea caracterelor de pe plăcuțe
- **BeamNG.drive** – Simulator auto pentru generarea de videoclipuri
- **Tkinter** – Crearea interfeței grafice
- **Pandas** – Exportarea datelor în fișiere Excel

## Funcționalități
- Detectarea plăcuțelor de înmatriculare dintr-un videoclip
- Recunoașterea textului de pe plăcuță folosind OCR
- Filtrarea rezultatelor pentru a evita duplicatele
- Exportarea datelor recunoscute într-un fișier Excel
- Interfață grafică simplă pentru încărcarea fișierelor video și exportarea datelor

## Structura Proiectului
- **main.py** – Codul principal al aplicației
- **haarcascade_russian_plate_number.xml** – Fișier pentru detectarea plăcuțelor rusești
- **Tesseract-OCR** – Motorul OCR utilizat pentru recunoașterea caracterelor
- **resources/** – Folder cu exemple de videoclipuri și rezultate

## Instalare și Utilizare
### 1. Instalarea Dependențelor
Asigurați-vă că aveți instalate următoarele biblioteci Python:
```sh
pip install opencv-python pandas pytesseract
```
De asemenea, descărcați și instalați **Tesseract OCR** de la [Tesseract OCR](https://sourceforge.net/projects/tesseract-ocr.mirror/).

### 2. Rularea Programului
Lansați scriptul principal:
```sh
python main.py
```
Alegeți un videoclip de analizat și specificați locația fișierului Excel pentru rezultate.

### 3. Ieșire
După procesare, numerele de înmatriculare recunoscute vor fi salvate într-un fișier Excel.

## Referințe
- [OpenCV](https://github.com/opencv/opencv)
- [Tesseract OCR](https://sourceforge.net/projects/tesseract-ocr.mirror/)
- [Tutorial GeeksForGeeks](https://www.geeksforgeeks.org/license-plate-recognition-with-opencv-and-tesseract-ocr/)

