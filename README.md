# Compute in Transit 02 — Data Movement in LLM Training

What each kind of parallelism puts on the wire, how large a gradient sync is and where links bind; in-network aggregation (SwitchML, SHARP), low-communication training (DiLoCo, Streaming DiLoCo, MuLoCo, SparseLoCo), and frequency-domain compression of gradients and momentum (FFT sparsification, DeMo); how DeMo maps onto a photonic link module whose operation set has the DCT but not top-k, and a planned experiment and simulation to test a fixed frequency band in its place.

Topics: Ring all-reduce, In-network aggregation, DiLoCo, DeMo, DCT compression, Fixed band vs top-k.

**Live site:** https://brendanjameslynskey.github.io/CiT_02_Data_Movement_in_LLM_Training/

Part of the [Compute in Transit series](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit). Every number comes from [analysis/results.md](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit/blob/main/analysis/results.md), written by [analysis/cit_budget.py](https://github.com/BrendanJamesLynskey/LLM_Hub_Compute_in_Transit/blob/main/analysis/cit_budget.py), or from the papers cited on the slides; illustrative figures are labelled, and the fixed-band experiment is marked as planned. Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/LLM_Hub_Compute_in_Transit/#glossary). Sister series: [Fourier Optics for Inference](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference), [LLM Inference Simulators](https://github.com/BrendanJamesLynskey/LLM_Hub_Inference_Simulators), [FHE Accelerator Simulators](https://github.com/BrendanJamesLynskey/FHE_Hub_Accelerator_Simulators).

Licence: CC BY 4.0.
