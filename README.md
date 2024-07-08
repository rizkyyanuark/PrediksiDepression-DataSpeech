<div align="center">
  <h1>Prediksi Depresi dari Data Speech</h1>
  <blockquote>
    Project ini memanfaatkan metode Mel Frequency Cepstral Coefficients (MFCC) untuk mengekstrak fitur, dan menggunakan Convolutional Neural Networks (CNN) untuk proses pembelajaran dan prediksi.
    <br>
    Tujuan utama project ini adalah untuk mengembangkan model yang akurat dan efisien yang dapat digunakan dalam aplikasi kesehatan mental untuk mendeteksi dan mencegah depresi pada tahap awal.
  </blockquote>
</div>

<details>
  <summary>🏁 Table of Contents</summary>
  <ul>
    <li><a href="#Dataset">Dataset</a></li>
    <li><a href="#Teknologi-yang-Digunakan">Teknologi yang Digunakan</a>
    </li>
    <li><a href="#Cara-Menggunakan">Cara Menggunakan</a></li>
    <li><a href="#Referensi">referensi</a></li>
    <li><a href="#Kontribusi">Kontribusi</a></li>
    <li><a href="#License">Lisensi</a></li>
    <li><a href="#File">File</a></li>
    <li><a href="#Teams">Teams</a></li>
  </ul>
</details>

## Dataset
Proyek ini menggunakan dataset dari [RAVDESS](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio), yang merupakan sumber daya yang sangat berharga untuk penelitian dalam bidang pengenalan emosi melalui suara.

Berikut adalah penjelasan singkat tentang identifikasi nama file dalam dataset RAVDESS:

* Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
* Vocal channel (01 = speech, 02 = song).
* Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
* Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
* Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
* Repetition (01 = 1st repetition, 02 = 2nd repetition).
* Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

Sebagai contoh, nama file audio `02-01-06-01-02-01-12.mp4` memiliki meta data sebagai berikut:

* Video-only (02)
* Speech (01)
* Fearful (06)
* Normal intensity (01)
* Statement "dogs" (02)
* 1st Repetition (01)
* 12th Actor (12) - Female (as the actor ID number is even)

Dalam proyek ini, kami melakukan pengelompokan emosi menjadi dua kelas utama: `Depresi` dan `Non-Depresi`. Emosi seperti neutral, calm, surprised, dan happy akan dikategorikan ke dalam kelas `Non-Depresi`. Sementara itu, emosi seperti sad, angry, fearful, dan disgust akan dikategorikan ke dalam kelas `Depresi`.

Tujuan dari pengelompokan ini adalah untuk memudahkan analisis dan pemahaman tentang bagaimana emosi dapat dikelompokkan berdasarkan karakteristik mereka. Dengan demikian, ini akan membantu dalam penelitian lebih lanjut tentang pengenalan depresi berbasis dataset emosi

## Teknologi yang Digunakan

- Python
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Keras

## Cara Menggunakan

1. Clone repositori ini.
2. Install semua dependensi yang diperlukan.
3. Jalankan notebook Jupyter atau script Python.

## Referensi

Jika Anda tertarik untuk mempelajari lebih lanjut tentang topik ini, berikut adalah beberapa referensi yang mungkin berguna:

- Understanding Depression: Signs, Symptoms, Causes, and Help
- Machine Learning for Mental Health Prediction

## Kontribusi

Kontribusi, masalah, dan permintaan fitur baru selalu diterima. Untuk perubahan besar, harap buka issue terlebih dahulu untuk membahas apa yang ingin Anda ubah.

## License

MIT

## File

- Proposal : [pdf](https://github.com/rizkyyanuark/PrediksiDepression-DataSpeech/blob/main/Proposal%20Prediciton%20of%20Depression%20from%20Data%20Speech.pdf)
- HKI : EC002023123353, 4 Desember 2023


## Teams

<div align="center">
  <table style="margin: auto;">
    <tr>
      <td align="center">
  <a href="https://github.com/rizkyyanuark">
    <img src="https://avatars.githubusercontent.com/u/82692777?v=4" width="100px;" alt="RizkyYanuarK"/>
  </a>
  <br />
  <sub>RizkyYanuarK</sub>
</td>
<td align="center">
  <a href="https://github.com/fadhilahnuria">
    <img src="https://avatars.githubusercontent.com/u/114966285?v=4" width="100px;" alt="Fadhilah Nuria Shinta"/>
  </a>
  <br />
  <sub>Fadhilah Nuria Shinta</sub>
</td>
<td align="center">
  <a href="https://github.com/prenji3">
    <img src="https://avatars.githubusercontent.com/u/171494212?v=4" width="100px;" alt="Rivadian Ardiansyah"/>
  </a>
  <br />
  <sub>Rivadian Ardiansyah</sub>
</td>
<td align="center">
  <a href="https://github.com/resharjuliand">
    <img src="https://avatars.githubusercontent.com/u/171216405?v=4" width="100px;" alt="Reshar Faldi Julianda"/>
  </a>
  <br />
  <sub>Reshar Faldi Julianda</sub>
</td>
  </table>
</div>
