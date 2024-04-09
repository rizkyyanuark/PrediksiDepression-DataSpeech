## Table of Contents

<details>
  <summary>Table of Contents</summary>

  - [Deskripsi](#Deskripsi)
  - [Fitur Utama](#Fitur-Utama)
    - [Vanilla, no framework](#vanilla-no-framework)
    - [With Bootstrap](#with-bootstrap)
    - [With Material Design](#with-material-design)
    - [As Single Select](#as-single-select)
  - [test](#Teknologi-yang-Digunakan)
    - [As NPM package](#as-npm-package)
    - [Using a CDN](#using-a-cdn)
    - [Peer Dependencies](#peer-dependencies)
  - [Usage](#usage)
  - [Props](#props)
    - [className](#classname)
    - [clearSearchOnChange](#clearsearchonchange)
    - [onChange](#onchange)
    - [onNodeToggle](#onnodetoggle)
    - [onAction](#onaction)
    - [onFocus](#onfocus)
    - [onBlur](#onblur)
    - [data](#data)
    - [texts](#texts)
    - [keepTreeOnSearch](#keeptreeonsearch)
    - [keepChildrenOnSearch](#keepchildrenonsearch)
    - [keepOpenOnSelect](#keepopenonselect)
    - [mode](#mode)
      - [multiSelect](#multiselect)
      - [hierarchical](#hierarchical)
      - [simpleSelect](#simpleselect)
      - [radioSelect](#radioselect)
    - [showPartiallySelected](#showpartiallyselected)
    - [showDropdown](#showdropdown)
      - [initial](#initial)
      - [always](#always)
    - [form states (disabled|readOnly)](#form-states-disabled-readonly)
    - [id](#id)
    - [searchPredicate](#searchpredicate)
    - [inlineSearchInput](#inlinesearchinput)
    - [tabIndex](#tabIndex)
    - [disablePoppingOnBackspace](#disablePoppingOnBackspace)
  - [Styling and Customization](#styling-and-customization)
    - [Using default styles](#default-styles)
    - [Customizing with Bootstrap, Material Design styles](#customizing-styles)
  - [Keyboard navigation](#keyboard-navigation)
  - [Performance](#performance)
    - [Search optimizations](#search-optimizations)
    - [Search debouncing](#search-debouncing)
    - [Virtualized rendering](#virtualized-rendering)
    - [Reducing costly DOM manipulations](#reducing-costly-dom-manipulations)
  - [FAQ](#faq)
  - [Doing more with HOCs](/docs/HOC.md)
  - [Development](#development)
  - [License](#license)
  - [Contributors](#contributors)
</details>

## Deskripsi
> Proyek “Prediksi Depresi dari Data Speech” adalah sebuah inisiatif penelitian yang bertujuan untuk mendeteksi tanda-tanda awal depresi melalui analisis suara. Proyek ini menggunakan teknik Mel Frequency Cepstral Coefficients (MFCC) untuk ekstraksi fitur dari data suara, dan Convolutional Neural Networks (CNN) untuk pembelajaran mesin dan prediksi.
> 
> Tujuan utama proyek ini adalah untuk mengembangkan model yang akurat dan efisien yang dapat digunakan dalam aplikasi kesehatan mental untuk mendeteksi dan mencegah depresi pada tahap awal.

## Fitur Utama

- **Analisis Eksploratif Data (EDA)**: Melakukan analisis mendalam pada data untuk memahami pola dan hubungan antar variabel.
- **Pemodelan Machine Learning**: Membangun dan menguji beberapa model Machine Learning untuk memprediksi depresi.
- **Evaluasi Model**: Menggunakan metrik evaluasi yang tepat untuk membandingkan kinerja model.

## Teknologi yang Digunakan

- Python
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
- Seaborn

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

## License {#license}

MIT

## Kontak

Jika Anda memiliki pertanyaan atau ingin berdiskusi lebih lanjut tentang proyek ini, jangan ragu untuk menghubungi saya.


## our Teams
<div align="center">
  <table style="margin: auto;">
    <tr>
      <td align="center"><a href="http://www.yanoucrea.fr"><img src="https://avatars.githubusercontent.com/u/82692777?v=4" width="100px;" alt=""/><br /><sub><b>toofff</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Atoofff" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=toofff" title="Code">💻</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=toofff" title="Documentation">📖</a> <a href="#ideas-toofff" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="http://www.les-tilleuls.coop"><img src="https://avatars3.githubusercontent.com/u/1257968?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Grégory Copin</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3AGregcop1" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=Gregcop1" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/priyanshu92"><img src="https://avatars1.githubusercontent.com/u/7589718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>PRIYANSHU AGRAWAL</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Apriyanshu92" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=priyanshu92" title="Code">💻</a> <a href="#ideas-priyanshu92" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="http://james.greenaway.io"><img src="https://avatars3.githubusercontent.com/u/425261?v=4?s=100" width="100px;" alt=""/><br /><sub><b>James Greenaway</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Ajvgreenaway" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=jvgreenaway" title="Co</td>
    </tr>
  </table>
</div>
