1. Created by: Aleksandar Ivanoski
2. Concordia - app for musicians, by musicians
3. Machine learning
4. Supervised machine learning/digital signal processing that detects chords, tempo and the key of a song input by the user. It is made for musicians for all levels, from beginners struggling with learning songs, to undecisive experts. It helps them find the correct chords/key and makes it easier to learn songs, instead of painstakingly trying to figure them out manually. It also finds the tempo which is useful for cover musicians. It's very simple: user uploads song -> audio is preprocessed (using librosa) -> feature extraction (chroma, onsets, beat tracking) -> analysis modules (tempo detection, key detection, chord detection) -> results shown to user
5. No APIs
6. No datasets
7. Key functions:
Automatic tempo detection - analyzes the rhythmic structure of the uploaded song and automatically detects its tempo in beats per minute.
Musical Key Identification - determines the key (eg. Gmaj, Cmin) of a song.
Chord Recognition Over Time - detects and labels the chords across time
8. Example output:
🎵 Concordia Analysis

Tempo: 124 BPM
Key: A Minor

Chords:
0.00 – 1.23  | Am
1.23 – 2.45  | F
2.45 – 3.67  | C
3.67 – 5.01  | G
