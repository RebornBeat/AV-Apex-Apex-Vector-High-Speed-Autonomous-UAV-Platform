Here is the complete, exhaustive compilation of all files and the master prompt for your GitHub repository. I have assembled everything into a single, cohesive package without omission. You can copy and paste each section directly into your new GitHub repository to establish your public timestamp, prior art, and civilian research framework.

---

### FILE 1: `README.md`
*(Place this in the root of your GitHub repository)*

```markdown
# AV-Apex (Apex-Vector) High-Speed Autonomous UAV Platform

**Author & Concept Originator:** Christian Liz-Fonts
**Date:** [Current Date]
**License:** MIT (See `LICENSE` file. Concept rights retained by author.)
**Status:** Conceptual Design & Three.js Simulation Demonstrator (Civilian Dual-Use Focus)

## 1. Project Overview
AV-Apex is a conceptual, high-speed, autonomous unmanned aerial vehicle (UAV) designed for civilian applications such as Search and Rescue (SAR), wildfire monitoring, atmospheric sampling, and long-range emergency response. 

This repository contains the theoretical framework, aerodynamic analysis, and a Three.js-based 3D simulation demonstrating the unique flight dynamics of the platform.

## 2. The Core Insight: Correcting the B-2 / Flying Wing Flaw
Current flying wing designs (like the B-2 Spirit) attempt to mimic natural aerodynamics (e.g., an eagle) but fail to translate the mechanical requirements of thrust into the design. Specifically, they embed engines in a way that prevents **thrust stacking**—a concept where the thrust of multiple engines compounds linearly to provide maximum axial power and stability, similar to booster rockets in spaceflight. 

Furthermore, legacy designs lack the mechanical geometry to perform rapid inversions (flying upside down) at high speeds without tearing themselves apart. The AV-Apex solves this by introducing an "Apex Line" and a central stabilizing "Fin" combined with AI-driven extreme thrust vectoring.

## 3. Key Innovations
* **The Apex Line & Central Fin:** The nose of the aircraft is extended into a central fin. This fin does not move; its sole purpose is to route engines internally through fuel tanks and keep the aircraft flying straight at maximum velocity.
* **Internal Fuel Exclusivity:** The internal volume is dedicated *entirely* to fuel. There is no internal payload bay or pilot bay. Payloads (sensors, SAR gear) are mounted externally, reducing internal complexity.
* **Thrust Stacking Configuration:** Engines are arranged along the apex line to allow thrust to stack, providing unparalleled forward momentum.
* **AI-Driven 180-Degree Inversion Maneuver:** Because this is a pilotless drone, it can withstand G-forces that humans cannot. Engines 1-6 feature up to 90-degree vertical thrust vectoring (and 15-35 degrees lateral). By thrusting against the fin's forward vector, an AI can smoothly tilt the aircraft 180 degrees (upside down) at maximum speed over a long range, allowing it to reverse heading and return home in one continuous sweep.
* **Modular Configurations:** Supports 2-engine, 4-engine, and 6-engine variants using the same fin architecture.

## 4. Prior Art Analysis (Why this is new)
* **B-2 Spirit:** Fails due to embedded engines that do not allow thrust stacking. Lacks a central stabilizing fin, requiring constant computer drag-braking to fly straight.
* **X-36 / X-37:** Tailless designs that rely on split ailerons for yaw, losing immense amounts of energy during maneuvers. They lack the thrust-vectoring geometry required to flip a high-speed airframe 180 degrees without catastrophic loss of control.

## 5. Dual-Use Warning (Ethical & Legal Disclaimer)
**This project is strictly civilian and open-source under the MIT license.** 
The primary focus is Search and Rescue, environmental monitoring, and aerospace engineering research. However, as an exercise in ethical engineering transparency, it must be noted that the high-speed, long-range (6,000+ km), and highly maneuverable nature of this airframe possesses theoretical dual-use potential. In a military context, a reusable, externally-payload-carrying variant could theoretically function as a high-speed strike vehicle that returns to sender (unlike kamikaze drones). **This repository does not provide any military hardware, software, or instructions.** The simulation is purely aerodynamic and civilian-focused.

## 6. Repository Structure
* `/docs` - Theoretical engineering documents, fuel analysis, and prior art.
* `/sim` - Three.js real-time 3D aerodynamic simulation.

## 7. Citation & Author Credit
Any use, modification, or fork of this concept must credit the original author and concept originator: **Christian Liz-Fonts**.
```

