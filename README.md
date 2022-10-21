# esr_plot

Visualize ESR data with PGFPlots & TikZ.

## Compilation

Compile the document ``main.tex`` with XeLaTeX using MikTeX. When visualizing many line plots it may be necessary to 
expand the main memory size with the additional compiler argument ``--extra-mem-top=100000000``.

## Experimental & Simulated Data

This work contains example ESR data acquired during a practical as well as data simulated with the MatLab software 
package EasySpin. Both are located in the directory ``data``. Complementary kinetic EPR data can be found in the 
repository [``kepr_plot``](https://github.com/Rastow/kepr_plot).

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
- ``esr_daten-4_simulation.txt``: Simulation of the ESR spectra of the galvinoxyl radical using the ``garlic`` function 
from EasySpin.
- ``esr_daten-5.txt``: TEMPO radical in toluene, various concentrations 
(175mM, 125mM, 83mM, 50mM, 25mM, 10mM, 5mM, 1mM, 0.25mM).
- ``esr_daten-5_simulation.txt``: Simulation of the ESR spectra of the galvinoxyl radical using the ``garlic`` function 
from EasySpin.
- ``esr_daten-6_sepr.txt``: _tert_-Butylperoxyl radical generated through UV-irradiation of 10uL 
2,2,4,4-tetramethyl-3-pentanone (5.79M) in 90uL _tert_-butylbenzene.
- ``esr_daten-7_sepr.txt``: Stannyloxy nitroxide generated through two reaction pathways:
  - Pathway 1: 7uL 0.921M 2-methyl-2-nitropropane solution (12.9mM) and 63uL bis(tributyltin) (0.249M) in 430uL 
_tert_-butylbenzene.
  - Pathway 2: 7uL 0.921M 2-methyl-2-nitropropane (12.9mM), 33uL tributyltinhydride (0.247M) and 10 uL 
di-_tert_-butylperoxide (0.109M) in 450uL _tert_-butylbenzene.

## Further Reading

- Stoll, S.; Schweiger, A. EasySpin, a comprehensive software package for spectral simu-
lation and analysis in EPR. _Journal of Magnetic Resonance_ **2006**, _178_, 42–55, DOI:
[10.1016/j.jmr.2005.08.013](https://doi.org/10.1016/j.jmr.2005.08.013).

## License

This work may be distributed and/or modified under the conditions of the LaTeX Project Public License. This work has 
the LPPL maintenance status `maintained'.