Sebelum memulai analisis kali ini, ada beberapa package yang perlu kita kenali yang akan membantu kita dalam melakukan analisis data, yaitu:
1.	Package dplyr, merupakan package yang paling sering digunakan dalam analisis data dan sangat membantu dalam melakukan data manipulation. Fungsi yang paling sering digunakan dari library ini adalah :
- mutate(), untuk membuat variabel baru berdasarkan variabel yang sudah ada
- select(), untuk memilih variabel berdasarkan namanya
- filter(), untuk memfilter data berdasarkan value dari variabelnya
- summarise(), untuk mengubah beberapa nilai menjadi satu ringkasan nilai
- arrange(), untuk mengurutkan baris data
2.	Package ggplot2, merupakan package yang digunakan untuk membuat plot dengan syntax yang konsisten. Secara umum, untuk membuat plot kita bisa melakukannya dengan memanggil fungsi:
![image](https://user-images.githubusercontent.com/72802495/121839512-6c91f480-cd04-11eb-993d-1ddd73891d2a.png)

Fungsi geom_type bisa kita ganti dengan fungsi yang sesuai dengan jenis plot yang akan dibuat, misalnya geom_line, geom_bar, geom_point, geom_boxplot dan sebagainya.
3.	Package scales, digunakan untuk memformat value data numerik menjadi format yang mudah dibaca. Meskpiun tidak terlalu sering digunakan, package ini sebenarnya sangat membantu kita dalam eksplorasi data. Adapun fungsi yang biasa dipakai dari package ini adalah:
- comma(), untuk mengubah data numerik menjadi simbol ribuan, misalnya 10000000000 yang diubah menjadi 10,000,000,000
- percent(), untuk mengubah data numerik menjadi format persen, misalnya 0.65877 yang diubah menjadi 66%
