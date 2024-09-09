# Elevator Based Packaging System

## Introduction

Automation technology encompasses several specialties, drawing on various engineering sciences. According to the DIN 19223 standard, an automaton is an artificial system that behaves in specific ways by relating input commands to system states to achieve the necessary outputs for task completion. Modern automated processes require three key components:
- **Torque sensors**: Capture the states of the system.
- **Actuators**: Issue control commands.
- **Control units**: Execute the program and make decisions.

A Programmable Logic Controller (PLC) is used in industrial automation to control electromechanical processes, such as factory machinery on assembly lines. Unlike general-purpose computers, PLCs are designed for multiple input and output signals, extended temperature ranges, immunity to electrical noise, and resistance to vibration and shock.

An elevator is a transportation vehicle used to transport, tow, push, stack, raise, or lower various objects. Industrial freight elevators allow the transportation of heavy and bulky objects, making them ideal for use in warehouses and industrial settings.

## Objective

Automate a freight elevator using a PLC and run the simulation in Factory I/O software.

## Materials and Equipment

- **TIA Portal**
- **S7 PLC SIM**
- **SIMATIC S7-1200 PLC CPU 1211C**
- **Factory I/O**

## Development

The Factory I/O software provides default templates for some processes, including the "Elevator (advanced)" template. This template involves raising a box through three floors, loading a package on each floor, unloading the box, and directing it to another process. The cycle repeats with a new box.

### Steps

1. **Template Setup**: Utilize the "Elevator (advanced)" template in Factory I/O.
2. **Input/Output Configuration**: Edit the inputs and outputs for the Siemens S7-PLCSIM PLC in Factory I/O.
3. **PLC Programming**:
   - Use TIA Portal to create the ladder diagram.
   - Select the SIMATIC S7-1200 PLC with CPU 1211C.
   - Define necessary variables, inputs, and outputs.
4. **Simulation**:
   - Load the program into S7 PLCSIM, a PLC simulator.
   - Compile the program correctly.
   - Reset inputs and outputs before establishing the connection with Factory I/O.

### Example Ladder Diagram Networks

- **Network 3**: Configuration of specific logic for elevator operation.
- **Network 4**: Further detailing of control logic.
- **Network 5**: Additional control sequences for automation.

## Figures

- **Figure 1**: Plan of a freight elevator in FACTORY I/O.
- **Figure 2**: Inputs and outputs of the Siemens S7-PLCSIM PLC in FACTORY I/O.
- **Figure 3**: SIMATIC S7-1200 PLC in TIA Portal V12.
- **Figure 4**: Program loaded into S7 PLCSIM.

## Conclusion

The project demonstrates the automation of a freight elevator using PLC technology and Factory I/O simulation software. This setup showcases the integration of sensors, actuators, and control units to achieve automated processes in an industrial environment.