# semantic_chunking_of_a_youtube_video

The objective of this projevt is to extract high-quality, meaningful (semantic) segments from a specified YouTube video.

Workflow:

1.**Download Video and Extract Audio**: Download the video and separate the audio component.

2.**Transcription of Audio**: Using **Whisper.ai** an open-source Speech-to-Text model to transcribe the audio. 

3.**Time-Align Transcript with Audio**: Describe the methodology and steps for aligning the transcript with the audio.

4.**Semantic Chunking of Data**: Slicing the data into audio-text pairs, using both semantic information from the text and voice activity information from the audio, with each audio-chunk being less than 15s in length. 
