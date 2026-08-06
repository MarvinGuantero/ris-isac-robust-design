# Robust Joint Waveform and Passive Beamforming Design for RIS-Assisted ISAC Systems Under Imperfect Channel State Information

## Overview
![Graphical Abstract](https://github.com/MarvinGuantero/ris-isac-robust-design/blob/main/Graphical%20Abstract%20Image.png)

This repository contains the MATLAB implementation, simulation scripts, figures, and supporting materials accompanying the research paper:

> **Robust Joint Waveform and Passive Beamforming Design for RIS-Assisted ISAC Systems Under Imperfect Channel State Information**

**Authors**
- Marvin A. Guantero
- Lawrence Materum

Department of Electronics, Computer, and Electrical Engineering  
De La Salle University  
Manila 1004, Philippines

International Centre  
Tokyo City University  
Tokyo 158-8557, Japan

**Corresponding Author**
- Marvin A. Guantero
- Email: marvin_guantero@dlsu.edu.ph

---

## Abstract

Reconfigurable Intelligent Surface (RIS)-assisted Integrated Sensing and Communication (ISAC) has emerged as a promising technology for future 6G wireless networks by enabling simultaneous communication and sensing through programmable passive beamforming. However, most existing approaches assume perfect channel state information (CSI), an assumption that rarely holds in practical deployments due to inevitable channel estimation errors.

This work proposes a **robust joint waveform and passive beamforming framework** that explicitly accounts for bounded CSI uncertainty. The robust optimization problem is formulated as a worst-case minimax program and solved using a multi-scenario alternating optimization algorithm. The transmit waveform is optimized via convex quadratic programming, while the RIS phase shifts are optimized on the complex unit-modulus manifold using Riemannian optimization.

Monte Carlo simulations demonstrate that the proposed robust framework consistently outperforms conventional non-robust approaches, providing improved sum-rate performance and significantly enhanced resilience against CSI uncertainty.

---

## Key Contributions

This repository provides:

- Robust RIS-assisted ISAC optimization under imperfect CSI
- Joint waveform and passive beamforming design
- Worst-case bounded CSI uncertainty modeling
- Multi-scenario alternating optimization framework
- Riemannian manifold optimization for RIS phase shifts
- Convex quadratic programming for waveform optimization
- Reproducible MATLAB implementation for robust ISAC research

---

## Features

- RIS-assisted ISAC system model
- Imperfect CSI modeling
- Worst-case robust optimization
- Joint transmit waveform design
- Passive beamforming optimization
- Alternating optimization algorithm
- Riemannian manifold optimization
- Convex quadratic programming
- Monte Carlo simulations
- Performance comparison with non-robust methods

---

## Simulation Configuration

The proposed framework includes:

- RIS-assisted ISAC system
- Imperfect channel state information
- Bounded CSI uncertainty model
- Worst-case minimax optimization
- Multi-scenario optimization
- Alternating optimization algorithm
- Riemannian manifold optimization
- Convex quadratic programming
- Monte Carlo simulations (50 independent channel realizations)

---

## Performance Metrics

The simulation framework evaluates:

- Sum rate
- Spectral efficiency
- CSI robustness
- Algorithm convergence
- Waveform performance
- Passive beamforming gain
- Robustness against channel estimation errors

---

## Methodology

The optimization framework alternates between:

1. **Transmit Waveform Optimization**
   - Convex quadratic programming
   - Power-constrained waveform design

2. **RIS Passive Beamforming Optimization**
   - Unit-modulus phase constraints
   - Riemannian manifold optimization

The process repeats until convergence under bounded CSI uncertainty.

---

## Research Highlights

Key findings include:

- Robust optimization significantly improves system performance under CSI uncertainty.
- At a CSI error bound of **ϵ = 0.20**, the proposed method achieves **11.47 bits/s/Hz**, compared with **10.31 bits/s/Hz** for conventional non-robust approaches.
- The robust design provides an **11.3% improvement** in achievable sum rate under realistic CSI imperfections.
- Performance degradation remains substantially lower than that of non-robust methods, demonstrating improved resilience to channel estimation errors.
- Robust optimization enables practical RIS-assisted ISAC deployment with reduced CSI accuracy requirements.

---

## Research Applications

This repository can be used for research in:

- Reconfigurable Intelligent Surfaces (RIS)
- Integrated Sensing and Communication (ISAC)
- Robust Wireless Communications
- 6G Networks
- Passive Beamforming
- Waveform Design
- Robust Optimization
- Convex Optimization
- Riemannian Optimization
- Channel Estimation
- Signal Processing

---

## Citation

If you use this repository in your research, please cite:

```bibtex
@article{Guantero2026,
  author  = {Marvin A. Guantero and Lawrence Materum},
  title   = {Robust Joint Waveform and Passive Beamforming Design for RIS-Assisted ISAC Systems Under Imperfect Channel State Information},
  journal = {Under Review},
  year    = {2026}
}
```

Please update the citation once the manuscript has been accepted for publication.

---

## Requirements

- MATLAB R2022a or later (recommended)
- Optimization Toolbox
- CVX (for convex optimization, if applicable)
- Manopt Toolbox (for Riemannian manifold optimization)
- Parallel Computing Toolbox (optional)

---

## License

This repository is intended for academic and research purposes.

If you use the source code or reproduce any figures, please cite the associated publication.

---

## Contact

**Marvin A. Guantero**

Department of Electronics, Computer, and Electrical Engineering  
De La Salle University

Email: marvin_guantero@dlsu.edu.ph

---

## Keywords

Reconfigurable Intelligent Surface, RIS, Integrated Sensing and Communication, ISAC, Robust Optimization, Imperfect CSI, Passive Beamforming, Waveform Design, Riemannian Manifold Optimization, Convex Optimization, 6G Wireless Communications, MATLAB.
