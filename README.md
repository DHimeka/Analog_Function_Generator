# Analog Function Generator

## Introduction
This is the project done during the third semester for the module EN2091 - Laboratory Practice and Projects.
During the course of this project, Our team had the privilege of designing and developing a fully functional function generator that seamlessly incorporates essential features commonly found in laboratory-grade devices. With a clear focus on versatility and performance, we harnessed the potential of basic electronic components, including opamps, transistors, resistors, capacitors, and potentiometers, to achieve waveform generation and control with optimum precision.
Through an extensive research and a meticulous design, we successfully utilized analog electronic calculations to generate sine, square, triangular, sawtooth, and PWM waveforms. We ensured accurate frequency control across the impressive range of 20Hz to 20kHz, empowering users to tailor the function generator to their specific experimental requirements.
A key aspect of the project was the robust control over amplitude and DC offset. Employing feedback mechanisms and precise opamp configurations, we allowed users to manipulate the output voltage from a 0V to 20V and introduce desired DC offsets for waveform customization. 
Throughout the endeavor, we encountered and various challenges, from refining the circuits iteratively to optimize performance, building up enclosures, making pcbs to presenting a marketable prooduct. Yet the outcome was worthful and impressive. The result is a fully functional and adaptable function generator, seamlessly blending the artistry of creative circuit design with the precision of engineering finesse.

## Electronic Design

### Design Guidelines

The project adhered to specific design requirements, including waveform generation, frequency, amplitude, PWM control, and 50 Ω load compatibility. These guidelines influenced the electronic design decisions.

### Waveform Generation

1. **Square Wave and PWM Wave Generation:** A Schmitt trigger circuit generates square waves, which can be further modified to achieve PWM waves with adjustable duty cycles.

2. **Triangular Wave and Sawtooth Generation:** Triangular and sawtooth waveforms are generated through a capacitor-based charging and discharging process, with frequency control.

3. **Sine Wave Generation:** A Wien bridge oscillator generates sine waves, which can be adjusted for frequency.

### Output Circuit

The output circuit handles waveform selection, probe selection (1x and 10x), amplitude control, and push-pull amplification to drive a 50 Ω load.

## Calculations and Component Selection

Careful component selection and calculations were crucial for ensuring proper functionality. The NE5532n operational amplifier was chosen for its low noise and appropriate gain-bandwidth product. Transistors TIP31C and TIP32C were selected to handle the required power and current.

## Simulations

NI Multisim was used for circuit simulations to validate the design before proceeding to PCB fabrication. Simulations confirmed that the circuit met the desired specifications.

## Testing

After simulation, the circuit was implemented on a breadboard and tested. Issues related to waveform interference and instability were addressed through careful circuit adjustment and troubleshooting.

## PCB Designing and Soldering

The PCB was designed using Altium and printed through JLCPCB in a two-layer configuration. Soldering was done with locally sourced components to create a physical circuit.

## Results

The project successfully achieved the following results:

- Generation of square, triangular, sawtooth, and sine waves within the specified frequency and amplitude ranges.
- PWM wave generation with adjustable duty cycles.
- Compatibility with a 50 Ω load.

## Enclosure Design

The enclosure for the function generator was designed using Solidworks 2020, ensuring a suitable physical housing for the device.

## Discussions

The project team encountered challenges with waveform distortions at high frequencies. Strategies to mitigate these distortions, including the use of high-quality components and minimizing wire resistance, were discussed.

[Link to full project report (PDF)](link_to_full_project_report.pdf)








