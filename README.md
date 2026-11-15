# EXPERIMENT NO: 5

# ZENER DIODE AS A VOLTAGE REGULATOR

## AIM
To study the operation of a Zener diode as a voltage regulator and observe its line regulation and load regulation characteristics using Proteus simulation.

## COMPONENTS REQUIRED

- Zener Diode – 1N4740A
- Resistor R1 – 100 Ω
- Load Resistor R2 – 2 kΩ
- Variable Resistor (RV1)
- DC Voltage Source
- Ammeter
- Voltmeter
- Ground
- Connecting Wires

## THEORY

A Zener diode is a semiconductor diode designed to operate in the reverse breakdown region.

When connected in reverse bias, the Zener diode maintains an approximately constant voltage across its terminals, even when the input voltage or load current changes within its operating limits.

It is commonly used as a voltage regulator to maintain a stable output voltage.

### 1. LINE REGULATION

Line regulation is the ability of a voltage regulator to maintain a constant output voltage when the input voltage changes.

In this experiment:
- The load resistance is kept constant.
- The input voltage is varied.
- The output voltage is observed.

### 2. LOAD REGULATION

Load regulation is the ability of a voltage regulator to maintain a constant output voltage when the load resistance changes.

In this experiment:
- The input voltage is kept constant.
- The load resistance is varied.
- The output voltage is observed.

## PROCEDURE

### LINE REGULATION

1. Open Proteus and create the line regulation circuit.
2. Connect the Zener diode in reverse bias.
3. Connect the series resistor and load resistor.
4. Set the load resistance to 2 kΩ.
5. Apply an input voltage within the verified operating limits of the components.
6. Vary the input voltage in suitable steps.
7. Observe and record the output voltage.
8. Plot the graph between input voltage and output voltage.

### LOAD REGULATION

1. Create the load regulation circuit in Proteus.
2. Connect the Zener diode in reverse bias.
3. Keep the input voltage constant.
4. Vary the load resistance using the variable resistor.
5. Observe and record the output voltage.
6. Plot the graph between load resistance and output voltage.

## CIRCUIT DIAGRAMS

### LINE REGULATION CIRCUIT

<img width="1920" height="1080" alt="Line_Reg_Circuit" src="https://github.com/user-attachments/assets/796982c5-e5a6-4811-9f2e-035529e45194" />

### LOAD REGULATION CIRCUIT

<img width="1920" height="1080" alt="Load_Reg_Circuit" src="https://github.com/user-attachments/assets/2ef0dd13-be46-4b79-8c49-ddf9946afeab" />

## SIMULATION USING PROTEUS

### LINE REGULATION SIMULATION

<img width="1920" height="1080" alt="Line_Reg_1" src="https://github.com/user-attachments/assets/c0907bcd-2f6b-4cc1-80a4-58eb4d373b8d" />

<img width="1920" height="1080" alt="Line_Reg_2" src="https://github.com/user-attachments/assets/b425239c-1627-482f-8ca1-f462dfb68d7a" />

### LOAD REGULATION SIMULATION

<img width="1920" height="1080" alt="Load_Reg_1" src="https://github.com/user-attachments/assets/ab516a03-9310-4ed1-90bf-776eaa9331d1" />

<img width="1920" height="1080" alt="Load_Reg_2" src="https://github.com/user-attachments/assets/3bdeb0c7-58cc-4041-9255-0c18b9f22d6f" />

## OBSERVATION TABLES

### 1. LINE REGULATION

| S.No | Input Voltage (V) | Output Voltage (V) |
|---|---:|---:|
| 1 | 30 | 10.10 |
| 2 | 40 | 10.12 |
| 3 | 50 | 10.14 |
| 4 | 60 | 10.16 |
| 5 | 70 | 10.18 |
| 6 | 80 | 10.20 |
| 7 | 90 | 10.22 |
| 8 | 100 | 10.24 |
| 9 | 110 | 10.26 |
| 10 | 120 | 10.28 |

### 2. LOAD REGULATION

| S.No | Load Resistance (Ω) | Output Voltage (V) |
|---|---:|---:|
| 1 | 100 | 9.80 |
| 2 | 200 | 9.85 |
| 3 | 300 | 9.89 |
| 4 | 400 | 9.92 |
| 5 | 500 | 9.95 |
| 6 | 600 | 9.98 |
| 7 | 700 | 10.00 |
| 8 | 800 | 10.03 |
| 9 | 900 | 10.05 |
| 10 | 1000 | 10.08 |

## GRAPHS

### LINE REGULATION GRAPH

<img width="1600" height="1000" alt="line_regulation_graph" src="https://github.com/user-attachments/assets/17dc8555-b812-4d98-ab91-bcde273c26d6" />

### LOAD REGULATION GRAPH

<img width="1600" height="1000" alt="load_regulation_graph" src="https://github.com/user-attachments/assets/9d741239-4ea9-4bea-8c89-a9884d2f8995" />

## FORMULAE

### LINE REGULATION

Line Regulation = Change in Output Voltage / Change in Input Voltage

### LOAD REGULATION

Percentage Load Regulation =

((No-load Voltage - Full-load Voltage) / Full-load Voltage) × 100

## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
