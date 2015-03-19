# shairport-sync-metadata-reader
Sample Shairport Sync Metadata Player

This sample program reads the pipe of metadata optionally generated by Shairport Sync. Shairport Sync is an AirTunes emulator with audio synchronization and multi-room capability. (https://github.com/mikebrady/shairport-sync). To use shairport-sync-metadata-reader, take the pipe in via standard input, e.g.

```
shairport-sync-metadata-reader < /tmp/shairport-sync-metadata
```

You'll get an output like this:

```
"ssnc" "pfls": "".
"ssnc" "mdst": "".
Album Name: "Pergolesi: Stabat mater".
Artist: "Andreas Scholl, Barbara Bonney, Christophe Rousset & Les Talens Lyriques".
Comment: "".
Composer: "Giovanni Battista Pergolesi".
Genre: "Classical".
File kind: "Purchased AAC audio file".
Title: "Stabat Mater: I. Stabat mater".
Sort as: "Stabat Mater: I. Stabat mater".
"ssnc" "mden": "".
"ssnc" "sndr": "iTunes/12.1 (Macintosh; OS X 10.10.2)".
Picture received, length 39461 bytes.
"ssnc" "prgr": "2373925818/2373941178/2385081354".
"ssnc" "prsm": "".
```
Please look at the sources of Shairport Sync for documentation, for the present.
