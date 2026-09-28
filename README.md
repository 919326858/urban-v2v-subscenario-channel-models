## Overview

This repository provides supplementary channel-model parameters and for the paper:

"Sub-Scenario Channel Modeling and Lightweight CNN Identification for
Urban V2V Communications."

The channel models are derived from an urban V2V measurement campaign
conducted at a center frequency of 1.41 GHz. Four representative sub-scenarios are considered:

- Urban Edge
- Urban Canyon
- Urban LOS
- Urban NLOS

- ## Measurement Configuration

- Center frequency: 1.41 GHz
- Measurement bandwidth: 20 MHz
- Sounding sequence: Zadoff-Chu sequence
- Sequence length: 4096
- Snapshot duration: 204.8 us
- Number of measurement routes: 4
- Valid snapshots per sub-scenario: approximately 200,000

- ## Channel Models

Measurement-derived multipath parameters were extracted using the SAGE
algorithm. The resulting channel statistics were used to construct
scenario-specific tapped-delay-line (TDL) channel models.

The complete model parameters for the four sub-scenarios are provided
in the `TDL_models` directory.
