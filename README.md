ARDUINO IDE
> buka apk ARDUINO IDE. klik file-preferences, salin link 'https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json' dan paste kedalam Additional Boards Manager URLs. klik OK.
> 
>  downloaod Library ZIP esp32 cam pada link Github berikut 'https://github.com/yoursunny/esp32cam.git'
>  
>  klik Sketch - Include Library - Add .ZIP Library - [tambahkan ZIP yang sudah di download] - Add 
>
> klik Tools - Board - Board Manager - [install board esp32 by Espressif Systems]
>
> klik Tools - Board - Board Manager - esp32 - AI Thinker ESP32-CAM
>
> sambungkan ESP32 Cam dengan kabel USB-Micro pada Laptop
> 
> klik Tools - Port - [pilih port yang tersedia]
> 
> salin code pada file 'WifiCam.ino' dan ubah 'WIFI_SSID dan WIFI_PASS' sesuai Jaringan WIFI yang tersambung
>
> upload code lalu tekan serial monitor untuk mendapatkan link url web esp32 cam
> 
> salin link url beserta keterangan resolusi camera

VSCODE 
> buat folder dan file kosong 
>
> copy code file 'obdec.py' dan paste-kan kedalam file kosong yang sudah dibuat
> 
> ubah link url esp32 cam di variable url menjadi link url yang sudah didapat 
> 
> jalankan code dibarengi streamlit yang akan tertera setelah code dijalankan
> 
> halaman akan otomatis berpindah ke web page streamlit
> 
> camera object detection akan muncul pada halaman streamlit dilengkapi data object yang berada dibawah gambar detection
> 
> device (laptop) akan secara otomatis mengeluarkan output berupa suara object yang berapa didepan esp32 cam
> 
> nyalakan bluetooth untuk menghubungkannya ke earphone bluetooth yang sudah disediakan 
