# Neuro SandBox

Neuro Sandbox allows users to construct small neural networks composed of excitatory and inhibitory neurons directly from their iOS device, connect them with weighted synapses, and observe how activity propagates through the network over time.

The app focuses on emergent dynamics, showing how simple local rules can lead to stable activity, oscillations, or runaway excitation.

All simulation and visualization runs fully on-device.

## Summary
	•	Neurons are modeled using a rate-based framework
	•	Firing rate is computed from a basal rate plus weighted excitatory and inhibitory drives
	•	Synaptic inputs decay over time using adjustable decay constants
	•	Optional Hebbian learning strengthens synapses when pre- and post-synaptic neurons fire within a short temporal window
	•	Activity is clamped to prevent unbounded firing while still allowing runaway dynamics to emerge

This design prioritizes conceptual clarity and real-time interaction over biological detail.

## Features
	•	Build and visualize neural networks interactively
	•	Excitatory and inhibitory neuron types
	•	Adjustable basal firing rates, synaptic weights, and decay parameters
	•	Live firing rate visualization and temporal history plots
	•	Optional Hebbian learning
	•	Automatic detection and explanation of runaway network activity
	•	Runs entirely on-device with no external dependencies

## Intended Use
	•	Educational demonstrations in neuroscience and computational neuroscience
	•	Rapid intuition building for network dynamics
	•	Exploring the effects of excitation–inhibition balance
	•	Visualizing feedback loops and stability in small networks

## Support
For questions or feedback:  
**Email:** neurosandbox.app@gmail.com

## Privacy
Neuro SandBox does not collect or store personal data.  
All simulations run locally on your device.

## Developer
Michael C. Marone

## Copyright
© 2026 Michael C. Marone. All Rights Reserved.
