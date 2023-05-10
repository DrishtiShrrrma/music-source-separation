# Pitch Detection using Traditional Methods Vs ML Methods


While traditional methods can be effective in many pitch detection scenarios, there are situations where they may face challenges or limitations:

1. Complex Harmonic Structures: Traditional methods may struggle to accurately detect pitch in cases where the audio contains complex harmonic structures. For example, when multiple harmonic series or inharmonic partials are present, traditional methods based on simple frequency analysis techniques may fail to identify the fundamental frequency correctly.

2. Noisy Environments: Traditional methods are often sensitive to background noise and other types of distortions in the audio signal. In noisy environments, the accuracy of traditional pitch detection methods may be compromised as the noise interferes with the identification of the fundamental frequency. In contrast, machine learning approaches can learn to filter out noise and focus on relevant features for more robust pitch estimation.

3. Variability in Timbre and Articulation: Different musical instruments and voices produce varying timbre and articulation characteristics, which can influence the perception of pitch. Traditional methods may struggle to account for these variations and might require manual adjustments or instrument-specific calibrations. Machine learning approaches, on the other hand, can learn to capture the nuances and unique characteristics associated with different instruments and voices.

4. Non-stationary Signals: Traditional pitch detection methods often assume stationary signals, where the pitch remains relatively constant over time. However, in certain cases, the pitch may change rapidly or exhibit pitch modulation. Traditional methods may not be well-equipped to handle such non-stationary signals. Machine learning approaches, especially those based on sequence modeling or time-series analysis, can better capture the dynamics and temporal variations in pitch.

5. Lack of Clear Harmonic Structure: In some audio recordings or musical genres, the pitch information may not be well-defined due to unconventional playing techniques, extended techniques, or non-traditional musical structures. Traditional methods that rely on harmonic analysis may struggle to extract meaningful pitch information in such cases. Machine learning approaches can potentially adapt to these complex and non-conventional pitch structures by learning from a diverse range of examples.

# Do we Perform Pitch Detection on Individual Audio Stems?

Yes, pitch detection can be performed on individual audio stems. In audio production and music analysis, stems refer to the separate audio tracks or elements that make up a complete mix or composition. These stems can include vocals, instruments, drum tracks, or any other isolated audio components.

Pitch detection on stems can be useful in various applications. For example:

1. Vocal Processing: Pitch detection on vocal stems allows for tasks such as pitch correction, harmonization, or melody extraction. It helps identify the fundamental frequencies of the vocal performances and enables processing techniques like auto-tuning or generating harmony parts.

2. Instrument Analysis: Pitch detection on instrument stems can help in analyzing and transcribing melodies, identifying chord progressions, or extracting melodic patterns. It enables understanding the musical content of individual instruments within a mix.

3. Remixing and Sampling: When working with stems in remixing or sampling scenarios, pitch detection is valuable for aligning different audio elements to a common key or tempo. It aids in ensuring that different stems or samples are harmonically compatible and can be seamlessly integrated.

4. Music Information Retrieval: Pitch detection on stems can contribute to music information retrieval tasks, such as music indexing, content-based searching, or genre classification. Extracting pitch information from individual stems allows for more detailed analysis and indexing of the musical content.
