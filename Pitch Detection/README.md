# Pitch Detection using Traditional Methods Vs ML Methods


While traditional methods can be effective in many pitch detection scenarios, there are situations where they may face challenges or limitations:

1. Complex Harmonic Structures: Traditional methods may struggle to accurately detect pitch in cases where the audio contains complex harmonic structures. For example, when multiple harmonic series or inharmonic partials are present, traditional methods based on simple frequency analysis techniques may fail to identify the fundamental frequency correctly.

2. Noisy Environments: Traditional methods are often sensitive to background noise and other types of distortions in the audio signal. In noisy environments, the accuracy of traditional pitch detection methods may be compromised as the noise interferes with the identification of the fundamental frequency. In contrast, machine learning approaches can learn to filter out noise and focus on relevant features for more robust pitch estimation.

3. Variability in Timbre and Articulation: Different musical instruments and voices produce varying timbre and articulation characteristics, which can influence the perception of pitch. Traditional methods may struggle to account for these variations and might require manual adjustments or instrument-specific calibrations. Machine learning approaches, on the other hand, can learn to capture the nuances and unique characteristics associated with different instruments and voices.

4. Non-stationary Signals: Traditional pitch detection methods often assume stationary signals, where the pitch remains relatively constant over time. However, in certain cases, the pitch may change rapidly or exhibit pitch modulation. Traditional methods may not be well-equipped to handle such non-stationary signals. Machine learning approaches, especially those based on sequence modeling or time-series analysis, can better capture the dynamics and temporal variations in pitch.

5. Lack of Clear Harmonic Structure: In some audio recordings or musical genres, the pitch information may not be well-defined due to unconventional playing techniques, extended techniques, or non-traditional musical structures. Traditional methods that rely on harmonic analysis may struggle to extract meaningful pitch information in such cases. Machine learning approaches can potentially adapt to these complex and non-conventional pitch structures by learning from a diverse range of examples.
