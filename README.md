#CamPhish
Ambil jepretan kamera dari kamera depan ponsel target atau webcam PC hanya dengan mengirimkan tautan.
![CamPhish](https://i.ibb.co/VTPX0GN/Screenshot-78.png)

# Apa itu CamPhish?
<p>CamPhish adalah teknik mengambil bidikan kamera dari kamera depan ponsel atau webcam PC target. CamPhish Menghosting situs web palsu di server PHP bawaan dan menggunakan ngrok & serveo untuk menghasilkan tautan yang akan kami teruskan ke target, yang dapat digunakan melalui internet. situs web meminta izin kamera dan jika target mengizinkannya, alat ini akan mengambil gambar perangkat target</p>

## Fitur
<p>Dalam alat ini saya menambahkan dua templat laman web otomatis untuk target keterlibatan di laman web guna mendapatkan lebih banyak gambaran kamera</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>cukup masukkan nama festival atau ID video youtube</p>

## Alat Ini Diuji Pada :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

# Instalasi dan persyaratan
<p>Alat ini memerlukan PHP untuk server web, SSH, atau tautan serveo. Pertama jalankan perintah berikut di terminal Anda</p>

```
apt-get -y install php openssh git wget
```

## Instalasi (Kali Linux/Termux):

```
git klon https://github.com/techchipnet/CamPhish
cd CamPhish
bash camphish.sh
```

## Ubah Log:

<p><b>Versi: 1.5:</b> Tambahkan template rapat online baru</p>
<p><b>Versi: 1.4:</b> Pembaruan autentikasi Ngrok</p>
<p><b>Versi: 1.3:</b> Perbaiki tautan langsung ngrok</p>

### Demo Video
[![Demo Pembaruan CamPhish](https://img.youtube.com/vi/i7tvDJx3-yw/0.jpg)](https://www.youtube.com/watch?v=i7tvDJx3-yw)
#### Untuk Video Lainnya, berlanggananlah <a href="http://youtube.com/techchipnet">Saluran YouTube TechChip</a>
<p>CamPhish dibuat untuk membantu pengujian penetrasi dan tidak bertanggung jawab atas penyalahgunaan atau tujuan ilegal apa pun.</p>
<p>CamPhish terinspirasi oleh https://github.com/thelinuxchoice/ Terima kasih banyak kepada @thelinuxchoice</p>
