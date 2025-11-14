# Deep Dive: Experiment M  
**COMP3421 / COMP9415 – Computer Graphics 2024 T3**  

> A 3D narrative-driven escape-room puzzle adventure built with Unreal Engine 5.  
> Featuring five unique puzzle levels, environmental storytelling, and a climactic boss encounter.

---

## Overview
**Deep Dive: Experiment M** is a single-player 3D escape-room adventure set inside an abandoned underground biological research institute.  
Players explore five floors filled with puzzles, hidden clues, environmental storytelling, and dangerous mutated subjects.  
Your mission: uncover what happened, assemble the Lure, defeat the final creature, and escape before demolition occurs.

The game blends:

- Escape-room puzzle design  
- Narrative exploration  
- Atmospheric horror  
- Chemical & scientific interactions  
- Character–Drone dual control  
- Light combat + environmental trap systems  

---

## Core Features

### Multi-Mechanic Puzzle Experience
Every floor introduces a new mechanic:
- **Level 1:** Laser & mirror reflection  
- **Level 2:** Symbolic language decoding, blacklight clues, pipe & chemical puzzles  
- **Level 3:** Shadow matching, colour memory tests, path memorisation  
- **Level 4:** Body-switch maze (Human ↔ Drone) with box pushing & hazards  
- **Level 5:** Enemy combat + binary-search scanner + trap assembly  

### Immersive Horror Environment
- Third-person perspective for cinematic storytelling  
- Gradual lighting shift from **cold blue → sickly green** as danger increases  
- Abandoned facility aesthetics: damaged equipment, scattered papers, broken furniture  
- Hidden narrative clues across all levels  

### Narrative-Driven Progression
Find out:
- What the researchers were experimenting on  
- Why the test subjects mutated  
- How the facility collapsed  
- Why your contractor *really* sent you  

Collect **4 Lure Components** (one per level), then assemble them in Level 5.

### Escape-Room × Boss Encounter Hybrid
A rare combination in the genre:
- Freeze Ray & Shotgun  
- Environmental trap building  
- Strategy-heavy lure system  
- Timed escape sequence  

---

## Level Overview

### 1️⃣ Level 1 – Lasers & Mirrors
Use adjustable mirrors to redirect lasers, break debris, unlock mechanisms, and access the next floor.

### 2️⃣ Level 2 – Code Deciphering
Decode a custom symbol language, reveal hidden blacklight messages, repair pipes, mix chemicals, and discover early hints of the creatures.

### 3️⃣ Level 3 – Shadows & Colours
Arrange objects to cast specific silhouettes, recall increasing colour sequences, and navigate a trap-filled memory path.

### 4️⃣ Level 4 – Body-Switch Maze
A 2.5D maze with:
- Human ↔ Drone switching  
- Box pushing  
- Laser fences  
- Fans, shock floors, dark rooms  
- Multi-floor exploration  

### 5️⃣ Level 5 – Enemy Floor & Final Boss
- Binary-search scanning puzzle  
- Chemical thawing using Bunsen burner  
- Assemble laser trap  
- Freeze ray + shotgun  
- Lure monster into cage  
- Extinguish fire at the exit  
- Escape before the building detonates  

---

## Interaction System

| Category      | Examples                                                                 |
|--------------|--------------------------------------------------------------------------|
| Universal | Movement, camera, interacting, picking items, inventory                  |
| Puzzle    | Mirrors, blacklight, valves, chemical mixing, shadows, buttons          |
| Drone     | Flying, lighting dark areas, pressing remote triggers                    |
| Environment | Breaking debris, pushing boxes, activating triggers                    |
| Combat    | Freeze Ray, Shotgun, Lure throwing, trap activation                      |

---

## Visual & Art Direction
- Realistic UE5 lighting  
- Gradual colour shifts for tension building  
- Heavy environmental storytelling  
- Use of Unreal Marketplace & Megascans assets  
- Stylised but horror-enhanced creature models  
- Two playable character models + drone companion  

---

## Technical Highlights
- Third-person perspective (rare for escape-room genre)  
- Puzzle-solving integrated into combat design  
- Modular level structure with persistent items  
- Dynamic environment: physics, lighting, destructible elements  
- Custom UI: Inventory, Intel Viewer, Builder  
- 3D + 2.5D mixed design for clarity and style  

---

## Full Proposal
The complete detailed proposal is available in:

👉 `docs/Computer Graphics_A1_Proposal.release.pdf`  

This includes:
- Full narrative  
- All puzzle breakdowns  
- Level flowcharts  
- UI mockups  
- Environment maps  
- Reference list  

---

## Technologies Used
- Unreal Engine 5  
- Blueprint Visual Scripting  
- C++ Gameplay Extensions  
- Quixel Megascans  
- UE Marketplace Assets  
- Physics-based interactions  
- Custom UI Systems  

---

## Future Improvements
- Cutscenes & voice-over logs  
- Advanced combat polish  
- Complete sound design  
- Optimised lighting pass  
- Steam-ready packaging  

---

## License
MIT License

Copyright (c) 2025 Ethan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


