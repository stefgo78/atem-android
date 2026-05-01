# ATEM-ANDROID

Panel do zmiany adresu RTMP w ATEM Mini Pro uruchamiany na Androidzie (Termux), z presetami YouTube, Facebook i własnym RTMP.

## Instalacja

1. Zainstaluj Termux (z F-Droid).
2. Zainstaluj Node.js:
   pkg update && pkg upgrade
  pkg install nodejs git
3. Sklonuj repozytorium:
   git clone https://github.com/TwojeKonto/atem-android.git (github.com in Bing)
  cd atem-android
4. Zainstaluj zależności:
   npm install
5. Ustaw IP ATEM Mini Pro w pliku `server.js`:
   const ATEM_IP = "192.168.1.50";
6. uruchom:
7. npm start
8. Uzycie::
   ## Użycie

Wejdź w przeglądarce na:
http://IP_ANDROID:3000
Możesz:
- wpisać własny RTMP URL + Stream Key  
- kliknąć preset YouTube / Facebook / RTMP1  
