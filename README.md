# Postselection Controlled Nonclassicality in Multiphoton-Added Cat States

Mathematica notebooks accompanying the manuscript by **Janarbek Yuanbek, Zelalem Abebe Bekele, Bruno Tenorio, and Zhi-qiang Liu**.

## About the paper

The paper studies multiphoton-added cat states (MPACSs) under postselected von Neumann measurements and repeated indirect measurements. The calculations examine postselection success probability, Hillery amplitude-squared squeezing, and Wigner-function negativity. Quantum-trajectory Monte Carlo simulations also explore how sequential measurement statistics evolve from weak-value-dependent conditional shifts toward resolved photon-number outcomes as the number of measurements increases.

## Notebooks

| File | Calculation |
| --- | --- |
| [Fig.2+Ps.nb](Fig.2%2BPs.nb) | Postselection success probability for different measurement and state parameters. |
| [Fig.3+squeezing.nb](Fig.3%2Bsqueezing.nb) | Hillery amplitude-squared squeezing of the postselected pointer state. |
| [Fig.4+Wigner.nb](Fig.4%2BWigner.nb) | Wigner distributions of the postselected MPACSs. |
| [Fig.5+Channel.nb](Fig.5%2BChannel.nb) | Monte Carlo statistics of sequential indirect measurements and MPACS postselection. |
| [Fig.6+Ps_three.nb](Fig.6%2BPs_three.nb) | Comparison of success probabilities for three cat-state phases (Appendix A). |

These notebooks replace the earlier `Fig.2.nb`. Figure numbers in the filenames follow the accompanying manuscript.

## Running the calculations

The manuscript uses **Wolfram Mathematica 15.0** and the **Wolfram Quantum Framework**. Install the framework once, then load it in a Mathematica session:

```wolfram
PacletInstall["Wolfram/QuantumFramework"]
Needs["Wolfram`QuantumFramework`"]
```

Open a notebook in Mathematica and evaluate its input cells in order, starting with a fresh kernel for each notebook. Parameters and plotting settings are defined within the notebooks. Check the destination paths before evaluating optional export cells; some retain paths from the authors' local environment.

## Wolfram Quantum Framework

The [Wolfram Quantum Framework](https://www.wolfram.com/quantum-computation-framework/) integrates symbolic and numerical quantum calculations with Wolfram Language. It provides representations of quantum states, operators, channels, measurements, and circuits, together with tools for time evolution, entanglement analysis, and visualization. In this repository, the squeezing, Wigner, and three-phase probability notebooks load the framework and its second-quantization functionality; the other notebooks use direct Wolfram Language calculations.

See the [official paclet page and documentation](https://resources.wolframcloud.com/PacletRepository/resources/Wolfram/QuantumFramework/) for installation details and examples.
