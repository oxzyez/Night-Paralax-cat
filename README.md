# Night-Paralax-cat
di projek reppo ini gw bikin animasi kucing yang ekornya bergerah. dan projek ini mencerminkan untuk ketenangan kln atau untuk membuat tidur kln tenang

using:
<br>HTML, CSS</br>

## Mengedit / Coding for text

### 1. menambahkan judul
untuk membuat judulnya kalian harus memberi code berikut di html, tapi di luar div container
<br>HTML</br>
```html
        <h3 class="font">Night paralax</h3>
```

untuk mendesign tulisannya agar bagus lu harus import urs stylenya dulu dengan menggcopy import ini ke "style.css" kalian di paling atas text editor kalian
<br>CSS</br>
```html
@import url('https://fonts.googleapis.com/css2?family=Redressed&display=swap');
```

dan styling si titlenya dengan code ini di css kalian
```html
  .font {
    text-align: center;
    font-family: 'Redressed', cursive;
    font-weight: 400;
    font-size: 50px;
    color: aliceblue;
    top: -70px;
    text-shadow: 0 0 7px #01a3c4;
    animation: font 2s ease-in-out infinite;
}
```

untuk menganimasikannya copy code berikut
```html
  @keyframes font {
    50% {
        opacity: 0.4;
      }
}
```

### 2. gradient background
kalian bisa mengganti backgrounnya menjadi gradient linear dengan copy code ini
```html
background: linear-gradient(90deg, #133B5C, #1D2D50);
```

butuh refrensi warna tapi bingung kombinasinya bisa kunjungi website ini: https://colorhunt.co/
pengen cari font yang lebih bagus dan mau berkereasi sendiri kunjungi website ini: https://fonts.google.com/

