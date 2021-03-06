# HiFiMAN HE-500
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.9; 25 -1.2; 28 -1.6; 31 -1.9; 34 -2.1; 37 -2.2; 41 -2.2; 45 -2.2; 49 -2.1; 54 -2.2; 60 -2.7; 66 -2.8; 72 -2.9; 79 -2.9; 87 -3.2; 96 -3.3; 106 -3.5; 116 -3.5; 128 -3.7; 141 -3.9; 155 -3.9; 170 -4.0; 187 -4.1; 206 -4.0; 227 -4.2; 249 -4.3; 274 -4.5; 302 -4.3; 332 -4.2; 365 -4.4; 402 -4.0; 442 -4.2; 486 -4.4; 535 -4.1; 588 -4.3; 647 -4.0; 712 -3.3; 783 -2.6; 861 -3.2; 947 -3.2; 1042 -3.6; 1146 -3.1; 1261 -2.8; 1387 -2.2; 1526 -2.7; 1678 -2.2; 1846 -0.8; 2031 -0.5; 2234 -2.4; 2457 -0.7; 2703 -0.8; 2973 -2.4; 3270 -2.8; 3597 -2.7; 3957 -3.2; 4353 -4.9; 4788 -4.5; 5267 -1.3; 5793 -1.1; 6373 -2.9; 7010 -3.4; 7711 -3.8; 8482 -7.0; 9330 -9.3; 10263 -4.7; 11289 -3.5; 12418 -3.5; 13660 -3.5; 15026 -3.5; 16529 -3.5; 18182 -6.1; 20000 -8.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`HiFiMAN HE-500 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN HE-500 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.2dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 21 Hz   |  1.33 | 2.9 dB  |
| Peaking | 49 Hz   |  2.37 | 1.1 dB  |
| Peaking | 2138 Hz |  1.7  | 2.6 dB  |
| Peaking | 5668 Hz |  7.49 | 3.1 dB  |
| Peaking | 9177 Hz |  5.29 | -6.5 dB |
| Peaking | 345 Hz  |  0.65 | -0.9 dB |
| Peaking | 783 Hz  |  8.04 | 1.2 dB  |
| Peaking | 2642 Hz | 10.41 | 1.3 dB  |
| Peaking | 4571 Hz |  5.29 | -3.2 dB |
| Peaking | 5031 Hz |  2.82 | 1.3 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-2.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.0 dB  |
| Peaking | 62 Hz    | 1.41 | 0.6 dB  |
| Peaking | 125 Hz   | 1.41 | -0.2 dB |
| Peaking | 250 Hz   | 1.41 | -0.8 dB |
| Peaking | 500 Hz   | 1.41 | -0.6 dB |
| Peaking | 1000 Hz  | 1.41 | -0.0 dB |
| Peaking | 2000 Hz  | 1.41 | 2.4 dB  |
| Peaking | 4000 Hz  | 1.41 | 0.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.9 dB |
| Peaking | 16000 Hz | 1.41 | -0.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/HiFiMAN%20HE-500/HiFiMAN%20HE-500.png)