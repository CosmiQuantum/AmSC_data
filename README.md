# CosmiQ — Public Datasets

Experimental data from the CosmiQ group (Fermilab/IIT/Northwestern), hosted on the [American Science Cloud (AmSC)](https://amsc.energy.gov/).

## Datasets

| Dataset | `<dataset>` | Description | Link |
|---------|------------|-------------|------|
| **NEXUS Run 22** | `nexus_run_22` | Charge tomography scans from superconducting qubits, 107 m underground at Fermilab. First measurement of correlated charge jumps in a controlled underground radiation environment. [[paper]](https://www.nature.com/articles/s41467-025-63724-4) | [Browse](https://amsc.fnal.gov:2880/amsc/public/cosmiq/nexus_run_22/) |

More datasets from the NEXUS, QUIET, and LOUD testbeds will be added here as they become available.

## Accessing the data

Data is hosted on the AmSC through Fermilab. Browsing via the web may require **FNAL SSO** credentials.

To download from the command line:

```bash
curl -L https://amsc.fnal.gov:2880/amsc/public/cosmiq/<dataset>/
```

## Citation

If you use any of these datasets, please cite the relevant paper listed in the table above.

## Related work

- [NVIDIA Ising open models](https://nvidianews.nvidia.com/news/nvidia-launches-ising-the-worlds-first-open-ai-models-to-accelerate-the-path-to-useful-quantum-computers) — AI models for quantum computing, trained in part on CosmiQ data
- [SQMS Center](https://sqms.fnal.gov/) — Superconducting Quantum Materials and Systems Center at Fermilab

## Contact

For questions about the data or access issues, please [open an issue](https://github.com/CosmiQuantum/AmSC_data/issues) on this repository.
