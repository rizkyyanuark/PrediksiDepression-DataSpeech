<div align="center">
  <h1>Prediksi Depresi dari Data Speech</h1>
  <blockquote>
    Project ini memanfaatkan metode Mel Frequency Cepstral Coefficients (MFCC) untuk mengekstrak fitur, dan menggunakan Convolutional Neural Networks (CNN) untuk proses pembelajaran dan prediksi mesin.
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

- Proposal :
- HKI : 


## Teams

<div align="center">
  <table style="margin: auto;">
    <tr>
      <td align="center">
  <a href="https://github.com/Dianayuww">
    <img src="https://avatars.githubusercontent.com/u/82692777?v=4" width="100px;" alt="RizkyYanuarK"/>
  </a>
  <br />
  <sub>RizkyYanuarK</sub>
</td>
<td align="center">
  <a href="https://github.com/Dianayuww">
    <img src="https://avatars.githubusercontent.com/u/167867871?v=4" width="100px;" alt="Dian Ayu Fauziah"/>
  </a>
  <br />
  <sub>Dian Ayu Fauziah</sub>
</td>
      <td align="center"><a href="https://github.com/priyanshu92"><img src="https://avatars1.githubusercontent.com/u/7589718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>PRIYANSHU AGRAWAL</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Apriyanshu92" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=priyanshu92" title="Code">💻</a> <a href="#ideas-priyanshu92" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="http://james.greenaway.io"><img src="https://avatars3.githubusercontent.com/u/425261?v=4?s=100" width="100px;" alt=""/><br /><sub><b>James Greenaway</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Ajvgreenaway" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=jvgreenaway" title="Co</td>
    </tr>
  </table>
</div>
