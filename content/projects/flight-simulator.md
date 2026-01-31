---
title: "Autonomous Flight Simulator"
summary: "ML-Agents powered aircraft that learns to take off and land"
description: ""
cover: "/img/flight-sim.jpg"
coverGif: "/img/flight-sim.gif"
coverAlt: "Autonomous Flight Simulator"
weight: 3
---

## Overview

An arcadey flight simulation project without the use of unity's built in physics. The simulator features classic flight controls and a neural network trained to autonomously perform landings.

## Technical Details

I engineered custom flight physics using a system of composite colliders to simulate realistic aircraft movements. The autonomous pilot was trained using Unity ML-Agents, with a reward function designed to encourage, stable landings only from knowing it's own position and the position of the airstrip.

---

**Technologies:** Unity, C#, ML-Agents  
**Repository:** [GitHub](https://github.com/BenjaminEmag/Flight-Simulator)