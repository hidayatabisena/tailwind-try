# TailwindCSS
Software Developer selalu berusaha untuk membuat / menggunakan tools yang memenuhi **prinsip 80/20** (20% kerja menghasilkan 80% output).

Dan TailwindCSS adalah salah satu **open-source CSS framework** yang masuk kategori prinsip 80/20 tersebut. Setelah mempelajari dokumentasi TailwindCSS di halaman resminya, berikut adalah beberapa benefit TailwindCSS yang saya tangkap:

### Utility class menghadirkan konsistensi design system
TailwindCSS menggunakan pendekatan _utility-first_ yang artinya “_satu class, satu style_”, seperti contohnya `flex`, `pt-4`, `text-center`, `rotate-90` dan sebagainya, yang bisa kita gunakan untuk membuat desain tampilan web langsung dari HTML nya.

Dengan pendekatan tersebut memudahkan kita untuk membuat tampilan yang konsisten contohnya dari segi pewarnaan, jarak spasi, typography, shadow, dan lain-lainnya dengan design system yang proper.

### Kebebasan untuk kustomisasi
Berbeda dengan Bootstrap, TailwindCSS memungkinkan kita untuk melakukan kustomisasi lebih dalam lagi karena sifatnya yang _low-level_, kita tidak butuh tools lagi semacam SASS atau LESS untuk melakukan kustomisasi. 

### Utility-first class
Dengan TailwindCSS, kita bisa membuat halaman website _full-frontend-feature_ tanpa harus meninggalkan HTML. Nama-nama class nya mudah diingat dan mudah dimengerti. It is so beginner friendly, dah. Itu yang terpenting 👌🏻

contohnya seperti ini:
```css
<div class=" bg-indigo-500 text-white px-4 py-4">
<h1> Hello </h1>
</div>
```

Jika dirincikan seperti ini:
- `div` adalah tag HTML
- `bg-indigo-500` : Style background-color dengan warna indigo dan kerapatan density nya 500
- `text-white` : Style text di dalam div akan berwarna putih
- `px-4` : Style untuk memberikan padding, x disini berarti sumbu-x left dan right dari div
- `py-4` : Style untuk memberikan padding, y disini berarti sumbu-y top dan bottom dari div

Kalau pakai CSS murni, mungkin akan banyak code CSS yang perlu kita buat untuk mendapatkan output yang sama. Ingat prinsip 80/20 yang diawal saya sebutkan. 

# Dokumentasi lengkap
Saya berencana untuk memahami TailwindCSS hingga ke akar-akarnya untuk kemudian mempraktekkan apa yang dipelajari. Kedepannya semoga ada kesempatan untuk sharing-sharing mengenai TailwindCSS dan implementasinya.

Sementara itu silahkan dibaca-baca dulu dokumentasi resminya: 
[https://tailwindcss.com/docs](https://tailwindcss.com/docs)

### Hasil percobaan pertama

![Image source]https://user-images.githubusercontent.com/3937792/105792929-cf375d80-5fba-11eb-8eb2-284b889eeece.png)