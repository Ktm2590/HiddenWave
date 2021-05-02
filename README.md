# HiddenWave
Embedding secret messages in wave audio file

# What is HiddenWave
Hiddenwave is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

# Requirements
<p>This tool require python3</p>

## Installation

```
git clone https://github.com/techchipnet/HiddenWave.git
cd HiddenWave
```
## Uses
<p>Hiddenwave have two python scripts. </p>
<ul>
<li>HiddenWave.py : for hide secret information.</li>
<li>ExWave.py : for extract secret information for wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python3 HiddenWave.py -f Demo.wav -m "Secret Msg" -o output.wav
```
### Extract Secret Information from Audio file

```
python3 ExWave.py -f output.wav
```

### Video Demo
[![How to control android camera](https://img.youtube.com/vi/G_nNHrWwCOM/0.jpg)](https://www.youtube.com/watch?v=G_nNHrWwCOM)
#### For More Video subcribe <a href="http://youtube.com/techchipnet">TechChip YouTube Channel</a>