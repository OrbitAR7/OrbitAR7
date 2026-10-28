### Hamoud Alshammari

Aerospace engineer working on GNSS/PNT, estimation and orbital mechanics. M.S.E. in Aerospace Engineering from UT Austin (2024), including research at the Center for Space Research on lunar geodesy and reference frames. Since 2025 at Neo Space Group on satellite communications, navigation and Earth observation.

Applying to PhD programs for Fall 2027. The research I want to do is about uncertainty in space-derived products: when an orbit, gravity field or position fix comes with a covariance, how much should we trust it, and how do we tell when the model behind it is wrong.

**GNSS & navigation**

- [gnss-integrity-raim](https://github.com/OrbitAR7/gnss-integrity-raim): snapshot RAIM with chi-square FDE and slope-based protection levels, checked by Monte Carlo (false-alarm and missed-detection rates match Pfa/Pmd)
- [gnss-pseudorange-solver](https://github.com/OrbitAR7/gnss-pseudorange-solver): header-only C++ least-squares positioning with Sagnac correction, tested against known truth
- [constellation-dop-analyzer](https://github.com/OrbitAR7/constellation-dop-analyzer): DOP of GPS, Galileo, BeiDou and Starlink geometry from real TLEs

**Estimation & dynamics**

- [EstimationToolkit.jl](https://github.com/OrbitAR7/EstimationToolkit.jl): 36 filters in Julia (sigma-point family, IMM/GPB multiple-model, particle flow, information form), 568 tests, with a LEO maneuver-detection example
- [tle-sgp4-cpp](https://github.com/OrbitAR7/tle-sgp4-cpp): header-only C++ SGP4 (near-Earth), matching the reference implementation to under a micrometre
- [orbit-propagator-cpp](https://github.com/OrbitAR7/orbit-propagator-cpp): two-body + J2 propagator, validated against analytic closure and nodal drift
- [basilisk-link-budget](https://github.com/OrbitAR7/basilisk-link-budget): tests for Basilisk's ground-station/downlink modules against an analytic model, plus an RF link budget
- [gibbs-phenomenon-visualizer](https://github.com/OrbitAR7/gibbs-phenomenon-visualizer): spherical-harmonic ringing and leakage for regional masks

Website and CV: [orbitar7.github.io](https://orbitar7.github.io)
