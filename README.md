# GMX-Mail-FakeESIM
GMX apk mit der die ESIM funktionen dauerhaft aktiv sind, auch auf geräten ohne ESIM unterstürtzung, Deutsch DE, APK Download
SureSim&SecureElementAccses nicht mehr nötig

# ----------------------------------
# Geptached APK bei (V12) Release
# ----------------------------------

# 🚀 Selber Patchen?
bash
1. Script speichern
nano CrackGMXAPK.sh

2. Ausführbar machen
chmod +x CrackGMXAPK.sh

3. Ausführen
./CrackGMXAPK.sh

4. Bugs beheben, Script ist nicht getestet
   und wurde anhand meiner konsolen vergangenheit von einem LLm Generiert!
   
# 📋 Voraussetzungen (prüft das Script automatisch)
-adb (Android Platform Tools)  
-apktool  
-apksigner (aus Android SDK build-tools)  
-Python 3  
-Java (für keytool)  
  
# BUG
Bei mir ist die app alle 5sec gecrasht, laut log webview.  
Wenn ein neustart das nicht fixt einmal mit adb verbinden und deaktivieren. 
  
```
adb shell settings put global enable_webview_multiprocess 0
adb reboot
```
