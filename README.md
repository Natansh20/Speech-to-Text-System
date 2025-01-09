# Speech-to-Text-System

Summarized Pipeline:
* Enter Audio File or Use Real-Time Speech Input
  * Users can upload audio files or speak directly for transcription.
* Preprocess Audio
  * Applies wavelet-based noise reduction and audio normalization for improved clarity.
* Transcribe Audio
  * Uses OpenAI Whisper to convert spoken language into accurate text output.

### Detailed Pipeline (Including Rationales and Alternatives)
* Overall Stack: OpenAI Whisper, Gradio

  * OpenAI Whisper: Handles accurate transcription with pre-trained speech models.
  * Gradio: Provides a simple input-output interface for file uploads and real-time speech recognition.
* Audio Preprocessing:
  * Wavelet-based noise reduction ensures clarity in audio.
  * Audio normalization aligns input volumes for consistent transcription quality.
* Transcription:
  * OpenAI Whisper offers robust performance across accents and speaking styles.
* Frontend:
  * Gradio simplifies user interaction and supports file upload and real-time speech input.
