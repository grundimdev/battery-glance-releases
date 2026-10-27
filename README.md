<p align="center"><img src="assets/icon.png" width="96" alt=""></p>

<h1 align="center">BatteryGlance</h1>

<p align="center">
  Der Akkustand von Maus, Tastatur, Kopfhörern und Controllern direkt in der Windows-Taskleiste.<br>
  <a href="#english">English below</a>
</p>

<p align="center">
  <a href="https://github.com/grundimdev/battery-glance-releases/releases/latest/download/BatteryGlance-win-Setup.exe"><b>Herunterladen für Windows 10/11</b></a>
</p>

## Was die App kann

- **Ein Blick genügt:** Das Symbol im Infobereich zeigt das Gerät mit dem niedrigsten Akkustand, in Ampelfarben und auf Wunsch mit Prozentzahl.
- **Alle Geräte auf einen Klick:** Ein Klick aufs Symbol öffnet die Übersicht. Bei Earbuds stehen links, rechts und das Etui einzeln da.
- **Rechtzeitig gewarnt:** Eine Benachrichtigung (auf Wunsch mit Warnton) meldet, wenn ein Gerät aufgeladen werden sollte. Die Schwelle stellst du selbst ein.
- **Verlauf:** Ein Klick auf ein Gerät zeigt den Akkustand der letzten Tage und schätzt, wie lange der Akku noch hält.
- **Deins:** Geräte sortieren, ausblenden oder festlegen, welches das Symbol zeigt. Hell und dunkel, Deutsch und Englisch.
- **Für Bastler:** Auf Wunsch stellt die App die Akkustände als JSON unter `http://localhost:47800/api/devices` bereit, z. B. für Rainmeter oder Stream Deck.
- **Hält sich selbst aktuell** und startet mit Windows.

## Unterstützte Geräte

| Art | Geräte |
| --- | --- |
| Bluetooth allgemein | Alle Geräte, deren Akkustand Windows kennt, und Geräte mit dem Bluetooth-LE-Akkudienst |
| Apple | AirPods und Beats (links, rechts, Etui), Magic Keyboard, Magic Mouse, Magic Trackpad |
| Earbuds | Samsung Galaxy Buds, Sony WH-/WF-/LinkBuds, Huawei FreeBuds, Geräte mit Google Fast Pair (Pixel Buds, OnePlus, Nothing, JBL u. a.) |
| Logitech | Unifying, Bolt, Lightspeed und Bluetooth; alles, was Logitech G HUB kennt |
| Gaming | Razer (kabellos), Headsets von SteelSeries, Corsair, HyperX |
| Büro-Headsets | Jabra (Link 380/390, Evolve2), Poly BT600 |
| Controller | Xbox, PlayStation DualSense und DualShock 4 |

Wird ein Gerät nicht erkannt: Rechtsklick aufs Symbol → **Diagnosebericht öffnen**. Der Bericht hilft, das Gerät nachzurüsten.

## Installieren

1. [`BatteryGlance-win-Setup.exe`](https://github.com/grundimdev/battery-glance-releases/releases/latest/download/BatteryGlance-win-Setup.exe) herunterladen und starten. Adminrechte sind nicht nötig.
2. Windows SmartScreen kann warnen, weil die Datei noch nicht signiert ist: **Weitere Informationen → Trotzdem ausführen**.
3. Das Akku-Symbol erscheint im Infobereich der Taskleiste (ggf. über den Pfeil `^` ausklappen).

Deinstallieren über *Einstellungen → Apps*. [Datenschutz](PRIVACY.md)

---

<h2 id="english">English</h2>

BatteryGlance shows the battery level of your mouse, keyboard, headphones and controllers right in the Windows taskbar.

- The tray icon shows the device with the lowest level, color-coded and optionally as a number.
- One click opens the overview; earbuds show left, right and case separately.
- A notification (optionally with a sound) tells you when a device needs charging, at a threshold you choose.
- Click a device for its battery history and an estimate of how long it lasts.
- Reorder or hide devices, pick the one for the icon. Light and dark, German and English.
- Optional JSON interface at `http://localhost:47800/api/devices` for Rainmeter, Stream Deck or scripts.
- Updates itself and starts with Windows.

Supported devices are listed in the table above: standard Bluetooth, AirPods/Beats, Apple Magic devices, Galaxy Buds, Sony, Huawei, Google Fast Pair earbuds, Logitech (incl. G HUB), Razer, SteelSeries, Corsair, HyperX, Jabra, Poly and Xbox/PlayStation controllers.

**Install:** download [`BatteryGlance-win-Setup.exe`](https://github.com/grundimdev/battery-glance-releases/releases/latest/download/BatteryGlance-win-Setup.exe) and run it (no admin rights needed). If SmartScreen warns, choose **More info → Run anyway**. [Privacy](PRIVACY.md#english)
