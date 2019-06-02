---
title: "MEMBUAT WEB RECEHAN SEDERHANA DENGAN DJANGO & HTML/CSS/Js"
description: "Latar Belakang"
date: "2019-06-02T03:21:54.439Z"
categories: []
published: false
---

---

**MEMBUAT WEB RECEHAN SEDERHANA DENGAN DJANGO & HTML/CSS/Js**

**Latar Belakang**

Menurut [Glossaria](http://www.glosaria.com/2018/06/receh.html), **Recehan** berarti humor yang simpel tapi lucu. Recehan sering digunakan kalangan muda untuk bercanda, ataupun berjenaka bersama.

Contoh penggunaan kata:  
 _“Permen, permen apa yang gede banget?”_

_“Apaan?”_

_“Candy Borobudur”  
 “Receh banget dah lo”_

**Masalah**

Pernahkah anda mengalami sebuah situasi dimana anda sedang duduk bersama dengan teman-teman anda, lalu anda ingin sekali menyampaikan sebuah **_recehan,_** tapi anda tidak memiliki inspirasi recehan yang lucu untuk di _send_ ke teman anda?

Website ini adalah jawabannya, dengan menggunakan data yang dikumpulkan secara _crowdsource_ (Google Forms yang diexport ke CSV) menampilkan recehan terbaik menurut beberapa mahasiswa Fasilkom UI, bisa di copy ke clipboard lalu di paste sesuai kebutuhan.

**Solusi**

Website **Recehfy** memiliki database dalam bentuk CSV (Comma seperated values) dan bisa menampilkan semua value recehan dengan indah dan responsif dengan bantuan Django dan juga framework Materialize. Jadi anda tinggal memilih recehan mana yang diinginkan, lalu tekan _copy to clipboard,_ dan masalah anda selesai.

Tampilan Recehfy

**Hal yang digunakan:**

1\. HTML

2\. CSS

3\. Javascript

4\. Django

5\. [Materialize](https://materializecss.com/) (Untuk framework front-end agar responsive)

**Tentang Django**

Apa itu Django?

Django adalah framework _high-level_ Python untuk membuat web.

Mengapa pakai Django?

1\. Aman

Saat kita membuat sebuah projek dengan Django, maka Django akan membuat sebuah page khusus bernama /admin sehingga developer akan aman _for the most part._ Django juga membantu developer yang memiliki MySQL database dan melindungi database tersebut dari beberapa vulnerabilities yang _common_ seperti SQL Injection, CSS (Cross-Site-Scripting),dll

2\. Cepat

Django sangat cepat, tidak perlu banyak _hassle_ untuk membuat sebuah django project. Cukup membuat sebuah Python virtual enviroment, lalu sebuah django project, dan project anda sudah siap.

3\. Batteries Included

Konsep yang sangat _taken granted_ oleh komunitas developernya, Django come _fully loaded and batteries included._ Artinya saat diinstal, Django sudah bisa mengurusi berbagai web task seperti login authentication, content administration, sampai RSS. Semua tanpa plugin tambahan.

4\. Scalable

Tidak perlu takut tentang scalability, 1 user ataupun 1000 user, Django bisa menghandle demand dari user anda.

5\. Komunitas yang ramai

Banyak sekali komunitas Django di dunia maupun di internet, mulai dari mencari views ataupun template, banyak orang yang sudah berkontribusi ataupun memberikan anda bantuan, sehingga anda tidak perlu takut.

Mengapa Django dibuat?

**Sejarah Django**

Dahulu kala, The World Company of Lawrence, Kansas, membuat sebuah project untuk membantu mereka dalam meng_handle_ jurnalisme yang intens yang mereka dapatkan, karena sangat intensnya demand yang mereka dapatkan, akhirnya mereka memutuskan untuk mengganti project mereka dari PHP ke Python. Dari sinilah dibuat sebuah framework untuk membuat web application yang cepat dan serta dari bahasa Python, dan disitulah, Django dilahirkan.

**Cara memakai Django**

1\. Pertama, _make sure_ Python anda sudah Python3, karena jika Python2, anda harus menggunakan Django 1.

2\. Download Django dengan