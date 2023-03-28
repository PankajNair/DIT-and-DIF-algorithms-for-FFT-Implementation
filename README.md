# DIT-and-DIF-algorithms-for-FFT-Implementation
DIT (Decimation in Time) and DIF (Decimation in Frequency) are two common algorithms used for calculating the Fast Fourier Transform (FFT) of a discrete signal. These algorithms are efficient and can greatly reduce the computation time required for calculating the FFT.

DIT algorithm breaks down the FFT into multiple smaller FFTs by dividing the input signal into halves and processing them recursively. The input signal is processed in a way that the even-indexed samples are grouped together, and the odd-indexed samples are grouped together, forming two sub-sequences. The algorithm then calculates the FFT of these sub-sequences and combines them to obtain the final FFT.

On the other hand, DIF algorithm breaks down the FFT in a similar manner to the DIT algorithm but in the reverse order. In this algorithm, the input signal is first divided into two sub-sequences with alternating samples. The algorithm then recursively computes the FFT of these sub-sequences and combines them to obtain the final FFT.

The algorithms were implemented using the NumPy and MatPlotLib libraries.
