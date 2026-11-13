# Team Trinity Karterz — Go-Kart (HKFC Season 5)

Design, analysis and fabrication work on our team's racing go-kart for **HKFC Season 5**.

## 🏆 Results
- **1st place — Cross Pad**
- **1st Runner-up — Acceleration**

## My role
| Area | What I did |
|---|---|
| Pedal design | Designed the **brake pedal** and **throttle pedal** in CAD |
| FEA | Ran **static structural analysis in Ansys** on both pedals and the stub axle |
| Fabrication | **Welding and grinding** on the chassis |
| Powertrain | Replaced the spark plugs and the carburettor |

## Pedal FEA (Ansys Static Structural)

| Part | Applied load | Max. equivalent stress | Max. deformation | Factor of safety |
|---|---|---|---|---|
| Brake pedal | 650 N | _TBD_ MPa | _TBD_ mm | _TBD_ |
| Throttle pedal | 150 N | _TBD_ MPa | _TBD_ mm | _TBD_ |

- **Material:** mild structural steel (commercial grade; exact grade not certified)
- **Software:** Ansys Workbench (originally R18.2; being re-run in Ansys 2026 R1)
- **Boundary conditions:** pivot fixed, load applied normal to the pedal pad

![Brake pedal stress plot](images/brake_pedal_stress.png)
![Throttle pedal stress plot](images/throttle_pedal_stress.png)

## Stub axle FEA
_Load case, results and plots to be added._

## Repository structure
```
cad/        CAD models of pedals and stub axle
ansys/      Ansys project files / exported results
images/     Stress & deformation plots, kart and team photos
docs/       HKFC Season 5 certificate, design report
```

## Team
Team Trinity Karterz, Punjabi University, Patiala.

---
**Divyam Singla**: B.Tech Mechanical Engineering, Punjabi University Patiala
[Portfolio](https://divyamsingla09.github.io) · [LinkedIn](https://linkedin.com/in/divyamsingla09)
