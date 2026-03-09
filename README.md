# 🎵 UntitledVol1 - Music Data Repository

Willkommen bei **UntitledVol1**. Dies ist ein dediziertes Speicher-Repository für Audio-Assets und Metadaten. 

---

## ⚠️ Wichtiger Hinweis zur Nutzung
Dieses Repository ist **kein** eigenständiger Player. Die hier gespeicherten Dateien sind darauf optimiert, vom **Untitled Music Player** (Flutter App) gestreamt zu werden. 

👉 **Empfehlung:** Nutze für das beste Hörerlebnis die offizielle App. Das direkte Abspielen über die GitHub-Weboberfläche wird nicht empfohlen, da GitHub kein Musik-Streaming-Dienst ist und die Ladezeiten/Buffer dort nicht optimiert sind.

---

## 🏗 Struktur dieses Volumes
Jedes `UntitledVol#` Repository folgt einer festen Struktur, damit die App die Daten automatisch einlesen kann:

* `/covers/` - Enthält die Album-Artworks (empfohlen: `.png` oder `.jpg`, max 500x500px).
* `/songs/` - Enthält die Audio-Dateien (empfohlen: `.mp3`, CBR 192kbps).
* `playlist.json` - Das "Gehirn": Diese Datei verknüpft die Titel mit den Raw-URLs von GitHub.

---

## 🚀 Wie die App die Musik lädt
Die App greift nicht auf die normale GitHub-Ansicht zu, sondern nutzt die **Raw-Content-Schnittstelle**. 

**Beispiel für einen Daten-Link:**
`https://raw.githubusercontent.com/[DEIN_NUTZERNAME]/UntitledVol1/main/songs/storm.mp3`

---

## 🛠 Anleitung: Ein neues Album hinzufügen
1.  Lade die `.mp3` Dateien in den Ordner `/songs/`.
2.  Lade das Cover in den Ordner `/covers/`.
3.  Aktualisiere die `playlist.json` mit den neuen Dateinamen und Titeln.
4.  Starte die App neu – das Album erscheint automatisch im Home-Grid!

---

## ⚖️ Disclaimer
Dieses Repository dient ausschließlich zu privaten Entwicklungs- und Testzwecken im Rahmen des "Untitled Project
