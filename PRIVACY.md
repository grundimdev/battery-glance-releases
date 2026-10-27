# Datenschutz bei BatteryGlance

Stand: 27. Oktober 2026 · [English below](#english)

BatteryGlance läuft vollständig auf deinem PC. Die App erhebt keine persönlichen Daten, hat keine Konten, keine Werbung und keine Nutzungsstatistik.

**Was die App liest:** Namen und Akkustände deiner Bluetooth- und USB-Geräte, um sie anzuzeigen. Diese Daten bleiben auf deinem PC.

**Was gespeichert wird:** Einstellungen (`%AppData%\BatteryGlance`), der Akku-Verlauf der letzten 14 Tage, ein Diagnoseprotokoll und auf Wunsch ein Diagnosebericht (`%LocalAppData%\BatteryGlance`). Nichts davon wird verschickt. Den Diagnosebericht gibst du nur weiter, wenn du ihn selbst jemandem schickst.

**Verbindungen ins Internet:** Die über `Setup.exe` installierte Version fragt alle 6 Stunden bei GitHub nach Updates und lädt sie von dort; dabei sieht GitHub deine IP-Adresse ([Datenschutz von GitHub](https://docs.github.com/de/site-policy/privacy-policies/github-general-privacy-statement)). Die Version aus dem Microsoft Store wird über den Store aktualisiert. Sonst baut die App keine Verbindungen ins Internet auf.

**Lokale Verbindungen:** Läuft Logitech G HUB, fragt die App dessen Dienst auf dem eigenen PC (`localhost`) nach Akkuständen. Die optionale Schnittstelle für andere Programme ist ausgeschaltet, bis du sie einschaltest, und nur auf deinem PC erreichbar.

Deinstallierst du die App, kannst du die Ordner oben löschen, um alle Daten zu entfernen.

---

<h2 id="english">Privacy (English)</h2>

BatteryGlance runs entirely on your PC. It collects no personal data and has no accounts, ads or usage statistics.

- **Read:** names and battery levels of your Bluetooth and USB devices, to display them. They stay on your PC.
- **Stored locally:** settings (`%AppData%\BatteryGlance`), 14 days of battery history, a diagnostic log and, on request, a diagnostic report (`%LocalAppData%\BatteryGlance`). None of it is sent anywhere.
- **Internet:** the version installed with `Setup.exe` checks GitHub for updates every 6 hours, so GitHub sees your IP address. The Microsoft Store version is updated by the Store. No other internet connections are made.
- **Local connections:** if Logitech G HUB runs, the app asks its service on `localhost` for battery levels. The optional interface for other programs is off until you turn it on and only reachable from your PC.
