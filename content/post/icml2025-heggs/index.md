---
title: ICML 2025 - 1 paper accepted
summary: 'Broadband Ground Motion Synthesis by Diffusion Model with Minimal Condition'
date: 2025-05-13
authors:
  - admin
# tags:
#   - Hugo Blox
#   - Markdown
image:
  caption: 'ICML 2025 @ Vancouver, Canada'
---


## Simulating Earthquakes with AI: A New Era in Seismic Safety

When an earthquake strikes, the ground shakes in complex ways. Accurately simulating these motions is key to designing safer buildings, improving early warning systems, and understanding our planet’s interior. But here’s the challenge: large earthquakes are rare, and collecting real seismic data is expensive and limited.

{{< spoiler text="View laypeople introduction" >}}


### The Innovation: HEGGS
To overcome this, the research team introduced HEGGS—short for High-fidelity Earthquake Groundmotion Generation System. It’s an AI model that learned historical earthquakes to create realistic 3D earthquake waveforms using just a few (minimal) facts about an earthquake quake:

- Where the earthquake started (latitude, longitude, and depth)
- Its strength (magnitude)
- Where the ground motion is being recorded (station location)

That’s it—**no extra geological details needed!**

### How Does It Work?
HEGGS makes best use of a cutting-edge AI technique called diffusion model, originally designed for generating high-quality images (like those you see in modern AI art tools). Instead of pictures, this system learns to generate earthquake shockwaves, i.e. vibrations recorded at seismic stations.

When trained on real earthquake data from North America, East Asia, and Europe, HEGGS learns what the earthquake shockwaves “look like” on seismographs, and generates scientifically realistic earthquake waveforms. 

### How Good Is It?
**HEGGS outperforms existing methods** in many aspects:

- More accurate arrival times for seismic waves
- Better match to real waveforms in shape, noise levels, and energy distribution
- Strong performance even when generating earthquakes with only minimal input data
- Visual tests and scientific metrics confirm that HEGGS-generated waveforms closely resemble real earthquake data 

### Why It Matters

- Smarter Simulations: HEGGS can generate realistic seismic waves even for hypothetical earthquakes (ones that haven’t happened yet).
- Better Early Warnings: Because it models wave arrival times very precisely, it could help improve alert systems that warn people before the shaking starts.
- Safer Infrastructure: Engineers can simulate ground shaking in areas without much historical data, leading to better-informed construction.

HEGGS could become a vital tool in saving lives and protecting communities around the world.

{{< /spoiler >}}

Click to [know more about the research]({{< relref "/publication/2025ICML-jung-lee-jung-kim-jung-lee" >}}).
