# Lightweight Guitar Amp Modelling – Neural Networks + Impulse Responses

## Overview
This repository contains early-stage experiments in building lightweight guitar amp models using neural networks and impulse responses. The aim is to reduce CPU usage compared to existing amp simulation plugins, making it suitable for real-time use in DAWs and eventually as a standalone solution.

The work builds upon research and methodologies initiated by Steven Atkinson, especially drawing inspiration from the Neural Amp Modeler (NAM) project.

## Approach
- **Neural Network Architectures:** Focused on efficiency and tone accuracy.
- **Impulse Response Integration:** Exploring hybrid models combining IRs with neural nets.
- **Frameworks Used:**
  - PyTorch
  - Neural Amp Modeler (NAM) for reference and benchmarking

## Project Goals
- Reduce CPU overhead while maintaining high-quality amp tone.
- Create a real-time capable model for use inside DAWs.
- Build a foundation for future commercial plugin development.

## Current Status
- One working notebook with core model experiments.
- Real-time integration and standalone development planned for future phases.

## How to Use
Clone the repository and open the provided Colab or local Jupyter notebook:

## Credits:
Steven Atkinson for creating the neural amp modeler and making it open source: https://www.neuralampmodeler.com/

```bash
git clone https://github.com/yourusername/lightweight-amp-modelling
cd lightweight-amp-modelling
# Open notebook.ipynb
