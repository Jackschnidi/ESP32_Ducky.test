# DuckyKeyboardESP – Tastatur + Touchpad/Maus

Oberfläche und Tastenliste für Tastenkombinationen stammen aus der GitHub-Pages-Version
(CTRL/ALT/SHIFT/WIN als Checkboxen, Tasten A–Z, 0–9, ENTER, TAB, SPACE, BACK, ESC, Pfeile, F1–F12).
Zusätzlich enthalten: Touchpad, Maus-Klicks, Scrollen, „Tasten freigeben“ (RESET), Leeren, mehrzeiliger Text.

Die Datei `DuckyKeyboardESP_Touchpad.ino` ist unverändert.

## Bluetooth-Name
Im Sketch oben ändern: `#define BLE_DEVICE_NAME "ESP32-S3 Keyboard"`.
Die Webseite filtert nach der Service-UUID und zeigt im Browser-Dialog nur ESP32-Geräte mit diesem Sketch (egal welcher Name); nach dem Verbinden steht der Gerätename im Status.

## GitHub Pages
`index.html`, `style.css`, `app.js` (und README) in den Root-Ordner des Repos hochladen.
Settings → Pages → Deploy from a branch → `main` → `/(root)`. Web Bluetooth braucht HTTPS und Chrome.
