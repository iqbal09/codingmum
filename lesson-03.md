# CODING MUM

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Lesson 08][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:----------------:|:--------------:|

---

### LESSON 03: STRUKTUR WEBSITE

---

### Tujuan
1. Peserta mengerti struktur website dibentuk dari **HTML** `div`, dibantu **CSS** `float`.
2. Peserta mampu membuat baris dan kolom menggunakan **HTML** `div` dan **CSS** `float`.

---

### Materi

#### 1. HTML dan CSS 1 Kolom
* HTML `index.html`
  ```html
  <div class="parent">
    Ini div 1 kolom
  </div>
  ```
* CSS `style.css`
  ```css
  .parent {
    background-color: #ff0000;
    height: 200px;
    width: 100%;
  }
  ```

#### 2. HTML dan CSS 2 Kolom
* HTML `index.html`
  ```html
  <div class="parent">
    <div class="kolom1">
      Kolom 1
    </div>
    <div class="kolom2">
      Kolom 2
    </div>
  </div>
  ```
* CSS `style.css`
  ```css
  .parent {
    background-color: #ff0000;
    height: 200px;
    width: 100%;
  }

  .kolom1 {
    background-color: #00ff00;
    float: left;
    height: 100px;
    width: 50%;
  }

  .kolom2 {
    background-color: #0000ff;
    float: right;
    height: 150px;
    width: 50%;
  }
  ```

#### 3. HTML dan CSS 3 Kolom
* HTML `index.html`
  ```html
  <div class="parent">
    <div class="kolom1">
      Kolom 1
    </div>
    <div class="kolom2">
      Kolom 2
    </div>
    <div class="kolom3">
      Kolom 3
    </div>
  </div>
  ```
* CSS `style.css`
  ```css
  .parent {
    background-color: #ff0000;
    height: 200px;
    width: 100%;
  }

  .kolom1 {
    background-color: #00ff00;
    float: left;
    height: 50px;
    width: 30%;
  }

  .kolom2 {
    background-color: #0000ff;
    float: left;
    height: 100px;
    width: 40%;
  }

  .kolom3 {
    background-color: #ffff00;
    float: left;
    height: 150px;
    width: 30%;
  }
  ```

---

### Latihan
1. Peserta membuat struktur website **Header**, **Content**, **Sidebar**, **Footer** menggunakan **HTML** `<div>`.
2. Peserta membuat 2 dan 3 kolom bagian website menggunakan **HTML** `<div>` dan **CSS** `float`.

---

### Review
1. Apa yang menjadi bottleneck dari **lesson 03** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 03** ini?

---

### Referensi

---

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Lesson 08][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:----------------:|:--------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Pengenalan Website Development"
[2]: lesson-02.md "HTML dan CSS Dasar"
[3]: lesson-03.md "Struktur Website"
[4]: lesson-04.md "Intro Framework"
[5]: lesson-05.md "Framework Lanjutan"
[6]: lesson-06.md "Personal Project"
[7]: lesson-07.md "Domain, Hosting dan GitHub"
[8]: lesson-08.md "Presentasi"
