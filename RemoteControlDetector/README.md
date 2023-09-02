# Remote Control Detector

This project can be used to detect infra-red remote controls!

## What Does it Do?

Press a button on any remote control (well, infra-red based remote controls) such as a TV remote, and the light-emitting diode (LED) will flash!

## How Does it Work?

All TVs contain a little integrated circuit (IC) that senses light with an internal photodiode, and then amplifies the signal provided it is changing rapidly (at about 38 kHz). An output signal indicates the presence of the rapidly changing light. The circuit uses such an integrated circuit, part code TL1838. 

Beyond that, all that is needed in the circuit is a way to reduce or regulate the power to the chip (it needs to be less than 5V not to damage it). An LED is connected to the output of the chip, through a resistor to limit the current (LEDs don’t need a lot of power).

## Downloads

[PDF circuit diagram and pinouts](remote_control_detector_schematic.pdf)

## Circuit Diagram

<img width="100%" align="left" src="doc\schematic.png">

## Components List

    COMPONENTS LIST
    R1, R2: 10k RESISTORS
    R3: 220 ohm RESISTOR
    Q1: BC547 NPN TRANSISTOR
    C1: 10uF CAPACITOR
    U1: TL1831 INFRA-RED 38kHz SENSOR
    D1: LIGHT EMITTING DIODE (LED)

## Photos and Video

<img width="100%" align="left" src="doc\rem-con-layout-photo.jpg">

<img width="100%" align="left" src="doc\rem-con-layout-photo2.jpg">





