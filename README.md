# Pianolizer

## tl;dr

- [Pianolizer app](https://sysd.org/pianolizer/) - runs directly in the browser. Also, mobile browser. Chrome is recommended for the best experience.
- [Algorithm benchmark](https://sysd.org/pianolizer/benchmark.html) - test the speed of the core algorithm, in the browser. WASM results closely match what is expected from the native binary performance, on the same machine. 44100 samples per second is enough for realtime performance.

## References

- [Piano key frequencies](https://en.wikipedia.org/wiki/Piano_key_frequencies) - Wikipedia article.
- [The Fundamentals of FFT-Based Signal Analysis and Measurement](https://www.sjsu.edu/people/burford.furman/docs/me120/FFT_tutorial_NI.pdf) - tutorial by National Instruments.
- [Sliding DFT](https://en.wikipedia.org/wiki/Sliding_DFT) - Wikipedia article.
- [The Sliding DFT](http://www.comm.toronto.edu/~dimitris/ece431/slidingdft.pdf) - tutorial featuring GNU Octave/MATLAB implementation.
- [The sliding DFT](https://ieeexplore.ieee.org/document/1184347) - Published in: IEEE Signal Processing Magazine (Volume: 20, Issue: 2, March 2003).
- [Sliding Discrete Fourier Transform](http://dream.cs.bath.ac.uk/SDFT/) - Development & Research in Electro-Acoustic Media page.
- [Constant-Q transform](https://en.wikipedia.org/wiki/Constant-Q_transform) - Wikipedia article.
- [Computationally Efficient Moving Average for Microcontrollers](https://www.daycounter.com/LabBook/Moving-Average.phtml) - fast approximation of moving average.

## Copyright

MIT License

Copyright (c) 2022 Stanislaw Pusep