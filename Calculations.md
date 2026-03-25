1. Electrophoresis

    - v_ep = μE
        - v_ep = electrophoretic drift velocity, m/s
        - μ = electrophoretic mobility, m^2/(V⋅s)
        - E = electric field, V/m

    - v_gal = μ_gal ⋅ E
        - ignore EOF for now

2. Electro-osmosis (Helmholtz-Smoluchowski)

    - v_EOF = - ε𝜁E / η
        - ε: fluid permittivity, 𝐹/𝑚
        - ζ: zeta potential, V
        - 𝜂: viscosity, Pa·s
        - E: electric field, V/m
    
    - in water:
        - 𝜀 ≈ 80 * 𝜀_0 ≈ 7.08 × 10e-10 𝐹/𝑚
        - 𝜂 ≈ 10e-3 𝑃𝑎⋅𝑠

3. Brownian diffusion

    - Δx_diff ~ sqrt(2Ddt)𝜂
        - D: diffusion coefficient, m^2/s
        - 𝜂: random value (mean = 0, sd = 1)

    - Membrane protein lateral diffusion
        - D_gal ~ 10e-14 to 10e-13 m^2/s