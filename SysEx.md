# Known puc+ SysEx messages
These must be framed correctly within a SysEx message (`f0...f7`) including the BLE-MIDI mandated Timestamp byte before the final `f7`.

## Set MIDI cable to "IN"
00 02 02 62 4d 49 44 49 43 41 42 4c 00 *00* 0e   ...bMIDICABL...

## Set MIDI cable to "OUT"
00 02 02 62 4d 49 44 49 43 41 42 4c 00 *01* 0e   ...bMIDICABL...
