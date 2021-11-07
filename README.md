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
| Fred (Scrooge's Nephew) | Siri Male - normal  |
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
| Christmas Present |  |
| Mrs. Cratchit |  |
| Cratchit girl #1 | ttsmp3.com - Emma |
| 2 young Cratchit girls |  |
| Martha Cratchit | play.ht - Isla |
| Bob Cratchet (Clerk) | ttsmp3.com - Brian |
| Tiny Tim | play.ht - Anna |
| Fred (Scrooge's Nephew) | Siri Male - normal  |
| Scrooge's niece | |
| Plump sister | |

## Audiograms

https://onlineimagetools.com/pixelate-image
https://github.com/naomiaro/audiogram

## Other links

https://www.youtube.com/watch?v=2qauMSeqWpU

https://www.theguardian.com/technology/2015/aug/12/siri-real-voices-apple-ios-assistant-jon-briggs-susan-bennett-karen-jacobsen

