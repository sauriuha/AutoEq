# Sony MDRV-SA5000
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.9; 60 -2.2; 66 -3.3; 72 -4.2; 79 -5.1; 87 -6.0; 96 -6.8; 106 -7.1; 116 -7.1; 128 -7.1; 141 -7.1; 155 -7.2; 170 -6.6; 187 -6.4; 206 -6.3; 227 -6.0; 249 -5.7; 274 -5.3; 302 -5.0; 332 -4.8; 365 -5.6; 402 -6.8; 442 -5.7; 486 -6.0; 535 -6.4; 588 -6.6; 647 -6.8; 712 -7.6; 783 -8.2; 861 -8.9; 947 -9.0; 1042 -7.9; 1146 -6.4; 1261 -5.3; 1387 -5.4; 1526 -6.2; 1678 -7.0; 1846 -8.1; 2031 -9.4; 2234 -11.2; 2457 -12.2; 2703 -11.4; 2973 -9.0; 3270 -6.2; 3597 -1.5; 3957 -1.7; 4353 -5.6; 4788 -4.5; 5267 -0.8; 5793 -0.5; 6373 -1.0; 7010 -4.4; 7711 -7.4; 8482 -11.3; 9330 -12.6; 10263 -7.4; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony MDRV-SA5000 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDRV-SA5000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.2dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 33 Hz   | 0.89 | 7.1 dB  |
| Peaking | 2495 Hz | 2.72 | -6.5 dB |
| Peaking | 3696 Hz | 6.88 | 6.8 dB  |
| Peaking | 5915 Hz | 2.75 | 7.2 dB  |
| Peaking | 8935 Hz | 4.08 | -7.7 dB |
| Peaking | 55 Hz   | 3.08 | 2.0 dB  |
| Peaking | 109 Hz  | 1.19 | -1.7 dB |
| Peaking | 304 Hz  | 2.18 | 1.7 dB  |
| Peaking | 908 Hz  | 2.91 | -2.9 dB |
| Peaking | 1312 Hz | 3.43 | 2.3 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 7.1 dB  |
| Peaking | 62 Hz    | 1.41 | 2.9 dB  |
| Peaking | 125 Hz   | 1.41 | -2.2 dB |
| Peaking | 250 Hz   | 1.41 | 1.5 dB  |
| Peaking | 500 Hz   | 1.41 | -0.1 dB |
| Peaking | 1000 Hz  | 1.41 | -0.0 dB |
| Peaking | 2000 Hz  | 1.41 | -4.4 dB |
| Peaking | 4000 Hz  | 1.41 | 4.6 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.5 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDRV-SA5000/Sony%20MDRV-SA5000.png)