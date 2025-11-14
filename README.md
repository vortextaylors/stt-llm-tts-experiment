# STT → LLM → TTS Experiment
## Introduction
This repository working on real-time voice processing pipeline that integrates Speech-to-Text (STT), Large Language Model (LLM) inference, and Text-to-Speech (TTS) to create an end-to-end conversational system.

## Area of Work
- STT → LLM → TTS: Audio from the user is transcribed, processed by a language model, and converted back to speech for real-time response.
- Partial & Final Transcription: Display partial STT result as the user speaks for live feedback, and use the final transcript to reliably trigger LLM response.
- Voice Activity Detection (VAD) & Silence Detection: Detect when the user stops speaking, enabling accurate end-of-speech detection and natural conversation timing.
- Real-time Streaming: Support low-latency audio streaming for interactive application, with a focus on responsive and natural user experience.
- Noise Robustness & Preprocessing: Improve STT accuracy by handling poor microphone quality and removing background noise through noise suppression, echo cancellation, AGC, and optional filtering.