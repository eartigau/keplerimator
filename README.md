# Keplerian Guestimator

Simple browser-based tool for precision-RV planning.

## Features

- Computes and plots RV semi-amplitude `K` (m/s) vs orbital period for input stellar and planet masses.
- Computes and plots equilibrium temperature `Teq` vs orbital period.
- Computes required planet mass vs period for an input RV threshold `K`.
- Marks optimistic and conservative habitable zone (HZ) period ranges.

## Inputs

- Stellar mass in solar units (`Msun`)
- Planet mass in Earth units (`Mearth`)
- Target `K` in m/s (for inverse curve)
- Bond albedo (for equilibrium temperature)

## Model assumptions

- Circular orbit, edge-on (`e = 0`, `sin(i) = 1`).
- Main-sequence star relations for luminosity and radius (quick-look approximation).
- Equilibrium temperature with full heat redistribution.
- HZ boundaries from:
  - Kopparapu et al. 2013, ApJ 765, 131
  - Kopparapu et al. 2014, ApJL 787, L29

## Run

Open `index.html` in any modern browser.