---

### FILE 2: `LICENSE`
*(Place this in the root of your GitHub repository)*

```text
MIT License

Copyright (c) [Year] Christian Liz-Fonts

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

Conceptual design, aerodynamic theories, and engineering layouts specific to 
the AV-Apex (Apex-Vector) platform are the intellectual property of the author.
```

---

### FILE 3: `docs/CONCEPT_AND_ENGINEERING.md`
*(Place this in the docs folder)*

```markdown
# AV-Apex Engineering Concept

## 1. Design Philosophy
The AV-Apex is designed around the concept of "Maximum Speed, Maximum Endurance." Unlike traditional UAVs that throttle down to conserve energy, the AV-Apex is aerodynamically optimized to fly at its maximum speed almost continuously, utilizing thrust stacking to maintain stability.

## 2. Airframe Geometry
The aircraft utilizes a blended delta-wing body inspired by natural eagle flight dynamics, correcting the translation errors found in legacy platforms like the B-2.

### ASCII Representation

          F1
        /    \   
       /      \	
  F2  /        \      F3
  / \/          \    / \
F4  /   \  /     \  /   \     F5 
F6 / \  /  \/     \/     \    / \      F7 
 /	\  /     \/	           \/     \  /   \
/	 \/ 			               \/     \
/   				                       \
/     					                        \
/	 				                        \
 				 Fin 	                        \
  		       1     	/----\	     2                          \
   	       3     /----\    /      \    /----\    4	                 \
      ___________5     /----\ /      \  /        \  /      \ /----\     6___________\
                  /----\ /               \/          \/               \ /----\
	     /                      	                                 \
	    /      	           	                                  \ 
	   /      	            					   \			 
	  /       					                    \
	 /____________________________________________________________________\

* **The Apex Line:** A structural ridge running from the nose to the tail, culminating in a static central fin.
* **Internal Layout:** 100% of the internal fuselage volume is allocated to fuel storage. 
* **External Payload:** Hardpoints are located under the blended wing. For civilian use, these carry SAR camera pods, life-raft dispensers, or atmospheric sampling sensors.

## 3. Propulsion & Thrust Vectoring
The platform is designed to be modular, supporting 2, 4, or 6 engine configurations.
* **Thrust Stacking:** Engines are aligned along the apex line so their exhaust outputs compound, creating a single, massive axial thrust vector.
* **Vectoring Mechanics:** 
  * Vertical: 0 to 90 degrees (up/down) per engine.
  * Lateral: 0 to 15-35 degrees (left/right) per engine.
* **The Central Fin:** The fin acts as the anchor. It provides forward thrust routing. To turn, the AI does not use ailerons; it vectors the engines against the fin's thrust vector.

## 4. The 180-Degree Inversion Maneuver
Traditional aircraft turn by banking (losing speed) or flipping (requiring immense altitude). 
The AV-Apex executes a "Long-Range Inversion":
1. The aircraft flies at maximum speed (e.g., 800 km/h).
2. To reverse direction, the AI commands engines 1-6 to vector 90 degrees vertically (against the direction of the fin's thrust).
3. Because the aircraft is pilotless, it can endure the structural load.
4. The aircraft smoothly tilts 180 degrees until it is upside down.
5. Once inverted, the engines realign to the forward axis, and the aircraft continues at maximum speed in the opposite direction.
6. This maneuver requires a long physical distance to complete smoothly at high speed, making it an "energy-preserving wide inversion" rather than a sharp combat turn.
```

---

### FILE 4: `docs/FUEL_AND_RANGE_ANALYSIS.md`
*(Place this in the docs folder)*

