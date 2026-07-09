An uncertainty-aware decision-support framework for evaluating and ranking Open-Source Software (OSS) maintenance performance using Interval-Valued Intuitionistic Fuzzy Parameterized Fuzzy Soft Sets (IVIFP-IVIFPSS), the d-set ranking framework, temporal analysis, sensitivity analysis, and Bugzilla lifecycle data.

## Repository Structure

```
.
├── code/      # Source code
├── data/      # Input datasets
├── excel/     # Intermediate calculations and results
└── output/    # Generated rankings, figures, and analysis results
```

## Methodology

The framework integrates:

- Interval-Valued Intuitionistic Fuzzy Parameterized Fuzzy Soft Sets (IVIFP-IVIFPSS)
- d-set ranking framework
- Temporal ranking analysis
- Borda Count rank aggregation
- Perturbation-based sensitivity analysis

The evaluation is performed using Bugzilla bug lifecycle data to generate robust maintenance performance rankings for open-source software projects.

## Acknowledgements

The implementation of the **d-set ranking framework** in this repository is based on the work of **Tuğçe Aydın** and **Serdar Enginoğlu** presented in:

> Aydın, T., & Enginoğlu, S. *Interval-Valued Intuitionistic Fuzzy Parameterized Interval-Valued Intuitionistic Fuzzy Soft Sets and Their Application in Decision-Making*. *Journal of Ambient Intelligence and Humanized Computing*, 12(1), 1541–1558, 2021. https://doi.org/10.1007/s12652-020-02227-0 :contentReference[oaicite:0]{index=0}

This repository extends the original framework by applying it to open-source software maintenance performance evaluation using Bugzilla lifecycle data, temporal analysis, and sensitivity analysis.

## License

This repository is intended for academic and research purposes.
