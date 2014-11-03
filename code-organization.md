# Code Organization for Tonal

What APIs and Libraries will be used.

Javascript, naturally, for Node or Browser, and supported on the key browser platforms:

- Chrome on Desktop and Android
- Safari on Desktoop and iOS
- Firefox on Desktop and Android

[Web Audio API documentation](http://chimera.labs.oreilly.com/books/1234000001552/index.html)

## Libraries to use and their licenses

- [jsfft](https://github.com/dntj/jsfft) Javascript Fast Fourier Transform
    - Not yet tested
- [fft.js](https://github.com/JensNockert/fft.js) this works as a library called by [pitch.js](https://github.com/audiocogs/pitch.js), at least the sound-getting and frequency detection
    - Tested and can detect pitch (tone/frequency) and display it as a number. Need to detect over time and display as a aline.

## Miscellaneous Notes

TONE:

- Spectrogram
- 500hz low pass, F0 contour
- frequency modulation (FM)

STRESS:

- volume
- amplitude modulation (AM)
