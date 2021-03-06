---
authors:
- admin
date: "2019-04-21T00:00:00+07:00"
draft: false
image:
  caption: 'Image credit: [paulvanderlaken.com](https://paulvanderlaken.com)'
  focal_point: 
  preview_only: false
lastmod: "2019-04-27T00:00:00+07:00"
subtitle: 'Kumpulan cheat sheet library R paling populer. :rocket:'
summary: Kumpulan cheat sheet library R paling populer.
tags:
- R
- Cheat Sheet
title: 'Kumpulan R Cheat [PART 1]'
---

<style>
body{
text-align: justify}
</style>

Pada postingan kali ini penulis akan memberikan kumpulan cheat sheet `R` yang penulis ambil dari berbagai sumber.

## 1. [Base R](http://github.com/rstudio/cheatsheets/raw/master/base-r.pdf)  oleh [Mhairi McNeil](http://mhairihmcneill.com/)

Merupakan cheat sheet yang berguna untuk memahami penggunaan fungsi dasar `R` seperti bagaimana cara membuat matrix, vektor, list, data frame, serta bagaimana bekerja dengannya. 

## 2. [Advanced R](https://www.rstudio.com/wp-content/uploads/2016/02/advancedR.pdf) oleh [Arianne Colton](http://www.ariannecolton.com/) dan Sean Chen

Cheat sheet yang berguna jika pembaca telah menguasai dasar-dasar `R` dan ingin mengembangkan diri keranah yang lebih mahir. Cheat sheet ini berisi kumpulan fungsi bekerja dengan *environment*, *data structures*, *functions*, dan lain-lain pada `R`.

## 3. [Caret](https://github.com/rstudio/cheatsheets/raw/master/caret.pdf) oleh [Max Kuhn](https://www.linkedin.com/in/max-kuhn-864a9110/)

Cheat sheet library `caret` ini berisi bagaimana melakukan modeling dan membuat *machine learning* pada `R` menggunakan library ini. Library ini sangat berguna jika pembaca juga ingin melakukan validasi dan optimasi pada model yang telah pembaca buat karena library ini dapat dibilang menyediakan fungsi yang cukup lengkap.

## 4. [Cartography](https://github.com/rstudio/cheatsheets/raw/master/cartography.pdf) oleh [Timothée Giraud](https://github.com/rCarto)

Cheat sheet yang digunakan untuk bekerja dengan library `cartography`. Cheat sheet ini berguna untuk membuat visualisasi data spasial yang interaktif.

## 5. [data.table](https://github.com/rstudio/cheatsheets/raw/master/datatable.pdf) oleh [Erik Petrovski](https://forskning.ruc.dk/en/persons/erikp)

