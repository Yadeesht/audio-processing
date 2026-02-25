PART 1: Dataset Identification & Exploratory Analysis

The notebook named as "Exploratoryanalysis.ipynb" has the details of the dataset choosen.

Analysis Performed
1. Duration and sampling rate analysis
2. Waveform visualization
3. Spectrogram analysis
4. Short-Time Energy (STE) analysis
5. Signal-to-Noise Ratio (SNR) estimation
The comments and my opinon on the analysis made is included in the notebook.


PART 2: Audio Enhancement

The notebook "audioenhancement.ipynb" has signal-processing-based enhancement pipeline to improve speech clarity in the AMI ES2008a meeting audio.

Enhancement Pipeline
1. High-pass filtering (< 80 Hz removal)
2. Spectral noise reduction using noise profile estimation
3. Amplitude normalization

Evaluation:
    Performance was evaluated using:
    Before vs After spectrogram comparison
    Short-Time Energy comparison
    Signal-to-Noise Ratio (SNR) improvement

Output:
    Enhanced WAV file
    Visual comparisons
    Quantitative SNR improvement