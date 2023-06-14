# Nutrimate-ML

Pengumpulan dataset Nutrimate menggunakan teknik scraping 15 jenis gambar makanan menggunakan scraping tools berbasis web yang tersedia pada library python berupa bing-image-downloader dengan parameter keyword dan limit data yang diambil. Dengan kuantitas masing-masing sebanyak 150 gambar, dataset akhir makanan memiliki sebanyak 2250 data untuk kemudian dilanjutkan pada proses augmentasi.

Model memanfaatkan teknik transfer learning dengan menggunakan pre-trained model berupa InceptionV3. InceptionV3 adalah model convolutional neural network (CNN) untuk membantu analisis gambar dan deteksi objek, dan dimulai sebagai modul untuk GoogLeNet. InceptionV3 terbukti dapat mencapai akurasi lebih dari 78,1% pada kumpulan data ImageNet. Selanjutnya, pre-trained model tersebut dihubungkan dengan model akhir yang memiliki komposisi layer flatten, dropout, dan dense. Pada hasil analisis akurasi validasi dan loss, model terbukti sukses dalam meraih akurasi validasi sebesar 82% dan loss sebanyak 16%.

![download (71)](https://github.com/Bangkit-Capstone-Project-C23-PS101/Nutrimate-ML/assets/82490903/892a3ea1-091f-4d27-96bf-6639b01bc2a1)
![download (72)](https://github.com/Bangkit-Capstone-Project-C23-PS101/Nutrimate-ML/assets/82490903/01407cb5-110b-4ba5-a40f-b6e5ec8d0f0a)
