# Final Audio Design Adagio V
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -9.7; 23 -9.8; 25 -10.0; 28 -10.1; 31 -10.2; 34 -10.3; 37 -10.4; 41 -10.4; 45 -10.5; 49 -10.5; 54 -10.5; 60 -10.5; 66 -10.3; 72 -10.2; 79 -10.1; 87 -10.1; 96 -10.0; 106 -9.8; 116 -9.8; 128 -9.6; 141 -9.5; 155 -9.3; 170 -9.1; 187 -8.9; 206 -8.6; 227 -8.5; 249 -8.2; 274 -7.8; 302 -7.4; 332 -7.0; 365 -6.5; 402 -5.9; 442 -5.4; 486 -4.8; 535 -4.2; 588 -3.5; 647 -2.8; 712 -2.0; 783 -1.3; 861 -0.6; 947 -0.5; 1042 -0.5; 1146 -0.5; 1261 -0.5; 1387 -0.5; 1526 -0.5; 1678 -0.5; 1846 -0.5; 2031 -0.5; 2234 -0.9; 2457 -2.9; 2703 -6.1; 2973 -10.6; 3270 -13.4; 3597 -13.6; 3957 -11.6; 4353 -9.5; 4788 -8.9; 5267 -11.4; 5793 -16.5; 6373 -18.6; 7010 -16.3; 7711 -11.3; 8482 -10.0; 9330 -12.0; 10263 -11.0; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Final Audio Design Adagio V GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Final Audio Design Adagio V ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 66 Hz   | 0.12 | -3.9 dB  |
| Peaking | 2053 Hz | 0.26 | 8.6 dB   |
| Peaking | 3376 Hz | 2.29 | -13.9 dB |
| Peaking | 6375 Hz | 2.24 | -16.4 dB |
| Peaking | 9633 Hz | 4.67 | -5.7 dB  |
| Peaking | 871 Hz  | 2.08 | 1.3 dB   |
| Peaking | 1400 Hz | 0.74 | -1.2 dB  |
| Peaking | 2294 Hz | 2.19 | 1.9 dB   |
| Peaking | 2924 Hz | 8.02 | -1.5 dB  |
| Peaking | 8075 Hz | 9.52 | 0.8 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -3.7 dB |
| Peaking | 62 Hz    | 1.41 | -3.0 dB |
| Peaking | 125 Hz   | 1.41 | -2.6 dB |
| Peaking | 250 Hz   | 1.41 | -1.8 dB |
| Peaking | 500 Hz   | 1.41 | 1.3 dB  |
| Peaking | 1000 Hz  | 1.41 | 5.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 6.4 dB  |
| Peaking | 4000 Hz  | 1.41 | -7.2 dB |
| Peaking | 8000 Hz  | 1.41 | -6.7 dB |
| Peaking | 16000 Hz | 1.41 | 1.1 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/referenceaudioanalyzer/zero/Final%20Audio%20Design%20Adagio%20V/Final%20Audio%20Design%20Adagio%20V.png)