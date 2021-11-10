# a-christmas-carol

https://www.cbc.ca/christmascarol/

## Generating VTT subtitles
```
python3 -m aeneas.tools.execute_task 001_a_christmas_carol.mp4 001_script.txt "task_language=eng|os_task_file_format=vtt|is_text_type=subtitles" map.vtt
```

https://www.readbeyond.it/aeneas/docs/textfile.html#aeneas.textfile.TextFileFormat.SUBTITLES

## Concatenating audio files.
```
ffmpeg -f concat -i playlist.txt -c copy output.wav
```

File :

```
#playlist.txt
file '1.wav'
file '2.wav'
file '3.wav'
file '4.wav'
```

## Cast

https://github.com/ExistentialAudio/BlackHole

https://blog.accusonus.com/voice-changer/siri-voice-generator/

https://ttsmp3.com/text-to-speech/British%20English/

https://play.ht/text-to-speech-voices/british-english/

**Stave 1**

| Character | Voice |
| --- | --- |
| Bob Cratchet (Clerk) | ttsmp3.com - Brian |
| Fred (Scrooge's Nephew) | Siri Male - UK  |
| Narrator | Daniel |
| Scrooge | Oliver |
| Gentleman #1 (donations) | play.ht - James |


**Stave 2**

| Character | Voice |
| --- | --- |
| Marley | Bad News  |
| Narrator | Daniel |
| Scrooge | Oliver |

**Stave 3**

| Character | Voice |
| --- | --- |
| Fezziwig | play.ht - Charlie |
| Narrator | Daniel |
| Scrooge | Oliver |
| Christmas Past | play.ht - Harry |
| Belle | play.ht - Sonia |

**Stave 4**

| Character | Voice |
| --- | --- |
| Narrator | Daniel |
| Scrooge | Oliver |
| Christmas Present | play.ht - Ryan |
| Mrs. Cratchit | Fiona |
| Cratchit girl #1 | ttsmp3.com - Emma |
| 2 young Cratchit girls | Acapela Box - Rosie |
| Martha Cratchit | play.ht - Isla |
| Bob Cratchet (Clerk) | ttsmp3.com - Brian |
| Tiny Tim | play.ht - Anna |
| Fred (Scrooge's Nephew) | Siri Male - UK |
| Scrooge's niece | Kate |
| Plump sister | play.ht - Libby |

**Stave 5**

| Character | Voice |
| --- | --- |
| Narrator | Daniel |
| Scrooge | Oliver |
| Man #1 | play.ht - George |
| Man #2 | play.ht - Thomas |
| Man #3 | play.ht - Brian |
| Woman #1 |  |
| Joe | play.ht - Logan |
| Mrs. Dilber | play.ht - Lily |
| Mrs. Cratchit | Fiona |
| Peter Cratchit | play.ht - Jack |
| Cratchit girl #1 | ttsmp3.com - Emma |
| Bob Cratchet (Clerk) | ttsmp3.com - Brian |
| Boy | Acapela Box - Harry |
| 3-4 fellows |  |
| Girl | play.ht - Hannah |
| Fred (Scrooge's Nephew) | Siri Male - UK |


## Audiograms

https://onlineimagetools.com/pixelate-image
https://github.com/naomiaro/audiogram

## Other links

https://www.youtube.com/watch?v=2qauMSeqWpU

https://www.theguardian.com/technology/2015/aug/12/siri-real-voices-apple-ios-assistant-jon-briggs-susan-bennett-karen-jacobsen

https://www.acapela-group.com/voices/children-voices/

https://www.youtube.com/watch?v=hUkDY3ipHw0


