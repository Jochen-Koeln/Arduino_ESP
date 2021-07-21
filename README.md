# Arduino_ESP

## IDE installieren

1. Über arduino.cc downloaden.
2. Zip entpacken.
3. Im neuen Arduino-Verzeichnis das Unterverzeichnis »portable« anlegen.
4. Im neuen Arduino-Verzeichnis ein Terminal öffnen.
5. Datei »./arduino-linux-setup.sh $USER« ausführen.

> ******* Add User to dialout,tty, uucp, plugdev groups *******

> ******* Removing modem manager *******

> *********** Please Reboot your system ************

7. Rebooten

## IDE einrichten

### Einstellungen

1. Datei → Voreinstellungen
2. Im Feld »Zusätzliche Bordverwalter-URLs« eingeben: `https://dl.espressif.com/dl/package_esp32_index.json,http://arduino.esp8266.com/stable/package_esp8266com_index.json`
3. ☑ Zeilennummern anzeigen 
4. ☑ Code nach dem Hochladen
5. ☑ Beim Start nach Updates suchen
6. ☐ use accesibily features
7. ☑ Code-Faltung aktivieren
8. ☐ Externen Editor verwenden
9. ☑ Speichern beim Überprüfen oder Hochladen
10. »ok« klicken

### Bordverwaltung

1. Werkzeuge → Board: "XXX" → Boardverwalter
2. Suchen nach »esp«
3. »esp32« (by Espressif Systems) installieren
4. »esp8266« (by ESP8266 Community) installieren
5. »schließen« klicken

### Python ergänzen

1. `sudo apt install python2.7`
2. `sudo apt install python2.7`
3. `pip install pyserial`
4. `sudo apt install python3-pip`
5. `pip3 install pyserial`


### ESP8266 testen

#### Beispiel alter Wemos D1 mini
1. Modul anschließen
2. Werkzeuge → Board: "XXX" → ESP8266 Boards → LOLIN(WeMos) D1 R1
3. Werkzeuge → Port: wählen
4. Datei → Beispiele → ESP8266WiFi → WiFiScan
5. Sketch → Hochladen
