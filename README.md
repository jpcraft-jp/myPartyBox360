# PartyBox360

Die **PartyBox360** ist ein smartes, modulares und vollständig programmierbares Soundsystem auf Raspberry Pi 5 Basis.  
Ziel ist es, ein leistungsstarkes, mobiles Audio-System zu bauen, das sich flexibel konfigurieren und erweitern lässt – für Festivals, Partys oder Studioanwendungen.

## Features (geplant)

- 🎛️ Web-basiertes UI zur Steuerung (Equalizer, Quellenwahl, etc.)
- 🎚️ Frequenzweiche & Dual-Audio-Output (z. B. Subwoofer separat steuerbar)
- 🎧 Bluetooth-Audioempfang mit Titel- und Coveranzeige
- 🔊 XLR-Ausgänge für professionellen Audioeinsatz
- 🧠 Raspberry Pi 5 CM mit Ubuntu + EasyEffects
- 🔋 Betrieb über Werkzeug-Akkus + Netzbetrieb mit Ladefunktion
- 🌐 SSH-/Webserver-Zugriff & OTA-Updates
- 💡 Optional: LED-Effekte und Display-Integration

## Software Stack

- Python (Backend)
- HTML/CSS/JS (UI)
- C++ für Audiointerface-Ansteuerung
- JSON für Konfigs
- EasyEffects + D-Bus
- Ubuntu ARM64 (Basis)

## Installation (Dev)

```bash
git clone https://github.com/jpcraft-jp/myPartyBox360.git
cd myPartyBox360
# setup scripts folgen noch

