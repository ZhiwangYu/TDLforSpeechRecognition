This paper encompasses all completed experimental studies, comprising four independent programs. All programs were implemented using TensorFlow, with significant reference to the official TensorFlow tutorial code. For instance, the waveform-to-spectrogram conversion program was directly adapted from relevant tutorials. We sincerely appreciate these resources.

The following is an introduction to the execution sequence and primary functionality of each program:

The first program, '1.Wave2Spectrogram.py', employs Short-Time Fourier Transform (STFT) to convert raw audio waveforms into spectrograms. In addition to its core functionality, it provides comparative visualizations of time-domain waveforms and their corresponding frequency-domain spectrograms to illustrate different voice commands.

The second program, '2.Speech2Phoneme.py', primarily utilizes Textgrid files to segment original sentences and paragraphs into phoneme fragments.

The third program, '3.main.py', serves as the primary experimental component of this paper. Initially, the orthogonal feature (OF) convolution kernels were appropriately adjusted. Experiments were then conducted under various conditions, including different datasets, Gaussian white noise perturbations, and whether phoneme filtering was applied (to consider data balance). Notably, audio normalization was applied in this experiment.

The final program, '4.Image2.py', integrates orthogonal features (OF) into image recognition.

These codes demonstrated strong adaptability in the main experiments of this paper. Some experiments were conducted without fixed random seeds, as the results exhibited good stability (although at a signal-to-noise ratio of 0dB, the performance of orthogonal features (OF) was less stable and might even underperform compared to traditional neural networks). In addition, many programs in this study show clear signs of modification, with most having undergone multiple rounds of experimental revision.

Thank you for visiting the homepage of this project. We warmly welcome your suggestions and feedback for further guidance and exchange.
