ARDUINO IDE
> > buka apk ARDUINO IDE. klik file-preferences, salin link 'https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json' dan paste kedalam Additional Boards Manager URLs. klik OK.
> > downloaod Library ZIP esp32 cam pada link Github berikut 'https://github.com/yoursunny/esp32cam.git'
> > 
> > klik Sketch-Include Library-Add .ZIP Library
> 
> salin code pada file 'WifiCam.ino' ubah 'WIFI_SSID dan WIFI_PASS' pada code yang berada didalam file 'WifiCam.ino' di aplikasi Arduino IDE. upload code lalu tekan serial monitor untuk mendapatkan link url web esp32 cam
> salin link url beserta keterangan resolusi camera

VSCODE 
> paste link url esp32 cam ke variable url didalam file obdec.py
> jalankan code file python dibarengi streamlit yang akan tertera setelah file obdec dijalankan
> halaman akan otomatis berpindah ke web page streamlit
> camera object detection akan muncul pada halaman streamlit dilengkapi data object yang berada dibawah gambar detection
> device (laptop) akan secara otomatis mengeluarkan output berupa suara object yang berapa didepan esp32 cam
> nyalakan bluetooth untuk menghubungkannya ke earphone bluatooth yang sudah disediakan 
