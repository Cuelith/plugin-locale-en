# plugin-locale-en

Modulo lingua inglese di Cuelith. Fonte di verità: il documento di progetto nel repo `cuelith-docs`.

- Solo dati: nessun codice, `runtime: none`. Non aggiungere script o processi.
- Stesse chiavi e stessi segnaposto di `plugin-locale-it`: ogni nuova chiave `core.*` o `protocol.*` va aggiunta nelle due lingue nello stesso giro di lavoro; il test delle lingue del nucleo lo verifica.
- Inglese per chi sta alla regia: frasi semplici e attive, termini del mestiere (Program, Preview, Playlist, Go live, Black, Freeze). Ortografia britannica.
- Le parole fisse del programma restano uguali in ogni lingua (Verse, Chorus, Bridge…: decisione 0005).
- Lavoro su `dev`; `main` riceve solo release taggate (SemVer).
- **Licenza GPL 3.0 o successiva** (decisione 0012), come il nucleo. Le versioni già pubblicate restano Apache; il cambio vale dal prossimo rilascio.
