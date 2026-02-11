- OblivionLock Voice AI -
OblivionLock Voice AI adalah tools Text to Speech (TTS) berbasis Python yang berjalan di terminal.
Tools ini bisa mengubah teks menjadi suara Bahasa Indonesia atau English (auto translate).

- Fitur - 
Text to Speech (TTS)
Bahasa Indonesia
Auto Translate Indonesia → English
Output suara .mp3
Auto play suara
Tampilan CLI sederhana

- Instalasi -
Termux
pkg update && pkg upgrade
pkg install python mpv git -y
pip install gTTS googletrans==4.0.0-rc1

Linux / Kali
sudo apt update
sudo apt install python3 python3-pip mpv git -y
pip3 install gTTS googletrans==4.0.0-rc1

- Menjalankan Tools -
git clone https://github.com/barzxploit-01/OblivionLock-Voice
cd OblivionLock-Voice
python OblivionLock-Voice_hard.py

- Cara Pakai -
Jalankan tools
Pilih menu:
1 Bahasa Indonesia
2 English (Auto Translate)
3 Masukkan teks
4 Suara otomatis diputar dan disimpan di folder voices/
