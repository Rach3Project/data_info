Musicians spend more time practicing than performing live, but the process of rehearsal has been understudied.
The project observes the progression of pianists learning new repertoire over long periods of time by recording their rehearsals, generating a comprehensive multimodal dataset, the **Rach3 dataset**, with video, audio, and MIDI for computational analysis.
This dataset will help investigating the way in which advanced students and professional classical musicians, particularly pianists, learn new music and develop their own expressive interpretations of a piece.

## Where to get the dataset
Due to the sheer size and complexity of the data, we have decided not to release the entire dataset all at once. 
Instead, we will make it accessible to the public in periodic subsections to ensure manageable access. 
The dataset will be found here, with detailed descriptions and regular updates.

If you are interested in working with the dataset, write an email to [Carlos Cancino-Chacón](mailto:carlos_eduardo.cancino_chacon@jku.at).

## Dataset Contents


### Multimodal rehearsal recordings
All rehearsal sessions are captured with synchronized video, audio and MIDI,
allowing for high-precision piano note-level recording. 
Rehearsals have mostly taken place on three pianos: a Yamaha GB1k Silent, an Essex EUP-116E with a built-in silent system, and a Yamaha C1 Disklavier Enspire ST.
To record video, a video camera (GoPro) is placed above the keyboard, capturing the position/movement of the hands (including fingers), arms, head and torso.
Video is recorded at 1080p at 60 frames per second (fps). 
Higher frame rates caused the GoPro to shut down due to overheating, so 60fps was chosen as a compromise between higher resolution and long recording times.

Audio is recorded at 44.1kHz using condenser microphones (2 AKG P120, AKG P170 or AKG P420, depending on the location) connected to a USB audio interface (Focusrite Scarlett 2i2). 

### Rehearsal documentation and subjective experience data.
A rehearsal log chronicles the focus of each rehearsal session, and the Multidimensional Mood State Questionnaire (MDBF) is employed to assess the pianists' mood after each session. 
We will utilize the MDBF questionnaire and the rehearsal log to contextualize day-to-day variations in rehearsal strategies. 
The rehearsal log serves a dual purpose: it documents played pieces or sections for labeling recordings and tracks rehearsal focus, such as strategies or goals, for qualitative analysis, in a similar way to the approaches used by Roger Chaffin's musician colleagues Gabriela Imreh and Tânia Lisboa.

### Machine-readable music scores.
The dataset will also incorporate machine-readable music scores (in formats like MusicXML or MEI) for all pieces.
For practical reasons, we will ask all contributing pianists to concentrate on music from the Common Practice Period, as these pieces are in the public domain and machine-readable scores may already be available online in repositories such as [IMSLP](https://imslp.org/wiki/Main_Page) or [MuseScore](https://musescore.com).
