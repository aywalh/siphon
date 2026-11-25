<p align="center">
  <img src="assets/banner.png" alt="Siphon: save any video, audio or image from any site" width="100%">
</p>

<p align="center">
  <a href="https://github.com/aywalh/siphon/releases/latest"><img src="https://img.shields.io/github/v/release/aywalh/siphon?style=for-the-badge&color=007AFF&label=latest" alt="latest release"></a>
  <a href="https://github.com/aywalh/siphon/releases"><img src="https://img.shields.io/github/downloads/aywalh/siphon/total?style=for-the-badge&color=34C759" alt="downloads"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-1d1d1f?style=for-the-badge&logo=windows" alt="Windows 10 / 11">
  <img src="https://img.shields.io/badge/Brave%20%C2%B7%20Chrome%20%C2%B7%20Edge%20%C2%B7%20Opera-1d1d1f?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Brave, Chrome, Edge, Opera">
</p>

<h3 align="center">
  Videos, Musik und Bilder von jeder Seite speichern – mit einem Klick, direkt auf deinem PC.<br>
  <a href="https://github.com/aywalh/siphon/releases/latest/download/Siphon.zip">⬇️ Siphon.zip herunterladen</a>
</h3>

---

## ✨ Was Siphon kann

- 🎬 **Videos** in bis zu 4K. YouTube, TikTok, Instagram, Pinterest, X, Reddit, Twitch, Vimeo, Facebook und über 1800 weitere Seiten.
- 🎵 **Audio als MP3** mit Cover und Titel. Ideal für Musik, Podcasts, SoundCloud und Bandcamp.
- 🖼️ **Bilder** in der größten Auflösung, die eine Seite hat. Ein einzelnes Bild oder alle auf einmal.
- 📸 **TikTok-Fotoposts** werden zu einem Video mit Ton.
- 🖱️ **Rechtsklick** auf ein Video, Bild oder Audio → *Siphon this …*. Das Popup brauchst du dafür nicht.
- 🔐 **Private Inhalte**, die du selbst sehen darfst, zum Beispiel Videos mit Altersgrenze. Dafür nutzt Siphon deinen Login aus dem Browser.
- 🔄 **Updates mit einem Klick** direkt im Popup.

## 🖥️ So sieht es aus

<p align="center"><img src="assets/popup.png" alt="Siphon Popup" width="372"></p>

Öffne eine Seite mit einem Video und klick auf das Siphon-Symbol. Dann wählst du **Video**, **Audio** oder **Images**, stellst die Qualität ein und klickst auf **Save**. Fertig.

Die Dateien landen in **`Downloads\Siphon`**.

## 📦 Installation (einmalig, ca. 3 Minuten)

1. **[Siphon.zip herunterladen](https://github.com/aywalh/siphon/releases/latest/download/Siphon.zip)** und entpacken.
   Leg den Ordner an einen festen Platz, zum Beispiel `Dokumente\Siphon`. Er bleibt dort, denn der Browser lädt Siphon direkt aus diesem Ordner.
2. Im Ordner **`INSTALL.bat`** doppelklicken.
   Das Skript installiert alles, was fehlt: Python, ffmpeg, yt-dlp, gallery-dl und deno.
   Fragt es nach der Python-Installation, ob du es nochmal starten sollst? Dann einfach nochmal doppelklicken.
   Danach öffnet sich ein **30-Sekunden-Video**, das die nächsten Schritte zeigt. Schau es dir an, es lohnt sich! 😉
3. Den Browser öffnen:
   - Brave: `brave://extensions`
   - Chrome: `chrome://extensions`
   - Edge: `edge://extensions`
   - Opera: `opera://extensions`

   Dort den **Entwicklermodus** einschalten, auf **Entpackte Erweiterung laden** klicken und den **Siphon**-Ordner auswählen.
4. Siphon in der Symbolleiste anpinnen (🧩 → 📌), das Popup öffnen und auf **Start Siphon** klicken.

<p align="center"><img src="assets/tutorial.png" alt="Das Installations-Video" width="80%"></p>

> [!TIP]
> Windows SmartScreen meldet „Der Computer wurde durch Windows geschützt“? Klick auf **Weitere Informationen** und dann auf **Trotzdem ausführen**. Das kommt, weil `INSTALL.bat` nicht signiert ist.

## 🔄 Updates

<p align="center"><img src="assets/update.png" alt="Update im Popup" width="372"></p>

Gibt es eine neue Version, zeigt das Popup oben **Update**. Ein Klick genügt: Siphon lädt die neue Version von hier, prüft sie und ersetzt die alten Dateien. Dabei bringt es auch yt-dlp & Co. auf den neuesten Stand und startet sich neu.

Laufende Downloads lass vorher fertig werden. Deine Einstellungen und deine Dateien bleiben erhalten.

## 🛟 Wenn etwas nicht geht

| Problem | Lösung |
|---|---|
| Popup zeigt **Siphon is off** | Auf **Start Siphon** klicken. Klappt das nicht, `INSTALL.bat` nochmal ausführen. |
| Eine Seite wird nicht erkannt | Seite neu laden (F5) und es nochmal versuchen. Oder Rechtsklick direkt aufs Video → *Siphon this video*. |
| YouTube / TikTok geht plötzlich nicht mehr | Das liegt meistens an einer Änderung auf der Seite. Auf ein Update warten oder `INSTALL.bat` nochmal ausführen, das holt das neueste yt-dlp. |
| Privates Video geht nicht | Im Popup **Use my login** einschalten und auf der Seite eingeloggt sein. |
| Status zeigt **no ffmpeg** | `INSTALL.bat` nochmal ausführen und den Browser einmal neu starten. |
| Ordner verschoben | `INSTALL.bat` im neuen Ordner ausführen und die Erweiterung neu laden. |
| Symbol zeigt rotes **!** nach Rechtsklick | Dort wurde nichts gefunden, oder Siphon ist aus. |

## 🔒 Privatsphäre

- Alles läuft **auf deinem PC**. Es gibt keinen Account, keinen Server und kein Tracking.
- Der Helfer hört nur auf `127.0.0.1` und nimmt nur Anfragen von Browser-Erweiterungen an.
- **Use my login** reicht die Cookies der aktuellen Seite nur an den lokalen Helfer weiter. Er löscht sie nach dem Download wieder.
- Ins Internet geht nur die Anfrage an die Seite, von der du lädst. Dazu kommt höchstens einmal pro Stunde eine Abfrage an GitHub, ob es ein Update gibt.

## 🗑️ Deinstallieren

1. Die Erweiterung auf der Erweiterungsseite deines Browsers entfernen.
2. Im Ordner `Siphon\helper` in der Adresszeile `cmd` eingeben und dann ausführen:
   ```bat
   py register.py --remove
   ```
3. Den Siphon-Ordner löschen.

---

<sub>Dieses Repository enthält nur die Downloads, der Quellcode wird hier nicht veröffentlicht. Siphon nutzt <a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a>, <a href="https://github.com/mikf/gallery-dl">gallery-dl</a> und <a href="https://ffmpeg.org">ffmpeg</a>. Lade nur Inhalte herunter, die du speichern darfst: Viele Plattformen verbieten das in ihren Nutzungsbedingungen, und die Rechtslage ist je nach Land unterschiedlich.</sub>