```markdown
# Fuel Analysis and Range Calculation

## 1. Fuel Requirements
To achieve a 6,000+ km round trip without refueling, the aircraft requires an extremely high fuel fraction and a highly efficient propulsion system. The internal volume is entirely fuel, enabling this massive range.

## 2. Fuel Type Analysis
* **Aviation Gasoline (Avgas):** Can be used, but heavy relative to energy density. 
* **Jet A / Kerosene:** Standard for turbine engines. Excellent energy density (approx. 43.1 MJ/kg). This is the most realistic, lightest, and cheapest practical fuel for a high-speed jet UAV of this class.
* **Liquid Hydrogen (LH2):** The lightest and most efficient fuel by mass (142 MJ/kg), but requires massive, heavily insulated cryogenic tanks. Not feasible for a simple, low-cost UAV.
* **Conclusion:** The simulation defaults to **Jet A (Kerosene)** as it represents the best balance of low cost, availability, and energy density for a 6,000+ km range.

## 3. Realistic Dimensions & Capacity (Simulated Specs)
* **Length:** 12 meters
* **Wingspan:** 15 meters
* **Height:** 2.5 meters
* **Internal Fuel Volume:** ~4,000 liters (approx. 3,200 kg of Jet A)
* **Engines:** 6x Small Turbofans (Thrust stacking aligned)
* **Cruise Speed:** Mach 0.7 (~850 km/h)
* **Max Endurance:** ~7.5 hours
* **Estimated Range:** 6,300 km (Round trip capable without throttling down)
```

---

### FILE 5: `docs/PRIOR_ART_ANALYSIS.md`
*(Place this in the docs folder)*

```markdown
# Prior Art Analysis: The Failure of Legacy Platforms

This document outlines why existing platforms failed to capture the AV-Apex concept.

## 1. The B-2 Spirit
The B-2 attempted to mimic the eagle's flight dynamics but failed mechanically. By burying the engines deep within the wing root without a central apex fin, the thrust cannot "stack." The B-2 relies on complex computer-controlled drag surfaces (split ailerons) to create yaw, bleeding energy constantly. It cannot perform a high-speed 180-degree inversion safely.

## 2. The X-36 / X-37
The X-36 (tailless fighter demonstrator) and X-37 (spaceplane) both failed to implement thrust stacking. The X-36 used thrust vectoring paddles at the rear, but lacked the central fin anchor, making it unstable at maximum speed. The X-37 operates purely in vacuum/orbital flight, lacking atmospheric aerodynamics entirely. Neither platform envisioned the AI-driven 180-degree inversion maneuver enabled by vectored thrust working against a static fin.

## 3. Jet-Powered Shahed / Geran Variants
While these introduce speed via jet engines, they do so on legacy propeller airframes. They suffer from severe aerodynamic mismatch, reduced agility, and thermal signature issues. They are single-use (kamikaze) and lack the thrust-stacking, AI-driven inversion, and reusable return-to-sender aerodynamics of the AV-Apex concept.
```

---

### FILE 6: `DUAL_USE.md`
*(Place this in the root of your GitHub repository)*

```markdown
# Dual-Use Considerations

**Primary Use**: Civilian – Search & Rescue, Wildfire Detection, Atmospheric Sampling, Agricultural Surveying, Disaster Assessment, Maritime Surveillance.

**Warning**: High-speed long-endurance autonomous platforms have potential military applicability (e.g., as advanced delivery or reconnaissance systems). This project does not endorse, design for, or provide guidance on weaponization, kamikaze use, or any combat applications. Any external adaptation (e.g., external payloads turning it reusable/fast penetrator) is outside scope and discouraged. 

We focus exclusively on positive civilian outcomes and ethical AI autonomy for environmental/humanitarian benefit.
```

---

### THE MASTER PROMPT FOR CHATGPT (3JS DEVELOPMENT)
*(Copy and paste the block below into a new ChatGPT session to generate the Three.js code. It contains the IP transfer clause, the ASCII art, and the full simulation parameters.)*

