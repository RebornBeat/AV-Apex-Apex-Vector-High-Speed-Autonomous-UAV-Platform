# AI & Autonomy Stack

## 1. Pilotless Advantage
Human physiological limits restrict traditional fighter maneuvers to roughly 9 Gs. The AV-Apex, being entirely pilotless, can execute wide-arc inversions at 12–15 Gs, allowing it to maintain 850 km/h during a heading reversal where a human-piloted aircraft would have to bleed speed or risk blacking out.

## 2. Flight Control System (FCS) Logic
The AI does not use traditional aerodynamic control surfaces (ailerons, elevators) for primary maneuvers. Instead, it uses pure differential thrust vectoring.
* **Pitch (Inversion):** All 6 engines vector 90° vertically against the Fin. The AI modulates throttle to ensure a perfectly smooth arc, preventing flat spin.
* **Yaw (Lateral):** Engines vector 15–35° laterally. Because the thrust is stacked, even a 15° vector on all 6 engines creates a massive lateral shift without banking the wings.
* **Roll:** Differential vectoring between engines 1/3/5 (left) and 2/4/6 (right) induces roll without aileron drag.

## 3. CG Management Algorithm
The AI constantly monitors the fuel state across F1–F7. As fuel burns, the AI shifts fuel between the nodes to keep the Center of Mass perfectly aligned with the Center of Lift. During the 180° inversion, the AI pre-emptively shifts fuel to the nose (F1) to ensure the arc is smooth and the drone does not tumble end-over-end.

