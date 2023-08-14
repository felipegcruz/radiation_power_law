# Radiation Power Laws Calculator

This Python program calculates and visualizes the radiation power laws based on user-input temperature using the Stefan-Boltzmann law and Wien's displacement law. It generates graphs displaying the total radiation power and the wavelength of maximum emission as functions of temperature.

## Prerequisites

To run this program, you'll need:

- Python 3.x installed on your machine.
- Matplotlib library for graph plotting. Install it using the following command:

```bash
pip install matplotlib
```

## Usage

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the program by executing the following command:

   ```bash
   python radiation_powerlaws_calculator.py
   ```

4. Enter the temperature in Kelvin when prompted. It must be between 1 and 5 Kelvin.

5. The program will calculate and display the total radiation power and the wavelength of maximum emission based on the provided temperature.

6. The program will also generate a graph displaying the relationship between temperature and both total radiation power and wavelength of maximum emission.

## Radiation Laws

The program uses the following radiation laws for calculations:

- **Stefan-Boltzmann Law:** Calculates the total radiation power as a function of temperature.
- **Wien's Displacement Law:** Calculates the wavelength of maximum emission as a function of temperature.

## Graphs

The program generates a graph with two subplots:

1. **Total Radiation Power:** Displays the relationship between temperature and total radiation power (W/m^2).
2. **Wavelength of Maximum Emission:** Displays the relationship between temperature and wavelength of maximum emission (meters).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
