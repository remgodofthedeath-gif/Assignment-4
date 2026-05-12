# Assignment-4
Nynyan
Game Overview: Scrap & Skull
Scrap & Skull is a high-octane, top-down survival shooter set in a decaying urban wasteland. Players must navigate claustrophobic alleyways and desolate warehouses to retrieve vital supply crates. The goal is simple: Get the boxes, kill anything that groans, and reach the extraction point alive.

The AI & Task System
The game utilizes a Dynamic Threat Engine to manage the zombie hordes and player objectives:

Horde Behavior: Zombies use a "scent and sound" logic. Firing a weapon or running creates noise ripples that attract nearby AI. If you stay in one spot too long, the AI triggers a "Pincer Maneuver," spawning zombies from multiple directions to prevent camping.

The Scavenge Loop: The Task System tracks your inventory in real-time. Collecting a box isn't just a stat change—it adds weight to your character, slightly slowing your movement speed and increasing the "noise" you make, raising the stakes for every successful find.

Feedback Integration
To keep the player immersed and informed, the game uses multi-sensory feedback:

Visual Cues: The screen edge pulses red based on proximity to threats. Supply boxes emit a faint golden pulse, and your weapon's muzzle flash illuminates dark corners, momentarily revealing hidden enemies.

Haptic & Audio: A distinct "metallic thud" plays upon collecting a box, accompanied by a controller vibration. As your health drops, the game audio becomes muffled, replaced by the sound of a heavy heartbeat to signal urgency.

Level Overview: The Dead Depot
The primary level is a multi-layered industrial shipyard.

Zone 1 (The Yards): Wide-open spaces with high visibility but very little cover.

Zone 2 (The Warehouse): A maze of shipping containers where supply boxes are hidden. Tight corners make shotguns essential.

Zone 3 (Extraction): A rooftop helipad that requires the player to hold their ground for 60 seconds while the extraction timer counts down.

Controls
Action	Input (PC)	Input (Console)
Move	W A S D	Left Stick
Aim	Mouse Movement	Right Stick
Shoot	Left Click	RT / R2
Reload	R	X / Square
Interact / Pick up Box	E	A / Cross
Sprint	Left Shift	L3 (Click Stick)
Melee Push	V
