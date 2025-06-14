# Stellar Structure: Lane-Emden Equation and the Chandrasekhar Limit

This repository documents an ongoing project exploring the structure of white dwarfs using classical and statistical physics tools.

---

## Part I — Lane-Emden Equation

This section presents the derivation and solution of the Lane-Emden equation, a dimensionless form of the hydrostatic equilibrium equation for polytropic stars. 
The analysis includes:

- Derivation of the Lane-Emden equation from first principles
- Analytical solutions for polytropic indices \( n = 0 \) and \( n = 1 \)
- Numerical solutions using the Runge-Kutta 4th order (RK4) method for \( n = 1.5, 3, 5 \)
- Mass-density profiles and physical interpretation of the polytropic index

### 🔧 Files
- `main.tex` — Full LaTeX article with equations and plots
- `lane_emden_solver.py` — General RK4 integrator for all \( n \)
- `figures/` — All numerical plots and physical profiles

---

## Part II — Chandrasekhar Limit (Coming Soon)

In the next phase, I will derive the **Chandrasekhar mass limit** for white dwarfs using:

- Fermi-Dirac statistics at \( T = 0 \)
- Polytropic models for degenerate electron gases
- Numerical comparisons with the \( n = 3 \) Lane-Emden profile
- (Optional) Energy minimization and stability conditions following Landau's approach

The goal is to bridge classical stellar structure with quantum statistical mechanics and understand the mass limit beyond which white dwarfs become unstable to collapse.

---

## Author

**Arnav Wadalkar**  
B.Sc. Physics student at NIT Rourkela  

--- 
This project is open for academic and educational use. All figures are original unless stated otherwise.
