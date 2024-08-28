# PI-GaPhI: Gait cycle Phases Identification from Pressure Insoles (INDIP)

Accurate detection of foot-floor contact during gait analysis is crucial for estimating spatio-temporal gait parameters. Variability in the sequence of gait phases (HFPS) is also a key factor in assessing fall risk among the elderly and pathological subjects. This repository introduces ```PI-GaPhI```, an approach designed for automatic and user-independent classification of gait cycle phases based on pressure insoles signals.

Although the use of force platforms and instrumented walkways is direct well-established gold standards approach in this field, it is costly, non-portable, and confined to laboratory environments. Instrumented plantar insoles (pressure insoles) including only sixteen force sensing resistor elements offer a valid alternative, overcoming these limitations.

```PI-GaPhI``` is a robust tool for the accurate and efficient classification of gait phases from pressure insoles data.

## Files description
The following files are provided within the GitHub repository:
- PI-GaPhI: Main function that guides you through all the main steps of Gait Cycle Phases detection;
- openINDIP.m: Function that imports an INDIP text file (".txt") into a MATLAB matrix;
- HFPTSdetect: Function containing detection of gait cycle phases from clustering of pressure insoles channels according to anatomic regions of foot;
- INDIP#098_28-05-2024_132036.txt: INDIP txt file containing representative data acquired from pressure insole and other sensors of a healthy subject during locomotion.

## What the ```PI-GaPhI``` algorithm does:
1.	Load and convert INDIP text file (".txt") into a MATLAB matrix
2.	Detect Gait Cycle Phases from anatomic clustering of channels of PI
3.	Save and visualize results.


## How to prepare your data
INDIP data must be in .txt format to fit the analysis framework.


## How to contribute to ```PI-GaPhI```
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!
1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes
4. Push to the Branch
5. Open a Pull Request

## Disclaimer
This algorithm is provided as-is, and unfortunately, there are no guarantees that it fits your purposes or that it is bug-free.

## Contact
Nicolas Leo, Fellow Research
nicolas.leo@polito.it

