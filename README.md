# Deutsche Radiosender Streams

Eine Sammlung von Streaming-URLs deutscher Radiosender, organisiert nach Kategorien und Sendeanstalten.

## Detaillierte Übersichten
- [Übersicht aller deutschen Radiosender](german_radio_streams.md)
- [Übersicht aller Rock & Metal Sender](rock_metal_streams.md)

## Projektstruktur

```
.
├── german/                      # Öffentlich-rechtliche und private Radiosender
│   ├── deutschlandfunk.m3u     # Deutschlandfunk-Familie
│   ├── wdr.m3u                # Westdeutscher Rundfunk
│   ├── ndr.m3u                # Norddeutscher Rundfunk
│   ├── br.m3u                 # Bayerischer Rundfunk
│   ├── hr.m3u                 # Hessischer Rundfunk
│   ├── swr.m3u                # Südwestrundfunk
│   ├── mdr.m3u                # Mitteldeutscher Rundfunk
│   ├── rsa.m3u                # Radio Sachsen-Anhalt
│   └── privatsender.m3u       # Private Radiosender
│
├── rock_metal/                 # Rock und Metal Radiosender
│   ├── delta_radio.m3u        # Delta Radio Familie
│   ├── radio_bob.m3u          # Radio BOB! Familie
│   ├── star_fm.m3u            # Star FM Familie
│   ├── rock_antenne.m3u       # Rock Antenne Familie
│   ├── lautfm.m3u            # Laut.fm Metal & Rock Streams
│   ├── oeffentlich_rechtliche.m3u  # Öffentlich-rechtliche Rocksender
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
- **HR**: hr1-4, hr-info
- **SWR**: SWR1-4 BW
- **MDR**: MDR SACHSEN, MDR JUMP, MDR KULTUR
- **RSA**: Radio Brocken, 89.0 RTL, Radio SAW, Rockland
- **RSA**: Radio Brocken, 89.0 RTL, Radio SAW, Rockland

### Rock & Metal Sender
- **Delta Radio**: Hauptsender und HEAVY
- **Radio BOB!**: 15 Spartensender (Metal, Classic Rock, Hardrock, etc.)
- **Star FM**: 13 Spartensender (Rock, Metal, Alternative, etc.)
- **Rock Antenne**: 15 Spartensender (Heavy Metal, Alternative, Classic Rock, etc.)
- **Laut.fm**: Verschiedene Metal & Rock Streams
- **Öffentlich-rechtliche**: Bremen NEXT, Fritz (RBB), DASDING (SWR)

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
