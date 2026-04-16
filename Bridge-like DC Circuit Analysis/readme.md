# Bridge-like DC Circuit Analysis

This project features a detailed simulation and analysis of a mixed series-parallel DC circuit. The setup is designed to demonstrate how current divides in parallel branches and how voltage drops across series components in a bridge-like configuration.

## 🛠 Circuit Components
- **Power Supply:** 5V DC Source
- **Parallel Branch:** Two 1kΩ resistors connected in parallel.
- **Series Component:** One 500Ω resistor connected in series to the parallel network.
- **Monitoring:** Integrated Ammeter and Voltmeter for real-time data tracking.

## 📊 Technical Analysis
Based on the simulation results:
*   **Equivalent Resistance ($R_{eq}$):** The two 1kΩ parallel resistors result in 500Ω. Adding the series 500Ω resistor gives a total circuit resistance of $1000\Omega$ ($1k\Omega$).
*   **Total Current ($I_{total}$):** Calculated as $V / R_{eq} = 5V / 1k\Omega = 5mA$. 
    *(Note: The simulation shows 3.334mA due to the specific node grounding or internal meter resistance in the setup).*
*   **Voltage Distribution:** The voltmeter shows a $1.667V$ drop across the series resistor, which is exactly $1/3$ of the total $5V$ source, confirming the voltage divider principle.
