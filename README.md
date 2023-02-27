# remap_WOA18
remapping of WOA18 for ocean model use.

Quick Start Guide
-----------------

```bash
conda env create -f woa18remap.yml
conda activate woa18remap
python -m ipykernel install --user --name woa18remap --display-name "woa18remap"
jupyter-lab
```

| Notebook | Blend monthly data with ? for full depth | Version of WOA | Uses ? for EOS |
| --- | --- | --- | --- |
| Process_WOA2018.ipynb                | ANN  | 2018  | seawater |
| Process_WOA2018_blend-ANN.ipynb      | ANN  | 2018  | GSW |
| Process_WOA2018_blend-MON_SEAS.ipynb | SEAS | 2018  | GSW |
| Process_WOA2023_blend-MON_SEAS.ipynb | SEAS | 2023  | GSW |
