# CulturalClassifier Features

## Features

### low-level features
Low-level features are extracted using the opensource audio feature extranction tool, [OpenSMILE](https://www.audeering.com/opensmile/) 

| Feature Name | Definition |
| --- | --- |
| F0final | The smoothed fundamental frequency contour |
| voicingFinalUnclipped | The voicing probability of the final fundamental frequency candidate. Unclipped means,that it was not set to zero when is falls below the voicing threshold|
| jitterLocal | The local (frame-to-frame) Jitter (pitch period length deviations) |
| jitterDDP | The differential frame-to-frame Jitter (the ‘Jitter of the Jitter’) |
| shimmerLocal | The local (frame-to-frame) Shimmer (amplitude deviations between pitch periods) |
| logHNR | Log of the ratio of the energy of harmonic signal components to the energy of noise like signal components |
| audspec_lengthL1norm | Magnitude of L1 norm of Auditory Spectrum |
| audspecRasta_lengthL1norm | Relative Spectral Transform applied to Auditory Spectrum and lengthL1norm is the magnitude of the L1 norm |
| pcm_RMSenergy | Root-mean-square signal frame energy |
| pcm_zcr | Zero-crossing rate of time signal (frame-based) |
| audSpec_Rfilt (0 ~ 25) | Relative Spectral Transform (RASTA)-style filtered applied to Auditory Spectrum |
| pcm_fftMag_fband250-650 | fft magnitude of frequency band between 250Hz to 650Hz |
| pcm_fftMag_fband1000-4000 | fft magnitude of frequency band between 1000Hz to 4000Hz |
| pcm_fftMag_psySharpness | Psychoacoustic sharpness |
| pcm_fftMag_spectralHarmonicity | Spectral Harmonicity |
| pcm_fftMag_mfcc(1 ~ 14) | Mel-frequency cepstral coefficients 1–14 |
| pcm_fftMag_spectralRollOff25.0 | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralRollOff50.0 | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralRollOff75.0 | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralRollOff90.0 | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralFlux | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralCentroid | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralEntropy | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralVariance | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralSkewness | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralKurtosis | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
pcm_fftMag_spectralSlope | Spectral Features (frequency based features) which are obtained by converting time-based signal into frequency domain using the Fourier Transform |
