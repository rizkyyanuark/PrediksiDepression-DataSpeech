## Table of Contents

<details>
  <summary>Table of Contents</summary>

  - [Deskripsi](#Deskripsi)
  - [Fitur Utama](#Fitur-Utama)
    - [Vanilla, no framework](#vanilla-no-framework)
    - [With Bootstrap](#with-bootstrap)
    - [With Material Design](#with-material-design)
    - [As Single Select](#as-single-select)
  - [Install](#install)
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

## 🛠️ Teknologi yang Digunakan

- Python
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
- Seaborn

## 📈 Cara Menggunakan

1. Clone repositori ini.
2. Install semua dependensi yang diperlukan.
3. Jalankan notebook Jupyter atau script Python.

## 📚 Referensi

Jika Anda tertarik untuk mempelajari lebih lanjut tentang topik ini, berikut adalah beberapa referensi yang mungkin berguna:

- Understanding Depression: Signs, Symptoms, Causes, and Help
- Machine Learning for Mental Health Prediction

## 🤝 Kontribusi

Kontribusi, masalah, dan permintaan fitur baru selalu diterima. Untuk perubahan besar, harap buka issue terlebih dahulu untuk membahas apa yang ingin Anda ubah.

## 📜 License {#license}

MIT

##📧Kontak

Jika Anda memiliki pertanyaan atau ingin berdiskusi lebih lanjut tentang proyek ini, jangan ragu untuk menghubungi saya.


## Contributors

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.yanoucrea.fr"><img src="https://avatars0.githubusercontent.com/u/966550?v=4?s=100" width="100px;" alt=""/><br /><sub><b>toofff</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Atoofff" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=toofff" title="Code">💻</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=toofff" title="Documentation">📖</a> <a href="#ideas-toofff" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://www.les-tilleuls.coop"><img src="https://avatars3.githubusercontent.com/u/1257968?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Grégory Copin</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3AGregcop1" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=Gregcop1" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/priyanshu92"><img src="https://avatars1.githubusercontent.com/u/7589718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>PRIYANSHU AGRAWAL</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Apriyanshu92" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=priyanshu92" title="Code">💻</a> <a href="#ideas-priyanshu92" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://james.greenaway.io"><img src="https://avatars3.githubusercontent.com/u/425261?v=4?s=100" width="100px;" alt=""/><br /><sub><b>James Greenaway</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Ajvgreenaway" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=jvgreenaway" title="Code">💻</a> <a href="#ideas-jvgreenaway" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/itrombitas"><img src="https://avatars1.githubusercontent.com/u/36223986?v=4?s=100" width="100px;" alt=""/><br /><sub><b>itrombitas</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=itrombitas" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/davehenton"><img src="https://avatars2.githubusercontent.com/u/18341459?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dave Henton</b></sub></a><br /><a href="#infra-davehenton" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/nagaskolli"><img src="https://avatars3.githubusercontent.com/u/4869717?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Swetha Kolli</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=nagaskolli" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/BaarishRain"><img src="https://avatars1.githubusercontent.com/u/13344028?v=4?s=100" width="100px;" alt=""/><br /><sub><b>BaarishRain</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3ABaarishRain" title="Bug reports">🐛</a></td>
    <td align="center"><a href="http://kovacsalexandrurobert.ro"><img src="https://avatars0.githubusercontent.com/u/32507174?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kovacs Alexandru Robert</b></sub></a><br /><a href="#ideas-akovacspentalog" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/amondragon"><img src="https://avatars2.githubusercontent.com/u/11201133?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alexis Mondragon</b></sub></a><br /><a href="#ideas-amondragon" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/Charlie91"><img src="https://avatars2.githubusercontent.com/u/13438795?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Charlie91</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3ACharlie91" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/dhirendrarathod2000"><img src="https://avatars3.githubusercontent.com/u/1930681?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dhirendrasinh</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Adhirendrarathod2000" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/JKapostins"><img src="https://avatars1.githubusercontent.com/u/7006862?v=4?s=100" width="100px;" alt=""/><br /><sub><b>JKapostins</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3AJKapostins" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/josvegit"><img src="https://avatars0.githubusercontent.com/u/24354568?v=4?s=100" width="100px;" alt=""/><br /><sub><b>josvegit</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Ajosvegit" title="Bug reports">🐛</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://twitter.com/LoconLuis"><img src="https://avatars1.githubusercontent.com/u/12422912?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Luis Locon</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Aloconluis" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/mikdatdogru"><img src="https://avatars3.githubusercontent.com/u/10121255?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mikdat DOĞRU</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Amikdatdogru" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/will-izard"><img src="https://avatars1.githubusercontent.com/u/7553535?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Will Izard</b></sub></a><br /><a href="#ideas-will-izard" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://gitlab.com/nikperic"><img src="https://avatars3.githubusercontent.com/u/4504265?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nikola Peric</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Anikolap" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/ramonrf"><img src="https://avatars2.githubusercontent.com/u/6119839?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ramón Alejandro Reyes Fajardo</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Aramonrf" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/sarada-Cheukupalli"><img src="https://avatars3.githubusercontent.com/u/10716099?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sarada Cherukupalli</b></sub></a><br /><a href="#ideas-sarada-Cheukupalli" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/dilip025"><img src="https://avatars1.githubusercontent.com/u/45608461?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dilip Gavara</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=dilip025" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.dealzeit.de"><img src="https://avatars3.githubusercontent.com/u/491877?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Lutz Lengemann</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=mobilutz" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Eainde"><img src="https://avatars0.githubusercontent.com/u/26381655?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Akshay Dipta</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3AEainde" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://langworth.com/"><img src="https://avatars3.githubusercontent.com/u/137158?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Ian Langworth ☠</b></sub></a><br /><a href="#ideas-statico" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/stoberov"><img src="https://avatars1.githubusercontent.com/u/5932031?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Stoyan Berov</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Astoberov" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/ellinge"><img src="https://avatars0.githubusercontent.com/u/17863113?v=4?s=100" width="100px;" alt=""/><br /><sub><b>ellinge</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=ellinge" title="Code">💻</a> <a href="#ideas-ellinge" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-ellinge" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/moonjy1993"><img src="https://avatars3.githubusercontent.com/u/5017449?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sandy M</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=moonjy1993" title="Code">💻</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Amoonjy1993" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://www.gazab.se"><img src="https://avatars1.githubusercontent.com/u/529614?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gustav Tonér</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=gazab" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://kYem.net"><img src="https://avatars1.githubusercontent.com/u/3390897?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kestutis Kasiulynas</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3AkYem" title="Bug reports">🐛</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=kYem" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/isuscbrmid"><img src="https://avatars3.githubusercontent.com/u/20484267?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jesus Cabrera Gonzalez</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=isuscbrmid" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/MJRuskin"><img src="https://avatars2.githubusercontent.com/u/27359753?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MJRuskin</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=MJRuskin" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/akarshjairaj"><img src="https://avatars1.githubusercontent.com/u/64946671?v=4?s=100" width="100px;" alt=""/><br /><sub><b>akarshjairaj</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=akarshjairaj" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/berdyshev"><img src="https://avatars1.githubusercontent.com/u/539090?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Artem Berdyshev</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=berdyshev" title="Code">💻</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Aberdyshev" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://matheushw.com/"><img src="https://avatars3.githubusercontent.com/u/42154031?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Matheus Wichman</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=m4theushw" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/aarce-uncharted"><img src="https://avatars1.githubusercontent.com/u/60662654?v=4?s=100" width="100px;" alt=""/><br /><sub><b>aarce-uncharted</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=aarce-uncharted" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://osmancode.me"><img src="https://avatars0.githubusercontent.com/u/1795294?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mohamad Othman</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=osmancode" title="Code">💻</a> <a href="#ideas-osmancode" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/smurfs2549"><img src="https://avatars3.githubusercontent.com/u/8286468?v=4?s=100" width="100px;" alt=""/><br /><sub><b>kathleenlu</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=smurfs2549" title="Code">💻</a> <a href="https://github.com/dowjones/react-dropdown-tree-select/issues?q=author%3Asmurfs2549" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/r-zane-spalding"><img src="https://avatars.githubusercontent.com/u/88853042?v=4?s=100" width="100px;" alt=""/><br /><sub><b>r-zane-spalding</b></sub></a><br /><a href="https://github.com/dowjones/react-dropdown-tree-select/commits?author=r-zane-spalding" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!
