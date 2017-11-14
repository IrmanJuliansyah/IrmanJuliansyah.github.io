---
layout: post
title: Belajar Membuat Blog Dengan Jekyll
modified:
categories:
excerpt:
tags: []
image:
  feature:
date: 2015-08-02T07:09:00+07:00
---

##Pengenalan Jekyll

Jekyll merupakan sebuah tool untuk membuat blog tanpa menggunakan cms.Halaman blog pada jekyll dibuat dengan format markdown. Markdown adalah sebuah bentuk file yang biasanya digunakan untuk format penulisan. Markdown ditemukan oleh John Gruber. Jekyll ini menyediakan format penulisan markdown yang nantinya akan di convert ke html.

![jekyll.png](../images/jekyll.png)

##Instalasi Jekyll

Untuk dapat melakukan instalasi Jekyll terlebih dahulu install ruby dengan perintah.

Tambahkan repository PPA brightbox.

`sudo apt-add-repository ppa:brightbox/ruby-ng`

Lalu lakukan update

`sudo apt-get update`

Install Ruby 2.1

`sudo apt-get install ruby2.1.6`

Setelah itu, kita bisa langsung menginstall jekyll.

`sudo gem install jekyll`

##Memulai membuat blog dengan Jekyll

Untuk membuat blog dengan jekyll lakukan perintah berikut 

`jekyll new namablogkamu`

contoh jekyll new BlogJekyll.lalu kita akan jalankan servenya dengan perintah

`jekyll serve`

jika berhasil maka akan seperti ini.

![serve.png](../images/serve.png)

selanjutnya buka browser kita dan ketik 'localhost:4000' maka secara default akan seperti ini.

![title.png](../images/title.png)

Jika ingin melakukan merubah tampilan kita dapat merubah dibagian file berikut :

- _config_yml berfungsi sebagai tempat konfigurasi nama blog, nama user dan lain-lain.
- _posts merupakan folder yang berisikan file markdown yang nanti akan di convert ke html.
- _layouts tempat untuk menyimpan file html.
- _includes berisi file html yang merupakan file yang bisa diinclude ke page lainnya seperti header, footer dan sebagainya.

ok sekarang kita lakukan membuat file markdown yang nantinya sebagai tempat penulisan kita di dalam blog.

buat file dengan nama '2015-08-02-belajar-jekyll.markdown' .lalu isi file dengan perintah berikut.
{% highlight text %}

---
layout: post
title:  "Belajar Jekyll"
date:   2015-08-02 07:09:10
categories: jekyll update
---

Hello World, Saya sedang belajar jekyll.

{% endhighlight %}

selanjutnya jalankan kembali dengan perintah `jekyll serve` dan buka browser ketik `localhost:4000`,maka perubahan pun terjadi file markdown kalian sekarang diconvert ke dalam html.

##Hosting ke Github

Setelah kita selesai dibagian jekyll selanjutnya kita akan hosting ke [Github](http://github.com/) jika kalian belum menemukan theme yang sesuai keinginan, kalian dapat mencarinya dengan perintah 'jekyll themes' pada [Google](http://google.com/).

Ok...Jika kalian ingin hosting ke github terlebih dahulu lakukan tahap ini :

- Membuat account [Github](http://github.com/) .
- Instalasi git.
- Membuat repository yang nantinya akan jadi nama hosting kita contoh `Irmanjuliansyah.github.io`.
- Selanjutnya clone repo tersebut dengan perintah 'git clone https://github.com/IrmanJuliansyah/Irmanjuliansyah.github.io.git' sebagai catatan nama clone sesuai dengan nama repo kalian.
- lalu ketik perintah berikut :
{% highlight text %}
git init
git add --all
git commit -m 'initial web'
git remote add origin https://github.com/IrmanJuliansyah/Irmanjuliansyah.github.io.git
git push -u origin master
{% endhighlight %}

Jika berhasil maka kalian dapat mengakses blog kalian sebagai contoh Irmanjuliansyah.github.io
sekian tutorial membuat blog dengan jekyll semoga bermanfaat buat kita semua :) .





