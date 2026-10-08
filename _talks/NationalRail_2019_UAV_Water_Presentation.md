---
title: "National Rail Demonstration — Autonomous UAV Water Detection and Sampling"
collection: talks
type: "Invited Demonstration"
venue: "National Rail Industry Visit, University of Sussex"
date: 2019-11-15
permalink: /talks/national-rail-2019/
excerpt: "Invited demonstration for National Rail showcasing an autonomous UAV system for water-body detection, descent, sampling, and return-to-base behaviour."
---

During my PhD, I was invited to present a live demonstration to National Rail during their visit to the University of Sussex. The demonstration showcased an autonomous UAV system capable of detecting water bodies using onboard RGB imagery, descending to perform sampling, and returning to base, illustrating how autonomous drones could support large-scale environmental monitoring.

Context:

National Rail were exploring UAV-based monitoring solutions for sections of their network affected by frequent cliff drops and unstable terrain. Existing helicopter-based inspections were costly and infrequent, motivating interest in autonomous, low-cost aerial monitoring systems.

Demonstration:

* Developed a MATLAB simulation of an autonomous UAV that:
  * Searches an area for water bodies using RGB imagery,
  * Detects water via texture and colour cues,
  * Hovers above the detected region,
  * Descends to sampling height,
  * Autonomously returns to base.

* Programmed a Parrot Mambo drone to replicate this behaviour in a live indoor demonstration:
  * Drone hovered until detecting a blue surface (representing a water body),
  * Descended towards the target,
  * Stabilised at low altitude,
  * Returned to its starting position.

Technical features:

* Physics-aware water detection using texture cues (surface smoothness, reflections).
* Real-time image processing and autonomous control loops.
* Integration of perception, decision-making, and flight control.
* Demonstration of autonomous UAV behaviour without manual piloting.

Impact:

* Showcased how autonomous UAVs could support continuous, low-cost monitoring of critical infrastructure.
* Demonstrated practical translation of computer vision research into robotics.
* Provided National Rail with a proof-of-concept for UAV-based inspection workflows.
* Highlighted the potential for autonomous systems to replace expensive helicopter-based monitoring.
