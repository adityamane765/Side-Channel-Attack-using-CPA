# Side-Channel Attack on AES

This is part of my course project implementing Correlation Power Analysis (CPA) against AES hardware power traces.

The project models the power leakage of AES intermediate values using Hamming weight, then compares these models with measured traces using Pearson correlation. The highest-correlated key-byte guesses are combined and verified through AES decryption and reverse key-schedule analysis.

The implementation also includes trace preprocessing and experiments on both 8-bit and 32-bit AES implementations.
