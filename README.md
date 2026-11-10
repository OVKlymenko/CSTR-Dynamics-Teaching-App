# CSTR Dynamics Teaching App

This educational application helps students formulate and analyse dynamic mass and energy balances for modular process systems using tanks, batch reactors and CSTRs as examples. Users can switch inlet, outlet, reaction, and heating/cooling-jacket modules on or off, enter operating parameters, build and check the corresponding balance equations and solve the resulting ODE system numerically. The app visualises reactor configurations and transient concentration, temperature, conversion, and liquid-volume responses, supporting investigation of operating modes, steady-state behaviour, and parameter sensitivity.

Developed by A. Kadir, T. Sire and O.V. Klymenko, School of Chemistry and Chemical Engineering, University of Surrey, UK. Funding support: Fluor Global University Sponsorship Programme (GUSP)

## What this package contains

This release contains compiled binaries for Windows only. Source files are not included.

The installer may download the required MATLAB Runtime components from MathWorks during installation. An internet connection is therefore required for the first installation unless MATLAB Runtime is already installed.

## Installation

### Windows

1. Download the Windows installation file `CSTRLearningAppInstaller.exe`.
2. Extract it to a local folder whose path contains only ASCII characters.
4. Run `CSTRLearningApp.exe`.

## Troubleshooting

- Install the application in a path without non-ASCII characters.
- Run the application from a local disk rather than a cloud-synchronised or network folder.

## Citation

If you use this software in research, cite:

> A. Kadir, T. Sire, O.V. Klymenko, “CSTR Dynamics Teaching App”, version 1.0.0, 2026, https://github.com/OVKlymenko/CSTR-Dynamics-Teaching-App.

## Licence

Use of this application is subject to [`LICENSE.txt`](LICENSE.txt). MATLAB Runtime is a separate MathWorks component and is subject to MathWorks terms. 
