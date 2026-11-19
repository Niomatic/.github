<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.jpg">
  <img alt="Niomatic — Robots, designed by AI. Robot Studio, release soon." src="assets/banner-light.jpg">
</picture>

<br>

## Robot Studio

> **Release soon.** Robot Studio is in private development. This page will link to it as soon as it opens.

Robot Studio is a desktop studio in which a robot is **one project**: its 3D assembly and joints, its
schematics and circuit boards, its firmware, and everything it takes to make it. **AI agents do the
design work** through the studio's built-in MCP server — you watch it happen live, look inside every
part, change anything and take over at any time.

<table>
  <tr>
    <td width="50%"><img src="assets/part-details.jpg" alt="A made part's details: how it is made, its route and its files"><br><sub><b>Mechanics</b> — every part says how it is made, and is made from the panel.</sub></td>
    <td width="50%"><img src="assets/motion.jpg" alt="The Motion place: a walking gait on lanes, with the path of every foot traced"><br><sub><b>Motion</b> — the actions of the firmware on lanes, played on the robot.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/system-overview.jpg" alt="System overview of boards, batteries, actuators and modules"><br><sub><b>System</b> — boards and devices with the connections between them.</sub></td>
    <td width="50%"><img src="assets/schematic.jpg" alt="A schematic page with module pictures"><br><sub><b>Schematic</b> — several boards, each with its pages.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/pcb-3d.jpg" alt="The robot's carrier board in 3D"><br><sub><b>PCB</b> — routed and checked by KiCad's own engines.</sub></td>
    <td width="50%"><img src="assets/code.jpg" alt="The Code place with the gait firmware"><br><sub><b>Code</b> — a full IDE for the robot's firmware.</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="assets/build-make.jpg" alt="The Build place: every part to make with its route and files"><br><sub><b>Build</b> — what to buy, what to make and in which order.</sub></td>
    <td width="50%"><img src="assets/gcode-simulation.jpg" alt="A part sliced by PrusaSlicer and its G-code simulated"><br><sub><b>Make</b> — sliced for your printer and simulated before it is sent.</sub></td>
  </tr>
</table>

### What it does

|  |  |
| --- | --- |
| **Mechanics** | Real B-rep solids, sub-assemblies, joints that move only as they really can, interference and joint-travel checks, wires laid by physics, motions run in a physics engine. |
| **Electronics** | Several boards per robot, professional schematics, PCB layout with Push & Shove routing, copper pours and 1–10 copper layers, design-rule checks and fabrication files. |
| **Code** | A JetBrains-style IDE for the robot's firmware: build and upload to the board, run and deploy Python, the robot's pins inside the code. |
| **Making it** | Drawings with materials and ISO tolerances, parts sliced for your 3D printer and simulated before printing, board files for the fab house, what to buy, the assembly steps. |
| **AI agents** | Close to three hundred MCP tools: whatever a person can do in the window, an agent can do too — and it is told at once what its change broke. |

### Built on open source

Robot Studio integrates established open-source engines rather than reinventing them:
Open CASCADE · KiCad · Freerouting · MuJoCo · Monaco · clangd · PrusaSlicer · three.js · the Model Context Protocol.
