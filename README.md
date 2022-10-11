# esr_plot

Visualize ESR data with PGFPlots & TikZ.

## Compilation

Compile the document ``main.tex`` with XeLaTeX using MikTeX. When visualizing many line plots it may be necessary to 
expand the main memory size with the additional compiler argument ``--extra-mem-top=100000000``.

## Experimental & Simulated Data

This work contains example ESR data acquired during a practical as well as data simulated with the MatLab software 
package EasySpin. Both are located in the directory ``data``.
- ``esr_daten-1_attenuation.txt``: 100ug DPPH radical in 0.5ml toluene with variation of the microwave attenuation
(3dB, 7dB, 12dB, 17dB, 23dB, 30dB).
- ``esr_daten-1_modulation.txt``: 100ug DPPH radical in 0.5ml toluene with variation of the modulation amplitude
(0.005mT, 0.02mT, 0.1mT, 0.3mT, 0.5mT, 0.7mT).
- ``esr_daten-1_simulation.txt``: Simulation of the ESR spectra of DPPH with linewidth 1mT and 0.1mT using the 
``garlic`` function from EasySpin.
- ``esr_daten-2.txt``: Aqueous manganese(II)sulfate solution.
- ``esr_daten-3.txt``: Copper(II)chloride and copper(II)sulfate powder spectra.
- ``esr_daten-3_simulation.txt``: Simulation of resolved rhombic and axial copper(II) powder spectra with arbitrary 
hyperfine couplings using the ``pepper`` function from EasySpin.
- ``esr_daten-4.txt``: 100ug galvinoxyl radical in 1ml toluene (aerated, degassed with nitrogen).
- ``esr_daten-5.txt``: TEMPO radical in toluene of various concentrations 
(175mM, 125mM, 83mM, 50mM, 25mM, 10mM, 5mM, 1mM, 0.25mM).

## License

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License. This work has 
the LPPL maintenance status `maintained'.