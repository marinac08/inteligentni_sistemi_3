**Created by:** Aleksandar Ivanoski

# Concordia — Audio Intelligence Workspace

### An application for musicians, by musicians

**Category:** Machine Learning • Digital Signal Processing • Music Technology

Concordia is an intelligent music analysis and composition platform designed to assist musicians of all skill levels. Using digital signal processing and supervised machine learning concepts, the application analyzes uploaded audio files to identify harmonic and rhythmic characteristics of a song, helping users learn, study, and create music more efficiently.

The platform automatically processes audio files through a multi-stage analysis pipeline:

**Audio Upload → Signal Preprocessing → Feature Extraction → Harmonic & Rhythmic Analysis → Interactive Results**

During analysis, Concordia performs:

* **Automatic Tempo Detection** – determines the tempo of a song in beats per minute (BPM).
* **Musical Key Identification** – detects the tonal center and key signature of a piece.
* **Chord Recognition Over Time** – identifies chord changes throughout the song and displays them on a timeline.
* **Interactive Playback Tracking** – synchronizes detected chords with audio playback for real-time visualization.
* **Live MIDI Chord Detection** – listens to MIDI input and identifies played chords in real time.
* **AI-Assisted MIDI Generation** – generates chord progressions and downloadable MIDI suites from user prompts such as “Chill Jazz,” “Pop,” or “Dark Cyberpunk.”

The system utilizes audio signal processing techniques including:

* Fourier-based frequency analysis
* Chroma feature extraction
* Harmonic pattern matching
* Beat and rhythm analysis
* Chord template recognition
* MIDI event generation

**Technologies Used**

* JavaScript
* Web Audio API
* Digital Signal Processing (DSP)
* Custom chord-recognition algorithms
* MIDI generation engine

**External APIs:** None

**Datasets:** None

**Target Users**

* Beginner musicians learning songs
* Instrumentalists practicing by ear
* Cover musicians requiring tempo and chord information
* Music producers seeking harmonic analysis
* Composers looking for inspiration through MIDI generation

### Example Analysis Output

🎵 **Concordia Analysis**

**Tempo:** 124 BPM
**Key:** A Minor

**Chord Timeline**

* 0.00 – 1.23 | Am
* 1.23 – 2.45 | F
* 2.45 – 3.67 | C
* 3.67 – 5.01 | G

Concordia combines music theory, signal processing, and machine learning principles to create a practical workspace where musicians can analyze, understand, and generate music more efficiently.
