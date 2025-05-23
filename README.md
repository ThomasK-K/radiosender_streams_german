# Deutsche Radiosender Streams

Eine Sammlung von Streaming-URLs deutscher Radiosender, organisiert nach Kategorien und Sendeanstalten.

## Detaillierte Übersichten
- [Übersicht aller deutschen Radiosender](german_radio_streams.md)
- [Übersicht aller Rock & Metal Sender](rock_metal_streams.md)

## Projektstruktur

```
.
├── german/                      # Öffentlich-rechtliche und private Radiosender
│   ├── 01_deutschlandfunk.m3u  # Deutschlandfunk-Familie
│   ├── 02_wdr.m3u             # Westdeutscher Rundfunk
│   ├── 03_ndr.m3u             # Norddeutscher Rundfunk
│   ├── 04_br.m3u              # Bayerischer Rundfunk
│   ├── 05_hr.m3u              # Hessischer Rundfunk
│   ├── 06_swr.m3u             # Südwestrundfunk
│   ├── 07_mdr.m3u             # Mitteldeutscher Rundfunk
│   └── 08_privatsender.m3u    # Private Radiosender
│
├── rock_metal/                 # Rock und Metal Radiosender
│   ├── delta_radio.m3u        # Delta Radio Familie
│   ├── radio_bob.m3u          # Radio BOB! Familie
│   ├── star_fm.m3u            # Star FM Familie
│   ├── rock_antenne.m3u       # Rock Antenne Familie
│   └── other_rock.m3u         # Weitere Rock-Sender
│
├── german_radio_streams.md     # Übersicht aller deutschen Radiosender
└── rock_metal_streams.md       # Übersicht aller Rock/Metal-Sender
```

## Inhalt

### Öffentlich-rechtliche Sender
- **Deutschlandfunk**: DLF, DLF Kultur, DLF Nova
- **WDR**: 1LIVE, WDR 2-5
- **NDR**: NDR 1, NDR 2, NDR Kultur, N-JOY
- **BR**: Bayern 1-3, BR-Klassik
- **HR**: hr1-4
- **SWR**: SWR1-4 BW
- **MDR**: MDR SACHSEN, MDR JUMP, MDR KULTUR

### Rock & Metal Sender
- **Delta Radio**: Hauptsender und HEAVY
- **Radio BOB!**: 15 Spartensender (Metal, Classic Rock, Hardrock, etc.)
- **Star FM**: 13 Spartensender (Rock, Metal, Alternative, etc.)

## Format

Alle Radiosender sind im M3U-Format gespeichert. Jede .m3u Datei enthält:
- #EXTM3U Header
- Sendername als #EXTINF:-1 Eintrag
- Direkte Stream-URL im MP3-Format

## Verwendung

Die .m3u Dateien können in jedem kompatiblen Media Player geöffnet werden, z.B.:
- VLC Media Player
- Windows Media Player
- Winamp
- foobar2000
- und viele weitere

## Aktualisierung

Die Stream-URLs werden regelmäßig auf Aktualität geprüft und bei Bedarf aktualisiert.
