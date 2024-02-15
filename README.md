# Convolution of Audio Signals

This Python script demonstrates audio convolution using a custom convolution function. It allows users to record audio, specify the impulse response length, and convolve the recorded audio with the defined impulse response. Additionally, it provides an option to play the original recording and the convoluted audio.

### Usage

1. **Recording**: Run the script and enter the desired duration for recording when prompted.

2. **Impulse Response**: Enter the length of the impulse response.

3. **Convolution**: The script convolves the recorded audio with the specified impulse response.

4. **Playback**: Listen to the original recording and the convoluted audio.

### Dependencies

- `numpy`
- `matplotlib`
- `sounddevice`
- `scipy`

### How to Run

Ensure you have all dependencies installed. You can install them via pip:

```
pip install numpy matplotlib sounddevice scipy
```

Run the script:

```
python audio_convolution.py
```

Follow the on-screen instructions to record audio and perform convolution.

### Note

- The convolution function used in the script is a custom implementation for educational purposes. Alternatively, you can use the `np.convolve()` function provided by NumPy for faster convolution.
- The recorded audio is saved as `myRecord.mp3`, and the convoluted audio is saved as `myConvolutedRec.mp3`.

---

Feel free to adjust the content according to your preferences or add any additional information you find relevant.