Jika pembaca pernah melakukan manipulasi data menggunakan library keluarga [tidyverse](http://tidyverse.org/) seperti `dplyr`, `tidyr`, `tibble`, dll. `data.table` adalah library alternatif untuk melakukan manipulasi data seperti `reshaping`, `subseting`, dll dengan kecepatan proses komputasi yang setara dengan library keluarga [tidyverse](http://tidyverse.org/).

## 6. [lubridate](https://github.com/rstudio/cheatsheets/raw/master/lubridate.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`lubridate` merupakan library yang digunakan untuk melakukan pengolahan data dengan format data berupa waktu dan tanggal.Cheat sheet ini berisi bagaimana bekerja dengan jenis data waktu dan tanggal seperti pembulatan tanggal, bekerja dengan zona waktu, melakukan ekstraksi elemen waktu atau tanggal, dll.

## 7. [stringr](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`stringr` meupakan paket yang berguna saat kita ingin berkerja dengan huruf atau string misalnya karakter pada data. Cheat sheet ini memberikan panduan bagi pembaca dalam manipulasi jenis data string pada `R`.

## 8. [purr](https://github.com/rstudio/cheatsheets/raw/master/purrr.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`purr` merupakan salah satu library yang termasuk dalam keluarga library [tidyverse](http://tidyverse.org/). Library ni berguna saat pembaca ingin bekerja dengan list dan function di `R`. Cheat sheet ini akan memberikan kita panduan bagaimana melakukan manipulasi pada list sebaik mengaplikasikan function secara iteratf pada tiap elemen list atau vektor menggunakan library `purr` yang merupakan library alternatif yang memberikan kecepatan dalam proses komputasi dibandingkan keluarga fungsi `apply()` pada `R`.

## 9. [data import](https://github.com/rstudio/cheatsheets/raw/master/data-import.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

Cheat sheet ini memberikan panduan bagaimana membaca flat file (.csv, .tsv, .txt, dll) menggunakan library `readr`, bekerja dengan hasil import berupa tibble serta melakukan *reshape* data yang berantakan dengan `tidyr`. Gunakan library `tidyr` untuk mentransformasi data frame atau tibble menjadi lebih *tidy* yang dapat bekerja lebih lancar dengan `R` dan library [tidyverse](http://tidyverse.org/).

## 10. [Transformasi data](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

Cheat sheet yang memberikan panduan bagi pembaca bagaimana bekerja dengan grammar untuk manipulasi tabel pada dataset yang pembaca miliki menggunkan library `dplyr`. Manipulasi tabel yang dapat dilakukan seperti `select()`, `filter()`, `arrange()`, `mutate()`, `summarise()`, `group()`, dan menggabungkan data frame serta tibble menggunakan kaluarga fungsi `join` yang merupakan alternatif yang lebih *advance* dari fungsi seperti `cbind()` dan `rbind()`.

## 11. [R Markdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`R Markdown` adalah format penulisan yang dapat mempermudah penulisan laporan yang dapat digunakan kembali dengan R. Pembaca dapat menggabungkan kode R dengan narasi yang ditulis dalam markdown (format *plain text* yang mudah ditulis) dan kemudian mengekspor hasilnya menjadi format html, pdf, atau File Word. Pembaca bahkan dapat menggunakan `R Markdown` untuk membuat dokumen interaktif dan slideshow.

## 12. [RStudio IDE](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`RStudio IDE` adalah lingkungan pengembangan terintegrasi paling populer untuk R. Apa pun yang pembaca ingin lakukan dengan `R` (seperti menulis, menjalankan, dan men-*debug* sintaks pada `R`, serta berkeja secara kolaboratif dan kontrol versi, membuat paket, dokumen serta aplikasi), RStudio IDE dapat membantu pembaca melakukannya lebih cepat. Cheat sheet ini akan memandu pembaca memahami fitur-fitur IDE yang paling berguna, serta daftar panjang pintasan keyboard yang ada di dalam `RStudio IDE`.

## 13. [Shiny](https://github.com/rstudio/cheatsheets/raw/master/shiny.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

Cheat sheet ini memberikan panduan bagaimana membangun sebuah website aplikasi interaktif menggunakan library `shiny`. Jika pembaca ingin membuat sebuah laporan dari hasil analisa pembaca kedalam bentuk aplikasi yang interaktif, `shiny` sangat tepat untuk pembaca pertimbangkan sebagai sebuah library untuk membangun aplikasi tersebut.

## 14. [ggplot2](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

Library `ggplot2` membantu pembaca dalam membuat visualisasi data yang cantik dan mudah dikustomisasi. Library ini mengimplementasikan konsep *grammar of graphics* yang merupakan sistem yang mudah digunakan dalam membangun grafik.

## 15. [R Markdown Reference Guide](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf) oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

`R Markdown` merupakan suatu paket yang mengintegrasikan 3 buah perangkat lunak yaitu markdown, knitr, dan pandoc. Cheat sheet ini berisi panduan option yang digunakan pada markdown, knitr, dan pandoc yang digunakan untuk kustomisasi laporan atau slideshow yang akan pembaca buat.

## 16. [Tidyverse](https://datacamp-community-prod.s3.amazonaws.com/e63a8f6b-2aa3-4006-89e0-badc294b179c) oleh [Datacamp Community](https://www.datacamp.com/community/data-science-cheatsheets)

Cheat sheet ini membantu pembaca dalam melakukan tranformasi data menggunakan library keluarga `tidyverse` yaitu `dplyr` serta visualisasi data menggunakan `ggplot2`. Cheat sheet ini sangat cocok digunakan untuk pemula yang baru belajar bagaimana cara melakukan transformasi dan visualisasi pada data.

## 17. [Jupyter Notebook](https://datacamp-community-prod.s3.amazonaws.com/48093c40-5303-45f4-bbf9-0c96c0133c40) oleh [Datacamp Community](https://www.datacamp.com/community/data-science-cheatsheets)

Cheat sheet yang menbantu pembaca dalam menyusun dokumentasi terhadap pekerjaan yang analisis data yang telah pembaca buat menggunakan `Jupyter Notebook`. Pada `Jupyter Notebook` kita tidak hanya dapat bekerja dengan bahasa pemrograman `Python` namun juga `R`. Perangkat lunak dokumentasi ini sama dengan `R Markdown` pada `R`, bedanya `R Markdown` secara luas dapat digunakan untuk penulisan akademik.

## 18. [xts](https://datacamp-community-prod.s3.amazonaws.com/e04c5a6b-4aca-46f5-8cd5-803d975ccc4b) oleh [Datacamp Community](https://www.datacamp.com/community/data-science-cheatsheets?page=2)

`xts` merupakan library yang memiliki fungsi yang relatif sama dengan `lubridate` bedanya adalah `xts` sering digunakan untuk transformasi data menjadi bentuk data *time series*.

## 19. [Reticulate](https://github.com/rstudio/cheatsheets/raw/master/reticulate.pdf) oleh oleh [RStudio](https://www.rstudio.com/resources/cheatsheets/)

[reticulate](https://rstudio.github.io/reticulate/index.html) merupakan sebuah library yang menyediakan seperangkat alat yang komprehensif untuk interoperabilitas antara `Python` dan `R`. Dengan `reticulate`, pembaca dapat memanggil `Python` dari `R` dalam berbagai cara termasuk mengimpor modul `Python` ke dalam skrip `R`, menulis potongan `R Markdown Python`, sumber skrip `Python`, dan menggunakan `Python` secara interaktif dalam  `RStudio IDE`.

