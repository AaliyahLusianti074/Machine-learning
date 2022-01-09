# Dataset
Dataset yang digunakan  adalah <a href="https://www.kaggle.com/grassknoted/asl-alphabet"><i>American Sign Language</i></a> yang didapatkan dari open source kaggle.com. Dalam dataset tersebut, Kumpulan data training berisi 87.000 gambar berukuran 200x200 pixel. Ada 29 kelas, 26 di antaranya untuk huruf A-Z dan 3 kelas untuk SPACE, DELETE dan NOTHING.
3 kelas ini sangat membantu dalam aplikasi real-time, dan klasifikasi. Kumpulan data testing hanya berisi 29 gambar, untuk mendorong penggunaan gambar testing di dunia nyata.
Persentase perbandingan data training adalah 90% dan 10% data testing. Contoh dataset ditunjukkan pada gambar berikut :

<img width="482" alt="ASL Lang" src="https://user-images.githubusercontent.com/64589800/138824570-78c10825-e839-4c89-bb6c-8329a22fea50.png">

## Preprocessing
<a href="https://github.com/AaliyahLusianti074/TugasPraktikumML_066-074/blob/main/PreprocessingData.py">Preprocessing</a> pada dataset dilakukan dengan membagi data training dan data testing dengan perbandingan 9:1. Kelas dataset memiliki 29 gambar terdiri dari gambar ASL huruf A sampai dengan Z serta 'nothing', 'space' dan 'del'. Pembagian dataset terbagi sebanyak 78300 gambar data training dan sisanya 8700 sebagai data testing dengan size(224,224).

