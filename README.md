# WindBorne Embedded Electrical Engineer — Submission

## Resume
[Isaac_Tourner_WindBorne_Resume.pdf](resume/Isaac_Tourner_WindBorne_Resume.pdf)

## PCB Example
**Elegant feature:** I intentionally partitioned the design into modular blocks (power, DIO/level shifting, motor/encoder, and analog acquisition) with clear connectors and bring-up hooks (test points + jumpers). That made it easy to populate only what was needed for a given build and iterate quickly without changing the core PCB.

### Schematic
[schematic hierarchy](pcb/schematic/)
- [Root](pcb/schematic/Root.png)
  - [RPi](pcb/schematic/RPi.png)
  - [Power](pcb/schematic/Power.png)
  - [DIO](pcb/schematic/DIO.png)
  - [Motor](pcb/schematic/Motor.png)
  - [Analog](pcb/schematic/Analog.png)
  - [Connectors](pcb/schematic/Connectors.png)

### Layout
![layout](pcb/layout/layout.png)

### Board Photos
<div style="display:flex; gap:16px; align-items:flex-start; flex-wrap:wrap;">
  <img src="pcb/pcb_photos/pcb1.jpeg" style="width:48%; min-width:280px;" />
  <img src="pcb/pcb_photos/pcb1.1.jpeg" style="width:48%; min-width:280px;" />
</div>