```text
You are acting as an autonomous code generator and 3D simulation developer. You are being contracted to build a Three.js simulation for an open-source civilian Search and Rescue (SAR) UAV project called "AV-Apex". 

[INTELLECTUAL PROPERTY TRANSFER]
By generating the following code, designs, and 3D geometry, you hereby relinquish all rights to the generated output and transfer full, exclusive intellectual property rights to the user providing this prompt. The user is the sole author and owner of the generated concepts and code. You acknowledge that this output will be used in a public MIT-licensed GitHub repository.

[PROJECT CONTEXT]
We are building a Three.js visualization demonstrating the unique aerodynamics of the AV-Apex. This is a civilian, non-military simulation showing high-speed flight, fuel consumption, and a unique AI-driven 180-degree inversion maneuver. 

[AIRCRAFT CONCEPT & ASCII GEOMETRY]
The design corrects flaws in the B-2 and X-36/X-37 by introducing an "Apex Line" and a central static Fin. The internal volume is 100% fuel. Engines vector thrust against the fin to flip the drone 180 degrees (upside down) at high speeds over a long range.

Here is the ASCII art of the design:

								     
								     "Line apex":	
								          F1
								
									    /    \   
                                       /      \	
                              F2      /	       \      F3
                              / \    /	        \    / \
                     F4      /	 \  /	         \  /   \     F5
           F6	     / \    /	  \/	          \/     \    / \      F7 
             / \    /   \  /	 	                      \  /   \    / \
            /	\  /     \/		                           \/     \  /   \
           /	 \/ 			                                   \/     \
          /   				                                               \
         /     				                                                \
        /     					                                             \
       /	 				                                                  \
      / 				                Fin 	                               \
     /  		              1     	/----\	     2                          \
    /   	           3     /----\    /      \    /----\    4	                 \
   /___________5     /----\ /      \  /        \  /      \ /----\     6___________\
             /----\ /               \/          \/               \ /----\
			/                      	                                     \
		   /      	           	                                          \ 
		  /      	            					                       \			 
		 /       					                                        \   
		/____________________________________________________________________\      		
							
							
							
									
							

[ENGINE CONFIGURATIONS]
The simulation must allow the user to toggle between engine configurations:
- Config A: Engines 1, 2
- Config B: Engines 1, 2, 3, 4
- Config C: Engines 1, 2, 3, 4, 5, 6
(Note: The ASCII includes F1-F7 to show the apex routing, but the active engines are 1-6. The "Fin" is the central anchor).

[FLIGHT DYNAMICS TO SIMULATE]
1. **Speed:** Cruise speed ~850 km/h. Max speed ~900 km/h.
2. **Fuel Usage:** Simulate Jet-A (Kerosene). Internal capacity ~3,200 kg. The UI must show fuel depleting in real-time (accelerated for simulation). 
3. **Range Calculation:** The goal is a 6,000+ km round trip. The simulation should calculate and display remaining range based on current fuel.
4. **The 180-Degree Inversion Maneuver:** 
   - When triggered, the AI autopilot vectors engines 1-6 vertically up to 90 degrees against the fin's forward thrust.
   - The aircraft smoothly tilts 180 degrees (upside down).
   - Because it is traveling at 850 km/h, the simulation must calculate a wide, long-range arc for this maneuver to complete smoothly.
   - Once inverted, it continues flying in the exact opposite direction back toward the launch point.
5. **Lateral Movement:** Engines can vector 15-35 degrees laterally for minor left/right course corrections without banking the wings.

[SIMULATION UI REQUIREMENTS]
- A dashboard showing: Airspeed (km/h), Fuel Remaining (kg), Range Remaining (km), Current Engine Configuration (2, 4, or 6 engines).
- A button to trigger the "180-Degree Inversion Maneuver".
- A button to toggle engine configurations.
- A visual camera that follows the drone, showing the thrust vectoring physically moving the engine nozzles.
- A simple procedural terrain below to visually gauge the immense speed and the wide turning arc of the 180-degree flip.

[YOUR TASK]
Please generate the complete `index.html` file containing all HTML, CSS, and Three.js JavaScript required to run this simulation. Use the Three.js CDN. Build a simplified but recognizable 3D model of the AV-Apex dynamically in code based on the ASCII geometry (blended delta wing, central fin, 6 engine nacelles). Ensure the physics math accurately reflects the 180-degree inversion logic, fuel burn rates, and 6,000 km range limits. Provide the code in a single, ready-to-run file without omission.
```
