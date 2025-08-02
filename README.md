# AI Voice
# 🎙️ TTS Embedding Optimization

A project that reduces Text-to-Speech (TTS) inference time by up to 59% using speaker embedding caching, without compromising audio quality.

## 🚀 Features

- Open-source pretrained TTS model
- Speaker embedding caching for faster generation
- Visual comparison (mel spectrograms, MFCCs, waveforms)
- Audio samples for perceptual analysis

## 📊 Results

| Script | Version         | Gen Time (s) | Total Time (s) | Time Saved |
|--------|------------------|--------------|----------------|------------|
| 1      | Embedded         | 53.58        | 71.80          | ✅ 25%     |
| 1      | Non-Embedded     | 73.57        | 95.27          |            |
| ...    | ...              | ...          | ...            | ...        |

## 📁 Folder Structure

- `audio_samples/` - WAV files of TTS output
- `visuals/` - Spectrograms, waveform comparisons
- `notebooks/` - Jupyter notebooks for testing & visualization
- `results/` - CSVs with benchmarking data

## 🎧 Listen & Compare

Check out the `audio_samples/` and view visual comparisons in `visuals/`.

## 🛠 Tech Stack

- Python
- Librosa
- Matplotlib
- NumPy
- Open-source TTS model (Coqui/Bark/etc.)

## 📄 License

MIT

---
z
