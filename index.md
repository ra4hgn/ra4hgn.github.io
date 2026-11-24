---
layout: default
---

I design and build **open SDR systems for the microwave bands** (13 cm, 6 cm, 3 cm and up) for amateur radio: measurement instruments, signal sources, and — as the lab grows — receivers and transceivers. Everything here is practical and reproducible, from the C/DSP core and GNU Radio flowgraphs to Python GUIs and calibration procedures.

## What you'll find

*   **Instruments & measurement** — analyzers, calibration, power and noise measurements.
*   **Signal sources & transmitters** — beacons, generators, CW and test signals.
*   **Receivers & transceivers** — LNAs, downconverters and full SDR chains (work in progress).
*   **Software & DSP** — GNU Radio blocks and flowgraphs, C/DSP cores, Python tooling and GUIs.
*   **Methods & notes** — measurement techniques and what works, what doesn't, and why.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [pluto-cw-beacon-5.7](https://github.com/ra4hgn/pluto-cw-beacon-5.7) | 5.7 GHz (6 cm) CW beacon transmitter for ADALM-PlutoSDR | C, GNU Radio, IIO |
| [pluto-analyzer](https://github.com/ra4hgn/pluto-analyzer) | 70–6000 MHz scalar S21 analyzer: CLI + PyQt6 GUI, thru calibration, PNG/PDF reports, Touchstone export | Python, PyQt6, libiio |

## How I work

*   Reproducible builds and open licenses (MIT, GPLv3).
*   Every measurement comes with its method: calibration, setup and expected uncertainty.
*   PlutoSDR is the main platform today; new projects are written to be portable to other SDR hardware.

## Roadmap

*   More measurement tools and calibration procedures for the 6 cm and 3 cm bands.
*   Receivers and transceivers for microwave SDR chains.
*   GNU Radio out-of-tree modules for microwave work.

## Contacts

*   GitHub: [@ra4hgn](https://github.com/ra4hgn)
*   QRZ: [RA4HGN](https://qrz.com/db/ra4hgn)

The goal of this site is to document my own experience and make it useful to other amateur radio operators who work with SDR on microwaves.
