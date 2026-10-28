### Hamoud Alshammari

Aerospace engineer working on satellite navigation, estimation and orbital mechanics. Most of what's here started as a question I wanted to answer properly: does this filter actually behave the way the textbook says, does this propagator really match the reference, are these protection levels honest? So the repos tend to come with tests, validation runs and the numbers to back them up.

The thread through most of it is trust in space-derived numbers: an orbit, a gravity field, a position fix. How good is the covariance, and how do you tell when the model behind it has gone wrong? Lately that means LEO navigation, integrity monitoring, maneuver detection, and reference frames beyond Earth orbit.

M.S.E. in Aerospace Engineering from UT Austin, including research at the Center for Space Research on lunar geodesy and reference frames. Now working in the space industry on satellite communications, navigation and Earth observation.

**GNSS & navigation**

- [gnss-integrity-raim](https://github.com/OrbitAR7/gnss-integrity-raim): snapshot RAIM with chi-square fault detection/exclusion and slope-based protection levels, checked by Monte Carlo
- [gnss-pseudorange-solver](https://github.com/OrbitAR7/gnss-pseudorange-solver): header-only C++ least-squares positioning with Sagnac correction, tested against known truth
- [constellation-dop-analyzer](https://github.com/OrbitAR7/constellation-dop-analyzer): DOP of GPS, Galileo, BeiDou and Starlink geometry from real TLEs

**Estimation & dynamics**

- [EstimationToolkit.jl](https://github.com/OrbitAR7/EstimationToolkit.jl): 36 filters in Julia (sigma-point family, IMM/GPB multiple-model, particle flow, information form) with a LEO maneuver-detection example
- [tle-sgp4-cpp](https://github.com/OrbitAR7/tle-sgp4-cpp): header-only C++ SGP4, matching the reference implementation to under a micrometre
- [orbit-propagator-cpp](https://github.com/OrbitAR7/orbit-propagator-cpp): two-body + J2 propagator, validated against analytic results
- [basilisk-link-budget](https://github.com/OrbitAR7/basilisk-link-budget): tests for Basilisk's ground-station and downlink modules, plus an RF link budget
- [gibbs-phenomenon-visualizer](https://github.com/OrbitAR7/gibbs-phenomenon-visualizer): spherical-harmonic ringing and leakage for regional masks

More at [orbitar7.github.io](https://orbitar7.github.io)
