<h2 align="center">
  <p align="center"><i>&ltaksara-jawa/&gt</i></p>
  <!--
  <p align="center"><img src="" width="80%" alt="aksarajs"></p>
  -->
</h2>

Tag element HTML kustom untuk transliterasi Latin ke Aksara.

> Custom HTML element for latin to aksara transliteration.

## Instalasi

Anda bisa memakai paket terkini dari kustom tag ini melalui CDN seperti jsDeliver.

```html
<script defer src="https://cdn.jsdelivr.net/gh/sajenid/aksara-jawa-html/dist/index.mjs"></script>
```

Atau untuk instalasi paket dengan versi yang spesifik misalnya `1.0.0-beta`

```html
<script defer src="https://cdn.jsdelivr.net/gh/sajenid/aksara-jawa-html@1.0.0-beta/dist/index.mjs"></script>

```
## Penggunaan

Pakai tag `<aksara-jawa>` di dokumen HTML dan isi prop `latin` dengan string yang akan di transliterasi ke Aksara Jawa.

```html
<aksara-jawa latin="saksi mata"/>
```
akan menghasilkan dokumen seperti berikut

```html
<span>ꦱꦏ꧀ꦱꦶ​ꦩꦠ</span>
```
---


MIT © 2020, Sajen.id