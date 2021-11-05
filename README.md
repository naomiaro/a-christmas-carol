# a-christmas-carol

## Generating VTT subtitles
```
python3 -m aeneas.tools.execute_task 001_a_christmas_carol.mp4 001_script.txt "task_language=eng|os_task_file_format=vtt|is_text_type=subtitles" map.vtt
```

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
