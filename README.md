# UUV Self-noise Denoising Comparison Demo

This is a web-based demonstration of UUV (Unmanned Underwater Vehicle) self-noise denoising methods, comparing various deep learning approaches with and without SINet enhancement.

## Demo Features

- **Interactive Audio Comparison**: Listen to audio samples processed by different denoising methods
- **Multiple Methods**: Compare UNet, DCCRN, BSRNN, and FullSubNet
- **SINet Enhancement**: See how SINet improves each baseline method
- **Clean Reference**: Compare with original clean audio
- **Responsive Design**: Works on desktop and mobile devices

## Methods Compared

### Baseline Methods
- **UNet**: U-Net architecture for audio denoising
- **DCCRN**: Deep Complex Convolution Recurrent Network
- **BSRNN**: Band-Split RNN for speech enhancement
- **FullSubNet**: Full-band and sub-band fusion model

### Enhanced Methods (Ours)
- **UNet + SINet**: UNet enhanced with SINet
- **DCCRN + SINet**: DCCRN enhanced with SINet
- **BSRNN + SINet**: BSRNN enhanced with SINet
- **FullSubNet + SINet**: FullSubNet enhanced with SINet

## Audio Samples

The demo includes 6 different audio samples with various underwater scenarios:
- Motorboat recordings with different noise levels
- Passenger vessel recordings
- Different underwater conditions (mid-depth, low-depth)

## Usage

Simply open `index.html` in your web browser to start the demo. The interface allows you to:

1. Browse different audio samples
2. Compare noisy vs. clean audio
3. Listen to results from different denoising methods
4. Compare baseline methods with SINet-enhanced versions

## Technical Details

- **Audio Format**: WAV files, 30-second samples
- **Sampling Rate**: Standard audio sampling rates
- **Processing**: Real-time audio comparison interface
- **Compatibility**: Modern web browsers with HTML5 audio support

## Live Demo

Visit the live demo at: [GitHub Pages URL will be here]

## Citation

If you use this demo or the SINet method in your research, please cite:

```bibtex
@article{your_paper,
  title={Your Paper Title},
  author={Your Name},
  journal={Your Journal},
  year={2024}
}
```

## License

This project is licensed under the MIT License - see the LICENSE file for details. 