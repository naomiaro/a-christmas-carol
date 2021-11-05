# a-christmas-carol

https://www.cbc.ca/christmascarol/

## Generating VTT subtitles
```
python3 -m aeneas.tools.execute_task 001_a_christmas_carol.mp4 001_script.txt "task_language=eng|os_task_file_format=vtt|is_text_type=subtitles" map.vtt
```

https://www.readbeyond.it/aeneas/docs/textfile.html#aeneas.textfile.TextFileFormat.SUBTITLES

## Concatenating audio files.
```
ffmpeg -f concat -i mylist.txt -c copy output.wav
```

File :

```
#mylist.txt
file '1.wav'
file '2.wav'
file '3.wav'
file '4.wav'
```

## Cast

**Stave 1**

https://github.com/ExistentialAudio/BlackHole

https://blog.accusonus.com/voice-changer/siri-voice-generator/

https://ttsmp3.com/text-to-speech/British%20English/


| Character | Voice |
| --- | --- |
| Bob Cratchet (Clerk) | Siri Male - normal |
| Fred (Scrooge's Nephew) | Brian  |
| Narrator | Daniel |
| Scrooge | Oliver - Speaking rate 25% below normal |
| Gentleman #1 (donations) | |


**Stave 2**
Marley - Bad News

