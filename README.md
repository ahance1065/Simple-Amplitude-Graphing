## 🎵 Audio Amplitude Graphing

This simple waveform graph can be used to visualize the amplitude (dB) changes over time or compare certain song features.

## Purpose
By visualizing the waveforms of different audio samples on a graph like this, anyone can compare instrumental elements and refine their own sound production. For example, if you want to re-create the drums from scratch, you can download the drum audio file from an instrument extractor, and then import the file here to compare the waveforms to your drum samples (The pitch may still need tweaking, but you can get close).
(Today, most DAWs/Editors have these waveforms graphs, but if you want to take a picture to share it with someone, this might be easier)

## Project Status
I am still relatively new to coding. I am working on creating a version with a file upload button, but this current one I did through Kaggle's database/input feature.

## How it Works
1. Loads Audio Samples: The project uses librosa.load() to read and process .wav files.
2. Waveform Visualization: Displays the waveform of each audio file using librosa.display.waveshow().
3. Audio Preprocessing: Removes leading and trailing silence with librosa.effects.trim().
4. Analysis: Enables comparison between different instrumental components for sound recreation.

### Technology Used
1. Python 🐍
2. Librosa (for audio analysis)
3. Matplotlib & Seaborn (for visualization)
4. NumPy & Pandas (for data manipulation)
5. Jupyter Notebook

### Example of Graph
![image](https://github.com/user-attachments/assets/ee042166-be25-4fdb-91cb-1ec1e53382e0)

## Getting Started
1. Clone the repository: git clone https://github.com/yourusername/audio-waveform-analysis.git
2. Install dependencies (or use Kaggle): pip install librosa numpy pandas seaborn matplotlib
3. Run the Jupyter Notebook

## Contributors
This is an independent coding project created by Austin Hance (ahance1065). Feel free to reach out to me for anything. 🚀
