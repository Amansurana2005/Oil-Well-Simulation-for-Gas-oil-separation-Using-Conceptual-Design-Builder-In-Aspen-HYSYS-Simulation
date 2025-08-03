# Oil-Well-Simulation-for-Gas-oil-separation-Using-Conceptual-Design-Builder-In-Aspen-HYSYS-Simulation

Project Title: Crude Oil Characterization and Fractionation Process Simulation

Challenge: The objective was to simulate a complete crude oil processing plant, from initial characterization to final product separation, using Aspen Hysys. The key challenge was accurately modeling crude oil as a multi-component mixture, designing an efficient pre-treatment and distillation train, and implementing a complex side-stream and heat integration system to produce specific products with defined flow rates.

Methodology:

Crude Oil Characterization: The project began with the characterization of a crude oil stream using lab data. The crude oil was defined with a bulk density of 879.8 kg/m 
3
  and a given composition of light ends (e.g., methane 0.0065% liquid volume). An assay (SA) with 12 data points was used to generate hypothetical components, allowing Hysys to calculate true boiling point and molecular weight curves for the mixture.

Pre-treatment Design: A pre-treatment section was designed to prepare the crude oil for distillation. This included:

Mixing the crude oil (600,000 kg/hr) with a water stream (21,600 kg/hr) at 15 
∘
 C and 1000 kPa.

A heater (ΔP=50 kPa, outlet 65 
∘
 C) to preheat the mixture.

A shell-and-tube heat exchanger with a 30 
∘
 C minimum approach to raise the temperature to 100 
∘
 C.

A three-phase separator (desalter) to remove water and light gases.

A furnace to raise the crude temperature to a final value of 400 
∘
 C before entering the column.

Atmospheric Distillation Column with Side Strippers: A 29-stage reflux absorber was the core of the separation process. The column was operated with a condenser pressure of 140 kPa and a bottom pressure of 230 kPa.

Automotive Gas Oil (AGO): A side stripper, steam-stripped, drew AGO at stage 22 and returned fluid at stage 21, producing 30.69 m 
3
 /hr of product.

Diesel: A second steam-stripped side stripper drew from stage 17 and returned to stage 16, yielding 128.88 m 
3
 /hr of diesel.

Kerosene: A reboiled side stripper drew from stage 9 and returned to stage 8, producing 64.10 m 
3
 /hr of kerosene.

Results and Impact:

Accurate Process Modeling: The simulation successfully characterized a complex crude oil mixture and converged a detailed flowsheet, demonstrating the ability to handle multi-component systems and rigorous thermodynamic calculations.

Efficient Product Separation: The designed column and side stripper system achieved the specified separation goals, yielding distinct, high-value products with controlled flow rates.

Demonstrated Heat Integration Expertise: The inclusion of a pump-around loop with a duty of −3.7×10 
7
  kJ/hr showcased an understanding of heat recovery and energy optimization in an industrial setting.

Proficiency in Advanced Simulation Tools: The project highlights hands-on experience with advanced Hysys features, including oil manager for crude characterization, side strippers, and pump-around specifications, all of which are critical for real-world process design.
